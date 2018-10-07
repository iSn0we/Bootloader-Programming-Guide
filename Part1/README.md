# Part 1

## Setting up requirements

So, the 2 programms, we will use the most should be preinstalled, in the most Linux Distros.


### Installing Bochs

For testing our bootloader, we will be using a programm called Bochs. To install bochs, open a new terminal and type in:
```console
luca@CentOS:~$  sudo apt-get install bochs-x
```
After you've installed Bochs, we have to set it up.
For this, we will create a new folder on your desktop, for this Project.
```console
luca@CentOS:~$  cd ~/Desktop
luca@CentOS:~/Desktop$  mkdir MyBootloader
luca@CentOS:~/Desktop$  cd MyBootloader
luca@CentOS:~/Desktop/MyBootloader$  nano bochsrc.txt
```
Now we will configure our Bochs setup.
Before we can start, please download this file. Its the Default and newest Bochs BIOS Image.

