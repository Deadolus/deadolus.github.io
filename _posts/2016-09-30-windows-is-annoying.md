---
layout:     post
title:      "Windows is unbearable"
subtitle:   "The OS is annoying as hell"
date:       2016-09-30 14:05:00
author:     "Smne"
header-img: "img/post-broken-computer.jpg"
---
We have a emulated Windows 8 in Virtualbox.
And I consider myself lucky that we still can use our favourite flavour of Linux for our *real* development environment (Ubuntu for me and Debian for my colleague).   

Windows seems so slow and buggy to me, that I would have probably quit by now if I would have to actually work with it. 
The problem starts with the start up process: I never could figure out why I have to first input another character before I can start enter my password. 
Worse, sometimes it seems that Windows forfeits on that requirement and would accept the first letter of my password - but by then I've already typed an other character. 
This inconsistency leads to me cursing about the OS, which I am about to use, even before I see the desktop. 
It seems that even some of my everyday Windows colleagues are annoyed by that and have not yet figured out how to circumvent this behaviour 

There seems to be no hope with this OS: the new restart/shutdown behaviour is annyoing as well. 
I am a developer and sometimes I switch OS. This means turning the computer off completely and then start it up again, choosing another system in GRUB (right after the BIOS) and booting up. 
I then want to mount the NTFS partition from Windows in my Linux system. 
But the new restart behaviour seems to be one of semy sleep, where it never actually goes down and sets the NTFS partition in a "resting" place, where it can only be mounted as "read only". 
Shutting down the system does not help either: same thing - the NTFS partition never gets powered off properly.   
I have to 
	shutdown /r /t 0
The system in order for it to actually go down properly. 

It is the little things that make this system so unbearingly annoying to me. 



