### install python-pip and git
```
sudo apt-get install python-pip git
su -c 'pip install git+git://github.com/Lokaltog/powerline'
```
### Font installation:
```
wget https://github.com/Lokaltog/powerline/raw/develop/font/PowerlineSymbols.otf https://github.com/Lokaltog/powerline/raw/develop/font/10-powerline-symbols.conf
sudo mv PowerlineSymbols.otf /usr/share/fonts/
sudo fc-cache -vf
sudo mv 10-powerline-symbols.conf /etc/fonts/conf.d/
```
### vim

