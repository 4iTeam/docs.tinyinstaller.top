# Convert Windows Server Evaluation To Datacenter



## Steps to do

* Launch a PowerShell as an Administrator

<figure><img src="../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

* Type DISM /online /Set-Edition:ServerDatacenter /ProductKey:{KEY-KEY-KEY-KEY-KEY} /AcceptEula and press ENTER

<figure><img src="../.gitbook/assets/image (45).png" alt=""><figcaption><p>Answer y to reboot</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption><p>There should be no evaluation text at the bottom right corner.</p></figcaption></figure>

## Windows 2012R2 Datacenter

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:BH9T4-4N7CW-67J3M-64J36-WW98Y /AcceptEula`

## Windows 2016 Datacenter

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:CB7KF-BWN84-R7R2Y-793K2-8XDDG /AcceptEula`

## Windows 2019 Datacenter

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:WMDGN-G9PQG-XVVXX-R3X43-63DFG /AcceptEula`&#x20;

## Windows 2022 Datacenter

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:WX4NM-KYWYW-QJJR4-XV3QB-6VM33 /AcceptEula`&#x20;

## Windows 2022 Standard

`DISM /online /Set-Edition:ServerStandard /ProductKey:VDYBN-27WPP-V4HQT-9VMD4-VMK7H /AcceptEula`

## Windows 2025 Datacenter

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:D764K-2NDRG-47T6Q-P8T8W-YP6DF /AcceptEula`

_<mark style="color:red;">**Note: This guide only changes the Edition of Windows Server; it doesn't mean you are licensed. You still need to buy a product key from Microsoft to activate your Windows Server.**</mark>_
