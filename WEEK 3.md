# Week 3 Learning Objectives 

Windows fundamentals

* Windows settings
* Control Panel
* Task Manager
* Services
* Event Viewer
* Users and groups
* Updates
* Windows Defender
* Command Prompt
* PowerShell basics

Linux introduction

* Linux distributions
* Terminal navigation
* Files and directories
* Users
* Groups
* Permissions
* Processes

# 1. Windows Settings

Windows Settings is the main place where you control and customize your Windows computer.

What can you do in Windows Settings?

* System (Display, sound, notifications, power, storage, etc.)
* Bluetooth & devices (keyboard, printers, and other devices)
* Network & Internet  Personalization(wallpaper, colors, themes, lock screen, etc.)
* Apps
* Accounts(passwords, sign in options..)
* Time & language
* Privacy & security 
* Windows Update  


# 2. Control Panel

Control Panel is a traditional Windows tool used to view and change system settings. It can be seen as the older version of Windows Settings.

 It is still useful because many administrative options are found there.

What can you do in Control Panel?

* Programs and Features
* User Accounts
* System 
* Devices and Printers  
* Network and Sharing Center.
* Power Options
* File Explorer Options
* Windows Defender Firewall 
    
NOTE: Window Settings is the modern control center while Control Panel is the older control center that still provides some options and administrative tools not presented in the same way in Settings.

# 3.  Task Manager

Task Manager is a Windows tool that lets you see what your computer is doing and manage running programs and processes.

Task Manager helps to:

* See running programs/processes
* Monitor system resource usage
* Manage startup applications
* End unresponsive applications
* Important things you can see

These are how it run; 
*  Processes: Shows programs and background processes currently running e.g,Chrome, File Explorer, Windows processes, Background applications, they can see how much CPU, memory (RAM), disk, and network each process is using.
* Performance: Shows how your hardware is being used by monitoring the, CPU usage, Memory (RAM) usage, Disk usage, Wi-Fi/Ethernet activity, GPU usage.
* App history: Shows resource usage by certain applications over time.
*  Startup apps: Shows programs that automatically start when Windows starts. It can be enable or disable startup applications.
* Users: Shows users currently signed into the computer and the resources they are using.
*   Services: Shows Windows and application services running on the computer.

# 4.  Windows Services

A Windows service is a program that runs in the background to perform a specific job for Windows or another application. They are usually not seen but they help computer function properly.

Each service can have a status such as:

* Running → currently operating
* Stopped → not currently running

Startup types

A service can also have different startup configurations:

* Automatic → Starts automatically when Windows starts.
* Manual → Doesn't automatically start at startup but can be started when needed.
* Disabled → Windows won't start it unless you change the setting.

   Services are important for troubleshooting. For example, if a Windows feature isn't working, an IT technician might check whether the service responsible for that feature is running
NOTE: Don't randomly stop or disable Windows services. Some services are important to Windows, and disabling the wrong one can cause problems.

# 5.  Event Viewer

Event Viewer is a Windows tool that records and displays events that happen on your computer. When something happens such as an application crashing, a service starting, or a security event occurring windows can record information about it in Event Viewer.


It's mainly used for troubleshooting.
For example, imagine:
Your computer suddenly shuts down.
An IT technician can check Event Viewer to look for records around the time the shutdown happened. The logs may provide clues about what caused the problem. commonly see: Error, Warning, Information, Critical.

Event Viewer contains different logs; Application, System, Security. Example;Suppose an application keeps crashing. Event Viewer → Windows Logs → Application, Then look around the time the application crashed for an Error event. The information might help identify the problem.

# 6. Users and Groups

In Windows, users and groups are used to control who can access a computer and what they are allowed to do.

Users

A user account represents one person or identity using the computer.

Types of Windows accounts
Standard User
A standard user can perform normal activities but has limited administrative privileges.
For example, they can use applications and create files, but some system-level changes require administrator permission.

Administrator

An administrator has greater control over the computer.

They can perform tasks such as:

* Installing software
* Changing important system settings
* Managing user accounts
* Changing certain security settings

Administrator access should be used carefully because it gives greater control over the system.

Groups

A group is a collection of user accounts. Instead of giving permissions to users one by one, an administrator can put users into a group and assign permissions to the group.

Why are users and groups important?

They are important for security and access control.

They help answer:

Who are you, and what are you allowed to access? This connects directly to cybersecurity. For example: User → belongs to group → group has permissions → user receives those permissions.

Authentication vs Authorization

Authentication = proving who you are. Example: entering your username and password.

Authorization = determining what you're allowed to do. Example: you are allowed to view a folder but not delete files from it.

# 7.  Windows Updates

Windows Update is a Windows feature that helps keep your computer up to date, secure, and working properly. Windows regularly receives updates from Microsoft. Updates can include; Security updates, Bug fixes, Feature updates, It add or improve features, Performance improvements, Driver updates.

If Windows is updated, computer is generally better protected against known security problems. Imagine researchers discover a weakness in Windows that attackers could exploit. Microsoft can release a security update that fixes the vulnerability.

Automatic updates: Windows can automatically download and install many updates. However, some updates may require you to restart the computer to finish installing.

# 8.  Windows Defender / Windows Security

Windows Defender is Microsoft's built-in security protection for Windows. In modern Windows versions, much of this protection is presented through the Windows Security app. It is like a security guard for computer. Its job is to help protect PC from threats such as malware and unauthorized activity. It protect against; Viruses and malware, Real-time protection, Firewall, Account protection, Device security

  Windows Defender vs Windows Security


Microsoft Defender = Microsoft's security technologies, including Defender Antivirus.

Windows Security = the Windows app/interface where you can view and manage many of these security protections.

# 9.  Command Prompt (CMD)

Command Prompt, often called CMD, is a Windows program that lets you interact with your computer by typing commands instead of clicking through menus. Think of it as talking directly to Windows using text commands

## Why is Command Prompt useful?

It is useful for; Troubleshooting, Managing files and folders, Checking network information, Testing network connections, Running system commands, Automating certain tasks. Administrator Command Prompt Sometimes are; Run as administrator. This gives CMD elevated privileges, allowing commands that require administrator permissions. Don't run commands as administrator unless you understand what they do.

# 10. PowerShell Basics

PowerShell is a Windows command-line shell and scripting tool used to manage and automate computers. Like Command Prompt, you type commands instead of clicking buttons. But PowerShell is more powerful and designed for more advanced system administration and automation. PowerShell can help to; Manage files and folders, Manage users, Manage services, Check computer information, Troubleshoot systems, Manage networks, Automate repetitive tasks, Run scripts.

  This makes PowerShell particularly useful for IT administrators and cybersecurity professionals PowerShell commands often have a special structure called Verb-Noun. For example; Get-Process, Get = what you want to do, Process = what you want to work with


# 11. Linux Distributions

Linux is an open-source operating system kernel. The kernel is the core part of an operating system. It manages things like: CPU,Memory,Hardware,Processes.Files,Devices.....But when people say "Linux", they often mean a complete operating system built around the Linux kernel.

## What is a Linux distribution?

A Linux distribution, or distro, is a complete operating system built using the Linux kernel plus other software. Linux kernel + other software = Linux distribution

 ### Popular Linux distribution

  Ubuntu: Ubuntu is one of the most popular Linux distributions, especially for beginners.It's commonly used for: Learning Linux,Servers,Development,Cloud computing,Cybersecurity

   Debian: Debian is known for being stable and reliable.Ubuntu is actually based on Debian.

   Kali Linux: Kali Linux is specifically designed for cybersecurity and penetration testing. It comes with many security and networking tools.

    Fedora: Fedora is another popular Linux distribution, often used by developers and technical users.
    
     Linux Mint: Linux Mint is designed to be beginner-friendly and has a desktop experience that can feel familiar to Windows users.

There are so many Linux distributions because Linux is open source. Different communities and organizations can build their own distributions with different: Software,Desktop environments,Package managers,Security configurations,Default applications,Target users

Ubuntu is a Linux distribution.
The same applies to Kali, Debian, Fedora, and Mint.

# 12. Linux Terminal Navigation

The Linux terminal is a text-based interface where you type commands to communicate with the operating system. Instead of clicking folders with a mouse, you can navigate and manage files by typing commands.For example, instead of opening File Manager and clicking into Documents, type(Cd(Documents)pwd(print working directory, current working directory),Is(see what is inside))

Linux organizes files differently from Windows. Linux starts from: Plain text / which is called root directory.

You might see paths such as: Plain text /home/student/Documents

- / → the starting point
- home → users' home directories
- student → a particular user's directory
- Documents → their Documents folder

Linux terminal navigation means using commands to move through and inspect the filesystem.

## Command & Meaning
- pwd: Show current location
- ls: List files/directories
- cd: Change directory
- cd ..: Go up one directory
- cd ~: Go to your home directory

# 13. Linux Files and Directories

In Linux, files and directories are used to organize information on the computer. A directory is basically what Windows calls a folder.

* Files: (notes.txt → text file,photo.jpg → image,report.pdf → PDF document,script.sh → shell script)

Linux doesn't rely on file extensions in exactly the same way Windows does, but extensions are still commonly used to help identify files.

*  Directories: A directory is a container that holds files and other directories.(Plain text
/home/student/
├── Documents/
│   ├── notes.txt
│   └── report.pdf
├── Pictures/
│   └── photo.jpg
└── Downloads)


# 14.  Linux Users

Just like Windows, Linux allows multiple users to use the same computer. A Linux user is an account that identifies a person or process and determines what that account can access or do on the system.

## Types of Linux Users

I. Regular User

A regular user is an ordinary account used for everyday activities. Regular users normally have limited privileges so they can't freely change important system files.

II. Root User

Root is the most powerful account in Linux. It can be seen as the system administrator with almost unlimited control and it be run carefully. Root can:

- Install and remove software
- Change system settings
- Create and delete users
- Access protected files
- Start and stop services
- Change permissions

III. sudo

sudo means to ask Linux to run a command with elevated privileges, usually as an administrator.


Regular user → limited privileges, sudo → temporarily elevated privileges, root → full administrative privileges.

## Why are users important in cybersecurity?

User accounts help provide access control. For example: If you have a file containing sensitive information, you don't necessarily want every user on the computer to be able to read or modify it. Linux uses users, groups, and permissions to control this access.

# 15. Linux Groups

A Linux group is a collection of users. Groups make it easier to manage permissions and access for multiple users at once.

## UID and GID

Linux identifies users and groups with numbers. UID = User ID and it is a number assigned to a user account. GID = Group ID is a number assigned to a group.

Linux uses these IDs internally to keep track of users and groups.

# 16. Linux Permissions

Linux permissions control who can access a file or directory and what they can do with it. This is very important in Linux and cybersecurity because you don't want every user to have unlimited access to every file.

## The 3 basic permissions

 - Read — r: Allows the user to view or read the contents.
- Write — w: Allows the user to modify something.
- Execute — x: Allows the file to be executed as a program/script.

## Who do these permissions apply to?
Linux divides users into three categories: Owner — u, Group — g, Others — o

## Why permissions matter

Imagine having a Plain text, I wouldn't want every user on the computer to be able to modify it that is why permissions can restrict access so that only the appropriate owner or group can make changes. It is a major part of Linux security.

# 17.  Linux Processes
A process is a program or task that is currently running on a Linux computer.

For example, when i open a web browser, Linux creates processes that allow the browser to run.

## Why are processes important?

Processes use computer resources such as:CPU,RAM,Storage,Network resources

If too many processes are running, computer may become slower.This is why system administrators monitor processes. Process ID (PID). Every running process gets a unique number. Linux uses these numbers to identify individual processes.

 It is important to be very careful when terminating processes, especially system processes.

## Foreground and background processes

A process can run in the:
- Foreground: The process is actively using terminal, so you're interacting with it.
- Background: The process runs without taking over your terminal.
You may see commands using &, for example:(someprogram &)

The & tells the shell to start the program in the background.

Linux processes vs Windows processes. The concept is basically the same.

# COMPTIA A+ 
- VIRTUALIZATION(VIRTUAL MACHINES, E.G VSCODE..)
- CLOUD COMPUTING
- NETWORKING(MEANING, TYPES, WIRED & WIRELESS, TWISSTED CABLE PAIR, ETHERNET CONNECTION CATEGORY, IP ADDRESS, IPV4 & IPV6  FIBER-OPTIC CABLE, CABLES CONNECTION, CELLULAR, SATELLITE, PORTS PROTOCOLS, SERVERS)
- MOBILE DEVICES(DISPLAY TYPES, ACCESSORIES, COMPONENTS, WIRELESS & WIRED CONNECTIVITY, MDM & MAM, SYNCHRONIZATION, MOBILE APPLICATION, LAPTOP HARDWARE)
- PRINTERS(TYPES, MANAGEMENT....)
- 