<img width="1856" height="977" alt="image" src="https://github.com/user-attachments/assets/c4f965c1-726a-4f7e-be64-6583cfc1ddb6" />

<img width="1470" height="956" alt="image" src="https://github.com/user-attachments/assets/2e8602f0-2715-4ff9-8892-488b34f46483" />


This is black and white theme for btop. You can use it for your black and white rice or for other rices, because it is very easy to rewrite hex-codes of colors in this config. 

## This theme works correctly on
* MacOS 26 Tahoe
* MacOS Sonoma
* Gentoo openrc
* Arch Linux and arch based distributions

I didn't test this config on other distributions. I think that it will be work correctly

## Installation (universal)
```
git clone https://github.com/RomanLivik/white-btop
mkdir -p ~/.config/btop/themes
cd ~/white-btop
cp white.theme ~/.config/btop/themes
```

## Applying this theme
```
nano ~/.config/btop/btop.conf
```
Then you need to find line "color_theme" and rewrite it:
```
color_theme = "/home/NAME_OF_YOUR_USER/.config/btop/themes/white.theme"
```
