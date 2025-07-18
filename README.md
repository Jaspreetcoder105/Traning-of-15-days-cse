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
## DAY-5(1-july-2025):
### GPU(Graphics Processing unit)
It is a specialized chip designed to perform many calculations at once, especially for rendering graphics and handling parallel tasks.
It was originally made for gaming and image rendering ,but now widely used in AI, data science, and video editing for super-fast processing 
It’s like having thousands of tiny workers inside your computer, all solving problems together. 
In simple words its :
 ~Responsible for rendering graphics and visual output.
 
 ~Problems include overheating, driver issues, screen tearing, or no display output.

 ![image](https://github.com/user-attachments/assets/221c8453-6dc3-4843-9545-d9aa12d05597)

 ### PCU (Personal Computer unit):
1. Installation & Hard Disk Preparation:
   
##### Partitioning: 
 The first step of Partitinong is to organize the hard disk into:
 Primary (C: Drive):
      
  - Where the Operating System (Windows/Linux/Unix) is installed.
      
  - Avoid storing personal/important files in C-Drive

  ![image](https://github.com/user-attachments/assets/1a945b27-e794-4d28-ba36-b33fadfd36fb)

##### Why C-drive?
Because , In case ,If Windows crashes, files in D,E,F-Drive are safer and can often be recovered. if we put files in same Drive then there will be Data loss if window get crashed.

![image](https://github.com/user-attachments/assets/6ea1ea19-4f63-49e8-a1b4-8f0d936e9126)

##### Logical Drives (D:, E:, F:):
      Used for pictures, videos, documents, etc.
#### performace regression /Slow performance :
-The speed of system slowed down due to some reasons like ; memory full, less RAM, Viruses.

this issues can be resolved by using system efficiently , and use antiviruses .

-Keeping the files and Documents in Desktop also make system slow , so keep the files and folders out of Desktop.

-Taskbar: keep taskbar clean . close the apps which are not in use.

-Bookmarks: Booksmarks also slows down the speed . because system keep running them in background .

-Temporary files : The files that get created by default during web browsing are temporary files . These can also be the cause of slower performance.

while web browsing some websites ask permmision to accept cookies by which these temporary files are created.

-Malvares : keep your system updated and scan for viruses every month atleast.

#### Concept of Optimisation:
Optimization means making something as good, efficient, or effective as possible.

In the computer world, it often refers to:

- Speeding up software or hardware so it runs faster or uses fewer resources

-Improving algorithms to solve problems more efficiently

-Reducing energy use in devices or systems

![image](https://github.com/user-attachments/assets/d53b289d-72cc-44f3-be84-1e35c2ea8a81)

#### DEFRAGMENTATION:
Defragmentation is the process of reorganizing fragmented data on a hard disk so that related pieces are stored close together. This improves file access speed and overall system performance on traditional HDDs. It’s not needed for SSDs, which use a different method called TRIM.
#### DRIVERS:
Drivers are software that let the operating system communicate with hardware like printers, keyboards, or graphics cards. Without them, hardware won’t work properly.
#### ISSUES FACED WHILE USING PRINTER:
Here’s a compact list of common printer issues and how to fix them:

![image](https://github.com/user-attachments/assets/dcd9d0ab-75e5-41ab-8856-7abca11e3fd5)

1. **Printer not printing**  
   - *Cause:* Connectivity issues or outdated drivers  
   - *Solution:* Check cables/Wi-Fi, restart printer and PC, reinstall or update drivers

2. **Paper jams**  
   - *Cause:* Misaligned or poor-quality paper  
   - *Solution:* Gently remove jammed paper, align guides, use recommended paper type

3. **Low ink warnings (even when ink remains)**  
   - *Cause:* Inaccurate ink sensors  
   - *Solution:* Keep printing until quality drops; replace only when necessary

4. **Slow printing**  
   - *Cause:* High-resolution settings or complex documents  
   - *Solution:* Lower print quality settings, use draft mode for basic prints

5. **Poor print quality**  
   - *Cause:* Dirty print heads or low ink  
   - *Solution:* Run print head cleaning utility, check ink levels

6. **Printer offline**  
   - *Cause:* Network or driver issues  
   - *Solution:* Reconnect to network, set printer as default, restart spooler service
###  Blue Screen of Death (BSOD):
It is used to indicate a system crash, in which the operating system reaches a critical condition where it can no longer operate safely.

![image](https://github.com/user-attachments/assets/758e6a03-e650-4c7d-b3f1-a83181e34d2b)

**Common Causes of BSOD:**

1. Hardware Failures: <br>
   Faulty RAM, hard disk, or other internal components
2. Driver Issues: <br>
   Outdated, incompatible, or corrupted device drivers
4. Corrupted System Files: <br>
   System file corruption due to improper shutdowns, malware, or failed updates
5. Overheating or Power Issues: <br>
   Inadequate cooling or power supply malfunctions
## Day7(3-july-25):
### Network:

 when two or more hosts are connected and can communicate, the connection between them is said to be network.
 ### Host:
 Host is any device which sends or receive data traffic over a network. For example a computer, it can also include other networked devices.
 ### Server:
  Server is a computer designed to respond to requests from clients. It serves the requested data or services to the user.
  ### Client: 
  Client is a host that initiates requests for services from another device on the network. Simply we can say the user which interact with the server.
  ### Traffic:
  It refers to the data sending or receiving. when someone send data to other using network.
  ### IP address:
full form: Internet Protocol.
where protocol refers to the set of rules which govern the data transmission.
Properties:

Unique: Each device on a network must have a unique IP address.

Universal: IP addresses are a globally recognized standard for network communication.

Types:

Public IP Address: Used on the internet, these addresses are globally unique and routable.

Private IP Address: Used within private networks (e.g., home or school networks), these addresses are not directly routable on the internet.

Dynamic Nature: IP address can change over time, especially for devices on dynamic IP assignments. However, its fundamental properties (uniqueness and universality) remain constant.

### IPV4:
Internet Protocol version 4
An IPv4 address consists of series of four eight-bit binary numbers which are separated by decimal point. Although any numbering system can be used to represent a unique 32- bit number, most commonly you see IP address expressed in dot decimal notation.
#### IPv4 Address Format:

An IPv4 address consists of 32 bit (binary digit), grouped into four section of known as octets or bytes. Each octet has 8 bits and this bits can be represented only in 0 or 1 form, and when they grouped together, they form a binary number. Since each octet has 8 bits, it can represent 256 numbers ranging from o to 255. These four octets are represented as decimal numbers, separated by periods known as dotted decimal notation. For example IPv4 address 185.107.80.231 consists of four octets.
#### Binary Representation:
IPv4 is basically converted into binary form by computer although these are usually seen in decimal form for human readability. Each octet is converted into 8 bit binary number . For instance 185.107.80.231 in binary looks like:
![image](https://github.com/user-attachments/assets/2247b1e7-421c-4a3b-9db4-bdf5f9dff972)

185: 10111001
107: 01101011
80: 01010000
231: 11100111

### IPV6:
Internet Protocol Version 6
The Internet Protocol version 6, or IPv6, is the latest version of the Internet Protocol (IP), which is the system used for identifying and locating computers on the Internet. IPv6 was developed by the Internet Engineering Task Force (IETF) to deal with the problem of IPv4 exhaustion. IPv6 is a 128-bit address having an address space of 2128, which is way bigger than IPv4. IPv6 uses a Hexa-Decimal format separated by a colon (:).
#### Components in IPv6 Address Format:
There are 8 groups and each group represents 2 Bytes (16-bits). 
Each Hex-Digit is of 4 bits (1 nibble)
Delimiter used - colon (:)

![image](https://github.com/user-attachments/assets/1c29e8ab-6b31-40ae-9c51-29f8dc6defed)

 ### Classes in IP:
![image](https://github.com/user-attachments/assets/2b5b145f-15e2-4cbd-88c7-e3fcc4fda740)
### DIFFERENCE BTW UNICAST, MULTICAST, BROADCAST.
![image](https://github.com/user-attachments/assets/598ac0f3-d66e-4a5f-ac18-61793fdb4e04)

### Subnetting:
A subnet is like a smaller group within a large network. It is a way to split a large network into smaller networks so that devices present in one network can transmit data more easily. For example, in a company, different departments can each have their own subnet, keeping their data traffic separate from others. Subnet makes the network faster and easier to manage and also improves the security of the network.

Bandwidth: Capacity of network; data transmission rate (e.g., Mbps). Should be maximum.

Latency: Delay in data transmission. Should be minimum.

Host Bits: Denoted by '0's in subnet mask.

Network IP: First IP of a subnet (cannot be assigned to host).

Broadcast IP: Last IP of a subnet (cannot be assigned to host).
### MAC address:
MAC Addresses are unique 48-bit hardware numbers of a computer that are embedded into a network card (known as a Network Interface Card) during manufacturing. The MAC Address is also known as the Physical Address of a network device. In the IEEE 802 standard, the data link layer is divided into two sublayers:

Logical Link Control (LLC) Sublayer

Media Access Control (MAC) Sublayer

The MAC address is used by the Media Access Control (MAC) sublayer of the Data-Link Layer. MAC Address is worldwide unique since millions of network devices exist and we need to uniquely identify each. 

A MAC address uniquely identifies network interfaces. For more on networking fundamentals and concepts like MAC addresses, the GATE CS Self-Paced Course is a comprehensive guide.
![image](https://github.com/user-attachments/assets/7fd70f8e-2403-4309-8fe3-3b83311dec1b)
### DNS:
It is a naming system for computers, service etc connected to the Internet or a private network. It translates domain names (www.google.com) into machine-readable IP addresses (172.217.160.142).
### DEFAULT GATEWAY:
Its a device (typically a router) that acts as a pathway for data to leave a local network and reach other networks, including the internet.

## Day 8(4-july-25)
### Networking commands:
#### ping:
it means : "Hey, are you there?" It's used to check if another computer, server, or website is currently online and reachable from your PC.
 ping sends ICMP (Internet Control Message Protocol) Echo Request packets to a target host.

If a reply is received, the host is active.
Otherwise, its blocked.
Syntax: ping website_address

### loopback Address (127.0.0.1):

This IP always refers to "yourself" – your own computer.It's used to test the network configuration of your local PC.
Example: Like sending a letter to your own house to test if your mailbox works.
### TRACEROUTE:
The traceroute command is a network diagnostic tool used to track the path that data packets take from your computer to a specified destination, such as a website or an IP address. It helps identify network problems by showing each hop (router) the packets pass through and the time it takes to reach each hop.

##### How Traceroute Works

Traceroute sends a sequence of packets using the ICMP protocol, similar to the ping command. Each packet has a time-to-live (TTL) value that starts at 1 and increments with each subsequent packet. When a packet's TTL reaches 0, the router discards the packet and sends an error message back. This process continues until the packet reaches its destination, allowing traceroute to map out the path and measure the delay at each hop.

###### Using Traceroute

To use traceroute, open a command prompt or terminal window. On Windows, type cmd in the search bar and press Enter. Then, use the following syntax:

tracert [hostname or IP address]
### IPCONFIG:
The ipconfig command is a powerful tool in Windows that displays all current TCP/IP network configuration values and refreshes Dynamic Host Configuration Protocol (DHCP) and Domain Name System (DNS) settings. It is commonly used for troubleshooting network issues and managing network settings.

##### Basic Usage
This will display the basic network information for all network adapters, including IPv4 and IPv6 addresses, subnet mask, and default gateway.
##### Syntax: ipconfig websitename\ipaddress
|Term	|Represents|
|---------------|--------------|
|inet	|IP address|
|netmask	|Network range|
|lo0	|Loopback|
|broadcast	|Address used to send messages to all devices.|


### Comparison of Network Types
|Network Type	|Definition	|Type|
|----------|----------------------------------------------|---------------------|
|Ethernet|	A specific wired technology for local area networking.|	LAN Technology (Wired)|
|Wi-Fi|	A specific wireless technology for local area networking.|	LAN Technology (Wireless)|
|LAN|	A network connecting devices within a limited area (e.g., home, office)|.	Local Network|
|WAN	|A network that spans a large geographical area, often connecting multiple LANs.|	Wide Network|
|Internet|	A global system of interconnected networks using the Internet Protocol (IP) suite.|	Global WAN|
## Day9
### HTML: 
it s a programming language used to create web pages and to design websites.
html stands for hyper text markup lanuage.
#### How browsers render the html:
1. The browser reads the HTML file line by line.

2.It builds the DOM (Document Object Model) - a tree-like structure of the page.

3. The browser then displays the structured content visually based on HTML + CSS.
### Structure of html:
HTML Structure:

HTML (Hypertext Markup Language) is used to define the structure and content of web pages. Here's a basic structure of an HTML document:

<img width="272" height="180" alt="image" src="https://github.com/user-attachments/assets/b7f7c2e1-9891-4a07-85f1-60642e839f99" />


Explanation:
1. !DOCTYPE html: Declares the document type and version of HTML.

2. html: The root element of the HTML document.

3. head: Contains metadata about the document, such as title, charset, and links to stylesheets or scripts.

4.title: Sets the title of the page, displayed in the browser's title bar or tab.

5. body: Contains the content of the HTML document, such as text, images, and other elements.
## Day10:
#### Some Common HTML Tags:

<img width="307" height="180" alt="image" src="https://github.com/user-attachments/assets/6dbed445-f338-4f7f-9777-ed6a765781b0" />

## Day11:

### Semantic HTML Elements:

Semantic HTML elements provide meaning to the structure of a web page, making it easier for search engines and screen readers to understand the content. Here are some common semantic HTML elements:

<img width="411" height="481" alt="image" src="https://github.com/user-attachments/assets/d20dfc8d-10ab-4dae-bf29-0dea1fb8f8fc" />

###### Benefits:
1. Improved Accessibility: Semantic HTML elements help screen readers and other assistive technologies understand the structure of the content.
2. Better Search Engine Optimization (SEO): Search engines can better understand the structure and content of the page.
3. Easier Maintenance: Semantic HTML elements make it easier to maintain and update the structure of the content.

By using semantic HTML elements, you can create a more structured and accessible web page that is easier to understand for both humans and machines.

1. header: Defines a header section for the document or a section.

2. nav: Defines a navigation section.

3. main: Defines the main content section.

4. footer: Defines a footer section.

5. section, article, aside: Define different types of content sections.
### Day 12:
#### webpage example using html:
<img width="1366" height="768" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/8600e9d8-0b28-4b83-b2b8-e58798b9d100" />
<img width="1366" height="768" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/d02cd032-8669-4308-843f-38f019c241be" />
<img width="1366" height="768" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/7a0a5584-836c-411d-8438-c0657c1a1815" />
<img width="1366" height="768" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/a0fe3155-7830-4fc3-963b-47287602d49f" />
<img width="1366" height="768" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/95949010-9e15-4a52-9ab5-77d569814e7f" />
<img width="1366" height="768" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/5fe0a3e7-855e-4750-8f2e-0dea99a5e5c3" />
## Day13:
### GIT:
Git is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency
It helps you keep track of code changes, collaborate with other developers, and manage different versions of your codebase.
-Git is used to tracking changes in the source code

-The distributed version control tool is used for source code management

-It allows multiple developers to work together

-It supports non-linear development through its thousands of parallel branches

### Features of Git
-Tracks history

-Free and open source

-Supports non-linear development

-Creates backups

-Scalable

-Supports collaboration

-Branching is easier

-Distributed development
<img width="406" height="235" alt="image" src="https://github.com/user-attachments/assets/453b9a79-cf01-4cf4-a056-30b8eba7c93e" />

### How to use github?
Github is very easy to use website . it is used by almost every coder .
##### Getting Started with Git
Step 1. Install Git
Download and install Git from Git's official website. Follow the instructions for your operating system.

Step 2. Configure Git
Set up your name and email to identify your commits:

Step 3. Create a New Repository
To start a new project, create a new directory and initialize it as a Git repository:
<img width="1366" height="768" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/2532bffa-6f73-48d0-b270-b468d64a0645" />

 now open the git app and run the command git clone link of your repository
 <img width="1366" height="768" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/0c3fc782-6908-45ed-b8b1-4227a71a0e97" />

Step 4. Clone an Existing Repository
To contribute to an existing project, clone a repository from GitHub:
##### Clone command:
this command is used to create the clone of original repository.
<img width="1366" height="768" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/46afb041-28b3-4e85-bd11-20ef80196437" />

Step 5. Track Changes
Add files to your repository and track changes:
###### touch command:
to create a file touch command is used
syntax: touch filename.
<img width="1366" height="768" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/3d01bc0c-3b53-473e-80d2-4e4bc7e3dd7c" />

#### GIT STATUS:
this command is used to just check the status of the repository.
<img width="1366" height="768" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/31c6c8bb-bdf2-4f79-8c2f-e362ed3c017e" />
#### nano command:
use to enter data in to the file .
<img width="1366" height="768" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/87cca5c5-d30b-4b8c-a9b0-c243aad949a0" />
it opens the editor where data can be enterred.
#### git commit -m
use to add file to the origial repository.
<img width="1366" height="768" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/f9f63dbb-0546-47b0-9e0a-64f9d445d906" />
<hr>
the file is get added to the repository
<img width="1366" height="768" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/26ac4ab0-9667-4401-ac06-efb27001e228" />
 <h1> DAY 14</h1>
 <h2>BRANCHING:</h2> branching allows you to work on new features without affecting the main branch.
 in simple we can create the new branch to edit or work on our repository without commiting changes in main branch as main branch is one who contain the main repository.
 <h2> commands:</h2>

git branch <branch-name> – creates a new branch.

git checkout <branch-name> – switches to the branch.

git switch <branch-name>– alternative to checkout (recommended in newer versions).

git merge <branch-name> – merges the specified branch into the current branch.

git push -
### Creating the branch and switching the branches :
<img width="1366" height="768" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/cfdc473f-ec96-4ef7-8e63-abf2ea8e88b9" />
#### The branch is get created here:
<img width="1366" height="768" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/b8d461d9-46d5-4984-b814-1356183e34fc" />
### adding file to the repository:
<img width="1366" height="768" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/5a6f3e9d-2d2b-441a-823e-34302fe14426" />
#### file get added:
<img width="1366" height="768" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/693bfb31-066b-4bd0-92b3-d2113827d71c" />
### git push and git merge repository:
<img width="1366" height="768" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/996e54a6-115e-41fd-b21a-8c6b1861d5d1" />
<img width="1366" height="768" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/633918a3-b4e7-4bf7-8de3-4ad15b13ddab" />




 
