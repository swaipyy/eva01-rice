# eva01-rice
## my dwm rice!
my dwm rice with kitty spt spotifyd and pywal
# Dependences 
- awesome fonts or nerd-fonts-complete / jetbrainsmono
- libxft-bgra for dmenu
- kitty & pywal
# How to use it?
clone this repo
`git clone https://github.com/mental-breakdown/eva01-rice
cd eva01-rice`
after this do
`cd dwm`
and please READ THE "config.h" FILE IS WHERE ARE ALL THE KEYBOARD SHORTCUTS (recommendation: edit it with your own kb shourcuts please) and run
`sudo make install`
do the same thing with slstatus/ and dmenu/
to install the kitty conf just 
`cp .config/kitty/kitty.conf ~/.config/kitty/` replace the /home/swaipy/ with your username and zsh with your shell!!
if you're using lightdm you need to do this to use dwm: https://www.reddit.com/r/suckless/comments/jj61py/how_do_i_make_dwm_appear_on_my_display_manager/
to use my colorscheme just install pywal
use: `yay -s pywal` if you're in arch, idk how it works in others distro tbh
to run pywal `wal -i path/file.png` 
to use spt you need a lightweidth client so install spotifyd: https://github.com/Spotifyd/spotifyd
spt: https://github.com/Rigellute/spotify-tui
fetch: https://github.com/dylanaraps/neofetch
to display imagines in terminal with kitty in neo fetch use this: `neofetch --backend kitty --source path/file.png`
lyrics in terminal: https://github.com/Jugran/lyrics-in-terminal
text editor: nvim
# Clarifications
my dwm, slstatus and dmenu configs are based in luke's smith configs!
please check his github: https://github.com/LukeSmithxyz
so thank you so much luke! your videos showed me a world that Im now passionate about
