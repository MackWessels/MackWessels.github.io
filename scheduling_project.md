[Back to Portfolio](./)

Process Scheduling Algorithm Implementation
===============

-   **Class: Operating Systems** 
-   **Grade: A** 
-   **Language(s): C** 
-   **Source Code Repository:** [features/mastering-markdown](https://github.com/MackWessels/Process-Scheduling-Algorithm/tree/main/posix)  
    (Please [email me](mailto:mwessels@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This project involves the implementation of several process scheduling algorithms, including First-Come, First-Served (FCFS), Shortest Job First (SJF), Priority Scheduling, Round-Robin (RR), and Priority with Round-Robin scheduling. Each task is assigned a priority and CPU burst, and the scheduler selects tasks based on the algorithm being executed. The project demonstrates proficiency in core scheduling techniques used in operating systems and managing task execution in a simulated CPU environment.

## How to compile and run the program

How to compile (if applicable) and run the project.

Clone the repository:

```bash
git clone [https://github.com/MackWessels/Process-Scheduling-Algorithm/tree/main/posix]
```

Navigate to the project directory:
```bash
cd ./posix/
```

Compile and run the program based on the chosen scheduling algorithm:
For FCFS:
```bash
make fcfs
./fcfs schedule.txt
```

For SJF:
```bash
make sjf
./sjf schedule.txt
```
Repeat the above commands for other algorithms like priority and round-robin scheduling.

## UI Design

Upon running the program, it processes tasks based on the selected algorithm and outputs the order of task execution along with the remaining CPU burst after each execution.

In this screenshot, the terminal output shows the successful compilation and execution of a process scheduling program using multiple algorithms (FCFS, SJF, RR, Priority with RR). The user first executes the command make all, which compiles all necessary files for different scheduling algorithms using gcc. After compilation, the program is run with the fcfs (First-Come, First-Served) algorithm on the input task schedule (schedule.txt). The output displays each task being executed, followed by performance metrics such as average turnaround time, waiting time, and response time.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

In this project, the process scheduler reads tasks from the schedule.txt file, which defines tasks in the format [task name], [priority], [CPU burst]. An example schedule includes the following tasks:

```bash
T1, 4, 20
T2, 3, 25
T3, 3, 25
T4, 5, 15
T5, 5, 20
T6, 1, 10
T7, 3, 30
T8, 10, 25
```
These tasks are then scheduled using various algorithms such as FCFS, SJF, and Priority with Round-Robin, as demonstrated in the screenshot. After running the scheduler, the output shows the execution order and important performance metrics like average turnaround time, waiting time, and response time, providing insights into the efficiency of each algorithm when handling the given task set.

## 3. Additional Considerations

This project focuses on core scheduling concepts and demonstrates effective use of linked lists for task management, alongside creating a modular design to easily swap between different scheduling algorithms.

[Back to Portfolio](./)