#### The TOPIC we will cover in this class
- Linux File Hierarchy
- VIM
- NANO
- Linux user management
## System Files 
- **system files** : are files used by the system software (OS).
  - This system files are located:-
    1. In window :- local disk (c)
    2. In Linux :- its under the root directory (/)

### File structure in detail (**Linux file hierarchy**)
---
1. / (Root):- *every single file and directory starts from the root directory.* we have learn about it in [[class3;Linux for user]]
  - only the root user has the right  to write under this directory.
  - and in the /root directory there is root directory which is used to store all the file of the root user.
2. *bin*:- Binary executables :- *In Linux every thing is file*
    - all the commands are found in this folder
3. /boot :-*grub files are located under /boot*
4. /dev (device):- It includes terminal devices ,usb or any device attached to the system in a form of files. 
  - EG :- sda means hard disk so in /dev there are sda1, sda2...
 5. **/etc (extra)**:- contains configuration files required by all programs.
   - This contains start up and shut down shell scripts .
   - our password and all user that has been created are stored in here.
 6. **/home **:- All the personal data are stored in here.
    - /home will display only the file which  is named after the user name ![[cd home   cmd.png]]
       By the way I have 3 user gtst and test were exercise to create new user. 
    - But if we put /home/etsubdink   (the combination is called ~ (tilda) )
![[home and etsubdink.png]]
It will automatically list all of this.
7. /lib:- *library essential for the binaries in /bin & /sbin*
8. /media :- mount points for removable media such as CD-ROMS , flash
9. /mnt :- temporarily mounted file note that it says file not removable media if so its /media.
10. **/opt (optional application software package)**:- I mean isn't the name it self an explanation.
11. **/sbin* (essential system binaries):- command using SUDO.
    - so with normal command we can access file that are found in /bin but to access file that are found on /sbin we need the command SUDO.
    - EG of file that are found on /sbin:- **adduser**
12. /tmp:- storage for temporal file.
    - NOTE:- if the system is rebooted or restarted this tempo file will be deleted.
13. /usr (user utilities):- impo file for the user is found in here.

  #### Text Editors
  - These are programs that used for text processing like notepad.
  - Linux command line text editor
     1. VIM
     2. Nano 
     3. Emacs
     4. Neovin

 - Linux Graphical text editors
   1. Sublime
   2. Vscode (were mentioned in [[class1;Introduction to ethical hacking]]
   3. Gedit
   4. Pluma
### VIM
---
Before its name was vi , which is the primary editor used on Unix ,It was line editor after vi now its named as VIM. 
- The vim editor is very powerful and same time it is cryptic.
- **It have mainly to modes** *by default when we open it will be in the command mode.*
  1. COMMAND mode:- where you can insert command.
  2. INSERT mode :- where you can write the notes.

#### vim command 
  - To be in a *command mode first touch the 'esc' key*in the keyboard, after this it will be in a command mode. And *touch i to be in the insert mode.**
    - **:w then enter**(save):- this will save the text to know if its   saved or not , it will say written in the bottom line   if its saved.
    - **:q then enter**(exit):- this command will exit from vim.
    - **:wq then enter**:- this will save it and exit.
    - **:q! then enter**(force quit):- will exit it forcefully without saving the text. we can also use it as *:wq!* 
    - **:u then enter**(undo):- to undo or to make the text you lost appear.
    - **:%!your command**(execute Bash commands):- this will be used for different command like grep, sed...

### Nano
It is user friendly(easy and simple to use).
It really don't need to write down its command because we can easily access them in the bottom. 

### Linux User Management

- To know our name on Linux -> whoami"

##### On Linux there's 2 kinds users.

- Root id = 0
- Normal User id start with 1-999
The root user have the power to do everything on linux

### Creating Users
- On linux, to create users you can use the following command
Useradd -> simple
Adduser -> Detailed
-  Useradd command
   sudo useradd username
- Adduser command
 sudo adduser username
**NOTE**:- When you create a user it creates a group with that name.
#### To access root user

Command *sudo su* 