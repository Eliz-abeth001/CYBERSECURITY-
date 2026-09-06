# Week 4: Learning Objectives 

# Virtualization

* Virtual machines
* Hypervisors
* Snapshots
* Virtual networking
* Host-only, NAT and bridged Task: Create Ubuntu and Windows virtual machines and take snapshots.

# 1. Virtualization

Virtualization is the technology that allows one physical computer to create and run other computers inside it using software.

For example, your physical Windows computer can run Ubuntu inside VirtualBox without replacing Windows.

Think of it like this:

Physical computer → VirtualBox → Ubuntu VM

The physical computer is called the host, while Ubuntu running inside VirtualBox is called the guest.


# 2. Virtual Machines (VMs)

A Virtual Machine (VM) is a computer created using software.

A VM behaves like a real computer. It can have its own:

* Operating system
* RAM
* CPU
* Storage
* Network connection
* Applications
* File

The VMs share the physical computer’s hardware resources.

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

* VirtualBox
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


# 4. Snapshots

A snapshot saves the state of a virtual machine at a particular point in time.

For example:

1. You install Ubuntu.
2. Ubuntu is working correctly.
3. You take a snapshot called “Fresh Ubuntu Installation.”
4. You experiment with Ubuntu later.
5. Something goes wrong.
6. You can restore the snapshot and return to the earlier state.

A snapshot is not exactly the same as a normal backup. It is mainly useful for quickly returning a VM to an earlier state.

# 5. Virtual Networking

Virtual networking allows your virtual machines to communicate with:

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

NAT is usually the easiest option when you simply want your VM to have internet access.

# 7. Host-only Networking

Host-only networking creates a private network between the host computer and the virtual machine.

The VM can communicate with the host, but it normally does not have internet access through that network.

Think of it as a private road between your computer and your VM.

Windows host ↔️ Ubuntu VM

But:

Ubuntu VM ✕ Internet

This can be useful to create an isolated environment for testing.


# 8. Bridged Networking

With Bridged networking, the VM connects to the same physical network as the host computer.

It is like giving the VM its own presence on your local network.

Difference from NAT

With NAT:

Host → shares its connection → VM

With Bridged:

Host and VM → connect to the same physical network.

# COMPTIA A+ CORE 1
- TROUBLESHOOTING METHODOLOGY(THE 6 TM)
- TROUBLESHOOTING HARDWARE ISSSUES
- TROUBLESHOOTING STORAGE DEVICES ISSUES 
- TROUBLESHOOTING VIDEOS ISSUES
- TROUBLESHOOTING NETWORKS
- TROUBLESHOOTING MOBILE DEVICES
- TROUBLESHOOTING PRINT DEVICES
