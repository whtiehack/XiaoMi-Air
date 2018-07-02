# XiaoMi NoteBook Air for macOS High Sierra & Sierra

让你的小米AIR笔记本吃上黑苹果


## 完美度

* 触摸板基本满足日常使用
    * 触摸板灵敏度很完美。
    > 单指轻点
    > 双指轻点（右键）
    > 单指双击拖拽
    > 双指滚动
* 完美电源管理
    * 插入电源亮度提高，拨出电源亮度降低. 
    * 续航与win10下没有什么差别，个人感觉MAC下续航还有增加。
* 正常睡眠，正常唤醒，唤醒后USB正常
    * 需要取消勾选节能中的`如果可能，使硬盘进入睡眠`。
* 集显完美，界面没有任何卡顿。
* iMessage,FaceTime 正常登录
* Siri 正常使用。
* 声卡麦克风完美.
    * 耳机需要把声音平衡调到右。
* HiDPI 正常




## 已知问题

* 自带蓝牙与WIFI不支持。蓝牙已屏蔽
* 独显不支持。已屏蔽
* 集显还需要优化。HiDPI分辨率下打开启动台偶尔有掉帧的感觉。
* 键盘亮度调节没有用，可以通过`偏好设置->显示器`来调节亮度。
    * 就是没有小太阳 F4 F5 调节亮度无用`F14 F15` 按键不识别
    * 解决方法： [调整快捷键](http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1737010&highlight=)
        > 系统偏好设置-键盘-快捷键  把亮度调节快捷键改成 ctrl+,（ctrl+<），ctrl+.（ctrl+>）即可
* 触摸板不支持多手势.不支持放大缩小
* 睡眠可以正常唤醒，但是唤醒以后USB设备都不识别了。
    * 目前发现的解决方式，需要取消勾选节能中的`如果可能，使硬盘进入睡眠`。

## 支持列表

* 支持10.13.5
* CPU为原生支持
* 显卡仿冒支持，platform-id为0x19160000，注入信息通过 `config.plist` 注入

## 已测试的版本

* 小米笔记本 Air 13.3 不带指纹版本   i5-6200U 
    * 经测试，续航能力没有问题。
    * ![942d2425-669e-4d09-9ba9-5dc4b8ab087e](https://user-images.githubusercontent.com/12741016/41816633-99064fd4-77bc-11e8-94c7-0bca09d0796f.png)
    * 
    * <img width="254" alt="wx20180624-145516 2x" src="https://user-images.githubusercontent.com/12741016/41816757-9bb89b6c-77bf-11e8-8392-5a5c731e67a9.png">
    




## 安装

* 推荐使用 10.13.5 镜像    
    * [10.13.5镜像](https://blog.daliansky.net/macOS-High-Sierra-10.13.5-(17F77)-Release-Version-with-Clover-4512-original-mirror.html)
    * 制作完安装盘 把U盘的EFI删除掉，换上这个库的EFI。
    * EFI 下载 [EFI Release](https://github.com/whtiehack/XiaoMi-Air/releases)


具体安装流程请参考详细的小米Pro安装教程（中文版）[macOS安装教程兼小米Pro安装过程记录](https://blog.daliansky.net/MacOS-installation-tutorial-XiaoMi-Pro-installation-process-records.html).

## WIFI

目前的解决方式是使用 USB WIFI。

* 支持小米随身WIFI 驱动在 Drivers目录 `RT2870-小米wifi驱动.zip`[下载](https://github.com/whtiehack/XiaoMi-Air/raw/master/Drivers/RT2870-%E5%B0%8F%E7%B1%B3wifi%E9%A9%B1%E5%8A%A8.zip) 有详细的使用说明
    * <img width="830" alt="wx20180624-150423 2x" src="https://user-images.githubusercontent.com/12741016/41816774-ef3dc064-77bf-11e8-978e-388e5f88e0cc.png">

* 其它版本的WIFI 可以自己找驱动，或者淘宝免驱的USB WIFI

## 开启 HIDPI 

使用 `HIDPI for Mi Air` 完美解决。

使用方法在 `HIDPI for Mi Air` 内的README 内。

简单流程:

* 打开 终端 `Terminal.app`
* 输入 cd 
* 把 你下载的 `HIDPI for Mi Air` 解压后的文件夹拖 终端。
* 按回车
* 输入 `./hidpi.sh` 回车
* 输入 `.install.command` 回车

* * <img width="684" alt="2018-06-29 23 23 22" src="https://user-images.githubusercontent.com/12741016/42100766-ab926918-7bf3-11e8-957c-a83419bcb23e.png">


## 洗白（正常使用`iMessage`,`FaceTime`）

* 教程可以看这里。[教程](http://www.vmengblog.com/hackmacimessage/)


iMessageDebug `imessage_debug` 下载 [iMessageDebug](https://github.com/whtiehack/XiaoMi-Air/raw/master/iMessageDebug.zip)

## 支持与讨论

* 小米PRO黑苹果 QQ群:
  * 247451054 [小米PRO黑苹果高级群](http://shang.qq.com/wpa/qunwpa?idkey=6223ea12a7f7efe58d5972d241000dd59cbd0260db2fdede52836ca220f7f20e)
  * 137188006 [小米PRO黑苹果](http://shang.qq.com/wpa/qunwpa?idkey=c17e190b9466a73cf12e8caec36e87124fce9e231a895353ee817e9921fdd74e)

> 入群口令 `blog.daliansky.net`

* 小米黑苹果 QQ群:
    * 667951858

## EFI完全参考了 Xiaomi Pro 的 EFI

感谢 [stevezhengshiqi的小米Pro EFI](https://github.com/stevezhengshiqi/XiaoMi-Pro)

