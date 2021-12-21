# slock-inspirational
simple script for showing quotes on shuffle for slock 

# dependencies
- slock installation with color message patch
	- [color message](https://tools.suckless.org/slock/patches/colormessage/)
- gnu coreutils 

# installation
1. clone this repository
```
git clone https://github.com/andrewlmao/slock-inspirational.git
cd slock-inspirational
```
2. copy the script ```slock-inspirational``` into /usr/bin
```
mv slock-inspiration /usr/bin
```
3. create a directory and file to store quotes
```
cd
mkdir .slock-quotes
cd .slock-quotes
mkdir quotes.txt
```
4. put your individuals quotes in single lines (use \n if you want a line break)
ex.
```
1      Your never fully dressed without a smile
```
5. insert slock-inspirational into your suspend script
