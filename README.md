Listen By no means I am Capable enough of creating a complete repo with every single detail Even when I want to I will try my best to no break your system with my README 
so for the things mentioned below Please refer to their manuals before starting blindlly I myself Have experienced the pain from r/unixporn readme
for the sake of that I will include links to all the resources possible

# A Quick guide for Getting started with bspwm [PlEASE READ ME](https://www.instructables.com/Bspwm-Installation-and-Configuration/)
## JUST TO CLARIFY I WANTED TO HAVE A COLORFULL WM SO ...

| What Is It    | What is used |
| ------------- | ------------- |
| WM  | [Bspwm](https://github.com/baskerville/bspwm.git)  |
| text editor  | [nvim](https://neovim.io/)  |
| Browser   | [firefox](https://www.mozilla.org/en-US/firefox/new/)  |
| Wallpapers   | [Wallhaven.cc](https://github.com/dylanaraps/neofetch.git)  |
| terminal   | urxvt |
| Fetch  | [neofetch](https://github.com/dylanaraps/neofetch.git)  |
| Discord   | [BetterDiscord](https://github.com/BetterDiscord/BetterDiscord.git)   |
| Color Scheme   | [pywal](https://github.com/dylanaraps/pywal)  |
| Compositor | ([picom-ibhagwan-git](https://github.com/ibhagwan/picom-ibhagwan-git.git) |




Ok So after writing like 200 lines I realized I have already uploaded my dots <br />
anyways <br /><br />
First Bspwm & sxhkd <br />
Just copy and paste if you already have a Bspwm & sxhkd configs and or up and running if you don't <br />
then <br />
(Note: Do not copy the $) <br />
$ mkdir ~/.config (only if you don't have one) <br />
$ mkdir ~/.config/bspwm <br />
cd into my dotfiles and again cd into bspwm then <br />
$ cp -r  bspwmrc resize ~/.config/bspwm <br />
after that <br />
edit the both of them to your liking mine has some minor changes and stuff if and everything is commented <br />
[NExt] <br />
Install pywal with pip using (pip install pywal)  <br />
after that cd into my dotsfiles and <br />
$ cp -r wal ~/.config/ <br />
[Important] <br />
after that run this command <br />
chmod +x ~/.config/wal/pywal.sh <br />
If you don't run it than the colors will never change on (super + p) <br />
[NExt] <br />
cd again into my dots <br />
this time for the fish shell IF YOUR using bash which is default please refer to <br />
https://itsfoss.com/pywal/ <br />
For the fish shell after installing cd into my dotsfiles and cp -r fish ~/.config/ <br />
if you don't copy the whole folder than the annoying fish_greeting message and {fish wal command not found} errors will haunt you <br />
[NExt] <br />
same For the neofetch after installing cd into my dotsfiles and cp -r neofetch ~/.config/ <br />
[NExt] <br />
same For the picom after installing cd into my dotsfiles and cp -r picom  ~/.config/ <br />
