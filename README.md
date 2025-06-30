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
there are few softwares that can run linux OS without annoying window system.
#### VM ware:
It is a software that is use to run multiple Virtual machines. it is basically paid software but there are some free verions of it.
#### Virtual Machine:
Virtual machine is virtual system that allow to run a OS on it. (eg. linux)
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
### Dual boot:
Dual boot means installing two operating systems (OSes) on the same computer, so you can choose which one to use when the computer starts.
### Bare Metal Instalation:
It the method in which the software is downloaded in any system using a physical drive (pen drive).
### Partition scheme:
1. MBR : Master Boot Record
   Works on most old computers (BIOS systems) and Can have up to 4 primary partitions. It supports drives up to 2 TB only.
2. GPT : GPT (GUID Partition Table) is a newer and better partitioning system used with modern computers. It Supports more than 100 partitions. It Works with large hard drives (over 2 TB) and Stores multiple copies of data for safety.
### ISO file:
An ISO file (or ISO image) is a copy of an entire CD, DVD, or installation disc saved as a single file. It's often used to distribute operating systems or software.

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
#### Echo  command:
This command is used to print the string or a text.
![Screenshot (17)](https://github.com/user-attachments/assets/ea817d1d-d9be-4ccb-93cc-60af80f21d69)
### Redirection :
It does the given below tasks:
~Take input from a file instead of typing it.
~Send output to a file instead of the screen.
#### types of Redirection:
1.Standard Output Redirection (>)
Purpose: Sends output to a file (overwrites if it exists).
![Screenshot (18)](https://github.com/user-attachments/assets/b18e82e9-b944-4f66-8fef-0ab24a409b61)

Saves output of ls to files.txt.

2.Append Output (>>)
Purpose: Sends output to a file without overwriting.

![Screenshot (19)](https://github.com/user-attachments/assets/a4c74afe-929f-4404-b0c1-63a44322302c)


3.Standard Input Redirection (<)
Purpose: Takes input from a file instead of keyboard.

![Screenshot (20)](https://github.com/user-attachments/assets/f60a39d3-aaa6-447e-9b6f-7f7a9972933d)


Sorts the contents of names.txt.
### Pipes:
The pipe is used to combine two or more commands, and in this, the output of one command acts as input to another command.

![Screenshot (21)](https://github.com/user-attachments/assets/f5e8b374-cd0b-47e6-ab97-31dc8cbcfc21)

### Programing using shell programming:
#### Programm to read and display the details of person:
![Screenshot (23)](https://github.com/user-attachments/assets/dd24b55e-1869-43c0-b4e2-7f9184eec996)

![Screenshot (22)](https://github.com/user-attachments/assets/03763006-6f7e-4b78-b83b-e08b2ab6f21f)
#### Programm for multiplication table of any number:
![Screenshot (25)](https://github.com/user-attachments/assets/be119d6a-2b53-46b0-8b40-1405695ebf9a)

![Screenshot (24)](https://github.com/user-attachments/assets/7583ba25-510c-47da-a2af-50b1633ffc7e)
#### Programm to compare values:
![Screenshot (27)](https://github.com/user-attachments/assets/6f1a12ee-e8d9-469e-bfaf-cd6295134dd8)

### Day4 (30-june-25)
#### Gzip and Gunzip command:
##### gzip
What it does: Compresses (makes smaller) files to save disk space.
![Screenshot (28)](https://github.com/user-attachments/assets/424cd757-c4eb-411b-93af-38fd1c64213d)

It Results in:
The original file (filename) is replaced by a compressed file called filename.gz.
##### gunzip
gunzip
What it does: Decompresses (uncompresses) files that were compressed with gzip.
![Screenshot (29)](https://github.com/user-attachments/assets/f1288252-a915-43b5-bcf8-c95525f1128b)

It Results in:
The compressed file (filename.gz) is restored back to the original file (filename).



#### Hardware of computers 🖥:*Computer Hardware:*

Computer hardware refers to the physical components of a computer system. Here are some hardware components:
![image](https://github.com/user-attachments/assets/de2c97cd-f7c9-4728-9e42-c7e823689cef)
#### Types of hardware can be specified as below:
![image](https://github.com/user-attachments/assets/3ee9b75e-4eab-4164-be44-7d5296d518c4)

##### Internal Hardware:
1. *CPU (Central Processing Unit):* The brain of the computer, executes instructions.
2. *Motherboard:* The main circuit board that connects all hardware components.
3. *RAM (Random Access Memory):* Temporary storage for data and applications.
4. *Storage Drive:* A device that stores data, such as a hard drive or solid-state drive (SSD).
5. *Power Supply:* Converts AC power to DC power for the computer's components.

##### External Hardware:
1. *Monitor:* Displays visual output from the computer.
2. *Keyboard:* Input device for typing and controlling the computer.
3. *Mouse:* Input device for navigating and interacting with the computer.
4. *Speakers:* Output device for audio.
5. *Printers:* Output device for printing documents.

##### Other Hardware Components:
1. *Graphics Card:* Controls the output display and handles graphics processing.
2. *Sound Card:* Controls audio output and processing.
3. *Network Card:* Connects the computer to a network.
4. *Cooling System:* Helps regulate the computer's temperature.

#### In Simple Terms:
Computer hardware refers to the physical parts of a computer system, including internal components like the CPU and RAM, and external devices like monitors and keyboards. These components work together to enable the computer to process and store data.
#### Motherboard:
The motherboard is the main circuit board of a computer that connects all hardware components together. It's like the backbone of the system, allowing different parts to communicate and work together.
![image](https://github.com/user-attachments/assets/11c49033-cb19-4e96-ab5e-fea523e63c65)

##### Parts of motherboard:
1. CPU Socket: To Installs CPU.

2. RAM Slots: To Installs RAM modules.

3. Chipset: Manages data transfer, and the performanceof computer depends on it..

4. Storage Connectors (SATA): To Connects storage drives.

5. Expansion Slots :To  Adds expansion cards (graphics, sound).

6. Power Connectors: Connects power supply.

7. BIOS/UEFI Chip: Stores firmware settings.

8. USB Ports: Connects peripherals (keyboard, mouse).

9. Audio Connectors: Connects audio devices (speakers, headphones)
![image](https://github.com/user-attachments/assets/e7d6f9ca-4153-4111-8e8c-cc3587d0e978)


### RAM:
RAM (Random Access Memory) is the short-term memory of a computer. It temporarily stores the data and programs your computer is using right now so it can access them quickly. The more RAM you have, the more things your computer can do at once without slowing down.
![image](https://github.com/user-attachments/assets/55a42bf2-ceb4-491b-a6e1-e7cf587cfdee)

### Hard Drive:
A **hard drive** (or **hard disk drive**/ HDD) is the part of a computer that stores all your data like your photos, documents, programs, and even the computer’s operating system. Unlike RAM, which is temporary, a hard drive keeps your files even when the computer is turned off. It's like your computer’s long-term memory.
![image](https://github.com/user-attachments/assets/b983dec5-4233-42a5-b912-758d1b8be20f)
### ROM:
ROM stands for Read-Only Memory. It is a type of memory in a computer that stores important instructions that don’t change, like the code your computer needs to start up.
###### Here are some key points of RAM:

* **“Read-only”** means you can read the information from it, but you usually can’t change it.
* It **keeps its data even when the power is off**.
* ROM is used to store **firmware**, which is the basic software that helps start and control the computer.
![image](https://github.com/user-attachments/assets/4a950171-9064-4501-9e2e-3e9feab7b44f)
### Difference between RAM , ROM and HDD:

| Feature                       | RAM (Random Access Memory)         | ROM (Read-Only Memory)          | HDD (Hard Disk Drive)                    |
|------------------------------|------------------------------------|----------------------------------|------------------------------------------|
| **Type of Memory**           | Temporary (Volatile)               | Permanent (Non-volatile)         | Permanent (Non-volatile)                 |
| **Purpose**                  | Runs active programs and processes | Stores startup instructions       | Stores files, software, and operating system |
| **Data Lost When Power Off?**| Yes                                | No                               | No                                       |
| **Can You Change Data?**     | Yes (temporarily)                  | Usually No (some types updatable)| Yes                                      |
| **Speed**                    | Very Fast                          | Fast (but less than RAM)         | Slower than RAM and ROM                  |
| **Example**                  | Running apps like games or browsers| BIOS or bootloader code          | Movies, photos, documents, applications  |

#### Simple Analogy:
-  **RAM**: Like your desk — holds what you're working on right now.
-  **ROM**: Like a manual — gives instructions, but you can’t change it.
-  **HDD**: Like a filing cabinet — stores everything even when the power is off.
#### RAM vs Cache Memory

| Feature                       | RAM (Random Access Memory)           | Cache Memory                          |
|------------------------------|--------------------------------------|----------------------------------------|
| **Location**                 | On the motherboard                   | Inside or very close to the CPU        |
| **Speed**                    | Slower than cache memory                               | faster than RAM            |
| **Size**                     | Larger (GBs)                         | Smaller (KBs to a few MBs)             |
| **Purpose**                  | Stores data for running programs     | Stores frequently used CPU instructions and data |
| **Cost**                     | Cheaper than cache memory per MB                       | More expensive per MB                  |
| **Access Time**              | Slower compared to cache             | Extremely quick (nanoseconds)          |
| **Controlled By**            | Managed by OS and programs           | Managed automatically by hardware      |
| **Type of Memory**           | Volatile (data lost when power off) | Volatile                               |

##### Simple Analogy:
-  **RAM**: Like a big table — you put all your work materials on it.
-  **Cache**: Like a small tray right next to your hand — it holds only the most used items for super-fast access.
-  ![image](https://github.com/user-attachments/assets/d20b9d2d-357c-49cb-a4b6-0424cb63b54f)

##### Why cache memory is needed:
Cache memory is needed because it’s **faster than RAM** and is located **closer to the CPU**. It stores **frequently used data**, so the CPU can access it quickly without waiting, which makes the computer run faster and more efficiently.
![image](https://github.com/user-attachments/assets/add809a8-fb63-4513-b69a-9c79a141c07e)

### Process of booting:

###  What is Booting?

Booting is what happens **when you turn on your computer** — it’s the process that gets everything ready so you can use it.


Step-by-Step (Simple Words):

1. **Power On** 
   You press the power button. The computer wakes up.

2. **Self-Check** 
   It checks if parts like the keyboard, screen, and memory are working.

3. **BIOS/UEFI Starts** 
   A tiny program in the computer (stored in ROM) starts running to help the system start.

4. **Finds the OS** 
   It looks at the hard drive to find your operating system (like Windows or Linux).

5. **Loads the OS** 
   It brings the OS from the hard drive into memory (RAM).

6. **You See Login Screen** 
   Your computer is ready for you to use

~ Simple  example to remember:

It’s like waking up, brushing your teeth, putting on clothes, and getting ready for the day. That’s what your computer is doing when it boots.

![image](https://github.com/user-attachments/assets/823736e6-fa84-4099-8e03-247dfe543b94)




