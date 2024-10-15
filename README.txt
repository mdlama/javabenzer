Requirements for javaBenzer
===========================

javaBenzer only requires two other pieces of software

1) A web browser (for reading the Help files).

2) OpenJDK (java) version 11 or newer.

It will run under any operating system that has a current version of OpenJDK (e.g. Windows, MacOS, Linux, etc)

Installing javaBenzer
=====================

Since you're reading this, you've probably already downloaded and unpacked javaBenzer. However, if you acquired it some other way, you can get the javaBenzer software from

https://qubeshub.org/community/groups/bioquest

Once you get the zip archive containing the package, unpack it on your computer. The file contains a single folder named "javaBenzer" -- everything else is inside that folder. You can place the folder anywhere you want, but keep track of the location because you will need it later.

These days, it's hard to imagine a usable computer without a web browser, so I'm not even going to talk about that.

To see if java is installed and what version it is, open a command window ("Command Prompt" or "PowerShell" on Windows, etc.) and type "java -version". A successfil response would be something like the following:

openjdk version "11.0.11" 2021-04-20
OpenJDK Runtime Environment Microsoft-22268 (build 11.0.11+9)
OpenJDK 64-Bit Server VM Microsoft-22268 (build 11.0.11+9, mixed mode)

As long as the version is 11 or above, you ought to be fine.

If java wasn't found, you need to install it. 

Windows and Mac users will probably find it easiest to download OpenJDK from the installers made available by Microsoft at 

https://docs.microsoft.com/en-us/java/openjdk/download

Note that you want the msi or pkg file, although you could get the zip or tar.gz files and install it by hand.

You can find further directions for installing OpenJDK at

https://docs.microsoft.com/en-us/java/openjdk/install

Linux users will also find links to the packages there (rpm or deb), or you can probably use your native package manager.

Finally, you could get OpenJDK from the source 

https://openjdk.java.net/

but it's generally easier to use Microsoft's installers.

Once you've installed OpenJDK, test for the version again and go on.

Running javaBenzer
=============

The easiest way to run javaBenzer is to

1) Open a command window

2) cd into the javaBenzer folder

3) Type "java -jar javaBenzer.jar"

If your skills permit, you can create a shortcut or menu item to run javaBenzer, but it's important that you run it within the javaBenzer folder. This allows the program to find the jar file, the config file, the default save location and the help files. It will still run without them (except for the jar file), but it will be a less user-friendly experience.