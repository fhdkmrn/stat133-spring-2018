## stat133-spring-2018

This repository holds the course materials for the Spring 2018 edition of 
__Statistics 133: Concepts in Computing with Data__ at UC Berkeley.


- __Instructor:__ [Gaston Sanchez](http://gastonsanchez.com), gasigiri [at] berkeley [dot] edu
- __Class Time:__ MWF 8-9am in [Dwinelle 155](http://www.berkeley.edu/map?dwinelle)
- __Session Dates:__ 01/17/18 - 05/04/18
- __Code #:__ 30844
- __Units:__ 3 (more info [here](http://classes.berkeley.edu/content/2018-spring-stat-133-001-lec-001))
- __Office Hours:__ MWF 1-2pm 309 Evans
- __Final:__ Mon May 7, 8-11am (room TBD)
- __Piazza:__ [piazza.com/berkeley/spring2018/stat133](https://piazza.com/berkeley/spring2018/stat133)
- __GSIs:__ Office hours of the GSIs displayed below.
You can go to the office hours of __any__ GSI, not just your own.

| GSI          | Office Hours in 342 |
|:-------------|:--------------|
| Jin Kweon    | M Tu 9 - 11am |
| Da Xu        | W 4-6pm, Th 8-9am & 5-6 pm |
| Minchul Shin | M 10:30am-12:30pm, Th 5-7 pm |
| Ninh Do      | M 8-11am, Th 8-9 am |
| Qi Chen      | M 3-5pm, Tu 8-10 am |

- __Lab Sections:__

| Lab | Date       | Room         | GSI             |
|-----|------------|--------------|-----------------|
| 101 | W 10-12pm  | 342 Evans    | Jin Kweon       |
| 102 | W 12-2pm   | 340 Evans    | Qi Chen         |
| 103 | W 12-2pm   | 342 Evans    | Ninh Do         |
| 104 | W 2-4pm    | 340 Evans    | Qi Chen         |
| 105 | W 2-4pm    | 342 Evans    | Rui Chen        |
| 106 | Th 9-11am  | 342 Evans    | Ninh Do         |
| 107 | Th 9-11am  | 330 Evans    | Da Xu           |
| 108 | Th 11-1pm  | 342 Evans    | Jin Kweon       |
| 109 | Th 11-1pm  | 330 Evans    | Rui Chen        |
| 110 | Th 1-3pm   | 342 Evans    | Minchul Shin    |
| 111 | Th 2-4pm   | 340 Evans    | Da Xu           |
| 112 | Th 3-5pm   | 342 Evans    | Minchul Shin    |


-----


### Philosophy

__Concepts in Computing with Data__ presents computing tools and basic concepts 
for the main stages of the _Data Analysis Cycle_ (DAC): 1) data preparation, 
2) actual analysis, and 3) reporting of results. 

<img src="images/data-by-the-numbers.png" width="700" height="300">

Traditionally, teaching has been focused on the actual analysis part of a data 
set (e.g. description, hypothesis testing, modeling, validation) while leaving 
out the data preparation steps, as well as the presentation and reporting of results. 
This is nuts. Typically, the most time consuming parts in the _DAC_ are the 
preparation of data (e.g. cleaning, reformatting, tidying), and the report and 
communication of results (e.g. images, tables, papers, presentations, reports, docs). 
However, we don't teach students how to approach these tasks. They are left alone 
to acquire them in the wild. Stat 133 aims to add its two cents to provide solid 
foundations that will help you crunch data in a less 
improvised/naive/inefficient way.


### Description

__Stat 133: Concepts in Computing with Data__ is an introductory course to computational 
data analysis using the statistical programming language __R__ (and other computational tools)
with an emphasis on five major cornerstones:

- Data Manipulation (wrangling, reshaping, tidying)
- Data Visualization (focus on statistical charts)
- Programming Concepts (with emphasis on data analysis)
- Data Technologies (various sources/formats of data)
- Reporting Tools (via dynamic documents)

Because Stat 133 is one of the core courses of the Statistics Department,
the underlying goal is to provide foundations for "computing with data" so students 
have the basic computational skills for subsequent 
upper division courses (e.g. Stat 150, 151A, 152, 153, 154, 155, 157, 158, 159).
This involves teaching students how to:

- understand common data formats
- use the computer extensively to conduct statistical analysis of data.
- use existing software rather than build routines from the ground up.
- understand how to visualize data and display statistical information
- learn the basic principles for writing code
- organize your workflow
- focus on aspects of computing to conduct data analysis, NOT the 
computational aspects of statistical methods
- use computational tools to carry out the data analysis cycle

For more details, check the [syllabus](syllabus/README.md)


### Prerequisites / Review

This course does not have any prerequisites, although it would be nice if you 
have taken an introductory course in statistics (e.g. Stat 2, 20, 21, 131A). 

The curriculum and format is designed specifically for students (ideally 
majoring in Statistics) __who have NOT taken computer science courses__.

You don't need previous programming experience, and you also don't need previous
data analysis experience. However, students with some exposure to programming
concepts, and data analysis tend to understand certain concepts better.

Students with some prior experience in either computational statistics 
or computing are welcome to enroll, though some parts of the course will feel 
extremely slow. 
Students who have taken computer science courses (e.g. CS C8, CS C100, CS 9H, 
CS 61a, CS 61b) should instead take a more advanced course.



### Expectations

We expect that, at the end of the course, you have a basic understanding of R. 
But more important, we expect that you understand the general principles of 
data analysis projects, independently of the programming
language that you use.

After completing the course, we expect that you feel comfortable in any of 
the three stages of the _Data Analysis Cycle (DAC)_. This means that 
you can take almost any data set(s), clean it, tidy it, get visualizations, 
write code, and report the results in a varied number of formats.

We don't expect you to become a jedi data scientist, an R ninja, or a super coder. 
That takes YEARS of practice, training, learning, and collaborating. Instead, 
we want you to become a skilled [padawan](http://starwars.wikia.com/wiki/Padawan) 
analyst (which, if interested, can be prepared to take the next steps of a data 
science marathon race).



### Methods of Instruction

We will be using a combination of materials such as slides, tutorials, 
reading assignments, and chalk-and-talk.

The main computational tool will be the [computing and programming environment R](https://www.r-project.org/). 
The main workbench will be the IDE [RStudio](https://www.rstudio.com/).
You will also use a terminal emulator to work with command line.



### Other

- Please read the course [logistics and policies](syllabus/policies.md), and the [piazza etiquette rules](syllabus/piazza.md) for more details
about the structure of the course, DO's and DONT's, etc.

<a href="syllabus/policies.md"><img src="images/it-is-in-the-syllabus.png" width="580" height="330"></a>

- I've prepared a list of [Frequently Asked Questions](syllabus/faqs.md) that I get asked 
every semester.



-----

### License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Unless otherwise noticed, this work, by Gaston Sanchez, is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

Author: [Gaston Sanchez](http://gastonsanchez.com)
