# Reference Books for Machine Vision [work in progress]

Expect this wiki page to be updated periodically. Books mentioned in community posts and replies should find there way here eventually.

See the starter post ["machine vision reference books: familiar, unfamiliar, and new (FUN)"](https://www.reddit.com/r/MachineVisionSystems/comments/1jhfv9o/machine_vision_reference_books_familiar/)

Books specific to machine vision are listed first, followed by books on computer vision, image processing, and related subjects.

## Machine Vision Books
For most topics in image processing you'll find textbooks with the words "computer vision" in the title. Those are listed in their own section below. Books with the words "machine vision" in the title are more likely to address practical considerations of hardware systems, including the selection of cameras, CCD or CMOS sensors, lenses, lighting, digital communications, and so on. 

[**Understanding and Applying Machine Vision**](https://www.routledge.com/Understanding-and-Applying-Machine-Vision-Revised-and-Expanded/Zeuch/p/book/9780367399023?srsltid=AfmBOooH0_0k5NUs0nKvrxooCi6y7WHV_eO5SvoD9qaIiWKbDzm48WhW) by Nello Zuech is a great, underappreciated work by a practitioner. Nello is well known by the older generation of machine vision professionals. 

[**Machine Vision Algorithms and Applications**](https://www.wiley.com/en-us/Machine+Vision+Algorithms+and+Applications%2C+2nd+Edition-p-9783527413652) by Steger, Ulrich and Wiedemann covers the topics critical to machine vision such as optics and lighting. The book includes examples of classic vision applications: ball grid array (BGA) inspection; dimensional gauging; 3D from stereo; reading of serial numbers; and so on. Reddit member u/bartgrumbel wrote the following about the book:

> Goes into great detail of many low-level algorithms with a very practical perspective. 


## Machine Vision to Computer Vision
The 3rd edition of the textbook 
[**Machine Vision: Theorems, Algorithms, Practicalities**](https://www.reddit.com/mod/MachineVisionSystems/wiki/edit/index/books) by E.R. Davies 
was published in 2004, but still yields useful advice. You can likely find an inexpensive copy and learn from it.

In the 4th edition, published in 2012, the book was retitled to 
[**Computer and Machine Vision**](https://shop.elsevier.com/books/computer-and-machine-vision/davies/978-0-12-386908-1). 

Now, in the 5th edition, published in 2017, the book was retitled yet again, this time to
[**Computer Vision: Principles, Algorithms, Applications, Learning**](https://shop.elsevier.com/books/computer-vision/davies/978-0-12-809284-2)

Despite the title changes, content from earlier editions is carried forward:

> Examples and applications—including the location of biscuits, foreign bodies, faces, eyes, road lanes, surveillance, vehicles and pedestrians—give the ‘ins and outs’ of developing real-world vision systems, showing the realities of practical implementation.
 
Naming conventions shift over time.  A rose by any other name...

## Computer Vision & Digital Image Processing
The r/computervision community has a succinct summary of the field: 

> Computer Vision is the scientific subfield of AI concerned with developing algorithms to extract meaningful information from raw images, videos, and sensor data. 

Informally, you might consider computer vision to be "the academic study of digital image processing and artificial vision." To learn the fundamentals you could save money buying used copies of older textbooks. Consider having at least one solid reference book, and then supplement with academic papers, video courses, comments in open source projects, and online documentation.

[**Digital Picture Processing**](https://books.google.com/books?id=eKp2BjTHK5sC&printsec=copyright#v=onepage&q&f=false) by Kak & Rosenfeld (1982) is a classic two-volume set. Some years ago a VP of Cognex said something like the following: everything one needs to know about [machine] vision can be found in Kak & Rosenfeld. That statement was a bit broad even at the time, but it's true enough to be worth contemplating. You might find the two books for as little as U.S. $20.

[**Computer Vision**](https://homepages.inf.ed.ac.uk/rbf/BOOKS/BANDB/bandb.htm) by Ballard and Brown is an old text available online. Fundamental concepts are explained more clearly than in many more recently published textbooks.

[**Digital Image Processing**](https://www.imageprocessingplace.com/) by Gonzalez and Woods has been used for undergraduate courses in image processing. You could write a number of key algorithms using just this book, and without having to slog through too much math.

[**Learning OpenCV**](https://www.oreilly.com/library/view/learning-opencv/9780596516130/) by Bradski & Kaehler is an O'Reilly book about OpenCV, the widely used open source library [OpenCV](https://opencv.org/). If you work in computer/machine vision, you know about OpenCV. There are other open source vision libraries well worth exploring, but you'd do well to start with OpenCV. 

[**Vision**](https://mitpress.mit.edu/9780262514620/vision/) by Marr is a classic 1982 book still in print from MIT Press. Reading or at least skimming Marr's book, along with Kak & Rosenfeld, will give you a sense of what inspired vision research and development in the 1980s and 1990s.  

[**An Introduction to 3D Computer Vision Techniques and Algorithms**](https://www.wiley.com/en-us/An+Introduction+to+3D+Computer+Vision+Techniques+and+Algorithms-p-9781119964476) by Cyganek and Siebert is a great reference if you'll be working with 3D sensors, including passive stereo, active stereo, Kinect-style pattern projection, and so on. 3D vision sensors are suitable for robot guidance and many other applications.

[**Computer Vision: A Modern Approach**](https://www.pearson.com/en-us/subject-catalog/p/computer-vision-a-modern-approach/P200000003374/9780133001921) by Forsyth and Ponce has step-by-step explanations of what have become common techniques.

[**Computer Vision**](https://books.google.com/books/about/Computer_Vision.html?id=FftDAQAAIAAJ) by Shapiro and Stockman includes pseudocode and math that undergraduate students will follow without (much) trouble. 

## A brute-force technique to find the right book(s) for you
Work in digital image processing and computer/machine vision can be a grind if you're doing it right. If you're willing to grind, and if you have a deep passion or at least interest for the subject, then there is a simple way to learn a lot about the field in relatively little time. 

Take a breath. Here's the method:

**Skim every book on image processing and vision in a university engineering library.** Yes, every single book.

Set aside a full day for this exercise.

1. **In advance**, decide on a single goal for your library visit. Write that down. You may want to find your first textbook on vision, or maybe you want to study a single problem in depth.
1. Eat, caffeinate, and gird yourself for the trip.
1. Find the section(s) about computer vision, image processing, and related subjects such as AI. 
1. Start with the very first book (b = 0). Read the table of contents and index. Skim. Judge the writing style.
1. Take notes.
1. b += 1: pick up the next book, and repeat the process.
1. Stop when you've skimmed every book. Every single book. Absolutely every single book, no exceptions.
1. If the library has a collection of theses, conference proceedings, and the like, repeat the process with those, maybe on a second day.

Your library visit will yield rewards that can't be reaped by online searches alone. Why not? A few reasons:

* Buying books gets spendy. Don't just rely on reviews or recommendations--skim the books.
* Books that are out of print may have explanations that click better with your brain.
* Getting away from the computer will help diversify your learning.
* Libraries are magical places.
* Students who are studying vision could be enthusiastic interns, and you might not find those students with your HR bot.
* (AHEM!) Books that aren't currently in vogue, and conference proceedings that few may have read, could contain algorithms, frameworks, or even just hints that you won't find online, and that may help you develop technology that will address an unmet need.

In Boston, Massachusetts, the [Barker Library at MIT](https://libraries.mit.edu/barker/) is a large engineering library [open to the public](https://libguides.mit.edu/visitors). Barker Library houses shelves and shelves of vision books and a collection of theses.

## What about videos?
Videos can be a great supplement to learning. This wiki will eventually host a page on video instruction. 

## Why are there so many more computer vision books than machine vision books?
Most textbooks about digital image processing algorithms are written by academics, which would include researchers, most of whom are professors required to teach a certain number of hours or classes per academic year. Some university staff members may consult, work part time in private industry, or found companies. 

Books that focus on machine vision--digital image processing for industrial applications--are few in number. In the industrial automation industry, there is (typically) little pressure to publish, aside perhaps from [white papers](https://en.wikipedia.org/wiki/White_paper) posted to a company website. Relatively few vision companies have the resources to fund R&D departments, though such companies do exist.

Since the advent of smart phones, GPUs, and cheap(er) computing sufficient to process images at high frame rates, more programmers and engineers have been empowered to build powerful vision technologies into firmware and high-level software for products that aren't specifically "vision" systems. The trend would appear to be a type of sensor fusion of which vision is simply one of several sensing modalities.
  
## Metrology
(Add good reference)

## Safety
(Add good reference, not just links)

## Sensor Fusion
(Add good reference)

## Computational Geometry
[Geometric Tools for Computer Graphics](https://www.geometrictools.com/Books/GeometricTools/AboutTheBook.html) by Schneider and Eberly is a must-have book if you're a developer and your work in vision involves computational geometry. Be sure to download the [extensive corrections](https://www.geometrictools.com/Books/GeometricTools/BookCorrections.html)! 
 
Eberly maintains a [GeometricTools.com](https://www.geometrictools.com/index.html) website with [documentation (white papers) and portable code](https://www.geometrictools.com/Documentation/Documentation.html).

## Machine Communications
Machine vision systems are components of larger production systems. A machine vision system, or a system that incorporates vision, will typically communicate with other machines. The vision system is a black box that provides a decision or measurement as an output. The output data can be communicated optically isolated digital I/O, networks over a variety of protocols

(TODO: insert references about industrial protocols, including older protocols)


## PLC programming
Many thanks to the r/PLC community for the PLC references in their pinned [READ FIRST](https://www.reddit.com/r/PLC/comments/lsa8rc/read_first_how_to_learn_plcs_and_get_into_the/) post:

[Programmable Logic Controllers: An Emphasis on Design and Application
Fourth Edition](https://www.dogwoodvalleypress.com/production2/bookhome.asp?booknum=5) (4th edition) by Kelvin T. Erickson is a 1520-page hardcover. That'd keep you busy for a while.

[Programmable Logic Controllers](https://www.mheducation.com/highered/product/Programmable-Logic-Controllers-Petruzella.html?cid=ppc%7CHE%7CPaid-G-Shop%7Cgoogle%7C&gad_source=1) (6th edition) by Frank Petruzella is another big book at 800+ pages.

(TODO: find a pocket-sized reference)

[Programmable Logic Controllers](https://en.wikipedia.org/wiki/Programmable_logic_controller) (PLCs) form the backbone of many automation systems. A vision system could be one of many systems patched into a PLC. Although a vision system may have its own graphical user interface (GUI) for setup and for runtime monitoring, a PLC may be the primary interface for local users who monitor production processes. A vision system fault (error) would typically be reported to a PLC that controls the work cell or production line.

## Robot programming
Robot guidance is a long-standing application for machine vision systems. For industrial applications, a robot could be a 6-axis industrial arm mounted next to an assembly line, or a small pick-and-place machine integrated into a small work cell. 

But is there a "best" robot programming book for beginners? Consider a textbook for [ROS] (https://www.ros.org/) (Robot Operating System). O'Reilly published a book on ROS in 2015: 

[Programming Robots with ROS: A Practical Introduction to the Robot Operating System](https://www.oreilly.com/library/view/programming-robots-with/9781449325480/)

Open source libraries such as [ROS](https://www.ros.org/) can change rapidly, but make what you can with what you have.

### A friendly caution about ROS, startups, and industrial robots
No matter how cool your vision system is, assume that industrial robot OEMs such as FANUC, ABB, Universal, Kuka, Yaskawa, Kawasaki, and others may **never** provide the level of access to robot internals that you wish you could have. Your vision system may provide data to the robot, but don't assume your vision system will "drive" the robot moment by moment.

If you've sold dozens, hundreds, or thousands of robot guidance systems, and your experience with robot OEMs is different, that's great! 


## Programming in C++, Python, and other languages
There are too many good books and course on programming to mention here. However, in digital image processing a few programming languages are dominant. Just a few titles will be mentioned here for vision enthusiasts who wish to learn programming. [OpenCV](https://opencv.org/) code examples are mostly commonly presented in C++ and Python.

### C++
For C++, consider these titles:
[**Accelerated C++: Practical Programming by Example**](https://books.google.com/books/about/Accelerated_C++.html?id=OaVQAAAAMAAJ&source=kp_book_description) by Koenig and Moo dates back to 2000, but it remains an excellent introduction. 

[**A Tour of C++**](https://www.stroustrup.com/tour3.html) by Bjarne Stroustrop, creator of C++, is a compact book more suitable to programmers with prior experience. If you can afford to buy a new book, get the 3rd edition of the Tour, which covers C++20. Keep in mind that a lot of running, debugged C++ may be written in [C++11](https://en.cppreference.com/w/cpp/11) or earlier. 


### Python
Python is "the" high-level programming language for AI. If you want to work with machine learning models, large language models (LLMs), and other technologies, you'll should learn or at least be able to read and tweak Python code. You might write Python code that calls very fast C++ code (that in turn gets transmogrified into lower-level code, and the turtles go all the way down).

[**Learning Python**](https://learning-python.com/about-lp6e.html) by Mark Lutz is a thick O'Reilly book now in its 6th edition.

[**Learn Python 3 the Hard Way**](https://learnpythonthehardway.org/python3/) by Zed A. Shaw is a short taskmaster's guide. If you like books with a distinct personality, and if you want something small to slip into a travel bag, this is an excellent choice.

### Software Architecture
There are many great books about the design of software, and many of those books are literally hefty. For machine vision developers who want a travel-friendly book about software design, one recent book stands out.

[**A Philosophy of Software Design**](https://web.stanford.edu/~ouster/cgi-bin/book.php) by John Ousterhout is not as widely known as some of the older classics, but Ousterhout provides exceedingly clear guidance in the design of functions and APIs.

### Configuration without Programming
Not all machine vision professionals are programmers. Many of the most widely deployed general purpose machine vision (GPMV) systems are configured, installed, supported, and maintained by applications engineers, field service engineers, skilled trades workers, and technicians without having to write a line of code. The firmware of the vision systems may support many algorithms, including proprietary algorithms, but for individual use cases the system can be confirued using graphical user interfaces, client-server connections, and wiring. This trend toward high-level configuration and creation of commodity vision systems started to take hold in the mid to late 1990s. But someone still needs to write the firmware.

Digital image processing has a decades-long history of being written in the C++ programming language. Image processing and C++ could be said to have grown up together. 

Some textbooks express algorithms in [pseudocode](https://en.wikipedia.org/wiki/Pseudocode). The pseudocode is a guide to implementing an algorithm in any programming language. 

Libraries such as [OpenCV](https://opencv.org/) make it possible to create custom image processing applications using C++, Python, Java, Matlab, Rust, and other languages. OpenCV is a cross-platform library that can be built into apps for smart phones and other devices.
