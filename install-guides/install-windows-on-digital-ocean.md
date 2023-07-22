# Install Windows on Digital Ocean

## Step 1 - Generate init script from TinyInstaller

You need to have license key first, if don't have let's buy one

#### Login to TinyInstaller

Go to https://tinyinstaller.top/login then enter your key

<figure><img src="../.gitbook/assets/image (12) (1).png" alt=""><figcaption><p>Login</p></figcaption></figure>

#### Get Init Script

Then select Os and check Init Script

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption><p>Get Init script</p></figcaption></figure>

## Step 2 - Create Windows VPS on Digital Ocean with Init Script

### Create new Droplet

Login to Digital Ocean then click Create -> Droplets

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption><p>Select Create -> Droplets</p></figcaption></figure>

### Choose Location, Configration

Choose location and server size for your needed. On Image make sure you select **Ubuntu** one

<figure><img src="../.gitbook/assets/image (22) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Set the initialization script

Expand Advanced Options and Check Add Initialization scripts, then paste init script from TinyInstaller here

<figure><img src="../.gitbook/assets/image (11) (1).png" alt=""><figcaption></figcaption></figure>

### Create Droplet

Select Quantity you want to create, make sure that not exceeded number of max Install Process allowed in your package. \
_Example: In this picture below we have 20 free process then we can create 20 instances_

<figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

### Droplet created

After droplet created we go back to TinyInstaller -> My Instances to check install status

<figure><img src="../.gitbook/assets/image (9) (1).png" alt=""><figcaption></figcaption></figure>

## Step 3 - Check install status

You can monitor install processes at [My Instances](https://tinyinstaller.top/my-instances)

<figure><img src="../.gitbook/assets/image (24) (1).png" alt=""><figcaption></figcaption></figure>

You can view status detail by click the link on status column

<figure><img src="../.gitbook/assets/image (23) (1).png" alt=""><figcaption></figcaption></figure>

## Step 4 - Access to Windows

When installation done, you can copy it and access to RDP

<figure><img src="../.gitbook/assets/image (31) (1).png" alt=""><figcaption></figcaption></figure>

That's all, you now connect to windows via RDP. Everything is processed automatically.
