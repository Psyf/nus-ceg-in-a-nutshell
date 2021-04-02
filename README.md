# nus-ceg-in-a-nutshell

- A quick summary of my CS education from 2017-2021!
- The ordering below is largely chronological.
- The aim of this is to document my learning journey during my college years, so I can look back at this fondly when I'm old and tired.
- I'll add a quick description of the course, what I thought of it, and add link(s) to similar, free/open resources on the internet I've stumbled onto (mostly so I can look back at the contents when my goldfish memoty fails me!)
- This list is not meant as a review list for the courses. See NUSMods for that (I've probably left a review for most)
- I'll skip the non-cs-related modules :)

## Engineering Principles & Practices I and II

The dry names don't do the courses _any_ justice. Very hands on, lab-based modules designed to give you a holistic picture of what you'll learn in your 4 years. Really broad pair of courses covering everything including:

- Hardware Circuits (all that Inductor/Capacitor/Kerchoff/Filter stuff I seem to have forgotten),
- some programming, datastructures and algorithms (most of us didn't know much programming yet!),
- Microcontrollers (Arduino, Interrupts, Bare-Metal), ROS (on an RPi's Raspbian),
- sensors (Ultrasound, IR, LIDAR), and actuators (motors mostly)
- technical presentations, documentations, and working in teams!

By the end of each course you make a semi-autonomous maze solving robot with the help of everything you've learnt! The courses are real tests of what gets you excited, and some people are really looking forward to the rest of their degrees while others realize they need to switch majors!

## Programming Methodology

Quick introduction to the C programming language and how to think like a problem solver. There are other variants based on Java/Python/JS-fork, but I'm really glad I took the C version. The C version let me think about things much closer to the metal, and it has helped me over my degree when I had to crack open black-boxes.

Similar to:

- [TutorialsPoint](https://www.tutorialspoint.com/cprogramming/index.htm)
- [CS50x by Harvard](https://cs50.harvard.edu/x/2021/)
- [by Duke](https://www.coursera.org/specializations/c-programming#courses)

## Discrete Mathematics

First introduction to formal notation and proofs. Over the semester we learnt lots of fun theories about the world of discrete maths (without any practical CS context elaborated) and I can't say I remember enough to ace the final exam if I were to take it now. However, it did give me the skills to follow formal logic (albeit very carefully and slowly) and for that I'm extremely grateful.

Similar to:

- [MIT OCW 6.042J](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about)
- [UCSD on Coursera](https://www.coursera.org/specializations/discrete-mathematics)

## Engineering Calculus

I can tell you the word "Lagrangian" exists and I can tell you I never want to encounter that word again. Pretty much sums it up. This course was so poorly taught (in a rush, 6 classes only!) that it sucked out all the love I had for Math (and I _really_ liked Maths in High School) and I will never forgive this :'(

On a side note, it helped me get out of grade anxiety pretty early on. I thought I'd failed after the finals, but ended up getting a B+ (NUS grades on a bell curve, which means most of my peers kinda "failed" too).

I hope I get the chance to revisit this subject and really learn beyond double integrals and the notations.

Similar to:

- [MIT OCW 18.02SC](https://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/)
- [3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)

## Differential Equations

Similar to Engineering Calculus (but not _as_ bad). We learnt some techniques of solving different kinds of differential equations (basically get the equation to one of these patterns and then use this formula to solve it...). I _don't_ care about how fish populations change over time according to Malthus beyond the 5 minutes of philosophical ramblings that went on in my head. And why on earth are you pouring water in a tank that's leaking!

Needless to say, Shift+Deleted most of the content as soon as I was done with the exams. I think I can still find the "cheatsheet" I prepared for the exam somewhere though.

Similar to:

- [3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDNPOjrT6KVlfJuKtYTftqH6)
- [MIT OCW 18.03SC](https://ocw.mit.edu/courses/mathematics/18-03sc-differential-equations-fall-2011/)

## "Data Structures and Algorithms" | "Design and Analyis of Algorhtms"

The first course taught us the basic Data Structures (from Lists to Balanced Trees), and Algorithms (from MaxInList to Djikstra). The course was really well taught, and we had an awful lot of gamified practice on Kattis (think Leetcode). The course did not expect us to memorize much and challenged us to use multiple structures and algorithms in combination to meet some time/space constraints. Most NUS CS courses are open-book, bring whatever; recently you can even bring your laptop!

The second course was an extension of "Data Structures and Algorithms" and very proof-heavy. We looked at Complexity (Master Theorem, P-NP), Dynamic Programming, Graph Flow Algorhtms, Randomized and Approximate algorithms. I just wish we had some hands-on components instead of 4 paper-based assignments (taken at UofT)

Similar to:

- [Standford Specialization on Coursera](https://www.coursera.org/specializations/algorithms)
- [UCSD Specialization on Coursera](https://www.coursera.org/specializations/data-structures-algorithms)

## Digital Design | Transistor-Level Digital Circuits | Computer Organization

The first course taught us the basics of Boolean Logic, KMaps (quite simple after Discrete Maths) and some practice with Finite State Machines. The second half had an FPGA segment with Verilog and I **absolutely do not** want to touch an FPGA ever again.

The second course was a pretty fun course on transistors (thankfully bounded to the digital parts only). We learnt about how transistors make different digital circuits (which go on to build everything on your computer - from CPU to RAM to SSDs!)

What's up with boring names for fun courses? The third course taught us about building components with transistors and using those components in various configurations to make a CPU. We designed a very basic CPU and briefly looked at the ARM ISA (and painfully translated some instructions to Machine Code). Also my first taste of Assembly language, and that was pretty cool.

Similar to:

- [Digital Circuits](https://www.coursera.org/learn/digital-systems#syllabus)
- [Condensed Coursera Course](https://www.coursera.org/learn/build-a-computer?#syllabus)
- [FPGA/VHDL](https://www.coursera.org/learn/fpga-hardware-description-languages?specialization=fpga-design#syllabus)

## Linear Algebra

Thankfully, this course was more fun than the other soul-crushing math courses taken by Engineering (though I wish I took the CS variant). We had a good teacher who tried to make things intuitive. I must say though, even though I enjoyed it a lot, it didn't become second nature to me and I knew I could never get into serious Game Development.

Similar to:

- [Linear Algebra by Gilbert Strang](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/)
- [3B1B again](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

## Object-Oriented Programming and Software Engineering

Basically gave us a traditional Java Monolith, bucketed us unto teams of 4, and made us repurpose the monolith to whatever we wanted. It took us through the Software Development Life Cycle while teaching us about Object Oriented Programming and Software Engineering Patterns. We went through a few (5?) 2 week sprints and code-reviews and it was a pretty fun experience overall!

The course had a companion course about technical documentation and technical presentation, and it helped me practice my skills there (though all the theory was too basic and common-sense-y to be useful).

Similar to:

- [OOP Basics in Java](https://www.coursera.org/learn/object-oriented-java?specialization=object-oriented-programming#syllabus)
- [OOP Design](https://www.coursera.org/learn/object-oriented-design#syllabus)
- [Software Design](https://www.coursera.org/specializations/software-design-architecture)
- [SDLC Overview](https://www.coursera.org/specializations/software-development-lifecycle)
- [TutorialsPoint](https://www.tutorialspoint.com/software_engineering/index.htm)

## Signals and Systems

Fourier transforms and all that. Enjoyed learning about them, but why on Earth would I want to calculate these by hand? I'd much prefer if we delved a lot more into the applications. (To be fair, we did have a nifty little lab module to build circuits for changing voice-audio in different ways)

Similar to:

- [Specialization by EPFL](https://www.coursera.org/specializations/digital-signal-processing)

## Real Time Operating Systems

Fun module learning about the Operating System internals. We mainly focused on Real Time Operating Systems, so I didn't get to dive into the Linux Kernel or anything (I wish :'( )

We did have lots of fun building a bluetooth-controlled RC race-car on FreeRTOS+Arduino with bells and whistles and blinking lights (no, really!).
The obstacle course race at the end of the course was fun too.

Similar to:

- [RTOS Specialization](https://www.coursera.org/specializations/embedded-systems-security)

## Database Systems

Learning the basics of SQL (postgres) and some theory behind them (Relational Algebra, ACID, Normal Forms etc). It was fun writing contrived, complex SQL queries under exam stress (I don't remember whether we were allowed to use postgres to validate the queries), and we made a simple webapp (most of the concentration was on the Schema Design and DB Layer as you can imagine).

Simialr to:

- [UColorado Course](https://www.coursera.org/learn/database-management#syllabus)

## Introduction to Information Security

Seriously, for the last time, what is up with boring names for extremely fun courses??! The course taught us the basics of cybersecurity, and every week we had CTF style assignments to try and exploit using the techniques we learnt in class. We also had tutorials where we discussed the biggest security snafus and hacks in recent history so that was pretty fun!

It was so fun that I decided to specialize in Cybersecurity (and never took another related course /shrugs )

Similar to:

- [Coursera Specialization by IBM](https://www.coursera.org/specializations/it-fundamentals-cybersecurity#courses)

## Probablity and Statistics

Pretty standard requirement for any degree. Necessary to read/write scientific papers that present statistics. Understand the reasoning, kinda understand the proofs behind the theorems, and then just apply the formulae as needed. Meh.

Similar to:

- [MIT OCW 18.05](https://ocw.mit.edu/courses/mathematics/18-05-introduction-to-probability-and-statistics-spring-2014/syllabus/)

## Computer Networks

Loved this course. Took it at UofT under researchers at the forefront of SoftwareDefinedNetworking and it gave me a big picture view of how the internet works (at different layers) and appreciate the emergent behaviours of decentralized networks and protocols.

Similar to:

- [UColorado Specialization](https://www.coursera.org/specializations/computer-communications#courses)

## Philosophy of Science

Not directly related to Computer Science, but I found this course quite illuminating. Can't believe this is not mandatory requirement!

Similar to:

- [Shareless Plug](https://medium.com/dabbler-in-de-stress/the-philosophy-of-science-324098cd6780)

## Engineering Professionalism

Though most of my friends hated this course, I rather enjoyed teasing apart the ethical dillemmas in multiple case studies (for example: Space Shuttle Disasters)

Similar to:

- [TutorialsPoint??!](https://www.tutorialspoint.com/engineering_ethics/engineering_ethics_introduction.htm)

## Embedded Software Design

I took a graduate level course just to see whether I could cope with the workload while working on my internship full-time. We talked about the state of the Embedded market today (big.LITTLE), different scheduling algorithms for tasks, power efficiency etc. Surprisingly light workload even though we got to play with clock frequency and core usage a little, hybrid multicore machine.

Similar to:

- [This but less depth](https://www.coursera.org/specializations/real-time-embedded-systems#courses)

## Programming Language Concepts

One of the most fun courses I've taken, and it has made me such a better programmer. It was mainly about Functional Programming (Haskell), though we touched on OCaml and Scala. I assume the professor didn't touch Python, C or Java because most people in the class seemed to have some experience with them anyways. Definitely should have taken it much earlier, though I doubt I'd take much away without having experienced reading (and writing!) messy codebases.

Similar to:

- [All 3 courses on PL](https://www.coursera.org/learn/programming-languages#syllabus)

## Parallel Computing

We had hands on experience with threads, processes, OpenMP, CUDA, MPI (all on C++). Worked very hard for this course, but mainly because it was so damn fun (and I was procrastinating on my other courses). A couple lines of additional OpenMP code leaving my custom code (that I worked on for a couple weeks) in the dust was a _very_ humbling experience. And we got to play around with NVidia's Tesla GPUs to "mine" bitcoins. How cool is that??!

Similar to:

- [Architecture](https://www.tutorialspoint.com/parallel_computer_architecture/index.htm)
- [OpenMP](https://riptutorial.com/openmp)
- [MultiThreading in C](https://www.geeksforgeeks.org/multithreading-c-2/)
- [MultiProcessing in C](https://codehs.com/tutorial/neel/Introduction_to_Multiprocessing_in_C-1)
- [CUDA](https://developer.nvidia.com/blog/even-easier-introduction-cuda/)

## Data Science Basics

Taught by ECE, didn't like it all that much. All the knowledge in the course could be condensed into a couple weeks, but this maybe because I'd taken Deeplearning.ai a couple years back (during a quick summer research stint). Still, was an okay experience because I got to learn a bit more about "traditional" Machine Learning models (Bayesian Models, SVMs etc.) I regret not taking the CS version of the AI/ML courses (I'm starting to sniff a pattern here...) because they went in much deeper and weren't afraid of some deep hands-on programming.

Similar to:

- [Statquest Playlist](https://www.youtube.com/watch?v=Gv9_4yMHFhI&list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF)

## Big Data Systems for Data Science

Very fun course. We learnt about HDFS, MapeReduce, PageRank (and other Graph Algorithms), Apache Spark, NoSQL Databases etc. For the project, our team analyzed a tonne of data from AirBnB on a spark cluster, and wrote quite a nifty report. If only I'd had these skills during my 6-month internship...

Similar to:

- [Course](https://www.coursera.org/learn/big-data-essentials#syllabus)
- [Specialization](https://www.coursera.org/specializations/big-data)

## Database Systems Implementation

Covers a broad base from calculating I/O cost and required buffer space for different SQL query operators to implementation details like indexes, query optimizers, concurrency control, transaction flow, crash recovery etc. The best part of the course was being given a barebones Database implementation (unfortunately in Java), and having to code up, optimize query operators under dynamic bufferSpace+pageSize constraints. Definitely lost a couple nights, but absolutely loved doing it!

Similar to:

- [Awesome CMU Course](https://www.youtube.com/watch?v=oeYBdghaIjc&list=PLSE8ODhjZXjbohkNBWQs_otTrBTrjyohi&index=1)

## Capstone

Supposed to be the culmination of our 4 years in college. We had to design a distributed IoT system for "dance training". The system involved microcontrollers, IMUs, BLE, EMG Sensors, Message Brokers, SSH Tunnels, a WebApp, Neural Networks and an FPGA for hardware acceleration. Team of 6 developing the system over 12 weeks, and writing a 100 page developer guide. Not the project I'd go for if I was given a choice, but definitely enjoyed myself!

## Looking Back

Wow! I can't believe how much cool shit I've learnt just in the past 4 years. 2017 Saif would definitely be impressed by 2021 Saif. I've worked with bare bits on Microcontrollers to Mini Data Centers on the cloud, on a variety of different projects, languages and paradigms. There was a distinct lack of more robust Software Engineering stacks and practices, but the basics we learnt in school were solid enough to pick things up fast during internships.

I regret not taking enough courses outside the CS discipline (blew most my flexible slots away on CS courses), AND I also regret not having the time to take a lot more CS courses (AR/VR, Advanced Cybersec, Compilers, Distributed Systems, Competitive Programming, Robotics and so much more!)

Ah well, at least I did a decent job at being a passionate, interested learner without caring too much (or too little!) about my grades. I can't wait to see what I learn in the next few years!
