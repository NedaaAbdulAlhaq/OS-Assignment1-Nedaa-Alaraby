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
| **Full Name** | [Nedaa AbdulAlhaq Alaraby] |
| **Student ID** | [446052622] |
| **University Email** | [446052622]@std.psau.edu.sa |
| **GitHub Username** | [NedaaAbdulAlhaq] |
| **Repository Link** | [https://github.com/NedaaAbdulAlhaq/OS-Assignment1-Nedaa-Alaraby] |
 
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

### Entry 1 - [October 4, 2026 – 9:30 PM]
**What I did**:
I opened the assignment for the first time, read the instructions, and changed my student ID. Then I made my first commit.

**Details**:
When I first opened the assignment, I spent time trying to understand the idea of the scheduler and what the project was asking me to do. I logged into GitHub, accessed the repository, and looked through the starter code to see how everything was structured. After that, I changed my student ID as required and pushed my first commit. Then I realized that editing directly on GitHub wasn’t practical, so I downloaded Visual Studio Code and installed Git and the needed extensions. Setting up VS Code took some time because I had to connect it to my GitHub account and make sure everything was configured correctly before I could continue working.

**Challenges**:
It was difficult to follow the steps exactly as written. I kept doing extra actions or installing things I didn’t actually need, which made me confused and slowed me down.

**Solution**:

I went back and re-read the instructions carefully until I understood the correct workflow. Once I followed the steps properly, everything became clearer and I was able to continue .

**Time spent**:
5 hours.

---

### Entry 2 - [October 5, 2026 – 11:00 PM]
**What I did**:
I started working on the coding part of the assignment, tried to understand the initial structure of the program, and added Feature 1 (priority). After testing that the code worked correctly, I made my second commit.

**Details**:
When I opened the code, I spent time trying to understand how the classes were connected and how the scheduler was organized. I added a new variable called priority and defined it as a random number between 1 and 10. Then I made sure that the priority value appears for each process when it enters the ready queue. At first, I wasn’t sure where exactly I should place the priority—whether inside the main method or inside the constructor. After thinking about it, I realized that the constructor is responsible for defining each process, so the priority logically belongs there. Once I confirmed the code was running correctly, I committed the changes.

**Challenges**:
I was unsure about the correct place to generate and store the priority value, and I didn’t want to break the structure of the program.

**Solution**:
I reviewed how the constructor works and understood that it initializes all process-related properties, so placing the priority there was the right decision. 

**Time spent**:
1 hour 30 minutes. 
---

### Entry 3 - [October 6, 2026 – 12:30 AM]
**What I did**:
I started working on Feature 2 (context switches) and made my third commit after confirming the feature was working correctly.
**Details**:
I added a new variable called counterContextSwitches to keep track of how many times the CPU switches from one thread to another. Then I incremented this counter every time a new thread started running. After that, I printed the final number of context switches at the end of the simulation and tested the program several times to make sure the value changed correctly based on the number of processes. At first, I wasn’t sure where exactly to place the increment—whether before start() or after join(). I tried both options multiple times, and eventually realized that the correct place was before calling start(), because that’s when the CPU actually switches to a new process.

**Challenges**:
I didn’t know the correct moment to count a context switch, and placing it in the wrong spot gave inaccurate results.

**Solution**:
Through testing and re-reading the code flow, I understood that the switch happens right before the thread starts, so I placed the increment there.

**Time spent**:
 2hour.
---

### Entry 4 - [October 9, 2026 – 2:00 AM]
**What I did**:
I started working on Feature 3 to calculate the waiting time and generate a summary table for all processes. I tested the code repeatedly until everything worked correctly.

**Details**:
I added the variables creationTime, lastEnqueueTime, and Totalwaitingtime inside the constructor so each process could track its timing information. Then I calculated the waiting time using System.currentTimeMillis() and updated lastEnqueueTime every time the process re-entered the ready queue. After that, I implemented the methods getwaitingtime() and getTurnaroundTime() to return the correct values for each process. The most difficult part was understanding how waiting time should be calculated and where exactly to update the timing values in the code. I also struggled with the final printing because the processes were repeating in the table and the formatting was messy, which caused several errors. I kept testing and adjusting the code until I found the right place to update the waiting time and fixed the printing logic.

**Challenges**:
Understanding the waiting time logic and fixing the repeated rows in the summary table was confusing and caused multiple errors.

**Solution**:
I tested the code step by step, re-read the scheduling flow, and kept adjusting the timing updates until the waiting time and table output became correct.

**Time spent**:
 3 hour.

---

### Entry 5 - [October 10, 2026 – 3:30 AM]
**What I did**:
I continued working on Feature 3 and fixed the issue of repeated processes in the final summary table. After confirming the output was correct, I made the commit.

**Details**:
While printing the final summary table, I noticed that the same process appeared multiple times, and the rows were messy and not aligned. The problem was that I was printing directly from the map, which created duplicates every time a process re-entered the ready queue. To fix this, I added an ArrayList to store each process only once when it was first created. Then I used this list in the final printing instead of the map. After updating the printing format with printf, the table became clean, organized, and without duplicates. Once everything looked correct and the waiting and turnaround times were accurate, I committed the changes.

**Challenges**:
The repeated rows and messy formatting made the table confusing, and it took time to understand why the processes were duplicated.

**Solution**:
I added a separate list to store unique processes and used it for the final output, which solved the duplication problem completely.

**Time spent**:
1 hour.

---

### Entry 6 - [October 10, 2026 – 5:30 PM]
**What I did**:
I worked on writing the documentation, answering all reflection and technical questions, and preparing the final submission.

**Details**:
Today I focused on completing the written parts of the assignment. I organized my development log, wrote the reflection answers, and explained the technical concepts based on my own code and output. I also reviewed the instructions again to make sure I didn’t miss any required section. After finishing the answers, I checked the formatting and made sure everything was clear and well‑written. This was the final step before submitting the assignment

**Challenges**:
It took time to write everything clearly and make sure my answers matched the code I actually wrote.

**Solution**:
I went through each part slowly, reviewed my code and output, and wrote the documentation step by step until everything was complete.

**Time spent**:
4 hour.

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [16 hours]

**Most challenging part**:
The hardest part for me was understanding how the code works, especially the waiting time logic and where exactly to update the timing values inside the scheduler. I also struggled with the final summary table because the processes kept repeating and the formatting looked messy until I fixed it.

**Most interesting learning**:
The most useful thing I learned was how multithreading actually works in practice—how each process runs inside its own thread, how the scheduler controls execution using the time quantum, and how context switches happen. It helped me understand how operating systems manage tasks .

**What I would do differently next time**:
Next time, I would start the assignment as soon as it is released so I have more time to understand each part without rushing. I would also document my work step‑by‑step instead of writing everything at the end, because documenting while working makes the process much easier and clearer.


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

[During this assignment, I learned how multithreading actually works in Java and how each process runs inside its own thread. I understood how Runnable is used to define the work of a thread and how Thread.start() begins the execution. I also learned that Thread.join() makes the main thread wait until the process finishes, which helped me control the order of execution. Using Thread.sleep() to simulate the time quantum was new to me, and it showed me how the scheduler pauses a thread. One thing that surprised me was how threads can run independently but still be managed in a queue like the ready queue in our simulation. Seeing the output change every time a thread started made the concept much clearer.]


## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part for me was calculating the waiting time correctly in Feature 3. I struggled to understand where exactly I should update lastEnqueueTime and how to make sure the waiting time increases only when the process re-enters the ready queue. At first, the table kept printing repeated processes, and the numbers were completely wrong. I also had several errors because the timing values were updated in the wrong place. This part took me the longest because I had to test the code many times and watch the output carefully. Understanding the logic behind waiting time was harder than I expected.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame the challenges by testing the code step by step and using System.out.println to see the actual values during execution. Every time something looked wrong, I printed the timing variables to understand what was happening. I re-read the README and the scheduler loop multiple times until I understood the flow of the program. I also tried different places to update lastEnqueueTime until I found the correct one inside addProcessToQueue(). For the repeated printing issue, I added an ArrayList to store each process only once. Testing after every small change helped me fix the errors without breaking other parts of the code.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is used in many real applications that I use every day. For example, web browsers like Chrome run each tab in a separate thread, similar to how each process in my simulation ran inside its own thread. In mobile apps, music continues playing while I scroll or open other screens, which is also done using threads. Games use threads to handle graphics, physics, and sound at the same time, just like how our scheduler switches between processes using a time quantum. Even operating systems use Round-Robin scheduling to give each program a fair amount of CPU time. Working on this assignment helped me understand how these systems manage multiple tasks smoothly.]

### Optional: What would you like to learn more about?

[I would like to learn more about thread synchronization and how to prevent threads from accessing the same data at the same time. I also want to understand deadlocks and how they happen.]

### Optional: How confident do you feel about multithreading concepts now?

[I feel more overwhelmed at the beginning because even though I understand the basic concepts of multithreading, the practical implementation in this assignment was more complex. The code had many interactions and details that made it harder to follow at first. I needed to read the scheduler and the process flow several times before I understood how everything was connected. The structure of the code made me feel more confused than I expected, especially with the waiting time and the repeated printing issues. After finishing all the features, I feel more comfortable, but I still think I need more practice with real multithreading projects. Overall, I would describe my level as intermediate, because I understand the theory well but the practical part still needs more time and repetition.]

### Optional: Feedback on the assignment

[The assignment was complicated and took a long time to understand all the connections between the classes and methods. The practical style of the project made it harder because I had to understand the code design before I could implement anything. If I had studied the structure and logic of the code earlier, the assignment would have been much easier. The amount of interactions inside the scheduler and the process class made the work more challenging at the beginning. I had to read the code multiple times until I understood how each part affected the other. Overall, the assignment was useful, but it required a lot of time to fully understand the design.]

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

[A process is a program with its own memory space, while a thread is a lightweight unit of execution that shares memory with other threads in the same process. In this assignment, the class named Process is only a simulation, and each one is actually executed by a real Java thread created using new Thread(process) inside addProcessToQueue(). Threads are faster to create and communicate because they share memory, unlike processes which have higher creation overhead. Using threads made the simulation easier and more efficient, especially when switching between processes during the time quantum.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, if a process does not finish within its time quantum, it is placed back into the ready queue to wait for another turn. In my output, process P3 had a large burst time, so it was re‑queued multiple times before finishing. Each time it exceeded the time quantum, the scheduler printed a message showing it being added again to the ready queue. This re‑queueing ensures fairness because no single process can take all the CPU time.]

Example from my output:
```
[ ? P1 executing quantum [2000ms] 
  ? Quantum progress: [███████████████] 100%
  ? P1 completed quantum 2000ms │ Overall progress: [█████████░░░░░░░░░░░] 46%
     Remaining time: 2316ms
  ? P1 yields CPU for context switch

  ? P1 added to ready queue │ Burst time: 4316ms *** priority: 10 
  ? P1 executing quantum [2000ms] 
  ? Quantum progress: [███████████████] 100%
  ? P1 completed quantum 2000ms │ Overall progress: [██████████████████░░] 92%
     Remaining time: 316ms
  ? P1 yields CPU for context switch

  ? P1 added to ready queue │ Burst time: 4316ms *** priority: 10]
```

**Explanation of example:**
[this output shows that P1 used its full quantum twice and still had remaining burst time, so the scheduler re‑queued it each time. Only after the third execution did P1 finish completely.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is in the New state right when it is created inside addProcessToQueue(), before calling new Thread(process).start(). At this moment, the thread object exists but has not started running yet.]

2. **Runnable**: [P1 becomes Runnable immediately after the scheduler calls thread.start() in the main loop. This means the thread is ready to run and waiting for CPU time.]

3. **Running**: [P1 enters the Running state when its run() method begins executing and it starts consuming its time quantum. This happens during the line where the scheduler prints P1 executing quantum [2000ms].]

4. **Waiting**: [P1 enters the Waiting state when it calls Thread.sleep(timeQuantum) inside the run() method. Here, P1’s thread is sleeping to simulate CPU usage, while the main thread waits later using join().]

5. **Terminated**: [P1 becomes Terminated when its remaining burst time reaches zero and the run() method finishes. In the output, this is shown when the scheduler prints P1 finished execution.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Time Sharing in an Operating System]

**Description**:
[Operating systems like Windows and Linux use Round‑Robin scheduling to divide CPU time among running programs. Each program acts like a “process,” similar to the processes in my simulation such as P1 and P2. The OS gives each program a small time quantum, then switches to the next one so the system stays responsive even when many applications are open.]

**Why Round-Robin works well here**:
[Round‑Robin ensures fairness because every program gets an equal chance to use the CPU. It also improves responsiveness, since no single program can block the CPU for too long. The context switch in the OS works just like the context switch in my simulation, where the scheduler moves from one thread to another after each quantum.]

### Example 2: [Mobile App with Background Music and UI Updates]

**Description**:
[In mobile apps, background music can keep playing while the user scrolls, opens menus, or interacts with the interface. Each part of the app runs in its own thread: one thread for music, one for animations, and one for user input. This is similar to how each process in my simulation runs inside its own thread.]

**Why Round-Robin works well here**:
[Round‑Robin makes the app feel smooth because it gives each thread a fair share of CPU time. The music thread gets a quantum to play audio, then the UI thread gets a quantum to update the screen, and so on. This predictable switching prevents the app from freezing and keeps everything responsive.]

## Summary

**Key concepts I understood through these questions:**
1.How threads run independently but are controlled by a scheduler.
2.How Round‑Robin uses time quantum and context switches to share CPU time fairly.
3.How waiting time and turnaround time are calculated in a scheduling system.

**Concepts I need to study more:**
1.Thread synchronization and how threads share data safely.
2.Deadlocks and how they happen in multithreaded programs.

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
