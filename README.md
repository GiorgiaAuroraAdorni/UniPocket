# UniPocket
Second Assignment for the Software Development Process course

Version 1.0 – 20.11.2018  
Version 1.1 –    2.12.2018

Adorni Giorgia 806787  
Basso Matteo 807628

# Requirements Elicitation (RE)

## Objectives of the document

The following document describes the procedures for extracting the requirements of the **UniPocket** application and the resulting results, including analysis activities. The system's functionality and what it intends to solve are also described, serving as a contractual basis between the client and the developer.
The document is written in the language of the business domain and of the customer's competence (in our case, Italian).

## Sistem as-is

The **UniPocket** application is an alternative that combines several existing systems. Currently, two different mobile applications are needed to view the university career and classroom schedules. On the other hand, some information is not available from any of them but can only be accessed via websites.
It is, therefore, clear that there is a fragmentation of information that makes users confused or dissatisfied with the systems in use. Having a single application through which all kinds of activities can be carried out would lead to the simplification of university life and perhaps to greater inclusion on the part of students.

The UniPocket system and its services, listed in the following chapters, are designed to be a single application for smartphone devices (iOS and Android). 

## System to-be
UniPocket is a university mobile application aimed at two main user groups: students and teachers (of the University of Milan-Bicocca). 

It provides several groups of functionalities, also differentiated based on the user. In particular, by logging in (through the online secretariat system) and consenting to access the data, the following functions are available. 

- Consultation of class and exam schedules
- University news via the Unimib Informa newsletter
- Consultation of the daily menu of the university canteens
- Consultation of shuttle bus timetables
- Data analysis for statistical purposes by the university administration

#### Students

- Visibility of study plan and grade book 
- Statistics on career development, such as exam grade point average and graduation basis
- Statistics relating to course difficulties (e.g. teacher evaluation, evaluation of the organisation and difficulty of a course, etc.)
- Examination enrolment
- Sale and purchase of used and non-used books

#### Professors

- Statistics on satisfaction with one's own courses and teaching methods 
- Statistics on the performance of one's own students in the different courses
- Creation of exam schedules 
- Booking classrooms and laboratories

## Stakeholders

There are six main types of 'actors' in the UniPocket application:

- The **students** have the possibility to access the application and monitor their university career. They are relevant for the elicitation process to identify and solve problems in finding certain information that may be useful daily. In addition, they can provide opinions about current systems, i.e. the reasons for their lack of use.  
- The **professors** can access the application and perform various activities, including reserving classrooms and labs, entering exams and viewing statistics about their courses. They are the ones who use the application to manage university activities and, therefore, need the system to be convenient and quick to use according to their needs. They can identify which processes can make communication with students difficult and a possible solution.
- Online secretariats may cause difficulties in the process of requesting student/professor data if certain aspects interfere with their rights, but they are not considered stakeholders since their main impact, if any, will be as a source of constraints. 
- The **university administration** needs to be able to access statistics and information about the activities of students and professors. It is relevant to understand which data are of fundamental interest and which screens can be developed for their visualisation and analysis. It is necessary to determine how the university may be able to assess overall satisfaction and how certain changes are reflected in the users. The administration then provides external constraints on the project, e.g. what data it is interested in collecting and how the application can help to do so, thus becoming a stakeholder with limited rights.
- Privacy authorities (data protection authorities), which impose regulations on the handling of user data, impose 'regulatory' constraints but are not stakeholders. Their main impact will be as a source of constraints. 
- The development team is the one who actually implements the application once all the requirements have been obtained, and the analysis carried out. It is, therefore, clear why they are interested in the product.

By examining these candidates, we defined that only three of them are real stakeholders, namely students, professors and the university administration. The previous analyses will be used to define the elicitation strategy.

Before proceeding to the submission phase of the questionnaires and interviews, we defined the priorities and rights of each category so that we could choose between two conflicting requirements and resolve situations in which they have equal priority and cannot be exchanged effectively. In particular, we chose to give more importance to students, as they are the ones who will use mobile systems the most during their daily lives and who need access to a large number of different kinds of information. Next are the professors who use information systems to do their work, probably most of the time using a laptop computer, and only finally, the university administration.  
Nevertheless, the requirements of students, professors and administration should not be at odds with each other, as each of them displays a different version of the application with only the available functionalities consistent with their role.  
A number of appropriate stakeholder representatives were also selected to speak on behalf of the group. In the case of students, as in the case of professors, these are those who hold administrative positions, i.e. student representatives and departmental coordinators. In the case of the administration, on the other hand, it is necessary to identify those responsible for analysing data and questionnaires for general satisfaction.

## Elicitation strategy

According to the stakeholder specifications explained in the previous chapter, an elicitation strategy was elaborated as shown below. The first phase consists of gathering quick and effective information to understand the domain and existing systems so that questionnaires and interviews can be conducted more efficiently. Next, questionnaires and interviews are carried out to understand the users' current problems and gather useful information to develop a mock-up of the application. It will then be shown and modified until it satisfies the stakeholders fully. At that point, the actual developments can begin.
Note that the activities are carried out in this precise order to obtain as much information as possible before carrying out each step.

1. **Background study**: Initially, the existing system and the application domain are studied and evaluated to not take up unsolicited stakeholder time during interviews and questionnaires. In particular, the points to be investigated through this activity are the understanding of the university's services and the platforms that provide them. It is necessary to understand whether it is possible to retrieve information from such systems, such as online secretariats, and to be able to interact with them to carry out certain procedures, such as exam registration.   
Furthermore, applications already developed by third parties and the features they offer will be identified so that comparisons can be made and their problems and strengths understood.
2. **Questionnaires**: according to the criteria set out in the following sub-chapters, two different questionnaires are submitted to the largest stakeholder groups: students and lecturers. This activity aims to obtain information quickly and enable an initial mock-up and the organisation of targeted interviews.
3. **Interviews**: interviews are carried out with university administrations according to the criteria set out in the following sub-chapters. An attempt is made to understand the existing applications, identify which data are useful for various analyses, and how they can be found, visualised and possibly shared with students and professors to carry out transparent management.
4. Following this first phase of questionnaires and interviews, the emerging requirements will be analysed, and any conflicts between them in the various stakeholder groups will be checked. Should this occur, it will be necessary to resume the elicitation process considering the rules defined in the previous chapter for conflict resolution. It will be possible to organise a brainstorming session involving some representatives of the different stakeholder groups.
5. **Mock-ups**: At the end of the previous points, it will be possible to develop mock-ups for stakeholder evaluation. These mock-ups will be modified gradually until an approved and confirmed version is reached by all stakeholders.
6. **Interviews**: Following the analysis carried out on the student questionnaires and the creation of the mock-ups, targeted interviews will be developed with specific students, in which the aspects that emerged from the submission of the questionnaire will be clarified and in which the mock-ups created in the previous point will be shown, the approval of which will allow the start of technical development.
7.  If everything is correct, it will be possible to proceed with the developments. Otherwise, it will be necessary to resume the elicitation activity. 

### Questionnaires

The questionnaires are multiple and different depending on the stakeholder. In particular, it was decided to submit different questionnaires to students and professors, representing the most numerous stakeholders.
They mainly consist of closed and multiple-choice questions so that subjective information about the current system and its use can be obtained quickly from various people. They are also used to show the degree of interest in the solution proposed by UniPocket. They do not aim to replace interviews but only to acquire information to improve them and emphasise what is really important.

The questionnaires were developed and carried out according to the scale below:

1. decision of the questionnaire audience (various questionnaires for different stakeholders).
2. determination of the information to be obtained.
3. decision on the data collection method (electronic, telephone, postal).
4. deciding on the types of questions.
5. use of the questionnaire on a sample of potential respondents and, if necessary, revision of the questions.
6. distribution of the questionnaire.
7. analysis of the answers.
8. presentation and use of the results.

#### Student Questionnaire

The first section of the student questionnaire asks questions aimed at understanding current systems and their use by students.
In particular, we ask what applications exist, how many of them use them, what functionalities they have and the degree of satisfaction with their use so that we can better delineate the current situation and subsequently act accordingly by offering a higher level of service.
Also, in the first section, questions are asked about the level of interest in UniPocket and its degree of usefulness. In this way, obtaining information about the users' interest in our proposal is possible.
In the next two sections, you are asked to assess the degree of interest in the individual functionalities, so that you can better identify the users' interests and be able to prioritise and emphasise them.  
Finally, in addition to the multiple-choice questions, a number of short open questions are asked, some of which are optional, better to understand further user ideas, comments and overall interest.   

It should also be noted that some questions are repeated several times within the questionnaire to understand whether the user is actually filling out the questionnaire carefully and to be able to give their answers due weight. 

Many questions have an even numerical rating scale, i.e. from 0 to 5, so that the user does not give a neutral answer and can attach more expressive importance to each point.

#### Professor questionnaire

Similarly to the students' questionnaire, the professors' questionnaire consists of a first section to understand the current systems and their use, then they are asked about their interest in UniPocket and the services they are most interested in.   
The questions are different because the functionalities involved and the applications used to use them are different. While for students, a variety of applications are available, in the case of professors, these are particularly limited, so it is necessary to further understand the requirements for the system.
Redundant questions and numerical rating scales are always present.

### Interviews

Different documents were also drawn up for the interviews depending on the stakeholder. They will be asked of students and the administration. In the first case, they will be carried out from the previously submitted questionnaire, while in the second case, they will be carried out without previous interaction.  
From a practical point of view, a limited set of questions was selected to be asked to obtain specific and targeted information. They are deliberately not too numerous to leave room for free dialogue to explore and better understand the current system, its problems and possible solutions from its point of view.  
The interviews will, therefore, begin with the structured part, consisting of the questions defined in the documents, and will continue with an unstructured, free part.

Below is the information to be obtained from each stakeholder:
- Students have the opportunity to express general satisfaction regarding the receipt of information and the use of applications offered by the university and third parties for the management of their university career, resulting in the identification of a solution.
- Professors can express their satisfaction with the procedures and use of applications offered by the university. They are able to identify existing problems, as they are frequent users of the systems and, therefore, potentially able to identify procedural and communication improvements within the university environment.
- The university has the ability to identify which data are relevant for analysis and how they can be visualised and used to improve the services offered to staff and students.

After each interview, a report will be written to summarise and highlight the critical issues and points of interest that emerged from the process. This report is then submitted to the stakeholder, who must confirm or refine what has been reported. It will then be possible to carry out an analysis of what has been reported and assess which is the appropriate way forward.

#### Student interview

Based on the questionnaires carried out, a number of students were selected to be interviewed to investigate and clarify certain aspects that emerged from the open-ended questions.   
One of the aspects we will focus on will be to identify the reasons why only 50% of the students use university applications.  
We will then investigate whether the respondents share the main requirements that emerged from the questionnaire.  
Furthermore, by structuring the mock-ups, we will define the impression of the application on first impact with the user, in particular, to understand whether it gives the idea of being confusing as it contains a wide range of functionalities.

An attempt is then made to understand together with the respondent what functionality is needed within it and why.

#### Interview administration

Not having previously carried out a questionnaire to the administration, this stakeholder will first be asked questions about using current applications for data collection during the academic year.  
Specifically, it is asked which processes are monitored, how data is collected and used, the formats in which it is made available, and its actual usefulness. 

Subsequently, an attempt is made to identify what further data might interest administrations, potentially useful for improving university activity, but currently unavailable for various reasons.  
In particular, an attempt will be made to establish whether and how the use of UniPocket could contribute to obtaining such information.

In addition, an attempt will be made to identify statistics that can also be shared with application users to maintain transparent management.

## Analysis of results

### Student questionnaire

The questionnaire was submitted to the students via Google Forms and is available at the following link: [UniPocket Student Questionnarie](https://docs.google.com/forms/d/e/1FAIpQLSd7e5LX8WeAVVtyQL24afb8JZkmHL7s5nHrhenUhMRVNFwtUQ/viewform).

#### Users involved

The students were contacted via social networks, particularly by sharing the link via the Instragam 'SpottedBicocca' page.  
34 students completed the questionnaire, equally divided between men and women. They came from different study courses, although the vast majority, around 70%, were from the computer science course.

#### Currently used systems

Around 50% of the student respondents do not seem to use any application to monitor their university career, study plan, media, etc. Among users, there is a strong prevalence of the 'UniWhere' application. On the other hand, to check class schedules, it appears that most students use the 'UnimibCourse' application.  
Regarding the sale of books, almost all students do not use applications, only 20% use alternative channels such as social networks (Facebook and Telegram in particular) or shops such as the "libraccio". Moreover, users do not seem to be interested in adding this kind of functionality within UniPocket.  
The examination booking system does not satisfy students sufficiently, with many expressing the need to do this more conveniently via a mobile app.  
The university canteen does not seem to be frequented often, except by a few students, despite which we note a certain interest in the services we would like to integrate.   
Finally, moving between buildings for classes does not appear to be difficult, despite which many are interested in having the shuttle bus timetable and even other means of transport connecting the various buildings.

#### Interest in functionality

This section summarises the main information gathered from the questionnaire in graphs. All answers to the questionnaire are made available in a CSV file.

![alt text](RE%20questionnaires/Domanda1.png)

![alt text](RE%20questionnaires/Domanda2.png)

![alt text](RE%20questionnaires/Domanda3.png)

#### The proposed solution

Existing applications are currently used with average frequency, but it has emerged that a single application containing all functionalities would save students a lot of time and simplify university life.  
All the proposed functionalities appear to be of almost equal importance, while of particular relevance is the possibility of knowing where to find a place in the study rooms and the library to stop and study.  
Concerning the general interest in the development of UniPocket, it emerged that about 20% of the respondents are enthusiastic about the idea, so much so that they left extensive comments.
Some users appear visibly afraid of producing a single application with many functionalities, thinking it will become particularly difficult or confusing. As some of them pointed out, developing a simple, smooth and intuitive system is necessary to achieve the right objective. Through the use of mock-ups, it will be possible to verify whether this condition is correctly met.

## Reporting emerging requirements

After conducting questionnaires and interviews, additional requirements of various kinds emerged from different students. The requirements in their entirety are reported.

| **Other Requirements**                                       |
| ------------------------------------------------------------ |
| Laboratories and free classrooms                             |
| Classroom capacities                                         |
| Academic calendar                                            |
| Materials provided by lecturers                              |
| Notes section                                                |
| Secretarial hours and waiting time                           |
| Integrated university mail                                   |
| Online answering machine replacement                         |
| Freshman orientation                                         |
| Building and classroom opening and closing times             |
| Library section                                              |
| Importing events and lectures into the personal calendar     |
| Forecast grade based on general statistics and trends        |
| Statistics study time required for the exam                  |
| List of chapters to be studied                               |
| Fee control                                                  |

It is worth mentioning that the requirement "display of classroom capacity and seating availability" was requested several times and is, therefore, a fairly important element.
