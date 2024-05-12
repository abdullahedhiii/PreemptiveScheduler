Preemptive Scheduler 🔄⏱️🔝
This project is a 4th-semester Operating System course project implemented in C++. It consists of a Preemptive Scheduler that incorporates three scheduling algorithms: Round Robin, Shortest Remaining Time First (SRTF), and Priority Scheduling.

Project Structure 📁
The project is structured into several header files along with their corresponding source files. Here is an overview of the main files and directories:

include: Contains header files
src: Contains source files
Makefile: Used for compilation

Compilation 🛠️
To compile the project, use the provided Makefile.

Scheduling Algorithms 📊

Round Robin 🔄
Round Robin is a preemptive scheduling algorithm where each process is assigned a fixed time unit (time quantum) and is scheduled in a circular queue.

Shortest Remaining Time First (SRTF) ⏱️
SRTF is a preemptive scheduling algorithm where the process with the shortest remaining burst time is given priority. It ensures that shorter jobs are executed first.

Priority Scheduling 🔝
Priority Scheduling is a preemptive scheduling algorithm where each process is assigned a priority. The process with the highest priority is executed first.
