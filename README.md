# CSN-232-Project-
Banker's Algorithm and Producer-Consumer Implementation using counting semaphore and mutex. The code has been documented.

Problem Statement for the project:
The concept of the producer-consumer problem was introduced in detailed in the class.
So in this project, you need to implement the famous producer consumer problem using Pthreads.
The following points should be taken care of properly for successful compilation of the project:
1. Rather than using binary semaphores for empty and full, you will be using standard
   counting semaphores and mutex lock to replace mutex binary semaphore.
2.  The programs should be thread safe.
3. Standard mutex locks can be used

Extend the above module using a multithreaded program that implements the banker’s
algorithm. The banker will grant the request only if it leaves the system in a safe state. Here
also mutex locks will be used to safe data access. A thorough analysis is to be done to
showcase the working of the model. The team will get additional credits if they improve the
model with different ideas.
