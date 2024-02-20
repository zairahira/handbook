Learning Linux is one of the most valuable skills in the IT industry. It can help you get things done faster and efficiently. Many of the world's powerful servers and supercomputers run on Linux.

I have been an active user of Linux for more than 8 years now. I have maintained critical Linux application and webservers as my role as a system administrator. I have also used Linux as my primary operating system for development and personal use.

Fun fact- as much as I am a fan of Linux right now, there was a time when I hated(yes hated, I can't find a better word) Linux. I used to skip the labs when I was studying software engineering. I just didn't have the patience to understand the commands or to identify the syntax errors in the scripts as they were very unforgiving. Today, I stand at a different place. So, you never actually know when the tables can be turned. 😃

I don't want any learner to go through unwanted pain when learning the command line. It seems daunting and it is easy to get overwhelmed. Don't worry, I have you covered. I'll go through the concepts step by step and I'll make sure that you understand the concepts before moving on to the next one. It won't just be theory, but also some practical examples to make sure that you understand the concepts.

The contents of this book are carefully curated as I am only teaching the content that made sense to me, and the content that is fool-proof, no non-sense.In this book, you'll learn the basics of the Linux command line, and then more advanced topics such as shell scripting and system administration. Whether you are new to Linux, or have been using it for years, this book has something for you.

# Table of Contents

## What is Linux?

Linux is an open-source operating system that is based on the Unix operating system. It was created by Linus Torvalds in 1991.Open-source means that the source code of the operating system is available to the public. This allows anyone to modify and distribute the operating system.

If you are curious, you can have a look at the source code of the Linux kernel at [GitHub](https://github.com/torvalds/linux)

## Why should you learn about Linux?

In today's data center landscape, Linux and Microsoft Windows stand out as the primary contenders, with Linux having a major share. Here are several compelling reasons to learn Linux:

- If you are accustomed to Windows environments, familiarity with Linux is essential for seamless interoperability.
- Given the prevalence of Linux hosting, there is a high chance that your application would be hosted on Linux. Hence learning Linux as a developer becomes increasingly valuable.
- With cloud computing becoming the norm, chances are high that your cloud instances will rely on Linux.
- Linux serves as the foundation for many operating systems for Internet of Things (IoT) and mobile applications.
- In IT, opportunities abound for those skilled in Linux, remains consistently high.

Based on my personal experience in the corporate with Project managers and developers, I have noticed that people don't focus on learning such stuff. It is overwhelming and pushed to the side. So why don't you leearnit and become a unique asset?

## What does it meant that Linux is an open source operating system?

First, what is open-source? Open source software is the software whose source code is freely accessible, allowing anyone to utilize, modify, and distribute it.

Whenever source code is created, it is automatically considered copyrighted, and its distribution, is governed by the copyright holder through software licenses.

In contrast to open source, proprietary or closed-source software restricts access to its source code. Only the creators can view, modify, or distribute it.

Linux is open source primarily and it means that its source code is freely available. Anyone can view, modify, and distribute it. Developers from anywhere in the world can contribute to its improvement. This lays the foundation of collaboration which is an important aspect of open source softwares. The collaboative approach has led to the widespread adoption of Linux across servers, desktops, embedded systems, and mobile devices.

The most interesting aspect of Linux being open source is that anyone can tailor the operating system to their specific needs without being restricted by proprietary limitations. Who knows, maybe you are the next distro creator :wink:

If you are curious how the Linux kernel looks like, [here](https://github.com/torvalds/linux) is the GitHub link!

## What is a Linux distribution?

By this point you know that you can re-use the Linux kernel code, modify it and create a new kernel. You can further combine different utilities and software to create a completely new operating system. So,a Linux distribution is a version of the Linux operating system that includes the Linux kernel, system utilities, and other software. Being open-source, a Linux distribution is a collaborative effort involving multiple independent open-source development communities.

Today there are [hundreds](https://upload.wikimedia.org/wikipedia/commons/1/1b/Linux_Distribution_Timeline.svg) of Linux distributions to choose from, offering differing goals and criteria for selecting and supporting the software provided by their distribution.

- Distributions vary from one another, but they generally have a number of common characteristics:
- A distribution consists of a Linux kernel.
- It supports user space programs.
- A distribution may be small and single-purpose or include thousands of open source programs.
- Some means of installing and updating the distribution and its components should be provided.

## How to install and access linux

The best way to learn is to apply the concepts as you go. In this section, we'll learn how to install Linux on your machine so you can follow along. We'll also learn how to access Linux on a Windows machine.

#### Install Linux as the primary OS

Installing Linux as the primary OS is the most efficient way to use Linux as you can use the full power of your machine.

In this section, you will learn how to install Ubuntu, which is one of the most popular Linux distributions.
I have left out other distributions for now, as I want to keep things simple. You can always explore other distributions once you are comfortable with Ubuntu.

- Step 1: Download the Ubuntu iso
  Go to the official [website](https://ubuntu.com/download/desktop) and download the iso file.

- Step 2: Create a bootable pendrive
  There are a number of softwares that can create a bootable pendrive. I recommend using Rufus, as it is quite easy to use. You can download it from [here](https://rufus.ie/)

- Step 3: Boot from the pendrive
  Once your bootable pendrive is ready, insert it and boot from the pendrive.The boot menu depends on your laptop. You can google the boot menu for your laptop model.

- Step 4: Follow the prompts
  Once, the boot process starts, select `try or install ubuntu`.

![Alt text](try-install-ubuntu.png)

The process would take some time. Once the GUI appears, you can select the language, keyboard layout and continue.
Enter your login and name. Remember it as you will need it to login to your system and access full privileges.

Wait for the installation to complete.

- Step 5: Restart

Click on restart now and remove the pendrive.

- Step 6: Login

Login with the credentials you entered earlier.

And there you go!
Now you can install apps, customize your desktop, and you are good to go!

![Alt text](image.png)

for advanced installation, you can explore the following topics:

- Disk partitioning.
- Setting swap memory for enabling hibernation.

Explore the terminal and folders.

> 💡 The shortcut for opening the terminal is `ctrl+alt+t`

### install linux on a windows machine

As a developer, you might need to run both Linux and Windows side by side. Luckily, there are a number of ways you can get the best of both worlds without getting different computers for each operating system.

In this article, we'll explore a few ways to use Linux on a Windows machine. Some of them are browser-based or cloud-based that do not need any installation prior to using them.
