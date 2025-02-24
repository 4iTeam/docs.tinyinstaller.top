# Build install command

## Install command

Parameters:\
`setup_url`: Setup url which get from [License Info Api](api-requests.md#get-license-info)\
`key`: Setup key which get from [License Info Api](api-requests.md#get-license-info)

### Base command

```
({setup_url} -4O setup.sh || curl {setup_url} -Lo setup.sh) && bash setup.sh {key}
```

You will be asked to select image when run this command. To generate pre-selected image please check below section

### Pre-selected image command

Append -i={image\_id} to general command\
image\_id can be found in [Images Api](api-requests.md#get-images)

### Pre-confirmed command

Append -y to command

## Init Script

```
#!/bin/bash
tries=10
while [ $tries -gt 0 ] && ! { (wget {setup_url} -4O install.sh || curl {setup_url} -Lo install.sh); } ; do
    echo "Download failed, retrying $tries more times"
    tries=$((tries-1))
    sleep 10
    echo -e "nameserver 8.8.8.8\nnameserver 1.1.1.1" > /etc/resolv.conf
done
bash install.sh {key} -i={image_id} -y

```
