# lfs-base
Rather than provide the entire filesystem, I have here the most vital parts of the operating system, that I most directly engaged with, /bin, /lib and /sources

[read more here](http://derric.xyz/lfs-port-page/index.html)
# About

## Why build Linux from scratch?
At Holberton we learn a lot in a wide range of topics. We use Linux with every project for development, and we learn a lot about how to use it and be comfortable having a linux workflow, but we never get the chance to learn how linux itself works.
I am fascinated by the simplicity, variety and flexibility of the linux operating system. It is found everywhere and makes up a majority of the worlds backend computing power. As a developer who has used linux personally for a few years, I felt the need to pull back the curtain and try to understand just what makes up a Linux operating system.
It should be said that Linux is a kernel. If you look at all the packages provided in this project, you'll see that linux makes up 1/80th of that number. The rest of the operating system is made of software designed to do a singular task. This means the system is highly modular.
The most common OS utilities come from Gnu Software. These utilities dont necessarily need the linux kernel. Gnu even develops their own kernel, The gnu Hurd kernel. This is most famously seen in the Gnu Guix OS. There are many other kernels used in the linux world, most notably the BSD family and Apples MacOS.

The Linux kernel holds a lion's share of the unix market and makes it the most accessible and approachable. The opensource development of the kernel makes it possible for anyone to theoretically take part in it's development and be a part of it's community. This also encourages those weary of commercial software to take part in making the open source option a viable consumer OS. With a driven community, the linux OS family is always growing in the desktop consumer market and we see an ever strong hold on the server market.

Building a Linux system from scratch is not easy, but it also not some insurmountable obstacle. It requires diligent research, a solid base understanding of the unix shell, the know how of building software from source and a bit of patience. What you get out of it is a completely custom system, a deep understanding of that system, and hopefully a linux takes special place in your development workflow.
# Packages - 
## find a rationalization for each included package here
[click on Packages tab](http://derric.xyz/lfs-port-page/lfs-overview.html)


## bin
 This directory holds all utlility programs. /bin = Binary, holds binaries of executable programs. These are typical for base administration of a linux system.
 
## lib
Holds import library files, linux kernel & modules, udev device programs and management. These help applications to properly execute. 

## sources 
Provides a list of source tar balls needed for every package in this linux system.

## boot
Boot directory, holds kernel and grub boot information


# Related
## Please read these sources if you are interested in linux from scratch.

[Linux from scratch project](http://www.linuxfromscratch.org/lfs/view/stable/index.html)

[Build your own linux project](https://acloud.guru/learn/9bb0f72b-7b03-4c4a-b5b6-684e80c12d42)

[learn about gentoo, a complete and professional from scratch distro](https://www.gentoo.org/)
 
 
