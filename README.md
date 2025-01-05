#First uninstall termux
#Download termux from

https://f-droid.org/en/packages/com.termux/

#Once Termux is installed, open it and run #the command.
#1 / Setup storage

termux-setup-storage

#2 / update and upgrade

pkg update -y && pkg upgrade -y

#3 / install wget

pkg install wget -y

#4 / download nethunter

wget -O install-nethunter-termux https://github.com/jonathancole85/install-nethunter-termux/blob/main/nethunter-images

#5 / Installing Nethunter

chmod 777 ./install-nethunter-termux
chmod +x ./install-nethunter-termux

#6 / run the script to install Kali.

./install-nethunter-termux

#7 / You must choose an appropriate option 
#for the nethunter you wanted:
#8 / After downloading, it will prompt you #to delete a file called rootfs; simply
#type (N) and continue.
#9 / waiting for extracting tar.jz
