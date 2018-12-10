### Basic Setup for a legacy Cisco IOS

* Enable SSH on Cisco IOS 

```
crypto key generate rsa
username $USR privilige 15 password $PSWD
line vty 0 4
transport input ssh
login local
```
