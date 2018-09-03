# MyLinuxConf
## 1. guake
更好用的控制台
```
sudo apt install guake
```

## 2 .zsh && on-my-zsh
更好看的控制台
```
sudo apt-get install zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## 3. linux QQ
直接可用的AppImage
[linux QQ(包括QQ和TIM)](https://github.com/askme765cs/Wine-QQ-TIM)


## 4. sublime text
解决不能输入中文的问题
```
sudo apt-get update && sudo apt-get upgrade

git clone https://github.com/lyfeyaj/sublime-text-imfix.git
//切换到git目录
cd sublime-text-imfix

./sublime-imfix
//need relogin
```

## 5. 桌面优化
提供一个系统监控面板
```
sudo apt-get install unity-tweak-tool
```
解压conky下Harmattan.zip到任意目录，移动.harmattan-assets到~目录下。将.harmattan-themes下相应主题下(比如Ubuntu-Touch)God-Mode/normal-mode/.conkyrc移动到~目录，更改该文件窗口位置到想要的位置。

    在Startup Application添加开机启动，命令: conky -q
