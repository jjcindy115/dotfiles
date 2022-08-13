Ok So first time using git and all so yeah ....
anyways 
First.
Pywal
the pywal config I added a keybind in the sxkhd which is (super+p)
which executes pywal.sh in wal folder 
I have almost 250+ wallaper in my directory ~/Pictures/Pywal change it to the folder where you want random wallpapers and color schemes from
Second.
Pywalfox
a dead-simple pip package to install (pip install pywalfox)
and for the color schemes install the pywal fox extension 
https://addons.mozilla.org/en-US/firefox/addon/pywalfox/
And the colors should change on the fly
Third.
the fish shell I use the fish shell as my default shell and so the for the colors in fish shell 
add this line to ~/.config/fish/config.conf
cat ~./cache/wal/sequences &
in between
(if status is-interactive 
cat ~./cache/wal/sequences & 
end)
like so and for discord I use betterdiscord with a pywal-discord theme from 
https://github.com/FilipLitwora/pywal-discord
it also gets changed on the fly by the pywal.sh
NOTE I made the pywal.sh in a way that only changes the firefox and betterdiscord if the 
color scheme is set sucessfully 
idk why but sorry for the Extermelly bad README if you have any questions I am sorry but please ask them from r/unixporn community I am not fit to solve my own problems So yeah...
