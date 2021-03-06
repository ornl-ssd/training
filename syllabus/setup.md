---
layout: page
title: Setup Instructions
---
## Python

[Python](https://python.org) is a popular language for research computing, and great for general-purpose programming as well. 
Installing all of its research packages individually can be a bit difficult, so we recommend 
[Anaconda](https://www.continuum.io/anaconda), 
an all-in-one installer. If you already have Python installed, *please install Anaconda anyway*. Anaconda
can be used alongside any other versions of Python. *Please also make sure you install Python version 
3.x (e.g., 3.5 is fine)*.

We will teach Python using the Jupyter notebook (also known as IPython notebook), a programming environment that runs 
in a web browser. For this to work you will need a reasonably up-to-date browser. The current versions of the Chrome, 
Safari and Firefox browsers are all supported (some older browsers, including Internet Explorer version 9 
and below, are not).

### Windows

[Video Tutorial](https://www.youtube.com/watch?v=xxQ0mzZ8UvA)

1. Open [http://continuum.io/downloads](http://continuum.io/downloads) with your web browser
2. Download the Python 3 installer for Windows
3. Install Python 3 using all of the defaults for installation *except* make sure to check 
**Make Anaconda the default Python**

### Mac OS X

[Video Tutorial](https://www.youtube.com/watch?v=TcSAln46u9U)

1. Open [http://continuum.io/downloads](http://continuum.io/downloads) with your web browser
2. Download the Python 3 installer for OS X
3. Install Python 3 using all of the defaults for installation

### Linux

1. Open [http://continuum.io/downloads](http://continuum.io/downloads) with your web browser
2. Download the Python 3 installer for Linux
3. Install Python 3 using all of the defaults for installation
4. Open a terminal window
5. Type `bash Anaconda3-` and then press tab. The name of the file you just downloaded 
   should appear.
6. Press enter. You will follow the text-only prompts. When there is a colon at the bottom of the 
   screen press the down arrow to move down through the text. Type yes and press enter to approve the 
   license. Press enter to approve the default location for the files. Type yes and press enter to 
   prepend Anaconda to your PATH (this makes the Anaconda distribution the default Python).

## The Bash Shell

Bash is a commonly-used shell that gives you the power to do simple tasks more quickly.

### Windows

[Video Tutorial](https://www.youtube.com/watch?v=339AEqk9c-8)

1. Download the Git for Windows [installer](https://git-for-windows.github.io/)
2. Run the installer and follow the steps bellow:
   1. Click on "Next" to accept the license.
   2. Click on "Next" to use the default destination location.
   3. **Select "Additional icons" and "On the Desktop"**, then click on "Next".
   4. Click on "Next" to add shortcuts to a "Git" folder.
   5. **Keep "Use Git from the Windows Command Prompt" selected** and click on "Next". 
      If you forgot to do this programs that you need for the workshop will not work properly. 
      If this happens rerun the installer and select the appropriate option.
   6. **Keep "Use the OpenSSL library selected** and click on "Next".
   7. **Keep "Checkout Windows-style, commit Unix-style line endings" selected** and click on "Next".
   8. **Select "Use Windows' default console window"** and click on "Next".
   9. Click on "Install".
   10. Click on "Finish".
3. If your "HOME" environment variable is not set (or you don't know what this is):
   1. Open command prompt (Open Start Menu then type cmd and press [Enter])
   2. Type the following line into the command prompt window exactly as shown: `setx HOME "%USERPROFILE%"`
   3. Press [Enter], you should see `SUCCESS: Specified value was saved`.
   4. Quit command prompt by typing exit then pressing [Enter]

This will provide you with both Git and Bash in the Git Bash program.

### Mac OS X

The default shell in all versions of Mac OS X is Bash, so no need to install anything. 
You access Bash from the Terminal (found in `/Applications/Utilities`). See the Git installation 
video tutorial for an example on how to open the Terminal. You may want to keep Terminal 
in your dock for this workshop.

### Linux

The default shell is usually Bash, but if your machine is set up differently you can run it 
by opening a terminal and typing bash. There is no need to install anything.

## Git

Git is a version control system that lets you track who made changes to what when and has options 
for easily updating a shared or public version of your code on [github.com](https://github.com/). You will need a 
supported web browser (current versions of Chrome, Firefox or Safari, or Internet Explorer version 9 or above).

You will need an account at [github.com](https://github.com/) for parts of the Git lesson. Basic GitHub accounts are free. 
Please create a GitHub account if you don't have one already. Also, it is worth considering what personal 
information you'd like to reveal. For example, you may want to review these 
[instructions for keeping your email address private](https://help.github.com/articles/keeping-your-email-address-private/)
provided at GitHub.

### Windows

Git should be installed on your computer as part of your Bash install (described above).

### Mac OS X

[Video Tutorial](https://www.youtube.com/watch?v=9LQhwETCdwY)

**For OS X 10.9 and higher**, install Git for Mac by downloading and running the most recent "mavericks" installer 
from [this list](http://sourceforge.net/projects/git-osx-installer/files/). After installing Git, there will 
not be anything in your `/Applications` folder, as Git is a 
command line program. **For older versions of OS X (10.5-10.8)** use the most recent available installer 
labelled "snow-leopard" available [here](http://sourceforge.net/projects/git-osx-installer/files/).

### Linux

If Git is not already available on your machine you can try to install it via your distro's package manager. 
For Debian/Ubuntu use the command `sudo apt-get install git` and for Fedora use the command `sudo yum install git`.

## A Text Editor

When you're writing code, it's nice to have a text editor that is optimized for writing code, with features like 
automatic color-coding of key words. The default text editor on Mac OS X and Linux is usually set to Vim, 
which is not famous for being intuitive. if you accidentally find yourself stuck in it, try typing the escape key, 
followed by `:q!` (colon, lower-case 'q', exclamation mark), then hitting Return to return to the shell.

You're welcome to use whatever editor you are comfortable with, or follow the instructions below for using `nano`.

### Windows

[Video Tutorial](https://www.youtube.com/watch?v=9LQhwETCdwY)

The `nano` editor is a basic editor and the default that instructors use in the workshop. 
To install it, download the 
[Software Carpentry Windows installer](https://github.com/swcarpentry/windows-installer/releases/download/v0.3/SWCarpentryInstaller.exe) 
and double click on the 
file to run it. **This installer requires an active internet connection**.

Note: This installer only works on 64-bit Windows. If you have 32-bit Windows (or you get
an error message when running the installer), you can try following the instructions in
[the 5th comment here](https://github.com/swcarpentry/windows-installer/issues/49). You will
need to restart or open a new bash shell before you can use nano.

Others editors that you can use are [Notepad++](http://notepad-plus-plus.org/) or 
[Sublime Text](http://www.sublimetext.com/). **Be aware that you must add 
its installation directory to your system path**. Please ask your instructor to help you do this.

### Mac OS X

The `nano` editor is a basic editor and the default that instructors use in the workshop.  See the 
Git installation [video tutorial](https://www.youtube.com/watch?v=9LQhwETCdwY) for an example on 
how to open `nano`. It should be pre-installed.

Others editors that you can use are [Text Wrangler](http://www.barebones.com/products/textwrangler/) or 
[Sublime Text](http://www.sublimetext.com/).

### Linux

The `nano` editor is a basic editor and the default that instructors use in the workshop. It should be pre-installed.

Others editors that you can use are [Gedit](https://wiki.gnome.org/Apps/Gedit), [Kate](http://kate-editor.org/) or 
[Sublime Text](http://www.sublimetext.com/).

## Eclipse

[Eclipse](https://eclipse.org) is a professional integrated development environment for Java, C, C++, Fortran, Python, R, and
many other languages. It offers many features not found in text editors such as Emacs, VIM, nano, etc.

### Windows

1. Make sure you have Java 8 installed. Open the `cmd` application and type `java -version`. If you get an error or
   the version is not 1.8.x then you need to install Java 8 as follows:
   1. Open the [Java download site](https://www.java.com/en/download/) in your web browser.
   2. Follow the download and installation instructions. Note that this will only install the Java Runtime Environment (JRE). 
      If you are planning to do Java development in the future, you should install the 
      [Java Development Kit (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
2. Download *either* the [Eclipse IDE for C/C++ Developers](https://www.eclipse.org/downloads/eclipse-packages/) or
   [Eclipse for Parallel Application Developers](https://www.eclipse.org/downloads/eclipse-packages/) package.
3. Unzip the archive and launch the Eclipse executable.
4. Accept the default workspace.

### Mac OS X

1. Make sure you have Java 8 installed. Open the `Terminal` application and type `java -version`. If you get an error or
   the version is not 1.8.x then you need to install Java 8 as follows:
   1. Open the [Java download site](https://www.java.com/en/download/) in your web browser.
   2. Follow the download and installation instructions. Note that this will only install the Java Runtime Environment (JRE). 
      If you are planning to do Java development in the future, you should install the 
      [Java Development Kit (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
2. Download *either* the [Eclipse IDE for C/C++ Developers](https://www.eclipse.org/downloads/eclipse-packages/) or
   [Eclipse for Parallel Application Developers](https://www.eclipse.org/downloads/eclipse-packages/) package.
3. Unzip the archive and launch the Eclipse application.
4. Accept the default workspace.

### Linux

1. Eclipse *will not* work with GCJ. To check if you have Java 8 installed, open a shell and type `java -version`. 
   If you get an error or the version is not 1.8.x then you need to install Java 8. If you wish to use OpenJDK,
   follow the instructions with your Linux distribution for updating the OpenJDK version. If you'd like to use
   Oracles Java, do the following:
   1. Open the [Java download site](https://www.java.com/en/download/) in your web browser.
   2. Follow the download and installation instructions. Note that this will only install the Java Runtime Environment (JRE). 
      If you are planning to do Java development in the future, you should install the 
      [Java Development Kit (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
2. Download *either* the [Eclipse IDE for C/C++ Developers](https://www.eclipse.org/downloads/eclipse-packages/) or
   [Eclipse for Parallel Application Developers](https://www.eclipse.org/downloads/eclipse-packages/) package.
3. Unzip the archive and launch the Eclipse executable.
4. Accept the default workspace.

## PyDev

[PyDev](http://www.pydev.org) is a complete development environment for Python programs of any size. Based on the hugely
popular Eclipse platform, PyDev provides a wide range of Python-specific tools, in addition to the development tools 
already integrated with Eclipse.

This section assems you've already installed [Eclipse](#eclipse). If you haven't install Eclipse, please do this first.

1. Launch Eclipse
2. From the **Help** menu, choose **Eclipse Marketplace...**.
3. In the **Find** box, enter "PyDev" (case doesn't matter) and click on **Go**.
4. From the PyDev entry, click on **Install** and follow the prompts. 
5. Restart when asked.

## C++ Development Tools

### Windows

1. Download Git for Windows SDK. There are two installers, one for 32-bit Windows and one for 64-bit Windows. Use the 64-bit version only if 
you have 64-bit Windows installed. If unsure, choose the 32-bit version.
	* 32-bit installer [git-sdk-installer-1.0.6-32.7z.exe](https://github.com/git-for-windows/build-extra/releases/download/git-sdk-1.0.6/git-sdk-installer-1.0.6-32.7z.exe)
	* 64-bit installer [git-sdk-installer-1.0.6-64.7z.exe](https://github.com/git-for-windows/build-extra/releases/download/git-sdk-1.0.6/git-sdk-installer-1.0.6-64.7z.exe)
2. Run the installer. Installation will proceed automatically.
3. The installation will take some time to compelete. 

You should have a "Git SDK" icon installed on your desktop at the end of the installation. This will provide you with a Bash shell, 
the `make` command, and a C++ compiler.

### Mac OS X

The default shell in all versions of Mac OS X is Bash, so no need to install anything. 
You access Bash from the Terminal (found in `/Applications/Utilities`). 

For the `make` command and a C++ compiler, you'll need the XCode command line tools. Run the
command `xcode-select --install`. 

### Linux

The default shell is usually Bash, but if your machine is set up differently you can run it 
by opening a terminal and typing `bash`.

Use the test process [below](#testing-the-installation) to see if you have `make` and the C++ 
compiler installed. If the test fails, you will need to
install the corresponding packages using your systems package manager. This will depend on
on the Linux distribution you have installed. The corresponding RPM packages are:

* make
* gcc-c++

### Testing the Installation

Once you have completed the installation of these packages, do the following to test the setup:

1. Download [setup-test.zip][zip-file].

2. Move `setup-test.zip` into a directory which you can access via your bash shell.

3. Open a Bash shell window ("Git Bash" on Windows).

4. Navigate to the directory where you downloaded the file.

5. Unpack `setup-test.zip` as follows:

   ~~~
   $ unzip setup-test.zip
   ~~~
   {: .source}

6. On Windows, open a "Git SDK" bash shell.

7. Change into the `setup-test` directory and run `make`:

   ~~~
   $ cd setup-test
   $ make
   ~~~
   {: .source}
   
   If you see the output `Hello world!` your installation is correctly configured.

[zip-file]: {{ site.github.url }}/files/setup-test.zip
