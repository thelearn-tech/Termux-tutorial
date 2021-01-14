# Termux-tutorial
Basic tutorial of Termux


![](https://i.ibb.co/99VXPwT/Termux.jpg)
**1**) ***What is Termux***

**Termux** in a nut shell is a pretty advance **Linux** emulator
 for Android.

Download [**Termux**](https://play.google.com/store/apps/details?id=com.termux)

**2**)***USAGE***

with Termux you can learn command line,Linux and make your 
own script and make your own program.

**3**) ***How to use***


***In built Command's***

a) **ifconfig**  to show ip address

b) **cd**  to change directory


*Example* you are in **home** directory
Which Is **/data/data/com.termux/files/home** and
 you want want to go to **host** directory 


***cd host***


![](https://raw.githubusercontent.com/thelearn-tech/Termux-tutorial/main/IMG_20210114_122340.jpg)


C) **cd ..**  to return to previous directory


D) **mv**  to move file to different directory



**Example** you want to move **httpd.conf** file to host 
directory 

That is **mv filename directoryname**
Or **mv filename path** 

Command is ***mv httpd.conf host***
Or **mv httpd.conf /data/data/com.termux/files/home/host**

Here **httpd.conf** and is **file name** and **host** is **directory name**.

![](https://raw.githubusercontent.com/thelearn-tech/Termux-tutorial/main/IMG_20210114_123702.jpg)




E) **cp**  to copy file or folder to a different name/renameing a file or folder

*Example* ***cp httpd.conf httpd.conf2***

Here we are copying **httpd.conf** to **httpd.conf2** , contains 
Will be remain same as **httpd.conf** but file name has change to **httpd.conf2**
Basically renaming a file.
**Note** source file will remain unchanged.


**cp filename directory**  to copy a file to a different directory

That is **cp httpd.conf host** 
Or

**cp httpd.conf /data/data/com.termux/files/home/host**

In **cp filename directory** we are copying 
For example **httpd.conf** to **host** directory
That we create a new file in **host** directory
 called **httpd.conf** which has same contains as **httpd.conf** which is in home directory


**touch** to create new file

*Example* **touch host** will create a empty file called **host**


**cat**  to print file contains

*Example* **cat host** will show content of **host** file.


**4**)***short cuts***

You can go to ***usr*** directory by typing **cd $PREFIX**

When you are moving a file to **home** directory type **mv filename $HOME**
Or **cp filename $HOME**

type **cd** in any directory ,and you will return to **home** 
director which is ***/data/data/com.termux/files/home*** 

