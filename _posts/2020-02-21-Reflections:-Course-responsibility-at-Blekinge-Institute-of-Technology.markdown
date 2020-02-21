---
layout: single
excerpt: Thoughts and reflections from the first time I was course responsible for a course.
---
During the spring of 2019 I became course responsible for one of three C++ courses at Blekinge Institute of Technology. This course was given for bachelor students during the first year of the Software Engineering programme and it was the second programming course they encountered; directly following an introductory Python programming course. Since I had been involved in a few other courses at this point (which I plan on writing about in an upcoming post) I knew that there were students that finished this course with a lack of understanding in two important subjects; memory and pointers.

Most glaringly, the students failed to:
1. Understand what pointers are and how data is stored in memory  
  - At a later course they were also expected to understand pointer arithmetic  
2. Understand that the data stored in memory is nothing else but 1's and 0's  
  - They also had to know how to convert from one data-type to another  

Seeing how I at this point had been criticizing the course for years, I felt that it was time for a change. Do note, however, that I was not alone in making this change. I worked close with a colleague that I studied, and co-authored my master thesis, with that had taken over another course. I will return to this point further down.

# Course Literature
The first change conducted was to update the course literature for the course. Originally this had been the book Starting out with C++: Early Objects. A book that I utterly despise. There is no denying that the authors have years of experience in higher education, but the book drags on without covering relevant topics. The international version (8th edition was the one available when this decision was taken) used at Blekinge Institute of Technology is over 1200 pages long and barely covers anything regarding C++11 or the standard library. It feels cluttered with examples and long block of codes spanning multiple pages. Examples and code that rarely give understanding and most students simply nod at while skimming. Some of these issues seems to have been fixed in the 9th edition, ~7-8 years and 2 standards after the release of C++11 (I’m not bitter, you’re bitter). The one thing I enjoy with the book, and a thing that is important to highlight, is the self-studying value it has for the students. The studying questions and projects, when and if ever used, are well written and strikes a great balance in challenge. 

Due to this, I have long felt that it is barely usable outside of the course itself. While some are of the opinion that this is not a problem, I am of a different opinion. I believe that course literature should cover the course and at the same time be usable for the student while they continue their studies. The students should be able to return to the book in a later course within their (computer science) programme and feel that the book still aids them in their learning and understanding of the subject. 

This means that the coursebook should not only be completely updated to use C++11 and the standard library, but also go into the depth of the language and show more than just the basics. Since the students had already finished a programming course and thus were expected to have a grasp of the structure of a program, the book does not necessarily have to cover every bit of the groundwork. 

Now, I was not the one conducting the research for the course literature in the end. Another C++ course given to the 5-year programmes had already changed their course literature and since I had been involved in this other C++ course, I knew that the book in question, C++ Primer, was exactly what I was looking for.

There was, however, another reason as well to why this book was chosen.

# Joint Courses
I was not alone in being a part of the C++ course aimed for the 5-year programmes. The colleague I mentioned earlier and I helped a professor to handle the course during its first iteration during the autumn of 2018 and spring of 2019. He handled the lectures while we supervised the labs, assessed the assignments, and came with factual corrections about the C++ theory presented in the class. Come late spring of 2019, it was decided that my colleague would take over this course at the same time I took over the C++ course for the Software Engineering programme. 

Due to the courses being so similar in structure and the amount of students taking the two courses reaching well over one-hundred and fifty, it was decided that the lectures should be given jointly for the two courses. The labs were not done jointly, since the examinations in and the speed of the courses differentiated. 

# Course Structure
One important change to note is the programming course that came before this C++ course. Previously, the course followed from another C++ course teaching basic syntax and code structure. Due to staff shortage and the steep learning curve, this course was superseded by a Python course that was very well liked by the students. Another important change was the material to be covered and the depth of the course. Suddenly C++11, smart pointers, STL algorithms, and STL containers had been included in the course.

The tool for the course was changed as well, from Visual Studio to Visual Studio Code. This change came from a will to keep the environment platform independent, but also to help students better understand the compiling and linking process. In later courses they were expected to understand makefiles and be able to work with them, when previously their view of compiling code went as far as _”Press F5 to compile”_.

The biggest change to the course was the lectures. (_Sanning med modifikation_ (truth with modification) as my students all to often heard me say during my lectures. I will return to this lie later.) 

For several years this course was given through labs with live-coding and sparse, if any, lectures. This is not necessarily a bad approach; done right it can help enhance the students understanding. Judging by the lack of understanding shown by the students that had passed the course previous years, this had not been the case. Furthermore, with labs hosting ~25 students at a time this approach would result in the presentation of the same material 8-10 times. Not to mention the extra material that had been included, adding 2-5 lectures to this mess. Instead, the main form of teaching became traditionally lectures with slide presentations, each two hours long. These lectures were split more or less evenly between my colleague and I.

The course started with a week where focus was to work with what the students had learned in the Python course and show how this translated into C++. It then quickly moved into the areas covered in this course; object-oriented programming, pointers and memory, the C++ standard library, and template programming.

## The lectures
At Blekinge Institute of Technology there is a lecture hall that is, in my opinion, completely useless. It is flat, so the students in the back can’t see the projector screen over the head of the students in front. The audio system does not always work, which makes it hard to be heard. The sun goes down, quite beautifully I might add, in the ocean just outside, making the screen even harder to see at the wrong time of day. I could go on about this hall, but I believe that it is very apparent that this is the _only_ hall at the institute that can host this amount of students. Thus, it was also the hall were most of the lectures were held.

My colleague and I are very different lecturers, even when using the same form of lecturing. My colleague would go through the concepts and theory in a broader sense, before turning to live-coding and do step-by-step examples. I, on the other hand, kept my code examples on my slides and took a deeper dive into the concepts and theory. Live-coding was saved to the minutes left of the lecture once the presentation was done, as code was presented on the slides themselves were I deemed it necessary.

The students were quickly divided into three camps; those who enjoyed my colleagues lectures more than mine, those that enjoyed my lecture more than my colleagues, and those who stopped showing up. At the last and second to last lectures I held, the week before Christmas 2019, I had a grand total of less than 20 students out of 150 showing up. It was quite a humorous sight, seeing this great hall that so many wanted for their course being so badly utilized.

## The labs
With so many students to supervise and assess, three students and another colleague, to avoid confusions hereafter referred to as the-one-that-stayed-behind---he knows what it means---were employed to help with the labs so that my colleague and I could focus on assessing and polishing lectures and material. While my colleague and I visited the labs often, and on multiple occasions supervised them ourselves, these four were liked by the students and of tremendous help.

Due to the limited space in each computer lab---20-25 places/lab---the students had to be split into smaller groups. All in all, a total of seven lab groups were planned, each having two hours of lab time two times a week.

Most of these lab groups were empty after the first few weeks of the course. It was quickly decided to open up all lab hours for all groups, resulting in a core group of 8-15 students utilizing every minute they could of the labs.

During these labs, the students were expected to work with the examinations of the course; two assignments and one project.

## The assignments
One thing to note about the course was that the assignments expected very little time from the students. Each of the two assignment expected ~13 hours of work, which is very little time to assess anything in depth. The first assignment was for the student to translate a program written in Python to C++, the focus being the differences between Python and C++. The secondary assignment focused on classes, inheritance, and some level of object-oriented programming. Both these assignments were fairly small, posed no bigger problems for active students, and had unit tests written that the students could run at any time.

## The project
Remember that lie I told you about earlier? 

The project was, by far, the biggest change to the course. It went from an open “code what you want” style of project into a very streamlined “everyone does the same” concept. Now, I generally do not have a problem with open-ended projects. But I firmly believe that they cannot be this early in a programme and that multiple things can go wrong with this approach if not great care is taken during supervision of the students. 

I had to often seen students not putting a lot of effort into the project, doing the bare minimum, and get a passing grade. More often than not, these students would then go on to other computer science courses were they would promptly get a failing grade. As mentioned earlier, the most common subjects these students had failed to grasp were pointers and memory. From this information, a new project was born.

In this new project, the students were expected to build a non-traditional _Heap Allocator_ from a given explanation. Heavy constraints were put on this allocator when it came to member function signatures and member variables. The students were only allowed to have a grand total of two variables; one for the first memory address and one for the first free block. They also had to implement an internal struct to hold header-data and store all headers inside the memory of the free blocks. To make sure that they conformed to these constraints, a special test-suite was created, completely written in C++17 and compilable regardless of compiler and level of completion. To aid the students in this task, a longer tutorial was created wherein a _Stack Allocator_ was created step-by-step.

A small core group of 8-15 students worked every lab, and a lot of free time, with this project. I am remarkably proud of these students. Not only did they produce really good project implementations and results, but they worked well together and really utilized the supervisors to quickly handle misunderstanding. 

Of course, this does not mean that the students were happy or satisfied with the course.

# Student course evaluation
The course evaluation was abysmal with a score of 2.2 (with 5 being the highest), some even saying that it was the worst course they had ever had (also their third). The average score for a course at Blekinge Institute of Technology at this time was 3.3. The students criticised the lectures that were to long, didn’t involve the students, and went to deep theoretically. They criticised the pedagogical capacity of the lecturers and the substandard reading instructions. The point they criticised the most was the project.

The consensus from the students was that the project had a to high level and demanded way to much time, especially since it was placed over the holidays. However, the students that finished the project, while still critical to parts of it, commented on how much they had learned and that they had never learned so much in such a short span of time.

Many students felt that this course had been a lot harder than it had to be, but one thing was quite interesting with the comments written in the course evaluation. Those students that had been active during the labs and finished the project were already positive looking forward to follow-up courses and using this new knowledge.

The one thing most, if not all, that submitted comments in the course highlighted was the labs and the help they could get there. The ones supervising, employed students and teachers alike, were all highlighted as an essential part that really helped the students in their learning.

# Reflections
Unfortunately, I left Blekinge Institute of Technology due to personal reasons, including a lack of faith in the HR-department, before this course was concluded. This really did not help the students, since the extra labs I had planned to have after the holiday to help them get on track before deadline never happened. However, I kept in touch with the-one-that-stayed-behind and got continuous update until the course had been finished.

Most of the points brought up in the course evaluation were known since beforehand, even if I personally do not agree with all of them. The project, for instance, was not to hard. The lack of a bridge between the assignments and the project was a real problem, one that could not be mended due to the lacklustre amount of credits for the assignments. That the exam at the end of the course also gave the majority of the credits did not help the students to feel that the project was worth it. The credits for the project reflected ~55 hours of work; most students reported less hours worked than that. However, I believe that there are some unrecorded hours in there for students that worked way more.

We knew after the first few weeks that the lectures would be a problem, something we tried to mend with an extra lecture clarifying the connection between Python and C++. One important misconception was that the Python course leading to this course was to learn Python. In reality the focus was more on programming structure and building blocks like statements and conditions. This lead to many students learning the Python-how, not the programming-how; something they were unable to translate into C++. As such, the first week’s lectures did not work out very well for the students as they thought they had to re-learn everything, when in reality they only needed to learn new syntax. One common complaint was that the first three weeks covered so much in the book. It did not help telling the students that these chapters were to skim and be connected to Python, and that they did not have to learn anything they had not done before in a different context. The extra lecture was appreciated by the students that attended.

Another source of problem was the labs. Or rather the lack of students attending these labs. Many students either just gave up on the course when the lecturing style did not fit them or they felt that it was more work than it was worth, or they felt that they were better of at home. Because the labs were almost completely empty. As mentioned earlier, there was this core group that really utilized the labs, but many students failed to show up. This really did not help them in their learning; something that was apparent during the assessing of the assignments. The labs are also an important place for group discussions and voicing opinions, something that they now missed out on.

One problem with the course that was outside of my control, but I had brought to the attention of the institute multiple times, was the course syllabus. I have already mentioned the credit distribution, but one thing that really made it all worse was the content that had to be in the course and the way the syllabus forced certain aspects. I will not go into all to much detail, but it is my hope that Blekinge Institute of Technology really put work into updating and heavily rewrites this syllabus. It was a real pain to work with it.

All in all, I believe that something good could come out of the change I contributed to this course. I have left out a lot in this summary. Things I did not feel would add anything or that are big enough to write a separate post about. I am certain this concept, especially the project, can be iterated upon for the better given some time. It is my firmest believe that the students that took this course with me and passed, or even only came halfway through, the project will become highly skilled C++ programmers; without a doubt surpassing me.

Unfortunately, I will not be the one doing this iterating.