**LINUX Assignment 1**

  

## **How to make a directory**

  

### **:- mkdir -** 

Definition - mkdir command is used for creating a directory.

   - Example: mkdir vats

\- Describe the command:

   - Example: mkdir: It is used to create a directory

   -            : vats: it is the name of folder

\- Output(Output content to be pasted along with screenshot)

  

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ mkdir vats

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ ll -ld vats

drwxrwxr-x 2 aman aman 4096 Dec 14 10:22 vats/

  

  

![](https://lh7-us.googleusercontent.com/rnN0L0AkaL-bCaZpjNHLIe0C07eRE6lutd9ekNV8dOOAFpv3snF4s4SRz7uGvxUBEZEzgI57gzN8n7Oua3Qq-OAowFztFEwAY0nOLvMuCFeq8UdaVMHP-i_oQBXMhxd2EkMCc2Wdqte26FZeGGdIkj8)

  

  

  

  

## **Remove a directory**

  

### **:- rmdir -**

Definition - rmdir is a command in Linux used to remove empty directories.

   - Example: rmdir aman

\- Describe the command:

   - Example: rmdir: rmdir is a command in Linux used to remove empty directories.

   -            : aman: it is the name of folder

\- Output(Output content to be pasted along with screenshot)

  

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ rmdir aman

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ ll -ld aman

ls: cannot access 'aman': No such file or directory

  

![](https://lh7-us.googleusercontent.com/Gb9IpB0FxrkztpvEDaI9MTpjbm8Hhr1rMS59scGGBTLHCwGghzg89ypBm3f8IzZy02PMDCbNKnz4B93w8P1jrg8jmyzNRhtBkCjxx11nJ0zWpF5Gp_uF6zxcMKFrpGnrulId297Cd0ATv57Cey29Zy0)

  

  

  

  

## **Make a copy of a file**

  

### **:-cp -** 

Definition - The cp command in Linux is used to copy files or directories from a source location to a destination location.

  

   - Example: cp a.txt aa\_copy.txt

\- Describe the command:

   - cp: The cp command in Linux is used to copy files or directories from a source location to a destination location.

 -            a.txt : it is the name of the file.

 -            aa\_copy.txt : it is the name of another file.

  

  

\- Output(Output content to be pasted along with screenshot)

  

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ cd vats

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/vats$ touch a.txt

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/vats$ ls

a.txt

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/vats$ cp a.txt aa\_copy.txt

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/vats$ ls

aa\_copy.txt  a.txt

  

![](https://lh7-us.googleusercontent.com/IyDmKYpPfhWdHlc-sdu7t2adCw2HJj2UcBdLA1EgSwrK50VsZTtylhA8m_wEJa2twpx05J5w4adAyO_n_lH2XDTG_bKHh90NFZAr1d5PMWcvkXZZav4aAL8v2IlzbmX3lIuSx9R_64NylqIjQhSZpz8)

  

  

  

  

  

  

## **Move or rename a file**

  

### **:-mv -** 

Definition - The mv command in Linux is used to move or rename files and directories.

  

   - Example: mv aa\_copy.txt /home/aman/a

\- Describe the command:

   -  mv : The mv command in Linux is used to move or rename files and directories.

\- aa\_copy.txt : file name 

\-  /home/aman/a : Address where we want to move this file.  

  

\- Output(Output content to be pasted along with screenshot)

  

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ cd vats

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/vats$ mv aa\_copy.txt /home/aman/a

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/vats$ cd ..

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ cd a

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/a$ ls

aa\_copy.txt

  

  

  

![](https://lh7-us.googleusercontent.com/GmyjghQ3kJUd3vW9X3fLn3SuaEHuyOnynHwyasBjZkEes7FcdSiLEzbY6DBSOLiAEYSel42sZmw8gi4RBzV6Q6hcxcRMmHzAtpLcPIkM_oI4GDhurasYJTeJsQdbXGzvDxFZTZ1ShEGNryX__G6uDyw)

  

  

## **Create an empty file**

  

### **:-touch -**

Definition - The touch command in Linux is used to create empty files or update the timestamps of existing files without modifying their content.

  

\- Example:touch av.txt

\- Describe the command:

   - touch : The touch command in Linux is used to create empty files or update the timestamps of existing files without modifying their content.

   -            : av.txt: it is the name of a new empty file.

  

  

\- Output(Output content to be pasted along with screenshot)

  

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/a$ touch av.txt

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/a$ ls

aa\_copy.txt  av.txt

  

![](https://lh7-us.googleusercontent.com/c6kSazU-KVgMzA1T-5BG1D80uHxgwtrXR-HJQOOCRODeJOe708HXhke7im8tSJWSBC4EPOJX3pi2uj3sGqgLx8t3Yvnn-bf65mIrV76nH4zAvOy8GGSUaTmyn1VAp3SZbMIBF5v99x0s9I9vGZqAwnI)

  

  

## **Remove multiple files with a single command**

  

### **:-rm -**

Definition - The rm command in Linux, when used with multiple filenames, allows the simultaneous removal or deletion of those specified files with a single command.

  

   - Example: rm b.txt c.txt d.txt

\- Describe the command:

   - Example: rm : The rm command in Linux, when used with multiple filenames, allows the simultaneous removal or deletion of those specified files with a single command.

   -            : b.txt,c.txt,d.txt: it is the name of files

\- Output(Output content to be pasted along with screenshot)

  

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/a$ ls

a.txt  b.txt  c.txt  d.txt

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/a$ rm b.txt c.txt d.txt

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/a$ ls

a.txt

  

![](https://lh7-us.googleusercontent.com/PT5RVNZVodaqHLa5roVY1_SaqUQqfQ6U2uaIgwESLjLOJDvTmkzBcJbJqWuX0NZG4boRFqIDC5w1D58HknnsahOSDrJtPaZ_V_Fo2JiGJcu13mO4-QHptYBDSIFvKiRr_rQxFIMFhr8j7w71sMg3JIM)

  

  

## **Remove content from the folder without removing folder**

  

### **:-rm -r  -**

Definition - The rm - r  command in Linux, when used with the appropriate directory path, recursively removes all files and subdirectories within the specified folder without removing the folder itself.

\- Example: rm -r a/\*

\- Describe the command:

   - Example: rm - r : The rm - r  command in Linux, when used with the appropriate directory path, recursively removes all files and subdirectories within the specified folder without removing the folder itself.

   -            : a: it is the name of folder

\- Output(Output content to be pasted along with screenshot)

  

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/a$ ls

a.txt  c.txt  d.txt  m.txt

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/a$ cd ..

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ rm -r a/\*

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ cd a

aman@aman-Mi-NoteBook-Horizon-Edition-14:~/a$ ls

  

![](https://lh7-us.googleusercontent.com/0z15THv6Hp093K1mti1JTgwnSRpI4jlImER5q_gcBVILJ7p7QWmyQMjPfb28QoKIr5sU5hqik-viV6NnB9itgIlOP9LL4UMKFES_tPDp1v6vjEpjfaypVm2-MBMOcP6Piw-n7X5DSWS5W8SoFtRiQY8)

  

  

## **Create multiple folder(a-z) with a single command**

  

### **:-mkdir -**

  

Definition - The mkdir command in Linux, when used with brace expansion {a . . z}, creates multiple folders from "a" to "z" with a single command.

  

   - Example: mkdir {a..z}

\- Describe the command:

   - Example: mkdir: The mkdir command in Linux, when used with brace expansion {a..z}, creates multiple folders from "a" to "z" with a single command.

\-   :{a..z}: it is a folders from a to z.

  

\- Output(Output content to be pasted along with screenshot)

  

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ mkdir {a..z}

aman@aman-Mi-NoteBook-Horizon-Edition-14:~$ ll -ld {a..z}

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 a/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 b/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 c/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 d/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 e/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 f/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 g/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 h/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 i/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 j/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 k/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 l/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 m/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 n/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 o/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 p/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 q/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 r/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 s/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 t/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 u/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 v/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 w/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 x/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 y/

drwxrwxr-x 2 aman aman 4096 Dec 14 11:38 z/

  

  

  

![](https://lh7-us.googleusercontent.com/a112k0iIVe0K3Wm6iXM-fg32F5cY_FxFiIvPytHxeDreiWGv_1jH_fnuuBh_bTT4_kdB3Eny6E-6KTpejRJ4zHMeOu6LcKKs_tukpUWQYSZmiNoVg1rrk9wm_-_g4WucqRfcG3oIjm-mCcj2ou3oqv8)
