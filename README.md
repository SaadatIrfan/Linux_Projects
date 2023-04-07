# A Pragmatic Approach To Linux 
-----------------------------------------------------------------------------------------------------------------------------------
## Fundamentals of Linux

### Concepts:

![image](https://user-images.githubusercontent.com/116474264/230573316-8b1eeec2-518f-4585-b20e-2d360589b02d.png)

• The Root is the central command or the father of all partitions,The hierarchy runs as per the below mentioned flowchart. 

![image](https://user-images.githubusercontent.com/116474264/230582818-fa42beb5-8f1b-4906-888e-9e1cc98eacc0.png)

#### Understanding Absolute vs Relative path with a example :
Example : Suppose a user has to reach a test directory is stored in the location **cd /opt/test**

• Absolute path  starts with root directory(/) and provides full and direct path to destination in one go. 
  So to reach test directory using absolute path the  path cd /opt/test is typed as a whole. 
  
• Relative path is to reach the destination test directory in steps by hopping indiviudally onto each directory
  and subdirectory pointing to the location .
  That is to reach testfile: 
  First opt directory is entered using **cd opt**.
  Secondly test directory is entered using **cd test** to access it.


#### Directories in Red Hat Linux :



1) Boot directory : It is the main directory in the OS, it contains contains imp files such as kernel file, 
   that are ignited by boot loader(grub) that loads operating system inside the memory/ram.(kernel=engine, boatloader=key)


2)  Dev directory : contains device drivers files

3)  etc : service configuration files apache,nginx

4)  bin : contains all user containing commands e.g ls,pwd,mkdir these are files actually.

5)  sbin :superbin directory
svin vs bin ???

6)  Lost & found: deleted files when recovered are found here .

7)  usr : softwares and applications are contained here.

8)  lib : .so (shed )files

9)  var : system activity log file is created which is stored In var.Like evernt viewer in windows

10) opt: optional directory where 3rd party softwares are kept.



•

• 
• 
• 
• 
• 
• 
• 

### Commands :  

