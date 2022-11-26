### 安装dwm
克隆我的dwm:

```plaintext
git clone https://github.com/Flandrescav/dwm.git
cd dwm
sudo make clean install
```

新建.xinitrc文件添加下面命令然后通过`startx`启动dwm:

```plaintext
exec dwm #添加这一行
```

### 状态栏
前置安装
> pipewire 获取音量
>
> top 获取cpu
>
> acpi 获取电量

安装dwm自启动[补丁](https://dwm.suckless.org/patches/autostart/)

把脚本添加到dwm自启动脚本里 可参考 [autostart](https://github.com/Flandrescav/scripts/blob/main/autostart.sh)
