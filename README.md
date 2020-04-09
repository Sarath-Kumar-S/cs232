<a name="Task(1-9)"></a>Task(1-9)

(t1)  Linux commands

(t2) Scripting Task
        Download KTU S1 results of your batch.
        Convert to .txt file: may be pdftotext -layout useful
        Separate results of S4C only. grep command may be useful. Don't edit the files directly.
        Compute sgpa for students who passed all subjects, for the rest count number failed subjects as n and display it as -n.
        Show result with name and register number.
        Similarly do for S2.
        Compute cgpa.
        Sort the result.

        grade and grade points
        O,A+,A,B+,B,C,P,F,FE,I
        10,9,8.5,8,7,6,5,0,0,0
  
(t3) Networking tasks
        Set up n/w with ifconfig, route, /etc/resolv.conf

(t4) ssh, rsync, scp etc.

(t5) ftp usage:
        Server: Public 14.139.189.217, LAN 192.168.0.30

        Refer and read ftp commands before usage (man ftp)

        username and password will be provided

        if any trouble with ftp, try sftp.


(t6) Linux installation:

(t7) Setting up http and ftp servers

(t8) Further tasks
        1. Package management
        2. perl
        3. LAMP stack
        4. Kernel compilation


(t9) Create own web page at our server.


<a name="Syllabus Experiment(s4-s9)"></a>Syllabus Experiment(s4-s9)

4.  Shell Programming :  Write shell script to show various system configuration like
        Currently logged user and his login name 
        Your current shell 
        Your home directory 
        Your operating system type 
        Your current path setting 
        Your current working directory 
        Number of users currently logged in    

5.  Write shell script to show various system configurations like

        your OS and version, release number, kernel version 
        all available shells 
        computer CPU information like processor type, speed etc 
        memory information 
        hard disk information like size of hard-disk, cache memory, model etc 
        File system (Mounted)        

6. Write a shell script to implement a menu driven calculator with following functions 
       1.  Addition 
       2.  Subtraction 
       3.  Multiplication 
       4.  Division 
       5.  Modulus

7.  Write a script called addnames that is to be called as follows                
            ./addnames ulist username 
  
        Here ulist is the name of the file that contains list of user names and username is a particular student's username. The script         should
          check that the correct number of arguments was received and print a message, in case the number of arguments is incorrect 
          check whether the ulist file exists and print an error message if it does not 
          check  whether  the  username  already  exists  in  the  file.  If  the  username  exists,  print  a message stating that the            name already exists. Otherwise, add the username to the end of the list.  

8.  Version Control System setup and usage using GIT. Try the following features.
          Creating a repository 
          Checking out a repository 
          Adding content to the repository 
          Committing the data to a repository 
          Updating the local copy 
          Comparing different revisions 
          Revert 
          Conflicts and a conflict Resolution 

9.  Shell script which starts on system boot up and kills every process which uses more than a specified amount of memory or CPU. 
