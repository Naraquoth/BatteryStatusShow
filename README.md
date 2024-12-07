# BatteryStatusShow
### View detail battery information on OSX for IOS and MAC devices

![ pic1](/README/readme_pic1.png)
![ pic2](/README/readme_pic2.png)

#### Version 1.5.5
Support Monterey 
#### Version 1.5.41
Solve 1.5.4 unable change level 
#### Version 1.5.4
Support Big Sur and Xcode 12 (only support Intel Platform, not for Apple Silicon)
#### Version 1.5.3
fixed crash and show information of latest IOS devices (suppot IOS 13) 
#### Version 1.5.2
fixed crash for not found device description (Macbook 16) and stable improvement
#### Version 1.5.1
fixed crash by library dependencies issue
#### Version 1.5



##### 1. Updated view and change of Battery Change Limit Level (By modifiy of SMC, USE AS YOUR RISK!)

   
```
To change of Changing Limit, such 70% to stop change, 
start BatteryStatusShow > macOS > click change button next Charge Level
A dialog with a slider to adjust the changing level, default is 100% 
Click OK,input your sudo password on next dialog
Finish!
May need up to above one minutes to update the status.

Resume default value simple set to 100% or reset SMC
Tested under 10.15.4 Macbook Pro 2018, may or may not work on your model.
```
##### 2. Update macOS device detail
##### 3. Update IOS device detail


## Download compiled APP

[BatteryStatusShow_1.5.5.zip](/release/BatteryStatusShow_1.5.5.zip)

### Compiled
1. clone this git
2. compile smcutil scheme 
3. compile BatteryStatusShow scheme

Copyright (c) 2020 SC Lee. All rights reserved.

Libmobiledevice http://www.libimobiledevice.org
smcutil modify from https://github.com/RehabMan/OS-X-FakeSMC-kozlek







