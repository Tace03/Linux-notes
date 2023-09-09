# Linux-notes
This file contains useful commands that we use for Linux

**1) Commands**
```
cp '-r' <source-folder> <dest-folder>
```
Copy files from source folder to destination folder. Tag '-r' is for whole folder.

```
cd <destination-dir>
```
Move to the desired directory.
```
cd ..(/..)
```
In a more advanced setting, this command moves to the upper directories

**2) Read and edit file**
```
sudo gedit <file>
sudo nano <file>
```
This command is used to read the files in a better manner, no reading from terminal
**3) Network related commands**
```
hostname
```
Print hostname of the device it is holding
```
ifconfig
```
Display full network configuration of the device
```
sudo ifup <target interface>
```
Build up the interface targeted of the device
```
sudo ifdown <target interface>
```
Turn off the targeted network interface
