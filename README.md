# Operating System Project

# CPU Scheduling Algorithms

## Functionalities

- 5 Algorithms are implemented.
- Each process can have different number of CPU Burst Time and I/O Burst Time.
- Gantt Chart and Timeline Chart for the given Schedule.
- Animation of the Time Log.
- Comparison between all the algorithms wrt Average Completion Time, Turn Around Time, Waiting Time and Response Time.

### Different Criteria and Algorithms

- The first process arrived in the ready queue is processed first.
  - **First Come First Serve (FCFS)**
    > Non-Preemptive
- The shortest job in the ready queue is processed first.
  - **Shortest Job First (SJF)**
    > Non-Preemptive
- The longest job in the ready queue is processed first.
- **Shortest Remaining Time First (SRTF)**
  > Preemptive
- The execution of the process can be stopped after certain amount of time.
  - **Longest Job First (LJF)**
    > Non-Preemptive
- The highest priority job in the ready queue is processed first.
  - **Round Robin (RR)**
    > Preemptive
- The job with the highest response ratio in the ready queue is processed first.

**Non-Preemptive:**
Once a job enters the Running Queue, it will only leave when its required CPU Burst Time is completed or it requires an I/O Job.

### Technologies Used

- HTML5
- CSS3
- Vanilla JS(ES6)
- Google Charts
