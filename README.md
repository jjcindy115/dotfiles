# RTFM [Read The Fucking Manual] 🙏
### Listen By No Means I Am Capable Enough Of Creating A Complete Repo With Every Single Detail Even When I Want To I Will Try My Best To No Break Your System With My README. So For The Things Mentioned Below Please Refer To Their Manuals Before Starting Blindly. I Myself Have Experienced The Pain From r/unixporn README For The Sake Of That I Will Include Links To All The Resources Possible. <br /> 
### Before jumping in I wanna remind you that For this to work you either have to put Wallpapers (For which you want color schemes from) In   <br />
### ~/Pictures/Pywal/  <br /> 
### or either change the path for the wallpapers in <br /> 
### ~/.config/wal/pywal.sh <br /> 

## A Quick guide for Getting started with bspwm [[PlEASE READ ME]](https://www.instructables.com/Bspwm-Installation-and-Configuration/) <br /> 
# Create A BACKUP 🙏🙏🙏🙏🙏🙏 <br /> 

| What Is It    | What is Used |
| ------------- | ------------- |
| OS | [Arch Linux](https://archlinux.org/) |
| WM  | [Bspwm](https://github.com/baskerville/bspwm.git)  |
| text editor  | [nvim](https://neovim.io/)  |
| Browser   | [firefox](https://www.mozilla.org/en-US/firefox/new/)  |
| Wallpapers   | [Wallhaven.cc](https://wallhaven.cc/)  |
| terminal   | [urxvt](https://wiki.archlinux.org/title/rxvt-unicode) |
| Fetch  | [neofetch](https://github.com/dylanaraps/neofetch.git)  |
| Discord   | [BetterDiscord](https://github.com/BetterDiscord/BetterDiscord.git)   |
| Color Scheme   | [pywal](https://github.com/dylanaraps/pywal)  |
| Compositor | [picom-ibhagwan-git](https://github.com/ibhagwan/picom-ibhagwan-git.git) |
| Discord-Theme | [pywal-discord](https://github.com/FilipLitwora/pywal-discord)
  | Font-UI | [UbunutMono Nerd Font Mono](https://www.programmingfonts.org/#ubuntu) |
| Font-Terminal | [FIraCode Nerd Font Mono](https://www.programmingfonts.org/#firacode) |

# Screenshots for eye-candy 😙
![Screenshot1](https://user-images.githubusercontent.com/108634945/184496564-e45bb1cf-40bb-4178-bbc7-3163bdda3d36.png)
![Screenshot2](https://user-images.githubusercontent.com/108634945/184496575-b99a505c-df28-42d7-93a7-2c7e8dd2fc37.png)
![Screenshot3](https://user-images.githubusercontent.com/108634945/184496577-e247fdc1-5770-4f66-a9e6-f268e7f3cc2b.png)
![Screenshot4](https://user-images.githubusercontent.com/108634945/184497440-1c60b8fb-9086-4fa3-bde8-b7964e9db68b.png)
![screenshot5](https://user-images.githubusercontent.com/108634945/184497499-8652182c-d5a2-48d0-a8e9-73e7882921a6.png)
![screenshot6](https://user-images.githubusercontent.com/108634945/184497378-b53a66d7-6e3a-40d5-b35a-220dea770972.png)
![screenshot7](https://user-images.githubusercontent.com/108634945/184497381-ec8dd108-99bc-442c-9e11-849496191bb8.png)
![screenshot8](https://user-images.githubusercontent.com/108634945/184497384-0f8b9250-b161-48a7-86e0-755889069da1.png)
![screenshot9](https://user-images.githubusercontent.com/108634945/184497386-0ae9e802-98e7-48aa-9811-e59d8c87cfa1.png)
![screenshot10](https://user-images.githubusercontent.com/108634945/184497387-641cf497-38a8-4a2a-8839-abc6a645cecd.png)

## First Bspwm <br />
### Just copy and paste if you already have a Bspwm & sxhkd configs and or up and running if you don't <br />
      mkdir ~/.config (only if you don't have one) 
    
      mkdir ~/.config/bspwm 
### cd into my dotfiles and again cd into bspwm then <br />
      cp -r  bspwmrc resize ~/.config/bspwm/
### (Note: DO NOT FORGET) <br />
      chmod +x ~/.config/bspwm/bspwmrc 
##  Sxhkd  <br />
### Edit it to your liking | Mine has some minor changes and stuff | Everything is commented <br />
      mkdir ~/.config/sxhkd 
### cd into my dotfiles and again cd into sxhkd then <br />
       cp sxhkdrc ~/.config/sxhkd/
### (Note: DO NOT FORGET) <br />
       chmod +x ~/.config/sxhkd/sxhkdrc 
## [.xinitrc] <br />
### cd into dotfiles and <br />
       mv .xinitrc ~/
## [Pywal] <br />
### Install pywal with pip using  <br />
     pip install pywal  
### after that cd into my dotsfiles and <br />
     cp -r wal ~/.config/ 
## [Important] <br />
### after that run this command 
     chmod +x ~/.config/wal/pywal.sh 
### If you don't run it than the colors will never change on (super + p) <br />
## [Fish] <br />
     sudo pacman -Syyu fish 
### this time for the fish shell IF YOUR using bash which is default please refer to Pywal for Bash <br />
### cd again into my dots <br />
### For the fish shell after installing cd into my dotsfiles and <br />
     cp -r fish ~/.config/ 
### if you don't copy the whole folder than the annoying fish_greeting message and {fish wal command not found} errors will haunt you <br />
## [Pywal for Bash] <br />
### Visit This [arcticle](https://itsfoss.com/pywal/) <br />
## [Neofetch] <br />
     sudo pacman -Syyu neofetch 
### same For the neofetch after installing cd into my dotsfiles and <br />
     cp -r neofetch ~/.config/
## [Picom] <br />
     paru -S picom-ibhagwan-git 
### same For the picom after installing cd into my dotsfiles and  <br />
     cp -r picom  ~/.config/
## [Firefox] <br />
### For Firefox Firstly get the pywalfox with (pip install pywalfox) then install using <br />
     pip install pywalfox 
     
     pywalfox install 
### after that go get the [Pywalfox extenstion for Firefox](https://addons.mozilla.org/en-US/firefox/addon/pywalfox/) <br />
<br />

### Last But not Least Press the shortcut (super + p) to check if everything works <br />


### I Really Hope you Would atleast have a working arch install <br />
### If not I'm sorry I guess ...... 🙇
