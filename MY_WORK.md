# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Abdullah Mubarak Alqaddan] |
| **Student ID** | [446050819] |
| **University Email** | [446050819]@std.psau.edu.sa |
| **GitHub Username** | [ Abdullah Alqaddan] |
| **Repository Link** | [https://github.com/AbdullahAlqaddan/OS-Assignment1-Abdullah-Alqaddan.git] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (446050819)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 446050819`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - October 9, 2026, 5 PM
**What I did**: Started working on the assignment from the PDF summary.
**Details**:
- I practiced on my own in my IDE to learn how to create and manage threads.
**Challenges**: The assignment was not visible on Blackboard, so I could not see the full instructions (for example, that I had to fork the starter repository on GitHub).
**Solution**: I stopped working until the assignment became visible, then continued.
**Time spent**: 1 hour
---
### Entry 2 - October 10, 2026, 5 PM
**What I did**: Set up my tools and GitHub.
**Details**:
- Installed Git (Apple developer tools on my Mac), Java 21 and VS Code with the Java extension
- Created my GitHub account with my university email
- Forked the starter repository, renamed it, kept it public, and cloned it in VS Code
**Challenges**: This was my first time using Git and GitHub, and I was not sure about the steps on macOS.
**Solution**: I followed the steps one by one and checked the result on GitHub.
**Time spent**: 30 minutes
---
### Entry 3 - October 10, 2026, 5 PM
**What I did**: Set my student ID.
**Details**:
- Changed studentID on line 150 to 446050819
- Committed and pushed: `Set my student ID`
**Challenges**: I was not sure how to commit and push from VS Code.
**Solution**: I used the Source Control panel: wrote a message, committed, then synced.
**Time spent**: 35 minutes
---
### Entry 4 - October 18, 2026, 10 AM
**What I did**: Added Feature 1 (Process Priority) and Feature 2 (Context Switch Counter).
**Details**:
- Added a priority field, constructor parameter and getter in the Process class
- Generated the priority with random.nextInt(10) + 1 and printed it in addProcessToQueue(); the queue stays FIFO
- Added a static int contextSwitchCount, incremented it right before currentThread.start(), and printed the total at the end (my run gave 27 context switches)
**Challenges**: (1) I was not sure which println line to edit in addProcessToQueue(). (2) I forgot to add the context switch counter the first time and noticed it when I reviewed my code. (3) I implemented the features in one session, so they ended up in one commit instead of one commit per feature, because the full instructions were not visible to me earlier.
**Solution**: (1) I searched the file for "added to ready queue" and edited that println. (2) I added the counter, the increment and the print, then re-ran the program.
**Time spent**: 2.3 hours
---
### Entry 5 - October 18, 2026, 12 PM
**What I did**: Added Feature 3 (Waiting Time Tracking) and fixed output problems.
**Details**:
- Added arrivalTime and finishTime using System.currentTimeMillis()
- Waiting time = turnaround time - burst time
- Printed the final table with all 14 processes
- Fixed Arabic-Indic digits in the table by using Locale.US in printf
**Challenges**: (1) VS Code showed "no registered task type 'Java'" when I pressed Run. (2) The table printed numbers like ١٢٠٣٨ because my Mac uses an Arabic locale.
**Solution**: (1) I made sure the Java extension was working and reopened the project folder. (2) I added Locale.US to printf so the numbers print in English digits.
**Time spent**: 45 minutes

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

## Development Log Summary

**Total time spent on assignment**: about 5 hours

**Most challenging part**: This was my first time uploading a project to GitHub so I had to learn Git and GitHub from scratch I also spent time trying to understand what every function in the code does

**Most interesting learning**: I enjoyed taking a close look at how Round-Robin works how each process runs for one time quantum and then goes back to the end of the queue I also learned what I can add or modify in the code to extend it

**What I would do differently next time**: Next time I want to try a different scheduling algorithm like SJF (Shortest Job First) and add a mutex to protect shared data between threads or proccec
---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[Through this assignment I learned practically how multithreading works in Java First making the `Process` class implement `Runnable` means we define the code that a thread executes inside its `run()` method. When we call `start()` on a thread, Java begins running that `run()` method in a separate thread The most important part for me was `join()` because the main thread uses it to wait until the current thread finishes its time quantum  Without `join()` all the processes would run at the same time and the ready queue idea would break completely I used `Thread.sleep()` inside `run()` to simulate CPU processing time Finally, what surprised me is that a Java thread cannot be started again after it finishes so I have to create a `new Thread` every time a process goes back to the queue]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most difficult and also the most enjoyable part of this assignment was working with Java threads and seeing how they behave inside a scheduler  It was hard because I had to understand how `start()`and `join()` and `Thread.sleep()` work together and how the main thread controls which process runs next Watching the ready queue after every quantum helped me see how a process that does not finish goes back to the end of the queue so the order of the processes keeps changing I also saw how a very small change in the code like where a counter is incremented or a time is recorded can change the whole output For example the context switch count and the waiting times depend on exactly where I placed those lines This showed me that in multithreaded programs the order and position of every call really matters]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[To overcome the challenges I first went back to the code examples in the course slides and watched some videos on the Tuwaiq learning platform to understand more about how threads work I also asked my classmate Ibrahim Al-Tufail when I got stuck and we discussed the ideas together while I wrote my own code I used an AI assistant to guide me through the setup steps and to check whether my work was right or wrong and then I read the code again until I understood what each part does When VS Code showed the error "no registered task type 'Java'" I fixed it by checking the Java extension reopening the project folder and running the program again When the table printed Arabic-Indic digits I solved it by adding `Locale.US` to `printf` I also tested the program after each small change which made it easier to find which line caused a problem]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is used in almost every real application For example in Spotify one thread plays the audio another thread downloads the next song from the internet and a third thread updates the lyrics and the progress bar on the screen This is similar to my simulation where each process runs inside its own thread that executes the `run()` method The progress bar I print inside `run()` is a small example of a thread doing a task step by step while using `Thread.sleep()` between the updates Web browsers do the same when each tab loads its page in a separate thread so that one slow tab does not freeze the others Learning how `start()` and `join()` control the order of threads helps me understand why these applications stay responsive and why synchronization is important when threads share data]

### Optional: What would you like to learn more about?

[I would like to learn more about SJF scheduling deadlocks and mutexes I enjoy analyzing how these concepts work even though I still get a little confused by them I think understanding them better will help me write safer and more efficient multithreaded programs]

### Optional: How confident do you feel about multithreading concepts now?

[Intermediate I am neither a beginner nor an expert but I want to keep improving and understand more. I understand how `start()`and`join()` and `Thread.sleep()` work and how Round-Robin sends an unfinished process to the end of the queue I need more practice with mutexes deadlocks and the thread lifecycle states]

### Optional: Feedback on the assignment

[The assignment was useful and I learned a lot from it I wish I had not been late in submitting it and that I had started earlier so I could learn and understand more I will make sure not to repeat this mistake and waste opportunities like this in the future]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.


[A process is an independent program with its own private memory space while a thread is a smaller unit of execution inside a process that shares the memory of the other threads in the same process Creating a process is heavy and slow because the operating system must allocate memory and a separate Process Control Block (PCB) but a thread is lightweight and faster to create and to switch between Threads can also communicate quickly through shared variables while processes need inter-process communication such as pipes or sockets In this assignment I used threads because all the simulated processes need to share the same `processQueue`, `processMap` and `contextSwitchCount` inside one program The class named `Process` in my code is only a simulated process and the real Java thread is created by `Thread thread = new Thread(process);` in `addProcessToQueue()`]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*


In Round-Robin when a process does not finish within its time quantum the scheduler puts it back at the end of the ready queue so the next process can use the CPU For example P1 has a burst time of 12038ms and the quantum is 5000ms so it ran for 5000ms then 5000ms again and finally 2038ms which means it was re-queued 2 times before it finishedd Re-queueing matters for fairness because a long process cannot monopolize the CPU and every process gets a regular turn of the same length This also improves the response time of the whole system

Example from my output: P1

**Explanation of example:**
P1 used its full 5000ms quantum and still had 7038ms left so it printed "yields CPU for context switch" It was then added to the ready queue again and placed at the back behind P14 The other 13 processes each get a turn before P1 runs again which shows the fairness of Round-Robin



## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*


1. **New**: P1thread is in the New state right after `Thread thread = new Thread(process);` in `addProcessToQueue()` The thread object exists in memory but has not started yet

2. **Runnable**: P1 becomes Runnable when the main loop calls `currentThread.start();` It is ready to run and when the scheduler picks it it starts executing `run()`

3. **Running**: P1 is Running while it executes inside `run()` during its time quantum printing the progress bar and reducing `remainingTime`

4. **Waiting**: There are two waiting threads P1 own thread is in Timed Waiting while it calls `Thread.sleep(stepTime);` inside `run()` The main thread is in Waiting at `currentThread.join();` until P1 finishes its quantum

5. **Terminated**: P1 thread is Terminated when it reaches the end of `run()` Because a terminated thread cannot be started again a new `Thread` is created when P1 returns to the ready queue

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): CPU scheduling between running programs

**Description**:
On modern operating systems such as macOS or Windows, many programs run at the same time, for example a web browser, a code editor and a music player. The OS scheduler shares the CPU time between them using time slices, and its basic idea is the same as Round-Robin. In my simulation, each program is like a `Process` object, the time slice is the time quantum (5000ms in my run), and saving one program's state and switching to the next one is the context switch (27 in my run).

**Why Round-Robin works well here**:
It is fair and responsive, because a heavy program cannot monopolize the CPU and freeze the user interface. Every program gets a regular turn, so the music keeps playing while the user types in the editor.

### Example 2: Web server handling many requests

**Description**:
A web server receives many requests from different users at the same time. Usually each request is handled by a worker thread, and the operating system schedules these threads on the CPU with a time-slicing approach similar to Round-Robin. In my simulation, each user request is like a `Process`, the time the OS gives each thread per turn is the time quantum, and moving between worker threads is the context switch.

**Why Round-Robin works well here**:
It gives every user a quick first response instead of making small requests wait behind a huge data download. It is also predictable, because the waiting time depends on the number of active threads and the quantum size.
## Summary

## Summary

**Key concepts I understood through these questions:**
1. The importance of `join()` for synchronizing threads and forcing an organized order in the scheduling logic
2. How a thread moves between the lifecycle states (New, Runnable, Waiting, Terminated) during execution
3. The difference between lightweight Java threads and the simulated `Process` objects in my code

**Concepts I need to study more:**
1. Advanced synchronization tools beyond `join()` such as mutexes semaphores and locks
2. The cost of context switching at the hardware level and how memory is managed during interrupts

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
