# Install Windows on AWS

## Step 1 - Generate init script from TinyInstaller

To get started, you need an active **TinyInstaller access key.**

#### Login to TinyInstaller

Go to https://tinyinstaller.top/login then Enter your access key to continue.

<figure><img src="../.gitbook/assets/tiny_login.png" alt=""><figcaption><p>Login</p></figcaption></figure>

#### Get Init Script

Then select Os and check Init Script

<figure><img src="../.gitbook/assets/image (18) (1).png" alt=""><figcaption><p>Get Init script</p></figcaption></figure>

## Step 2 - Create Windows VPS on AWS with Init Script

### Create new Instance

Login to AWS EC2 then click Launch instances

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Choose Location, Configration

Choose location and server size for your needed. Make sure you select **Ubuntu** one and increase **Storage.**

**Instance types supported**: _<mark style="color:green;">**T3, M5, C5, T2, C4**</mark>_

* T3, M5, C5 need special aws image [https://tinyinstaller.top/images?hl=en\&s=t3](https://tinyinstaller.top/images?hl=en\&s=t3)
* T2, C4: All other images

### Set the initialization script

Expand Advanced Options and Check Add Initialization scripts, then paste init script from TinyInstaller here

<figure><img src="../.gitbook/assets/image (5) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Create Instance

Select Quantity you want to create, make sure that not exceeded number of max Install Process allowed in your package. \
&#xNAN;_&#x45;xample: If you have 20 free process then we can create 20 instances_

<figure><img src="../.gitbook/assets/image (6) (2).png" alt=""><figcaption></figcaption></figure>

### Instance created

<figure><img src="../.gitbook/assets/image (8) (1).png" alt=""><figcaption></figcaption></figure>

After instance created we go back to TinyInstaller -> Install history to check install status

## Step 3 - Check install status

You can monitor install processes at [Install history](https://tinyinstaller.top/my-instances)

<figure><img src="../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

You can view status detail by click the link on status column

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Step 4 - Access to Windows

When installation done, you can copy IP address (include port), user/pass and access to RDP

<figure><img src="../.gitbook/assets/image (24) (1).png" alt=""><figcaption></figcaption></figure>

That's all, you now connect to windows via RDP. Everything is processed automatically.
