Ok So after writing like 200 lines I realized I have already uploaded my dots 
anyways 
First Bspwm & sxhkd 
Just copy and paste if you already have a Bspwm & sxhkd configs and or up and running if you don't 
then 
(Note: Do not copy the $)
$ mkdir ~/.config (only if you don't have one)
$ mkdir ~/.config/bspwm
cd into my dotfiles and again cd into bspwm then 
$ cp -r  bspwmrc resize ~/.config/bspwm
after that 
edit the both of them to your liking mine has some minor changes and stuff if and everything is commented 
[NExt]
Install pywal with pip using (pip install pywal) 
after that cd into my dotsfiles and 
$ cp -r wal ~/.config/
[Important] 
after that run this command 
chmod +x ~/.config/wal/pywal.sh
If you don't run it than the colors will never change on (super + p)
[NExt]
cd again into my dots 
this time for the fish shell IF YOUR using bash which is default please refer to 
https://itsfoss.com/pywal/
For the fish shell after installing cd into my dotsfiles and cp -r fish ~/.config/
if you don't copy the whole folder than the annoying fish_greeting message and {fish:wal command not found} errors will haunt you 
[NExt]
same For the neofetch after installing cd into my dotsfiles and cp -r neofetch ~/.config/
[NExt]
same For the picom after installing cd into my dotsfiles and cp -r picom  ~/.config/
