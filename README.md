## install Awesome,Sddm ,Git > 
```bash 
sudo pacman -S awesome sddm git
``` 
# What is Sddm?
The Simple Desktop Display Manager (SDDM) is a display manager.

## config Sddm >
```bash 
sudo systemctl enable sddm 
``` 
<h2 align="center">😃Than reboot</h2>

## clone dot-Config File > 
```bash
git clone https://github.com/Komi7/Archlinux-dotfiles.git
```
## Packages install >
```bash 
sudo pacman -S --needed - < packages.sh
``` 
## picom-git
```bash
git clone https://aur.archlinux.org/picom-git.git
```



## Awesome theme Config  >
###Installation
```bash
mkdir .config/awesome

git clone --recurse-submodules --remote-submodules --depth 1 -j 2 https://github.com/lcpz/awesome-copycats.git

mv -bv awesome-copycats/{*,.[^.]*} ~/.config/awesome; rm -rf awesome-copycats
```

**NOTE!** These were made for my computer specifications. So use it at your own risk! 

## Aesthetic-Night gtk theme setup:
### go to Archlinux-dotfiles download location & unzip theme zip file
```bash
cd ~/Download/Archlinux-dotfiles
unzip themes.zip
```

### Copy the themes to the themes folders
```bash
sudo cp -rf themes/Aesthetic-Night/* /usr/share/themes

cp -rf themes/Aesthetic-Night-GTK4/* ~/.config/gtk-3.0
```
### Add this line on ``` ~/.config/gtk-3.0/settings.ini ``` for left controls
```bash
gtk-decoration-layout=close,maximize,minimize:menu
```

## Aesthetic VSCode setup ☄️:


### Install required extension

  •
  <a href="https://marketplace.visualstudio.com/items?itemName=iocave.customize-ui">Customize UI</a>

  •
  <a href="https://marketplace.visualstudio.com/items?itemName=antfu.icons-carbon">Carbon Product Icons</a>

### copy config file
```bash
cp misc/vscode/User/settings.json ~/.config/Code/User
```
  
***modify ongoing ! ...........🤞***


<h1 align="center">Hi , I'm Shousuke Komi <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>
<p align="center">
 <h1 align="center"> <p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?multiline=true&lines=Linux+user+,+Learning+coding">
  </h1>
 
</p>


<div align="center">

  <img  src="https://github.com/Komi7/resources/blob/main/img/grid-snake.svg"
       alt="snake" /></a>
</div>

<details>
  <summary>☎️ contact me</summary>
<div>
  <samp>
    <h2 align="center">😎 you can reach me by:</h2>
    <p align="center">
      <br/>
      <a href="https://t.me/mahmud11507" target="blank"><img align="center"
         src="https://img.shields.io/badge/-Telegram-brightgreen.svg?style=for-the-badge&logo=Telegram&logoColor=white"
         alt="komii" height="30"/></a>
      <a href="https://discord.com/channels/@me/724963674477035561" target="blank"><img align="center"
         src="https://img.shields.io/badge/-Discord-blue.svg?style=for-the-badge&logo=Discord&logoColor=white""
         alt="komii" height="30"/></a>
      <a href="https://instagram.com/shousuke.komii" target="blank"><img align="center"
         src="https://img.shields.io/badge/instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white"
         alt="komii" height="30"/></a>
