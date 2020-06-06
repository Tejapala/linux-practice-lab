# linux-practice-lab
Name: P.Tejapala
Reg No.: 17MIS1082

Question 1 : To use SL command
code:
sudo apt-get install sl      #command to install
sl -v 				    #to check version
sl				         #to run

Question 2: To use commands rev and factor

Additional Question:
Write a C program to implement Simple reader-writer algorithm using shared memory segment with semaphore.

Explanation

Step 1 − Create pipe1 for the parent process to write and the child process to read. 
Step 2 − Create pipe2 for the child process to write and the parent process to read. 
Step 3 − Close the unwanted ends of the pipe from the parent and child side.
Step 4 − Parent process to write a message and child process to read and display on the screen. 
Step 5 − Child process to write a message and parent process to read and display on the screen

Hot question:
Write a bash shell script to monitor the health of your system. Let the details be stored and archived in any folder of your choice

Explanation:

the vmstat 1200 – monitors every 24 hours and puts the data into the vmstat1.data

grep “swap”- the swap should always be zero if its not then some process has consumed massive memory. That will be monitored in this line

grep “r”- the running queue is constantly above process 1 it indicates the system is slow and some process is waiting to be executed. That will be monitored here.

Grep “cpu”- it indicates the cpu usage of the system. If the cpu usage is more it will be monitored and will alert in this line.
