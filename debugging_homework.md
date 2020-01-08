# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?
  - When we add a break point to our code and run said code, the code will run as normal, until it hits the breakpoint. Here it will pause and launch the debugger in our IDE.

2. Does the line of code on a breakpoint run when you start debugging?
  - No

3. How do we debug the next line of code?
  - Using the debugger console we can use the step over button which will continue running the line we are on and then pause at the next line.

4. What does the step into command do?
  - The step into command will take us into the method and class which is using the line and open the debugger on the first line within the method of the class.

5. What is the difference between evaluate expression and evaluate code fragment?
  - An Expression is for the evaluation of a singular method or line of code, no ; are needed (or allowed). Fragment however, evaluates multiple methods or lines of code. We can also make temporary variables. ; are required.
