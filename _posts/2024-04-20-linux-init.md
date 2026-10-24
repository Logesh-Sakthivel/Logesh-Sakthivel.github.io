title: "Linux init"
categories:
  - Blog
tags:
  - Linux
  - init
---

### Daemon process

In the Unix and Linux world, a daemon is a background process that typically performs tasks without requiring user interaction. These tasks often involve critical services like system logging, email routing, or web server hosting. A daemon process, also known as a daemon, is a background process in Linux that runs continuously, even when no user is logged in.

### User mode
There are two modes found in a operating system, 
    - Kernel mode
    - User mode

User mode has some limited access to the system resources. Whenever you run the application in your computer system, it runs in User mode.  When opening the program in user mode, it is not allowed to access the RAM and hardware directly. To access the hardware and RAM in user mode, it sends a request to the kernel. That is the reason user mode is also known as slave mode, or restricted mode. If there is any program failure in user mode, it does not affect the other processes. It only affects that particular process where an interrupt occurs.

### Kernel mode
 When we start our system, it boots in the kernel mode. The kernel can access the hardware and RAM of the system directly. There are some privileged instructions that can run in the kernel mode only. If a kernel-mode driver crashes, it causes the entire operating system to crash.
