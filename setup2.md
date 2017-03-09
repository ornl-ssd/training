---
layout: page
title: Setup for Day 2
---

For the second lesson in this course, you will need to ensure the following are installed on your computer:

* A [development environment](#a-development-environment) that includes Bash, `make`, and a C++ compiler
* [A Text Editor](#a-text-editor)

Please follow the instructions below for installing these packages for your operating system.

### A Development Environment

#### Windows

1. Download Git for Windows SDK. There are two installers, one for 32-bit Windows and one for 64-bit Windows. Use the 64-bit version only if 
you have 64-bit Windows installed. If unsure, choose the 32-bit version.
	* 32-bit installer [git-sdk-installer-1.0.3-32.7z.exe](https://github.com/git-for-windows/build-extra/releases/download/git-sdk-1.0.3/git-sdk-installer-1.0.3-32.7z.exe)
	* 64-bit installer [git-sdk-installer-1.0.3-64.7z.exe](https://github.com/git-for-windows/build-extra/releases/download/git-sdk-1.0.3/git-sdk-installer-1.0.3-64.7z.exe)
2. Run the installer and follow the instructions. Choose the option to create an icon on the desktop as this makes starting the shell easier.
3. The installation will take some time to compelete.

This will provide you with a Bash shell, the `make` command, and a C++ compiler.

To check if your installation is correct, launch the `Git SDK` application and type the command `make`.
If you see the following output, your installation is ok:

~~~
make: *** No targets specified and no makefile found.  Stop.
~~~
{: .output}

To check for a C++ compiler, enter the command `c++` at the prompt. You should see
the following output:

~~~
c++.exe: fatal error: no input files
~~~
{: .output}

#### Mac OS X

The default shell in all versions of Mac OS X is Bash, so no need to install anything. 
You access Bash from the Terminal (found in `/Applications/Utilities`). 

For the `make` command and a C++ compiler, you'll need the XCode command line tools. Run the
command `xcode-select --install`. 

To check if your installation is correct, open a Terminal window and type the command `make`.
If you see the following output, your installation is ok:

~~~
make: *** No targets specified and no makefile found.  Stop.
~~~
{: .output}

To check for a C++ compiler, enter the command `c++` in the Terminal window. You should see
the following output:

~~~
clang: error: no input files
~~~
{: .output}

#### Linux

The default shell is usually Bash, but if your machine is set up differently you can run it 
by opening a terminal and typing bash.

To check if you have `make` installed, open a terminal and type `make`. You should see the following
output:

~~~
make: *** No targets specified and no makefile found.  Stop.
~~~
{: .output}

To check for a C++ compiler, enter the command `c++` in the terminal window. You should see
the following output:

~~~
c++: fatal error: no input files
compilation terminated.
~~~
{: .output}

If either of these commands produce a message about the command being missing, you will need to
install the corresponding package using your systems package manager. This will depend on
on the Linux distribution you have installed. The corresponding RPM packages are:

* make
* gcc-c++

### A Text Editor

When you're writing code, it's nice to have a text editor that is optimized for writing code, with features like 
automatic color-coding of key words. The default text editor on Mac OS X and Linux is usually set to Vim, 
which is not famous for being intuitive. if you accidentally find yourself stuck in it, try typing the escape key, 
followed by `:q!` (colon, lower-case 'q', exclamation mark), then hitting Return to return to the shell.

You're welcome to use whatever editor you are comfortable with, or follow the instructions below for using `nano`.

#### Windows

[Video Tutorial](https://www.youtube.com/watch?v=9LQhwETCdwY)

The `nano` editor is a basic editor and the default that instructors use in the workshop. 
To install it, download the 
[Software Carpentry Windows installer](https://github.com/swcarpentry/windows-installer/releases/download/v0.3/SWCarpentryInstaller.exe) 
and double click on the 
file to run it. **This installer requires an active internet connection**.

Others editors that you can use are [Notepad++](http://notepad-plus-plus.org/) or 
[Sublime Text](http://www.sublimetext.com/). **Be aware that you must add 
its installation directory to your system path**. Please ask your instructor to help you do this.

#### Mac OS X

The `nano` editor is a basic editor and the default that instructors use in the workshop.  See the 
Git installation [video tutorial](https://www.youtube.com/watch?v=9LQhwETCdwY) for an example on 
how to open `nano`. It should be pre-installed.

Others editors that you can use are [Text Wrangler](http://www.barebones.com/products/textwrangler/) or 
[Sublime Text](http://www.sublimetext.com/).

### Linux

The `nano` editor is a basic editor and the default that instructors use in the workshop. It should be pre-installed.

Others editors that you can use are [Gedit](https://wiki.gnome.org/Apps/Gedit), [Kate](http://kate-editor.org/) or 
[Sublime Text](http://www.sublimetext.com/).