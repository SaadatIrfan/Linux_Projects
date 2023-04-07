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

1) Boot directory
2)  Dev directory 
3)  etc directory
4)  bin directory
5)  sbin (superbin directory)
6)  Lost & found directory
7)  usr directory
8)  lib directory
9)  var directory
10) opt directory


### Commands :  

1. df –h >> files displayed in human readable form.
2.	pwd >>> path to the present/current file.
3.	rm –rf file (removes recursively and forcefully).
4.	command –help >>> tells flags available in any command.
5. ls –lt –reverse >> shows list in reverse order
6.	ls /proc >>shows linux kernel files
7. ls -l >>>shows contents in a list
8. mkdir creates a directory 
9. touch abc >>>creates abc file
10. man command >> shows flags or features of a particular command. 

#### Creating and managing user in linux:

1.  su - username >>switching from one user to other user
2.  useradd xyz  >>>>creates xyz user
3.	passwd xyz  >>>>>changes password

