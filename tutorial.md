# Week 1 Tutorial Lab: How to Setup your CSE15L Account & Environment

## 1. Setting Up Your CSE15L Account

To being setting up your account, head to the link below:

[Link]https://sdacs.ucsd.edu/~icc/index.php

First, lookup your account through inputting your UCSD username and student ID, or alternatively your last name and student ID.
If your information is correct, you should then be able to find your username for the class that starts with *cs15lwi23*.

Clicking on your username should bring you to a page where you can then choose to change your password. The process of changing your process
is extremely specific so be careful and make sure to abide by every password requirement (length, symbols, numbers, etc).

## 2. Installing Visual Studio Code

Now it's time to install Visual Studio Code.

[Link]https://code.visualstudio.com/

Head to the link and then follow all the appropriate download instructions for your specific computer. After installation,
open up VS Code and hopefully something similar to this will appear.

![VS code screenshot](https://user-images.githubusercontent.com/122496012/211947536-76d201b7-c97b-453d-b96e-103a34f1bb6a.PNG)

Yours will most likely not look the same (mine, didn't as I'm on windows). But as long as it is similarily enough, you can move on to installing Git.

## 3. Installing Git

This is a windows specific step, if your on Mac you do not need to install Git as Mac already has a similar option built in.

[Link]https://gitforwindows.org/

Follow the link and install Git onto your computer.

After installation, head over to VS Code to follow the next steps.

## 4. Setting Up Git Bash on VS Code

First on VS Code we need to open the terminal. You can do this through inputting **Ctrl + '** or go to **Terminal** on the top and then **New Terminal**.

AFter openning the terminal input **Ctrl + Shift + P** to open the command palette. Type **Select Default Profile** and then select *Git Bash* from the options 
available.

Then by the terminal window, press on the **+** button, and then select *bash* from the options.

## 5. Connecting Remotely

In the terminal input, 
> $ ssh cs15lwi23zz@ieng6.ucsd.edu

Were the **zz** should be replaced by the correct parts of your own CSE 15L username.
After doing so you will most likely see a message similar to 
> ⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 

Say *yes* and then enter your password when prompted. Whatever you type will not show up so make sure you type it correctly and then press enter
after.

![ssh](https://user-images.githubusercontent.com/122496012/211947665-f696bb3b-e332-4520-984e-7609eaafe26f.PNG)

Hopefully something similar to this should be appear which means now your terminal should be connected to the CSE servers!

## 6. Enter Some Commands

Finally, enter some commands into your terminal.

![Commands](https://user-images.githubusercontent.com/122496012/211947720-46c844ab-7e6f-4ff2-9709-7c850eaeb205.PNG)

Just type any in and see what pops up. Your screen should then look pretty similar to this, obviously depending on the commands you chose.

![image](https://user-images.githubusercontent.com/122496012/211947777-bce97802-408d-4cb5-b9b6-6bde5903aa64.png)

**And finally you are done :D**
