# CS Courses To Watch


Introduction
------------

Courses I want to watch (pulled from https://github.com/prakhar1989/awesome-courses)

Table of Contents
-----------------

- [CS Courses To Watch](#cs-courses-to-watch)
	- [Introduction](#introduction)
	- [Table of Contents](#table-of-contents)
	- [Courses](#courses)
		- [Systems](#systems)
		- [Programming Languages / Compilers](#programming-languages--compilers)
		- [Algorithms](#algorithms)
		- [CS Theory](#cs-theory)
		- [Introduction to CS](#introduction-to-cs)
		- [Machine Learning](#machine-learning)
		- [Security](#security)
		- [Artificial Intelligence](#artificial-intelligence)
		- [Computer Graphics](#computer-graphics)
		- [Misc](#misc)


Courses
-------

### Systems

- [CS 168](https://inst.eecs.berkeley.edu/~cs168/fa14/) **Introduction to the Internet: Architecture and Protocols** *UC Berkeley*
    - This course is an introduction to the Internet architecture. We will focus on the concepts and fundamental design principles that have contributed to the Internet's scalability and robustness and survey the various protocols and algorithms used within this architecture. Topics include layering, addressing, intradomain routing, interdomain routing, reliable delivery, congestion control, and the core protocols (e.g., TCP, UDP, IP, DNS, and HTTP) and network technologies (e.g., Ethernet, wireless).
    - [Lecture Notes & Assignments](https://inst.eecs.berkeley.edu/~cs168/fa14/class.html)
    - [Discussion Notes](https://inst.eecs.berkeley.edu/~cs168/fa14/)

- [CS 186](https://sites.google.com/site/cs186spring2015/) **Introduction to Database Systems** *UC Berkeley*
	- In the project assignments in CS186, you will write a basic database management system called SimpleDB. For this project, you will focus on implementing the core modules required to access stored data on disk; in future projects, you will add support for various query processing operators, as well as transactions, locking, and concurrent queries.
	- [Lecture Videos](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iBVK2QzAV-R7NMA1ZkaiR2y)
	- [Lecture Notes](https://sites.google.com/site/cs186fall2013/section-notes)
	- [Projects](https://sites.google.com/site/cs186fall2013/homeworks)

- [CS 2043](http://www.cs.cornell.edu/courses/CS2043/2014sp/) **Unix Tools & Scripting** *Cornell University*
	- UNIX-like systems are increasingly being used on personal computers, mobile phones, web servers, and many other systems. They represent a wonderful family of programming environments useful both to computer scientists and to people in many other fields, such as computational biology and computational linguistics, in which data is naturally represented by strings. This course provides an intensive training to develop skills in Unix command line tools and scripting that enable the accomplishment and automation of large and challenging computing tasks. The syllabus takes students from shell basics and piping, to regular-expression processing tools, to shell scripting and Python.
	- [Syllabus](http://www.cs.cornell.edu/courses/CS2043/2014sp/)
	- [Lectures](http://www.cs.cornell.edu/courses/CS2043/2014sp/)
	- [Assignments](http://www.cs.cornell.edu/courses/CS2043/2014sp/)

- [CS 4410](http://www.cs.cornell.edu/courses/CS4410/2014fa/) **Operating Systems** *Cornell University*
	- CS 4410 covers systems programming and introductory operating system design and implementation. We will cover the basics of operating systems, namely structure, concurrency, scheduling, synchronization, memory management, filesystems, security and networking. The course is open to any undergraduate who has mastered the material in CS3410/ECE3140.
	- [Syllabus](http://www.cs.cornell.edu/courses/CS4410/2014fa/slides/01-intro.pptx)
	- [Lectures](http://www.cs.cornell.edu/courses/CS4410/2014fa/lectures.php)

- [CS 5412](http://www.cs.cornell.edu/Courses/CS5412/2014sp/) **Cloud Computing** *Cornell University*
	- Taught by one of the stalwarts of this field, Prof Ken Birman, this course has a fantastic set of slides that one can go through. The Prof's [book](http://www.amazon.com/Guide-Reliable-Distributed-Systems-High-Assurance/dp/1447124154) is also a gem and recommended as a must read in Google's tutorial on [Distributed System Design](http://www.hpcs.cs.tsukuba.ac.jp/~tatebe/lecture/h23/dsys/dsd-tutorial.html)
	- [Slides](http://www.cs.cornell.edu/Courses/CS5412/2014sp/Syllabus.htm)

- [CSCI 493.66](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/csci493.66_spr12.php) **UNIX System Programming (formerly UNIX Tools)** *CUNY Hunter College*
	- A course that is mostly about writing programs against the UNIX API, covering all of the basic parts of the kernel interface and libraries, including files, processes, terminal control, signals, and threading.

- [CSCI 493.75](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.65/csci493.65_spr14.php) **Parallel Computing** *CUNY Hunter College*
	- The course is an introduction to parallel algorithms and parallel programming in C and C++, using the Message Passing Interface (MPI) and the OpenMP application programming interface. It also includes a brief introduction to parallel architectures and interconnection networks. It is both theoretical and practical, including material on design methodology, performance analysis, and mathematical concepts, as well as details on programming using MPI and OpenMP.

- [Hack the Kernel](https://www.ops-class.org/) **Introduction to Operating Systems** *SUNY University at Buffalo, NY*
	- This course is an introduction to operating system design and implementation. We study operating systems because they are examples of mature and elegant solutions to a difficult design problem: how to safely and efficiently share system resources and provide abstractions useful to applications.
	- For the processor, memory, and disks, we discuss how the operating system allocates each resource and explore the design and implementation of related abstractions. We also establish techniques for testing and improving system performance and introduce the idea of hardware virtualization. Programming assignments provide hands-on experience with implementing core operating system components in a realistic development environment. Course by [Dr.Geoffrey Challen](https://blue.cse.buffalo.edu/people/gwa/)
	- [Syllabus](https://www.ops-class.org/courses/buffalo/CSE421_Spring2016/)
	- [Slides](https://www.ops-class.org/slides/)
	- [Video lectures](https://www.youtube.com/playlist?list=PLE6LEE8y2Jp-kbEcVR2W3vfx0Pdca0BD3)
	- [Assignments](https://www.ops-class.org/asst/0/)
	- [Old Exams](https://www.ops-class.org/exams/)

- [PODC](http://dcg.ethz.ch/lectures/podc_allstars/) **Principles of Distributed Computing** *ETH-Zurich*
	- Explore essential algorithmic ideas and lower bound techniques, basically the "pearls" of distributed computing in an easy-to-read set of lecture notes, combined with complete exercises and solutions.
	- [Book](http://dcg.ethz.ch/lectures/podc_allstars/lecture/podc.pdf)
	- [Assignments and Solutions](http://dcg.ethz.ch/lectures/podc_allstars/)
- [SPAC](http://homes.cs.washington.edu/~djg/teachingMaterials/spac/) **Parallelism and Concurrency** *Univ of Washington*
	- Technically not a course nevertheless an awesome collection of materials used by Prof Dan Grossman to teach parallelism and concurrency concepts to sophomores at UWash
- [6.824](http://css.csail.mit.edu/6.824/2014/index.html) **Distributed Systems** *MIT*
	- MIT's graduate-level DS course with a focus on fault tolerance, replication, and consistency, all taught via awesome lab assignments in Golang!
	- [Assignments](http://css.csail.mit.edu/6.824/2014/labs/) - Just do `git clone git://g.csail.mit.edu/6.824-golabs-2014 6.824`
	- [Readings](http://css.csail.mit.edu/6.824/2014/schedule.html)

- [15-213](http://www.cs.cmu.edu/~213/) **Introduction to Computer Systems (ICS)** *Carnegie-Mellon University*
	- The ICS course provides a programmer's view of how computer systems execute programs, store information, and communicate. It enables students to become more effective programmers, especially in dealing with issues of performance, portability and robustness. It also serves as a foundation for courses on compilers, networks, operating systems, and computer architecture, where a deeper understanding of systems-level issues is required. Topics covered include: machine-level code and its generation by optimizing compilers, performance evaluation and optimization, computer arithmetic, memory organization and management, networking technology and protocols, and supporting concurrent computation.
	- This is the must-have course for everyone in CMU who wants to learn some computer science no matter what major are you in. Because it's CMU (The course number is as same as the zip code of CMU)!
	- [Lecture Notes](http://www.cs.cmu.edu/~213/schedule.html)
	- [Videos](https://scs.hosted.panopto.com/Panopto/Pages/Sessions/List.aspx#folderID=%22b96d90ae-9871-4fae-91e2-b1627b43e25e%22)
	- [Assignments](http://csapp.cs.cmu.edu/public/labs.html)

- [15-319/619](http://www.cs.cmu.edu/~msakr/15619-s17/recitations.html) **Cloud Computing (ICS)** *Carnegie-Mellon University*
	- This project-based on-line course focuses on skill building across various aspects of cloud computing. We cover conceptual topics and provide hands-on experience through projects utilizing public cloud infrastructures (Amazon Web Services (AWS), Microsoft Azure and Google Cloud Platform (GCP)). The adoption of cloud computing services continues to grow across a variety of organizations and in many domains. Simply, cloud computing is the delivery of computing as a service over a network, whereby distributed resources and services are rented, rather than owned, by an end user as a utility.
	- For the projects, students will work with Amazon Web Services, Microsoft Azure and Google Cloud Platform, use them to rent and provision compute resources and then program and deploy applications that run on these resources. Students will develop and evaluate virtual machine (VM) and container scaling, elasticity and load balancing solutions. In addition, students will work with cloud storage systems and learn to develop different applications using batch, iterative and stream processing frameworks. 15-619 students will have to complete an extra project which entails designing and implementing a complete web-service solution for querying big data. For the extra project, the student teams are evaluated based on the cost and performance of their web service.
	- [Lecture Notes](http://www.cs.cmu.edu/~msakr/15619-s17/recitations.html)
	- [Videos](http://www.cs.cmu.edu/~msakr/15619-s17/recitations.html)

- [15-440](http://www.cs.cmu.edu/~dga/15-440/F12/index.html) **Distributed Systems** *Carnegie-Mellon University*
	- Introduction to distributed systems with a focus on teaching concepts via projects implemented in the Go programming language.
	- [Assignments](http://www.cs.cmu.edu/~dga/15-440/F12/assignments.html)

- [15-721](http://15721.courses.cs.cmu.edu/spring2016/) **Database Systems** *Carnegie-Mellon University*
	- This course is a comprehensive study of the internals of modern database management systems. It will cover the core concepts and fundamentals of the components that are used in both high-performance transaction processing systems (OLTP) and large-scale analytical systems (OLAP). The class will stress both efficiency and correctness of the implementation of these ideas. All class projects will be in the context of a real in-memory, multi-core database system. The course is appropriate for graduate students in software systems and for advanced undergraduates with strong systems programming skills.
	- [Assignments](http://15721.courses.cs.cmu.edu/spring2016/syllabus.html)
	- [Lecture Videos](https://www.youtube.com/playlist?list=PLSE8ODhjZXjbisIGOepfnlbfxeH7TW-8O)
	- [Readings](http://15721.courses.cs.cmu.edu/spring2016/schedule.html)
- [15-445/645](http://15445.courses.cs.cmu.edu/fall2017/) **Database Systems** *Carnegie-Mellon University*
	- This course covers fundamental topics of DBMS, compared to CMU 15-721.
	- [Assignments](http://15445.courses.cs.cmu.edu/fall2017/assignments.html)
	- [Lecture Videos](https://www.youtube.com/playlist?list=PLSE8ODhjZXjYutVzTeAds8xUt1rcmyT7x)
	- [Readings](http://15445.courses.cs.cmu.edu/fall2017/schedule.html)
- [15-749](http://www.andrew.cmu.edu/course/15-749/) **Engineering Distributed Systems** *Carnegie-Mellon University*
 	- A project focused course on Distributed Systems with an awesome list of readings
	- [Readings](http://www.andrew.cmu.edu/course/15-749/READINGS/)

--------
### Programming Languages / Compilers

- [CS 75](https://www.cs.swarthmore.edu/~jpolitz/cs75/s16/index.html) **Principles of Compiler Design** *Swathmore College*
	- Modelled after the influential paper on [incremental approach to compiler design](http://scheme2006.cs.uchicago.edu/11-ghuloum.pdf), this course teaches how to build a compiler in OCaml
	- [Course on Github](https://github.com/compilers-course-materials)
	- [Notes](https://github.com/compilers-course-materials/cs75-s16-lectures)

---

- [CIS 194](http://www.seas.upenn.edu/~cis194/) **Introduction to Haskell** *Penn Engineering*
	- Explore the joys of functional programming, using Haskell as a vehicle. The aim of the course will be to allow you to use Haskell to easily and conveniently write practical programs.
	- [Previous](http://www.seas.upenn.edu/~cis194/spring13/index.html) semester also available, with more exercises

---

- [CIS 198](http://cis198-2016s.github.io/) **Rust Programming** *UPenn*
	- This course covers what makes Rust so unique and applies it to practical systems programming problems. Topics covered include traits and generics; memory safety (move semantics, borrowing, and lifetimes); Rust’s rich macro system; closures; and concurrency.
	- [Assignments](https://github.com/cis198-2016s/homework)

---

- [Clojure](http://mooc.cs.helsinki.fi/clojure) **Functional Programming with Clojure** *University of Helsinki*
	- The course is an introduction to functional programming with a dynamically typed language Clojure. We start with an introduction to Clojure; its syntax and development environment. Clojure has a good selection of data structures and we cover most of them. We also go through the basics of recursion and higher-order functions. The course material is in English.
	- [Github Page](http://iloveponies.github.io/120-hour-epic-sax-marathon/index.html)
- [CMSC 430](http://www.cs.umd.edu/class/spring2015/cmsc430/) **Introduction to Compilers** *Univ of Maryland*
	- The goal of CMSC 430 is to arm students with the ability to design, implement, and extend a programming language. Throughout the course, students will design and implement several related languages, and will explore parsing, syntax querying, dataflow analysis, compilation to bytecode, type systems, and language interoperation.
	- [Lecture Notes](http://www.cs.umd.edu/class/spring2015/cmsc430/Schedule.html)
	- [Assignments](http://www.cs.umd.edu/class/spring2015/cmsc430/Projects.html)
- [COS 326](http://www.cs.princeton.edu/~dpw/courses/cos326-12/info.php) **Functional Programming** *Princeton University*
	- Covers functional programming concepts like closures, tail-call recursion & parallelism using the OCaml programming language
	- [Lectures](http://www.cs.princeton.edu/~dpw/courses/cos326-12/lectures.php)
	- [Assignments](http://www.cs.princeton.edu/~dpw/courses/cos326-12/assignments.php)
- [CS 143](https://web.stanford.edu/class/cs143/) **Compiler construction** *Stanford University*
	- CS143 is a Stanford's course in the practical and theoretical aspects of compiler construction.
	- [Home](https://web.stanford.edu/class/cs143/)
	- [Syllabus](https://web.stanford.edu/class/cs143/syllabus.html)
	- [Lectures](https://web.stanford.edu/class/cs143/)
	- [Assignments](https://web.stanford.edu/class/cs143/)
	- [CS143 - 2011](http://www.keithschwarz.com/cs143/WWW/sum2011/)
- [CS 164](https://sites.google.com/a/bodik.org/cs164/home) **Hack your language!** *UC Berkeley*
	- Introduction to programming languages by designing and implementing domain-specific languages.
	- [Lecture Videos](https://archive.org/details/ucberkeley-webcast-PL3A16CFC42CA6EF4F)
	- [Code for Assignments](https://bitbucket.org/cs164_overlord/)
- [CS 173](http://cs.brown.edu/courses/cs173/2014/) **Programming Languages** *Brown University*
	- Course by Prof. Krishnamurthi (author of [HtDP](http://htdp.org/2003-09-26/Book/)) and numerous other [awesome](http://cs.brown.edu/courses/cs173/2012/book/) [books](http://papl.cs.brown.edu/2014/index.html) on programming languages. Uses a custom designed [Pyret](http://www.pyret.org/) programming language to teach the concepts. There was an [online class](http://cs.brown.edu/courses/cs173/2012/OnLine/) hosted in 2012, which includes all lecture videos for you to enjoy.
	- [Videos](http://cs.brown.edu/courses/cs173/2012/Videos/)
	- [Assignments](http://cs.brown.edu/courses/cs173/2014/assignments.html)
- [CS 223](https://www.classes.cs.uchicago.edu/archive/2016/winter/22300-1/) **Purely Functional Data Structures In Elm** *University of Chicago*
	- This course teaches functional reactive programming and purely functional data structures based on Chris Okazaki's book and using the Elm programming language.
	- [Lectures](https://www.classes.cs.uchicago.edu/archive/2015/winter/22300-1/Schedule.html)
	- [Assignments](https://www.classes.cs.uchicago.edu/archive/2015/winter/22300-1/Schedule.html)
- [CS 240h](http://www.scs.stanford.edu/14sp-cs240h/) **Functional Systems in Haskell** *Stanford University*
	- Building software systems in Haskell
	- [Lecture Slides](http://www.scs.stanford.edu/14sp-cs240h/slides/)
	- 3 Assignments: [Lab1](http://www.scs.stanford.edu/14sp-cs240h/labs/lab1.html), [Lab2](http://www.scs.stanford.edu/14sp-cs240h/labs/lab2.html), [Lab3](http://www.scs.stanford.edu/14sp-cs240h/labs/lab3.html)
- [CS 421](https://courses.engr.illinois.edu/cs421/fa2014/) **Programming Languages and Compilers** *Univ of Illinois, Urbana-Champaign*
 Course that uses OCaml to teach functional programming and programming language design.
	- [Lectures](https://courses.engr.illinois.edu/cs421/fa2014/lectures/index.html)
	- [Videos](http://recordings.engineering.illinois.edu/ess/portal/section/631edaeb-2a33-4537-b7c8-0c1cba783a4f)
	- [Assignments](https://courses.engr.illinois.edu/cs421/fa2014/mps/index.html)
	- [Exams](https://courses.engr.illinois.edu/cs421/fa2014/exams/index.html)
- [CS 3110](http://www.cs.cornell.edu/Courses/cs3110/2014fa/course_info.php) **Data Structures and Functional Programming** *Cornell University*
	- Another course that uses OCaml to teach alternative programming paradigms, especially functional and concurrent programming.
	- [Lecture Slides](http://www.cs.cornell.edu/Courses/cs3110/2014fa/lecture_notes.php)
	- [Assignments](http://www.cs.cornell.edu/Courses/cs3110/2014fa/)
- [CS 4120](http://www.cs.cornell.edu/courses/CS4120/2013fa/) **Introduction to Compilers** *Cornell University*
	- An introduction to the specification and implementation of modern compilers. Topics covered include lexical scanning, parsing, type checking, code generation and translation, an introduction to optimization, and compile-time and run-time support for modern programming languages.  As part of the course, students build a working compiler for an object-oriented language.
	- [Syllabus](http://www.cs.cornell.edu/courses/CS4120/2013fa/overview.html)
	- [Lectures](http://www.cs.cornell.edu/courses/CS4120/2013fa/schedule.html)
	- [Assignments](http://www.cs.cornell.edu/courses/CS4120/2013fa/homework.html)
- [CS 4400](https://pl.barzilay.org/) **Programming Languages** *Northeastern University*
	- This is a course on the study, design, and implementation of programming languages.
	- The course works at two simultaneous levels: first, we will use a programming language that can demonstrate a wide variety of programming paradigms. Second, using this language, we will learn about the mechanics behind programming languages by implementing our own language(s). The two level approach usually means that we will often see how to use a certain feature, and continue by implementing it.
	- [Syllabus](https://pl.barzilay.org/syllabus.html)
	- [Lecture Notes/Resources](https://pl.barzilay.org/resources.html)
- [CS 4610](http://www.cs.virginia.edu/~weimer/4610/) **Programming Languages and Compilers** *University of Virginia*
	- Course that uses OCaml to teach functional programming and programming language design. Each assignment is a part of an interpreter and compiler for an object-oriented language similar to Java, and you are required to use a different language for each assignment (i.e., choose 4 from Python, JS, OCaml, Haskell, Ruby).
	- [Lecture Notes](http://www.cs.virginia.edu/~weimer/4610/lectures.html)
	- [Assignments](http://www.cs.virginia.edu/~weimer/4610/pa.html)
- [CS 5114](http://www.cs.cornell.edu/courses/CS5114/2013sp/index.php) **Network Programming Languages** *Cornell University*
	- This course provides an introduction to the languages used to program computer networks. It will examine recent proposals based on logic, functional, and distributed languages, as well as tools for establishing correctness using automatic solvers, model checkers, and proof assistants.
	- [Syllabus](http://www.cs.cornell.edu/courses/CS5114/2013sp/syllabus.php)
	- [Lectures](http://www.cs.cornell.edu/courses/CS5114/2013sp/syllabus.php)
- [CS 5142](http://www.cs.cornell.edu/courses/CS5142/2013fa/) **Scripting Languages** *Cornell University*
	- Perl, PHP, JavaScript, VisualBasic -- they are often-requested skills for employment, but most of us do not have the time to find out what they are all about. In this course, you learn how to use scripting languages for rapid prototyping, web programming, data processing, and application extension. Besides covering traditional programming languages concepts as they apply to scripting (e.g., dynamic typing and scoping), this course looks at new concepts rarely found in traditional languages (e.g., string interpolation, hashes, and polylingual code). Through a series of small projects, you use different languages to achieve programming tasks that highlight the strengths and weaknesses of scripting. As a side effect, you practice teaching yourself new languages.
	- [Syllabus](http://www.cs.cornell.edu/courses/CS5142/2013fa/)
	- [Lectures](http://www.cs.cornell.edu/courses/CS5142/2013fa/#schedule)
	- [Assignments](http://www.cs.cornell.edu/courses/CS5142/2013fa/#schedule)
- [CS 5470](http://matt.might.net/teaching/compilers/spring-2015/) **Compilers** *University of Utah*
	- If you're a fan of Prof Matt's writing on his [fantastic blog](http://matt.might.net/articles/) you ought to give this a shot. The course covers the design and implementation of compilers, and it explores related topics such as interpreters, virtual machines and runtime systems. Aside from the Prof's witty take on [cheating](http://matt.might.net/teaching/compilers/spring-2015/#collaboration) the page has tons of interesting links on programming languages, parsing and compilers.
	- [Lecture Notes](https://www.dropbox.com/sh/zanwtoflw4pcfu8/5pdT6axS3y)
	- [Projects](http://matt.might.net/teaching/compilers/spring-2015/#projects)
- [CS 6118](http://www.cs.cornell.edu/courses/CS6118/2012fa/) **Types and Semantics** *Cornell University*
	- Types and Semantics is about designing and understand programming languages, whether they be domain specific or general purpose. The goal of this class is to provide a variety of tools for designing custom (programming) languages for whatever task is at hand. Part of that will be a variety of insights on how languages work along with experiences from working with academics and industry on creating new languages such as Ceylon and Kotlin. The class focuses on types and semantics and the interplay between them. This means category theory and constructive type theory (e.g. Coq and richer variations) are ancillary topics of the class. The class also covers unconventional semantic domains such as classical linear type theory in order to both break students from conventional thinking and to provide powerful targets capable of formalizing thinks like networking protocols, resource-sensitive computation, and concurrency constructs. The class project is to design and formalize a (programming) language for a purpose of the student's choosing, and assignments are designed to ensure students have had a chance to practice applying the techniques learned in class before culminating these skills in the class project.
	- [Syllabus](http://www.cs.cornell.edu/courses/CS6118/2012fa/)
	- [Lectures](http://www.cs.cornell.edu/courses/CS6118/2012fa/)
- [CSC 253](http://pgbovine.net/cpython-internals.htm) **CPython internals: A ten-hour codewalk through the Python interpreter source code** *University of Rochester*
  - Nine lectures walking through the internals of CPython, the canonical Python interpreter implemented in C. They were from the *Dynamic Languages and Software Development* course taught in Fall 2014 at the University of Rochester.
- [CSE 341](http://courses.cs.washington.edu/courses/cse341/16sp/) **Programming Languages** *University of Washington*
	- Covers non-imperative paradigms and languages such as Ruby, Racket, and ML and the fundamentals of programming languages.
	- [Lectures and Videos](https://courses.cs.washington.edu/courses/cse341/16sp/#lectures)
	- [Assignments and Tests](https://courses.cs.washington.edu/courses/cse341/16sp/#homeworks)
- [CSE P 501](http://courses.cs.washington.edu/courses/csep501/09au/lectures/video.html) **Compiler Construction** *University of Washington*
	- Teaches understanding of how a modern compiler is structured and the major algorithms that are used to translate code from high-level to machine language. The best way to do this is to actually build a working compiler, so there will be a significant project to implement one that translates programs written in a core subset of Java into executable x86 assembly language. The compilers themselves will use scanner and parser generator tools and the default implementation language is Java.
	- [Lectures](http://courses.cs.washington.edu/courses/csep501/09au/lectures/video.html)
	- [Assignments, Tests, and Solutions](http://courses.cs.washington.edu/courses/csep501/09au/homework/index.html)
- [DMFP](http://cs.wheaton.edu/~tvandrun/dmfp/) **Discrete Mathematics and Functional Programming** *Wheaton College*
  - A course that teaches discrete maths concepts with functional programming
  - [Lecture Videos](http://cs.wheaton.edu/~tvandrun/dmfp/)
  - [Assignments](http://cs.wheaton.edu/~tvandrun/dmfp/source.html)
- [PCPP](http://www.itu.dk/people/sestoft/itu/PCPP/E2015/) **Practical Concurrent and Parallel Programming** *IT University of Copenhagen*
  - In this MSc course you learn how to write correct and efficient concurrent and parallel software, primarily using Java, on standard shared-memory multicore hardware.
  - The course covers basic mechanisms such as threads, locks and shared memory as well as more advanced mechanisms such as parallel streams for bulk data, transactional memory, message passing, and lock-free data structures with compare-and-swap.
  - It covers concepts such as atomicity, safety, liveness and deadlock.
  - It covers how to measure and understand performance and scalability of parallel programs.
  - It covers tools and methods to find bugs in concurrent programs.
- [6.945](https://groups.csail.mit.edu/mac/users/gjs/6.945/index.html) **Adventures in Advanced Symbolic Programming** *MIT*
	- Taught by Gerald Sussman of SICP fame, this class deals with concepts and techniques for the design an implementation of large software systems that can be adapted to uses not anticipated by the designer. Applications include compilers, computer-algebra systems, deductive systems, and some artificial intelligence applications.
	- [Assignments](https://groups.csail.mit.edu/mac/users/gjs/6.945/assignments.html): Extensive programming assignments, using MIT/GNU Scheme. Students should have significant programming experience in Scheme, Common Lisp, Haskell, CAML or other "functional" language.
	- [Readings](https://groups.csail.mit.edu/mac/users/gjs/6.945/readings/)
- [CS 696](http://www.eli.sdsu.edu/courses/fall15/cs696/index.html) **Functional Design and Programming** *San Diego State University*
	- Covers functional programming basis using Clojure.
	- Topics include testing, functional programming, immutable collections and concurrency.
	- Also includes assignments covering Clojurescript, [Reagent](Reagent Github) etc.
- [L28](https://www.cl.cam.ac.uk/teaching/1516/L28/) **Advanced Functional Programming** *University of Cambridge*
	- This module aims to teach students how to use the features of modern typed functional programming languages (e.g. OCaml, Haskell) to design and implement libraries and DSLs. It aims to demonstrate how such techniques can improve both correctness and efficiency. Students wishing to take the module should have some experience of a typed functional programming language and an understanding of type inference.
	- This particular session was taught by a prominent OCaml programmer, open Source contributor & author of real world OCaml - Dr Anil Madhavapeddy.

-------

### Algorithms

- [CS 61B](http://datastructur.es/sp16/) **Data Structures** *UC Berkeley*
	- In this course, you will study advanced programming techniques including data structures, encapsulation, abstract data types, interfaces, and algorithms for sorting and searching, and you will get a taste of “software engineering”—the design and implementation of large programs.
	- [Full Lecture Materials](http://datastructur.es/sp16/) Lecture of Spring 2016. This website contains full matrials including video links, labs, homeworks, projects. Very good for self-learner. Also a good start for Java. And it includes some other useful resources for Java Documentation, Data Structure Resources, Git/GitHub and Java Development Resources. [Resources](http://datastructur.es/sp16/resources.html)
	- [Labs](http://www.cs.berkeley.edu/~jrs/61b/lab/index.html) The link to labs and projects is included in the website.
	- [Lecture Videos](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iC2Khb1B5NnbE7SHPQ1-W17)

- [CS 224](http://people.seas.harvard.edu/~minilek/cs224/fall14/index.html) **Advanced Algorithms** *Harvard University*
	- CS 224 is an advanced course in algorithm design, and topics we will cover include the word RAM model, data structures, amortization, online algorithms, linear programming, semidefinite programming, approximation algorithms, hashing, randomized algorithms, fast exponential time algorithms, graph algorithms, and computational geometry.
	- [Lecture Videos](http://people.seas.harvard.edu/~minilek/cs224/fall14/lec.html) ([Youtube](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uP4rJgf5ayhHWgw7akUWSf))
	- [Assignments](http://people.seas.harvard.edu/~minilek/cs224/fall14/hmwk.html)
- [CS 261](http://theory.stanford.edu/~tim/w16/w16.html) **A Second Course in Algorithms** *Stanford University*
	- Algorithms for network optimization: max-flow, min-cost flow, matching, assignment, and min-cut problems. Introduction to linear programming. Use of LP duality for design and analysis of algorithms. Approximation algorithms for NP-complete problems such as Steiner Trees, Traveling Salesman, and scheduling problems. Randomized algorithms. Introduction to online algorithms.
	- [Lecture Notes, Videos & Assignments](http://theory.stanford.edu/~tim/w16/w16.html) ([Youtube](https://www.youtube.com/playlist?list=PLEGCF-WLh2RJh2yDxlJJjnKswWdoO8gAc))
- [CS 473/573](http://web.engr.illinois.edu/~jeffe/teaching/algorithms/) **Fundamental Algorithms** *Univ of Illinois, Urbana-Champaign*
	- Algorithms class covering recursion, randomization, amortization, graph algorithms, network flows and hardness. The lecture notes by Prof. Erikson are comprehensive enough to be a book by themselves. Highly recommended!
	- [Lecture Notes](http://web.engr.illinois.edu/~jeffe/teaching/algorithms/all-algorithms.pdf)
	- [Labs and Exams](http://web.engr.illinois.edu/~jeffe/teaching/algorithms/all-hwex.pdf)
- [CS 2150](https://github.com/aaronbloomfield/pdr) **Program & Data Representation** *University of Virginia*
	- This data structures course introduces C++, linked-lists, stacks, queues, trees, numerical representation, hash tables, priority queues, heaps, huffman coding, graphs, and x86 assembly.
	- [Lectures](http://aaronbloomfield.github.io/pdr/slides/)
	- [Assignments](http://aaronbloomfield.github.io/pdr/labs/)
- [CS 4820](http://www.cs.cornell.edu/courses/CS4820/2015sp/) **Introduction to Analysis of Algorithms** *Cornell University*
	-  This course develops techniques used in the design and analysis of algorithms, with an emphasis on problems arising in computing applications. Example applications are drawn from systems and networks, artificial intelligence, computer vision, data mining, and computational biology. This course covers four major algorithm design techniques (greedy algorithms, divide and conquer, dynamic programming, and network flow), computability theory focusing on undecidability, computational complexity focusing on NP-completeness, and algorithmic techniques for intractable problems, including identification of structured special cases, approximation algorithms, and local search heuristics.
	- [Lectures](http://www.cs.cornell.edu/courses/CS4820/2015sp/lectures/)
	- [Syllabus](http://www.cs.cornell.edu/courses/CS4820/2015sp/syllabus/)
- [CSCI 104](http://www-scf.usc.edu/~csci104/20142/lectures/) **Data Structures and Object Oriented Design**   *University of Southern California (USC)*
	- [Lectures](http://www-scf.usc.edu/~csci104/20142/lectures)
	- [Labs](http://www-scf.usc.edu/~csci104/20142/labs)
	- [Assignments](http://www-scf.usc.edu/~csci104/20142/assignments/)
	- [Additional Resources](http://www-scf.usc.edu/~csci104/20142/resources.html)
- [CSCI 135](http://compsci.hunter.cuny.edu/~sweiss/courses/csci135.php) **Software Design and Analysis I**
*CUNY Hunter College*
	- It is currently an intensive introduction to program development and problem solving. Its emphasis is on the process of designing, implementing, and evaluating small-scale programs. It is not supposed to be a C++ programming course, although much of the course is spent on the details of C++. C++ is an extremely large and complex programming language with many features that interact in unexpected ways. One does not need to know even half of the language to use it well.
	- [Lectures and Assignments](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci135/csci135_36_fall12.php)
- [CSCI 235](http://compsci.hunter.cuny.edu/~sweiss/courses/csci235.php) **Software Design and Analysis II** *CUNY Hunter College*
	- Introduces algorithms for a few common problems such as sorting. Practically speaking, it furthers the students' programming skills with topics such as recursion, pointers, and exception handling, and provides a chance to improve software engineering skills and to give the students practical experience for more productive programming.
	- [Lectures and Assignments](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci235/csci235_f14.php)
- [CSCI 335](http://compsci.hunter.cuny.edu/~sweiss/courses/csci335.php) **Software Design and Analysis III**
*CUNY Hunter College*
	- This includes the introduction of hashes, heaps, various forms of trees, and graphs. It also revisits recursion and the sorting problem from a higher perspective than was presented in the prequels. On top of this, it is intended to introduce methods of algorithmic analysis.
	- [Lectures and Assignments](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci335/csci335_s14.php)
- [CSE 331](http://courses.cs.washington.edu/courses/cse331/15sp/) **Software Design and Implementation** *University of Washington*
	- Explores concepts and techniques for design and construction of reliable and maintainable software systems in modern high-level languages; program structure and design; program-correctness approaches, including testing.
	- [Lectures, Assignments, and Exams](http://courses.cs.washington.edu/courses/cse331/15sp/#all)
- [CSE 373](http://www3.cs.stonybrook.edu/~skiena/373/) **Analysis of Algorithms** *Stony Brook University*
	- Prof Steven Skiena's no stranger to any student when it comes to algorithms. His seminal [book](http://www.algorist.com/) has been touted by many to be best for [getting that job in Google](http://steve-yegge.blogspot.com/2008/03/get-that-job-at-google.html). In addition, he's also well-known for tutoring students in competitive [programming competitions](http://www.programming-challenges.com/pg.php?page=index). If you're looking to brush up your knowledge on Algorithms, you can't go wrong with this course.
	- [Lecture Videos](http://www.cs.sunysb.edu/~algorith/video-lectures/)
- [ECS 122A](http://web.cs.ucdavis.edu/~gusfield/cs122f10/) **Algorithm Design and Analysis** *UC Davis*
	- Taught by [Dan Gusfield](http://web.cs.ucdavis.edu/~gusfield/) in 2010, this course is an undergraduate introduction to algorithm design and analysis. It features traditional topics, such as Big Oh notation, as well as an importance on implementing specific algorithms. Also featured are sorting (in linear time), graph algorithms, depth-first search, string matching, dynamic programming, NP-completeness, approximation, and randomization.
	- [Syllabus](http://web.cs.ucdavis.edu/~gusfield/cs122f10/syll122.pdf)
	- [Lecture Videos](http://web.cs.ucdavis.edu/~gusfield/cs122f10/videolist.html)
	- [Assignments](http://web.cs.ucdavis.edu/~gusfield/cs122f10/)
- [ECS 222A](http://web.cs.ucdavis.edu/~gusfield/cs222w11/) **Graduate Level Algorithm Design and Analysis** *UC Davis*
	- This is the graduate level complement to the ECS 122A undergraduate algorithms course by [Dan Gusfield](http://web.cs.ucdavis.edu/~gusfield/) in 2011. It assumes an undergrad course has already been taken in algorithms, and, while going over some undergraduate algorithms topics, focuses more on increasingly complex and advanced algorithms.
	- [Lecture Videos](http://web.cs.ucdavis.edu/~gusfield/cs222f07/videolist.html)
	- [Syllabus](http://web.cs.ucdavis.edu/~gusfield/cs222w11/syll11.pdf)
	- [Assignments](http://web.cs.ucdavis.edu/~gusfield/cs222w11/)
- [6.INT](http://courses.csail.mit.edu/iap/interview/index.php) **Hacking a Google Interview** *MIT*
	- This course taught in the MIT Independent Activities Period in 2009 goes over common solution to common interview questions for software engineer interviews at highly selective companies like Apple, Google, and Facebook. They cover time complexity, hash tables, binary search trees, and other common algorithm topics you should have already covered in a different course, but goes more in depth on things you wouldn't otherwise learn in class- like bitwise logic and problem solving tricks.
	- [Handouts](http://courses.csail.mit.edu/iap/interview/materials.php)
	- [Topics Covered](http://courses.csail.mit.edu/iap/interview/calendar.php)
- [6.006](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/index.htm) **Introduction to Algorithms** *MIT*
	- This course provides an introduction to mathematical modeling of computational problems. It covers the common algorithms, algorithmic paradigms, and data structures used to solve these problems. The course emphasizes the relationship between algorithms and programming, and introduces basic performance measures and analysis techniques for these problems.
	- [Lecture Videos](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/lecture-videos/)
 	- [Assignments](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/assignments/)
	- [Readings](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/readings/)
	- [Resources](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/download-course-materials/)
	- [Old Exams](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/exams/)
- [6.046J/18.410J](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2015/index.htm) **Design and Analysis of Algorithms** *MIT*
	- This is an intermediate algorithms course with an emphasis on teaching techniques for the design and analysis of efficient algorithms, emphasizing methods of application. Topics include divide-and-conquer, randomization, dynamic programming, greedy algorithms, incremental improvement, complexity, and cryptography. This course assumes that students know how to analyze simple algorithms and data structures from having taken [6.006](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/). It introduces students to the design of computer algorithms, as well as analysis of sophisticated algorithms.
	- [Lecture Videos](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2015/lecture-videos/)
 	- [Lecture Notes](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2015/lecture-notes/)
	- [Assignments](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2015/assignments/)
	- [Resources](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2015/download-course-materials/)
	- [Old Exams](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2015/exams/)
- [6.851](http://courses.csail.mit.edu/6.851/spring14/index.html) **Advanced Data Structures** *MIT*
	- This is an advanced DS course, you must be done with the [Advanced Algorithms](http://courses.csail.mit.edu/6.854/current/) course before attempting this one.
	- [Lectures](http://courses.csail.mit.edu/6.851/spring14/lectures/) Contains videos from sp2012 version, but there isn't much difference.
	- [Assignments](http://courses.csail.mit.edu/6.851/spring14/hmwk.html) contains the calendar as well.
- [6.854/18.415J](http://courses.csail.mit.edu/6.854/current/) **Advanced Algorithms** *MIT*
	- Advanced course in algorithms by Dr. David Karger covering topics such as amortization, randomization, fingerprinting, word-level parallelism, bit scaling, dynamic programming, network flow, linear programming, fixed-parameter algorithms, and approximation algorithms.
	- **Register** on [NB](http://nb.mit.edu/subscribe?key=D3a8CYpoO2VcR1ZcfaxmR5KbyjCGXd3INNXvL3mxEakYJ7qGJw) to access the [problem set and lectures](http://nb.mit.edu/).

- [15-451/651](http://www.cs.cmu.edu/afs/cs/academic/class/15451-f10/www/) **Algorithms** *Carnegie Mellon University*
	- The required algorithms class that go in depth into all basic algorithms and the proofs behind them. This is one of the heavier algorithms curriculums on this page. Taught by Avrim Blum and [Manuel Blum](http://en.wikipedia.org/wiki/Manuel_Blum) who has a Turing Award due to his contributions to algorithms. Course link includes a very comprehensive set of reference notes by Avrim Blum.
- [16s-4102](http://www.cs.virginia.edu/~shelat/16s-4102/) **Algorithms** *University of Virginia*
	- [Lecture Videos & Homeworks](http://www.cs.virginia.edu/~shelat/16s-4102/) ([Youtube](https://www.youtube.com/channel/UCxXYk53cSZof2bR_Ax0uJYQ/videos))

-------

### CS Theory

- [CIS 500](http://www.seas.upenn.edu/~cis500/cis500-f14/index.html) **Software Foundations** *University of Pennsylvania*
	- An introduction to formal verification of software using the Coq proof assistant. Topics include basic concepts of logic, computer-assisted theorem proving, functional programming, operational semantics, Hoare logic, and static type systems.
	- [Lectures and Assignments](http://www.seas.upenn.edu/~cis500/cis500-f14/index.html#schedule)
	- [Textbook](http://www.cis.upenn.edu/~bcpierce/sf/current/index.html)
- [CS 103](http://web.stanford.edu/class/cs103/) **Mathematical Foundations of Computing** *Stanford University*
	-  CS103 is a first course in discrete math, computability theory, and complexity theory. In this course, we'll probe the limits of computer power, explore why some problems are harder to solve than others, and see how to reason with mathematical certainty.
	-  Links to all lectures notes and assignments are directly on the course page

- [CS 276](http://www.cs.berkeley.edu/~sanjamg/classes/cs276-fall14/) **Foundations of Cryptography** *UC Berkeley*
	- This course discusses the complexity-theory foundations of modern cryptography, and looks at recent results in the field such as Fully Homomorphic Encryption, Indistinguishability Obfuscation, MPC and so on.

- [CS 3110](http://www.cs.cornell.edu/courses/CS3110/2014fa/) **Data Structures and Functional Programming** *Cornell University*
	- CS 3110 (formerly CS 312) is the third programming course in the Computer Science curriculum, following CS 1110/1112 and CS 2110. The goal of the course is to help students become excellent programmers and software designers who can design and implement software that is elegant, efficient, and correct, and whose code can be maintained and reused.
	- [Syllabus](http://www.cs.cornell.edu/courses/CS3110/2014fa/course_info.php)
	- [Lectures](http://www.cs.cornell.edu/courses/CS3110/2014fa/lecture_notes.php)
	- [Assignments](http://www.cs.cornell.edu/courses/CS3110/2014fa/index.php)

- [CS 4300](http://www.cs.cornell.edu/courses/CS4300/2013fa/) **Information Retrieval** *Cornell University*
	- Studies the methods used to search for and discover information in large-scale systems. The emphasis is on information retrieval applied to textual materials, but there is some discussion of other formats.The course includes techniques for searching, browsing, and filtering information and the use of classification systems and thesauruses. The techniques are illustrated with examples from web searching and digital libraries.
	- [Syllabus](http://www.cs.cornell.edu/courses/CS4300/2013fa/lectures/introduction.pdf)
	- [Lectures](http://www.cs.cornell.edu/courses/CS4300/2013fa/lectures.htm)
	- [Assignments](http://www.cs.cornell.edu/courses/CS4300/2013fa/lectures.htm)
- [CS 4810](http://www.cs.cornell.edu/~dsteurer/toc13/) **Introduction to Theory of Computing** *Cornell University*
	-  This undergraduate course provides a broad introduction to the mathematical foundations of computer science. We will examine basic computational models, especially Turing machines. The goal is to understand what problems can or cannot be solved in these models.
	- [Syllabus](http://www.cs.cornell.edu/~dsteurer/toc13/syllabus/)
	- [Lectures](http://www.cs.cornell.edu/~dsteurer/toc13/lectures/)
	- [Assignments](http://www.cs.cornell.edu/~dsteurer/toc13/homework/)
- [CS 6810](https://complexity16.dsteurer.org/) **Theory of Computing** *Cornell University*
	-  This graduate course gives a broad introduction to complexity theory, including classical results and recent developments. Complexity theory aims to understand the power of efficient computation (when computational resources like time and space are limited). Many compelling conceptual questions arise in this context. Most of these questions are (surprisingly?) difficult and far from being resolved. Nevertheless, a lot of progress has been made toward understanding them (and also why they are difficult). We will learn about these advances in this course. A theme will be combinatorial constructions with random-like properties, e.g., expander graphs and error-correcting codes. Some examples:
		-  Is finding a solution inherently more difficult than verifying it?
		-  Do more computational resources mean more computing power?
		-  Is it easier to find approximate solutions than exact ones?
		-  Are randomized algorithms more powerful than deterministic ones?
		-  Is it easier to solve problems in the average case than in the worst case?
		-  Are quantum computers more powerful than classical ones?
	- [Syllabus](https://complexity16.dsteurer.org/syllabus/)
	- [Lectures](https://complexity16.dsteurer.org/lectures/)
	- [Assignments](https://complexity16.dsteurer.org/homework/)
- [CSCE 3193](http://www.csce.uark.edu/~sgauch/3193/S11/index.html) **Programming Paradigms** *University of Arkansas (Fayetteville)*
	- Programming in different paradigms with emphasis on object oriented programming, network programming and functional programming. Survey of programming languages, event driven programming, concurrency, software validation.
	- [Syllabus](http://www.csce.uark.edu/~sgauch/3193/S11/syllabus.html)
	- [Notes](http://www.csce.uark.edu/~sgauch/3193/S11/notes/index.html)
	- [Assignments](http://www.csce.uark.edu/~sgauch/3193/S11/hw/index.html)
	- [Practice Exams](http://www.csce.uark.edu/~sgauch/3193/S11/exams/index.html)


-------

### Introduction to CS


- [CS 50](https://cs50.harvard.edu/) **Introduction to Computer Science** *Harvard University*
	- CS50x is Harvard College's introduction to the intellectual enterprises of computer science and the art of programming for majors and non-majors alike, with or without prior programming experience. An entry-level course taught by David J. Malan.
	- [Lectures](http://cs50.tv/2017/fall/#about,lectures)
	- [Problem Sets](http://cs50.tv/2017/fall/#about,psets)
	- The course can also be taken from [edX](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x).
	- The course's OpenCourseware resides [here](http://cs50.tv)

- [CS 101](http://online.stanford.edu/course/computer-science-101-self-paced) **Computer Science 101** *Stanford University*
	- CS101 teaches the essential ideas of Computer Science for a zero-prior-experience audience. Participants play and experiment with short bits of "computer code" to bring to life to the power and limitations of computers.
	- Lectures videos will available for free after registration.
- [CS 106A](https://see.stanford.edu/Course/CS106A) **Programming Methodology** *Stanford University*
	- This course is the largest of the introductory programming courses and is one of the largest courses at Stanford. Topics focus on the introduction to the engineering of computer applications emphasizing modern software engineering principles: object-oriented design, decomposition, encapsulation, abstraction, and testing. Programming Methodology teaches the widely-used Java programming language along with good software engineering principles.
	- [Lecture Videos](https://see.stanford.edu/Course/CS106A)
	- [Assignments](https://see.stanford.edu/Course/CS106A)
	- [All materials in a zip file](http://see.stanford.edu/materials/icspmcs106a/ProgrammingMethodologyAllMaterials.zip)
- [CS 106B](https://see.stanford.edu/Course/CS106B) **Programming Abstractions** *Stanford University*
	- This course is the natural successor to Programming Methodology and covers such advanced programming topics as recursion, algorithmic analysis, and data abstraction using the C++ programming language, which is similar to both C and Java.
	- [Lectures](https://see.stanford.edu/Course/CS106B)
	- [Assignments](https://see.stanford.edu/Course/CS106B)
	- [All materials in a zip file](http://see.stanford.edu/materials/icspacs106b/ProgrammingAbstractionsAllMaterials.zip)
- [CS 107](https://see.stanford.edu/Course/CS107) **Programming Paradigms** *Stanford University*
	- Topics: Advanced memory management features of C and C++; the differences between imperative and object-oriented paradigms. The functional paradigm (using LISP) and concurrent programming (using C and C++)
	- [Lectures](https://see.stanford.edu/Course/CS107)
	- [Assignments](https://see.stanford.edu/Course/CS107)



- [CS 1133](http://www.cs.cornell.edu/courses/CS1133/2013fa/) **Transition to Python** *Cornell University*
	- Introduction to the Python programming language. Covers the basic programming constructs of Python, including assignment, conditionals, iteration, functions, object-oriented design, arrays, and vectorized computation. Assumes programming knowledge in a language like Java, Matlab, C, C++, or Fortran.
	- [Syllabus](http://www.cs.cornell.edu/courses/CS1133/2013fa/about/overview.php)
	- [Lectures](http://www.cs.cornell.edu/courses/CS1133/2013fa/lectures/index.php)
	- [Assignments](http://www.cs.cornell.edu/courses/CS1133/2013fa/assignments/index.php)
- [CS 1410-2](http://www.eng.utah.edu/~cs1410-20/) and [CS2420-20](http://www.eng.utah.edu/~cs2420-20/) **Computer Science I and II for Hackers** *University of Utah*
	- An intro course in the spirit of SICP designed by [Professor Matthew Flatt](http://www.cs.utah.edu/~mflatt/) (one of the lead designers of Racket and author of HtDP). Mostly Racket and C, and a bit of Java, with explanations on how high level functional programming concepts relate to the design of OOP programs. Do this one before SICP if SICP is a bit too much...
	- [Lectures and Assignments 1](http://www.eng.utah.edu/~cs1410-20/schedule.html)
	- [Lectures and Assignments 2](http://www.eng.utah.edu/~cs2420-20/schedule.html)
	- [Textbook](http://htdp.org/2003-09-26/Book/curriculum.html)
	- [Racket Language](http://racket-lang.org/)

- [CSCE 2004](http://www.csce.uark.edu/~sgauch/2004/S14/index.html) **Programming Foundations I** *University of Arkansas (Fayetteville)*
	- Introductory course for students majoring in computer science or computer engineering. Software development process: problem specification, program design, implementation, testing and documentation. Programming topics: data representation, conditional and iterative statements, functions, arrays, strings, file I/O, and classes. Using C++ in a UNIX environment.
	- [Syllabus](http://www.csce.uark.edu/~sgauch/2004/S14/syllabus.html)
	- [Notes](http://www.csce.uark.edu/~sgauch/2004/S14/notes/index.html)
	- [Assignments](http://www.csce.uark.edu/~sgauch/2004/S14/hw/index.html)
	- [Practice Exams](http://www.csce.uark.edu/~sgauch/2004/S14/index.html)
- [CSCI E-1](http://cse1.net/lectures) **Understanding Computers and the Internet** *Harvard University Extension College*

	- This course is all about understanding: understanding what's going on inside your computer when you flip on the switch, why tech support has you constantly rebooting your computer, how everything you do on the Internet can be watched by others, and how your computer can become infected with a worm just by being turned on. Designed for students who use computers and the Internet every day but don't fully understand how it all works, this course fills in the gaps. Through lectures on hardware, software, the Internet, multimedia, security, privacy, website development, programming, and more, this course "takes the hood off" of computers and the Internet so that students understand how it all works and why. Through discussions of current events, students are exposed also to the latest technologies.
	- [Lecture Videos](http://cse1.net/lectures)
	- [Syllabus](http://cse1.net/syllabus)
	- [Notes / Recaps](http://cse1.net/recaps)
	- [Assignments](http://cse1.net/psets)
- [CS-for-all](http://www.cs.hmc.edu/csforall/) **CS for All**  *Harvey Mudd College*
	- This book (and course) takes a unique approach to “Intro CS.” In a nutshell, our objective is to provide an introduction to computer science as an intellectually rich and vibrant field rather than focusing exclusively on computer programming. While programming is certainly an important and pervasive element of our approach, we emphasize concepts and problem-solving over syntax and programming language features.
	- [Lectures and Other resources](https://www.cs.hmc.edu/twiki/bin/view/ModularCS1)



-------

### Machine Learning

- [DEEPNLP](https://github.com/oxford-cs-deepnlp-2017/) **Deep Learning for Natural Language Processing** *University of Oxford*
	- This is an applied course focussing on recent advances in analysing and generating speech and text using recurrent neural networks. We introduce the mathematical definitions of the relevant machine learning models and derive their associated optimisation algorithms. The course covers a range of applications of neural networks in NLP including analysing latent dimensions in text, transcribing speech to text, translating between languages, and answering questions. This course is organised by Phil Blunsom and delivered in partnership with the **DeepMind Natural Language Research Group**.
	- [Lectures](https://github.com/oxford-cs-deepnlp-2017/lectures)
	- Assignments are available on the organisation page titled as "practicals"
- [CS20si](http://web.stanford.edu/class/cs20si/index.html) **Tensorflow for Deep Learning Research** *Stanford University*
	- This course will cover the fundamentals and contemporary usage of the Tensorflow library for deep learning research. We aim to help students understand the graphical computational model of Tensorflow, explore the functions it has to offer, and learn how to build and structure models best suited for a deep learning project. Through the course, students will use Tensorflow to build models of different complexity, from simple linear/logistic regression to convolutional neural network and recurrent neural networks with LSTM to solve tasks such as word embeddings, translation, optical character recognition. Students will also learn best practices to structure a model and manage research experiments.
	- [Assignments](https://github.com/chiphuyen/tf-stanford-tutorials) available on Github.
- [COMS 4771](http://www.cs.columbia.edu/~jebara/4771/index.html) **Machine Learning** *Columbia University*
	- Course taught by [Tony Jebara](http://www.cs.columbia.edu/~jebara/resume.html) introduces topics in Machine Learning for both generative and discriminative estimation. Material will include least squares methods, Gaussian distributions, linear classification, linear regression, maximum likelihood, exponential family distributions, Bayesian networks, Bayesian inference, mixture models, the EM algorithm, graphical models, hidden Markov models, support vector machines, and kernel methods.
	- [Lectures and Assignments](http://www.cs.columbia.edu/~jebara/4771/handouts.html)
- [CS 109](http://cs109.github.io/2015/) **Data Science** *Harvard University*
	- Learning from data in order to gain useful predictions and insights. This course introduces methods for five key facets of an investigation: data wrangling, cleaning, and sampling to get a suitable data set; data management to be able to access big data quickly and reliably; exploratory data analysis to generate hypotheses and intuition; prediction based on statistical methods such as regression and classification; and communication of results through visualization, stories, and interpretable summaries.
	- [Lectures](http://cm.dce.harvard.edu/2015/01/14328/publicationListing.shtml)
	- [Slides](http://cs109.github.io/2014/pages/schedule.html)
	- [Labs and Assignments](http://cs109.github.io/2014/pages/homework.html)
	- [2014 Lectures](http://cs109.github.io/2014/)
	- [2013 Lectures](http://cm.dce.harvard.edu/2014/01/14328/publicationListing.shtml) *(slightly better)*
- [CS 156](https://work.caltech.edu/telecourse.html) **Learning from Data** *Caltech*   <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20    " height="20" alt="Lecture Notes" title="Lecture Notes" />
	- This is an introductory course in machine learning (ML) that covers the basic theory, algorithms, and applications. ML is a key technology in Big Data, and in many financial, medical, commercial, and scientific applications. It enables computational systems to adaptively improve their performance with experience accumulated from the observed data. ML has become one of the hottest fields of study today, taken up by undergraduate and graduate students from 15 different majors at Caltech. This course balances theory and practice, and covers the mathematical as well as the heuristic aspects.
	- [Lectures](https://work.caltech.edu/lectures.html)
	- [Homework](https://work.caltech.edu/homeworks.html)
	- [Textbook](https://work.caltech.edu/textbook.html)
- [CS 189](http://www.eecs189.org/) **Introduction To Machine Learning** *UC Berkeley*
	- Introductory ML course covering a wide range of topics: ranging from least squares to convolutional neural networks
	- [Notes](http://www.eecs189.org/)
	- [Homework](http://www.eecs189.org/)
- [CS 224d](http://cs224d.stanford.edu/) **Deep Learning for Natural Language Processing** *Stanford University*
	- Natural language processing (NLP) is one of the most important technologies of the information age. Understanding complex language utterances is also a crucial part of artificial intelligence. Applications of NLP are everywhere because people communicate most everything in language: web search, advertisement, emails, customer service, language translation, radiology reports, etc. There are a large variety of underlying tasks and machine learning models powering NLP applications. Recently, deep learning approaches have obtained very high performance across many different NLP tasks. These models can often be trained with a single end-to-end model and do not require traditional, task-specific feature engineering. In this spring quarter course students will learn to implement, train, debug, visualize and invent their own neural network models. The course provides a deep excursion into cutting-edge research in deep learning applied to NLP.
	- [Syllabus](http://cs224d.stanford.edu/syllabus.html)
	- [Lectures and Assignments](http://cs224d.stanford.edu/syllabus.html)
- [CS 229r](http://people.seas.harvard.edu/~minilek/cs229r/fall15/index.html) **Algorithms for Big Data** *Harvard University*
	- Big data is data so large that it does not fit in the main memory of a single machine, and the need to process big data by efficient algorithms arises in Internet search, network traffic monitoring, machine learning, scientific computing, signal processing, and several other areas. This course will cover mathematically rigorous models for developing such algorithms, as well as some provable limitations of algorithms operating in those models.
	- [Lectures](http://people.seas.harvard.edu/~minilek/cs229r/fall15/lec.html) ([Youtube](https://www.youtube.com/playlist?list=PL2SOU6wwxB0v1kQTpqpuu5kEJo2i-iUyf))
	- [Assignments](http://people.seas.harvard.edu/~minilek/cs229r/fall15/hmwk.html)
- [CS 231n](http://cs231n.stanford.edu/) **Convolutional Neural Networks for Visual Recognition** *Stanford University*
	- Computer Vision has become ubiquitous in our society, with applications in search, image understanding, apps, mapping, medicine, drones, and self-driving cars. This course is a deep dive into details of the deep learning architectures with a focus on learning end-to-end models for these tasks, particularly image classification. During the 10-week course, students will learn to implement, train and debug their own neural networks and gain a detailed understanding of cutting-edge research in computer vision.
	- [Lecture Notes](http://cs231n.stanford.edu/syllabus.html)
	- [Lecture Videos](https://www.youtube.com/watch?v=NfnWJUyUJYU&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC)
	- [Github Page](http://cs231n.github.io/)

- [CS 395T](http://www.nr.com/CS395T/) **Statistical and Discrete Methods for Scientific Computing** *University of Texas*
	- Practical course in applying modern statistical techniques to real data, particularly bioinformatic data and large data sets. The emphasis is on efficient computation and concise coding, mostly in MATLAB and C++.
Topics covered include probability theory and Bayesian inference; univariate distributions; Central Limit Theorem; generation of random deviates; tail (p-value) tests; multiple hypothesis correction; empirical distributions; model fitting; error estimation; contingency tables; multivariate normal distributions; phylogenetic clustering; Gaussian mixture models; EM methods; maximum likelihood estimation; Markov Chain Monte Carlo; principal component analysis; dynamic programming; hidden Markov models; performance measures for classifiers; support vector machines; Wiener filtering; wavelets; multidimensional interpolation; information theory.
	- [Lectures and Assignments](http://wpressutexas.net/forum/)
- [CS 4780](http://www.cs.cornell.edu/courses/CS4780/2014fa/) **Machine Learning** *Cornell University*
	- This course will introduce you to technologies for building data-centric information systems on the World Wide Web, show the practical applications of such systems, and discuss their design and their social and policy context by examining cross-cutting issues such as citizen science, data journalism and open government. Course work involves lectures and readings as well as weekly homework assignments, and a semester-long project in which the students demonstrate their expertise in building data-centric Web information systems.
	- [Syllabus](http://www.cs.cornell.edu/courses/CS4780/2014fa/)
	- [Lectures](http://www.cs.cornell.edu/courses/CS4780/2014fa/)
- [CS 4786](http://www.cs.cornell.edu/courses/CS4786/2015sp/index.htm) **Machine Learning for Data Science** *Cornell University*
	- An introductory course in machine learning, with a focus on data modeling and related methods and learning algorithms for data sciences. Tentative topic list:
		- Dimensionality reduction, such as principal component analysis (PCA) and the singular value decomposition (SVD), canonical correlation analysis (CCA), independent component analysis (ICA), compressed sensing, random projection, the information bottleneck. (We expect to cover some, but probably not all, of these topics).
		- Clustering, such as k-means, Gaussian mixture models, the expectation-maximization (EM) algorithm, link-based clustering. (We do not expect to cover hierarchical or spectral clustering.).
		- Probabilistic-modeling topics such as graphical models, latent-variable models, inference (e.g., belief propagation), parameter learning.
		- Regression will be covered if time permits.
	- [Assignments](http://www.cs.cornell.edu/courses/CS4786/2015sp/assignments.htm)
	- [Lectures](http://www.cs.cornell.edu/courses/CS4786/2015sp/lectures.htm)

- [DS-GA 1008](http://cilvr.cs.nyu.edu/doku.php?id=deeplearning2015:schedule) **Deep Learning** *New York University*
	- This increasingly popular course is taught through the Data Science Center at NYU. Originally introduced by [Yann Lecun](http://yann.lecun.com/), it is now led by [Zaid Harchaoui](http://www.harchaoui.eu/), although Prof. Lecun is rumored to still stop by from time to time. It covers the theory, technique, and tricks that are used to achieve very high accuracy for machine learning tasks in computer vision and natural language processing. The assignments are in Lua and hosted on Kaggle.
	- [Course Page](http://cilvr.cs.nyu.edu/doku.php?id=deeplearning2015:schedule)
	- [Recorded Lectures](http://techtalks.tv/deep-learning-nyu-spring-2015/)
- [EECS E6893 & EECS E6895](http://www.ee.columbia.edu/~cylin/course/bigdata/) **Big Data Analytics & Advanced Big Data Analytics** *Columbia University*
	- Students will gain knowledge on analyzing Big Data. It serves as an introductory course for graduate students who are expecting to face Big Data storage, processing, analysis, visualization, and application issues on both workplaces and research environments.
	- Taught by [Dr. Ching-Yung Lin](http://researcher.watson.ibm.com/researcher/view.php?person=us-chingyung)
	- [Course Site](http://www.ee.columbia.edu/~cylin/course/bigdata/)
	- Assignments - Assignments are present in the Course Slides
- [EECS E6894](http://llcao.net/cu-deeplearning15/index.html) **Deep Learning for Computer Vision and Natural Language Processing** *Columbia University*
  - This graduate level research class focuses on deep learning techniques for vision and natural language processing problems. It gives an overview of the various deep learning models and techniques, and surveys recent advances in the related fields. This course uses Theano as the main programming tool. GPU programming experiences are preferred although not required. Frequent paper presentations and a heavy programming workload are expected.
  - [Readings](http://llcao.net/cu-deeplearning15/reading.html)
  - [Assignments](http://llcao.net/cu-deeplearning15/programming_problem.html)
  - [Lecture Notes](http://llcao.net/cu-deeplearning15/index.html)

- [Fast.ai Introduction to Machine Learning for Coders](http://course.fast.ai/ml.html) *Fast.ai / University of San Francisco*
	- There are around 24 hours of lessons, and you should plan to spend around 8 hours a week for 12 weeks to complete the material. The course is based on lessons recorded at the University of San Francisco for the Masters of Science in Data Science program. We assume that you have at least one year of coding experience, and either remember what you learned in high school math, or are prepared to do some independent study to refresh your knowledge.
	- [Lecture Videos](http://course.fast.ai/lessonsml1/lessonsml1.html)
	- [Lecture Notes](https://medium.com/@hiromi_suenaga/machine-learning-1-lesson-1-84a1dc2b5236)
	- [Jupyter Notebooks](https://github.com/fastai/fastai/tree/master/courses/ml1)
- [Info 290](http://www.ischool.berkeley.edu/courses/i290-abdt) **Analyzing Big Data with Twitter** *UC Berkeley school of information*
	- In this course, UC Berkeley professors and Twitter engineers provide lectures on the most cutting-edge algorithms and software tools for data analytics as applied to Twitter's data. Topics include applied natural language processing algorithms such as sentiment analysis, large scale anomaly detection, real-time search, information diffusion and outbreak detection, trend detection in social streams, recommendation algorithms, and advanced frameworks for distributed computing.
	-  [Lecture Videos](http://www.ischool.berkeley.edu/newsandevents/audiovideo/webcast/21963)
	-  [Previous Years coursepage](http://blogs.ischool.berkeley.edu/i290-abdt-s12/)
- [Machine Learning: 2014-2015](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/) *University of Oxford*
    - The course focusses on neural networks and uses the [Torch](https://github.com/torch/torch7/wiki/Cheatsheet) deep learning library (implemented in Lua) for exercises and assignments. Topics include: logistic regression, back-propagation, convolutional neural networks, max-margin learning, siamese networks, recurrent neural networks, LSTMs, hand-writing with recurrent neural networks, variational autoencoders and image generation and reinforcement learning
    - [Lectures and Assignments](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
    - [Source code](https://github.com/oxford-cs-ml-2015/)
- [StatLearning](https://lagunita.stanford.edu/courses/HumanitiesandScience/StatLearning/Winter2015/about) **Intro to Statistical Learning** *Stanford University*
	- This is an introductory-level course in supervised learning, with a focus on regression and classification methods. The syllabus includes: linear and polynomial regression, logistic regression and linear discriminant analysis; cross-validation and the bootstrap, model selection and regularization methods (ridge and lasso); nonlinear models, splines and generalized additive models; tree-based methods, random forests and boosting; support-vector machines.
	- The lectures cover all the material in [An Introduction to Statistical Learning, with Applications in R](http://www-bcf.usc.edu/~gareth/ISL/) which is a more approachable version of the [Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/) (or ESL) book.
- [10-601](http://www.cs.cmu.edu/~ninamf/courses/601sp15/) **Machine Learning** *Carnegie Mellon University*
	- This course covers the theory and practical algorithms for machine learning from a variety of perspectives. It covers topics such as Bayesian networks, decision tree learning, Support Vector Machines, statistical learning methods, unsupervised learning and reinforcement learning. The course covers theoretical concepts such as inductive bias, the PAC learning framework, Bayesian learning methods, margin-based learning, and Occam's Razor. Short programming assignments include hands-on experiments with various learning algorithms. This course is designed to give a graduate-level student a thorough grounding in the methodologies, technologies, mathematics and algorithms currently needed by people who do research in machine learning.
	- Taught by one of the leading experts on Machine Learning - **Tom Mitchell**
	- [Lectures](http://www.cs.cmu.edu/~tom/10701_sp11/lectures.shtml)
	- [Project Ideas and Datasets](http://www.cs.cmu.edu/~tom/10701_sp11/proj.shtml)

- [11-785](http://deeplearning.cs.cmu.edu/) **Deep Learning** *Carnegie Mellon University*
	- The course presents the subject through a series of seminars and labs, which will explore it from its early beginnings, and work themselves to some of the state of the art. The seminars will cover the basics of deep learning and the underlying theory, as well as the breadth of application areas to which it has been applied, as well as the latest issues on learning from very large amounts of data. We will concentrate largely, although not entirely, on the connectionist architectures that are most commonly associated with it. *Lectures* and *Reading Notes* are available on the page.
- [CS246](http://web.stanford.edu/class/cs246/) **Mining Massive Data Sets** *Stanford University*
	- The course will discuss data mining and machine learning algorithms for analyzing very large amounts of data. The emphasis will be on Map Reduce as a tool for creating parallel algorithms that can process very large amounts of data.
	- [Lecture Videos](http://www.mmds.org/#mooc)
	- [Assignments](http://web.stanford.edu/class/cs246/handouts.html)
	- [Lecture notes](http://web.stanford.edu/class/cs246/handouts.html)
	- [Readings](http://www.mmds.org/#book)
- [CS276](http://web.stanford.edu/class/cs276/index.html) **Information Retrieval and Web Search** *Stanford University*
	- Basic and advanced techniques for text-based information systems: efficient text indexing; Boolean and vector space retrieval models; evaluation and interface issues; Web search including crawling, link-based algorithms, and Web metadata; text/Web clustering, classification; text mining.
	- [Lecture notes](http://web.stanford.edu/class/cs276/index.html#syllabus)
	- [Readings](http://web.stanford.edu/class/cs276/index.html#books)
- [Practical_RL](https://github.com/yandexdataschool/Practical_RL) **Reinforcement Learning in the Wild** *Yandex SDA*
	- A course on reinforcement learning in the wild. Taught on-campus in HSE and Yandex SDA (russian) and maintained to be friendly to online students (both english and russian).
	- [Syllabus](https://github.com/yandexdataschool/Practical_RL#syllabus)

-------

### Security
- [CIS 4930 / CIS 5930](http://www.cs.fsu.edu/~redwood/OffensiveComputerSecurity/) **Offensive Computer Security** *Florida State University*
	- Course taught by [W. Owen Redwood](http://ww2.cs.fsu.edu/~redwood/) and [Xiuwen Liu](http://www.cs.fsu.edu/~liux/). It covers a wide range of computer security topics, starting from Secure C Coding and Reverse Engineering to Penetration Testing, Exploitation and Web Application Hacking, both from the defensive and the offensive point of view.
	- [Lectures and Videos](http://www.cs.fsu.edu/~redwood/OffensiveComputerSecurity/lectures.html)
	- [Assignments](http://www.cs.fsu.edu/~redwood/OffensiveComputerSecurity/assignments.html)
- [CS 155](https://crypto.stanford.edu/cs155/) **Computer and Network Security** *Stanford*
	- Principles of computer systems security. Attack techniques and how to defend against them. Topics include: network attacks and defenses, operating system holes, application security (web, email, databases), viruses, social engineering attacks, privacy, and digital rights management. Course projects focus on building reliable code. Recommended: Basic Unix. Primarily intended for seniors and first-year graduate students.
- [CS 161](http://www-inst.eecs.berkeley.edu/~cs161/sp15/) **Computer Security** *UC Berkeley*
	- Introduction to computer security. Cryptography, including encryption, authentication, hash functions, cryptographic protocols, and applications. Operating system security, access control. Network security, firewalls, viruses, and worms. Software security, defensive programming, and language-based security. Case studies from real-world systems.
- [CS 259](https://courseware.stanford.edu/pg/courses/331628/cs259-winter-2013) **Security Modeling and Analysis** *Stanford*
	- The course will cover a variety of contemporary network protocols and other systems with security properties. The course goal is to give students hands-on experience in using automated tools and related techniques to analyze and evaluate security mechanisms. To understand security properties and requirements, we will look at several network protocols and their properties, including secrecy, authentication, key establishment, and fairness. In parallel, the course will look at several models and tools used in security analysis and examine their advantages and limitations. In addition to fully automated finite-state model checking techniques, we will also study other approaches, such as constraint solving, process algebras, protocol logics, probabilistic model checking, game theory, and executable models based on logic programming.
- [CS 261](http://www.icir.org/vern/cs261n-Sp14/) **Internet/Network Security** *UC Berkeley*
	- This class aims to provide a thorough grounding in network security suitable for those interested in conducting research in the area, as well as students more generally interested in either security or networking. We will also look at broader issues relating to Internet security for which networking plays a role.  Topics include: denial-of-service; capabilities; network intrusion detection; worms; forensics; scanning; traffic analysis / inferring activity; architecture; protocol issues; legality and ethics; web attacks; anonymity; honeypots; botnets; spam; the underground economy; research pitfalls. The course is taught with an emphasis on seminal papers rather than bleeding-edge for a given topic.

- [CSCI 4968](https://github.com/RPISEC/MBE) **Modern Binary Exploitation** *Rensselaer Polytechnic Institute*
	- This repository contains the materials as developed and used by [RPISEC](http://rpis.ec) to
teach Modern Binary Exploitation at [Rensselaer Polytechnic Institute](http://rpi.edu) in
Spring 2015. This was a university course developed and run solely by students to teach
skills in vulnerability research, reverse engineering, and binary exploitation.
	- [Lectures Notes](http://security.cs.rpi.edu/courses/binexp-spring2015/lectures/)
	- [Labs](https://github.com/RPISEC/MBE/tree/master/src)
	- [Projects](https://github.com/RPISEC/MBE/tree/master/src)
- [CSCI 4976](https://github.com/RPISEC/Malware) **Malware Analysis** *Rensselaer Polytechnic Institute*
	- This repository contains the materials as developed and used by [RPISEC](http://rpis.ec) to
teach Malware Analysis at [Rensselaer Polytechnic Institute](http://rpi.edu) in
Fall 2015. This was a university course developed and run solely by students, primarily using the
- [EECS 588](https://www.eecs.umich.edu/courses/eecs588/) **Computer & Network Security** *University of Michigan*
	- Taught by [J. Alex Halderman](https://jhalderm.com/) who has analyzed the security of Electronic Voting Machines in the [US](https://jhalderm.com/pub/papers/dcvoting-fc12.pdf) and [over](https://jhalderm.com/pub/papers/ivoting-ccs14.pdf) [seas](https://jhalderm.com/pub/papers/evm-ccs10.pdf).
	- This intensive research seminar covers foundational work and current topics in computer systems security.
	- [Readings](https://www.eecs.umich.edu/courses/eecs588/readings.html)
[Practical Malware Analysis](http://www.amazon.com/Practical-Malware-Analysis-Dissecting-Malicious/dp/1593272901)
book by Michael Sikorski and Andrew Honig, to teach skills in reverse engineering, malicious behaviour, malware,
and anti-analysis techniques.
	- [Lectures Notes](https://github.com/RPISEC/Malware/tree/master/Lectures)
	- [Labs](https://github.com/RPISEC/Malware/tree/master/Labs)
	- [Projects](https://github.com/RPISEC/Malware/tree/master/Projects)
- [6.857](http://courses.csail.mit.edu/6.857/2015/) **Computer and Network Security** *MIT*
	- Emphasis on applied cryptography and may include: basic notion of systems security, cryptographic hash functions, symmetric cryptography (one-time pad, stream ciphers, block ciphers), cryptanalysis, secret-sharing, authentication codes, public-key cryptography (encryption, digital signatures), public-key attacks, web browser security, biometrics, electronic cash, viruses, electronic voting, Assignments include a group final project. Topics may vary year to year.
	[Lecture Notes](http://courses.csail.mit.edu/6.857/2015/handouts)
	[References](http://courses.csail.mit.edu/6.857/2015/references)
- [6.858](http://css.csail.mit.edu/6.858/2014/) **Computer Systems Security** *MIT*    <img src="" width="20" height="20" alt="Readings" title="Readings" />
	- Design and implementation of secure computer systems. Lectures cover threat models, attacks that compromise security, and techniques for achieving security, based on recent research papers. Topics include operating system (OS) security, capabilities, information flow control, language security, network protocols, hardware security, and security in web applications.
	- Taught by [James Mickens](http://research.microsoft.com/en-us/people/mickens/) and [Nickolai Zeldovich](http://people.csail.mit.edu/nickolai/)
	- [Video Lectures and Labs](http://css.csail.mit.edu/6.858/2014/schedule.html)
	- [Quizzes](http://css.csail.mit.edu/6.858/2014/quiz.html)
	- [Readings](http://css.csail.mit.edu/6.858/2014/reference.html)
	- [Final Projects](http://css.csail.mit.edu/6.858/2014/projects.html)

-------
### Artificial Intelligence

- [CS 188](http://ai.berkeley.edu/home.html) **Introduction to Artificial Intelligence** *UC Berkeley*   <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4dd.png" width="20    " height="20" alt="Lecture Notes" title="Lecture Notes" />
    - This course will introduce the basic ideas and techniques underlying the design of intelligent computer systems. A specific emphasis will be on the statistical and decision-theoretic modeling paradigm. By the end of this course, you will have built autonomous agents that efficiently make decisions in fully informed, partially observable and adversarial settings. Your agents will draw inferences in uncertain environments and optimize actions for arbitrary reward structures. Your machine learning algorithms will classify handwritten digits and photographs. The techniques you learn in this course apply to a wide variety of artificial intelligence problems and will serve as the foundation for further study in any application area you choose to pursue.
    - [Lectures](http://ai.berkeley.edu/lecture_videos.html)
    - [Projects](http://ai.berkeley.edu/project_overview.html)
    - [Exams](http://ai.berkeley.edu/exams.html)
- [CS 4700](http://www.cs.cornell.edu/courses/CS4700/2014fa/) **Foundations of Artificial Intelligence** *Cornell University*
	- This course will provide an introduction to computer vision, with topics including image formation, feature detection, motion estimation, image mosaics, 3D shape reconstruction, and object and face detection and recognition. Applications of these techniques include building 3D maps, creating virtual characters, organizing photo and video databases, human computer interaction, video surveillance, automatic vehicle navigation, and mobile computer vision. This is a project-based course, in which you will implement several computer vision algorithms throughout the semester.
	- [Assignments](http://www.cs.cornell.edu/courses/CS4700/2014fa/)
	- [Lectures](http://www.cs.cornell.edu/courses/CS4700/2014fa/)
- [CS 6700](http://www.cs.cornell.edu/courses/CS6700/2013sp/) **Advanced Artificial Intelligence** *Cornell University*
	- The design of systems that are among top 10 performers in the world (human, computer, or hybrid human-computer).
	- [Syllabus](http://www.cs.cornell.edu/courses/CS6700/2013sp/lectures/CS6700-Overview_v2.pptx)
	- [Lectures](http://www.cs.cornell.edu/courses/CS6700/2013sp/)
	- [Readings](http://www.cs.cornell.edu/courses/CS6700/2013sp/)

-------
### Computer Graphics
- [CAP 5415](http://crcv.ucf.edu/courses/CAP5415/) **Computer Vision** *University of Central Florida*
	- An introductory level course covering the basic topics of computer vision, and introducing some fundamental approaches for computer vision research.
	- [Lectures and Videos](http://crcv.ucf.edu/videos/Lecture_Videos/)
	- [Assignments](http://crcv.ucf.edu/courses/CAP5415/Fall2014/index.php)
- [CIS 581](https://alliance.seas.upenn.edu/~cis581/wiki/index.php?title=CIS_581:_Computer_Vision_%26_Computational_Photography) **Computer Vision and Computational Photography** *University of Pennsylvania*
	- An introductory course in computer vision and computational photography focusing on four topics: image features, image morphing, shape matching, and image search.
	- [Lectures](https://alliance.seas.upenn.edu/~cis581/wiki/index.php?title=Schedule)
	- [Assignments](https://alliance.seas.upenn.edu/~cis581/wiki/index.php?title=Projects)
- [CMU 462](http://15462.courses.cs.cmu.edu/fall2015) **Computer Graphics** *Carnegie Mellon University*
    - This course provides a comprehensive introduction to computer graphics. Focuses on fundamental concepts and techniques, and their cross-cutting relationship to multiple problem domains in graphics (rendering, animation, geometry, imaging). Topics include: sampling, aliasing, interpolation, rasterization, geometric transformations, parameterization, visibility, compositing, filtering, convolution, curves & surfaces, geometric data structures, subdivision, meshing, spatial hierarchies, ray tracing, radiometry, reflectance, light fields, geometric optics, Monte Carlo rendering, importance sampling, camera models, high-performance ray tracing, differential equations, time integration, numerical differentiation, physically-based animation, optimization, numerical linear algebra, inverse kinematics, Fourier methods, data fitting, example-based synthesis.
    - [Lectures and Readings](http://15462.courses.cs.cmu.edu/fall2015/reading)
    - [Assignments and Quizes](http://15462.courses.cs.cmu.edu/fall2015/exercises)

- [CS 4620](http://www.cs.cornell.edu/Courses/CS4620/2014fa/index.shtml#) **Introduction to Computer Graphics** *Cornell University*
	- The study of creating, manipulating, and using visual images in the computer.
	- [Assignments](http://www.cs.cornell.edu/Courses/CS4620/2014fa/index.shtml#asgn)
	- [Exams](http://www.cs.cornell.edu/Courses/CS4620/2014fa/index.shtml#exams)
- [CS 4670](http://www.cs.cornell.edu/courses/CS4670/2015sp/) **Introduction to Computer Vision** *Cornell University*
	- This course will provide an introduction to computer vision, with topics including image formation, feature detection, motion estimation, image mosaics, 3D shape reconstruction, and object and face detection and recognition. Applications of these techniques include building 3D maps, creating virtual characters, organizing photo and video databases, human computer interaction, video surveillance, automatic vehicle navigation, and mobile computer vision. This is a project-based course, in which you will implement several computer vision algorithms throughout the semester.
	- [Assignments](http://www.cs.cornell.edu/courses/CS4670/2015sp/projects/projects.html)
	- [Lectures](http://www.cs.cornell.edu/courses/CS4670/2015sp/lectures/lectures.html)

- [CS 6670](https://canvas.instructure.com/courses/904706) **Computer Vision** *Cornell University*
	- Introduction to computer vision. Topics include edge detection, image segmentation, stereopsis, motion and optical flow, image mosaics, 3D shape reconstruction, and object recognition. Students are required to implement several of the algorithms covered in the course and complete a final project.
	- [Syllabus](https://canvas.instructure.com/courses/904706/assignments/syllabus)
	- [Lectures](https://canvas.instructure.com/courses/904706)
	- [Assignments](https://canvas.instructure.com/courses/904706/assignments)

- [CSCI 1230](http://cs.brown.edu/courses/csci1230/index.html) **Introduction to Computer Graphics** *Brown University*
	- This course offers an in-depth exploration of fundamental concepts in 2D and 3D computer graphics. It introduces 2D raster graphics techniques, including scan conversion, simple image processing, interaction techniques and user interface design. The bulk of the course is devoted to 3D modeling, geometric transformations, and 3D viewing and rendering.
	- [Lectures](http://cs.brown.edu/courses/csci1230/lectures.html)
	- [Labs](http://cs.brown.edu/courses/csci1230/labs.html)
	- [Demos](http://cs.brown.edu/courses/csci1230/demos.html)
- [CSCI-GA.2270-001](https://mrl.nyu.edu/~perlin/courses/fall2015/) **Graduate Computer Graphics** *New York University*
	- Step-by-step study computer graphics, with reading and homework at each lecture (Fall2015)
	- [Lectures](https://mrl.nyu.edu/~perlin/courses/fall2015/)

-------
### Misc

- [CS 168](https://inst.eecs.berkeley.edu/~cs168/fa15/) **Computer Networks** *UC Berkeley*
    - This is an undergraduate level course covering the fundamental concepts of networking as embodied in the Internet. The course will cover a wide range of topics; see the lecture schedule for more details. While the class has a textbook, we will not follow its order of presentation but will instead use the text as a reference when covering each individual topic. The course will also have several projects that involve programming (in Python).
    - You should know programming, data structures, and software engineering. In terms of mathematics, your algebra should be very solid, you need to know basic probability, and you should be comfortable with thinking abstractly. The TAs will spend very little time reviewing material that is not specific to networking. We assume that you either know the material covered in those courses, or are willing to learn the material as necessary. We won't cover any of this material in lecture.

- [CS 411](http://video.bilkent.edu.tr/course_videos.php?courseid=10) **Software Architecture Design** *Bilkent University*
	- This course teaches the basic concepts, methods and techniques for designing software architectures. The topics include: rationale for software architecture design, modeling software architecture design, architectural styles/patterns, architectural requirements analysis, comparison and evaluation of architecture design methods, synthesis-based software architecture design, software product-line architectures, domain modeling, domain engineering and application engineering, software architecture implementation, evaluating software architecture designs.

- [CS 5150](http://www.cs.cornell.edu/courses/CS5150/2014fa/overview.html) **Software Engineering** *Cornell University*
	- Introduction to the practical problems of specifying, designing, building, testing, and delivering reliable software systems
	- [Lectures](http://www.cs.cornell.edu/courses/CS5150/2014fa/materials.html)
	- [Assignments](http://www.cs.cornell.edu/courses/CS5150/2014fa/assignments.html)
