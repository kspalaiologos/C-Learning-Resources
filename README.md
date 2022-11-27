# C learning resources
This repository contains a list of books and other resources about C programming that in my opinion are the best to learn from. There are many sources you could learn from, but not all of them present the topic in an approachable way and are correct. Because of this, people new to C usually make a lot of mistakes and build fundamental misunderstanding in how C works.

#### Avoid:
 - [TutorialsPoint](https://www.tutorialspoint.com/cprogramming/index.htm). TutorialsPoint appears to be a decent website for language reference, but not for learning. If you want to learn something to its fullest, get a book and consider other sources (e.g. manual pages).
 - [Udemy](https://www.udemy.com/c-programming-for-beginners/). Udemy and other sites that offer user-made courses aren't a good place to learn C from. Courses often cost quite a lot (up to $100), there's no tangible proof of the author's knowledge of the subject, and many of them are outdated - many courses which I have seen recommend using tools as old as Borland C++ Builder.
 - [Youtube](https://youtube.com/). Learning from various youtube channels is not a good idea. Most youtube content in this day and age is simplified beyond recognition in hopes of increased user retention. Processing knowledge of a complicated subject generally takes time. We all learn at a different pace, so an oversimplified (and consequently often incorrect) video might not help as much as you think. In process of making content more approachable, it may reinforce a misunderstanding you have, which will have long-term consequences.

#### Consider:
 - [K&R book](https://archive.org/download/cprogbooks/k%26r.pdf) is often thought of as the "Bible" of C. There are many C standards but the C described in the most recent revision of the book is considered the most ubiquitous.
   * Pros:
     * Written by Dennis Ritchie, who was one of the main people behind the development and design of C and UNIX.
     * This book is so well known that it's affectionately called "K&R", after the authors.
     * It's been cited in many other books and is familiar to most, if not all, CS students.
     * The challenges at the end of each chapter do a great job requiring many of the skills learned up to that point. Completing the challenges is a great way of ensuring that you understand the material.
   * Cons:
     * The K&R style works for old Unix mainframe command-line programs that exit after a simple task and leave the cleanup to the OS; where input is only from trusted experts; and most functions are only called internally to the program.
     * Some practices are out of date, so errata and googling is needed while going through the book.
     * Assumes familiarity not only with programming concepts but some C language specifics which are not so simple for beginners.
 * [C Programming: Modern approach, 2nd Edition](https://www.amazon.com/C-Programming-Modern-Approach-2nd/dp/0393979504)
   * Pros:
     * The book really challenges you to think like a programmer by constantly asking questions that force you to solve problems, rather than telling you how to solve the problem and only asking you to write the syntax. This way helps beginner programmers to get into programming.
     * The author breaks things down into small pieces and uses examples to explain everything in a very clear way.
     * Doesn't have exercise answers (can be counted as a con).
 * [Learn C the hard way](https://learncodethehardway.org/c/). By just looking at the title, it may not be greatest book for newcomer to learn.
   * Pros
     * It's not just about C. It will teach to become an over-all better programmer and give a better understanding of computer science. You are going to learn about things like (for example) testing, debugging, and various algorithms from a theoretical and practical standpoint.
     * Includes 52 practical project ideas that involve many concepts from pointers to stacks and queues.
   * Con: States in the preface that it is not for first-time programmers. Better check something else if you are new to C.
 * [C Programming Absolute Beginner's Guide (3rd Edition)](https://www.amazon.com/Programming-Absolute-Beginners-Guide-3rd/dp/0789751984). It's suggested to check out this book if others are too difficult for you.
   * Pro: There are 32 chapters in this book, which gives 352 pages. The short chapters make it extremely easy to use this book as a reference. The book breaks everything down into small pieces that are easy to digest.
   * Con: This book, as the title suggests, is really aimed at people with no prior programming experience.
Fundamentals are gone through in detail, this would be quite a slow review for someone with experience in another language.
 * [NASA C style book](https://web.archive.org/web/20130718191933/http://homepages.inf.ed.ac.uk/dts/pm/Papers/nasa-c-style.pdf). This book is pretty nice place to learn the proper way on how to program in C to write readable code.
 * [Steve Summit's C notes](https://www.eskimo.com/~scs/cclass/). These notes expand on the K&R book. You'll find other C goodies in [his](https://www.eskimo.com/~scs/) main webpage too.

#### Books that I am not sure about their quality:

 * [Programming in C (4th Edition) (Developer's Library)](https://www.amazon.com/Programming-C-4th-Developers-Library/dp/0321776410/ref=pd_bxgy_14_img_2?_encoding=UTF8&pd_rd_i=0321776410&pd_rd_r=F4EZTNWZYDBJA50CBXYE&pd_rd_w=ZihCY&pd_rd_wg=4ehaO&psc=1&refRID=F4EZTNWZYDBJA50CBXYE).
 
#### Best programming environment for a C programmer
- TLDR: [UNIX, GNU/Linux](https://www.amazon.com/-/es/Brian-W-Kernighan/dp/013937681X/).
- NTLDR:
Programming doesn't take place on a piece of paper. Maybe it starts there, or the black-board, when you're still exploring the ideas and the algorithms, but when it's time to type down your ideas and test them against the machine, you need a programming enviroment to program in. The UNIX and GNU/Linux systems were made for this purpose, and C was created to create UNIX. In other words, UNIX and C are made for each other. One cannot exist without the other, and if you want to maximize your potential as a C programmer, a knowledge of the UNIX based operating systems **will** make your life **so_much_easier** !. Luckilly for you, [Brian](https://en.wikipedia.org/wiki/Brian_Kernighan) (co-creator of C and UNIX) and [Rob](https://en.wikipedia.org/wiki/Rob_Pike) (member of the UNIX team, the "Plan 9 from Bell Labs" and co-creator of golang) wrote a book about it. [Read the reviews in goodreads](https://www.goodreads.com/book/show/337338.The_UNIX_Programming_Environment) and buy it from your an [online bookshop](https://www.amazon.com/-/es/Brian-W-Kernighan/dp/013937681X/).

 # Why to learn C?

There are a lot of programmers that think C is not language worth learning. Let's review this.

 - C was originally developed for the UNIX operating system by Dennis Ritchie. It's quite simple, is not tied to any particular hardware or operating system. **If some platform has C compiler, it's worth attention**.
 - C is a general purpose language, meaning that it's so common. This makes **it easier to write programs that will run without any changes on practically all machines that have POSIX compliant API's**. Additionally, most libraries worth your attention (PARI, sqlite, gmp, ...) are also written in C!
- The C language is a middle-level language as it combines the elements of high-level languages (structures, unions, enums, functions, conditionals) with the functionalism of assembly language.
 - It's possible to both simulate object orientation in C and write an operating system. C allows the manipulation of nearly everything giving the programmer more control over exactly how the program will behave and more direct access to the mechanics of the underlying hardware while keeping application fully portable. C is often called a "cross-platform assembler" because of this.
 - C is still one of the most popular programming languages out there [at the time of writing it was 2nd language overall](https://www.tiobe.com/tiobe-index/). Overall, C was first most commonly researched language from 1988 to 2013! Its popularity is still growing. In the year of writing, C had the highest rise in ratings in a year.
 - C is everywhere. Your keyboard is very likely powered by C, just like your fridge or even router. Windows was originally developed in C and has nearly 90% market share. Same as Linux, MacOS, iOS and Windows Phone. The world’s most popular databases, including MySQL, MS SQL Server, and PostgreSQL are developed in C. 3D movies are created with applications that are generally written in C and C++. The alarm clock that wakes you up is likely programmed in C. Later on in the day you use your microwave or coffee maker to make your breakfast. They employ embedded systems and therefore are probably programmed in C. You turn on your TV or radio while you eat your breakfast. Again, likely C. When you open your garage door with the remote control you are also using an embedded system that is most likely programmed in C. You park your car, go to the store and use vending machine to get a soda can. What language did they use to program this vending machine? Probably C. Then you buy something at the store. The cash register is also programmed in C. And when you pay with your credit card? The credit card reader is, again, likely programmed in C.
 - There are many programming languages nowadays that allow developers to be more productive than with C for different kinds of projects. There are higher level languages that provide much larger built-in libraries that simplify working with JSON, XML, UI, web pages, client requests, database connections, media manipulation, and so on. But despite that, there are plenty of reasons to believe that C will remain relevant for a very long time. In programming languages one size does not fit all.
 - Here are some reasons that C is unbeatable, and almost mandatory, for certain applications:
   * **Arbitrary memory address access and pointer arithmetic is an important feature that makes C a perfect fit for system programming (operating systems and embedded systems).**
   * **A common language feature that system programming cannot rely on it's garbage collection, or even just dynamic allocation for some embedded systems. Embedded applications are very limited in time and memory resources. They are often used for real-time systems, where a non-deterministic call to the garbage collector cannot be afforded. And if dynamic allocation cannot be used because of the lack of memory, it is very important to have other mechanisms of memory management, like placing data in custom addresses, as C pointers allow.** Languages that depend heavily on dynamic allocation and garbage collection wouldn’t fit for resource-limited systems.
   * **C has a very small runtime. And the memory footprint for its code is smaller than for most other languages.** When compared to C++, for example, a C-generated binary that goes to an embedded device is about half the size of a binary generated by similar C++ code. One of the main causes for that is exceptions support. Exceptions are a great tool added by C++ over C, and, if not triggered and smartly implemented, they have practically no execution time overhead (but at the cost of increasing the code size).
   * **C is a lingua franca for developers. Many implementations of new algorithms in books or on the internet are first (or only) made available in C by their authors.** This gives the maximum possible portability for the implementation. I’ve seen programmers struggling on the internet to rewrite a C algorithm to other programming languages because he or she didn’t know very basic concepts of C.

### The Illuminati doesn't run the world. C programmers do.

# Contribute

Please note that this list as stated on beginning, is based primarily on my opinion. If you disagree with some facts, please open an issue or submit a pull request whose contents satisfy you. 
