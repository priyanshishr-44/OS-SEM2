# OS-SEM2

CPU Scheduling Algorithms Implementation
📌 Project Overview
This project is part of the Operating System Lab (ENCA252) for the BCA (AI & DS) program. It demonstrates the implementation and performance analysis of two fundamental CPU scheduling algorithms:

First Come First Serve (FCFS)

Shortest Job First (SJF) - Non-Preemptive

The goal is to understand how an Operating System manages processes and calculates key metrics like Completion Time, Turnaround Time, and Waiting Time.

🚀 Features
Process Modeling: Uses a Python Process class to store PID, Arrival Time, and Burst Time.

Dynamic Input: Accepts user-defined data for 4-5 processes.

Automated Calculations: Computes CT, TAT, and WT for every process.

Comparison: Provides an average performance analysis between FCFS and SJF.

🛠️ Technology Used
Language: Python 3.x

Concepts: Object-Oriented Programming (Classes), List Manipulation, Sorting Algorithms.

📊 Performance Analysis
In this implementation, we observed that:

FCFS is simple to implement but can lead to the "Convoy Effect" where short processes wait for a long process to finish.

SJF is more efficient as it minimizes the Average Waiting Time by prioritizing shorter tasks.
