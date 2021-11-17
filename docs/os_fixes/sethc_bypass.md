Sticky Keys Documentation

1.	Plug in the windows 10 installation media 
2.	Press F12 to go to the bios screen and then select the disk from the boot menu 
3.	After it loads, click “next” and then “repair your computer”
4.	Select Troubleshoot and then Command Prompt. 
5.	Find your operating systems drive. In most cases you do 
 c: ''' 
6.	Navigate to system 32 
``` cd Windows\system32 ```
7.	Rename sethc.exe to something else, like sethc.bak
``` Ren sethc.exe sethc.bak ```
8.	We have to copy cmd.exe to sethc.exe
``` Copy cmd.exe sethc.exe ```
9.	Close the window and proceed to continue “Exit and continue to Windows 10”
10.	 Once at the Windows login screen, quickly spam the [Shift] many times
11.	The command prompt will appear and type 
``` Net user administrator ```
12.	Check if the user is active 
13.	If the user is not active run:
``` net user administrator /active:yes``` 
14.	To change the password run:
``` Net user administrator [password] ```
Replacing[password] with the password you would like to use. 
15.	You are good to go in, signing in as .\administartor with the password you just set.


After you complete this you have to remove the sticky keys!
1.	Plug in the windows 10 installation media 
2.	Press F12 to go to the bios screen and then select the disk from the boot menu 
3.	After it loads, click “next” and then “repair your computer”
4.	Select Troubleshoot and then Command Prompt. 
5.	Find your operating systems drive. In most cases you do 
c:
6.	Navigate to system 32 
``` cd Windows\system32 ```
7.	Delete sethc.exe file by running:
 ``` Del sethc.exe ```
8.	Rename sethc.bak to sethc.exe
``` Ren sethc.bak sethc.exe ```



