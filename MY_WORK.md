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
| **Full Name** | [ليان ابراهيم شويعي] |
| **Student ID** | [445052500] |
| **University Email** | 445052500@std.psau.edu.sa |
| **GitHub Username** | [layan-445052500] |
| **Repository Link** | [https://github.com/layan-445052500/OS-Assignment1-Layan-Shuwayi] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/1h1nPVQx9v1uDKK6pLBfM-0LHadS58TFc/view?usp=drivesdk]

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

### Entry 1 - [september 22, 2026, 2:30 PM]
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

### Entry 1 - [october 7 , 2026 , 12:46 AM]
**What I did**: I created my GitHub account, read the README.md, and started forking the repository, and update studentID.

**Details**:
created my GitHub account using my university email.
read the README.md to understand the assignment requirements.
started the process of forking the repository to my GitHub account.
udated random studentID with my studentID.

**Challenges**: I was still getting familiar with GitHub and the repository setup process.

**Solution**: I followed the instructions in the README.md and completed the setup step by step.

**Time spent**: 10 minutes

---

### Entry 2 - [october 7 , 2026 , 5:56 PM]
**What I did**: I installed visual studio code , opened the assignment1 folder, implemented feature1 by adding priority and committed my changes.

**Details**:
I tested my work using the terminal and checked that everthing was working correctly. 
after confirming that the feature worked as expected, i saved my work.

**Challenges**: I needed to make sure that the code worked correctly after implemented the feature .

**Solution**: I tested the program using terminal and checked the output to make sure everything was working correctly.

**Time spent**: 4 hours

---

### Entry 3 - [october 8 , 2026 , 8:27 PM]
**What I did**:I implemented feature2 by adding a context switch counter to the program.

**Details**: 
I initialized the counter to zero and incremented it each time the scheduler selected the next thread from the ready queue.
I printed the final counter value after all processes completed.
After running the program successfully and verifying the output , i committed may changes.

**Challenges**: I needed to make sure that the counter increased at the correct time during the scheduling process.

**Solution**: I updated the counter whenever the scheduler selected the next thread and checked the final output after running the program.

**Time spent**: 30 minutes

---

### Entry 4 - [october 8 , 2026 , 9:00 PM]
**What I did**: I implemented feature3 to track process waiting times.

**Details**: I used System.currentTimeMillis() to calculate waiting times and added a final table displaying each process's name , burst time, waiting time, and turnaround time. 
I tested the program and committed my changes.

**Challenges**: I needed to calculate waiting times correctly as processes moved through the ready queue.

**Solution**: I tracked when processes entered the queue and calculated their waiting times when they started running.

**Time spent**: 1 hour:40 minutes

---

### Entry 5 - [0ctober 8 , 2026 , 11:21 PM]
**What I did**: I tested the completed program and reviewed the final results.

**Details**: I ran the program , checked the waiting time table and context switch counter, and confirmed that all processes completed successfully.
I also verified that my changes were committed and pushed to GitHub.

**Challenges**: I needed to make sure that all three features worked correctly together.

**Solution**: I tested the program and checked the output to verify that everything worked as expected.

**Time spent**: 10 minutes

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

**Total time spent on assignment**: [6 hours]

**Most challenging part**: implementing the three features and the test part.

**Most interesting learning**: this experience helped me understand CPU scheduling and improve my java programming skills.

**What I would do differently next time**: I would start earlier, test my code more often, and orgnize my work better.

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

[i have learned how to established threads using Runnable , and Thread.start() , and 
Thread.sleep() it simulates the execution process . i also used join() to wait for the thread to be completed . i understand that the process scheduling is managed by the scheduler using ready queue. and i learned how to track waiting time and count context switches. surprised the way that threads work together and how the scheduler manages the threads.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[implementing Feature3 was to track waiting time.I calculated the waiting time using 'System.currentTimeMillis()', and added final table showing the details of each process includin its name, burst time, waiting time, and turnaround time, and committed the changes to GitHub.It was difficult to write the code and ensure there were no errors.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame the challenges by testing my code and working step by step.The README.md helped me understand the instructions,and i asked for help when i did not understand something.Testing the code multiple times it made it easier for me to detect and fix errors.I also learned that understanding how threads work helped me write better code and avoid errors.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Safari loads web pages and runs browser tasks simultaneously. Minecraft handles player movement and the in-game world. WhatsApp receives massages and downloads images and files while using the app. Spotify plays music or podcasts while browsing another app. YouTube plays the video and loads data simultaneously. Multithreading and the scheduler help orgnize and efficiently execute tasks in real-world applicatins.] 

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

[A process is a program in execution with its own memory that progress through its instructions. While thread is a basic unit of CPU utilization that can share memory and resources within the same process. Creating a process requires more resources than creating a thread. In my assignment,the Process class represents a simulated process,but a real java thread executes it. In the addProcessToQueue() method,the line new Thread(process) creates a thread for the simulated process.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In my program,if a process does not finish within its time quantum,it is added back to the ready queue. For example,P5 has a burst time of 6672ms,but its time quantum is 4000ms. After the first turn,P5 had 2672ms remaining,so it was added back to the ready queue once. It then executed for the remaining 2672ms and finished.]

Example from my output:
```
[
ظû╢ P5 executing quantum [2672ms] 
  ظأة Quantum progress: [ظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûê] 100%
  ظ╕ P5 completed quantum 2672ms ظ¤é Overall progress: [ظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûê] 100%
     Remaining time: 0ms
  ظ£ô P5 finished execution!

ظ¤îظ¤ Ready Queue ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤
ظ¤é [P7 (Priority: 6) ظْ P8 (Priority: 5) ظْ P9 (Priority: 6) ظْ P10 (Priority: 7) ظْ P11 (Priority: 2) ظ P1 (Priority: 4)]
ظ¤¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤
ظû╢ P5 executing quantum [2672ms] 
  ظأة Quantum progress: [ظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûê] 100%
  ظ╕ P5 completed quantum 2672ms ظ¤é Overall progress: [ظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûê] 100%
     Remaining time: 0ms
  ظ£ô P5 finished execution!

ظ¤îظ¤ Ready Queue ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤
ظ¤é [P7 (Priority: 6) ظْ P8 (Priority: 5) ظْ P9 (Priority: 6) ظْ P10 (Priority: 7) ظْ P11 (Priority: 2) ظ P1 (Priority: 4)]
ظ¤¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤
]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted:
outout shows that P5 used its first time quantum of 4000ms but did not finish because 2672ms remaining. It was added back to ready queue once, allowing other processes to execute. Then,P5 used the remaining 2672ms and fished execution. This demonstrates how Round Robin gives processes fair turns to use the CPU.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [when its thread object is created in addProcessToQueue().]

2. **Runnable**: [When Thread.start() is called by the scheduler.]

3. **Running**: [When it executes its run() method and uses the CPU.]

4. **Waiting**: [When Thread.sleep() is called, while the main thread may wait for completion using Thread.join().]

5. **Terminated**: [When its run() method finishes.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU scheduling in an OS]

**Description**:
[An operating system uses Round Robin scheduling to share CPU time among processes.]

**Why Round-Robin works well here**:
[Each process gets a fixed time quantum,which provides fairness and allows processes to take turns using the CPU. Context switching allows the OS to switch between processes.]

### Example 2: [Web Server]

**Description**:
[A web server handles multiple requests from users using threads.]

**Why Round-Robin works well here**:
[Each thread gets a turn to execute,improving fairness and responsiveness. The time quantum prevents one thread from using the CPU for too long,allowing other requests to be processed.]

## Summary

**Key concepts I understood through these questions:**
1.process
2.thread
3.multithread

**Concepts I need to study more:**
1.thread lifecycle.
2.waiting time and turnaround time.

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
