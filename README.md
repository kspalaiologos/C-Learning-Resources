# C learning resources
This repository contains list of books and other resources about C programming that are in my opinion best to learn from. There are many sources but not every is correct. This way, beginners make a lot of mistakes in their code. I'm suggesting to read books in the order I've provided.
##### Where **not** to learn from:
 - [TutorialsPoint](https://www.tutorialspoint.com/cprogramming/index.htm). TutorialsPoint is an good website for **reference** not learning. If you want to learn something to it's fullest, get a book.
 - [Udemy](https://www.udemy.com/c-programming-for-beginners/). Udemy is not good place to learn C from. Courses cost pretty much ($100). **Some courses recommend using old Borland C++ Builder** - learning outdated stuff is not way to go.
 - [SoloLearn](https://www.sololearn.com/). SoloLearn does not offer any course to learn C from. The website teaches you **how** to do something, while your own experience teaches you how to *do* something.
 - [Youtube](https://youtube.com/). Learning from various youtube channels that are not-so-popular is not a good idea. You need solid place to learn from. Although, there are channels like [this one](https://www.youtube.com/channel/UCzn6vAfspIcagLax1fck_jw). They introduce really bad programming practices and learn how to **not** program.
##### Where to learn from:
 - [K&R book](http://cs.indstate.edu/~cbasavaraj/cs559/the_c_programming_language_2.pdf) is often thought as the bible of C. There are many C standards but K&R C is thought as the most common - every compiler has to support it. The most used standard is C89, although we have C99 and C11 that are more recent. This way, K&R book is always on topic. It was written by creators of C - they can't be wrong.
   * Pros:
     * This book is **written by Dennis Ritchie**, who **was one of the main people behind the development and design of C** and UNIX.
     * This book is so well known that it's affectionately called "K&R", after the authors.
     * It's been cited in many other books and is familiar to most, if not all, CS students.
     * The challenges at the end of each chapter do a great job of requiring many of the skills learned up to that point. Completing the challenges is a great way of insuring you understand the material.
   * Cons:
     * The K&R style works for old Unix mainframe command-line programs that exit after a simple task and leave the cleanup to the OS; where input is only from trusted experts; and most functions are only called internally to the program. The environment is very different today. This style will get your server pwned by hackers, or crash it due to a memory leak. You will have to learn C again to use C correctly in the real world **today**.
     * Some commands and practices are out of date, so errata and googling is needed while going through the book.
     * Assumes familiarity not only with programming concepts but some C language specifics - not so simple for beginners.
 * [C Programming: Modern approach, 2nd Edition](https://www.amazon.com/C-Programming-Modern-Approach-2nd/dp/0393979504)
   * Pros:
     * The book really challenges you to think like a programmer by constantly asking questions that force you to solve problems, rather than telling you how to solve the problem and only asking you to write the syntax. This way helps beginner programmers to get into programming.
     * The author breaks things down into small pieces and uses examples to explain everything in a very clear way.
     * Doesn't have exercise answers (can be counted like con)
 * [Learn C the hard way](https://learncodethehardway.org/c/). Just looking at the title, it may not be greatest book for newcomer to learn.
   * Pros
     * It's not just about C. It will teach to become an over-all better programmer and give a better understanding of computer science. You are going to learn about things like testing, debugging, and sorting algorithms.
     * Includes 52 practical project ideas that include everything from pointers to stacks and queues.
   * Con: States in the preface that it is not for first-time programmers. Better check something other, if you are new to C.
 * [C Programming Absolute Beginner's Guide (3rd Edition)](https://www.amazon.com/Programming-Absolute-Beginners-Guide-3rd/dp/0789751984). It's suggested to check out this book if others are too hard for you.
   * Pro: There are 32 chapters in the book, which is 352 pages long. The short chapters make it extremely easy to use this book as a reference, and breaks everything down into small pieces that are easy to digest.
   * Con: This book, as the title suggests, is really aimed at people with no prior programming experience.
Fundamentals are gone through in detail, this would be quite a slow review for someone with experience in another language.
 * (NASA C style book)[http://homepages.inf.ed.ac.uk/dts/pm/Papers/nasa-c-style.pdf]. This book is pretty nice place to learn proper way how to program in C to write readable code.

Please note that this list as stated on beginning, is based primarily on my opinion. If you disagree with some facts, please open issue / submit a pull request that contents are satisfying you. I am working on a C book that after review will probably get on this list.
Books that I am not sure about quality:
 * [Programming in C (4th Edition) (Developer's Library)](https://www.amazon.com/Programming-C-4th-Developers-Library/dp/0321776410/ref=pd_bxgy_14_img_2?_encoding=UTF8&pd_rd_i=0321776410&pd_rd_r=F4EZTNWZYDBJA50CBXYE&pd_rd_w=ZihCY&pd_rd_wg=4ehaO&psc=1&refRID=F4EZTNWZYDBJA50CBXYE)
