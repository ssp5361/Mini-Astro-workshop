# Mini-Astro-workshop
Set of lectures on various topics in astrophysics by early PhD and Master's students. [Link](https://sites.google.com/view/surendrapadamata/mini-astro-workshop) to the schedule and other details of the workshop.

# Pre-Workshop Instructions
## BASH
To get a working *bash* login shell which is essential for the workshop. If you already have *bash* or know how to get one, please ignore this sub-section and move onto the next one. One can also dual-boot or remove windows and fresh install Ubunutu or other linux distro but please do only if you are familiar with the terminal.

* MacOS:
  * Please make sure your default login shell is 'bash'. Previous versions of macOS except catalina came with bash as the default login shell.
But if you have macOS catalina installed and if login shell is zsh or something else, 
you can switch to 'bash'. Follow this [webpage](https://www.howtogeek.com/444596/how-to-change-the-default-shell-to-bash-in-macos-catalina/) for more details.

* Windows:
You have a choice to either install WSL1 or WSL2, we suggest WSL1 as it is light-weight on the side of resource consumption and additional layers.
  * Win10 or previous versions, doesn't come wiht a pre-installed bash shell. To to be able to use bash-linux commands on Windows, one has to either install WSL or WLS-2. More details on how to install can be found [here](https://www.windowscentral.com/install-windows-subsystem-linux-windows-10#install_linux_subsystem_settings_windows10). 
  * When asked for a linux distro, please choose Ubuntu or any other linux distro too if you have researched about various distros previously.
  * If you already know how to use powershell on windows, follow these [steps](https://www.windowscentral.com/install-windows-subsystem-linux-windows-10#install_linux_subsystem_powershell_windows10) to install WSL 1.

## Creating a Git account
To access materials, follow and work through this workshop lectures and exercises, you need to create a github or bitbucket account. Please make your account today either on Github at [link](https://github.com/) or on bitbucket at [link](https://bitbucket.org/product/) using some email address.

## Install Git, SSH and other tools on your laptop
# git
Please make sure git is installed on your laptop. You can check this by typing 'git --version' on your terminal. If it's not installed, open the terminal and please follow these instructions:

* On Ubuntu or Debian: 
  * `$ sudo apt update`
  * `$ sudo apt install git`

* On MacOS:
  * `$ xcode-select --install`

For more details on how to install and configure your git on different OS plaforms, please refer to this [link](https://www.digitalocean.com/community/tutorials/how-to-contribute-to-open-source-getting-started-with-git) and the [other](https://www.atlassian.com/git/tutorials/install-git)

## SSH
Please make sure SSH is installed on your laptop. You can check this by typing 'sudo systemctl status ssh' on your terminal. If it's not installed, open the terminal and please follow these instructions:

* On Ubuntu or Debian:
  * `$ sudo apt update`
  * `$ sudo apt install openssh-server`
More details on ssh on Ubuntu, please refer to this [link](https://linuxize.com/post/how-to-enable-ssh-on-ubuntu-18-04/)

* On MacOS:
Firstly, please install 'brew' (a package installer on mac, which eases your job of installing new software), using the follow command:

For MacOS Catalina, macOS Mojave, and MacOS Big Sur:
  * `$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

For macOS High Sierra, Sierra, El Capitan, and earlier:
  * `$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Then install ssh using:
  * `$ brew install ssh`
More details on HOMEBREW can be found at [link](https://brew.sh/)

## wget
It's a command used for downloading various types of files to your laptop.

* On Ubuntu or Debian:
  * It should come pre-installed.

* On MacOS: 
  * `$ brew install wget`

# Workshop Instructions and Resources

## [Day 1 (September 19th 5:30pm-7:00pm IST)](https://github.com/ssp5361/Mini-Astro-workshop/tree/master/Day-1)
## [Day 2 (September 20th 5:30pm- 6:30pm IST)](https://github.com/ssp5361/Mini-Astro-workshop/tree/master/Day-2)
## [Day 3 (September 27th, 4:30pm-5:30pm IST)](https://github.com/ssp5361/Mini-Astro-workshop/tree/master/Day-3)
  



  
  
