# Install Windows on Linode

Install windows on Linode is not same with other providers, because we need to change boot setting to Direct Disk.

{% embed url="https://youtu.be/M9oUKKAFvzo" %}

<mark style="color:red;">**Note:**</mark>&#x20;

* If change to Direct Disk after status changed to "Installing" but before "Installed" => Don't need reboot
* If change to Direct Disk after status changed to "Installed" => Need reboot





***



We also able to use TinyInstaller's InitScript in Linode. If you want to use init script, please follow steps below

## Step 1 - Generate init script from TinyInstaller

To get started, you need an active **TinyInstaller access key.**

#### Login to TinyInstaller

Go to https://tinyinstaller.top/login then enter your key

<figure><img src="../.gitbook/assets/image (12) (1).png" alt=""><figcaption><p>Login</p></figcaption></figure>

#### Get Init Script

Then select Os and check Init Script

<figure><img src="../.gitbook/assets/image (18) (1).png" alt=""><figcaption><p>Get Init script</p></figcaption></figure>

## Step 2 - Create Stack Script

Goto StackScripts and click Create Stack Script

<figure><img src="../.gitbook/assets/image (13) (1).png" alt=""><figcaption></figcaption></figure>

Enter script (copy from Step 1) here, make sure you select Debian 11 in Target Images

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption><p>created scripts</p></figcaption></figure>

## Step 3 - Create Windows VPS on Linode with StackScript

In Linodes/Create screen select stack scripts tab then choose the stack which you created before

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

Click Create Linode to create

<figure><img src="../.gitbook/assets/image (28) (1).png" alt=""><figcaption></figcaption></figure>

After instance is running then go back to TinyInstaller -> My Instances to check install status

<figure><img src="../.gitbook/assets/image (15) (1).png" alt=""><figcaption></figcaption></figure>

## Step 4 - Check install status

Go to [My Instances](https://tinyinstaller.top/my-instances) you may check status there

<mark style="color:red;">**Please be patient and wait until you see your instance appear in the history list before moving to next step**</mark>

<figure><img src="../.gitbook/assets/image (6) (1).png" alt=""><figcaption></figcaption></figure>

## Step 5 - Update Direct Disk (important)

After instance appear in TinyInstaller website we need to update Configuration in Linode. There are 2 valid points to update:

* If TinyInstaller show "<mark style="color:green;">Installing</mark>" then just update to <mark style="color:green;">Direct Disk</mark>
* If TinyInstaller show "<mark style="color:blue;">Installed</mark>" then update to Direct Disk and <mark style="color:blue;">Reboot</mark>

<figure><img src="../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption><p>Edit Configuration</p></figcaption></figure>

Change Boot Setting to Direct Disk then Save Changes

<figure><img src="../.gitbook/assets/image (3) (1) (1).png" alt=""><figcaption></figcaption></figure>

Reboot instance

<figure><img src="../.gitbook/assets/image (5) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Wait it boots up and connect. It may take 10-15 min, please be patient. When you see Status changed to Done it's time to connect via RDP

<figure><img src="../.gitbook/assets/image (14) (1).png" alt=""><figcaption></figcaption></figure>

