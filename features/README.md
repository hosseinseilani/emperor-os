# Overview
The default user account of Emperor-OS is user and also the password of it is user.

* Username: user
* Password: user

The password of root account of Emperor-OS is user.
* Username: root
* Password: user


# Package manager in Emperor-os:

Different from other distro where one has a package manager that download and install a package, Emperor-OS uses per-compiled packages. It save your time and decrease the complexly of installing the programs. Also it have 6 package managers such as: dpkg, apt, aptitude, Tasksel, gdebi, synaptic.

*apt --version
*gdebi --version
*aptitude --version
*dpkg --version
*tasksel
*sudo synaptic

#Grub boot menu

Emperor-OS is a live distribution and also can be install on Hard disk, which means that the running environment is constructed in your system's memory when you boot it up. The ISO image is 'isohybrid' can be run on CD, flash drive, or hard drive used to construct this live file system.
You can modify and customize the way your system boots, and resolve or work around many hardware issues by using cheat codes. Cheat codes are passed to the system by pressing TAB at the boot.

# Permanent Aliases Commands:
Linux users are always using one command over and over. We created many aliases by default for the most commonly used commands to save your time. Aliases are custom shortcuts used to display a widely used command.

# Currently pre-defined Aliases in Emperor Linux

## Here you can see the default aliases defined for your user in emperor-os 18.04.
*alias off='sudo poweroff -f'
*alias reb='sudo reboot -f'
*alias syn='sudo synaptic'
*alias t='sudo xfce4-terminal'
*alias ug='sudo apt dist-upgrade'
*alias up='sudo apt update' alias cm='sudo chmod'
*alias def='sudo update-alternatives --config '
*alias egrep='egrep --color=auto'
*alias fgrep='fgrep --color=auto'
*alias fix='sudo apt -f install && sudo dpkg -a --configure'
*alias fm='sudo thunar'
*alias grep='grep --color=auto'
*alias l='ls -CF'
*alias la='ls -A'
*alias ll='ls -alF'
*alias ls='ls --color=auto' 
