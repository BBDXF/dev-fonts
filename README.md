# dev-fonts
the base fonts and config for my development used. include source code, jetbrain, misans, emoji.

## List
- ms-font
	- 微软雅黑, Microsoft YaHei : msyh?.tty
	- Segoe UI Emoji : seguiemj.ttf
	- 黑体 : simhei.ttf
	- 楷体 : simkai.ttf
	- 宋体 : simsun.ttf
	- 符号字体 : wingding?.ttf，webdings.ttf
- misans-font
	- MiSans VF
	- MiSans Latin VF
	- MiSans L3
	- Misans TC VF
- code-font
	- JetBrains Mono VF
	- SourceCodeVF
- maple-font
	- Maple Mono Normal NL NF CN

> Maple is a combined font embed with icons, Chinese and Japanese glyphs. the characteristic of perfect 2:1 alignment between Chinese and English allows this font to achieve a neat, uniform, beautiful, and comfortable appearance in scenarios such as multilingual display and Markdown tables.   

## Install

Linux:  
```bash
git clone xxxxxxxxxxxxxxxxx
cd dev-fonts
# system space
sudo cp -r code-font misans-font ms-font maple-font /usr/share/fonts/
# user space
sudo cp -r code-font misans-font ms-font maple-font ~/.fonts/
```

windows:  
> Select fonts ttf files,  then mouse right click,  install for all user  

## Links
- https://github.com/subframe7536/maple-font
- https://github.com/adobe-fonts/source-code-pro
- https://hyperos.mi.com/font/download
- Windows 11 
