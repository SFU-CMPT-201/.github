# CMPT 201 Systems Programming

The School of Computing Science is introducing a new course, CMPT 201 Systems Programming, that will
satisfy the curriculum requirements currently met by CMPT 300 Operating Systems for both CS and SoSy
students. In other words, any students who take this course will be able to use it toward satisfying
CMPT 300 requirements.

By taking this course, students will learn:

* User-level services and abstractions provided by operating systems, and
* How to write low-level programs that utilize those services and abstractions correctly,
  efficiently, and reliably, using Linux.

Although this course is known to be a challenging course, it is not designed for an advanced
programmer. The training that this course aims to provide is to get students out of the beginning
stage and move them to an early intermediate stage. Students have to make that jump at some point in
their college career. This course forces students to make that jump, so they can advance much
further with upper-level courses.

Prerequisites are:

* (CMPT 125 or CMPT 135) and MACM 101, all with a minimum grade of C-
    * This course assumes that students thoroughly understand the intro programming materials and
      they do not struggle with them *at all*. This includes, but not limited to, basic programming
      constructs (e.g., loops, conditionals, functions/methods/modules, etc.) as well as basic data
      structures (e.g., linked lists, hashing and hash tables, etc.).
* Proficiency in C programming
    * This course uses C but does not teach C.
    * This course assumes that students thoroughly know C. This includes, but not limited to, the
      syntax of C, C `struct`s, C strings and how to manipulate them, arrays and pointers, the use
      of `malloc()` and `free()`, etc.
    * Knowing C++ is better but not enough. C is still different from C++.
    * A very basic test is asking yourself, "Can I write a doubly-linked list in C without getting
      any help (with all the features, creating/appending/deleting a node and traversing the list)?"
    * The following seem to be good resources to learn C.
        * [C for Python programmers](https://diveintosystems.org/book/C1-C_intro/index.html): I
          think this can serve as a general intro to C, not just for Python programmers but any
          programmers.
        * [C for Java
          programmers](https://www.cs.rochester.edu/u/ferguson/csc/c/c-for-java-programmers.pdf)
        * [Here's another one](https://github.com/jflaherty/ptrtut13/blob/master/md/pointers.md)
          that talks about pointers and strings, which might be helpful:
* Experience in using the command-line interface on Linux
    * We do not expect students to have proficiency but *some* experience.

Upon completion of this course, students are expected to achieve proficiency in the following areas:

* Interacting with, and programming in, a Linux environment using the command-line interface.
* Utilizing programming tools such as build systems and debuggers.
* Programming with processes and threads.
* Understanding concurrency concepts such as semaphores, locks, critical sections, deadlocks, common
  concurrency patterns, etc.
* Manipulating and managing data in memory correctly.
* Understanding file system abstractions and programming with them.
* Understanding communication abstractions such as IPC, sockets, and RPC and programming with them.
* Understanding cryptographic functions and programming with them.

## Course Schedule and Location

### Lectures

* Tu 12:30PM - 2:20PM (K9500)
* Th 12:30PM - 2:20PM (Images Theatre in RCB Hall)

### Labs

* Th 2:30PM - 3:20PM (ASB9838)
* Th 2:30PM - 3:20PM (ASB9838)
* Th 3:30PM - 4:20PM (ASB9838)
* Th 3:30PM - 4:20PM (ASB9838)

## Instructor

* Steve Ko <<steveyko@sfu.ca>>

## TAs

* Kimia Khabiri <<kimia_khabiri@sfu.ca>>
* Parsa Hoseininejad <<parsa_hosseininejad@sfu.ca>>
* Mohammad Omidvar <<m_omidvart@sfu.ca>>
* Shishir Gopinath <<shishir_gopinath@sfu.ca>>

## Office Hours

* Steve Ko: 10 am - 12 pm Mondays at TASC1 8019
* Shishir Gopinath: 2:30 pm - 4:30 pm Tuesdays at ASB 9808
* Kimia Khabiri: 2:30 pm to 4:30 pm Wednesdays at ASB 9810
* Mohammad Omidvar: 9:00 am - 11:00 am Thursdays at ASB 9812
* Parsa Hoseininejad: 2:30 pm to 4:30 pm Fridays at ASB 9810

## Recommended Textbooks

The Linux Programming Interface: A Linux and UNIX System Programming Handbook, Michael Kerrisk,
2010.

* This book is arguably *the* best book on systems programming using Linux.
* If someone is looking to purchase *one* book on systems programming, this book is that book.
* A lot of the course materials are based on this book.
* This book is *almost* required. There are two reasons why it is almost.
    * The book covers much more than what this course covers.
    * The book is not inexpensive.
* If there is a student struggling with the materials of this course, it is recommended to purchase
  this book and read along.

[Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/), Remzi H.
Arpaci-Dusseau and Andrea C. Arpaci-Dusseau

* This is a free online book on operating systems.
* This course teaches some of the concepts described in the book. However, the book goes much more
  in detail than what this course teaches, hence it is not a required book.
* Nevertheless, [the course lecture notes](https://github.com/SFU-CMPT-201/lecture-notes) refer to
  some chapters of the book and students are expected to read those chapters.

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

## Lecture Notes and Schedule

The [Lecture Notes repo](https://github.com/SFU-CMPT-201/lecture-notes) contains the current lecture
notes. The schedule generally looks as follows.

* Week 1 - Week 2: [Tour of Computer
  Systems](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/01-tour.md)
* Week 2 - Week 3: [`fork()`, `exec()`, `wait()`, and
  `errno`](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/02-fork-exec-wait.md) &
  [Signals](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/03-signals.md)
* Week 4 - Week 5: [Scheduling
  Algorithms](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/04-scheduling.md) & [Memory
  Management](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/05-memory-management.md)
* Week 5 - Week 6: [Virtual
  Memory](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/06-virtual-memory.md)
* Week 6: Midterm
* Week 7 - Week 8: [Threads](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/07-threads.md)
  and
  [Synchronization](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/08-synchronization.md)
* Week 9 - Week 10: [File
  I/O](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/09-file-io.md)
* Week 10 - Week 11: [Network
  Programming](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/10-network-programming.md)
* Week 12: [IPC](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/11-ipc.md)
* Week 13: [Basic
  Cryptography](https://github.com/SFU-CMPT-201/lecture-notes/blob/main/12-basic-crypto.md)
* Week 14: Final

## Assignments

There are two types of assignments in this course---short assignments and long assignments. Short
assignments are designed to be straightforward and tutorial-like, while long assignments require a
significant time investment. The difficulty level of long assignments is **substantially** higher
than that of short assignments.

Students should consider these assignments **take-home exams** rather than traditional homework.
This is because we require students to complete them in a highly-controlled environment using our
[Docker setup](#docker-container-setup). Modifying the environment is **not** allowed and considered
a violation of academic integrity.

### Short Assignments

The first type of assignments in this course is short assignments.

* In the first few weeks of the course, students are expected to finish *two* short assignments per
  week.
* Each short assignment is in the style of a tutorial and takes about 2-3 hours to complete.
* These assignments are designed to teach students basic tools and concepts that students use for
  in-class activities and long assignments.
* Unlike long assignments, short assignments are designed to be straightforward.

Below are the short assignments, provided for your reference. Each offering of CMPT 201 has its own
private repos for these assignments and instructions may vary slightly. Therefore, if you are taking
CMPT 201, please make sure you use the correct repos corresponding to your term instead of the
repos below.

* [A0: Basics of the Command-Line Interface](https://github.com/SFU-CMPT-201/a0-pub)
* [A1: Neovim](https://github.com/SFU-CMPT-201/a1-pub)
* [A2: Bash Scripting](https://github.com/SFU-CMPT-201/a2-pub)
* [A3: Basics of Compilation](https://github.com/SFU-CMPT-201/a3-pub)
* [A4: Make and CMake](https://github.com/SFU-CMPT-201/a4-pub)
* [A5: Debugging Tools](https://github.com/SFU-CMPT-201/a5-pub)
* [A6: Memory Layout](https://github.com/SFU-CMPT-201/a6-pub)
* [A7: More on Memory Layout, Data Types, and Alignment](https://github.com/SFU-CMPT-201/a7-pub)

### Long Assignments

The second type of assignments in this course is long assignments.

* Long assignments are *exponentially* more challenging than short ones, specifically designed to
  push students to test and enhance their programming skills.
* The expectation is that each assignment will take 15-20 hours to complete. However, students
  sometimes report spending 30-40 hours on each long assignment. This discrepancy is likely due to
  varying levels of preparedness with the prerequisites.
* In other words, the level of challenge posed by the assignments can vary significantly, depending
  on the student's stage of proficiency in general programming and their understanding of the
  prerequisite materials (e.g., beginner-beginner, intermediate-beginner, advanced-beginner).
* Long assignments typically do not provide a detailed step-by-step guide. Students are expected to
  *figure things out* independently. The course is designed to train and challenge students,
  fostering self-reliance and problem-solving skills.

Below are the long assignments, provided for your reference. Each offering of CMPT 201 has its own
private repos for these assignments and instructions may vary slightly. Therefore, if you are taking
CMPT 201, please make sure you use the correct repos corresponding to your term instead of the repos
below.

* [A8: Simple Shell](https://github.com/SFU-CMPT-201/a8-pub)
* [A9: Memory Management](https://github.com/SFU-CMPT-201/a9-pub)
* [A10: Simple MapReduce](https://github.com/SFU-CMPT-201/a10-pub)
* [A11: A Simple Group Chat Server with Fuzzing Clients](https://github.com/SFU-CMPT-201/a11-pub)
* [A12: Simple Blockchain](https://github.com/SFU-CMPT-201/a12-pub)

## Exam Samples

Exams from Fall 2023 are available for reference.

* [Midterm](../res/midterm.pdf)
* [Final](../res/final.pdf)

## Docker Container Setup

* You will use a Docker container for everything in this course.
* You are **not** allowed to modify this setup in any way. **Doing so is considered an academic
  integrity violation.**
* Setting up the Docker container will take some time, e.g., a few hours, and it is necessary for
  the first assignment, which will take another few hours. So make sure you start this right away.
  Downloading and running the container (as described below) is not the end of the setup process.
  There are more things to do after you log in.
* First, install [Docker Desktop](https://docs.docker.com/desktop/). Choose the correct version for
  your platform. If you already have Docker installed, make sure you have the latest version. Once
  you install it, start it. You can run it in the background as you don't need the GUI.
    * On Linux, it may be simpler to just install [Docker Engine](https://docs.docker.com/engine/)
      instead of Docker Desktop. It is lighter weight than Docker Desktop. If you decide to do it,
      after installation, you should also follow the instructions on [Manage Docker as a non-root
      user](https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user).
      This way, you can avoid using `sudo` to use Docker.
* Next, make sure you have a good terminal emulator installed. For Windows, install [Windows
  Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701). For Mac, install
  [iTerm2](https://iterm2.com/). Do not use the default Terminal app since it's not going to display
  certain things correctly. For Linux, the default terminal is fine at least for GNOME. We have not
  tested the default terminal for KDE. There are many other options such as
  [foot](https://codeberg.org/dnkl/foot), [Alacritty](https://alacritty.org/), etc., but you need to
  be comfortable with editing configuration files with these. You can use those if you know what
  you're doing or if you are more adventurous.
* You will spend a lot of time on the terminal in this course. Therefore, it is important to use a
  terminal setting that is comfortable. Change the terminal setting as follows.
    * Change the width to more than 100, e.g., 110.
    * Change the height to a length that is sufficiently long.
    * Change the color scheme to `solarized dark`. Windows Terminal, iTerm2, and GNOME Terminal
      should support it out of the box. Google how to change the color scheme if you are not sure.
      For other terminal emulators, it's likely that you need to install the theme separately.
* Open the terminal and enter the following commands.
    * `docker create -it --name cmpt201 ghcr.io/sfu-cmpt-201/base`
        * This command downloads our container image (`ghcr.io/sfu-cmpt-201/base`) and creates an
          interactive (`-it`) container named `cmpt201`.
        * Note that you only need to execute this once as you don't need to create an image multiple
          times.
        * If you're using an ARM laptop, you may get a warning that says that the platforms don't
          match. Don't worry about it. Our Docker image is for `amd64` but ARM laptops can still run
          it without any issues.
    * `docker start -ai cmpt201`
        * This command starts the container interactively (`-ai`) and lets you enter the container.
    * Once again, from now on, you *do not* need to create a container image. You only need to start
      the created container. In other words, you only need to execute `docker start -ai cmpt201`.
* At this point, you should see a greeting message and a command-line prompt (`~❯`).
* If you enter `ls`, you should see two files (`start_here.sh` and `units`).
* Enter `./start_here.sh` and read through. It will show you what to do.
* When you want to stop using the container, enter `exit`.
* When you want to use the container again, enter the start command (`docker start -ai cmpt201`).
* Make sure you do not delete the container (e.g., `docker rm`). You will lose all the files, i.e.,
  your work.

## Course Policies

### Pull Request Policy

* If you see that you have a pull request, please merge it. Pull requests contain updates to the
  assignments.
* In order to do it, go to your repo's webpage, check if your `Pull requests` tab shows a number. If
  it doesn't show a number, you don't need to do anything as there is no pull requests.
* If it does show a number, click the tab, click a pull request, scroll all the way down, and click
  `Merge pull request` (green button). If there are more than one pull request, please merge each
  and every one.

### Grading Policy

* All submissions should be done on GitHub Classroom and/or CourSys. Email submissions are not
  accepted.
* Submissions that do not follow the instructions down to the letter receive a zero.
* Late submissions are not accepted.
* All members of the same group receive the same grade (if there is a group).
* Students must attain an overall passing grade on the weighted average of exams
  (quizzes/midterms/final) in the course in order to obtain a clear pass (C- or better).

### Re-grading Policy

* A *private Piazza post* is the *only* way to request a re-grading. Make sure you add all
  instructors (i.e., post to `Instructors`). If you do not post to all instructors, we will not
  accept the request.
* We will not accept email requests either.
* Before requesting a re-grading for an assignment, make sure you run the checker/grader/test cases
  and see the output. Request a re-grading only when the grade is different from your expectation
  based on the output.
* In your re-grading request, clearly tell us the assignment name, your SFU ID, your GitHub
  username, and how your grade is different from what you expect from the checker/grader/test cases
  output.
* If you have either chosen a wrong ID or not chosen an ID at all for GitHub Classroom, you get a 0
  and there is no re-grading.
* Lastly, you have one week to request a re-grading from the time your grade is released.

### Piazza Policy

* In this course, Piazza is mainly for you to help each other. If you know how to answer a question,
  please provide your answer and help out others.
* If no sensitive information is involved, always consider posting a question as a public question,
  not as a private question. It could be beneficial for other people in class.
* Depending on the volume of questions, the teaching staff may not be able to answer all questions
  in a timely fashion.
* The teaching staff monitors Piazza only during regular work days (Mon-Fri, excluding holidays) and
  regular work hours (9 am - 5 pm).
* For coding questions, it is most likely necessary to examine your code carefully and perhaps run
  it as well. This means that most of the times, it is much better to use the office hours than
  Piazza.
* For a followup discussion, always come back and mark it as resolved if the answer has been
  provided.

### Academic Integrity Policy

* All submitted work should be your own. For example, if you copy code from the Internet or from
  your peers, it is not your own work.
* You should not allow others to copy your code either. For example, your peer should not copy your
  code and you should not post your code on the Internet.
* Any violations of academic integrity receive an F for the course.
* We generally follow [the academic integrity policies from the
  university](http://www.sfu.ca/students/academicintegrity.html).
