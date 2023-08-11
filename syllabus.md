# Syllabus
## NESC 3505: Neural Data Science
*Cross-Listed as PSYO 3505*

### Fall 2023-24
September 7 – December 7, 2023

#### version 1.1 2021-09-04

### Instructor
Danny Godfrey ([daniel.godfrey@dal.ca](mailto:daniel.godfrey@dal.ca))

#### Teaching Assistant
Brynn Harris-Shanks

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

## Prerequisites
**PSYO 2000**, **PSYO 2501**, and **NESC 2470**, with a minimum grade of B in PSYO 2501. Grades of B+ or better in all three classes are recommended. **No prior programming experience is required**.

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
- Use AI coding assistants to generate Python code to perform basic data science tasks
- Critically evaluate, test, and debug code generated by AI coding assistants
- Use online tools for version control, collaborative software development, and project management
- Read and write data files in common formats such as CSV and Excel
- Organize and manipulate data structures such as lists, arrays, and data frames
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
- [Freely-accessible online **textbook**](https://neuraldatascience.io/)
- Asynchronous **online lessons**
- Weekly **in-person lab** sessions. Attendance is expected. In some labs the instructor and/or TA will review material, such as introducing an assignment and discussion approaches to completing it. Any such instruction will be recorded and posted via Teams. Some labs will be open work time where the instructor and TA are available for consultation.
- Online tutorials and practice through **DataCamp**, a massive online education platform for data science

The "home base" for this class will be a [Microsoft Teams](https://neuraldatascience.io/2/teams.html) site hosted through Dalhousie University. Registered students will receive an invitation to this site via their Dal.ca email. The Teams site will contain links to all course materials, as well as hosting text messaging and video/audio chat meetings. **The Teams site will be the primary source for course-related announcements, and the official source for assignment due dates.** This course does not use Brightspace.

## Online Lectures and Tutorials
This course employs a “flipped classroom” model. The primary course matierial is the [online textbook](https://neuraldatascience.io/), and video walkthroughs of the lessons in the textbook on the course [YouTube channel](https://youtube.com/playlist?list=PLtfEWMIgWS22MMZjPIzBRE2cHhMcvEKwp). These largely involve writing code. **This course requires that you put in significant hours per week outside of class: you should budget 8 h/week for work on the course, including the 2 h/week lab time.**

## Labs
Weekly lab sessions are held in-person and will be used for tutorial by the teaching team, and open office hours/consultation/work time. Participation in these is optional but recommended.

## Getting Help
One of the course learning objectives is "Extend your skills using online resources", and the course is based on the learning theory of [connectivism](https://neuraldatascience.io/1/connectivism.html). You are encouraged and supported in taking a *lifelong learning* approach to solving problems in this course. Many of the evaluations expect you to engage in this; you will not find all the answers in the textbook.

That said, learning can sometimes go a lot faster when you ask questions. We encourage you to ask questions of your peers in the class, and of the teaching team — in that order. Peer teaching is built into the class through collaboration tools, demos, and team projects. This is the way real, functional teams operate — supporting each other to achieve more.

The course Teams site is where you should direct all your questions (after making your own attempts to research and solve your problem). This can include posting questions in the messaging forums, or joining live check-ins to ask questions. Please do not email the teaching team with questions about the class — use the Teams site. Do feel free to email the instructor if you have personal topics that you need to discuss privately, or you can use direct messaging on Teams.

There are no formal instructor office hours for this course. If you wish to speak with the instructor or TA, just contact them via Teams and ask to schedule a meeting and we will set something up at a mutually-agreeable time.

# Course Materials
All necessary materials (including the textbook) will be provided online, through the course Teams site. **You must have access to a computer** running a recent version of the Mac, Windows, Chrome, or Linux operating systems. It may be possible to complete this course, including programming assignments, using an iPad, but this has not been verified. It is not a good idea to expect to be able to complete the course using only a mobile device (phone or tablet).

**You must also have access to internet service** of sufficient quality to stream videos and maintain a live connection to remote servers. Provisions will be made if students cannot participate in live audio/video sessions due to internet constraints; please contact the instructor to discuss if this is an issue for you.

Beyond these basic requirements, this course emphasizes (and will teach you about) openly accessible resources including the software that runs the course, open access to the course materials, and the use of external resources that are available for free. No textbook is required. This course will rely on [Open Educational Resources](https://neuraldatascience.io/1/oer_this_course.html) — materials that are freely accessible and openly licensed — including online tutorials, videos, and books. A wide variety of educational materials (free and paid) for data science are available, and this course teaches an approach to lifelong learning and exploration by which you will be able to find and critically evaluate the information necessary to perform desired tasks.

# Assessment and Evaluation
Your final grade will be based on a combination of [*formative assessments*](https://neuraldatascience.io/1/assessment_evaluation.html) (self and peer evaluations) and [*summative evaluations*](https://neuraldatascience.io/1/assessment_evaluation.html) (presentations, assignments, projects). Each component is described below, followed by a table showing the number and point weighting of each.

The items you're graded on are divided into two categories:
- **Formative assessments** are designed to support you in improving your performance in the class (they help "form" you), through self-assessment, peer assessment, and instructor feedback. These are designed to require little time to complete. They contribute a small proportion of your grade (10%), but they are all graded as pass/fail, so you get the full XP for completing them. Thus collectively they can make a significant difference in your grade.
- **Summative evaluations** comprise the majority (90%) of your final grade. These are meant to *summarize* your learning. All summative evaluations are graded.

The grading system is built to be **inclusive and adaptive** to the needs and life circumstances of individual students. While some assessments are not accepted after the due date, and some evaluations have late penalties, we recognize that missed or late assignments sometimes happen for excusable reasons. Rather than making a big deal about your proving to us that your reason is legitimate, we instead provide options *built right into the course* for you to make up lost points in other ways, including skipping a missed assignment in some cases, or having your worst mark on certain items (like assignments) be worth much fewer points. Because there are a variety of bonus points on offer, there are actually more opportunities to earn points than you need to get an A+ in the course. This means that you can, within reason, pick and choose how to achieve your desired grade. That said, your grade is intended to reflect the degree to which you have met the learning objectives, so you do need to demonstrate competence with regard to all of the objectives.

Due dates for all assessment and evaluation components will be posted on Teams.

## Formative Assessments

### Self-Assessments
You will submit regular written assessments of your own learning progress over the term. This type of self-reflection has been empirically demonstrated to improve learning outcomes. It's also an incredibly useful way for the instructor to keep in touch with every student, and recognize both individual and common areas where people are struggling. Each self-assessment should be 150-500 words in length. **Late work will be penalized 2% per hour**, with the clock starting the minute after the deadline has elapsed. Self-assessments are only helpful if they're done regularly, and in this class they are timed to synch up with your work in other aspects of the course. These are assigned and submitted via Teams.

### Meet 'n Greets
You will earn bonus points by participating in short (5-10 min) one-on-one meetings with other class members. These are scheduled by students at your mutual convenience, and can take the form of an online video/audio chat or in-person meeting. The purpose of these is to allow for the kinds of casual interactions you might normally have with others in a face-to-face class, and allow you to get to know people as potential team members for projects.

All students are expected to abide by [Dalhousie University's Code of Student Conduct](https://www.dal.ca/dept/university_secretariat/policies/student-life/code-of-student-conduct.html), and violations will be addressed through the procedures described there. If a meet 'n greet makes you uncomfortable, it is fine to terminate it immediately. Please report any inappropriate behaviour to the instructor immediately. You will be heard, and you will be respected.

Meet 'n greets should ideally occur early in the course. The required meet 'n greets should be completed by the end of the first month of class.

## Summative Evaluations
Because 10% of your final grade (the formative assessments) are "easy" pass/fail points, and an additional 10% is available in bonus points, you can expect that grading of the summative evaluations will be quite strict. For all summative evaluations, **late work will be penalized 2% per hour**, with the clock starting the minute after the deadline has elapsed. **Requests for extensions will only be considered prior to the due date**.

### Assignments
These are coding assignments that you will complete, based on neuroscience data. There is an assignment due approximately every second week, except weeks when projects are due. The first assignment is mandatory for everyone, and it's important because it will teach you how to access course materials and use the tools required for the rest of the course. All of the other assignments are mandatory, however --- if and only if you submit *all* of the assignments --- the grade on the assignment you did worst on will be dropped (see table below). 

### Projects
There are 2 [team-based](https://neuraldatascience.io/1/teamwork.html) projects to complete. These projects are directly based on the class assignments, but integrate across multiple classes and assignments, as well as requiring you to extend and apply what you have learned, to new contexts.

### Project Peer Assessments
You will be asked to submit structured peer reviews following each of the two team projects. This will be done using a rubric with five components: participation, preparation, communication, collaboration, and academic quality. Your grade will be the average of the ratings assigned to you by your team members. **Late peer assessments will be penalized 2% per hour**, with the clock starting the minute after the deadline has elapsed.

#### Dealing with unequal contributions
Submitting the peer assessment itself is worth only a few points towards your final grade. However, it is also an opportunity for teams to identify individuals who did not contribute substantially to the project work. The peer assessment asks each team member to estimate the proportion of work done on the project by each team member. If any team member is identified by a majority of other team members as having done substantially less then their fair share of the work ("substantially less" being less than half as much work as others), the average contribution rating of all team members (other than the student in question) will be used to reduce the student's grade on the team project.

For example, imagine a team of 4 members: A, B, C, and D. D slacks off and does little to none of the work, and members A, B, and C rate D's contribution as 0, 2, and 4% of the project respectively --- for an average of 2% (where equal work would have been 25% each). The team project receives a grade of 80/100 points. In this case, D's grade on the project would be 2/25 or 8% of the points awarded for the project, i.e., 0.08 * 80 = 6.4 points.

Please note that this is a "worst case" scenario, although it has happened in the past. We much prefer it if issues are identified before things get this bad. Teams should first try to contact the team member who seems to be doing less work, and discuss the issue with them to try to find a resolution. Secondly, *before the project deadline*, teams should contact the instructor to discuss the problem.

If you are on a team and are having trouble completing your fair share of the work, likewise please first discuss this with your team members, and if you can't resolve it that way, please contact the instructor to discuss — ideally well before the project deadline. The purpose of this mechanism is to prevent students from "freeloading" on the work of others, but it is *not* meant to penalize people who are experiencing genuine struggles of any kind. The instructor is eager to support students who are struggling in any way.

### Portfolio (Optional)
If you're interested in carrying on in data science, or otherwise showcasing your skills as a coder to potential supervisors or employers, an online portfolio is a great way to do this. The portfolio is optional, and counts for bonus points if you do submit it. We will provide lessons on how to build a portfolio, and you will have the option of submitting a draft for feedback prior to grading.

Your portfolio should be a publicly-accessible website. Our suggestion is that you use GitHub Pages for this purpose. There are a series of videos on the class [YouTube channel](https://youtube.com/playlist?list=PLtfEWMIgWS22MMZjPIzBRE2cHhMcvEKwp) with how-tos for doing this.

Grading will be according to a rubric with five components: quantity of samples; breadth; quality of content; quality of presentation; and organization. Here are links to the rubrics for [Submission 1](https://neural-data-science.github.io/NESC_3505/rubrics#portfolio-submission-1-rubric) and [Submission 2](https://neural-data-science.github.io/NESC_3505/rubrics#portfolio-final-submission-rubric).

### Demos
Demos are an opportunity for you to explore the world of neural data science, and data science more broadly, pursuing topics that are of individual interest to you. 

A demo can take a variety of formats, including code, video, a blog post, etc.. Regardless of the format, it should have a clear topic, and you should articulate in the demo why the topic is of interest and relevance to you, what is interesting about it, and how it connects to the course content. For more info and some guidance on demos, go [here](demos).

Grading (by the teaching team) will be based on a rubric with four components: *quality of content*, *quality of explanation*, *quality of presentation*, and *relevance/usefulness of topic*, with a few bonus points available for *creativity*.


# Grading
This course follows the [Dalhousie grading scale](https://www.dal.ca/campus_life/academic-support/grades-and-student-records/grade-scale-and-definitions.html). The table below lists the point values of individual grading items, which total 10,000. Your grade is based on the percentage of 10,000 points that you earn (including bonus points).

## How to Earn Points
The table below lists all the "core" and "bonus" opportunities to earn points in this course.

| **Summative Evaluations**                                                 | **XP** | **bonus XP** |
|---------------------------------------------------------------------------|--------|--------------|
| ***Assignments***                                                         |        |              |
| Assignment 1                                                              | 1000   |              |
| Assignments 2-5, 3 best marks @ 1500                                      | 4500   |              |
| (must turn in all assignments for worst grade to be dropped)              |        |              |
| ***Projects***                                                            |        |              |
| Project 1                                                                 | 1500   |              |
| Project 2                                                                 | 1500   |              |
| ***Demos***                                                               |        |              |
| Demos, 2 @ 500([rubric](rubrics#demo-rubric))                             | 1000   |              |
| ***Portfolio***                                                           |        |              |
| Portfolio (optional; [rubric](rubrics#portfolio-final-submission-rubric)) |        | 200          |
| **Formative Assessments**                                                 |        |              |
| ***Peer Assessments***                                                    |        |              |
| Project 1 peer assessment                                                 | 100    |              |
| Project 2 peer assessment                                                 | 100    |              |
| ***Self-Assessments***                                                    |        |              |
| Self-assessments 6 @ 50                                                   | 300    |              |
| ***Meet 'n Greets***                                                      |        |              |
| Meet 'n Greets - 5 @ 20                                                   |        | 100          |
| **Totals**                                                                | 10000  | 300          |

# Schedule

[Click here to see the schedule](https://neural-data-science.github.io/NESC_3505/schedule.html).

The course has weekly and bi-weekly structure:

## Weekly Structure
### Synchronous Activities
Each week, there will be one in-person lab session as scheduled in the university timetable. This session will typically include review of the week's learning material, tutorials on course content or on things that we identified as issues from errors on assignments or questions from students, and the opportunity to ask questions from the teaching team. Some lab sessions will be open work time when you can work on course material with the teaching team on-hand to answer questions as they arise.

### Asynchronous Activities
Most of your learning will come from sitting and coding, working through the lessons (ideally following along with the videos), and completing the assignments and projects. These are asynchronous activities so you can work on them on the schedule that best works for you. The course is designed expecting you to complete three lessons per week, along with any assignments. You should aim to follow the [schedule](https://neural-data-science.github.io/NESC_3505/schedule) to keep up with the lessons (although of course the beauty of asynchronous learning is the flexibility). For many people, it works best to block off time every day or two to focus on work for this course.

## Bi-Weekly Structure
There will be an assignment or project due every two weeks. On the alternating weeks when no assignment or project is due, a self-assessment will be due. As well, there are due dates for demos spaced over the term. These due dates are all mapped out on the [schedule](https://neural-data-science.github.io/NESC_3505/schedule), but as always, Teams is your authoritative source for due dates.

# Policies
This course is governed by the academic rules and regulations set forth in the University Calendar and by Senate.

## Attendance
Attendance of scheduled class meetings is optional, but scheduled class times are the only time when you can get in-person help with the course material. You can message the TA and instructor on Teams outside of this time for help, but response times will be variable.

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
