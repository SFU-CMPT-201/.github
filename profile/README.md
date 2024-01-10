# CMPT 201 Systems Programming

The School of Computing Science is introducing a new course, CMPT 201 Systems Programming, that will
satisfy the curriculum requirements currently met by CMPT 300 Operating Systems for both CS and SoSy
students. In other words, any students who take this course will be able to
use it toward satisfying CMPT 300 requirements.

By taking this course, students will learn:

* User-level services and abstractions provided by operating systems, and
* How to write low-level programs that utilize those services and abstractions correctly,
  efficiently, and reliably, using Linux.

Students will be equipped with important practical and theoretical background for upper-level
courses. Topics covered in this course include (but not limited to):

* Memory management
* Concurrency
* Storage and file system abstractions
* Communication abstractions such as IPC, sockets, and RPC
* Basics of OS security and cryptographic functions.

Prerequisites are:

* (CMPT 125 or CMPT 135) and MACM 101, all with a minimum grade of C-
* Proficiency in C programming (e.g., writing CMPT 125- or CMPT 135-level programs in C without
  getting help)
* Experience in using the command-line interface on Linux

Students are expected to achieve proficiency in the following areas:

* Interacting with, and programming in, a Linux environment using the command-line interface.
* Utilizing programming tools such as build systems and debuggers.
* Manipulating and managing data in memory correctly.
* Understanding concurrency concepts such as semaphores, locks, critical sections, deadlocks, common
  concurrency patterns, etc.
* Programming with processes and threads.
* Understanding file system abstractions and programming with them.
* Understanding communication abstractions such as IPC, sockets, and RPC and programming with them.
* Understanding cryptographic functions and programming with them.

## Course Schedule and Location

Tu & Th 12:30 PM - 2:20 PM, SWH 10041, Burnaby

## Instructor

Steve Ko <<steveyko@sfu.ca>>

## TAs

Kimia Khabiri <<kka156@sfu.ca>>

Parsa Hoseininejad <<sph6@sfu.ca>>

## Office Hours

Steve Ko: Tu & Th 11:00 AM

## Recommended Textbooks

The Linux Programming Interface: A Linux and UNIX System Programming Handbook, Michael Kerrisk,
2010.

[Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/), Remzi H.
Arpaci-Dusseau and Andrea C. Arpaci-Dusseau

## Reference Books

Computer Systems: A Programmer's Perspective, 3rd Edition, Randal E. Bryant and David R. O'Hallaron,
2015.

Advanced Programming in the UNIX Environment, 3rd Edition, W. Stevens and Stephen Rago, 2013

Unix Network Programming, Volume 1: The Sockets Networking API, 3rd Edition, W. Stevens, Bill
Fenner, and Andrew Rudoff, 2003

UNIX Network Programming, Volume 2: Interprocess Communications, 2nd Edition, W. Richard Stevens,
1998

The Art of Unix Programming, Eric Steven Raymond, 2003

C Programming Language, 2nd Edition, Dennis Ritchie and Brian Kernighan, 1988

## Grading (tentative)

* Midterm: 15%
* Final: 15%
* Programming assignments: 66%
    * 8 short assignments: 2% each
    * 5 long assignment: 10% each
* In-class activities: 4%

## Grading Policies

* All submissions should be done on GitHub Classroom and/or CourSys. Email submissions are not
  accepted.
* Submissions that do not follow the instructions down to the letter receive a zero.
* Late submissions are not accepted.
* All members of the same group receive the same grade (if there is a group).
* Students must attain an overall passing grade on the weighted average of exams
  (quizzes/midterms/final) in the course in order to obtain a clear pass (C- or better).

## Academic Integrity Policies

* All submitted work should be your own. For example, if you copy code from the Internet or from
  your peers, it is not your own work.
* You should not allow others to copy your code either. For example, your peer should not copy your
  code and you should not post your code on the Internet.
* Any violations of academic integrity receive an F for the course.
* We generally follow [the academic integrity policies from the
  university](http://www.sfu.ca/students/academicintegrity.html).

## VM Links and Instructions

* Setting up the course VM will take some time, e.g., a few hours, and it is necessary for the first assignment, which
  will take another few hours. So make sure you start this right away. Downloading and running the
  VM (as described below) is not the end of the setup process. There are more things to do after
  you log in.
* For Windows, Linux, and Intel Macs, please install the latest [VMware
  Player](https://www.vmware.com/ca/products/workstation-player.html) or
  [Fusion](https://customerconnect.vmware.com/evalcenter?p=fusion-player-personal-13) on your
  machine.
* For ARM-based Macs, please install [UTM](https://getutm.app/).
* Below are the links for our VM. To download these, you need to first log in on Microsoft 365
  (OneDrive, SharePoint, etc.) with your SFU credentials.
    * [VMware x86-64 VM Image](https://shorturl.at/yzE09)
    * [UTM Image for ARM-based Mac](https://shorturl.at/hipqS)
* Once you download an image, prepare it to run it.
    * Unzip the file.
    * Move the unzipped folder/file to a location where you want to keep it.
    * For VMware, you can either double click the `.vmx` file (inside the unzipped folder) or use
      `Open a Virtual Machine`.
    * For UTM, you can double click the unzipped `.utm` package. It will appear in your UTM VM list.
* You can now run the VM. After it boots up, pay attention to the login message. It should give you
  an IP address as well as the username and the password that you can use to log in.
* At this point, make sure you have installed a good terminal emulator. For Windows, install
  [Windows Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701). For
  Mac, install [iTerm2](https://iterm2.com/). Do not use the Terminal app since it's not going to
  display certain things correctly. For Linux, the default terminal is fine, at least for GNOME. We
  have not tested the default terminal for KDE. There are many other options such as
  [foot](https://codeberg.org/dnkl/foot), [Alacritty](https://alacritty.org/), etc., but you need to
  be comfortable with editing configuration files with these. You can use those if you know what
  you're doing or if you are more adventurous.
* You will spend a lot of time on the terminal in this course. Therefore, it is important to use a
  terminal setting that is comfortable. Change the terminal setting as follows.
    * Change the width to more than 100, e.g., 110.
    * Change the height to a length that is sufficiently long.
    * Change the color scheme to `solarized dark`. Windows Terminal, iTerm2, and GNOME Terminal
      should support it out of the box. Google how to change the color scheme, if you are not sure.
      For other terminal emulators, you need to install the theme separately.
* Open the terminal, and enter `ssh cmpt201@[VM's IP address]`. Replace `[VM's IP address]` with the
  IP address that you get from the VM window.
* Use the password from the VM window to log in on the terminal.
* If you enter `ls`, you should see two files (`start_here.sh` and `units`).
* Enter `./start_here.sh` and read through. It will show you what to do.
* When you want to stop using the VM, make sure that you properly shut it down by entering
  `sudo poweroff`. **Do not** just close the VM window since it will corrupt the VM.
  (You can also use `sudo reboot` to reboot the VM.)
