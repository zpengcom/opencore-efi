# opencore 

<img src="https://i.postimg.cc/sx8Z0swC/20153230.png">
<img src="https://raw.githubusercontent.com/zpengcom/opencore-efi/main/img/macinfo.png">

- 基于官方正式版,集成官方主题<br>
- Z390主板已补丁开启原生nvram<br>
- 开启启动音效，启用启动主题，3秒倒计时进入上一次系统（启动界面通过Enter进入选择的系统；或者按Ctrl+Enter进入系统并设为默认启动系统；或者在系统中通过Bootcamp切换系统并作为默认启动系统）F10截屏<br>
- 启动磁盘扫描参数 Scan Policy 由默认值0 改成 19596547 隐藏非常用启动项(仅显示win+mac)，按空格键切换完整项目<br>
- 移除了3码信息，可自己生成，然后去<a href="https://checkcoverage.apple.com/us/en/?sn=" target="_blank" style="target-new: tab;">苹果官网查询</a> ，能用就行。<br>

*bug:USB定制存在bug 已从0.6.9中开始移除

<a href="https://github.com/zpengcom/opencore-efi/releases"> 下载Opencore EFI 文件 </a>


# 硬件信息

系统：  Win10+macOS11.3.1

主板：  华硕 TUF Z390-PLUS GAMING (WI-FI)

CPU：  Intel Core i9-9900K @ 3.6Ghz

显卡：  AMD Radeon RX 590 (8GB)  +  Nvidia GeForce RTX 2070 (8GB)  => DELL U2414H

硬盘：  Intel M.2 SSDPEKKW512G8 + SSD浦科特PX-256M8VC + 希捷 ST2000DM001 - 2T

内存：  金士顿DDR4 3600MHz 16GB X2

网卡：  Broadcom BCM94360CD + Intel I219V7（主板） + intel wireless-AC 9560 & BT5.0（主板）

声卡：  Realtek ALC S1200A（主板）

# 软件推荐
<a href="https://staticz.com/soundcontrol/ " target="_blank" style="target-new: tab;">Sound Control</a> ----- 支持HDMI音频输出时的音量调节
                                                            
<a href="https://github.com/chris1111/OpenCanopy-Generator" target="_blank" style="target-new: tab;">OpenCanopy Generator</a> ------- 主题文件生成（.icns)
                                                                           
<a href="http://mackie100projects.altervista.org" target="_blank" style="target-new: tab;">OpenCore Configurator</a> ------- OpenCore配置工具
                                                                 
Hackintool ------- 工具箱
