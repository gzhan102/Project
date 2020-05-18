# This is demo project which shows how the simple OS works.
This project contains the following components:
1. CPU
2. IODevice which contains a IO Queue.
3. Main memory which contains a Ready Queue.
4. Secondary memory which contains a Job Queue.
5. Process Control Block which contains ProcessState, AccountingInfo, CPUState. Since this is a simple demo, it doesn't contain all the information.
6. Process
7. ProcessType can be divided to IOBound and CPUBound.
8. ProcessState has NEW, READY, RUNNING, WAITING, TERMINATED states.
9. Long-term scheduler.
10. Short-term scheduler.
11. Custom Queue structure.

When you download this Java Application, just run OperatingSystemApplication which is in the package app.
You can update other compotents if you want, and you can contact me to discuss the details about OS.
LinkedIn: Guoyucheng Zhang (Tommy)
