# OS Resource Management Simulator

Interactive browser-based educational simulator for CSCI 300 (Operating Systems).

## Features
- Resource dashboard with illustrative CPU, memory and process data.
- CPU scheduling: FCFS, non-preemptive SJF and Round Robin.
- Editable process inputs, Gantt chart, completion time (CT), turnaround time (TAT), waiting time (WT), and averages.
- Paging: FIFO and LRU with editable reference string and frame count.
- Per-request frame traces, page-hit and page-fault totals, and hit rate.

## Run locally
1. Clone or download this repository.
2. Open `index.html` in a modern browser.
3. No build step or external libraries are required.

## Assignment test data
Processes: P1 (AT 0, BT 8), P2 (AT 1, BT 4), P3 (AT 2, BT 2), P4 (AT 3, BT 6), P5 (AT 4, BT 3).

Paging reference string: `7, 0, 1, 2, 0, 3, 0, 4, 2, 3, 0, 3, 2`, using 3 frames.

## Notes
- Dashboard values are illustrative simulated values, not readings from the host computer.
- In Round Robin, arrivals at a quantum boundary enter the ready queue before the unfinished process is re-queued.
- Verify results, test the application, and add your own screenshots before submission. Make sure every group member understands and can explain the code.

Course: CSCI 300 – Operating Systems.
