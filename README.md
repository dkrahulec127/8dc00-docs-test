# Medical Image Analysis course (8DC00)
This course is a sequel to the second year introductory imaging course. In that course the basic principles of image analysis were covered. In 8DC00 we will concentrate on the more advanced image analysis methods and on how they can be used to tackle clinical problems. Topics covered include image registration and computer-aided diagnosis (CAD).

## Learning outcomes
After passing this course, the student is able to:
1.	explain the fundamental principles behind point- and intensity-based image registration.
2.	compose (homogeneous) 2D transformation matrices and identify the required transformation model, image similarity measure and optimization method, given an example of a medical image registration problem.
3.	explain the fundamental principles behind machine learning for medical image analysis tasks (classification & regression), including the k-Nearest neighbors algorithm and linear and logistic regression.
4.	recall the different building blocks of (convolutional) neural networks and explain how supervised and unsupervised machine learning techniques can be applied to medical image analysis problems.
5.	design medical image analysis methods using basic engineering and mathematical techniques such as optimization, and implement these techniques in Python.
6.	analyze the performance of the medical image analysis methods using appropriate validation metrics and interpret the results in a scientific report.

## Use of Canvas
This GitHub page contains information about the course and the study material. The [Canvas page of the course](https://canvas.tue.nl/courses/17910) will be used only for sharing course information that cannot be made public, submission of the practical work and posting questions to the instructors and teaching assistants (in the Discussion section). Students are highly encouraged to use the Discussion section in Canvas for general questions (e.g., issues with programming environment, methodology questions).

TLDR: GitHub is for content, Canvas for communication and submission of assignments.

## Schedule
The 2021 edition of the course will be given on campus. 

The schedule is as follows:

* **Lectures**: Tuesdays 13:30 – 15:30 (location: Gemini-zuid 3A.12) & Thursdays 8:45 – 10:45 (location: Atlas -1.310)
* **Guided self-study**: Tuesdays 15:30 - 17:30 (location: Gemini-zuid 3A.12/13) & Thursdays 10:45 - 12:45 (location: Atlas 2.215/Helix oost 1.91)

NB: Since there are two rooms available for the guided self-study, students with last names starting with A-K are requested to work in the first room that is mentioned, and L-Z in the second room.

The topics of the lectures and the suggested notebooks to work on during the guided selfstudy hours are summarized below:

| Week | Day | Date   | Time        | Activity                                 | Module              | Lecturer         | Topic                                                                                                        |
| ---- | --- | ------ | ----------- | ---------------------------------------- | ------------------- | ---------------- | ------------------------------------------------------------------------------------------------------------ |
| 1    | Tue | 07/Sep | 13:30-15:30 | Lecture                                  | Registration        | M. van Eijnatten | Course introduction; installation instructions; introduction into image registration                         |
|      | Tue | 07/Sep | 15:30-17:30 | Guided selfstudy                         | Registration        |                  | Notebook 0.1                                                                                                 |
|      | Thu | 09/Sep | 08:45-10:45 | Lecture                                  | Registration        | M. van Eijnatten | Geometrical transformations                                                                                  |
|      | Thu | 09/Sep | 10:45-12:45 | Guided selfstudy                         | Registration        |                  | Notebook 1.1                                                                                                 |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 2    | Tue | 14/Sep | 13:30-15:30 | Lecture                                  | Registration        | M. van Eijnatten | Point-based registration                                                                                     |
|      | Tue | 14/Sep | 15:30-17:30 | Guided selfstudy                         | Registration        |                  | Notebook 1.2                                                                                                 |
|      | Thu | 16/Sep | 08:45-10:45 | Lecture                                  | Registration        | M. van Eijnatten | Intensity-based registration                                                                                 |
|      | Thu | 16/Sep | 10:45-12:45 | Guided selfstudy                         | Registration        |                  | Notebook 1.3 & 1.4                                                                                           |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 3    | Tue | 21/Sep | 13:30-15:30 | Lecture                                  | Registration        | T. van Walsum    | Guest lecture 1: dr. Theo van Walsum (Erasmus MC)                                                            |
|      | Tue | 21/Sep | 15:30-17:30 | Guided selfstudy                         | Registration        |                  | Work on project 1                                                                                            |
|      | Thu | 23/Sep | 08:45-10:45 | Lecture                                  | Registration        | M. van Eijnatten | Validation; Active shape models                                                                              |
|      | Thu | 23/Sep | 10:45-12:45 | Guided selfstudy                         | Registration        |                  | Notebook 1.5 & work on project 1                                                                             |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 4    | Tue | 28/Sep | 13:30-15:30 | Lecture                                  | CAD                 | M. Veta          | Introduction into CAD and machine learning                                                                   |
|      | Tue | 28/Sep | 15:30-17:30 | Guided selfstudy                         | CAD                 |                  | Notebook 2.1                                                                                                 |
|      | Thu | 30/Sep | 08:45-10:45 | Lecture                                  | CAD                 | M. Veta          | Linear regression                                                                                            |
|      | Thu | 30/Sep | 10:45-12:45 | Guided selfstudy                         | CAD                 |                  | Notebook 2.1                                                                                                 |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
|      | Fri | 01/Oct | 23:59       | DEADLINE Report project 1 (registration) |                     |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 5    | Tue | 05/Oct | 13:30-15:30 | Lecture                                  | CAD                 | M. Veta          | Logistic regression and neural networks                                                                      |
|      | Tue | 05/Oct | 15:30-17:30 | Guided selfstudy                         | CAD                 |                  | Notebook 2.2                                                                                                 |
|      | Thu | 07/Oct | 08:45-10:45 | Lecture                                  | CAD (CNNs)          |                  | Convolutional neural networks                                                                                |
|      | Thu | 07/Oct | 10:45-12:45 | Guided selfstudy                         | CAD (CNNs)          |                  | Notebook 2.3                                                                                                 |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 6    | Tue | 12/Oct | 13:30-15:30 | Lecture                                  | CAD (CNNs)          |                  | Deep learning frameworks and applications                                                                    |
|      | Tue | 12/Oct | 15:30-17:30 | Guided selfstudy                         | CAD (CNNs)          |                  | Work on project 2                                                                                            |
|      | Thu | 14/Oct | 08:45-10:45 | Lecture                                  | CAD (CNNs)          |                  | Unsupervised machine learning                                                                                |
|      | Thu | 14/Oct | 10:45-12:45 | Guided selfstudy                         | CAD (CNNs)          |                  | Notebook 2.5 & work on project 2                                                                             |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 7    | Tue | 19/Oct | 13:30-15:30 | Lecture                                  | Registration + CNNs | M. van Eijnatten | First hour: Deep learning for deformable image registration; Second hour: Questions & preparing for the exam |
|      | Tue | 19/Oct | 15:30-17:30 | Guided selfstudy                         |                     |                  | Work on project 2                                                                                            |
|      | Thu | 21/Oct | 08:45-10:45 | Lecture                                  | CAD                 |                  | Guest lecture 2: t.b.d.                                                                                      |
|      | Thu | 21/Oct | 10:45-12:45 | Guided selfstudy                         |                     |                  | Work on project 2                                                                                            |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
|      | Fri | 29/Oct | 23:59       | DEADLINE Report project 2 (CAD)          |                     |                  |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
|      | Tue | 02/Nov | 09:00-12:00 | WRITTEN EXAM                             |                     |                  |                                                                                                              |

## Materials
Primary study materials are the **lecture slides** and the **reader** in the form of Jupyter notebooks containing theory, practical exercises and questions. In addition, you can study the relevant sections from the following books:

* Fitzpatrick, J.M., Hill, D.L. and Maurer Jr, C.R., [Image registration](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.464.5408&rep=rep1&type=pdf).
* Kolter, Z. Do, C., [Linear Algebra Review and Reference](http://cs229.stanford.edu/section/cs229-linalg.pdf)
* Toennies, Klaus D., [Guide to Medical Image Analysis - Methods and Algorithms](https://www.springer.com/gp/book/9781447173182)

# Practical work (exercises and project work)
During the practical sessions the students can work on practical exercises and the project (however, it is expected that students will also work on the project in their own time). The goal of the practical exercises is to help study and understand the material, and develop code and methods that can be used to complete the project work. The project work is divided into two projects, corresponding to the three two main modules of the course. The project work will be done in groups. The groups will be formed in Canvas and you will also submit all your work there (check the Assignments section for the deadlines). Your are expected to do this work independently with the help of the teaching assistants during the guided self-study sessions (begeleide zelfstudie). You can also post your questions in the Discussion section in Canvas at any time.

## Software

**IMPORTANT: It is essential that you correctly set up the Python working environment by the end of the first week of the course so there are no delays in the work on the practicals.**

To get started, carefully follow the instructions in Notebook 0.1.

## Python quiz

**IMPORTANT: Attempting the quiz before the specified deadline is mandatory.**

In the first week of the course you have to do a Python self-assessment quiz in Canvas. The quiz will not be graded. If you fail to complete the quiz before the deadline, you will not get a grade for the course. The goal of the quiz is to give you an idea of the Python programming level that is expected.

If you lack prior knowledge of the Python programming language, you can use the material in the "Python essentials" and "Numerical and scientific computing in Python" modules available [here](https://github.com/tueimage/essential-skills/).

## Reading assignment
As a part of the second project (CAD), you are asked to study a paper by [Graham et al. (2019)](https://doi.org/10.1016/j.media.2019.101563). Give a brief summary of the proposed method and discusss its advantages and weak points in your project report. Assessment will be included in the grade of the report.

## Assessment
The assessment will be performed in the following way:
* Project work: 30% of the grade (both projects have equal contribution)
* Written exam (open answer and multiple-choice questions): 70% of the grade

To pass the course the written exam grade needs to be > 5.0 and the final grade needs to be > 5.5.

Grading of the assignments will be done per group, however, it is possible that individual students get a separate grade from the rest of the group (e.g. if they did not sufficiently participate in the work of the group). More info on the assessment criteria can be found [here](rubric.md).

## Lecturers and teaching assistants
Course instructors:
* Maureen van Eijnatten  -  [(Make an appointment with Maureen)](https://maureenvaneijnatten.youcanbook.me)
* Mitko Veta

Guest lecturers:
* Theo van Walsum (Erasmus MC)
* 

Teaching assistants:
* Luuk van der Hoek (MSc student)
* Roderick Westerman (MSc student)
* Myrthe van den Berg (MSc student)
* Tim Jaspers (MSc student)
* Luuk Jacobs (MSc student)

The main communication with the teachers will be via Canvas and regularly scheduled office hours. We recommend the Discussion section in Canvas as the primary communication channel as this is visible for all students and teachers. Please note that the frequency of the office hours will not increase close to deadlines and the exam, so if you have any questions please come well on time.
