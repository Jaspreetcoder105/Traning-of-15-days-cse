# Traning 
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


### 《《 Difference between linux and window 》》
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

#### <<Key Functions:>>

1. Command Execution: The shell executes commands and scripts.

2. User Interface: The shell provides a command-line interface (CLI) for users to interact with the system.

### shells are divided into two parts.
■ command shell 
![image](https://github.com/user-attachments/assets/a9bf2293-44bf-416b-8f91-0672f8ea9885)

■ graphical shell.
![image](https://github.com/user-attachments/assets/ef3a27b6-3a15-47c0-b13f-0f911393166f)


### Commands:
- `date`: Returns current date.
- `whoami`: Returns the current domain and user name.
- `ls` (list): Returns content of a specified Directory
- `cd`: Changes directory.
  

- `mkdir`: Creates a new directory.
- `pwd`: Prints the current working directory.
  


- `touch`: Creates empty file.
- `cat`: Creates file with content.
  
  
- `whereis`: Finds the location of specified file.
  

- `mv`: To move or rename a file.
  
  
- `cp`: To copy content of a file to the other.
  

- `whatis`: Gives short description of a command.

  ![sc6](https://github.com/user-attachments/assets/067afe97-881b-4c32-a0b2-22d1ff6adbb2)
  ![sc5](https://github.com/user-attachments/assets/31750873-a9a1-4e41-aee1-63a7a558095f)
  ![sc4](https://github.com/user-attachments/assets/ff57149b-4d54-4c3f-92fe-c737ed454307)
  ![sc3](https://github.com/user-attachments/assets/ad2c5093-d875-42a5-bb52-2c9c7244af25)
  ![sc2](https://github.com/user-attachments/assets/03fef69e-472e-4548-8643-8f45d5033309)
  ![sc1](https://github.com/user-attachments/assets/dc8f025c-4569-4ad1-8f57-5cff8d9f611b)


 
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

![image](https://github.com/user-attachments/assets/19f4e61f-b1c3-4b79-bb14-aaaafc5a4905)


## day3(27-june-25):
### permissions and shell programming:
#### file and directory permisions:
#### *chmod* (change mode):
it is use to change the access of the files.
notations:
#### *chmod 444*:
it changes file to readable only no one can change the data inside the file.
![Screenshot (14)](https://github.com/user-attachments/assets/2599fdfe-168c-44f9-868b-8f4bd0504da6)
the result will be :
![Screenshot (13)](https://github.com/user-attachments/assets/72522676-65d9-4328-9586-f96bf263b527)
#### *chmod +x*:
it simply give permission to read the file
#### *chmod 644*:
By using this command the file can be converted into readable by everyone but no one can change the data of the file expect the owner.
![Screenshot (16)](https://github.com/user-attachments/assets/56b77c08-0a89-47fb-90a7-480e4b62f51c)
the result will be :
![Screenshot (15)](https://github.com/user-attachments/assets/bcd2723b-5d45-45ab-ab5b-db4a452a81f0)





