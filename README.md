# i3-config
i3 config i daily drive
my config of 13 vm i daily drive

Using the basic config of i3

exec rofi -show run
exec rofi -show drun (Steam)
bindsym $mod+x exec rofi -show window
exec nitrogen --restore &
exec compton/picom & (run in terminal if not active in config file/compton is replaced by picom)

client.focused #04FA25  #04FA25 #04FA25 #04FA25 <-window boarder color

need to be place in your i3 config file home/user.config/i3

alsamixer terminal <- sound from terminal if needed
ranger ~/.config/ranger/rc.conf textfile set preview_images true <- to view images in ranger, ranger need to be run from the terminal
pcmanfm vortex dark icons/paparius <- need to be downloaded to be install from the lxappearance program
Lxappearance <- to chance icon themes, and boarder
Ncdu - diskspace show terminal 

optional programs to install:
strawberry music Player 
cmus music from the terminal
scrot terminal screensaver <-replaced by maim
exec tint2 & <- for panel
konsole kde terminal 
guake -drop down terminal
Synaptic remove kernels, install /remove programs if need a graphic option instead of terminal

sudo apt update &&  sudo apt upgrade -y
sudo apt install i3 ranger comptom/picom nitrogen rofi lxappearance pcmanfm alsamixer guake ncdu

commands:
Find /boot/vmli* shows installed kernels from the terminal
sudo apt-fast to update the system faster (Debian)
