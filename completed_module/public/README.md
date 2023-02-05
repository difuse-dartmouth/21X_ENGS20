# Introduction to Scientific Computing Data Science Module

This folder contains all the components of the data science module for Dartmouth College's Engineering 6: Introduction to Scientific Computing.

## Primary Objective

The final “long” coding assignment for ENGS 20 had consistently been an investigation of the solutions to ordinary differential equations (ODEs) through the use of Euler’s method, analytical solutions, and ODE solvers in Matlab. However, Professor Bonfert-Taylor recognized that this assignment often lacked the context of a real-world application when only the ODEs were provided for students to solve through various methods. She was interested in finding an ODE or a system of ODEs describing a real interaction that could be modeled by students along with data to provide inputs for and then validate the model.

She found resources from papers investigating the response of the human insulin system to glucose and proposed that the DIFUSE team develop a new long assignment in which students apply an ODE model of this system. She also proposed a shorter coding assignment to be completed before the long assignment that introduces students to the concepts of ODEs and Euler’s method.

## Student Expectations

This course serves as an introduction to computer science for students in Engineering. Students begin by learning to code in C, and towards the end of the course, students also learn to code in MATLAB. This course or the combination of Computer Science 1 and Computer Science 10 serves as the computer science prerequisite to most engineering courses, so many students enroll in this class. Students entering this class are required to have prerequisite math skills, but no prior coding knowledge or experience is required.


## Learning Objectives 
By completing this term project, you will:
1. Establish a basic understanding of ODEs and MATLAB functionalities
2. Use a differential equation model of a real-world system to practice analysis of graphical behaviors in relation to equations.
3. Apply the Least-Squares Method to optimize one parameter in the model for a given set of data
4. Calculate additional parameters and compare these to acceptable values


## Module Outline
[Guide for Instructors](https://github.com/difuse-dartmouth/21X_ENGS20/blob/6e9df446b205300b61e5de6e0a6af273df913e05/completed_module/public/logistics/Instructor%E2%80%99s%20Guide.pdf)

1. [Short Assignment](https://github.com/difuse-dartmouth/21X_ENGS20/blob/6e9df446b205300b61e5de6e0a6af273df913e05/completed_module/public/components/short%20assignment/short_assignment_student_instructions.pdf)
    - Three questions introduce the student to ODEs in Matlab.
    - Students develop code to estimate a solution to an ODE with Euler’s method. Students then plot the solution for different coefficient values and plot the estimate against the analytical solution.
    - Assignment questions ask students to compare the effects of changing variables in the ODE and compare the estimated solution to the analytical solution.
2. [Long Assignment](https://github.com/difuse-dartmouth/21X_ENGS20/blob/6e9df446b205300b61e5de6e0a6af273df913e05/completed_module/public/components/long%20assignment/Long%20Assignment%20(Glucose-Insulin%20through%20Diff%20Equations).pdf) ([Student facing rubric](https://github.com/difuse-dartmouth/21X_ENGS20/blob/6e9df446b205300b61e5de6e0a6af273df913e05/completed_module/public/components/long%20assignment/Student%20Facing%20LA3%20Rubric.pdf))
    - Students Model the Glucose Insulin System in Matlab with Euler’s Method and explore the model by optimizing one parameter for a given set of data using the least-squares method.
    - Students comment on an initial plot and calculate if the initial parameters are within normal limits.
    - Students write code to perform an Euler’s method estimate of the model ODEs and then use the least-squares method to optimize one parameter of the model for a provided set of data.
    - Students are asked to plot the data and the estimate and also evaluate if the patient’s parameters are within the normal ranges.

## Implementation Calendar

| Item                            | Schedule                                            |
|:---:|:---:|
| MATLAB publishing tutorial      | Earlier in term                                     |
| Release Short Assignment (SA)   | At least one week before release of long assignment |
| Release Long Assignment  (LA)   | Due date of Short Assignment                        |
|                                 | (Beginning of second to last week of class)         |
| Return feedback on SA           | Two days after due date                             |
| TA sessions following up on SA  | ~Two days after release of feedback                 |
| LA due                          | Last day of class                                   | 
