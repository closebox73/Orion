![greetings](/Asset/Orion.png)

A Conky themes pack which I made in hopes of beautifying your desktop 

## Showcase :

#### [Betelgeuse](/Betelgeuse) theme

![](/Betelgeuse/preview.png)
#### [Rigel](/Rigel) theme

![](/Rigel/preview.png)
- Change the purple color as you want by changing color2 value in Rigel.conf
#### [Bellatrix](/Bellatrix) theme

![](/Bellatrix/preview.png)
#### [Meissa](/Meissa) theme

![](/Meissa/preview.png)
- Wallpaper [Here](https://unsplash.com/photos/3ytjETpQMNY)
#### [Thabit](/Thabit) theme

![](/Thabit/preview.png)
- Wallpaper [Here](https://unsplash.com/photos/bAYnUAtV9aY)
---------------------------------------------------
### Featured
#### [Maia](/Maia) theme

![](/Maia/preview.png)
#### [Zavijava](/Zavijava) theme

![](/Zavijava/preview.png)
#### [Altair](/Altair) theme

![](/Altair/preview.png)
#### [Aludra](/Aludra) theme

![](/Aludra/preview.png)
-----------------------------------------------------

## Note :
- syntax configuration of this theme for conky version 1.10.8 or newer
- the default folder for this theme is in ~/.config/conky if it doesn't exist please create one
- The music player I used was `mpd`
- If the network speed doesn't work, try changing the network interface according to yours, the way to check is as follows
	![](/Asset/Wlan.png)
- I currently use Openbox, sometimes for other DE requires a slightly different setting
	if you know how to set it on another DE (if an error occurs) please let me know and I will post it here
- All fonts i get from:
	 - [Dafont](https://www.dafont.com)
	 - [Google Fonts](https://fonts.google.com) 

## Requirements :
- Conky version 1.10.8 or newer ( open this  [Link](https://github.com/brndnmtthws/conky) for instalation )
- for the weather theme I download the data using `curl` in json format, and use `jq` to process the data, please install first.
- if you want to use the GUI when installing the theme, please install [conky-manager2](https://github.com/zcot/conky-manager2)

## How to use theme :
- Clone this repo by command
  ```bash
  git clone https://github.com/closebox73/Orion.git
  ```
- Move one or more theme folders into ~/.config/conky/
- Open a folder that will be used and Install all font in fonts folder ( if you haven't installed the font ) then update font cache
- For weather theme you must have API KEY and city id ( you can get it [Here](https://openweathermap.org) and fill weather.sh in scripts folder
- Execute `start.sh`
- If you use conky-manager2, just check the theme to be installed
	![](/Asset/CM2.png)
- Done

## Last
- these themes are inspired by
	- KWGT widget for Android
	- ZOOPER widget
	- RAINMETER 
