# XiaoMi NoteBook Air for macOS High Sierra & Sierra

[中文导游](./README.md)

## What's working

* The touchpad is basically suitable for daily use
* Touchpad sensitivity is perfect.
  > Single finger tap

  > Two-finger tap (right click)

  > Single-finger double-click

  > Two-finger scrolling

* Perfect power management
  * The brightness of the inserted power supply is increased, and the brightness of the outgoing power supply is lowered.
* There is no difference between battery life and win10. Personally, there is an increase in battery life.
* Normal sleep, normal wake-up, normal USB after wake-up
  * You need to uncheck the `Put hard disks to sleep when possible`.
* The set is perfect, the interface does not have any stuck.
* iMessage, FaceTime login normally
* Siri is used normally.
* Sound card microphone is perfect.
  * The headphones need to adjust the sound balance to the right.
* HiDPI is normal




## Known issues

* Bring your own Bluetooth and WIFI is not supported. Bluetooth is blocked
* Independently does not support. Blocked
* Set display also needs to be optimized. Opening the launch pad at HiDPI resolution occasionally has the feeling of dropping frames.
* Keyboard brightness adjustment is not useful, you can adjust the brightness by `Preferences>> Display`.
  * There is no small sun F4 F5 Adjust brightness without use `F14 F15` button does not recognize
  * Solution: [Adjust shortcuts] (http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1737010&highlight=)
    > System Preferences - Keyboard - Shortcuts Change the brightness adjustment shortcut to ctrl+, (ctrl+<), ctrl+.(ctrl+>)
* The touchpad does not support multiple gestures. It does not support zooming in and out.
* Sleep can wake up normally, but USB devices are not recognized after waking up.
  * The solution currently found needs to be unchecked. If possible, make the hard disk go to sleep.

## Support list

* Support 10.13.5
* CPU is native support
* Graphics card phishing support, platform-id is 0x19160000, injection information is injected through `config.plist`

## Tested version

* Xiaomi notebook Air 13.3 without fingerprint version i5-6200U
  * After testing, there is no problem with endurance.
  * ![942d2425-669e-4d09-9ba9-5dc4b8ab087e](https://user-images.githubusercontent.com/12741016/41816633-99064fd4-77bc-11e8-94c7-0bca09d0796f.png)
  *
  * <img width="254" alt="wx20180624-145516 2x" src="https://user-images.githubusercontent.com/12741016/41816757-9bb89b6c-77bf-11e8-8392-5a5c731e67a9.png">
    




## Installation

* Recommended use 10.13.5 Mirror
  * [10.13.5 Mirror] (https://blog.daliansky.net/macOS-High-Sierra-10.13.5-(17F77)-Release-Version-with-Clover-4512-original-mirror.html)
  * Make the installation disk Delete the EFI of the U disk and replace it with the EFI of this library.
  * EFI Download [EFI Release] (https://github.com/whtiehack/XiaoMi-Air/releases)


For the specific installation process, please refer to the detailed Xiaomi Pro installation tutorial (Chinese version) [macOS installation tutorial and Xiaomi Pro installation process record] (https://blog.daliansky.net/MacOS-installation-tutorial-XiaoMi-Pro-installation-process -records.html).

## WIFI

The current solution is to use USB WIFI.

* Support Xiaomi portable WIFI driver in the Drivers directory `RT2870-Millet wifi driver.zip`[download](https://github.com/whtiehack/XiaoMi-Air/raw/master/Drivers/RT2870-%E5%B0%8F %E7%B1%B3wifi%E9%A9%B1%E5%8A%A8.zip) Detailed instructions for use
  * <img width="830" alt="wx20180624-150423 2x" src="https://user-images.githubusercontent.com/12741016/41816774-ef3dc064-77bf-11e8-978e-388e5f88e0cc.png">

* Other versions of WIFI can find drivers by themselves, or USB WIFI for Taobao free drive

## Open HIDPI

Perfectly solved with `HIDPI for Mi Air`.

Use the method in the README in `HIDPI for Mi Air`.

Simple process:

* Open the terminal `Terminal.app`
* Enter cd
* Drag the downloaded folder of the `HIDPI for Mi Air` you downloaded to the terminal.
* Press Enter
* Enter `./hidpi.sh` Enter
* Enter `.install.command` Enter
* <img width="684" alt="2018-06-29 23 23 22" src="https://user-images.githubusercontent.com/12741016/42100766-ab926918-7bf3-11e8-957c-a83419bcb23e.png">


## Enabling `iMessage` and `FaceTime`

* The tutorial can be seen here. [Tutorial] (http://www.vmengblog.com/hackmacimessage/)


iMessageDebug `imessage_debug` Download [iMessageDebug](https://github.com/whtiehack/XiaoMi-Air/raw/master/iMessageDebug.zip)

## Support and discussion

* Xiaomi PRO Black Apple QQ Group:
  * 247451054 [Xiaomi PRO Black Apple Advanced Group] (http://shang.qq.com/wpa/qunwpa?idkey=6223ea12a7f7efe58d5972d241000dd59cbd0260db2fdede52836ca220f7f20e)
  * 137188006 [Xiaomi PRO Black Apple] (http://shang.qq.com/wpa/qunwpa?idkey=c17e190b9466a73cf12e8caec36e87124fce9e231a895353ee817e9921fdd74e)

> The group password is `blog.daliansky.net`

* Xiaomi Black Apple QQ Group:
  * 667951858

## EFI fully referenced Xiaomi Pro's EFI

Thanks [stevezhengshiqi's Xiaomi Pro EFI] (https://github.com/stevezhengshiqi/XiaoMi-Pro)
