# Open Firewall on AWS

## Open Security Group

Select instance -> Security tab -> Click on security group

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

## Open a port

In security group click on Edit Inbound rules

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

Then click Add rule

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Fill infomation and save

Type: Custom TCP\
Port: 3389 (or your selected port in tiny)\
Source Anywhere IPv4

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

Verify that you see the added rule

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>
