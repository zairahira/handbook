Learning Linux is one of the most valuable skills in the IT industry. It can help you get things done faster and more efficiently. Many of the world's powerful servers and supercomputers run on Linux.

I have been an active user of Linux for more than 8 years now. I have maintained critical Linux application and web servers in my role as a system administrator. I have also used Linux as my primary operating system for development and personal use.

Fun fact- as much as I am a fan of Linux right now, there was a time when I hated(yes hated, I can't find a better word) Linux. I used to skip the labs when I was studying software engineering. I just didn't have the patience to understand the commands or to identify the syntax errors in the scripts as they were very unforgiving. Today, I stand at a different place. So, you never actually know when the tables can be turned. 😃

I don't want any learner to go through unwanted pain when learning the command line. It seems daunting and it is easy to get overwhelmed. Don't worry, I have you covered. I'll go through the concepts step by step and I'll make sure that you understand the concepts before moving on to the next one. I won't teach only theory, but also some practical examples to make sure that you understand the concepts.

The contents of this book are carefully curated as I am only teaching the content that makes sense to me and the content that is fool-proof and to the point.

In this book, you'll learn the basics of the Linux command line, and then more advanced topics such as shell scripting and system administration. Whether you are new to Linux, or have been using it for years, this book has something for you.

# Table of Contents

[Part 1: Introduction to Linux](#part-1-introduction-to-linux)

- [1. Getting started with Linux](#1-getting-started-with-linux)
  - [What is Linux?](#what-is-linux)
  - [Why should you learn about Linux?](#why-should-you-learn-about-linux)
  - [What does it mean that Linux is an open source operating system?](#what-does-it-meant-that-linux-is-an-open-source-operating-system)
  - [What is a Linux distribution?](#what-is-a-linux-distribution)
  - [How to install and access linux](#how-to-install-and-access-linux)
    - [Install Linux as the primary OS](#install-linux-as-the-primary-os)
    - [How to use Linux on a windows machine](#how-to-use-linux-on-a-windows-machine)

# Part 1: Introduction to Linux

## 1. Getting started with Linux

### What is Linux?

Linux is an open-source operating system that is based on the Unix operating system. It was created by Linus Torvalds in 1991. Open source means that the source code of the operating system is available to the public. This allows anyone to modify and distribute the operating system.

If you are curious, you can have a look at the source code of the Linux kernel at [GitHub](https://github.com/torvalds/linux)

### Why should you learn about Linux?

In today's data center landscape, Linux and Microsoft Windows stand out as the primary contenders, with Linux having a major share. Here are several compelling reasons to learn Linux:

- If you are accustomed to Windows environments, familiarity with Linux is essential for seamless interoperability.
- Given the prevalence of Linux hosting, there is a high chance that your application will be hosted on Linux. Hence learning Linux as a developer becomes increasingly valuable.
- With cloud computing becoming the norm, chances are high that your cloud instances will rely on Linux.
- Linux serves as the foundation for many operating systems for the Internet of Things (IoT) and mobile applications.
- In IT, opportunities abound for those skilled in Linux, remain consistently high.

### What does it mean that Linux is an open-source operating system?

First, what is open source? Open source software is software whose source code is freely accessible, allowing anyone to utilize, modify, and distribute it.

Whenever source code is created, it is automatically considered copyrighted, and its distribution is governed by the copyright holder through software licenses.

In contrast to open source, proprietary or closed-source software restricts access to its source code. Only the creators can view, modify, or distribute it.

Linux is open source primarily and it means that its source code is freely available. Anyone can view, modify, and distribute it. Developers from anywhere in the world can contribute to its improvement. This lays the foundation of collaboration which is an important aspect of open source software. The collaborative approach has led to the widespread adoption of Linux across servers, desktops, embedded systems, and mobile devices.

The most interesting aspect of Linux being open source is that anyone can tailor the operating system to their specific needs without being restricted by proprietary limitations.

> Fun fact: Chrome OS used by Chromebooks is also based on Linux.

![Alt text](image-1.png)

After reading this book, you might be motivated to create your own Linux distribution! 😃

If you are curious about how the Linux kernel looks like, [here](https://github.com/torvalds/linux) is the GitHub link!

### What is a Linux distribution?

By this point, you know that you can re-use the Linux kernel code, modify it and create a new kernel. You can further combine different utilities and software to create a completely new operating system. So, a Linux distribution is a version of the Linux operating system that includes the Linux kernel, system utilities, and other software. Being open source, a Linux distribution is a collaborative effort involving multiple independent open-source development communities.

Today there are [hundreds](https://upload.wikimedia.org/wikipedia/commons/1/1b/Linux_Distribution_Timeline.svg) of Linux distributions to choose from, offering differing goals and criteria for selecting and supporting the software provided by their distribution.

Distributions vary from one another, but they generally have several common characteristics:

- A distribution consists of a Linux kernel.
- It supports user space programs.
- A distribution may be small and single-purpose or include thousands of open-source programs.
- Some means of installing and updating the distribution and its components should be provided.

Some known Linux distributions are:

1.  **Ubuntu**: One of the most widely used and popular Linux distributions. It is user-friendly and recommended for beginners. [Learn more about Ubuntu here](https://ubuntu.com/).
2.  **Linux Mint**: Based on Ubuntu, Linux Mint provides a user-friendly experience with a focus on multimedia support. [Learn more about Linux Mint here](https://linuxmint.com/).

3.  **Arch Linux**: Popular among experienced users, Arch is a lightweight and flexible distribution aimed at users who prefer a DIY approach.[Learn more about Arch Linux here](https://www.archlinux.org/).

4.  **Manjaro**: Based on Arch Linux, Manjaro provides a user-friendly experience with pre-installed software and easy system management tools. [Learn more about Manjaro here](https://manjaro.org/).
5.  **Kali Linux**: Kali Linux provides a comprehensive suite of security tools and is mostly focused on cybersecurity and hacking. [Learn more about Kali Linux here](https://www.kali.org/).
6.

### How to install and access Linux?

The best way to learn is to apply the concepts as you go. In this section, we'll learn how to install Linux on your machine so you can follow along. You'll also learn how to access Linux on a Windows machine.

I recommend you to follow any one of the methods mentioned in this section to get Linux so you may follow along.

##### Install Linux as the primary OS

Installing Linux as the primary OS is the most efficient way to use Linux as you can use the full power of your machine.

In this section, you will learn how to install Ubuntu, which is one of the most popular Linux distributions.
I have left out other distributions for now, as I want to keep things simple. You can always explore other distributions once you are comfortable with Ubuntu.

- Step 1: Download the Ubuntu iso
  Go to the official [website](https://ubuntu.com/download/desktop) and download the iso file.

- Step 2: Create a bootable pendrive
  There are many software that can create a bootable pendrive. I recommend using Rufus, as it is quite easy to use. You can download it from [here](https://rufus.ie/)

- Step 3: Boot from the pendrive
  Once your bootable pendrive is ready, insert it and boot from the pendrive. The boot menu depends on your laptop. You can google the boot menu for your laptop model.

- Step 4: Follow the prompts
  Once, the boot process starts, select `try or install ubuntu`.

![Alt text](try-install-ubuntu.png)

The process would take some time. Once the GUI appears, you can select the language, and keyboard layout and continue.
Enter your login and name. Remember it as you will need it to log in to your system and access full privileges.

Wait for the installation to complete.

- Step 5: Restart

Click on restart now and remove the pen drive.

- Step 6: Login

Login with the credentials you entered earlier.

And there you go!
Now you can install apps, and customize your desktop, and you are good to go!

![Alt text](image.png)

For advanced installation, you can explore the following topics:

- Disk partitioning.
- Setting swap memory for enabling hibernation.

> 💡 The shortcut for opening the terminal is `ctrl+alt+t`

#### How to use Linux on a Windows machine?

As a developer, you might need to run both Linux and Windows side by side. Luckily, there are some ways you can get the best of both worlds without getting different computers for each operating system.

In this section, you'll explore a few ways to use Linux on a Windows machine. Some of them are browser-based or cloud-based and do not need any OS installation before using them.

- **Option 1: "Dual-boot" Linux + Windows**
  With dual boot, you can install Linux alongside Windows on your computer, allowing you to choose which operating system to use at startup.

This requires partitioning your hard drive and installing Linux on a separate partition. With this approach, you can only use one operating system at a time.

- **Option 2: Use Windows Subsystem for Linux (WSL)**
  Windows Subsystem for Linux provides a compatibility layer that lets you run Linux binary executables natively on Windows.

Using WSL has some advantages:

The setup for WSL is simple and not time-consuming.
It is lightweight compared to VMs where you have to allocate resources from the host machine.
You don't need to install any ISO or virtual disc image for Linux machines which tend to be heavy files.
You can use Windows and Linux side by side.

**How to Install WSL2?**

1. First, enable the Windows Subsystem for Linux option in settings.

2. Go to Start. Search for "Turn Windows features on or off."

3. Check the option "Windows Subsystem for Linux" if it isn't already.

![img](windows-on-off.png)

4. Next, open your command prompt and provide the installation commands.

Open Command Prompt as an administrator:

![img](cmd-admin.png)

Run the command below:

```
wsl --install
```

This is the output:

![Alt text](output-wsl-command.png)

> Note: By default, Ubuntu will be installed.

![img](ubuntu-installed.png)

Once installation is complete, you'll need to reboot your Windows machine. So, restart your Windows machine.

After restarting, you might see a window like this:

![Alt text](installing.png)

Once installation of Ubuntu is complete, you'll be prompted to enter your username and password.

![Alt text](login.png)

And, that's it! You are ready to use Ubuntu.

Launch Ubuntu by searching from the start menu.

![Alt text](launch.png)
And here we have our Ubuntu instance launched.

![Alt text](end-wsl.png)

**Option 3: Use a Virtual Machine (VM)**

A virtual machine (VM) is a software emulation of a physical computer system. It allows you to run multiple operating systems and applications on a single physical machine simultaneously. Here's a detailed explanation of VMs:

You can use virtualization software such as Oracle VirtualBox or VMware to create a virtual machine running Linux within your Windows environment. This allows you to run Linux as a guest operating system alongside Windows.

VM software provides options to allocate and manage hardware resources for each VM, including CPU cores, memory, disk space, and network bandwidth. You can adjust these allocations based on the requirements of the guest operating systems and applications.

Here are some of the options available for virtualization:

- [Oracle virtual box](https://www.virtualbox.org/)
- [Multipass](https://multipass.run/)
- [VMware workstation player](https://www.vmware.com/content/vmware/vmware-published-sites/us/products/workstation-player.html.html)

**Option 4: Use a Browser-based Solution**

Browser-based solutions are particularly useful for quick testing, learning, or accessing Linux environments from devices that don't have Linux installed.

You can either use online code editors or web-based terminals to access Linux. Note that you usually don't have full administration privileges in these cases.

**- Online code editors**

Online code editors offer editors with built-in Linux terminals. While their primary purpose is coding, you can also utilize the Linux terminal to execute commands and perform tasks.

[Replit](https://replit.com/) is an example of an online code editor, where you can write your code and access the Linux shell at the same time.
![img](replit.gif)

Replit provides a code editor and a Linux shell.

**- Web-based Linux terminals**

Online Linux terminals allow you to access a Linux command-line interface directly from your browser. These terminals provide a web-based interface to a Linux shell, enabling you to execute commands and work with Linux utilities.

One such example is [JSLinux](https://jslinux.org/). The screenshot below shows a ready-to-use Linux environment:

![Alt text](js-linux.png)

**Option 5: Use a Cloud-based Solution**

Instead of running Linux directly on your Windows machine, you can consider using cloud-based Linux environments or virtual private servers (VPS) to access and work with Linux remotely.

Services like Amazon EC2, Microsoft Azure, or DigitalOcean provide Linux instances that you can connect to from your Windows computer. Note that some of these services offer free tiers, but they are not usually free in the long run.
