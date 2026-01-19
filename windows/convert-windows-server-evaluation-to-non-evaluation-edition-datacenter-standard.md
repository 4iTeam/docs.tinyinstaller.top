# Convert Windows Server Evaluation to Non-Evaluation Edition (Datacenter / Standard)

Important notice:\
The product keys used in this guide are official Microsoft-provided setup (generic) keys.\
They are used only to change the Windows Server edition from Evaluation to non-evaluation.\
These keys do NOT activate Windows and do NOT grant a license.\
A valid Windows Server license is still required for activation.

## Steps to do

* Launch a PowerShell as an Administrator

<figure><img src="../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

* Type DISM /online /Set-Edition:ServerDatacenter /ProductKey:{KEY-KEY-KEY-KEY-KEY} /AcceptEula and press ENTER

<figure><img src="../.gitbook/assets/image (45).png" alt=""><figcaption><p>Answer y to reboot</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption><p>After reboot, the Evaluation watermark will be removed.<br>Windows will remain unactivated until a valid license is provided.</p></figcaption></figure>

## Official Microsoft Setup Keys (for edition conversion only)

### Windows 2012R2 Datacenter

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:BH9T4-4N7CW-67J3M-64J36-WW98Y /AcceptEula`

### Windows 2016 Datacenter

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:CB7KF-BWN84-R7R2Y-793K2-8XDDG /AcceptEula`

### Windows 2019 Datacenter

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:WMDGN-G9PQG-XVVXX-R3X43-63DFG /AcceptEula`&#x20;

### Windows 2022 Datacenter

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:WX4NM-KYWYW-QJJR4-XV3QB-6VM33 /AcceptEula`&#x20;

### Windows 2022 Standard

`DISM /online /Set-Edition:ServerStandard /ProductKey:VDYBN-27WPP-V4HQT-9VMD4-VMK7H /AcceptEula`

### Windows 2025 Datacenter

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:D764K-2NDRG-47T6Q-P8T8W-YP6DF /AcceptEula`

<mark style="color:$danger;">Note:</mark>\ <mark style="color:$danger;">This process only changes the Windows Server edition.</mark>\ <mark style="color:$danger;">It does NOT activate Windows and does NOT provide a license.</mark>\ <mark style="color:$danger;">You must purchase a valid Windows Server license from Microsoft or an authorized reseller to activate the system.</mark>
