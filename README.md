[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vaSkB7zM)
# CECS 326 Reading Assignment: Processes and Threads

### Assignment Description
Answer the following questions from the chapter 2 reading from your text book. Be complete with your answers. You may work on these questions with one or two other partners, but *all* students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. Assume that you are trying to download a large 2-GB file from the Internet. The file is available from a set of mirror servers, each of which can deliver a subset of the file’s bytes; assume that a given request specifies the starting and ending bytes of the file. Explain how you might use threads to improve the download time.
   
2. What is the biggest advantage of implementing threads in user space? What is the biggest disadvantage?
   
3. Does Peterson’s solution to the mutual-exclusion problem shown in Fig. 2-24 of MOS4e work when process scheduling is preemptive? How about when it is nonpreemptive?
   
4. The producer-consumer problem can be extended to a system with multiple producers and consumers that write (or read) to (from) one shared buffer. Assume that each producer and consumer runs in its own thread. Will the solution presented in Fig. 2-28 of MOS4e, using semaphores, work for this system?
   
5. How could an operating system that can disable interrupts implement semaphores?

6. A fast-food restaurant has four kinds of employees:
    (a) order takers, who take customers’ orders; 
    (b) cooks, who prepare the food;
    (c) packaging specialists, who stuff the food into bags; and
    (d) cashiers, who give the bags to customers and take their money.
    
    Each employee can be regarded as a communicating sequential process. What form of interprocess communication do they use? Relate this model to processes in UNIX.

7. Five jobs are waiting to be run. Their expected run times are 9, 6, 3, 5, and x. In what order should they be run to minimize average response time? (Your answer will depend on x).

8. The aging algorithm with a = 1/2 is being used to predict run times. The previous four runs, from oldest to most recent, are 40, 20, 40, and 15 msec. What is the prediction of the next time? Explain.

9. In the dining philosophers problem, let the following protocol be used: An even-numbered philosopher always picks up his left fork before picking up his right fork; an odd-numbered philosopher always picks up his right fork before picking up his left fork. Will this protocol guarantee deadlock-free operation? Why or why not?

10. The readers and writers problem can be formulated in several ways with regard to which category of processes can be started when. Carefully describe three different variations of the problem, each one favoring (or not favoring) some category of processes. For each variation, specify what happens when a reader or a writer becomes ready to access the database, and what happens when a process is finished.

### Deliverables
Commit the answers to the questions in a readable file to your git repository by the due date and time indicated with your repository. Approved file submission formats are: .txt, .md, .pdf. .html (renderable) or anything that is web-readable on Github. Other formats will only be accepted with explicit approval.
