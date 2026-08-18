# Week 2 Learning Objectives

1. Complete 15hours of CompTIA A+ Core 1 (220-1201) 
2. ⁠Learn:
* CPU
* RAM
* Storage
* Motherboard
* Operating systems
* Applications
* Processes
* Files and directories
* ⁠* HDD and SSD
* Partitions
* NTFS
* FAT32
* ext4
* File permissions
* Backups
* Encryption basics 

# CPU(CENTRAL PROCESSING UNIT)

The CPU is the main processor of a computer. It executes instructions and performs calculations so the computer can run programs. It can be called the "brain" of the computer and it also gives instructions to the other component in a computer what to do.

It's best to simplify it as; 

- Fetch 
- Decode
- Execute

CPU gets instrustions. understand and process them then calculate to give result. 

CPU can have multiple cores, e.g, 

- 1 core=1 worker
- 4 core=4 workers e.t.c 

More cores can allow the computer to handle multiple tasks efficiently. 

The speed at which CPU is measured is GHz(gigahertz). e.g, 3.0 GHz, 4.2 GHz..

A higher speed means a core can perform more cycles per second but CPU performance cannot be judged by speed alone. 

I. CPU Features

- Simultaneous Multithreading(SMT) or Hyper Threading
- Threading: A single stream of instructions sent by a software apllication to a processor. 
- Multithreading: It allows a number of threads to be run through the processor or doing multiple task at the same time or simultaneously.
- Symmetric Multiprocessing(SMP)
- Multi Core Processor
- Virtualization

II. CPU Architecture

- X86(IA-32bit) Intel which support 4GB of RAM
- X64(64bit) AMD which can support both the 32bit and 64bit. (AMD is mostly used in mobile devices)

They are common levels in a CPU;

- L1(the fastest and smallest)
- L2 (not as fast as the first)
- L3 (Larger but slower)

CACHE:It is a very fast memory located on or close to the CPU. it's a high speed memoory in the CPU known and it as a small amount of space but very fast. 

CPU generate heat and needs cooling with the use of the cooling fan. 

## CPU Cooling Fan Installation

While installing CPU, it's important to add cooling fan to it to transfer out heat. it's important to add this four parts while installing the CPU;

- CPU
- Thermal paste
- Heat sink
- Processor
- Cooling Fan

All these help to cool the heat while using the CPU. 


# RAM(RANDOM ACCESS MEMORY)

RAM is also called system memory which is use to store data temporarily while the computer is on. it's called "Volatile" which means information is lost when power is removed. RAM is use to load application and files into a non-persistent, fast storage area so the processor can access the data when it need it. RAM is the copmputer temporary working memory. 

I. RAM SPEED

Random Access Memory is measured in GB(gigabytes) e.g, 4 GB, 8 GB, 16 GB, 18 GB, 32 GB, 64 GB
The speed is usually called "Throughput" and it's calculated based on the bus speed and the width of the data bus.

- For Workstation(16GB of RAM)
- For Gaming(32GB/64 GB of RAM) 

NOTE: Using 64bit of processor can access more than 4GB of RAM which is better than 32bit. 

II. MEMORY MODULES

NOTE: Between the memory and the cpu there is somethimg called "memory controller" Bus(control data) then data pathway(send and receive data) and address pathway(location of which the data is from either in 32 bit or 64 bit)

The type of memory to use is determine by the type of motherboard and the form factor. Form factor means(type, size & speed)

TYPES: DDR 3, DDR 4, DDR 5

Dual Date Rate(DDR): This is the most common type of memory used in most system.

- Double Data Rate SDRAM: This doubles the transfer speed of data on Static RAM (SRAM) module. 
- Double Data Rate 2: This is higher and faster access to the external bus calculated as PC 2-4200 to 4200MB/s to 4.2 GB/s
- Double Data Rate 3: This runs at a lower voltage & higher speed than DDR2
- Double Data Rate 4 & 5: They both run in version four & five at 128GB/s e.g PC 5- 42000 to 42000MB/s = 42GB/s

They are other types of memory modlues including the ones that came before the listed above. 

- Synchronous RAM Static Dynamic RAM (SDRAM): First memory module that operates at the same time as the motherboard bus. 
- Small Outline Dual In-Line Memory Module(SODIMM): Smaller memory module that is commonly use in laptops and other compact devices. 
- Dual In-Line Memory Module(DIMM): This is commonly use in desktop computers. 

III. MULTI CHANNEL MEMORY

This allow system to two different memory module to increase the performance and throughput(speed). They include;
- Single Channel Memory: 64bit data bus speed
- Dual Channel Memory :158bit data bus speed
- Triple Channel Memory: 192bit data bus speed
- Quad Channel Memory: 256bit data bus speed. 

# STORAGE

Computer storage is where information or data is kept parmanently even when the computer goes off. it's non-volatile and persistance.

 Things stored on computer can include;

- Window/Linux
- Applicatios
- Photes
- Videos
- Music
- Documents
- Games
- Downloads e.t.c

Storage can also be called Mass storage device(e.g, hard drives, CD roms...) that holds more data but slower than RAM and Cache which is faster than RAM. 

I. STORAGE SPEED

Storage capacity is commonlys measured in:

- KB-MB-GB-TB

They are three types of memory storage;

- Cache
- RAM/System Memory
- Virtual RAM/Virtual Memory: it can be divided into two which are; page files(windows) and swap space(linux, mac, unix) They both mean the same thing. It's a hidden file on a storage device and pretends to be system memory.

There are two types of storage commonly use;

- SSSD(SOLID STATE DRIVES): these are faster than HDD
- HDD(HARD DISK DRIVES): These are not as fast as Cache and RAM. 

II. STORAGE CABLES

They are connect storage devices to the computer's motherboard, allowing data transfer between the storage device and the system. They are different types of cables;

- Thunderbolt: Divided into two(1&2, use all USB C) and (3&4, use on USB C)
- Lighting: Can either use the type c side or other side into the port. it's the one goes into the port that is sending. e.g, iphone charger type c
- Serial Advanced Technology Attachment (SATA): Has two cables(Internal & External storage)

(SATA 7-PIN Data Cable to transfer data only)
(SATA 15-PIN Power Connector to provide the power)
- ESATA(connect harddrive external for external storage)

These days most devices use USB & Thunderbolt for external storage and SATA for internal data transfer. 

NOTE:They are other types of storage cables e.g, Small Computer Systems Interface(SCSI), Single Connector Attachment(SCA), Serial Attached (SCSI)

# HDD

 Hard Disk Drive (HDD) are formal mass storage device and they are any kind of non-volitale storage device that can hold data when the system is powered down at a large scale.

 They are two types of Mass Storage Device;

 - Internal and External 
 - Internal: The device placed inside the computer's case or tower e.g, Harddisk drive, solid state device, optical drive, tape back up, legacy floppy disc drive

 - External: The device that exist outside the computer's case e.g, external USB drive, ESATA drive..

 Hard Disk Drive(HDD): IT'S a device that stores data on a metal or glass platter coated with a magnetic substance. The platter physically spin and read/write heads move over them that is why HDDs are called "mechanical storage". The computer as to physically move these parts to access different data. Inside anHDD are;

 - Platter: The spinning disks
 - Spindle: This spins the platter
 - Read/Write heads: This read/write data 
 - Acuator arm: This moves the heads. 

 ## HDD SPEED

 They are measured in GB/TB

 - Consider speed while buying HDD
 - 5400 RPM Modele is the slowest model of hard drives commonly use in pc
 - 7200 RPM Modele provides faster performance without exceptionally high cost commonly use in computer
 - 10,000 RPM Modele cost more than the 7200 but gives increased performance commonly use gaming, pc, servers..
 - 15000 RPM Modele is one of the highest used inside of a hard drive. 

   HDD are often a cost effective way to get lots of storage because it's usually cheaper per GB. IT's has large storage capacities but slower than SSDs, more vulnerable to physical shock and make noise because of the drive spinning.

   SATA Cables can be use to connect HDD to the motherboard. 

   NOTE: COST(less cost), PERFORMANCE(slower performance), CAPACITY(lower storage)

   # SSD- SOLID STATE DRIVE 

   This uses flash memory to store data instead of using platter and spinning.

   - There is low tendency of it getting damage like the HDD 
   - It's faster and durable commonly use in phones.
   - SSDs have much faster access than HDDs.
   - It's quiet to use  and more resistant to physical shock
   - Can cost more per GB
   - This can be particularly useful in laptops, though actual power consumption depends on the specific drive and workload. 

   Under normal use, a good SSDs can last for years. Not every SSD is the same; SATA SSD uses the SATA Interface and it is commonly use to connect storage devices to a computer. 2.5-inch SATA SSD in a laptop or desktop. 

   NOTE: For performance SSDs is faster than HDDs but HDD are cheaper so because of more space, it's possible to install HDD to SSD to get more storage space.

   ## Removeable Storage

   This refers to any kind of storage device that can be moved from computer to computer without having to open up the case and remove it from the inside e.g, Tape Drives, Floppy Drives, USB Drive, Memory cards..

   Optical Drives: Compact Disc (CD)- Oldest form reader mostly for audio at 65omb-700mb

                   Digital Versatile Disc(DVD) at 4.7 GB OR 8.4GB dual layer video
                   Blu-ray Disc(BD) they come in 3 types; Read only memory, write-once CR, write many or erasable
                   Optical Drives speed are measured as x-rating , CD(1X=150KB/s), DVD(1X=1.385MB/s), Blu-ray(1X- 4.5MB)
                   Uses SATA Connection for installation. 

Operating Systems are build as software and stored on hard drive or solid state drive.

# BIOS/UEFI

BIOS- Basic, Input, Output, System. This is the older version that supports 32-bits processors and motherboard 

FIRMAWRE(Software on a chip)- contains the specialized BIOS program code in flash memory on the motherboard. 

BIOS- The program that a computer's microprocessor uses to start and boot after being turned on. 

- It is the first software to run by a computer whenever it is on.
- BIOS is stored in Read only memory-a type of chip embedded in the motherboard and can be upgraded through flashing. 
- BIOS relied on a text based menu system and a keyboard as its input. 
- Flashing can be use to upgrade BIOS

## What happens when a computer is turned on?

POWER BUTTON THEN FIRMWARE STARS(BIOS or UEFI begins running) THEN HARDWARE IS INITIALIZIED(the firmware identifies and initializes important hardware e.g, CPU, RAM, Storage Devices, Hardware Devices) THEN FIRMWARE LOOKS FOR SOMETHING TO BOOT e.g, SSD TO WINDOWS THEN BOOTLOADER STARTS THEN OPERATING SYSTEM LOADS THEN GET WINDOWS/LINUX LOGIN SCREEN. "POWER TO BIOS/UEFI TO BOOTLOADER TO OPERATING SYSTEM TO OUTPUT

# UNIFIED EXTENSIBLE FIRMWARE INTERFACE(UEFI)

This supports 64 bit processor and provides a graphical user interface.

- Supports larger hard disk drives and solid state drives
- This faster than BIOS
- An updated version of BIOS that allows keyboard and mouse as input and provides a Graphics User Interface(GUI)
- It support security feature such as; Secure Boot whivh helps ensure that only trusted properly signed boot software is allowed to start during the boot process. It helps to protect the early boot process.

## BIOS/UEFI SECURITY

- The supervisor/adminstration /set up password are used to protect access to the BIOS or UEFI Configuration program and Prevent unathorized access. 
- The user/system password is used to lock access to the entire computer. 
- The storage hard drive password which locks access to a hard drive connected to the system and requires the end user's password. 

NOTE: BIOS/ UEFI ARE FIRMWARE THAT INITIALIZE HARDWARE AND HELP START THE OPERATING SYSTEM. UEFI IS THE MODERN SUCCESSOR TO TRADITIONAL BIOS AND PROVIDES ADDITIONAL CAPABILITIES SUCH AS GPT SUPPORT AND SECURE BOOT. 

# MOTHERBOARD

- IT'S a printed circuit board that contains the particular components of a computer. 
- IT'S use by the other component of the computer to use external storage and internal data transfer back & forth between the system. 
- It allows different computer component to communicate and work together
- A lot of things connect to the motherboard e.g, CPU, RAM, Storage, GPU, Expansion cards, USB Devices, BIOS/UEFI, SATA CONNECTORS, Case Fanpower and many more.
- IT provides the appropriate sockets, slots, connectors and circuitry for these components. e.g a motherboard must use the appropriate CPU socket and platform not any CPU can go into the motherboard. To know the type of motherboard to use, first know the model and generation of the CPU you can use. The CPU Socket found in motherboard(Intel & AMD)
- EXPANSION CARDS: Spaces are created on the motherboard for this. An expansion card add additional hardware to the computer e.g, Graphics cards, Sound cards...
They are 5 different types but 2 are commonly use; PCIe(Peripheral Interconnect Express)which is a high speed connection speed for expansion devices and comes in different sixes but PCIe x1 and x16 are commonly use. Mini PCIe commonly use laptops and mobile devices. 
- PCIe x1 is slower than PCIe x16 and the higher the number the faster the speed. 
- The main thing is to recognize the different PCIe sizes and their uses.
- FORM FACTORS: A motherboard form factor describes its physical dimensions, layout and compatibility(type,size&speed) and they are three common FF; Advanced Technology Extended ATX(full sized/common desktop motherboard) then Micro-ATX(Smaller) then Mini-Information Technology EXtended ITX(Very small) The motherboard form factor as to be compatible with the computer case. It can describe the number of expansion card that can be installed in a motherboard. 
- POWER CONNECTIONS: Two important ones to know: 24-pin motherboard and CPU power connector(depending on the sytem, it may be a 4-pin, 8-pin or combination configuration)

POWER TO MOTHERBOARD THEN COMPONENTS

- CMOMPLEMENTARY METAL-OXIDE SEMICONDUCTOR(CMOS battery): It is a battery powered memory chip. Many motherboard as a small battery that helps to maintain certain settings and the system real tim clock when the computer is turned off so when the time is incorrect and firmware setting being reset or lost then the battery is getting bad. 

NOTE: They are many component connected to a motherboard with their functions.

# OPERATING SYSTEM

They are three functions of a computer which are:

- Input, Processing, Storage and Output and then, 

 They are three main component of computer which are:
 - Hardware(physical part of a computer), Software(programs and operating systems that instructs hardware what to do) and Firmware(software embedded in hardware components)
 OPERATING SYSTEM: This is the main sofware that manages the computer's software and hardware. e.g, Windows. Linux, MacOS. 
 - An OS manages CPU(it decides which processes get cpu time), RAM(it manages memory used by applications processes), STORAGE(it manages files and acess to storage), FILES(it provides ways to create, open, modify and delete files), DEVICES(it communicate with hardware e.g, mouse, keyboard..), USERS(it manages user account and permissions) AND SECURITY(it provides security tools e.g, permissions, acess contol, security updates...)
 - WINDOWS: Is one of the widely used desktop OS e.g, window 10, window 11 and it provides, desktop, start menu, file explorer...
 - LINUX: Is an OS family built around the linux kernal and it is used in, servers, networking, cybersecurity..
 - macOS: Is Apple's OS used on a computer and it manages, hardware, applications, files, memory, processor, user....
 - GRAPHICS USER INTERFACE(GUI): The visual interface e.g, windows, icons, keyboard, meus, mouse pointer..
 - COMMAND LINE INTERFACE(CLI): instead of clicking buttos, commands are type in e.g, windows has command prompt while linux has terminal
 - THE KERNEL: It helps to manage those component e.g, CPU, RAM, PROCESSES, HARDWARE INTERACTION..IT LIKE AN ENGINE IN TNSIDE THE OS
 - DRIVERS: It is a sofware that helps the operating system communicate with a particular hardware device. e.g, printer, graphics cards..
 - OS UPDATES: Operating system receive updates which can be e.g, fix bugs, improve functonality, improve compatibility, fix security vulnerbilities. If a computer remains unpatached then it may remain vulnerable to attacks that exploit the known weakness.
 - BOOT PROCESS: POWER THEN FIRMWARE THEN BOOTLOADER THEN KERNAL THEN OPERATING SYSTEM THEN LOGIN/DESKTOP.
 
 # APPLICATION 

 Application are software designed to perform a specific task. Different applications for different purpose e.g Chrome is to browse, Spotify is to music, VS Code is to write/edit code. 

 ## How Does an Application work?

 Step 1: Open Google Chrome then click Chrome(The OS recieves the request)
 Step 2: The OS finds Chrome(chrome is stored on computer storage)
 Step 3: Chrome is loaded into RAM(OS load the neccessary part of chrome into RAM)
 Step 4: CPU processes the instructions ( The cpu execute the instructions needed by chrome)
 Step 5: Chrome appears on the screen(it can now be use)

 STORAGE TO RAM TO CPU TO APPLICATION RUN

 Applcation does not work on it own, it use computer component like, CPU,RAM,STORAGE,GUI,NETWORK..

 Types of Application: Microsoft word, Excel, Powerpoint, Chrome, Firefox, Safari, Spotify, Antivirus software, firewall software e.t.c
 When an application is installed, the computer places the neccessary program files and suporting information onto storage.

 Keeping Application updated in neccessary in security practice. e.g, bug fixes, new features, security fixes...

 " A browser has a security vulnerability. The developer releases an update that fixes it. 

 " Some Application ask for permission to access things e.g, camera, location, contacts..and it is neccessary to pay attention to for security/ privacy consideration. 

 ## Application Crashes

 Some applicaion might stop responding and possible cause include:
 - Software bugs
 - Corrupted files
 - Driver problem
 - Insufficient resources

 Basic troubleshooting can include;

 - Close and reopen the application
 - Restart the computer
 - Check for update
 - Reinstall the application if neccessary
 - Check available reasources

 # PROCESSES

 A process is a program that is currently running

 STORAGE TO RAM TO CPU TO PROCESSES TO APPLICATION..

 NOTE: Not everything running on a computer has a visible window. Some processes run in the background. e.g, Window services, Antivirus software, update services and network services. They might not be seen on the desktop but they are still doing work. 
 A Process can start another process e.g, A legitimate applicaition starts another helper process but if a microsoft word process to suspious command shell to unknown program, that might deserve an investigation. 

 ## Process Location:

  A security analyst may want to know; where is the process running from? e.g, A legitimate windows program might normally be located in a known system directory but if a suspious process is seen pretending to be a windows component but running from an unusual location, that is something worth investigating. 

  ## Process and Cybersecurity

  imagine a level 1 SOC Analyst monitor the Security platform generates an alert: "Suspicious process detected"

  - Investigate first
  - a. What process is it? e.g something.exe
  - Who started it? (user account)
  - Where is it located? (what is the file path)
  - What started it? (What is the parent process(process to process))
  - What is it doing? (is it accessinf file, using the network, creating other processes,..)
  - Is it legitimate? (could it belong to windows, an installed application, security software..)

  ## Process/Application/File

  For Example;

  - notepad.exe, this is a FILE stored on your computer
  - NOTEPAD is the APPLICATION 
  - when NOTEPAD is opened, Window runs it as a PROCESS

  # FILES AND DIRECTORIES

  This import because everything to do on a computer invovle files in some way. A file is a collection of data stored on a computer. When something is created and saved that is usually creating or modifying. For example, my week 2 cybersecurity note in this VS Code and save as, WEEK 2.md..that's a file. 

  ## What is a Directory? 

  A directory is a location used to organize files and other directories known as Folder. A folder is use to organise files and dirctories.

  - A directory can contain files and other directories
  - A directory inside another directory is called subdirectory
  - A file usually as a name e.g, CybersecurityNotes
  - There is also what is called "Extention" e.g, .docx. THis often indicate the type of file it is. 

NOTES: Dont't assume the extension proves what the file really is, e.g, photos.jpg doesn't automatically mean it's harmless image. Security tools can inspect the actual file type , contents, metadata and behaviour. 

  - A file path tells where a file is located. like an address, where it is from..
  - There is also Window Path e.g, C:\, This usually represents the primary Windows drive..e.g, On the C drive to User to Student to Downloads to File.pdf. 
  - Linux use a different path structure. e.g, /home/student/Documents...Linux make use of / and not C\ like windows
  - Absolute Path: It gives complete location from the root/drive e.g, /home/student/Documents 
  - Relative Path: Describes a location relative to where you currently are. 
  - Root directory is the hihest level of a file system. e.g, L=/=W=C:\
  - File Operation: Create, Open, Read, Write, Copy, Move, Rename, Delete, Restore..copy doesnt make the file delete and move only move the location of the file to another place also delete does not make it delete parmanently. 
  - There are Hidden Files because somes files may not be use regularly. An attacker or malware may attempts to hide files, so security analyst need to understand that. "Not everything on a system is necessarily visible in the normal file browser. 
  - File Permission : This is important so that someone else won't have acccess to your file or modify it though another user maybe able to read it but can't change it. 
  - A file system provides the rules and structures needed to organize and manage files, e.g, windows. linux...

  # PARTITION

  A partition is a logical section of a storage drive. in a storage drive, you can divide one physical drive into multiple partitions.E.g, 1TB Storage device can be divided into 500GB which makes it Partition 1 and another 500 GB which makes it 500GB. The phsyical drive(actual hardware) is it 1TB but the OS sees separate logical storage areas. 

  They are two types of partition tables:

  - Master Boot Record(MBR)- The older pertition and has limitation compared with GPT 
  - GUID Partion Table(GPT)- The modern  one. it provide supports for very large drives, more partitions than MBBR, better data structure redundancy, use with UEFI System.

  NOTE: When investigating a computer, you need to understand where data lives.  That is also partition then it needs backup..

# NFTS

New Technology File System

IT's a file system developed by microsoft and commonly used by Windows systems. It is neccessery to have what you can use to organize so you can find them quickly and control who can access them. 

- NTFS provides the rules and structure Windows uses to organize and manage files and directories on storage. 

NFTS supports permissions. That means you caan conttol who is allowed to have access to a file or folder and what they can do with it. IT include; Allow someone to read, Write, Modify, Full Control. Permission control access to files and folder.

- NFTS uses journaling to maintain file system consistency. It can help to protect the file system structure from certain problems such as unexpected shutdown. 

- Window commonly use NFTS because it support very large files and storagr volume.

- Metadata: This stores informtion beyond just their contents. More Information like; File name, Sile Size(2mb), Timestamps(It was modified at this time), ...

- Master file table: It contains records describing files and directories on the NFTS volume

- As much as NFTS is good, it is excellent for Windows but some devices and operating systems may have limited or read only support for it. 

# FAT32

 File Allocation Table 32

 A FAT32 also organize data on storage device. it's a older version of NFTS but it has limitaion. It is very simple and widely compatible. It is mostly use in; USB drives, Memory Cards, Tv/Camera.. It is useful when you need a storage device to work with many different operating systems and devices.

 FAT32 has an individual full size limit e.g, if a file size is 6GB, it won't fit as a single file on FAT32 because it doesn't have more than 4GB even though the total space on a USB is larger than 6GB, it still won't go.  FAT32 drive itself is larger than 4GB but individual size file is 4GB.

 FAT32 is use because it support a very wide range of devices e.g, A USB drive can be use with; Windows in pc, camera, tv, game console e.t.c

 Compared to NFTS, FAT32 doesnt provide the same built in security such as, file permissions, journaling and that is one reason it is not normally the preferred one to use. 

 # EXT4

 Fourth Extended File System

 It is a file sytem commonly use by Linux. It is also use to organise data stored on a storage device. ext4 helps the operating system:

 - Organize files
 - Organize directories
 - Store file information
 - Track where  data is located
 - Manage available storage space
 - Manage file permissions
 - Recover From certain interruptions

 ext does the same like other file system, it is just use in linux computer..

 JOUNALING(it keep record of certain changes/operations so it can help maintain consistency after things like an unexpected shutdown). FILE PERMISSIONS(e.g, Owner, Group, Others...) AND OTHE SECURITY FEATURES ARE SUPPORTED IN ext4 also.It works with linux permissions and ownership system. 

 rwx in linux means, Read, Write and X means Execute


# FILE PERMISSION

File permission are rules that determine what user or programs are allowed to do a file or directory. This is imoportant because if it is not use the:

- Anyone can read private files
- Change important files
- Delete data
- Run Programs
- Access other users' information

So it help to enforce who can access something and what they can do with it. RWE are commonly use. 

LINUX PERMISSION: RWX, RWXR-XR-- (RWX means the owner) the (R-X means Group. a file can be associated wih a group, members of a "finanace group can have permission to access ceratin file and it is just read and execute cannot write) then (R---( the dash means permission is not granted to write and execute) means Others, they can only be given access to read) 

- LINUX also allows permission to be in numbers e.g, 755, rwx add them together(Owner as 4+2+1=7 then on terminal it is 7=rwx, Group as 4+1=5 so 5=r-x, Other can only read 4 so 4=r--) to decode 755, 7 is for owner, 5 for group then 5 is for other, 755=rwxr-xr-x

WINDOWS PERMISSION: Windows use Access Control List (ACL) which contain which user/group can access a resources and what actions can be allowed to be performed. e.g, Read, Write, Modify, Full Control.. Windows are more complex than linux.

NOTE: A user or program should have only the permissions necessary to perfrom its job. 

# BACKUPS

A backup is a copy of important data kept separately so you can recover it if the original is lost, damaged, deleted, or attack. Lots Of things can cause data loss e.g, Computer failure, Hard drive / SSD failure, Accidential deletion, Malware, Ransomware, Fire or physical damage, Water damage, Sofware problems, Someone intentionally deleting files so A backup gives you a way to recover those data loss. 

COPY IS DIFFERENT FROM BACKUP. A useful backup should ideally be stored somewhere that is not affected by the same failure.

SO a safer space to store your backup files can be in EXTERNAL drive e.g, external HDD/SSD, Cloud storage, Another Computer/server, Off-site location. The important thing is to not put all important copies in the smae place.

- Backup is stored on physical storage you can access directly. 
- A full backup copies all the selected data and staightforward to retore but takes more space, time and data transfer. 
- Incemental backup backs up data that has changed since the previous backup. e.g, if a back up is changed on tuesday after the full backup on monday, incremental save the changes
- Differential backup backs up data that has changed since the last full backup e.g, it can contain all the changes since monday...
- The 3-2-1 backrule is very useful e.g, keep 3 copies, use 2 diiferent types of storage/media then 1 copy off-site that means Original on Pc then Backup on external drive then Backup in cloud/off-site storage
- Always make sure a backup can be restored. It can always be test to know.
- When something goes wrong, backup can be use to restore it. 

# ENCRYPTION BASICS

Encryption is the process of transforming readable data into an unreadable form so that unathorized people cannot understand it. 
- Plaintext: It is the original, readable information e.g, my password is ABC123
- Ciphertext: The encrypted, unreadable looking version e.g, X7@kp9..

So Plaintext to Encryption to Ciphertext and when properly decrypted Ciphertext to Decryption to Plaintext

An Encryption key is information used by the encryption algorithm to encrypt and or decrypt data. 

- The encrpytion is like the lock mechanisim.

ENCRYPTION main goal is CONFIDENTIALITY.

- This is connected to the CIA Triad. Know that ENCRYPTION AND ENCODING are not the same thing. 
- ENCRYPTION is designed to protect information using a key while ENCODING changes data into another format so it can be represented or transmitted conveniently. 
- ENCRYPTION can generally be decrypted with the appropriate key used when data need to be recovered while HASHING produces a fixed size hash value from data, it is to be a one way operation in normal use. It is use for things such as:
- Password verification
- File inergrity checking
- Digital forensics
- Identifying known files. 

## SYMMETRIC AND ASYMMETRIC ENCRYPTION

SYMMETRIC ENCRYPTION: Uses the same(single) secret key encryption and decryption. It is fast and efficient for large amounts of data.

ASYMMETRIC ENCRYPTION: Uses a key pair. a public(can generally be shared) and private keys(must be kept a secret) It can be generally slower.
Modern secure communication systems often use both, rather than choosing only one. 

## HTTPS

It is seen while visiting many websites. HTTPS uses CRYPTOGRAPHIC protocols to help protect communication between your browser and the website. .  For example, when you log into a website and encryption helps protect the information traveling between your device and the server from being easily read by someone who intercepts the traffic. 

ENCRYPTION AT REST

It means data is encrypted while stored, e.g, Laptop storage, SSD, database, USB drive, Backup so if someone steals the phsysical laptop, encryption can help prevent them from simply removing the drive and reading stored data. 

ECRYPTION IN TRANSIT

It means data is protected while moving betwen systems. e.g, Phone to Internet to Website. encryption helps protect the communication while it is traveling. 

BitLocker

It is a Microsoft drive encryption technology for supported Windows editions/devices. It can encrypt an entire volume/drive to help protect stored data. e.g, if a laptop is stolen the encryption makes it harder for someone to access the stored data without the necessary authentication/recovery information. 

ENCRYPTING FILE SYSTEM (EFS)

It can encrypt individual files and folder on NFTS volunes.

ENCRYPTION AND DECRYPTION-FROM PLAINTEXT TO CIPHERTEXT THEN DECRPYPTION REVERSE IT FROM CIPHERTEXT TO PLAINTEXT USING THE DECRYPTION KEY

ENCRYPTION AND PASSWORD

They are not the same. A password can be used as part of an authentication or key protection system but simply putting a password on a document doesn't necessarily mean the underlying data is srongly encrypted and never assume a passwoord is secure just because it exits. Security depend on how the system stores and protect the password and encryption keys and if the key is lost all the necessary encrypt data or recovery mechanism are lost know that data may not be able to decrypt. As much as Encryption protect data, the keys must be protected also. 

 BITLOCKER IS A BUILT IN ENCRYPTION FEATURE IN THE WINDOW OS THAT WILL ENCRYPT ALL THE DATA STORED ON A HARD DRIVE USING AES ALGORITHMN ENCRYPTION. 

STORAGE>HOLDS DATA> PARTITION> DIVIDES STORAGE LOGICALLY> FILE SYSTEM>ORGANIZE DATA(NFTS-WINDOWS, FAT32-BROAD COMPABILITY, EXT4-LINUX)>DIRECTORY>ORGANIZE FILES> FILES>CONTAINS DATA> PERMISSIONS>CONTOL WHO CAN ACCESS> BACKUP>PROVIDES A RECOVERY COPY> ENCRYPTION>PROTECT DATA FROM UNATHORIZED READING 

# COMPTIA A+ CORE 1
- COMPUTER BASICS(MEANING OF COMPUTER, TYPES OF DEVICES,THEIR FUNCTIONS..)
- COMPUTER COMPONENTS(HARDWARE,SOFTWARE & FIRMWARE AND THEIR FUNCTIONS..)
- A BRIEF EXPLAINATION OF 6 TROUBLESHOOTING METHODOLOGY(IETEVD)
- COMPUTER SPEED(BITS & BYTES)
- DOMAIN 3(HARDWARE)
- USB CONNECTOR TYPES
- USB CABLES
- VIDEO CABLES(HDMI,DISPLAYPORT,DVI,VGATHUNDERBOLT,USB)
- STORAGE CABLES(SATA, THUNDERBOLT, LIGHTING...)
- MOTHERBOARD(MEANING, SPEED, FORMFACTORS, CPU SOCKET, CONNECTIONS, INSTALLATION)
- COOLING FAN
- POWER SUPPLY UNIT(DIRECT CURRENT AND ALTERNATING CURRENT, FUNCTION, INPUT&OUTPUT VOLTAGE..)
- RAM(MEANING, SPEED,...)
- BIOS/UEFI
- STORAGE DEVICES(HDD&SSD, REMOVEABLE STORAGE...)
- VIRTUALIZATION






