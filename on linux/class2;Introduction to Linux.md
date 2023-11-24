# Introduction to Linux

- *Linux* **is an open-source operating system that serves as the foundation for many different computer systems**. It is designed to be highly customizable and flexible, allowing users to modify and adapt it to suit their specific needs. Linux is known for its stability, security, and the wide range of software applications available for it. It is widely used in servers, desktop computers, smartphones, and other devices. Linux provides users with a powerful and free alternative to proprietary operating systems like Windows or macOS, and it has a large and supportive community of users and developers who contribute to its ongoing development and improvement.\

### Linux is a kernel.
---
- **what is a kernel?**
In simple terms, a kernel is the core component of an operating system. It acts as a bridge between the hardware of a computer and the software running on it. The kernel manages various essential tasks, such as memory management, process management, device driver communication, and system resource allocation.
![[Kernel_Layout.svg.png]]![[main-qimg-7c715471f68e052b0c028570f1fbbc52.png]]
#### so what is the history of Linux ?
- In 1969 Thompson and Dennis Ritchie created the first version of unix on s PDP-7 minicomputer but it wasn't cheap and open source.
- Then person called "LINUS TORVALDS" created the Linux kernel and posted it online to make it open source.
###### what is the main differnace between Linux and unix?

Linux and Unix are both operating systems with similarities and differences. Here are some key points to compare and contrast them:

- Origins: Unix was developed in the 1970s at Bell Labs by a group of programmers, while Linux was created by Linus Torvalds in 1991 as a personal project.

- Open Source: Linux is an open-source operating system, meaning its source code is freely available and can be modified, distributed, and contributed to by anyone. Unix, on the other hand, initially had a closed-source model. While there are some open-source versions of Unix available (e.g., FreeBSD, OpenBSD), the majority of Unix implementations have proprietary licenses.

- Kernel: Linux uses its own kernel, called the Linux kernel. Unix typically refers to various operating systems that are based on or derived from the original Unix system, such as Solaris, AIX, HP-UX, and macOS (which is based on the BSD variant of Unix).

- Variants and Distributions: Linux has numerous distributions (distros) available, such as Ubuntu, Fedora, and Debian, each with its own package management system and software repositories. Unix, on the other hand, has different variants or flavors, each provided by different vendors (e.g., IBM, Oracle, Apple), with their own sets of tools and utilities.

- Compatibility: Linux systems are generally more compatible across different hardware platforms due to its open nature and extensive community support. Unix systems, especially proprietary versions, are often tailored to specific hardware architectures and may have limited compatibility.

- Community and Support: Linux has a large and active open-source community, with extensive online resources, forums, and user groups, providing widespread support and development. Unix, while still having a community, often relies more on vendor-specific support and documentation.

- Market Share: Linux has gained significant market share, especially in the server and cloud computing domains, due to its flexibility, stability, and cost-effectiveness. Unix, while still used in certain specialized industries and legacy systems, has seen a decline in market share over the years.
###### what is GNU PROJECT?
The GNU Project is a free software movement initiated by Richard Stallman in 1983. GNU stands for "GNU's Not Unix," and its goal is to develop a complete, Unix-like operating system composed entirely of free software. The project aims to provide users with the freedom to run, modify, distribute, and share software. example: Bash , tar, emacs
- *so GNU+ LINUX will give the GNU/Linux OS.*
![[2868343128_c0fd2ba0af.jpg]]

## what is Shell?
Users communicate with the kernel by **shell**.
- The shell is a command Line interpreter. It translates command entered by the user and converts them in too a language that is understood by the kernel.
### Types of shell
- Based on their features there are money shells
   - SH
   - BASH
   - ZSH
   - FISH
*THEY differ in coloring, piping, command compilation, some kind of feature.
- To identify your shell "echo$SHELL"

## operating system?
---
**OS (operating system)**:- is the main software part of computer that helps to work on.
-*It contains:
    - kernel
    - software
    - Desktop environment
    - File extensions
    - window manager
#### Desktop environment

- **Types of desktop environment on Linux.
1. *Mate*: focuses on simplicity, ease of use, and familiarity, featuring a traditional layout with a taskbar, application menu, and a system tray. It provides a lightweight and responsive environment suitable for older hardware or users who prefer a more traditional desktop experience.
2. *Gnome*: is a desktop environment known for its modern and sleek design. It emphasizes simplicity, productivity, and user experience.
- Have a beautiful animation , while opening ,closing file.
3. *KDE Plasma*: KDE Plasma is a desktop environment that offers a highly customizable and feature-rich experience.
4. *XFCE*: is a lightweight and versatile desktop environment suitable for users seeking a balance between performance and usability, particularly on older or lower-end hardware configurations.

#### why Linux?
---
- Most hacking tools
- Most Secured
## Linux distribution/distro
- Distro: A Linux distribution (often referred to as a "distro") is a complete operating system built on top of the Linux kernel. (is Modified Linux kernel) type of operating system with different: 
   - Linux Kernel
   - Package(GNU)
   - Package manager
   - Desktop UI
##### There are so many distros:-
###### Debian
- kail linux 
- ubuntu
- parrot
###### Arch
- Black
- arch
- Garuda
##### what is best for hackers?
- kail Linux
- parrot OS
- Garuda
- Black Arch
###### Kail  Linux
Kali Linux is a specialized Linux distribution designed for penetration testing, digital forensics, and network security assessments. It is based on Debian. Have dragon wallpaper.
- **Desktop Env: XFCE
- **package manager: APT
- **shell: ZSH

###### Parrot OS
It is also based on Debian with a focus on security, privacy and development.
- **Desktop env : Mate
- **package manager: APT 
- **shell: BASH

###### Garuda
Is a Linux distribution based on Arch Linux operating system.
- **desktop env : KDE plasma
- **package manager: PACMAN
- **shell: FISH

#### **Note** that windows doesn't have distro. window is not open source so people wont use it.


## There are several methods to use a Linux distribution, depending on your needs and preferences. Here are some common methods:
---

1. **Main OS**:  typically refers when the primary operating system is Linux. recommended for slow pc.
2. **Dual Boot(2in1)**: Dual booting allows you to have multiple operating systems installed on your computer and choose which one to use at startup. With this method, you can install a Linux distribution alongside an existing operating system.
3. **Live boot**: a "live" version that allows you to run the operating system directly from a USB flash drive or DVD without installing it. This method is useful for testing out a Linux distribution or accessing a Linux environment temporarily without making any permanent changes to your computer.
4. **cloud terminal**: This method allows you to use a Linux distribution on a virtual machine in the cloud, have shell only.
5. **Virtual machines**: You can use virtualization software, such as Oracle VirtualBox or VMware, to create a virtual machine (VM) on your existing operating system. Then, you can install the Linux distribution within the virtual machine. This method allows you to run Linux alongside your primary operating system without affecting it.
- Example of software's to use : 
    - HyberV
    - VirtualBox-Oracle
    - VMware

6. **WSL V2(Windows subsystem for Linux)**:WSL allows you to run a Linux distribution within a lightweight virtual machine directly within the Windows environment. 
7. **Termux-Android**: for running some codes and doing simple things.
###### so this was Day 2 note✅ that is continued from [[class1;Introduction to ethical hacking]]


 