# Arch Linux To Go using log 

## Written in the Seewo Computer of Class 1 Grade 1, Jiangmen NO.1 High School.

# By snow@ArchToGo-snow

### 2025.03.17

这个希沃白板一体机，太抽象了，只要显示器黑屏（也就是系统没有输入的时候），再亮屏，主屏就会自动亮起 

也就是说，我在tty就提前手动按大屏幕上的按钮熄屏，防止别人事件，这个时候再启动hyprland，哈人的事情就发生了，主屏就亮起来了，大雨老师你知道的，我hyprland的壁纸是CAB的那张合影
所以我要趁没人的时候偷偷输hyprland，再非常快地把希沃大屏幕关掉
同样，关hyprland(\>killall hyprland)的时候也会亮，气晕了
鹤形好用（（

没有什么软件包和开机自启服务的Arch Linux真的很小！tty<=400 MiB
开了hyprland不怎么操作<=1.2 GiB （刚开的时候~1.0 GiB）
我目前手动加的开机服务貌似就iwd和dhcpcd（都是给网络连接和管理用的）
CPU占用更是1%

总之Arch Linux本身没有预装很多软件包真的很小(Packages: 602(pacman))

学校的8G内存真的很难受
CPU: Intel(R) Core(TM) i7-8700 (12) @ 4.60 GHz
这CPU基频比我10代i3高好多(3.60GHz)羡慕了:( 10代i3性能真的不太够

决定今天开始创建一个git仓库来存放我的Arch Linux使用记录(心得)，分成在家(Arch-snow)和在学校(ArchToGo-snow)
所以
`git init`
`git branch -m main`
`git add .`
`git commit -m "Initialized the repository and uploaded 20250317."`

### 2025.03.18

在自己的Arch Linux上做ppt可太舒服了）
OnlyOffice好玩（?

### 2025.03.19

其实我可以让希沃锁屏（进入画图模式）再进hyprland的））
结果今天操作不慎
想让ppt放出来然后我自己在下面做ppt
结果把锁屏关了，onlyoffice双开崩了（因为一些我的操作问题）
壁纸漏了！！
噔噔咚

现在还是用上了）
不过话说虽然我没有装截图软件但是我完全可以把ppt播放然后锁屏
还想着截图然后
`ffplay ./homework.png`
的））
