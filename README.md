# P4wnP1-A.L.O.A.-NOTES

[Exfiltrating Files With A Pi Zero | P4wnP1 A.L.O.A.](https://www.youtube.com/watch?v=I_BjCdJlCo4) 

[P4wnP1 A.L.O.A.](https://github.com/RoganDawes/P4wnP1_aloa) - [Download](https://github.com/RoganDawes/P4wnP1_aloa/releases) 

[[tutorial] How to connect P4wnP1 to Internet](https://www.youtube.com/watch?v=QEWaIoal5qU) 

[DEVICE INFO](https://www.myfakeinfo.com/mobile/get-android-device-information.php) 



Windows PowerShell
```
Get-NetConnectionProfile
```

```
Set-NetConnectionProfile -Name "Unidentified network" -NetworkCategory Private
```

Linux Terminal
```
sudo route add -net default gw 172.16.0.2
```

```
echo nameserver 8.8.8.8 > /etc/resolv.conf
```
