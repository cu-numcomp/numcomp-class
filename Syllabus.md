# Syllabus

CU Boulder: CSCI 3656 (Spring 2020)

Meeting Time: TR 9:30-10:45pm in HALE 230

### Instructor

[Jed Brown](https://jedbrown.org), [<tt>jed.brown@colorado.edu</tt>](mailto:jed.brown@colorado.edu), ECOT 824

Office Hours: Mon/Fri 10-11am, Thu 2-3:15pm, or by appointment.

## Overview

Covers development, computer implementation, and analysis of numerical methods for applied mathematical problems. Topics include floating point arithmetic, numerical solution of linear systems of equations, root finding, numerical interpolation, differentiation, and integration.

## Target audience

Core option for Computer Science BS and BA students.  This course may
also be of interest for non-CS students interested in theory and
practice of numerical computation.

### Required prerequisites (all minimum grade C-)

* Introductory programming: CSCI 1300 or CSCI 1310 or CSCI 1320 or ECEN 1310
* Calculus 2: APPM 1360 or MATH 2300
* Linear Algebra: CSCI 2820 or MATH 2130 or APPM 2360 or APPM 3310

## Outcomes

Upon completion of this course, students will possess the following traits as applied to the topics in scope (see below).

1. *Formulation*: proficiency at formulating real-world problems as instances of well-posed numerical problems
2. *Choice*: an ability to choose appropriate numerical methods for solving mathematical models arising in science and engineering
3. *Critique*: an understanding of the merits and limitations of those numerical methods
4. *Tradeoffs*: an understanding of accuracy vs cost tradeoffs in the key algorithms of continuous mathematics
5. *Creation*: an ability to write effective numerical programs, taking into account stability, accuracy, and cost
6. *Software*: familiarity with numerical libraries that provide production-grade implementations of state of the art numerical methods

## Scope

Students will be introduced to the formulation and solution of numerical problems of the following types

1. Rootfinding (solving nonlinear algebraic equations)
2. Numerical linear algebra
3. Interpolation
4. Regression
5. Numerical optimization
6. Numerical differentiation
7. Numerical integration
8. Numerical solution of ordinary differential equations

and will be familiar with these cross-cutting themes which are essential to robustness and to diagnosing failures:

* Stability of numerical algorithms
* Conditioning of physical problems and mathematical formulations

## Evaluation

### 20% class participation and in-class activities
Please bring a computer to class so that you can complete activities using Jupyter or Moodle.
These will be short and you'll be able to finish during class.
If you can't attend a particular class, you may still accept the activity and complete it within 48 hours of the class for full credit.

### 10% Perusall readings and discussion
We will have regular readings from various sources (online material, book excerpts, etc.) that I'll share via Perusall.
This tool allows you to ask and answer questions (anonymously or not) and rate peer answers.
Your participation will inform lecture content and class activities.

### 30% homework
There will be several homework assignments in which you will develop and evaluate numerical methods.
You will have at least one week from the date such an assignment is announced until its due date.
These assignments will usually consist of a combination of autograded and manually-graded parts (such as figures or free-text explanations); feedback will be returned within a week.

### 15% midterm exam
There will be one in-class midterm covering roughly the first half of the course, tentatively scheduled for March 5.

### 5% group presentations
You will give individual presentations to small groups about a method or application of numerical computation, applying concepts learned in class.
Each presentation will be followed by a question and answer session.
This is tentatively scheduled for March 17.

### 20% final project
The final project will involve working in teams of 3-4 on a project of your choosing.
Each team will give a presentation during the "final exam period" at the end of the semester.
Following all presentations, each team member will participate individually in a question and answer session.

## Technology

### Git and GitHub

Homework assignments and in-class activities will be submitted via Git.  This class will use GitHub classroom.

To follow along with lectures, you can fork the [class repository](https://github.com/cu-numcomp/numcomp-class).  Homeworks will be completed by cloning GitHub repositories, completing coding and analysis activities using Jupyter, and pushing completed assignments back to GitHub.

You will complete assignments using [Jupyter](https://jupyter.org/), which is available on the [Coding CSEL Hub](https://coding.csel.io/) and can be installed locally on most operating systems.

It is notoriously difficult to predict the time required to develop quality code, so please start early to give yourself plenty of time.  You are welcome to work together on all assignments, but must give credit to collaborators (at the top of each notebook).  You should ensure that each assignment you submit contains significant intellectual contribution of your own.

### Programming languages and environment

I will use Python with [Jupyter notebooks](https://jupyter.org/) in class and for homeworks.  This environment is convenient to work with, general purpose, and has extensive library support.  Native Python code is not high performance, however, so the scientific Python stack depends on numerical libraries written in other languages, such as C, C++, or Fortran.  MATLAB is also popular for numerical computing, though it is a proprietary environment and lacks general-purpose libraries.  Octave is a free MATLAB clone and Julia is a modern language that preserves much of the syntactic convenience.

Most high-performance computing (HPC), data science, and cloud resources use a Linux operating system.  You can use any environment for your local development environment, but I recommend the [Coding CSEL Hub](https://coding.csel.io/) because it includes a complete software environment and you can access it from any machine.

### Moodle

Moodle will be used to maintain grades.  Please [enroll yourself](https://moodle.cs.colorado.edu).

### Perusall

Perusall is a tool for social reading.
We'll use it to preview material before class and as formative assessment with concepts we cover in class.
It's meant to encourage collaboration and written communication about concepts.
There will be a small participation grade associated with these activities.
If you read the document and participate by asking and/or answering questions, you'll receive full credit.
Skimming at the last-minute will result in partial credit.

## Resources

This course will follow a collection of Jupyter notebooks.  The notebooks are intended to be self-contained.  There is no required textbook, but the following resources may be helpful.

* [Greenbaum and Chartier (2012), **Numerical Methods Design, Analysis, and Computer Implementation of Algorithms**](https://press.princeton.edu/titles/9763.html) -- an excellent, comprehensive book.
* [Driscoll and Braun (2017), **Fundamentals of Numerical Computation**](http://bookstore.siam.org/ot154/) -- another modern and comprehensive book, with [examples and videos](https://github.com/tobydriscoll/fnc-extras).
* [Sauer (2012), **Numerical Analysis**](https://www.pearson.com/us/higher-education/program/Sauer-Numerical-Analysis-2nd-Edition/PGM223463.html) -- used for this course in other semesters.
* [Boyd and Vandenberghe (2018), **Introduction to Applied Linear Algebra**](https://web.stanford.edu/~boyd/vmls/) -- practical introduction to linear algebra for computer scientists; free PDF
* [Trefethen and Bau (1997), **Numerical Linear Algebra**](http://bookstore.siam.org/ot50/) -- fantastic, but limited to numerical linear algebra and covers more advanced topics.
* [Eijkhout (2017), **Introduction to High-Performance Scientific Computing**](http://pages.tacc.utexas.edu/~eijkhout/istc/istc.html) -- includes introductory numerical linear algebra from a performance standpoint; free PDF.
* [Scopatz and Huff (2015), **Effective Computation in Physics**](http://physics.codes/) -- Python language, data science workflow, and computation.

A [SIAM Membership](http://www.siam.org/students/memberships.php) is free for CU students and provides a 30% discount on SIAM books.

## Disability Accommodations

If you qualify for accommodations because of a disability, please submit your accommodation letter from Disability Services to your faculty member in a timely manner so that your needs can be addressed.  Disability Services determines accommodations based on documented disabilities in the academic environment.  Information on requesting accommodations is located on the [Disability Services website](http://www.colorado.edu/disabilityservices/students). Contact Disability Services at 303-492-8671 or dsinfo@colorado.edu for further assistance.  If you have a temporary medical condition or injury, see [Temporary Medical Conditions](http://www.colorado.edu/disabilityservices/students/temporary-medical-conditions) under the Students tab on the Disability Services website.

## Classroom Behavior

Students and faculty each have responsibility for maintaining an appropriate learning environment. Those who fail to adhere to such behavioral standards may be subject to discipline. Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with race, color, national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation or political philosophy.  For more information, see the policies on [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior) and the [Student Code of Conduct](http://www.colorado.edu/osccr/).

## Preferred Names and Pronouns

CU Boulder recognizes that students' legal information doesn't always align with how they identify. Students may update their preferred names and pronouns via the student portal; those preferred names and pronouns are listed on instructors' class rosters. In the absence of such updates, the name that appears on the class roster is the student's legal name.

## Discrimination and Harassment

The University of Colorado Boulder (CU Boulder) is committed to fostering a positive and welcoming learning, working, and living environment. CU Boulder will not tolerate acts of sexual misconduct, intimate partner abuse (including dating or domestic violence), stalking, or protected-class discrimination or harassment by members of our community. Individuals who believe they have been subject to misconduct or retaliatory actions for reporting a concern should contact the Office of Institutional Equity and Compliance (OIEC) at 303-492-2127 or cureport@colorado.edu. Information about the OIEC, university policies, [anonymous reporting](https://cuboulder.qualtrics.com/jfe/form/SV_0PnqVK4kkIJIZnf), and the campus resources can be found on the [OIEC website](http://www.colorado.edu/institutionalequity/).

Please know that faculty and instructors have a responsibility to inform OIEC when made aware of incidents of sexual misconduct, discrimination, harassment and/or related retaliation, to ensure that individuals impacted receive information about options for reporting and support resources.

## Honor Code

All students enrolled in a University of Colorado Boulder course are responsible for knowing and adhering to the Honor Code. Violations of the policy may include: plagiarism, cheating, fabrication, lying, bribery, threat, unauthorized access to academic materials, clicker fraud, submitting the same or similar work in more than one course without permission from all course instructors involved, and aiding academic dishonesty. All incidents of academic misconduct will be reported to the Honor Code (honor@colorado.edu; 303-492-5550). Students found responsible for violating the academic integrity policy will be subject to nonacademic sanctions from the Honor Code as well as academic sanctions from the faculty member. Additional information regarding the Honor Code academic integrity policy can be found at the [Honor Code Office website](https://www.colorado.edu/osccr/honor-code).

## Religious Observances

[Campus policy regarding religious observances](http://www.colorado.edu/policies/fac_relig.html) requires that faculty make every effort to deal reasonably and fairly with all students who, because of religious obligations, have conflicts with scheduled exams, assignments or required assignments/attendance. If this applies to you, please speak with me directly as soon as possible at the beginning of the term. See the [campus policy regarding religious observances](http://www.colorado.edu/policies/observance-religious-holidays-and-absences-classes-andor-exams) for full details.
