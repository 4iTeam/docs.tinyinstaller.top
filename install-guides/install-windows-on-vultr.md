# Install Windows on Vultr

## Step 1 - Generate init script from TinyInstaller

You need to have license key first, if don't have let's buy one

#### Login to TinyInstaller

Go to https://tinyinstaller.top/login then enter your key

<figure><img src="../.gitbook/assets/image (12) (1).png" alt=""><figcaption><p>Login</p></figcaption></figure>

#### Get Init Script

Then select Os and check Init Script

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption><p>Get Init script</p></figcaption></figure>

## Step 2 - Create Windows VPS on Vultr with Init Script

#### Login to Vultr Account

<figure><img src="../.gitbook/assets/image (21) (1).png" alt=""><figcaption></figcaption></figure>

#### Deploy Server

1. From vultr dashboard just click + or Deploy Server
2. Select any location and server size you want
3. At Server Image please make sure you select "**Debian**"

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption><p>Select Debian Image</p></figcaption></figure>

Enable Cloud-Init and paste init script which copy from step 1.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

Select Qty then click Deploy Now

Note: the number of servers should not exceed Max install process on your TinyInstaller's key

<figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

#### Wait for instances

<figure><img src="../.gitbook/assets/image (30) (1).png" alt=""><figcaption></figcaption></figure>

## Step 3 - Check install status

You can monitor install processes at [My Instances](https://tinyinstaller.top/my-instances)

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

## Step 4 - Access to Windows

When installation done, you can copy it and access to RDP

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

Open Remote Desktop Connection app

<figure><img src="../.gitbook/assets/image (29) (1).png" alt=""><figcaption></figcaption></figure>

Copy and input IP address need to copy port as well then click connect

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

Input credentials then click OK

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

That's all, you now connect to windows via RDP. Everything is processed automatically.
