# win_privesc

## Features 

- [x] Get System Info
- [x] Get User and Group Info
- [x] Get Network Info
- [x] Check Insecure User Permission
- [x] Loot For Interresting File (files containing password)
- [x] Check Auto Login
- [x] Get PowerShell History
- [x] Get Process Info
- [x] Get Installed Software Info
- [x] Search Software Exploit (Should be connected to a kali machine and the IP address should me specified in $remote_check variable) at the top of the file
- [x] Get Tasks Info
- [x] Get Writable Auto Start Apps
- [x] Get Unquoted Services
- [x] Get Insecure Services
- [x] Get unusual Excutable File 
- [x] Get WSL Info
- [x] Get WSUS Info
- [x] Get Insecured Permission In Registry
- [x] Get Run As Apps
- [ ] Get Kernel Exploits 
- [x] Get unusual C Directory (for enumeration)
- [x] Get Alternate Data Stream files (for enumeration)
- [x] Get Potential Exploitable User Group

## How to run 
```
echo IEX(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/lucsemassa/win_privesc/main/win_privesc.ps1') | powershell -noprofile - 
```
