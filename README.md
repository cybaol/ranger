## install ranger (install dependencies as much as possible)
```bash
# Arch Linux
sudo pacman -S ranger
```
then
```bash
git clone https://github.com/cybaol/ranger.git ~/.config/ranger &&
git clone https://github.com/alexanderjeurissen/ranger_devicons ~/.config/ranger/plugins/ranger_devicons &&
git clone https://github.com/maximtrp/ranger-archives ~/.config/ranger/plugins/ranger-archives &&
cd ~/.config/ranger/plugins/ranger-archives && make install
```

if you want to have a better experience, recommend to install [nerdfonts](https://www.nerdfonts.com)<br>
