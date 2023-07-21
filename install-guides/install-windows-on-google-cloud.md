# Install Windows on Google Cloud

## Step 1 - Generate init script from TinyInstaller

You need to have license key first, if don't have let's buy one

#### Login to TinyInstaller

Go to https://tinyinstaller.top/login then enter your key

<figure><img src="../.gitbook/assets/image (12) (1).png" alt=""><figcaption><p>Login</p></figcaption></figure>

#### Get Init Script

Then select Os and check Init Script

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption><p>Get Init script</p></figcaption></figure>

## Step 2 - Create Windows VPS on Google Cloud with Init Script

### Create new VM Instance

Login to Google Cloud then click CREATE INSTANCE

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

### Choose Location, Configration

Choose location and server size for your needed. Make sure **Disk Size** is enough to run Windows

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

### Set the initialization script

Expand Advanced Options- > Management, then paste init script from TinyInstaller into Automation - Startup script

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

### Create VM

Finally click CREATE button to create VM

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

### Instance created

After droplet created we go back to TinyInstaller -> My Instances to check install status

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

## Step 3 - Check install status

You can monitor install processes at [My Instances](https://tinyinstaller.top/my-instances)

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

You can view status detail by click the link on status column

<figure><img src="../.gitbook/assets/image (23) (1).png" alt=""><figcaption></figcaption></figure>

## Step 4 - Access to Windows

When installation done, you can copy it and access to RDP

<figure><img src="../.gitbook/assets/image (31) (1).png" alt=""><figcaption></figcaption></figure>

That's all, you now connect to windows via RDP. Everything is processed automatically.
