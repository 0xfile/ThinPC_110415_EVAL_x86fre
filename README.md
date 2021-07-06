# [Windows Thin PC 下载、安装与激活](https://bitmingw.com/2017/04/24/windows-thin-pc-download-install-activate/)

中文语言包：https://blog.csdn.net/m0_43432635/article/details/83317560

语言包下载链接：https://download.microsoft.com/download/8/6/1/8616D57C-1163-45FB-832A-15FA60571002/SP1/Chinese%20%28Simplified%29%20Language%20Pack%20-%20Windows%20Embedded%20Standard%207%20SP1/lp.cab

使用方法

因为没有 lpksetup.exe 组件，所以不能在控制面板里直接安装语言包，可以用 DISM
命令添加 WES7 SP1 的中文语言包，把下载的语言包文件放到 C 盘根目录，然后以管
理员权限运行 cmd 命令提示符，然后输入命令：
dism /online /add-package /packagepath:C:\lp.cab
重启后在控制面板中更改显示语言
修改启动画面的中文显示那两步可以忽略，因为不能完全显示中文，不如不改。

web backup: https://web.archive.org/web/20201025081532/https://bitmingw.com/2017/04/24/windows-thin-pc-download-install-activate/

Origin download link: http://download.microsoft.com/download/C/D/7/CD789C98-6C1A-43D6-87E9-F7FDE3806950/ThinPC_110415_EVAL_x86fre.iso
