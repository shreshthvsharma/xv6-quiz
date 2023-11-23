# XV Quiz (CSL 3030)

Welcome to the XV Quiz for CSL 3030 - Operating Systems!



## Instructions
- Answer the multiple-choice questions by selecting the correct option.
- For theoretical questions, provide concise and accurate explanations.
- Feel free to use this quiz for self-assessment or educational purposes.

## Multiple-Choice Questions

#### Question 1: Basics
1. What is XV6?
   
Answer : 
   - b. A Unix-like operating system


#### Question 2: Architecture
2. XV6 is based on which earlier operating system?
   
Answer : 
   - c. BSD


#### Question 3: File System
3. Which file system is used in XV6?

Answer : 
   - d. simple

#### Question 4: System Calls
4. How are system calls implemented in XV6?

Answer : 
   - b. As interrupts


#### Question 5: Processes
5. In XV6, what is the maximum number of processes that can run simultaneously?

Answer : 
   - a. 128


#### Question 6: Shell
6. What is the name of the shell used in XV6?

Answer : 
   - c. Sh


#### Question 7: Scheduling
7. How does XV6 handle process scheduling?

Answer : 
   - a. Round-robin scheduling


#### Question 8: Memory Management
8. Which memory management technique is used in XV6?

Answer : 
   - a. Paging


#### Question 9: Interrupts
9. How are interrupts handled in XV6?

Answer : 
   - b. Using hardware interrupts


#### Question 10: Multithreading
10. Does XV6 support multithreading?

Answer : 
    - b. No

#### Bonus Question:
11. Who developed XV6?

Answer : 
    - c. MIT


## Theoretical Questions

#### Question 12: Process States
12. Briefly explain the different states a process can be in within the XV6 operating system.

#### Question 13: File System Structure
13. Describe the structure of the file system in XV6. Include the key components and their roles.

#### Question 14: System Calls vs. Library Functions
14. Explain the difference between system calls and library functions in the context of XV6. Provide examples of each.

#### Question 15: Memory Paging
15. How does memory paging work in XV6? Discuss the benefits of using paging in memory management.

#### Question 16: Shell Commands
16. Name and briefly explain three essential shell commands in the XV6 operating system.

#### Question 17: Process Synchronization
17. Discuss the concept of process synchronization in XV6. Why is it essential, and what mechanisms are used to achieve it?

#### Question 18: Interrupt Handling
18. Explain the role of interrupts in the XV6 operating system. How are interrupts handled, and what is their significance in system operation?

#### Question 19: Virtual Memory
19. What is virtual memory, and how is it implemented in XV6? Discuss the advantages of using virtual memory.

#### Question 20: Boot Process
20. Outline the steps involved in the boot process of XV6. What happens from the moment the computer is powered on to when the XV6 kernel is loaded into memory?

## Answers

### ANSWER 12

Xv6 uses the following names for process states (line 2350): UNUSED, EMBRYO, SLEEPING,
RUNNABLE, RUNNING, ZOMBIE.

UNUSED: This state represents a process that has been created but is not currently in use.

EMBRYO: In this state, the process is in the process of being created but is not yet ready to run.

SLEEPING: A process in this state is waiting for some event to occur, such as the completion of I/O operations or the expiration of a timer.

RUNNABLE: A process in this state is ready to run but is not currently executing because other processes are running.

RUNNING: The process is currently being executed by the CPU.

ZOMBIE: This state represents a process that has finished executing, but its exit status is still needed by its parent process before it can be completely terminated.

### ANSWER 13 







