# XiaoMi NoteBook Air for macOS High Sierra & Sierra

让你的小米AIR笔记本吃上黑苹果

## 完美度

* 完美睡眠
* 触摸板基本满足日常使用
    > 单指轻点
    > 双指轻点（右键）
    > 单指双击拖拽
* 完美电源管理
* 集显完美，界面没有任何卡顿。
* 


## 已知问题

* 自带蓝牙与WIFI不支持。蓝牙已屏蔽
* 独显支持。已屏蔽


## 支持列表

* 支持10.13 
* CPU为原生支持
* 显卡仿冒支持，platform-id为0x19160000，注入信息通过 `/CLOVER/ACPI/patched/SSDT-Config.aml` 加载
* 声卡为ALC298，采用AppleALC仿冒，layout-id为99，注入信息位于 `/CLOVER/ACPI/patched/SSDT-Config.aml`
* 其他ACPI补丁修复使用hotpatch方式，文件位于 `/CLOVER/ACPI/patched` 中

## 已测试的版本

> 小米笔记本 Air 13.3 不带指纹版本   i5-6200U 




## 安装

* 推荐使用 10.13.5 镜像    
    * [10.13.5镜像](https://blog.daliansky.net/macOS-High-Sierra-10.13.5-(17F77)-Release-Version-with-Clover-4512-original-mirror.html)
    * 制作完安装盘 把U盘的EFI删除掉，换上这个库的EFI。


具体安装流程请参考详细的小米Pro安装教程（中文版）[macOS安装教程兼小米Pro安装过程记录](https://blog.daliansky.net/MacOS-installation-tutorial-XiaoMi-Pro-installation-process-records.html).

## WIFI

目前的解决方式是使用 USB WIFI。

* 支持小米随身WIFI 驱动在 Drivers目录 `RT2870-小米wifi驱动.zip` 有详细的使用说明
* 其它版本的WIFI 可以自己找驱动，或者淘宝免驱的USB WIFI

## 支持与讨论

* QQ群:
  * 247451054 [小米PRO黑苹果高级群](http://shang.qq.com/wpa/qunwpa?idkey=6223ea12a7f7efe58d5972d241000dd59cbd0260db2fdede52836ca220f7f20e)
  * 137188006 [小米PRO黑苹果](http://shang.qq.com/wpa/qunwpa?idkey=c17e190b9466a73cf12e8caec36e87124fce9e231a895353ee817e9921fdd74e)

> 入群口令 `blog.daliansky.net`

