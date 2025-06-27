# Traning-of-15-days-cse
## Day-1 (25-june-25):
*On the first day of traning*
,I've leared about: 

### 《《what is linux?:》》

Linux is an open-source operating system (OS) that is widely used in computers, servers, and other devices. It's known for its stability, security, and flexibility.

### 《《it's uses》》
 •Servers (web, database, file)

 •Desktops (personal computers, laptops)

 •Embedded systems (routers, set-top boxes, loT devices)

 •Supercomputing

 •Scientific research

 •Education

 •Security applications

 •Cloud computing


### 《《Difference between linux and window》》
|linux.  | window |
|-------|--------|
|It is a open source | It's a close source|
|It is free of cost | It requires licensing fees|
|It's more secure than window| More vulnerable to malware and viruses.|
| It's highly customizable | It has limited customisation options|
|linux system is more helpful for programming | On the other hand we can use window for gaming|
### 《《And how to install linux on window system》》
## Day-2 (26-june-25):
### Booting:
fBooting is the process of starting a computer and loading the operating system into memory. It's the sequence of events that occurs when you power on your computer, from the initial hardware checks to the loading of the operating system
Types of Booting:

1. Cold Booting: Starting a computer from a powered-off state.(in mac and linux os)

2. Warm Booting: Restarting a computer without

powering it off (e.g., using the restart option). (in wondow)
 ### 《《what is kerenel?》》
The kernel is the core part of the Linux operating system. It's like the brain of the system, managing hardware resources and providing basic services to applications.
#### 《《key functions of kerenel 》》
◇hardware management 
◇process management
◇memory management
### 《《shell:》》
The shell is a program that interacts with the kernel and provides a user interface to the Linux system. It's like a command center where you can give instructions to the system.

Key Functions:

1. Command Execution: The shell executes commands and scripts.

2. User Interface: The shell provides a command-line interface (CLI) for users to interact with the system.

### shells are divided into two parts.
■ command shell and ■ graphical shell.

Commands:
- `date`: Returns current date.
- `whoami`: Returns the current domain and user name.
- `ls` (list): Returns content of a specified Directory
- `cd`: Changes directory.
  
![](../images/date_whoami_ls_cd.jpg)

- `mkdir`: Creates a new directory.
- `pwd`: Prints the current working directory.
  
![](../images/mkdir_pwd.jpg)


- `touch`: Creates empty file.
- `cat`: Creates file with content.
  
![](../images/cat_touch.jpg)
  
- `whereis`: Finds the location of specified file.
  
    ![](../images/whereis.jpg)

- `mv`: To move or rename a file.
  
  ![](../images/mv.jpg)
  
- `cp`: To copy content of a file to the other.
  
  ![](../images/cp.png)

- `whatis`: Gives short description of a command.
  
## Issues faced:
Running `whatis command` always returns "nothing appropriate"

![](../images/whatis_error.jpg)

**Solution found:**

`whatis` uses an index created and maintained by `mandb` to locate the documentation you're looking for. If said index doesn't exist, or if the command you're looking for isn't in the existing index, you'll see Nothing appropriate. If your setup doesn't have a `mandb` index yet, you can create one by running `sudo mandb`

![](../images/whatis_solved.jpg)
### File system structure:
| NAME | DESCRIPTION                                                                   |
| --------- | ----------------------------------------------------------------------------- |
| `/`       | The slash / character denotes the root of the filesystem tree. exp: Trunk of a tree.|
| `/home`   | Contains personal directories of user. |
| `/lib`    | Contains system libraries and critical file.|
| `/bin`    | Contains user executable files.|
| `/boot`   | Contains all the files that are required for booting.|
| `/dev`    | Contains hardware and development files.|
| `/media`  | Mount points for removable media.|
| `/mnt`    | Temporarily mounted filesystems.|
| `/opt`    | Contains optional files. |

