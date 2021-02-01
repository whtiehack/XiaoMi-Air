

## XiaoMi NoteBook Air(6200U) for macOS Big Sur


让你的小米AIR笔记本吃上黑苹果

** 建议安装 的macOS版本:11.1   经过测试的:Mi-Air 13.3 i5-6200u **


> 在[前人的基础](https://github.com/sakoula/XiaoMi-Air-6200U)上做的修改.



## 完美度

整体使用非常流畅。

* WIFI 正常使用。（用的 AirportItlwm ，不需要装HeliPort）
* 蓝牙 可以正常使用（前提是WIFI连接5G）
* 触摸板基本满足日常使用
    * 触摸板灵敏度很完美。
    > 单指轻点
    > 双指轻点（右键）
    > 单指双击拖拽
    > 双指滚动
    > 支持缩放
* 正常睡眠，正常唤醒，唤醒后USB正常
    * 需要取消勾选节能中的`如果可能，使硬盘进入睡眠`。
* 完美的电池管理
* 集显完美，界面没有任何卡顿。
* iMessage,FaceTime 正常登录
* Siri 正常使用。
* 声卡麦克风完美.
* HiDPI 正常
* 键盘亮度和电量调节正常


## 已知问题

* 独显不支持。已屏蔽
* WIFI 有时候会丢包，但是不影响日常使用。等待新版本的[驱动](https://github.com/OpenIntelWireless/itlwm)解决
* [关机有问题](https://github.com/sakoula/XiaoMi-Air-6200U/issues/11)。关机以后需要自己按住电源键4秒来关闭


### 安装过程参考 [XiaoMi-Air-6200U](https://github.com/sakoula/XiaoMi-Air-6200U) 即可

* 如果是老版本升级 可以先在系统内下载好，重启安装之前直接换EFI即可（注意先备份好重要数据）
* 记得重置 Nvram
* 双系统没有问题. 安装不会影响现有的windows系统.注意EFI里不要删除 `Microsoft`

## 与 [sakoula](https://github.com/sakoula/XiaoMi-Air-6200U) 原始版本的区别

* wifi驱动用的是 `AirportItlwm`。
* 添加了一个驱动 `RestrictEvents.kext` (没发现有什么不同,可以取消)
* 更改了 wifi和蓝牙 驱动的加载顺序



> 感谢 [sakoula](https://github.com/sakoula)



