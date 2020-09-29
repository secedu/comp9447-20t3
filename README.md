# Course Announcements (Changelog)
[31/8/2020]: Course Outline released

[6/9/2020]: [Week 0](https://github.com/secedu/comp9447-20t3/tree/master/week0) released

[13/9/2020]: [Week 1](https://github.com/secedu/comp9447-20t3/tree/master/week1) released

[20/9/2020]: [Week 2](https://github.com/secedu/comp9447-20t3/tree/master/week2) released

[28/9/2020]: [Week 3](https://github.com/secedu/comp9447-20t3/tree/master/week3) released

# FAQ
**Q: The course outline / project scope is so vague**\
A: We understand that this is a concern shared among many students, and are working on providing you with more supplemental information on the project and compiling a resource hub for this project. This will include more information on what building a SOAR looks like and other links to videos and articles that you may find helpful.

**Q: How to handle AWS costs?**\
A: Use tools like [cloudwatch alarms](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html) to get alerts on when your monthly bill exceeds a certain amount. Setup alarms for approx $60-70 to give you and your tutor time to address.

If you need codes, ask a tutor/mentor and you shall receive (within reasonable quantity)

If you go to billing dashboard on your console you can see what services you have spinned up (and in what regions). Our advice is to limit all your services into one region if you can. So that when the time comes to shut everything down you can do so without worrying about different services running in different regions + forgetting something in another region.

**Q: Where can I find lecture recordings?**\
A: [Here](#Lecture-Recordings) or the #Announcements channel in the Discord server.

**Q: Where can I find the self-paced labs?**\
A: [Week 0](https://github.com/secedu/comp9447-20t3/tree/master/week0)

**Q: When are the due dates?**\
A: see [Course Schedule](#Course-Schedule)

**Q: Where is the marking criteria?**\
A: [Here](https://unsw-my.sharepoint.com/:w:/g/personal/z3530721_ad_unsw_edu_au/EXUgsgjgAnlGuWElgxbJQDoBhLOg4Ec7yECWe0u6gMyVPQ?e=bBvmCV)

**Q: Where is the project overview?**\
A: [Here](https://unsw-my.sharepoint.com/:w:/g/personal/z3530721_ad_unsw_edu_au/ETGvukva94JGhc6UiAinDFYB1X1awFZArsnIBTDT7iEmMw?e=ld1xMA)

**Q: Are groups predetermined by staff or made during the course?**\
A: Your teams will be predetermined, and you will meet your teammates during the project kick off in Week 1

**Q: Is there any face to face communication?**\
A: see [Teaching Strategies](#Teaching-Strategies)

**Q: When are the labs/tutorials?**\
A: Timetabling for your weekly seminar will be arranged in Week 1 as you meet your team, mentor and tutor for the first time, and find a common time to meet for successive weeks.

# Lecture Recordings
* [Project Kickoff](https://unsw.zoom.us/rec/share/FPzGbEZherI092BvpkfEksfxE0qna4uIw4_IbHqBH8Drv5Jx97-G227wvYXzlUbb.Hpy7MHPaVma2pDQ6)
* [AWS 101 by Nic Seilaz](https://unsw.zoom.us/rec/share/RngzGb9mnU80o0sc1j3j4GlM6rTZbkgTps4ilprP9RK8a0TjEY6ncT92si1zYIIe.Lk5efBRU3yvrio2a)

# COMP9447 Course Outline: Security Engineering Workshop with AWS
## Details:
* Course Code: COMP9447
* Term: 2020 T2
* Course Title: Security Engineering Workshop
* Convenor: Richard Buckland
* Course Admin: [Christopher Shi](mailto:christopher.shi@unsw.edu.au) [Shantanu Kulkarni](mailto:shantanu.kulkarni@student.unsw.edu.au)
* Contact: cs9447@cse.unsw.edu.au
* Units of Credit: 6
* Handbook Entry: 
	* https://www.handbook.unsw.edu.au/postgraduate/courses/2020/COMP9447/
	* https://www.handbook.unsw.edu.au/undergraduate/courses/2020/COMP9447/

## Course Summary
COMP9447 Security Engineering Workshop is an applied course on security engineering. Students will learn cloud and distributed computing techniques using AWS and utilise them to build a product and associated SOAR (Security Orchestration, Automation and Response) tooling and technologies.

SOAR refers to technologies that enable organizations to collect inputs monitored by the security operations team. For example, alerts from the SIEM system and other security technologies — where incident analysis and triage can be performed by leveraging a combination of human and machine power — help define, prioritize and drive standardized incident response activities. SOAR tools allow an organization to define incident analysis and response procedures in a digital workflow format. [Gartner](https://www.gartner.com/en/information-technology/glossary/security-orchestration-automation-response-soar)

The students will be provided with a reference deployment for an application that will be used to demonstrate their SOAR solution's security capabilities.

All teams:
https://github.com/aws-samples/aws-modern-application-workshop

## Assumed Knowledge
* Security
* Cloud computing / platforms
* Computer networks
* Databases
* Web development

## Student Learning Outcomes
After completing this course, students should be able to have:
* The ability to make trade-off decisions with regard to cost, security, and deployment complexity given a set of application requirement
* A working knowledge of AWS security services and how to provide a secure production environment
* An understanding of AWS security best practices and how to implement them
* An understanding of data encryption methods and AWS mechanisms to implement them
* An understanding of incident response techniques in the cloud
* The ability to work through practical real world cloud challenges

## Teaching Strategies
Due to COVID-19, we have made some adjustments to the delivery of this course as per [university guidelines](https://www.covid-19.unsw.edu.au/information-students). This course is fully equipped to be delivered 100% online, however it's probable that there will be some face to face components (more information soon), restrictions permitting. We will let you know more details as we know them.

This course will involve an indicative per week:
* 1 x 90 minute - hands on seminar with AWS Mentors and UNSW Tutors (recorded)
* an additional estimated 7-8 hours of independent learning, collaborative work within your team

Attendance is not compulsory, however we highly encourage you to attend as you will get the most out of this experience.
If you cannot attend a seminar or would like to organise a F2F meet, please email the admins.

## Communication Channels:
This course will be run almost entirely using Discord, Github. (We won't be using webcms or moodle - so please don't hesitate to ask if you can't find something or something doesn't look right)

Discord: will be the preferred method of communication between students and staff this term.

Github: will be the preferred method of resource distribution to students. Reading material, references, marking criteria, files, etc. will be uploaded to this repo in respective folders.

Zoom links:
* Common: https://unsw.zoom.us/j/95199340741
* Team 1: https://unsw.zoom.us/j/95135935963
* Team 2: https://unsw.zoom.us/j/95258941934
* Team 3: https://unsw.zoom.us/j/99300763349
* Team 4: https://unsw.zoom.us/j/91558714871

this README.md: will contain course announcements, updates and the course outline

## Teaching Rationale and Improvements
This course (COMP9447) is designed to give students an opportunity to apply their knowledge and theory to real world applications of security engineering. Therefore, engaging external expertise is a primary part of this course. Partnering with AWS enables students to get mentorship and support as they work on a practical project and learn skills related to this highly evolving industry.

For the 20T3 iteration of this course, we have made the following student-facing changes:
- Increase in the intake of students (from 20 to 40)
- Increase in the number of teaching staff (from 1 admin, 1 AWS mentor to 4 tutors, 2 admins and 5 AWS mentors)
- The addition of self-paced labs for students to complete
- Fixed product ideas and architecture
	- Introduction to system design
	- Security in system design
- Introduction of SOAR (Security Orchestration, Automation and Response) topic, covering more breadth than previous automated IR topic.
- (TBD)

## Assessment
- 25% Final Product, marked as a group
- 25% Group Report, marked as a group
- 25% Final Presentation, marked as a group
- 25% Individual Self Reflection, marked individually

These artefacts are all due at the end of the term. Specific due dates will be released at the end of Week 2.

The [Marking Criteria](https://unsw-my.sharepoint.com/:w:/g/personal/z3530721_ad_unsw_edu_au/EXUgsgjgAnlGuWElgxbJQDoBhLOg4Ec7yECWe0u6gMyVPQ?e=bBvmCV) contains more specific information as to what is expected for each deliverable. Changes will be made to it throughout the term.


## Artefacts/Deliverables
Please consult the marking criteria for each artefact/deliverable for more information.

### Final Product
Includes:
- Code repository (Github)
- Supporting documentation
- Any other supporting material (that is required for the final product to be classified as minimum viable product (MVP))

Due: Thursday 26th November 11:59PM, repo link and supporting material emailed to [cs9447@cse.unsw.edu.au](cs9447@cse.unsw.edu.au)

### Group Report
A written business-case style report contributed to by all members of the team that documents their experience through this course and the project that they have been working on. This should include a evaluation of the project as a group, the challenges/breakthroughs you faced, what you liked/disliked about the whole experience, etc.

Due: Thursday 26th November 11:59PM, report emailed to [cs9447@cse.unsw.edu.au](cs9447@cse.unsw.edu.au)

### Final Presentation
A presentation (slide deck) presented at AWS at the end of the project detailing the functionality of the demo product and SOAR implementations, and the value it presents to solving an issue faced by AWS customers and partners.
 
Due: Thursday 19th November 1-3PM, presentation either via Zoom or in person.

### Self Reflection
At the end of the term students are expected to perform a self reflection on their progress and work output. Part of this self reflection should include a journal that students keep updated throughout the term as a record of their individual progress and learnings for this course.

Due: Sunday 29th November 11:59PM, reports emailed to [cs9447@cse.unsw.edu.au](cs9447@cse.unsw.edu.au)

## Course Schedule
| Week | Events | Activities |
|-------|------|-------|
| 0 |
| 1 | Virtual Kickoff | Here you will meet your team for the first time and be introduced to the course<br>  Discuss project scope and setup accounts and deploy demo App<br> Students setup access for students to access AWS accounts<br> Students setup Git repo<br> Students setup billing alerts for early notification of $70 spend<br> Students review marking criteria<br> Students capture self-contribution log|
| 2 | | Students complete high level plan for project timelines<br>Students complete project use cases<br>Students setup and log use cases in Git for task assignment<br>Students complete threat model<br>Students review Well-Architected Framework and complete early review of their solution to identify gaps<br>Students Capture self-contribution log
| 3 | |Students refine metrics for each use case and discuss collection patterns, logging, alarms, notifications, dashboards<br>Students review CI/CD and how to incorporate into project<br>Students start to build out use cases and scenarios on platform to validate their thinking<br>Students Capture self-contribution log
| 4 | |Students build, test, validate, iterate (look for automation oppertunities)<br>Students capture self-contribution log
| 5 | | Students build, test, validate, iterate, evolve<br>Students capture self-contribution log<br>Mid-project checkin (team to discuss current solution and areas for closure leading up to presentation)
| 6 | Flex Week | Students build, test, validate, iterate, evolve<br>Students capture self-contribution log
| 7 | | Students build, test, validate, iterate<br>Students capture self-contribution log
| 8 | | Students start working on story board and building presentation material<br>Students draft readme docs for github repo and validate usability<br>Students complete Well-Architected review and incorporate results into preso and areas for improvement<br>Students capture self-contribution log
| 9 | | Students draft preso to AWS mentor and Tutor<br>Students capture self-contribution log<br>Students Draft group report
| 10 | Final Presentation | Thursday 19th November, 1-3PM, Common Zoom<br>
| Study Period | Group Report and Final Product Due | Thursday 26th November 11:59PM |
|  | Self Reflection Due | Sunday 29th November 11:59PM |


## Resources for Students
Self Paced labs: 
* https://aws.amazon.com/training/self-paced-labs/

Other:
* https://aws.amazon.com/blogs/aws/ 
* https://aws.amazon.com/architecture/ 
* https://aws.amazon.com/solutions/ 
* https://aws.amazon.com/well-architected-tool/ 
* https://aws.amazon.com/whitepapers/ 
* https://github.com/aws-samples 

## Course Evaluation and Development
Any points of feedback for the course can be emailed directly to cs9447@cse.unsw.edu.au. At the end of the course, you will be asked to complete the [myExperience survey](https://student.unsw.edu.au/myexperience), which provides the university with a key source of student evaluative feedback.

## Course Contacts:
* Course specific: cs9447@cse.unsw.edu.au
* AWS Point of Contact: liddlep@amazon.com
* Course Admin: christopher.shi@unsw.edu.au, shantanu.kulkarni@student.unsw.edu.au
* SECedu General: secedu@unsw.edu.au

## Student Conduct
The Student Code of Conduct ([Information](https://student.unsw.edu.au/conduct) , [Policy](https://student.unsw.edu.au/conduct)) sets out what the University expects from students as members of the UNSW community. As well as the learning, teaching and research environment, the University aims to provide an environment that enables students to achieve their full potential and to provide an experience consistent with the University's values and guiding principles. A condition of enrolment is that students inform themselves of the University's rules and policies affecting them, and conduct themselves accordingly.

In particular, students have the responsibility to observe standards of equity and respect in dealing with every member of the University community. This applies to all activities on UNSW premises and all external activities related to study and research. This includes behaviour in person as well as behaviour on social media, for example Facebook groups set up for the purpose of discussing UNSW courses or course work. Behaviour that is considered in breach of the Student Code Policy as discriminatory, sexually inappropriate, bullying, harassing, invading another's privacy or causing any person to fear for their personal safety is serious misconduct and can lead to severe penalties, including suspension or exclusion from UNSW.

If you have any concerns, you may raise them with your lecturer, or approach the [School Ethics Officer](mailto:ethics-officer@cse.unsw.edu.au) , [Grievance Officer](grievance-officer@cse.unsw.edu.au) , or one of the student representatives.

Plagiarism is [defined as](https://student.unsw.edu.au/plagiarism) using the words or ideas of others and presenting them as your own. UNSW and CSE treat plagiarism as academic misconduct, which means that it carries penalties as severe as being excluded from further study at UNSW. There are several on-line sources to help you understand what plagiarism is and how it is dealt with at UNSW:

[Plagiarism and Academic Integrity](https://student.unsw.edu.au/plagiarism)
[UNSW Plagiarism Procedure](https://www.gs.unsw.edu.au/policy/documents/plagiarismprocedure.pdf)
Make sure that you read and understand these. Ignorance is not accepted as an excuse for plagiarism. In particular, you are also responsible that your assignment files are not accessible by anyone but you by setting the correct permissions in your CSE directory and code repository, if using. Note also that plagiarism includes paying or asking another person to do a piece of work for you and then submitting it as your own work.

UNSW has an ongoing commitment to fostering a culture of learning informed by academic integrity. All UNSW staff and students have a responsibility to adhere to this principle of academic integrity. Plagiarism undermines academic integrity and is not tolerated at UNSW. Plagiarism at UNSW is defined as using the words or ideas of others and passing them off as your own.

If you haven't done so yet, please take the time to read the full text of

[UNSW's policy regarding academic honesty and plagiarism](https://student.unsw.edu.au/plagiarism)
The pages below describe the policies and procedures in more detail:

[Student Code Policy](https://www.gs.unsw.edu.au/policy/documents/studentcodepolicy.pdf)
[Student Misconduct Procedure](https://www.gs.unsw.edu.au/policy/documents/studentmisconductprocedures.pdf)
[Plagiarism Policy Statement](https://www.gs.unsw.edu.au/policy/documents/plagiarismpolicy.pdf)
[Plagiarism Procedure](https://www.gs.unsw.edu.au/policy/documents/plagiarismprocedure.pdf)
You should also read the following page which describes your rights and responsibilities in the CSE context:

[Essential Advice for CSE Students](https://www.engineering.unsw.edu.au/computer-science-engineering/about-us/organisational-structure/student-services/policies/essential-advice-for-cse-students)

### AWS Acceptable Usage Policy
Please familiarise yourself with the [AWS Acceptable Usage Policy](https://aws.amazon.com/aup/)

