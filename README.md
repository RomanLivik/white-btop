<img width="1856" height="977" alt="image" src="https://github.com/user-attachments/assets/c4f965c1-726a-4f7e-be64-6583cfc1ddb6" />



This is black and white theme for btop. You can use it for your black and white rice or for other rices, because it is very easy to rewrite hex-codes of colors in this config. 

## Installation 
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
