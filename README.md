macOS Mojave 的硬件兼容性列表（不断更新中，此列表系拷贝远景账号962007201老铁的，不做传播，只自己收藏继续整理）



CPU部分:
--------------------------------------------------------------------------------------------------------

首选 intel 1151 针的 7/8/9代 酷睿 i9，i7，i5，i3，Mojave原生支持，带的核显UHD630/HD630 和独显一起可以正常编码解码开启核显硬件加速，是很好的选择。值得入手。
intel 1151针的6代酷睿 i7，i5，i3，凑合能用，但带的核显HD530不能正常编码解码硬解10-bit HEVC，只能硬解 8-bit HEVC。

--------------------------------------------------------------------------------------------------------
所以，目前看来，如果你不是Vega显卡，CPU就要选7/8/9代酷睿。
7代以前的酷睿，目前在Mojave里无法完全正常正常编码解码硬件加速，除非你用Vega显卡。
--------------------------------------------------------------------------------------------------------
1150，1155 针的2/3/4代 酷睿 i7，i5，i3 ，性能已经不行了，目前且仅搭配Vega显卡才可以完全正常正常编码解码硬件加速，
若搭配非Vega显卡，HD4600/HD4400/HD4000/HD3000/HD2500 核显硬件加速正常编码解码有问题，不能正常编码解码硬解HEVC。

1155，1150，1151平台的奔腾赛扬需要仿冒CPUID，核显无解，不建议新手入手。

X299/X99/X79平台，无集显的志强 E5，E3 ，目前在Mojave里仅搭配Vega显卡才能完全开启硬件加速。入手前要考虑。

AMD 的CPU，要替换破解内核，不太适合新手。不建议入手。

ES，QS等测试版的 CPU，有的会存在问题无法安装。不建议入手。

2012年前的1366针，1156针的老CPU，由于个人精力有限。本贴对2012年前上市的硬件不做探讨。
--------------------------------------------------------------------------------------------------------
主板部分:
--------------------------------------------------------------------------------------------------------

华硕，微星，技嘉 的 主板，是很好的选择。

8/9代酷睿首选Z390/Z370芯片组。DP/HDMI/DVI 核显输出不黑屏。

8代酷睿H370/B360/H310的芯片组，如果不插独显，主板要选带DP输出接口的。否则HDMI/DVI核显输出黑屏无信号。

微星和华硕的个别型号8代9代主板，更新最新的主板BIOS后，安装时会卡住。而老版本BIOS没问题。要注意。
影驰的8代主板BIOS很烂，新手尽量不要买。

6/7代酷睿，Z270/Z170/H270/H170/B250/B150/H110 芯片组都可以。如果不插独显，主板尽量选带DP输出接口的型号。

2/3/4代酷睿 1155/1150平台，性能已经落后了，如果你坚持要买，尽量选华硕，技嘉，微星这三个一线牌子和某宝的一些全新寨板（这些寨板竟然对黑苹果支持的挺友好，可能是公版方案直接拿来用的原因，虽然简陋但接近原生）。

华擎B75/B85 Pro4昂达H61映泰H61七彩虹H61翔升h61联想H61惠普H61戴尔H61等等等这些主板，它们的主板BIOS对UEFI支持相当差。尽量不选它们。

技嘉H61/技嘉B75/技嘉Z77/技嘉B85，虽然号称原生电源管理，但是质量堪忧，非常容易坏（无限重启/点不亮），缩水拒保嘉名副其实。（4代酷睿后，对黑苹果来说，相比华硕，技嘉已毫无优势了）。

高端的X99/X299平台相比酷睿平台，用户较为稀少。可参考的中文版教程有限，对新手来说不容易，不适合新手。
华硕X99/X299成功案例相对其他牌子的X99/X299多些。Tonymacx86有个大神发了华硕专用的黑苹果BIOS。
微星X99/X299，容易卡内存++++++。需要bios关闭cfg-lock和内存驱动OsxAptioFix2Drv-free2000.efi。

有些大厂的X79和双路的X79主板不好弄，反而淘宝上某些销量不错的寨板X79，寨板双路X79，寨板硬改H61/B75芯片组的X79，容易些（尤其是某某金牌X79成功案例很多）。


2012年之前的1366，1156平台的老主板，由于个人精力有限。本贴对2012年前上市的硬件不做探讨。

--------------------------------------------------------------------------------------------------------
硬盘部分:
--------------------------------------------------------------------------------------------------------

NVME  SSD 可选 三星的970 Pro/EVO。
HP，联想，Asgard，等等这些牌子的NVME 除了性能速度比三星差点，也没大毛病，毕竟价格便宜不少。

特别注意，三星 970 EVO Plus 和 三星 PM981 无法做为macOS系统盘安装原版，会导致死机，即使作为从盘，也会导致macOS死机。不要买。

影驰/浦科特的个别型号/intel的低端NVme，在macOS里也有小毛病。尽量不买。

SATA-3.0的SSD 选择很随意了，速度别太差的都行。注意老款intel的 SATA口SSD在macOS里有小毛病。

机械硬盘也很随意了，SATA-3.0/2.0 接口的都可以。



--------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------
显卡部分:

2012年前上市的老显卡，由于个人精力有限。本贴对2012年前上市的硬件不做探讨。
--------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------
intel 核显：

UHD630/HD630/HD530 核显输出的话，DP输出正常，其中，UHD630/HD630可以正常编码解码硬解10-bit HEVC，而 HD530并不能正常编码解码硬解10-bit HEVC，只能硬解 8-bit HEVC。

UHD630/HD630/HD530 核显输出的话，有些主板的HDMI/DVI接口在Mojave里黑屏。希望有成功驱动的景友把成功经验发帖出来分享给大家。

HD4600/HD4000 可以驱动，Mojave里黑屏的少。但是性能已经不行了，不能正常编码解码硬解HEVC。

HD4400/HD2500 对新手来说可能不太好驱动，希望有成功驱动的景友把成功经验发帖出来分享给大家。

--------------------------------------------------------------------------------------------------------
以下独显，目前，除了Vega架构的独显，其他独显都需要搭配集显HD630/UHD630才能硬件加速正常编码解码。
以下独显，目前，除了Vega架构的独显，其他独显都需要搭配集显HD630/UHD630才能硬件加速正常编码解码。
以下独显，目前，除了Vega架构的独显，其他独显都需要搭配集显HD630/UHD630才能硬件加速正常编码解码。
--------------------------------------------------------------------------------------------------------

Mojave免驱的A卡：

首选 蓝宝石 微星 的
Vega FE        （真正免驱，无需搭配集显也可完全硬件加速）
Vega 64        （真正免驱，无需搭配集显也可完全硬件加速）
Vega 56        （真正免驱，无需搭配集显也可完全硬件加速）
Vega Nano    （真正免驱，无需搭配集显也可完全硬件加速）
Pro SSG        （真正免驱，无需搭配集显也可完全硬件加速）
WX 9100       （真正免驱，无需搭配集显也可完全硬件加速）
WX 8200       （真正免驱，无需搭配集显也可完全硬件加速）
RX 590
RX 580          （注意，缩水的阉割版2048SP的RX580马甲卡不是免驱的，标准2304SP才是免驱卡）
RX 570
RX 560          （个别型号的HDMI/DVI输出黑屏，需要改FB，DP输出没问题）
RX 560D
RX 480
RX 470
RX 470D        （个别型号的HDMI/DVI输出黑屏，需要改FB，DP输出没问题）
RX 460
WX 7100 
WX 5100    
WX 4100
Pro Duo (Fiji) 
W9100
W9100 32GB
W9000
W8100
W8000
W7100
W7000
W5100
W5000 
R9 Fury
R9 Fury X
R9 Nano
R9 380   
R9 280X
R9 280
R9 370X 
R9 270X 
HD7990             （个别型号的HDMI/DVI输出黑屏，需要改FB，DP输出没问题）
HD7970             （个别型号的HDMI/DVI输出黑屏，需要改FB，DP输出没问题）
HD7950             （个别型号的HDMI/DVI输出黑屏，需要改FB，DP输出没问题）  
HD7870             （个别型号的HDMI/DVI输出黑屏，需要改FB，DP输出没问题）
HD7850             （个别型号的HDMI/DVI输出黑屏，需要改FB，DP输出没问题）
-------------------------------------------------------------------------------------------------

讯景XFX , 希仕 HIS ，的显卡BIOS问题多，除非你愿意冒险刷BIOS，否则不建议买。
华硕ASUS 的AMD卡个别型号黑屏，除非你愿意冒险刷BIOS，否则不建议买。

-------------------------------------------------------------------------------------------------

不适合新手的A卡：
有些通过仿冒/替换也能驱动，如果你不知道怎么仿冒/替换，不要买下面这些显卡：

RX580 2048SP     目前无解。
RX550        希望有成功驱动的景友把成功经验发帖出来分享给大家。
R9 380X     希望有成功驱动的景友把成功经验发帖出来分享给大家。
R9 290       希望有成功驱动的景友把成功经验发帖出来分享给大家。
R9 290X     希望有成功驱动的景友把成功经验发帖出来分享给大家。
R9 390       希望有成功驱动的景友把成功经验发帖出来分享给大家。
R9 390X     希望有成功驱动的景友把成功经验发帖出来分享给大家。
R9 370       希望有成功驱动的景友把成功经验发帖出来分享给大家。    
R7 240       希望有成功驱动的景友把成功经验发帖出来分享给大家。
R7 250       希望有成功驱动的景友把成功经验发帖出来分享给大家。
R7 250X     希望有成功驱动的景友把成功经验发帖出来分享给大家。
R7 260X     希望有成功驱动的景友把成功经验发帖出来分享给大家。
R9 270       希望有成功驱动的景友把成功经验发帖出来分享给大家。
R5 340       希望有成功驱动的景友把成功经验发帖出来分享给大家。
R7 350       希望有成功驱动的景友把成功经验发帖出来分享给大家。
R7 360       希望有成功驱动的景友把成功经验发帖出来分享给大家。
HD7750     希望有成功驱动的景友把成功经验发帖出来分享给大家。
HD7770     希望有成功驱动的景友把成功经验发帖出来分享给大家。
WX 2100    希望有成功驱动的景友把成功经验发帖出来分享给大家。
WX 3100    希望有成功驱动的景友把成功经验发帖出来分享给大家。
W2100       希望有成功驱动的景友把成功经验发帖出来分享给大家。
W4100       希望有成功驱动的景友把成功经验发帖出来分享给大家。
W4300       希望有成功驱动的景友把成功经验发帖出来分享给大家。
--------------------------------------------------------------------------------------------------------
Nvidia显卡在Mojave里免驱的目前只有开普勒架构的显卡，且其中一部分开普勒还会花屏：
Nvidia显卡在Mojave里免驱的目前只有开普勒架构的显卡，且其中一部分开普勒还会花屏：
Nvidia显卡在Mojave里免驱的目前只有开普勒架构的显卡，且其中一部分开普勒还会花屏：

开普勒GK104/GK107/GK110核心的在Mojave里原生驱动（不花屏）：
GTXTitan
GTXTitan Z
GTX Titan Black
GTX690
GTX680
GTX760
GTX770
GTX780
GTX780Ti
GTX650 
GTX650Ti
GT640
GT710
GT740
K6000
K5200
K5000
K4000
K4200
K2000
K2000D
K600
K420

--------------------------------------------------------------------------------------------------------
开普勒GK106/GK208核心的在10.12.6+的系统里花屏闪屏。谨慎购买: 
GTX650Ti  Boost
GTX660
GTX660Ti
GTX670
GT720
GT730
GT640
--------------------------------------------------------------------------------------------------------
开普勒架构核心后的所有N卡，都需要WebDriver才能驱动：
开普勒架构核心后的所有N卡，都需要WebDriver才能驱动：
开普勒架构核心后的所有N卡，都需要WebDriver才能驱动：

（Nvidia官方目前还没有放出Mojave版的WebDriver，估计今年不会有，明年也不一定有，甚至可能永远不会有）

麦克斯韦，帕斯卡，伏特，图灵架构，以及还没设计出来的架构：(X代表数字)

Titan RTX
Titan X
Titan XP
Titan V
GV100
GP100
PXX00             例如：P6000，P5200，P5000
PXX0               例如：P620，P600，P400
MX000            例如：M6000，M5000
RTX-40X0        例如：RTX-4080，RTX4070
RTX-30X0        例如：RTX-3080，RTX3070
RTX-20X0        例如：RTX-2080，RTX2070
RTX-X000        例如：RTX-6000，RTX5000
GTX-40X0        例如：GTX-4080，GTX4070
GTX-30X0        例如：GTX-3080，GTX3070
GTX-20X0        例如：GTX-2080，GTX2070
GTX-10X0        例如：GTX-1080，GTX1070
GTX-9X0          例如：GTX-980，GTX970
GT-1030
GTX-750Ti
GTX-750
K2200
K620
K1200

--------------------------------------------------------------------------------------------------------
华硕带vga接口的GTX750Ti/750，在macOS里DVI输出黑屏。

GP104核心的GTX1060 和 GDDR5X显存的GTX1060，目前在macOS里无法驱动。

影驰显卡BIOS在Mojave里问题多，除非你愿意冒险刷BIOS，不建议买。

--------------------------------------------------------------------------------------------------------
二手市场价低于50元的的显卡，大都不支持Metal，不建议买。

2012年之前上市的的老显卡，大都不支持Metal，不建议买。

Metal 是 macOS、iOS 和 tvOS 中内建的图形和计算技术。通过这项技术，主处理器 (CPU) 和图形处理器 (GPU) 可以更高效地协同工作，从而在游戏中提供更流畅的图形性能，并加快高性能媒体应用的运行速度。

--------------------------------------------------------------------------------------------------------


显示器部分：
--------------------------------------------------------------------------------------------------------
23.8寸的 4K分辨率显示器（一千出头可以买到），Windows直接2X缩放，macOS里默认开启HiDPI。
5K分辨率的27寸显示器也很好。因为iMac Pro 也是这个尺寸。
1K2K分辨率的显示器，在macOS里显示效果是比较尴尬的，不建议入手。
低于4K分辨率的27寸以上的显示器，在macOS里显示效果也比较尴尬，不建议入手。
无论你用什么显示器，优先用DP接口，不要用VGA输出接口来连接显示器。
--------------------------------------------------------------------------------------------------------


外设部分：
--------------------------------------------------------------------------------------------------------
苹果机同款的 BCM943602CS 是免驱卡，WIFI带蓝牙二合一，四天线的，即插即用。（三天线的蓝牙和2.4G无线冲突）

大部分常见的瑞昱芯片的 RTL8 开头的USB的无线网卡，在Mojave都可以驱动：

RTL8188CU/RTL8188CUS/RTL8188EU/

RTL8192CU/RTL8192DU/RTL8192EU/

RTL8811AU/RTL8811CU/

RTL8812AU/RTL8812BU/

RTL8813AU/RTL8814AU。


较老的RTL8 开头的芯片已经不支持Mojave，如：RTL8191SU/RTL8187L

较新的RTL8 开头的芯片目前也还不能驱动，如：RTL8188GU/8188RU


联发科 MediaTek 芯片的USB无线网卡，在Mojave里不容易驱动：
（改驱动ID能驱动，希望成功的景友分享方法）
联发科 MediaTek 芯片一般是 MT 或 RT 开头，例如：RT3070，MT7601。
小米wifi，360wifi，小度wifi，和某些号称免驱版带很长的信号天线的，一般都是 联发科 MediaTek的芯片，不建议新手买。

intel 芯片的 无线网卡目前Mojave里 无法驱动。


