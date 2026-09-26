# Week 4: Learning Objectives (24th August-30th)

# Virtualization

* Virtual machines
* Hypervisors
* Snapshots
* Virtual networking
* Host-only, NAT and bridged Task: Create Ubuntu and Windows virtual machines and take snapshots.

# 1. Virtualization
This is something i am familiar with because i learnt it on COMPTIA A+ course. 

Virtualization is the technology that allows one physical computer to create and run other computers inside it using software.

For example, my physical Windows computer can run Ubuntu inside VirtualBox without replacing Windows.

Physical computer → VirtualBox → Ubuntu VM

My physical computer is called the host while Ubuntu running inside VirtualBox is called the guest.


# 2. Virtual Machines (VMs)

A Virtual Machine (VM) is a computer created using software or Hpervisor.

A VM behaves like a real computer. It can have its own:

* Operating system
* RAM
* CPU
* Storage
* Network connection
* Applications
* File

The VMs share the physical computer’s hardware resources. When i installed my two virtual machines, i shared some of what is listed above to my Vm. For example, i assigned 1.5GB of RAM to my ubuntu and Windows each. I gave each 1.5GB because my host RAM is just 4GB so i must be careful to keep my host computer to run smoothly also. 

Why use VMs?

* To test another operating system
* To learn cybersecurity safely
* To test software
* To experiment without affecting the main OS
* To run different operating systems on one computer


# 3. Hypervisors

A hypervisor is software that creates and manages virtual machines.

It allows your physical computer’s hardware resources to be shared with the VMs.

Examples include:

* VirtualBox(This is what i am using which allows me to using multiple operating systems on it)
* VMware
* Hyper-V

There are two main types:

Type 1 — Bare-metal hypervisor

Runs directly on the physical hardware.

Hardware → Hypervisor → VMs

Commonly used in servers and data centres.

Type 2 — Hosted hypervisor

Runs as an application inside an existing operating system.

Hardware → Windows → VirtualBox → Ubuntu VM

* I am using a Type II Hypervisor which is my VM.

# 4. Snapshots

A snapshot saves the state of a virtual machine at a particular point in time.

For example:

1. I installed ubuntu.
2. Ubuntu is working correctly.
3. Then i took a snapshot and name it “Fresh Ubuntu Installation.”
4. My experiment with Ubuntu later.
5. Something goes wrong.
6. I can restore the snapshot and return to the earlier state.

A snapshot is not exactly the same as a normal backup. It is mainly useful for quickly returning a VM to an earlier state.

# 5. Virtual Networking

Virtual networking allows the virtual machines to communicate with:

* The host computer
* Other virtual machines
* The internet
* Other devices on the network

VirtualBox provides different networking modes.

The three to understand  NAT, Host-only, and Bridged.

# 6. NAT

NAT = Network Address Translation

With NAT, VM can normally access the internet through the host computer’s network connection.

So if Ubuntu is connected using NAT, Ubuntu can normally browse the internet.

- Windows gets internet from Wi-Fi.
- VirtualBox shares that connection with Ubuntu.
- Ubuntu can access the internet.

NAT is usually the easiest option when I simply want my VM to have internet access. I use NAT for practice for now.

# 7. Host-only Networking

Host-only networking creates a private network between the host computer and the virtual machine.

VM can communicate with the host but it normally does not have internet access through that network.

It more like a private road between computer and Vitual machine.

Windows host ↔️ Ubuntu VM

But:

Ubuntu VM ✕ Internet

This can be useful to create an isolated environment for testing.


# 8. Bridged Networking

With Bridged networking, the VM connects to the same physical network as the host computer.

It is like giving the VM its own presence on my local network.

The Difference from NAT

With NAT:

Host → shares its connection → VM

With Bridged:

Host and VM → connect to the same physical network.

# COMPTIA A+ CORE 1
This week on COMPTIA A+ I learnt TROUBLESHOOTING.

## TROUBLESHOOTING METHODOLOGY(THE 6 TM)
Here again on the six methods of Troubleshoting and what they do

* Identify the problem

First thing to do as a technician using this method is to gather information from the user. Question like what exactly is wrong would come up, what are the symptoms?what is happening? what may have caused this thing to begin with? Even a technician has to be curious.

- Establish a theory of probable cause

Here we can try to figure out a theory for the problem identified like, probable cause? different possible causes may have happened. Research should be conducted, internal & external research. The main goal is establish a theory of probable cause. 

- Test the theory to determine cause

It is essential to test the theory and see if it is right. Though there can be several theories if one doesn't seem to be the problem. If it goes beyond what one can solve, it can be escalated to people in higher position who can handle it.

- Establish a plan of action and implement a solution

Here is to resolve the problem and find a solution to it.

- Verify system functionality and if applicable implement preventives

Here is to make sure the 'action' taken really worked and everything is working well and no damage caused. If need be, implement preventives so it wont happen again.

- Doocumenting findings, actions and outcome.

Documentation is always important. It start immediately with identifying the problem.

## TROUBLESHOOTING HARDWARE ISSSUES
Hardware issues can be troubleshoot using the six troubleshooting methods. Issues like, Power issues, Post On Self Test issues, Crash Screen issues, Cooling Isuess, Physical Isuess, Performance Isuess. All these develop isuess as some point and it is important to solve these issues. Understanding Troubleshooting methods helps to know the right way to solve these isuues. For example, to know if a system is  overheating, to determine if it is the Thermal paste, first thing to check is the thermal load and heat dissipation. Touch the sides of the computer to check if it is really hot then turn off the computer and reboot it and check if fan is working on highspeed. When it comes to cooling, it is important to mak sure all cooling component are working properly. Overheating Solution is to shut down system and turn back on after a while then boot into bios/uefi.

##  TROUBLESHOOTING STORAGE DEVICES ISSUES 
Storage issues like, Boot Issues,The HDD & SSD Isuess, Drive Perfromance Isuess, Isuess with Raid. For example, If the sound coming from the HDD changes from normal then there is a problem so the first thing to do is get a good backup before all data get lost.In SSD, it Blocks and it identify bad blocks and Good data back up is essential so data won't be lost.

## TROUBLESHOOTING VIDEOS ISSUES
Videos isuess like, Physical Cabling and Source Selection,Projector issues, Video Quality Isuess. In these isuess, diferrent problem can come up. For example, Projector Isuess, Dim images can occur and it is usually due to the bulb reaching the end of life so it is better to change it. There is also shut down problem or restart which is similar to a computer shutting down from overheating and causes a projevtor to shut down intermittently.

## TROUBLESHOOTING NETWORKS
Network Issues are in several way as it is broad itself, e.g, Wired Connectivity issues, Network Performance issues, Wireless Connectivity issues, VOIP Issues, Limited Connectivity Issues. E.G, VOICE OVER INTERNET(VOIP)It issues occurs when there is latency or jitter in transmission and the best way to solve it is to Implement Quality Of Service.

## TROUBLESHOOTING MOBILE DEVICES
Mobile Issues like, Mobile power issues, Mobile hardware issues, Mobile performance issues, Mobile display isuess, Mobile Connectivity Issues, Mobile Malware infections issues. e.g, mobile connectivity issues, while configuring these issues, it is important to first consider physical issues, software configuration issues too. For example, blutooth, make sure it is enabled, properly paired, adequate battery and right range.

## TROUBLESHOOTING PRINT DEVICES
 Issues include, Printer connectivity issues, Print feed issues, Print Quality issues, Print Finishing issues, Print jobs issues. They are three things to troubleshoot when dealingb with printeer connectivity issues involves;
 -  Local connections such as those using USB. Network connections including ethernet and wi-fi
 -  Issues related to a frozen print queue. 

