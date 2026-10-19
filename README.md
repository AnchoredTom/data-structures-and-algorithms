# data-structures-and-algorithms
Project Reflection

What was the problem you were solving in the projects for this course?

In these projects, I worked on a course advising program that could read course information, print a list of courses in alphanumeric order, and look up individual courses and their prerequisites. Project One focused on comparing data structures and planning the program, while Project Two involved turning that plan into working C++ code.

How did you approach the problem? Consider why data structures are important to understand.

I started by comparing a vector, hash table, and binary search tree based on runtime, memory use, and how well each one fit the program's needs. I chose a binary search tree because an in-order traversal can print the courses in alphanumeric order without a separate sorting step. This helped me understand that choosing a data structure affects more than how information is stored. It also affects how a program performs and how easily it meets its requirements.

How did you overcome any roadblocks you encountered while going through the activities or project?

One challenge was making sure the program could both print the courses in the correct order and find individual courses when requested. I worked through this by separating the file loading, searching, and printing tasks and checking how they worked together. I also accounted for missing files, duplicate course numbers, invalid menu choices, and courses that could not be found. Testing those situations helped me catch problems beyond the basic program output.

How has your work on this project expanded your approach to designing software and developing programs?

These projects taught me to spend more time planning before I start writing code. Comparing the data structures and looking at their runtime helped me make a decision based on the program's requirements instead of just choosing what seemed easiest. By the time I started Project Two, I had a clearer idea of how the program should be organized and what each part needed to do.

How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?

I have learned to organize code into smaller parts that are easier to read, test, and update. In Project Two, I kept the binary search tree logic separate from the functions for loading data and interacting with the user. I also used descriptive names, clear error messages, and input handling that accepts course numbers in uppercase or lowercase. These choices make the program easier to maintain and give me a better starting point if its requirements change later.
