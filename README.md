Download Link: https://assignmentchef.com/product/solved-ucs1411-exercise-4-priority-and-round-robin
<br>
Implementation of CPU Scheduling Policies: Priority (Non-preemptive and Preemptive) and Round Robin

Develop a menu driven C program to implement the CPU Scheduling Algorithms

Priority (Non-Preemptive and Preemptive) and Round Robin

<u>Sample Learning Outcome:</u>

<ol>

 <li>Learn about the CPU Scheduling algorithms – Priority and RR.</li>

 <li>Implement the sorting algorithms necessary for scheduling and analyzing the performance using waiting time, turn around time and response time.</li>

 <li>Learn to draw the Gantt Chart <u>Best Practices:</u></li>

 <li>Algorithm design</li>

 <li>Naming convention – for file names, variables</li>

 <li>Comment usage at proper places</li>

 <li>Prompt messages during reading input and displaying output</li>

 <li>Error handling mechanisms for failures in system calls</li>

 <li>Incremental program development</li>

 <li>Modularity</li>

 <li>All possible test cases in output</li>

</ol>




<u>Algorithm:</u>

<ol>

 <li>Read the following

  <ol>

   <li>Number of processes</li>

   <li>Process IDs</li>

   <li>Arrival time for each process</li>

   <li>Burst Time for each process</li>

  </ol></li>

 <li>Design a menu with Priority and Round Robin options</li>

 <li>Upon selection of menu option apply the corresponding algorithm.</li>

 <li>Compute the Turnaround Time, Average waiting Time for each of the algorithm.</li>

 <li>Tabularize the results.</li>

 <li>Display the Gantt Chart.</li>

</ol>

<u>Sample Input &amp; Output:</u>

<h1>CPU SCHEDULING ALGORITHMS</h1>

<ol>

 <li>ROUND ROBIN</li>

 <li>PRIORITY</li>

 <li>EXIT</li>

</ol>

Enter your option: 1

ROUND ROBIN CPU SCHEDULER

Number of Processes: 5

Process ID:  P1

Arrival Time: 0

Burst Time:  4

–

–

–

–

Process ID:  P5

Arrival Time: 6

Burst Time:  3

<u>Output:</u>




Process ID   Arrival Time  Burst Time   Turnaround Time Waiting Time  Response time

P1                     0                     4                     ***                   ***                ***

***                    ***                   ***                 ***                  ***                ***

***

***

Average          ***        ***                ***




Want to Continue ( Y/N): Y

<h1>CPU SCHEDULING ALGORITHMS</h1>

<ol>

 <li>ROUND ROBIN</li>

 <li>PRIORITY</li>

 <li>EXIT</li>

</ol>

Enter your option: 2

PRIORITY CPU SCHEDULER

<ol>

 <li>Non preemptive PRIORITY</li>

 <li>Pre emptive PRIORITY</li>

</ol>

Enter your option: a

Number of Processes: 5

Process ID:  P1

Arrival Time: 0

Burst Time:  4

–

–

–

–

Process ID:  P5

Arrival Time: 6

Burst Time:  3

<u>Output:</u>




Process ID  Arrival Time   Burst Time  Turnaround Time Waiting Time Response Time

***    ***                 ***                    ***                  ***                  ***

***       ***               ***                     ***                 ***                  ***

***

***

Average              *** ***