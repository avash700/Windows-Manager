## i3wm

### 请务必查看配置文件并注意注释

### 必要组件：

* i3blocks
* i3lock-color --这个不是`i3lock`。。 是个增强版.... archlinux 在`AUR` 中
* ~~termite~~ alacritty or gnome-terminal

##### 另外可使用这个工具来换壁纸
* feh

##### 字体包
* ttf-ubuntu-font-family
* ttf-font-awesome

### 推荐软件：

* Fcitx
* Compton --用来让窗口支持透明的混成器
* Chromium
* pcmanfm

### 注意：

~~将`lock`文件复制到`/usr/bin`目录，并确保可运行~~

将`i3blocks`下的文件都复制到`/usr/libexec/i3blocks`目录(不同发行版路径不一）并确保可运行

请打开配置文件查看 根据需要修改
i3blocks的配置文件需要注意路径
比如Gentoo的i3blocks路径为`/usr/libexec/i3blocks/`, Arch Linux为`/usr/lib/i3blocks`
则你需要:`sed -i "s/libexec/lib/g" i3blocks.conf`

### 预览：

<p align="center">
  <img
src="https://raw.githubusercontent.com/Linux-Theme-Collection/Windows-Manager/master/i3/preview.png"
alt="preview"/><br/>
 <img

<p align="center">
  <img
src="https://raw.githubusercontent.com/Linux-Theme-Collection/Windows-Manager/master/i3/preview-lock.png"
alt="preview-lock"/><br/>
 <img
