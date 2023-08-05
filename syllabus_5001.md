# Syllabus
## PSYO 5001: Graduate Independent Study in Neural Data Science

### Fall 2021-22
September 6 – December 7, 2022

#### version 2.0 2022-09-09

### Instructor
[Dr. Aaron Newman](http://aaronjnewman.com) ([Aaron.Newman@dal.ca](mailto:Aaron.Newman@dal.ca))

---

## Contents:
- [Course Description](#course-description)
- [Background & Rationale](#background-and-rationale)
- [Learning Objectives](#learning-objectives)
- [Format](#course-format)
- [Materials](#course-materials)
- [Assessment & Evaluation](#assessment-and-evaluation)
- [Grading](#grading)
- [Schedule](#schedule)
- [Policies](#policies)

---

## Recognition of Mi’kmaq Territory
Dalhousie University is located in Mi’kma’ki, the ancestral and unceded territory of the Mi’kmaq. We are all Treaty people. The Elders in Residence program provides students with access to First Nations elders for guidance, counsel and support. Visit the [Indigenous Student Centre](https://www.dal.ca/campus_life/communities/indigenous.html) or contact the programs at [elders@dal.ca](mailto:elders@dal.ca).

## Diversity and Inclusion – Culture of Respect
Every person at Dalhousie has a right to be respected and safe. We believe inclusiveness is fundamental to education. We stand for equality. Dalhousie is strengthened in our diversity. We are a respectful and inclusive community. We are committed to being a place where everyone feels welcome and supported, which is why our Strategic Direction prioritizes fostering a culture of diversity and inclusiveness. For more information please see [here](http://www.dal.ca/cultureofrespect.html).

---
# Course Description

An introduction to data management, manipulation, visualization, and analysis for neuroscience. Students will learn scientific programming in Python, and use this to work with example data from areas such as cognitive-behavioural research, single-cell recording, EEG, and structural and functional MRI. Basic signal processing techniques including filtering will be covered.

**This is a graduate version of NESC (PSYO) 3505 *Neural Data Science***. Students enrolled in the PSYO 5001 variant of the course will follow the curriculum of NESC 3505, completing all lessons and assignments. In addition, graduate students will complete an additional term project not required of undergraduate students. This project will be worth 25% of the final grade (with the undergraduate evaluation components' weights pro-rated accordingly). The topic and scope of the project will be determined individually between the student and instructor. In general, such projects will build on the course material, such as applying and possibly extending material from the course to other data relevant to the student's interests, or exploration of a topic in data science not covered in the undergraduate curriculum.


## Prerequisites
Instructor's permission

# Background and Rationale
Most areas of neuroscience research and development rely on increasingly large and complex data sets. Discovery and application in neuroscience thus relies on the ability to manage these large data sets, and extract meaning from them. In other words, neuroscience now relies heavily on **data science**, which has been variously defined as “…an umbrella term to describe the entire complex and multistep processes used to extract value from data.” (Wing, 2019) and the ability to “bring structure to large quantities of formless data and make analysis possible” (Davenport & Patil, 2012, p.73).

**In neuroscience, data science is an increasingly necessary skill.** Data from techniques like single-cell recordings, local field potentials, EEG, and fMRI is complex and multidimensional. Being able to understand, manipulate, and visualize the structure of these complex datasets is a necessary skill for performing the research. On top of this, it is increasingly clear that very large data sets - often built collaboratively by many labs - are required to make reliable inferences about neuroscientific processes. Making inferences also depends on computational models - ways of identifying and representing patterns in the data. While some of these will be familiar from statistics class, a wide range of statistical and machine learning models are now widely used in neuroscience.

While data science and statistics are overlapping fields, statistics is generally focused on the specific task of testing hypotheses based on data. Data science more broadly includes the storage, manipulation, visualization, filtering, and preparation of data that is typically required prior to statistical analysis. Data science does also encompass statistics, as well as machine learning; whereas statistics generally involves deriving conclusions from existing data, machine learning involves making predictions from a data set that will generalize to other data. Since statistics is covered in other courses in the neuroscience and psychology curricula, this course focuses instead on the other “front-end” aspects of data science described above. Other areas of data science, including “back-end” data science (engineering, hardware, databases) and software development, will not be covered.

Central to data science is the ability to use scientific programming languages, such as Python, Matlab, and R. This ability includes a strong understanding of the fundamentals of at least one programming language, and the ability to extend one’s knowledge through continuous learning and problem-solving. This course teaches Python, a mature and widely-used language in neuroscience and data science more broadly. However, much of the fundamentals of scientific programming and data science are common to all languages. Thus, having learned Python, you will be better prepared to learn new languages in the future, as necessary.

Another important facet of data science is that it is a **team endeavour**. On the one hand, it is founded on open, shared software developed by widely distributed teams of contributors. On the other hand, the practice of data science typically involves teams of individuals with complementary skillsets, both due to the size and complexity of many projects. In science, these teams often comprise students and faculty members in collaborating labs distributed around the world. This class prepares you for such collaboration by developing and coaching your teamwork skills, as well as teaching you how to use software platforms that support such collaboration.

The skills learned in this class will benefit students working in a wide variety of areas of neuroscience. As well, the class will provide an introductory foundation in data science that can be applied to a wide range of areas of research and application, in academia, industry, and government.

### References:
Davenport, T. H., & Patil, D. J. (2012). Data scientist. *Harvard Business Review*, 90(5), 70-76

Irizarry, R. A. (2020). The role of academia in data science education. *Harvard Data Science Review*, 2(1). https://doi.org/10.1162/99608f92.dd363929

Wing, J. M. (2019). The data life cycle. *Harvard Data Science Review*. https://doi.org/10.1162/99608f92.e26845b4

# Learning Objectives
## Hard Skills
- Extract meaning from data, but also articulate the limitations of the conclusions you can draw from it
- Write functional and efficient code in Python to perform basic data science tasks
- Use online tools for collaborative software development and project management
- Read and write data files in common formats such as CSV and Excel
- Organize and manipulate data structures
- Work with continuous, discrete, and factorial data
- Visualize data in a variety of graphical formats
- Perform exploratory data analysis using graphical and basic statistical operations
- Perform basic signal processing on data, such as filtering in temporal and spatial dimensions
- Build and run data processing pipelines on various types of neuroscientific data, including single unit recordings, time series, and 2D/3D/4D images
- Understand basic concepts and common tools used in machine learning, including deep neural networks
- Extend your skills using online resources

## Soft Skills
- Demonstrate a professional work ethic
- Be effective and productive in a hybrid in-person/remote working environment
- Work collaboratively, effectively, and productively in a distributed team
- Manage projects: manage time and human resources effectively to achieve specific objectives on a stated timeline
- Peer-review the work of other team members
- Teach others skills and solutions you discover, and communicate your approach to discovering these
- Articulate your strengths and weaknesses as a data scientist working in a team, and identify ways to improve your abilities
- Demonstrate skills you have developed using a portfolio of work, to potential supervisors/employers
- Use, and communicate the value of, open and reproducible code and data

# Course Format
This course employs a hybrid online/in-person format, although it can be completed entirely online for people who are unable to attend the weekly lab sessions. The course consists of the following components:
- [Freely-accessible online **textbook**](https://neural-data-science.github.io/NESC_3505_textbook/)
- Asynchronous **online lectures**
- Optional  **check-ins** meetings with the instructor every 2 weeks or so, at mutual agreement of instructor and student(s)
- Online tutorials and practice through **DataCamp**, a massive online education platform for data science


## Online Lectures and Tutorials
This course employs a “flipped classroom” model. Lectures and tutorials are available in the [online textbook](https://neural-data-science.github.io/NESC_3505_textbook/) and/or as pre-recorded videos, available online for viewing at any time. Many of these lessons involve quizzes and coding activities. **This course requires that you put in significant hours per week outside of class:you should budget 8 h/week for work on the course, including the 2 h/week lab time.**

## Check-Ins
A biweekly meeting will be scheduled between the instructor and student(s) to check in on progress and answer questions.

## Getting Help
One of the course learning objectives is "Extend your skills using online resources", and the course is based on the learning theory of [connectivism](https://neural-data-science.github.io/NESC_3505_textbook/1/connectivism.html). You are encouraged and supported in taking a *lifelong learning* approach to solving problems in this course. Many of the evaluations expect you to engage in this; you will not find all the answers in the textbook.

That said, learning can sometimes go a lot faster when you ask questions. We encourage you to ask questions of your peers in the class, and of the teaching team — in that order. Peer teaching is built into the class through collaboration tools, demos, and team projects. This is the way real, functional teams operate — supporting each other to achieve more.

The course Teams site is where you should direct all your questions (after making your own attempts to research and solve your problem). This can include posting questions in the messaging forums, or joining live check-ins to ask questions. Please do not email the teaching team with questions about the class — use the Teams site. Do feel free to email the instructor if you have personal topics that you need to discuss privately, or you can use direct messaging on Teams.

# Course Materials
All necessary materials (including the textbook) will be provided online, through the course Teams site. **You must have access to a computer** running a recent version of the Mac, Windows, Chrome, or Linux operating systems. It may be possible to complete this course, including programming assignments, using an iPad, but this has not been verified. It is not a good idea to expect to be able to complete the course using only a mobile device (phone or tablet).

**You must also have access to internet service** of sufficient quality to stream videos and maintain a live connection to remote servers. Provisions will be made if students cannot participate in live audio/video sessions due to internet constraints; please contact the instructor to discuss if this is an issue for you.

Beyond these basic requirements, this course emphasizes (and will teach you about) openly accessible resources including the software that runs the course, open access to the course materials, and the use of external resources that are available for free. No textbook is required. This course will rely on [Open Educational Resources](https://neural-data-science.github.io/NESC_3505_textbook/1/oer_this_course.html) — materials that are freely accessible and openly licensed — including online tutorials, videos, and books. A wide variety of educational materials (free and paid) for data science are available, and this course teaches an approach to lifelong learning and exploration by which you will be able to find and critically evaluate the information necessary to perform desired tasks.

# Assessment and Evaluation
Your final grade will be based on a combination of [*formative assessments*](https://neural-data-science.github.io/NESC_3505_textbook/1/assessment_evaluation.html) (self and peer evaluations) and [*summative evaluations*](https://neural-data-science.github.io/NESC_3505_textbook/1/assessment_evaluation.html) (presentations, assignments, projects). Each component is described below, followed by a table showing the number and point weighting of each.

The items you're graded on are divided into two categories:
- **Formative assessments** are designed to support you in improving your performance in the class (they help "form" you), through self-assessment, peer assessment, and instructor feedback. These are designed to require little time to complete. They contribute a small proportion of your grade (10%), but they are all graded as pass/fail, so you get the full XP for completing them. Thus collectively they can make a significant difference in your grade.
- **Summative evaluations** comprise the majority (90%) of your final grade. These are meant to *summarize* your learning. All summative evaluations are graded.

The grading system is built to be **inclusive and adaptive** to the needs and life circumstances of individual students. While some assessments are not accepted after the due date, and some evaluations have late penalties, we recognize that missed or late assignments sometimes happen for excusable reasons. Rather than making a big deal about your proving to us that your reason is legitimate, we instead provide options *built right into the course* for you to make up lost points in other ways, including skipping a missed assignment in some cases, or having your worst mark on certain items (like assignments) be worth much fewer points. Because there are a variety of bonus points on offer, there are actually more opportunities to earn points than you need to get an A+ in the course. This means that you can, within reason, pick and choose how to achieve your desired grade. That said, your grade is intended to reflect the degree to which you have met the learning objectives, so you do need to demonstrate competence with regard to all of the objectives.

Due dates for all assessment and evaluation components will be posted on Teams.

## Formative Assessments

### Online Lessons/Practice: DataCamp
Registered students are provided with free access to the DataCamp massive online learning community. A number of DataCamp lessons are assigned in the schedule to align with the course content. They are meant to reinforce the textbook/lecture material, and provide opportunities to practice coding with immediate feedback. As well, there are several optional DataCamp lessons that you'll see suggested when you log onto your DataCamp account. You can get course credit for completing both the lessons assigned in the schedule, and any additional lessons on DataCamp that interest you (even ones not suggested by the instructor - choose your own adventure!)

Grading for DataCamp lessons is based on XP assigned by the DataCamp platform. You earn XP incrementally by completing lessons, so if you complete part of a lesson you get part of the total XP. Your DataCamp work is graded pass/fail on the basis of how many XP you earn. Your earned DataCamp XP (up to 25,000 XP) are used to compute your grade (5,000 DataCamp XP = 1% course grade).

DataCamp lessons can be completed later than the posted due date, up to the last day of class, with no penalty. However, not completing lessons by the posted due dates will leave you less prepared for future classes and assignments. No points for lessons will be granted after the last day of classes in the term.

## Summative Evaluations
For all summative evaluations, **late work will be penalized 2% per hour**, with the clock starting the minute after the deadline has elapsed. **Requests for extensions will only be considered prior to the due date**.

### Assignments
These are coding assignments that you will complete, based on psychology and neuroscience data.

### Projects
There are 2 individual, self-directed projects to complete. These projects should be defined *in advance* of working on them, between the student and instructor. The projects should be based on the material covered in the course, but can use data that the student has acquired, or other data (e.g., open source). The instructor may be able to provide data sets and advice on these, but students are encouraged to define projects that help support their learning goals and/or or degree-related research projects.


# Grading
This course follows the [Dalhousie Faculty of Graduate Studies grading scale](https://www.dal.ca/dept/university_secretariat/policies/academic/grading-practices-policy.html). The table below lists the point values of individual grading items, which total 13,333. Your grade is based on the percentage of 13,333 points that you earn (including bonus points).

## How to Earn Points
The table below lists all the "core" and "bonus" opportunities to earn points in this course.

| **Summative Evaluations (graded)**     | **% of final grade** |
|----------------------------------------|----------------------|
| ***Assignments***                      |                      |
| Assignment 1                           | 5                    |
| Assignment 2                           | 10                   |
| Assignment 3                           | 10                   |
| Assignment 4                           | 10                   |
| Assignment 5                           | 10                   |
| ***Projects***                         |                      |
| Project 1                              | 25                   |
| Project 2                              | 25                   |
| **Formative Assessments (Pass/Fail)**  |                      |
| ***Datacamp lessons***: 1% per 5000 XP | 5                    |
| **Totals**                             | 100                  |

# Schedule

[Click here to see the schedule](https://neural-data-science.github.io/NESC_3505/schedule.html).

# Policies
This course is governed by the academic rules and regulations set forth in the University Calendar and by Senate.

## Attendance
Attendance of scheduled class meetings is optional. However, due to the flipped classroom model, scheduled class times are the only time when you can get live help with the course material. However, if you have other issues you need to discuss (e.g., personal reasons that make it difficult for you to succeed in the class), you may contact the instructor by email to discuss the matter and/or set up a meeting.

## Academic Freedom
Freedom of speech and of thought are cornerstones of academic institutions such as Dalhousie. Our goal in science is to observe and characterize the world accurately and objectively. However, we must realize that our perceptions of reality are often coloured by our beliefs and assumptions, some of which we may not be aware of. Academic freedom includes not only the freedom to think as you please, but others’ freedom to express their beliefs as well. Please do not hesitate to express your ideas, but do so in a way that is respectful of others. This is the only avenue for the free expression and exchange of ideas.

## Academic Integrity
At Dalhousie University, we are guided in all of our work by the values of academic integrity: honesty, trust, fairness, responsibility and respect (The Center for Academic Integrity, Duke University, 1999). As a student, you are required to demonstrate these values in all of the work you do. The University provides policies and procedures that every member of the university community is required to follow to ensure academic integrity. For more details please see: [https://www.dal.ca/dept/university\_secretariat/academic-integrity.html](https://www.dal.ca/dept/university\_secretariat/academic-integrity.html)  

## Accessibility
The Advising and Access Services Centre is Dalhousie's centre of expertise for student accessibility and accommodation. The advising team works with students who request accommodation as a result of a disability, religious obligation, or any barrier related to any other characteristic protected under Human Rights legislation (Canada and Nova Scotia).
Information: [https://www.dal.ca/campus\_life/academic-support/accessibility.html](https://www.dal.ca/campus\_life/academic-support/accessibility.html)

## Code of Student Conduct
Everyone at Dalhousie is expected to treat others with dignity and respect. The Code of Student Conduct allows Dalhousie to take disciplinary action if students don’t follow this community expectation. When appropriate, violations of the code can be resolved in a reasonable and informal manner—perhaps through a restorative justice process. If an informal resolution can’t be reached, or would be inappropriate, procedures exist for formal dispute resolution. For more information please see [https://www.dal.ca/campus\_life/safety-respect/student-rights-and-responsibilities/student-lifepolicies/code-of-student-conduct.html](https://www.dal.ca/campus\_life/safety-respect/student-rights-and-responsibilities/student-lifepolicies/code-of-student-conduct.html)

## Important Dates in the Academic Year (including add/drop dates)
[https://www.dal.ca/academics/important\_dates.html](https://www.dal.ca/academics/important\_dates.html)

## University Grading Practices
[https://www.dal.ca/dept/university\_secretariat/policies/academic/grading-practices-policy.html](https://www.dal.ca/dept/university\_secretariat/policies/academic/grading-practices-policy.html)

## Missed or Late Academic Requirements due to Student Absence (policy)
[https://www.dal.ca/dept/university_secretariat/policies/academic/missed-or-late-academic-requirements-due-to-student-absence.html](https://www.dal.ca/dept/university_secretariat/policies/academic/missed-or-late-academic-requirements-due-to-student-absence.html)

## Learning and Support Resources

### Advising
General Advising: [https://www.dal.ca/campus\_life/academic-support/advising.html](https://www.dal.ca/campus\_life/academic-support/advising.html)

Science Program Advisors: [https://www.dal.ca/faculty/science/current-students/academic-advising.html](https://www.dal.ca/faculty/science/current-students/academic-advising.html)

Indigenous Student Centre: [https://www.dal.ca/campus\_life/communities/indigenous.html](https://www.dal.ca/campus\_life/communities/indigenous.html)

Black Students Advising Centre: [https://www.dal.ca/campus\_life/communities/black-student-advising.html](https://www.dal.ca/campus\_life/communities/black-student-advising.html)

International Centre: [https://www.dal.ca/campus\_life/international-centre/current-students.html](https://www.dal.ca/campus\_life/international-centre/current-students.html)

### Academic supports
Library: [https://libraries.dal.ca](https://libraries.dal.ca)  

Writing Centre: [https://www.dal.ca/campus\_life/academic-support/writing-and-study-skills.html](https://www.dal.ca/campus\_life/academic-support/writing-and-study-skills.html)

Studying for Success: [https://www.dal.ca/campus\_life/academic-support/study-skills-and-tutoring.html](https://www.dal.ca/campus\_life/academic-support/study-skills-and-tutoring.html)

Copyright Office: [https://libraries.dal.ca/services/copyright-office.html](https://libraries.dal.ca/services/copyright-office.html)  

Fair Dealing Guidelines: [https://libraries.dal.ca/services/copyright-office/fair-dealing.html](https://libraries.dal.ca/services/copyright-office/fair-dealing.html)

### Other supports and services
Student Health & Wellness Centre: [https://www.dal.ca/campus\_life/health-and-wellness/servicessupport/student-health-and-wellness.html](https://www.dal.ca/campus\_life/health-and-wellness/servicessupport/student-health-and-wellness.html)

Student Advocacy: [https://dsu.ca/dsas](https://dsu.ca/dsas)

Ombudsperson: [https://www.dal.ca/campus\_life/safety-respect/student-rights-and-responsibilities/where-to-get-help/ombudsperson.html](https://www.dal.ca/campus\_life/safety-respect/student-rights-and-responsibilities/where-to-get-help/ombudsperson.html)

### Safety
Biosafety: [https://www.dal.ca/dept/safety/programs-services/biosafety.html](https://www.dal.ca/dept/safety/programs-services/biosafety.html)

Chemical Safety: [https://www.dal.ca/dept/safety/programs-services/chemical-safety.html](https://www.dal.ca/dept/safety/programs-services/chemical-safety.html)

Radiation Safety: [https://www.dal.ca/dept/safety/programs-services/radiation-safety.html](https://www.dal.ca/dept/safety/programs-services/radiation-safety.html)

Scent-Free Program: [https://www.dal.ca/dept/safety/programs-services/occupational-safety/scent-free.html](https://www.dal.ca/dept/safety/programs-services/occupational-safety/scent-free.html)
