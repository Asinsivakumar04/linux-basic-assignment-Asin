SECTION 1 – Purpose and Example for Each Command

1. pwd
    purpose : The pwd command is used to display the current working
    directory where the user is currently located in the Linux system.
    example : pwd (/home/user/documents)
2. ls
    purpose : The ls command is used to list all the files and directories present in the current directory
    example : ls (file1.txt file2.txt folder1)
3. cd
    purpose : The cd command is used to change the current directory
    from one directory to another
    example : cd Documents (Moves to the Documents directory)
4. mkdir
    Purpose : Creates a new directory.
    Example : mkdir project (Creates a folder called project)
5. rm -rf
    Purpose : Deletes files or directories forcefully and recursively.
    Example : rm -rf project (Deletes the project folder and all files inside it)
6. ps -ef
    Purpose : This command shows the list of all running processes
    in the system with detailed information.
    Example : ps -ef ( Shows process ID, user, and running programs)
7. top
    Purpose : Shows real-time system processes and CPU/memory usage.
    Example : top (Displays system performance and running processes)
8. df -h
    Purpose : Shows disk space usage in human-readable format.
    Example : df -h (Displays disk size, used space, and free space)
9. history
    Purpose : Displays previously executed commands.
    Example : history (Shows a list of past commands)
10. uptime
    Purpose : The uptime command shows how long the system has
    been running along with system load.
    Example : uptime (10:20:05 up 5 days, 3:22, 2 users)

SECTION 2 – Linux Commands for Tasks

1.Create a directory called project-files
    Answer: mkdir project-files

2.Navigate into the project-files directory
    Answer: cd project-files

3.Create a file called notes.txt using vi
    Answer: vi notes.txt

4.Display the contents of notes.txt
    Answer: cat notes.txt

5.Copy notes.txt to backup.txt
    Answer: cp notes.txt backup.txt

6.Show the first 100 lines of logs.txt
    Answer: head -n 100 logs.txt

7.Show the last 100 lines of logs.txt
    Answer: tail -n 100 logs.txt

8.Check the disk storage usage of the server
    Answer: df -h

9.Check the running processes in the system
    Answer: ps -ef

10.Delete a file called temp.txt
    Answer: rm temp.txt

SECTION 3 – Concept Questions

1.Difference between > and >> in Linux
    Answer: > overwrites the existing file content, while >> appends content to the end of the file.

2.Purpose of kill -9 command
    Answer: kill -9 forcefully terminates a process using the SIGKILL signal.
    
3.Difference between rm and rmdir
    Answer: rm deletes files or directories, while rmdir deletes only empty directories.
    
4.Information from netstat -tulpn
    Answer: Shows active network connections, listening ports, protocols (TCP/UDP), and the process using the port.
    
5.Purpose of ping command
    Answer: Used to test network connectivity between your system and another host.

SECTION 4 – Scenario Based Questions

1.Check the current working directory
    Answer: pwd
    
2.Create a directory called devops inside the home directory
    Answer: mkdir ~/devops
    
3.Check which process is using high CPU
    Answer: top
    
4.Check whether your server can connect to google.com
    Answer: ping google.com

5.View the last 50 lines of application.log
    Answer: tail -n 50 application.log
     
