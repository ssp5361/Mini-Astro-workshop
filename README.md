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

## Day 1 (September 19th 5:30pm-7:00pm IST)
* Topic
  * Introduction to CLI, BASH and Git
* Instructions: 
  * Please make sure that you went through the pre-workshop instructions and that you have a working bash shell terminal, git account and other tools as specified.
* Resources:
  * [Presentation slides](https://github.com/ssp5361/Mini-Astro-workshop/blob/master/presentations/Introduction%20to%20CLI%2C%20BASH%20and%20Git.pdf)
  * [Lecture and tutorial notebook](https://github.com/ssp5361/Mini-Astro-workshop/blob/master/lectures%26tutorials/CLI%2C%20BASH%20and%20Git.pdf)
  * [Exercise sheet](https://github.com/ssp5361/Mini-Astro-workshop/blob/master/exercises/CBG%20Exercises.pdf)
  
## Day 2 (September 20th 5:30pm- 6:30pm IST)
* Topic
  * Introduction to Python and Julia
* Instructions:
  * The lab will be conducted using Jupyter Notebooks on Anaconda platform. Please follow this [link](https://docs.anaconda.com/anaconda/install/) to install Anaconda distribution in your workstations. This part of installation might be covered in the hands-on session if time permits. 
  * Next download and install Julia language and IJulia using this [link](https://juliahub.com/ui/Packages/IJulia/nfu7T/1.21.2).
* Resources
  * [Python Tutorial](https://github.com/aman2010ag/Python-Tutorials/blob/master/Lab0.ipynb)
  * [Julia Tutorial](https://github.com/aman2010ag/Julia-Tutorial/blob/master/Julia%20Tutorial.ipynb)
* For further queries email : agarwalaman2096@gmail.com   

## Day 3 (September 27th, 4:30pm-5:30pm IST)
* Topics:
  * Part 1: Fundamentals of Astrodynamics
    Abstract: Astrodynamics is the study of dynamics of man-made objects in orbit around the earth, moving under the effect of natural and artificial forces. This part of the talk will cover the fundamentals of Astrodynamics, its history, basic mathematical formulation and key concepts. It will also briefly discuss applications of Astrodynamics to satellite orbits around the earth and their practical significance. 
  * Part 2: Space Situational Awareness
    Abstract: This part of the talk will discuss the emerging field of Space Situational Awareness – to have knowledge about our near-space environment with the goal of minimizing threats to life and property – and examine the threat posed by orbital space debris. 
    
* Instructions:
  * There are no prerequisites. This talk will simply be an introduction to what the field is about. Knowledge of classical mechanics may make it more interesting.

* Resources
  * [Fundamentals of Astrodynamics by Roger R. Bate, Donald D. Mueller and Jerry E. White](https://books.google.com.au/books/about/Fundamentals_of_Astrodynamics.html?id=UtJK8cetqGkC&redir_esc=y)
  * [ESA SSA Programme Overview](https://www.esa.int/Safety_Security/SSA_Programme_overview)
  
* For further queries email komalguptag32@gmail.com
  
  
