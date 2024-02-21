# Introduction to Scientific Computing DIFUSE Module

## Contributors: Jackeline Corona (‘22), Logan Sankey (‘20), Petra Bonfert-Taylor (Professor of Engineering, DIFUSE PI), Laura Ray(Professor of Engineering, DIFUSE PI), Taylor Hickey ('23, Project Manager)

![Introduction to Scientific Computing DIFUSE Module Funded by NSF IUSE1917002](repository_assets/DIFUSE-ENGS20.png)

This module was developed through the DIFUSE project at Dartmouth College and funded by the National Science Foundation award IUSE-1917002.


| <a href="https://github.com/difuse-dartmouth/engineering-glucose-model-ode/archive/refs/heads/main.zip"><img src="/repository_assets/download-all.png" alt="Download the entire module" align="center" style="width: 4in;"></a>| <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="width=2in" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /><br></a>This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. |
|---------|----------|

## Module Objective 
Student gain experience with using a numerical solver for a differential equations model coupled with parameter estimation based on a experimental data set.

## Student Learning Objectives
1. Establish a basic understanding of ODEs and MATLAB functionalities
2. Use a differential equation model of a real-world system to practice analysis of graphical behaviors in relation to equations.
4. Apply the Least-Squares Method to optimize one parameter in the model for a given set of data
5. Calculate additional parameters and compare these to acceptable values

## Module Description
Using MATLAB, in this module students address questions about a model of the relationship between glucose and insulin in humans. To do so, students explore the use of numerical solvers for ODE and systems of ODE, both by coding Euler’s method ‘by hand’ as well as by using built-in solvers. Students use published data to fit parameters of a model and make predictions with the numerical solutions. The final “long” coding assignment for ENGS 20 had traditionally been an investigation of the solutions to ordinary differential equations (ODEs) through the use of Euler’s method, analytical solutions, and ODE solvers in MATLAB. However, Professor Bonfert-Taylor recognized that this assignment often lacked the context of a real-world application when only the ODEs were provided for students to solve through various methods. She was interested in finding an ODE or a system of ODEs describing a real interaction that could be modeled by students along with data to provide inputs for and then validate the model.

She found resources from papers investigating the response of the human insulin system to glucose and proposed that the DIFUSE team develop a new long assignment in which students apply a simplified ODE model of this system. She also proposed a shorter coding assignment to be completed before the long assignment that introduces students to the concepts of ODEs and to coding Euler’s method.

### Data
This module using glucose and insulin level data taken from a published experiment.

### Platform
The module uses MATLAB live scripts.

## Schedule and Links

Use this page to get an idea of the timeline of the module, what components are involved, and what documents are related to each component. This is the schedule intended for module deployment by the DIFUSE team, though instructors are welcome to modify the timeline to fit their course environment.
[Guide for Instructors](https://github.com/difuse-dartmouth/21X_ENGS20/blob/6e9df446b205300b61e5de6e0a6af273df913e05/completed_module/public/logistics/Instructor%E2%80%99s%20Guide.pdf)

1. [Short Assignment](https://github.com/difuse-dartmouth/21X_ENGS20/blob/6e9df446b205300b61e5de6e0a6af273df913e05/completed_module/public/components/short%20assignment/short_assignment_student_instructions.pdf)
    - Three questions introduce the student to ODEs in MATLAB.
    - Students develop code to estimate a solution to an ODE with Euler’s method. Students then plot the solution for different coefficient values and plot the estimate against the analytical solution.
    - Assignment questions ask students to compare the effects of changing variables in the ODE and compare the estimated solution to the analytical solution.
2. [Long Assignment](https://github.com/difuse-dartmouth/21X_ENGS20/blob/6e9df446b205300b61e5de6e0a6af273df913e05/completed_module/public/components/long%20assignment/Long%20Assignment%20(Glucose-Insulin%20through%20Diff%20Equations).pdf) ([Student facing rubric](https://github.com/difuse-dartmouth/21X_ENGS20/blob/6e9df446b205300b61e5de6e0a6af273df913e05/completed_module/public/components/long%20assignment/Student%20Facing%20LA3%20Rubric.pdf))
    - Students model the Glucose Insulin System in MATLAB with Euler’s Method and explore the model by optimizing one parameter for a given set of data using the least-squares method.
    - Students comment on an initial plot and calculate if the initial parameters are within normal limits.
    - Students write code to perform an Euler’s method estimate of the model ODEs and then use the least-squares method to optimize one parameter of the model for a provided set of data.
    - Students are asked to plot the data and the estimate and also evaluate if the patient’s parameters are within the normal ranges.

## Implementation Calendar

Typically the short assignment is due three days after it's been assigned and the long assignment is due after a week.


<table align="left">
    <br><br>
  <tr>
    <th>Item</th>
    <th>Schedule</th>
  </tr>
  <tr>
    <td>MATLAB publishing tutorial</td>
    <td>Earlier in term</td>
  </tr>
  <tr>
    <td>Release Short Assignment (SA)</td>
    <td>At least three days before release of long assignment</td>
    
  </tr>
    <tr>
    <td>Release Long Assignment (LA)</td>
    <td> Due date of SA, 1 week before due date of LA </td>
    
  </tr> 
    <tr>
    <td>Return feedback on SA   </td>
    <td> One day after due date of SA </td>
    
  </tr>
     <tr>
    <td>TA sessions following up on SA</td>
    <td> One day after release of SA feedback </td>
    
  </tr>
     </tr>
     <tr>
    <td>Long Assignment due</td>
    <td> One week after LA release </td>
    
  </tr>
    
</table>
<img src="https://github.com/difuse-dartmouth/21X_ENGS20/blob/110922f65be828f0aa09fad4c9fd2fafa4787cf8/completed_module/public/ENGS%2020%20timeline.png" width="300" style = "float: right">

## Course Information

This module was developed for an Engineering course, <a href="http://dartmouth.smartcatalogiq.com/current/orc/Departments-Programs-Undergraduate/Engineering-Sciences/ENGS-Engineering-Sciences-Undergraduate/ENGS-20">Introduction to Scientific Computing</a>, which introduces students to programming in C and MATLAB as well as the foundations of scientific computing.  Students are not assumed to have any programming experience at the outset, but learn both platforms leading up to the module.
---

| <a href="https://github.com/difuse-dartmouth/engineering-glucose-model-ode/archive/refs/heads/main.zip"><img src="/repository_assets/download-all.png" alt="Download the entire module" align="center" style="width: 4in;"></a>| <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="width=2in" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /><br></a>This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. |
|---------|----------|

For instructors and interested parties, the history of this repository (with detailed commits), can be found [here](https://github.com/difuse-dartmouth/engineering-glucose-model-ode/commits/main/).


