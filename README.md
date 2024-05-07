# p330-hackintosh
 lenove p330 tiny hackintosh
## BIOS
biso版本：M1VKT77A
CFG锁地址： 0x721

⚠️如果是低版本bios，需要先更新到最新bios：M1VKT77A

主机进入到bios以后，直接选择加载最优默认设置选项进行bios出厂设置。
随后，将biso的安全设置关闭以后就可以安装macOS系统了。

## 支持系统
macOS 12
macOS 13
macOS 14

## 驱动情况
睡眠唤醒：正常
Usb定制：完整
音频接口：正常
显卡驱动：uhd630 dp + hdmi 双屏支持
无线网卡：使用intel ax200无线网卡，价格便宜，还支持Wi-Fi6
蓝牙：目前没有放入驱动
## 主机 Model
![][image-1]

## EFI适用型号
P330/M920X/M920Q/M720Q
该efi使用uhd 630核显驱动

使用教程：
1. 先恢复bios到出厂设置，再关闭安全引导，并关闭cfg锁
2. 使用ocauxiliarytools 生成扫码信息，导入到引导中

## 设备信息-Macmini
![][image-2]

## 编码解码
![][image-3]
## 日常使用占用
![][image-4]
## 场景使用定位
1，日常办公，文字编辑，代码开发
2，影音娱乐，观看视频电影，支持4k hdr影视
3，基本剪辑，2-3轨道，1080p30帧
如需更高性能，需要配备一张免驱动显卡
## 双屏使用DP+HDMI 双4K屏幕
![][image-5]
## 其他信息
![][image-6]
![][image-7]
![][image-8]


[image-1]:	images/p330-model.webp
[image-2]:	images/info.png
[image-3]:	images/code.png
[image-4]:	images/base.png
[image-5]:	/images/4k.png
[image-6]:	/images/h1.png
[image-7]:	/images/h2.png
[image-8]:	/images/h3.png