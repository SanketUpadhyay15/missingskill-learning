<!--Heading-->
# Introduction to Linux
* Linux is an Operating System (OS).

```bash
 An Operating System is a piece of software that lies between application software and hardware and controls the operations of computer. 
The most important program in OS is Kernel that manages the OS.
```

* GNU/Linux is considered the first version of Linux.
* In Linux everything considered as a file or direcotry.
* Multi user support system is available. N number of employees can work togather remotely. 

# History of Linux

*  In 1969, Thompson and colleague Dennis Ritchie created the UNIX operating system at Bell Telephone Laboratories.
* In 1975 Company started selling UNIX commercially.
* People were not happy with that then company developed two versions of UNIX.
  
   * The Official AT&T UNIX
   * The Free BSD UNIX 
* In 1980's many companies started developing UNIX commercially for their business. Then there was a mess created amongst them. 

     Such as:
     
     * IBM created AIX
     * SUN created SunOS
     * HP created HP-UNIX etc.


* So the God Father of Technology __Mr. Richard Stallman__ comes in Era.

   His goal was to create it open source for everyone so everyone can work together. Then he started __GNU project__ and made it.

* In 1990's, Linus Torvaldss developed kernel and shared source code online that made GNU/LINUX more creative. 

# Linux Distribution 

![Screenshot (77)](https://user-images.githubusercontent.com/88035158/127700787-9cbd4a54-a0e7-4e9e-b775-5110186a5e16.png)


* Debian
  
  * Ubuntu
     
     * Mint
  * Kali
* Redhat
  
  * Fedora
  * CentOS
* Android

```bash
   *nix -includes Linux, FreeBSD etc.
```
# Basic Linux Commands

All the linux commands are executed online by __ONWORKS LINUX TERMINAL (UBUNTU)__ . So you don't need to install UBUNTU on your WINDOWS computer/ laptop.

1 . pwd  [Print working directory]
   :-   Used to print the present working directory.

   syntax : pwd

   execution :

   ![pwd](https://user-images.githubusercontent.com/88035158/127475933-abec9de0-dd69-4149-926e-662c69ddf876.png)

   ---
2 . mkdir  [Make directory]
   :- it is used to make an empty directory.

   syntax : mkdir [directoryname]

   execution :

   ![Screenshot (65)](https://user-images.githubusercontent.com/88035158/127647043-23a317db-d354-4cf1-a0b7-702703077145.png)
   ---

3 . rm  [Remove file]
   :- it is used to remove files.

   syntax : rm [filename] 

   execution :

  ![Screenshot (68)](https://user-images.githubusercontent.com/88035158/127655073-299b7ded-f3c1-4a2e-8446-f52e456b99b3.png)

  ---

4 . rm -r
   :- it is used to remove directory.

   syntax : rm -r

   execution :

  ![Screenshot (69)](https://user-images.githubusercontent.com/88035158/127655518-7e848c53-afe0-47d8-9412-d6f475f90533.png)

 
 `


___
   ## List and its flags:-

---


5 . ls  
   :-   list information of directory and files of current directory by default.

   syntax : ls

   execution :
   ![image](https://user-images.githubusercontent.com/88035158/127476897-0694e74a-b645-4139-9a9b-3e45b0ab9d44.png)

   ---


6 . ls -l 

   :-   It is used to show the list of folder/files with thier access permission.

   syntax : ls -l

   execution :
   ![image](https://user-images.githubusercontent.com/88035158/127477368-effc536a-bc9c-4f6a-9904-801b82eacd53.png)

---

7 . ls -F 
   
   :-   it will added **/** in front of directory.

   syntax : ls -F

   execution :
   ![image](https://user-images.githubusercontent.com/88035158/127477821-46b35122-2dc1-4925-ad1b-995eed40ef72.png)
   ---
---


8 . ls -t 
   
   :-   It is used to show the file which created first at the top of the list.

   syntax : ls -t
   ![image](https://user-images.githubusercontent.com/88035158/127478125-9c952f87-8469-46b7-a8e8-3fd5ad6f22b0.png)

---


9 . ls -r
   
   :-    it shows file in reverse order.

   syntax : ls -r
   ![image](https://user-images.githubusercontent.com/88035158/127478426-fcd028d7-f146-4be4-825d-62a4d0174b99.png)


---

10 . ls -h
  
   :-    it shows the details of the file in human readable format.

   syntax : ls -h
   ![image](https://user-images.githubusercontent.com/88035158/127479241-97562541-b8a6-4aa8-9890-747d43e956ef.png)

---


## cd and its flags :-

---
11 . cd
  
   :-  cd stands for change directory. It is used to jump from one directory to another or file file to another. 

   syntax : cd [directory name] or [file name]

   execution :
   ![image](https://user-images.githubusercontent.com/88035158/127482140-dca71e5a-1740-4da5-b543-6642898a8011.png)

---
12 . cd . . 
  
   :- Used to jump on previous directory/file. 

   syntax : cd . .

   execution :
   ![image](https://user-images.githubusercontent.com/88035158/127482559-0070411f-48f4-45a0-b5b0-744fd3e0516d.png)

  ---
13 . cd - 
  
   :-  It is used to jump to home directory.
   syntax : cd -

   execution :  

---

14 . cp  
  
   :-  Used to copy file and data to one location to another location.
   
   syntax : cp sourcefilename destinationfilename

   execution : 
 ![image](https://user-images.githubusercontent.com/88035158/127484257-e77f9055-53b0-4997-9356-927bb740f52e.png)

---

15 . cp  -R
  
   :- copy one floder to another folder.
   
   syntax : cp -R

   execution : 
   ![image](https://user-images.githubusercontent.com/88035158/127484477-4b54c2d6-d20c-46e9-92ca-6e32694cd34a.png)

   ---
16 . mv
  
   :- It is used to move file.
   
   syntax : mv sourcefilename destinationfilename

   execution : 
   ![Screenshot (59)](https://user-images.githubusercontent.com/88035158/127537479-410f9771-fca7-4ee3-832c-f8b9e787d023.png)

---

17 . rm
  
   :- It will delete the file from folder/directory.
   
   syntax : rm [filename]

   execution : 
   ![Screenshot (60)](https://user-images.githubusercontent.com/88035158/127538209-331483e0-473d-497b-b52e-6bd8df561a03.png)

   ---

18 . history
  
   :- It will show all previous commands that have been used till now.
   
   syntax : history

   execution :   
   ![Screenshot (62)](https://user-images.githubusercontent.com/88035158/127660970-0349f4f6-fa68-4795-82ea-c397a7182ebd.png)


   ---

19 . exit
  
   :- It is used to leave the terminal.
   
   syntax : exit

   execution : 
   
  ![Screenshot (63)](https://user-images.githubusercontent.com/88035158/127661104-cec773cc-98a7-4b1e-9ea5-f5a9236de583.png)

   ---

20 . who
  
   :- gives the working directory name.
   
   syntax : exit

   execution :   

![Screenshot (64)](https://user-images.githubusercontent.com/88035158/127661621-e52d1b6a-8f03-4df7-9428-c21e45183873.png)
   ---

21 . whoami
  
   :- gives the name of main user of system.
   
   syntax : exit

   execution :  
   ![Screenshot (69)](https://user-images.githubusercontent.com/88035158/127663696-7e5d5a8f-529b-4531-af6b-ccbdca1fcf23.png) 

   ---

23 . less
  
   :- it shows full content of file with scroll bar .
   
   syntax : less [filename]

   execution :  
   ![Screenshot (70)](https://user-images.githubusercontent.com/88035158/127664241-1856919d-339a-4da2-beef-717556fd33d8.png) 

   ---
24 . more
  
   :- it shows fixed content of file.
   
   syntax : more [filename]

   execution :   
   ![Screenshot (71)](https://user-images.githubusercontent.com/88035158/127664432-55c7d3d4-11bf-483a-8a04-ed4faf55b771.png)

   ---
25 . echo
  
   :- it shows the message on terminal.
   
   syntax : echo [message]

   execution :  
   ![Screenshot (66)](https://user-images.githubusercontent.com/88035158/127661991-a645ce99-b972-4f24-ba99-8034d1194b3a.png) 

   ---

26 . touch
  
   :- it is used to create a empty file.
   
   syntax : touch [filename]

   execution :  
   ![Screenshot (61)](https://user-images.githubusercontent.com/88035158/127645106-cb086a92-3d37-483b-b3b4-d9dbc8c6d91f.png)
 

   ---

27 . cat
  
   :- it is used to create file with some content.
   
   syntax : cat > [filename]

   execution :  
   ![Screenshot (63)](https://user-images.githubusercontent.com/88035158/127645699-4db72114-362b-4939-9401-49dfdd5e2f78.png)
 

   ---

28 . cat >>
  
   :- it is used to wirte some more content on existing file.
   
   syntax : cat [filename]

   execution :  

![Screenshot (64)](https://user-images.githubusercontent.com/88035158/127645987-08951faf-02a0-4855-88ad-e19fd26d6beb.png)

---

29 . tail
  
   :- it shows content of the file or directory.
   
   syntax : tail [filename]

   execution :  

![Screenshot (66)](https://user-images.githubusercontent.com/88035158/127647233-e38c548a-4a41-40de-865b-7060dfec3bf2.png)

---

30 . tail -n
  
   :- it shows fixed line of content of the file or directory.
   
   syntax : tail -n [number] [filename]

   execution :  

![Screenshot (67)](https://user-images.githubusercontent.com/88035158/127647750-63f9746a-1019-4d73-8afd-73522756a1ca.png)

---



31 . man
  
   :- gives information about specific command
   
   syntax : man [commandName]

   execution : 
   ![Screenshot (62)](https://user-images.githubusercontent.com/88035158/127665904-3150fd92-4699-49d2-a347-f4043d582fff.png)

   --- 

32 . help
  
   :- gives information about all commands
   
   syntax : help

   execution : 
   ![Screenshot (65)](https://user-images.githubusercontent.com/88035158/127661821-e67991d1-75ad-4490-91c8-3b3bea3611ca.png)

 --- 

 33 . ifconfig
  
   :- gives configuration of system
   
   syntax : ifconfig

   execution : 

   ![Screenshot (67)](https://user-images.githubusercontent.com/88035158/127662244-44606f14-4f4b-48b7-b57e-2c43c6484a02.png)

 --- 

 
 34 . clear
  
   :- it will clear the terminal.
   
   syntax : clear

   execution : 
   ![Screenshot (72)](https://user-images.githubusercontent.com/88035158/127666065-19d2c4f9-daeb-402a-9447-6bcd9fd19ff4.png)

   ![Screenshot (74)](https://user-images.githubusercontent.com/88035158/127666170-5fbe7162-736c-4ae1-ae9f-58faba145e23.png)

 --- 

 # FILE SYSTEM AND DIRECTORY

 * In Linux file system is a structured collection of files.
 * That means, everthing can only stored in form of files.
 * Some of the main files which let the system work are shown below.

 ## System Files :-

 | Sr. No      | File System | Description |
| ----------- | ----------- | ---------------- |
| 1.     | /boot       |  The system kernel is located in this.
| 2.   | /bin        | It contains only binary files..
| 3. | /sbin	| It is accessable to only system admin and contain system binary data.
| 4. | /lib | It contains system library files.
| 5. | /root | This is for root users, only admin can access over it.
| 6. | /home | It is for particular user of the system.
| 7. | /var | It contains system level variables.
| 8. | /dev | It contains external device informations.
| 9. | /etc | It contains system leve configuration informations.
| 10. | /tmp | It used to storing data temporary.
| 11. | /opt | It stores user-level software and also keep track of  software.
| 12. | /usr | It hepls to find user related services and resources.




