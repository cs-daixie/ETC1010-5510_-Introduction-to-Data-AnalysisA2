ETC1010-5510: Introduction to Data
Analysis
Assignment 2
Instructions to Students
This is an individual assignment and you must work on it on your own. Collaboration on the
assignment constitute collusion. For more on collusion and misconduct please see this webpage.
(https://connect.monash.edu/s/article/FAQ-2144)
This assignment gets you to use R to complete tasks and for you to explain your results in sentences.
Please make sure you read the hints throughout the assignment to help guide you on the tasks.
The points allocated for each of the elements in the assignment are marked in the questions and in certain
cases.
Marking + Grades
This assignment is out of 65 and will be worth 15% of your total grade. Due on: Tuesday, 15 October 2024,
4:30 PM (Melbourne time).
There are two sections: Part A and Part B. Part A is out of 26. Part B is out of 39.
For this assignment, you will need to upload the following into Moodle:
The rendered html file saved as a pdf. The assignment will be only marked if the pdf is uploaded in
Moodle. The submitted assignment pdf file must have all the code and output visible.
At a minimum, your assignment should be able to be “knitted” using the Knit button for your
Rmarkdown document so that you can produce a html file that you will save as pdf file and upload it into
Moodle.
If you want to look at what the assignment looks like as you progress , remember that you can set the R chunk
options to eval = FALSE like so to ensure that you can knit the file:
If you use eval = FALSE or echo = FALSE , please remember to ensure that you have set to eval = TRUE
and echo = TRUE when you submit the assignment, to ensure all your R codes run.
IMPORTANT: You must use R code to answer all the questions in the report.
Due Date
This assignment is due on Tuesday, 15 October 2024, 4:30 PM. You will submit the knitted html file saved as a
pdf via Moodle. Please make sure you add your name on the YAML part of the Rmd file before you knit it and
save it as pdf.
The answers to some questions are subjective, so in a few sentences explain what you think. DO NOT use dot
points.
There is less scaffolding in this assignment than in Assignment 1. You should write whatever code you think
helps answer the question.
You need to keep your code neat - you will be graded on the presentation quality of your code.
Libraries
You will need to use:
RColorBrewer
ggdendro
Part A: A little bit of visualisation
In Part A we will look at some visualisations using the Harry Potter data from the lectures.
The dataset hp_chars.csv contains an excerpt list of student characters from the novels. The variables in the
dataset are as follows.
name - name of a student character.
schoolyear - the year in which the student began at Hogwarts.
house - the house in which the sorting hat placed said student.
The dataset hp_edges.csv contains data on which characters in the first dataset (recorded under name in
hp_chars.csv ) conversed with other characters in that list, and in which books. In both datasets, the list is
incomplete. Not all character conversations are recorded, and not all students are represented. The variables
in this dataset are as follows.
name1 - name of a student wizarding character.
name2 - name of a student wizarding character whom the character in name1 spoke to.
book - In which book the conversation took place.
Read in the data
Part A.1
Question 1
Using the hp_chars data, present a table that shows which houses have the highest proportion of male
students. (3pts)
Question 2
Represent this information visually using barcharts. Load the RColorBrewer package and use the Set1 colour
scheme. Hint: use the position="fill" option. (2pts)
Question 3
In one or two sentences, describe what this graph tells us. (2 pts)
Question 4
Using the Dark2 color scheme, visually represent the counts by gender using the dodge option. (2pts).
Question 5
In one or two sentences, describe what this graph tells us. (2 pts)

# ETC1010-5510 Introduction to Data AnalysisA2

# 程序代做代写辅导

# 专业辅导，已辅导上千名留学生，帮助其获得高分

# Contact Me

# WeChat robotclx

# CS Professional Tutoring

# I can help you for Python,Java,C,C#,C++,Javascript,html,go,rust,database......

# 英国，澳洲，美国，日本，韩国等各国均可辅导，均可提供服务

# 在要求的范围内，可免费售后，可走平台

# 记得备注您是从github来的哦~

# Email bu32221@163.com
