java c
Database Development and Design (DTS207TC) 
Assessment 002: Individual Coursework
Due: Dec 24th, 2024 @ 23:59
Weight: 40%
Maximum Marks: 100
Overview  Outcomes 
This course work will be assessed for the following learning outcomes:
C. Illustrate the issues related to Web technologies and DBMS and XML as a semi-structured data representation formalism.
D. Identify the principles underlying object-relational models.
Submission 
You must submit the following files to LMO:
1)A report named as Your_Student_ID.pdf.
2)A directory containing all your source code, named as Your_Student_ID_code.NOTE: The report shall be in A4 size, size 11 font, and shall not exceed 8 pages in length. You can include only key code snippets in your reports. The complete source code can be placed in the attachment.
Assessment Tasks 
Now we have some stock-related datasets in XML format (attached). We would like to put it on a website for users to query.
1)   Browse through these XML files in the attachment, and define DTD and XML Schema for  them. Use both definitions to validate the XML files and manually fix any potential errors. Extract the file headers from the XML Schema and convert the XML to CSV. Open the generated CSV with any editor and take a screenshot. (20 Marks)
2)   Use flask_sqlalchemy in Flask to build an ORM for the CSV from task 1), and import the   data into PostgreSQL. Manually draw an Entity-Relationship diagram for the three tables, take a photo, and include it in the report. (20 Marks)
3)   Use Flask to implement the required web page as shown in the diagram, which includes a  table with the necessary fields. To differentiate yourself, you can set the form. style. to your preference and take a screenshot. (20 Marks)

4)   Based on task 3), add filtering functionalities for stock name, start time, and end time,
implementing a page as shown below. Note that one or more of these filter conditions can be empty, meaning no filtering based on that condition. To differentiate yourself, you can  set the form. style. to your preference and take a screenshot. (20 Marks)

5)   Use the provided testing program to perform. a performance test on task 4). The program   uses a POST request to query with all conditions set to empty, which should return the full  result set. As long as the returned content is correct, you can optimize performance in any  way. Take a screenshot of the test results. Ideal performance should be no higher than 0.2 seconds per query. (20 Marks)
NOTE:
a.    Provide a brief introduction to the program logic in your own words; including code
snippets is encouraged, but please do not directly paste the entire program into the report without explanation;b.   For your full academic development, the use of generative AI to gain inspiration is allowed  for this assignment; however, out of mutual respect, please do not directly paste its output into your assignment and submit it;
c.   To prove that you have indeed c代 写Database Development and Design (DTS207TC) Assessment 002: Individual CourseworkSQL
代做程序编程语言ompleted this assignment and did not rely solely on generative AI, please provide screenshots of the running results for each task
Marking Criteria 
The tasks in this assessment can be divided into 3 categories:
Charts Presentation  Analysis;
Essay;
Programs.
Criteria(%) 
Exemplary 
(100) 
Good (75) 
Satisfactory (50) 
Limited (25) 
Very Limited (0) 
Design 
Provides a 
detailed, 
accurate 
description of the methods. Provide 
comprehensive comparison 
between the methods, 
including pros and cons, 
performance analysis. 
The analysis provided 
demonstrates that the 
student's 
understanding of the various methods is 
correct and 
that they have the ability to 
solve problems independently. Although there 
are certain flaws, or 
incomplete. 
Provides 
adequate 
description of the methods. Comparison is provided with some level of details, however, with some obvious mistakes. 
There are obvious deviations in the understanding of the main 
methods, and it 
fails to reflect the ability to 
independently 
design 
algorithms. The 
description of the problem is vague, or the thought is incomplete. Limited or no description of methods. 
Limited 
comparison provided. 
Programs 
Demonstrated correctly 
implemented code that 
produces 
correct output. 
Excellent 
coding quality follows best 
practices. 
The program runs correctly and gives the expected 
results. 
However, 
special cases are not fully 
considered, or the program performs 
redundant 
calculations. Program basically works 
correctly for major 
functionality, however, with some 
conceptional problems. 
The program 
implements some minor 
functionality, or incorrectly 
implements major 
functionality. 
There is a certain degree of 
misunderstanding 
about the 
requirements of the questions. 
Program 
works 
incorrectly with limited attempt or irrelevant to the task. 
Charts 
Excellent 
Most of the 
Moderate 
Only some of the 
Limited or no 
Presentation 
quality of 
results in the 
quality of 
results in the 
attempt of 
 Analysis 
report with 
chart are 
report with 
chart are correct, 
report. 

clear structure, 
correct, but 
basic 
or some of them 


clear logic, 
there is a 
structure, 
are not filled in. 


concise writing, pleasing visual aids. 
certain degree of sloppy or 
wordy in the overview and analysis. 
where writing and visual aids 
can be 
improved. 
The analysis of 
the results was 
obviously biased. 

The mark allocations for the above tasks are:
Task 
Design 
Programs 
Charts Presentation  Analysis 
1 
0 
17 
3 
2 
15 
5 
0 
3 
10 
5 
5 
4 
0 
15 
5 
5 
10 
8 
2 



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
