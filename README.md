# opencore 

<img src="https://i.postimg.cc/sx8Z0swC/20153230.png">
<img src="https://raw.githubusercontent.com/zpengcom/opencore-efi/main/img/macinfo.png">
<img src="https://raw.githubusercontent.com/zpengcom/opencore-efi/main/img/mac-win.png">
<img src="https://raw.githubusercontent.com/zpengcom/opencore-efi/main/img/win-mac.jpg">

- 基于官方正式版,集成官方主题<br>
- Z390主板已补丁开启原生nvram<br>
- 开启启动音效，启用启动主题，3秒倒计时进入上一次系统（启动界面通过Enter进入选择的系统；或者按Ctrl+Enter进入系统并设为默认启动系统；或者在系统中通过Bootcamp切换系统并作为默认启动系统）F10截屏<br>
- 启动磁盘扫描参数 Scan Policy 由默认值0 改成 19596547 隐藏非常用启动项(仅显示win+mac)，按空格键切换完整项目<br>
- 移除了3码信息，可自己生成，然后去<a href="https://checkcoverage.apple.com/us/en/?sn=" target="_blank" style="target-new: tab;">苹果官网查询</a> ，能用就行。<br>
<br>
如需启用主板自带的intel wifi 参见<a href="https://github.com/OpenIntelWireless/HeliPort" target="_blank" style="target-new: tab;">HeliPort</a>项目<br>
<br>
*bug:USB定制存在bug(全部USB端口无法识别 或 USB2.0设备无法使用） 从 OC 0.6.9 中开始移除USB定制内容 并禁用端口补丁限制:Kernel -- XhciPortLimit 项

<a href="https://github.com/zpengcom/opencore-efi/releases"> 下载Opencore EFI 文件 </a>


# 硬件信息

系统：  Win10+macOS 11.6

主板：  华硕 TUF Z390-PLUS GAMING (WI-FI)

CPU：  Intel Core i9-9900K @ 3.6Ghz

显卡：  AMD Radeon RX 590 (8GB)  +  Nvidia GeForce RTX 2070 (8GB)  => DELL U2414H

硬盘：  Intel M.2 SSDPEKKW512G8 + SSD浦科特PX-256M8VC + 希捷 ST2000DM001 - 2T

内存：  金士顿DDR4 3600MHz 16GB X2

网卡：  Broadcom BCM94360CD + Intel I219V7（主板） + intel wireless-AC 9560 & BT5.0（主板）

声卡：  Realtek ALC S1200A（主板）

# windows10升级windows11 TPM问题
主板没有TPM项？<br>
启用PTT（Intel平台信息技术）即可，在主板设置中：<br>
高级 --> PCH-FW Configuration --> Intel Platform Trust Technology  -- Enabled

# 软件推荐
<a href="https://github.com/headkaze/Hackintool" target="_blank" style="target-new: tab;">Hackintool</a> ------- 工具箱
                                                                           
<a href="http://mackie100projects.altervista.org" target="_blank" style="target-new: tab;">OpenCore Configurator</a> ------- OpenCore配置工具

<a href="https://github.com/ic005k/OCAuxiliaryTools" target="_blank" style="target-new: tab;">OC Auxiliary Tools</a> ------- OpenCore辅助工具

<a href="https://github.com/USBToolBox/tool" target="_blank" style="target-new: tab;">USBToolBox</a> ------- USB定制

<a href="https://github.com/xzhih/one-key-hidpi/blob/master/README-zh.md" target="_blank" style="target-new: tab;">开启HiDPI</a> ------- 开启 macOS HiDPI
         
<a href="https://staticz.com/soundcontrol/ " target="_blank" style="target-new: tab;">Sound Control</a> ----- 支持HDMI音频输出时的音量调节
                                                            
<a href="https://github.com/chris1111/OpenCanopy-Generator" target="_blank" style="target-new: tab;">OpenCanopy Generator</a> ------- 主题文件生成（.icns)

<a href="https://github.com/chris1111/Icnspack-Builder" target="_blank" style="target-new: tab;">Icnspack-Builder</a> ------- OpenCore主题制作工具

