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
| **Full Name** | layan mohammed al harbi  |
| **Student ID** | 446051491 |
| **University Email** | 446051491@std.psau.edu.sa |
| **GitHub Username** | l1ayann |
| **Repository Link** | https://github.com/l1ayann/OS-Assignment1-layan-alharbi.git |
 
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
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 6, 2026, 4:00 PM]
**What I did**:Forked the repository and prepared the project environment.

**Details**:- Read the README file to understand the assignment requirements.
- Opened SchedulerSimulation.java and reviewed the existing code.
- Updated my student ID in the program.
- Ran the program to check that it worked correctly.
- Committed the changes.

**Challenges**:Understanding the structure of the existing scheduler code was difficult at first.

**Solution**:I read the code carefully and tested the program before making changes.

**Time spent**:45 minutes.

---

### Entry 2 - [October 9, 2026, 3:30 PM]
**What I did**: Implemented Feature 1: Process Priority.

**Details**:Added a priority field to the Process class.

Generated random priority values from 1 to 10.

Added a getter method for priority.

Updated the output to display each process priority.

Committed the changes.

**Challenges**:Making sure priority only displays information and does not change Round-Robin scheduling.

**Solution**:I tested the output and confirmed that processes still followed the ready queue order.

**Time spent**:1 hour.

---

### Entry 3 - [October 10, 2026, 1:30 PM]
**What I did**:Implemented Feature 2: Context Switch Counter.

**Details**:- Added a context switch counter variable.
- Increased the counter when a new process started running.
- Displayed the total context switches after completion.
- Tested the program output.
- Committed the changes.

**Challenges**:Finding the correct place to increase the counter.

**Solution**:I placed the counter before currentThread.start() because it represents a new process execution.

**Time spent**:40 minutes.

---

### Entry 4 - [October 10, 2026, 4:30 PM]
**What I did**:Implemented Feature 3: Waiting Time Tracking.

**Details**:- Added variables to track waiting time.
- Added methods to calculate waiting and turnaround time.
- Created the summary table.
- Tested the final output.

**Challenges**:Calculating waiting time when processes return to the ready queue.

**Solution**:I updated the ready time when a process entered the queue again and calculated the waiting duration before execution.

**Time spent**:1.5 hours.

---

### Entry 5 - [October 10, 2026, 6:00 PM]
**What I did**:Completed documentation and final testing.

**Details**:- Completed MY_WORK.md reflection and technical answers.
- Checked all implemented features.
- Reviewed program output.
- Verified GitHub commits and repository status.

**Challenges**:Checking that all assignment requirements were completed.

**Solution**:I reviewed the README instructions and final checklist.

**Time spent**:1 hour.

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

**Total time spent on assignment**:5 hours approximately.

**Most challenging part**:Understanding the existing scheduler code and adding new features without changing the original Round-Robin behavior.

**Most interesting learning**:I learned how threads, ready queues, and CPU scheduling work together.

**What I would do differently next time**:I would start documenting my progress earlier and test every feature after adding it.

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

During this assignment, I learned how to work with an existing Java program that uses multithreading concepts. I learned that threads can help organize the execution of different tasks inside the same program. I used Visual Studio Code to edit the code, run the program, and check the results after my changes. I also learned how to add new features without affecting the original program behavior. Adding priority, context switch counting, and waiting time tracking helped me understand how program information can be collected and displayed. This assignment improved my confidence in modifying Java code and working with GitHub.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*
The most challenging part of this assignment was understanding the existing code before making changes. The provided SchedulerSimulation.java file had many parts that I needed to review before adding my features. The waiting time feature was the hardest because I needed to add the calculation without causing problems in the original code. I also needed to make sure that the priority feature only displayed information and did not change the existing scheduling behavior. I solved this by testing my changes and checking the program output after each modification. This helped me understand how to work with a larger code project

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*
I overcame the challenges by following the instructions in the README file and working step by step. I used Visual Studio Code to test the program after adding each feature. I also used GitHub to save my progress and organize my commits. When I faced difficulties, I reviewed the code and checked where the new features should be added. Testing after every change helped me find mistakes and fix them. This process made my work more organized and helped me complete the assignment successfully.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading concepts can be used in many applications that need to perform multiple tasks. For example, mobile applications can use different threads to handle user actions and background tasks. Web browsers also use threads to load content and respond to user input. Operating systems use similar concepts to manage different programs efficiently. Learning about threads helped me understand how applications can run tasks in an organized way. The concepts from this assignment can help in developing faster and more responsive programs.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

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

**Your Answer:** *(3-5 sentences)*

A process is an independent program, while a thread is a smaller execution unit that works inside a program. In my code, the Process class represents a simulated process and it implements the Runnable interface. The method addProcessToQueue() creates a new thread using new Thread(process) and adds it to the ready queue. Threads are used in this assignment because they allow the processes to be executed and managed inside the same Java program.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*
When a process does not finish during its time quantum, the scheduler adds it back to the ready queue to continue later. In my output, P3 had a burst time of 12026ms and ran for a quantum of 5000ms, but it still had 7026ms remaining. The code checks if the process is not finished and uses addProcessToQueue() to return it to the queue. This re-queueing is important because it gives other processes a chance to run and keeps the scheduling fair.




Example from my output:

P3 (Priority: 9) added to ready queue
P3 executing quantum [5000ms]
P3 completed quantum 5000ms
Remaining time: 7026ms
P3 yields CPU for context switch
P3 (Priority: 9) added to ready queue

**Explanation of example:**

This output shows that P3 did not finish after its first quantum because it still had remaining time. The scheduler returned P3 to the ready queue so it could continue execution in another turn.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

New: P1 is in the New state when it is created using new Thread(process) inside addProcessToQueue().

Runnable: P1 becomes Runnable when the scheduler calls currentThread.start(), making it ready to execute.

Running: P1 is Running when its thread executes the Process.run() method and simulates process execution.

Waiting: P1's thread enters Timed Waiting when Thread.sleep(stepTime) pauses its execution. The main thread waits at currentThread.join() until P1's thread finishes.

Terminated: P1's thread becomes Terminated when its run() method finishes executing.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): CPU Scheduling

**Description**:
An operating system runs many programs at the same time. Each program needs CPU time to do its work. The operating system gives each process a small amount of time to run.

**Why Round-Robin works well here**:
Round-Robin helps give each process a fair chance to use the CPU. The time quantum limits how long each process can run in one turn. This is similar to the scheduling idea used in my simulation.

### Example 2: Tasks in an Application

**Description**:
An application may have several background tasks, such as loading data and updating the screen. Each task needs time to do its work. A scheduler can take turns between tasks instead of letting one task use all the time.

**Why Round-Robin works well here**:
Round-Robin can help tasks get a fair share of processing time. The time quantum sets the time for each turn, and a context switch happens when the scheduler moves to another task. This can help the application stay responsive while different tasks are running.

## Summary

**Key concepts I understood through these questions:**
1. I understood the difference between processes and threads.
2. I learned how to modify an existing Java project and add new features.
3. I understood how ready queues and scheduling manage execution.


**Concepts I need to study more:**
1. Advanced multithreading concepts.
2. More CPU scheduling algorithms.

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
