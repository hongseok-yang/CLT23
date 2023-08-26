# CS492(D), Computational Learning Theory, Fall 2023, KAIST

This is a webpage of the course "CS492(D) Computational Learning Theory", which is offered at the KAIST CS department in the fall of 2023. The webpage will contain links to course-related materials and announcements.

The goal of this course is to expose students to the mathematical techniques for proving the guarantees of machine-learning algorithms. The main theme of the course is to find a mathematical guarantee of inductive generalisation used by machine learning algorithms: when a learning algorithm returns a classifier based on a given training data, what can we say about the real error of the classifier mathematically? We will study concepts designed to measure the complexity of the hypothesis space considered by a machine learning algorithm, such as Rademacher complexity, growth function and VC dimension, and discuss mathematical techniques for assessing the qualities of inductive generalisations used by different machine learning algorithms.

The course will be highly mathematical. Explaining lemmas, propositions and theorems and their proofs will form the main part of each lecture. We use multiple mathematical tools, such as concentration inequalities and Fenchel duality, throughout the course. We assume that students do not have any issue in understanding complex mathematical formalisms and proofs, and can construct proofs.

This course is not about state-of-the-art machine learning algorithms and popular recent deep learning models. It is more about well-developed mathematical foundations, which deal mostly with basic traditional machine learning algorithms and concepts. So, if a student is interested in deep learning or other fashionable machine-learning techniques, we advise the student to take a different course targeted at such topics.

## 1. Important Announcements

#### [22 August] Policy for handling late submissions.

We will adopt the following scheme for handling late submissions for all assignments, including homework assignments. The scheme assumes that the total marks are 100.

1. <= One day late (by the midnight of the next day): -10
2. <= Two days late: -20
3. <= Three days late: -30
4. <= Four days late: -40
5. More than four days late: -100.

#### [22 August] Honour code.

In the course, we adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for any assignment, he or she will get F.

We also handle the case of plagiarism strictly. Plagiarism means that students copy texts from other sources in their reports. They shouldn't do it. If students have to use texts from other sources, they have to rephrase the texts in their own words and state the source of the texts explicitly. Ideally, students' write-ups should mostly consist of the students' own phrases and expressions, and use such borrowed and rephrased sentences only when doing so is absolutely needed; if a large part of the report is just a eries of rephrases of existing texts, the report won't get good marks. Copying texts from other sources is an instance of plagiarism, and if it happens to an academic, it can destroy his or her research career. If a report of a student or a project group is found to plagiarise, the student or everyone in the group will get F. 

## 2. Logistics

#### Evaluation

* Final exam (40%).  Group project (40%).  Homework (20%). 

#### Teaching Staffs

* Lecturer: [Prof Hongseok Yang](https://cs.kaist.ac.kr/people/view?idx=552&kind=faculty&menu=160) (email: hongseok00@gmail.com, office hour: 6:00pm - 7:00pm on Monday, office: 3402 in E3-1.)
* TA: Jaehui Hwang
* TA: Taeyoung Kim

#### Time and Place

* Time: 14:30 - 16:00 on Tuesday and Thursday.
* Place: 2445 in E3-1.

## 3. Final Exam

The final exam for this course will happen in class on the 30th of November. Please note the unusual date of the exam, and make sure that you come to the class on that day and take the exam. The detailed information about the exam is given below.

* Date: 30 November 2023 (Thursday).
* Time: 14:30 - 16:00.
* Place: 2445 in E3-1.
* The scope of the exam is all the chapters of the textbook that are covered in the course.

## 4. Group Project

A group project is an important part of this course, which accounts for the 40% of the total marks. 2-4 students should form a group, study an advanced research topic on the theories of machine learning, and present what they studied if their group is selected for presentation. Here are the detailed instructions on this group project.

1. Form a group.
  * Deadline - 11:59PM on 19 September 2023 (Tuesday).
  * Form a group with 2-4 students.
  * Inform the lecture and the TAs about the group by email.
2. Select a topic and write a proposal (5 marks out of 40 marks).
  * Deadline - 11:59PM on 12 October 2023 (Thursday).
  * Pick a paper or papers on the theories of machine learning that will be studied by your group.
    The paper or papers should be chosen among papers published in COLT'19, COLT'20, COLT'21,
    COLT'22, and COLT'23.
  * Submit a 1-page proposal in KLMS that contains the title(s) of the selected paper(s), the reasoning for choosing it or them, and the plan to study the paper in depth.
3. Write a report (15 marks out of 40 marks).
  * Deadline - 11:59PM on 16 November 2023 (Thursday).
  * Submit a report with at most 4 pages excluding bibliography and figures in KLMS.
  * The report should explain not just the topic studied by your group but also how the group studied the topic. The latter can be about how the group members studied the topic together, which questions they asked in order to understand the topic in depth, which other papers they studied, which existing implementations or mechanised proofs they looked at if there are any such, and how each member of the group contributed to the study, etc.
  * We encourage the students to go beyond a simple summary of the topic, and to have their own thoughts in the form of mathematical or experimental analyses on the topic. For instance, if the existing results on a chosen topic mostly use the call-by-value setting, the students may try to find out which parts of the results survive in the call-by-name setting.
4. Submit the slides of a presentation on the studied topic (15 marks out of 40 marks).
  * Deadline - 11:59PM on 23 November 2023 (Thursday).
  * Prepare the slides for a 35-minute talk on the studied topic, and submit them in KLMS.
  * The slides should be in the pdf format.
5. Present your study if your group project is chosen (5 marks out of 40 marks).
  * Four projects will be based on the votes by the students, TAs, and the lecture.
  * Two projects will be presented on 5 December 2023 (Tuesday), and the other two will be presented on 7 December 2023 (Thursday).
6. Warning on plagiarism.
  * Students should not copy texts from other sources in their reports. If students have to use such texts, they have to rephrase the texts in their own words and state the source of the texts explicitly. Ideally, students' write-ups should mostly consist of the students' own phrases and expressions, and use such borrowed and rephrased sentences only when doing so is absolutely needed. Copying texts from other sources is an instance of plagiarism, and if it happens to an academic, it can destroy his or her research career. If any of the reports of a group is found to plagiarise, everyone in the group will get F.


## 5. Homework

Submit your solutions in KLMS. We will create submission folders for all the homework assignments in KLMS.

## 6. Tentative Plan

* 08/29(Tue) - Introduction (Ch1).
* 08/31(Thu) - The PAC Learning Framework (Ch2).
* 09/05(Tue) - The PAC Learning Framework (Ch2).
* 09/07(Thu) - The PAC Learning Framework (Ch2).
* 09/12(Tue) - Rademacher Complexity and VC Dimension (Ch3).
* 09/14(Thu) - Rademacher Complexity and VC Dimension (Ch3).
* 09/19(Tue) - Rademacher Complexity and VC Dimension (Ch3).
* 09/21(Thu) - Rademacher Complexity and VC Dimension (Ch3).
* 09/26(Tue) - Model Selection (Ch4).
* 09/28(Thu) - Model Selection (Ch4).
* 09/26(Tue) - Model Selection (Ch4).
* 09/28(Thu) - __NO LECTURE. Chuseok.__
* 10/03(Tue) - __NO LECTURE. National Foundation Day.__
* 10/05(Thu) - Support Vector Machine (Ch5).
* 10/10(Tue) - Support Vector Machine (Ch5).
* 10/12(Thu) - Support Vector Machine (Ch5).
* 10/17(Tue), 10/19(Thu) - __NO LECTURES. Week for Mid-term Exams.__
* 10/24(Tue) - Support Vector Machine (Ch5).
* 10/26(Thu) - Kernel Methods (Ch6).
* 10/31(Tue) - Kernel Methods (Ch6).
* 11/02(Thu) - Kernel Methods (Ch6).
* 11/07(Tue) - Kernel Methods (Ch6).
* 11/09(Thu) - Regression (Ch11).
* 11/14(Tue) - Regression (Ch11).
* 11/16(Thu) - Regression (Ch11).
* 11/21(Tue) - Regression (Ch11).
* 11/23(Thu) - Special Topic.  
* 11/28(Tue) - Special Topic.
* 11/30(Thu) - __FINAL EXAM.__
* 12/05(Tue) - Project Presentations.
* 12/07(Thu) - Project Presentations.
* 12/12(Tue), 12/14(Thu) - __NO LECTURES. Week for Final Exams.__

## 7. Lecture Notes from Fall 2021

The lectures will be based on the following hand-written notes from the version of this course in the fall of 2021. The notes summarise the contents of the main textbook. Reading these notes and solving exercisers in the notes is a recommended way to study the topics covered by the course. 

* Introduction (Ch1) ([note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture1/CLT21-L1-Introduction.pdf)). Please ignore Sections 2 and 3 in the note, which are outdated.
* The PAC Learning Framework (Ch2) ([note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture2/CLT21-L2-PAC.pdf)).
* Rademacher Complexity and VC Dimension (Ch3) ([note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture3/CLT21-L3-Rademacher.pdf)).
* Model Selection (Ch4) ([note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture4/CLT21-L4-ModelSelection.pdf)).
* Support Vector Machine (Ch5) ([note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture5/CLT21-L5-SVM.pdf)).
* Kernel Methods (Ch6) ([note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture6/CLT21-L6-Kernel.pdf)).
* Regression (Ch11) ([note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture7/CLT21-L7-Regression.pdf)).

## 8. Study Materials

We will closely follow the textbook "Foundations of Machine Learning" (second edition) by Mohri, Rostamizadeh, and Talwalkar. The webpage of the textbook contains many useful materials, including the HTML version of the book and the list of typos.

* Main Textbook: [Foundations of Machine Learning (2nd edition)](https://cs.nyu.edu/~mohri/mlbook/).

