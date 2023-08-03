# Convert Windows Server Evaluation To Datacenter



## Steps to do

* Launch a PowerShell as an Administrator

<figure><img src="../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

* Type DISM /online /Set-Edition:ServerDatacenter /ProductKey:{KEY-KEY-KEY-KEY-KEY} /AcceptEula and press ENTER

<figure><img src="../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

## Windows 2012R2

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:BH9T4-4N7CW-67J3M-64J36-WW98Y /AcceptEula`

## Windows 2016

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:CB7KF-BWN84-R7R2Y-793K2-8XDDG /AcceptEula`

## Windows 2019

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:WMDGN-G9PQG-XVVXX-R3X43-63DFG /AcceptEula`&#x20;

## Windows 2022

`DISM /online /Set-Edition:ServerDatacenter /ProductKey:WX4NM-KYWYW-QJJR4-XV3QB-6VM33 /AcceptEula`&#x20;
