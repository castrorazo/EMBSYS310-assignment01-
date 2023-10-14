# EMBSYS-310-A-Assignment-01
## EMBSYS 310 A Assignment 1: Hello World

Welcome to the course! 

## Goal

The goal for this assignment is primarily to set up your development environment ready for future assignments.

This involves:

1.  Getting your GitHub repository set up to begin working on source code and documentation
2.  Setting up your IDE
3.  Setting up your hardware development kit and validating it works and you can connect, program and debug on the development kit

## Reading

-   Read the Wikipedia article on Embedded Systems:
    https://en.wikipedia.org/wiki/Embedded_system

-   Read chapter 1 and section 2.5 from "An Embedded Software Primer"
-   Read all of Level 0 of "Modern C" (PDF in Files)
-   Read Section 5 of "Modern C"

## Problem Questions (In your own words)

### Problem 1

-   Think about the print server and other examples in the Primer
-   What is an embedded system you would like to investigate?
-   Describe how you think it works
-   What design challenges and constraints does it present?
      - Applesssss

### Problem 2

-   What is the purpose / advantage of using Two's Complement binary arithmetic?
      - In Engineering it simplifies hardware design, reduces the number of special cases for software, and allows for efficient addition, subtraction, multiplication, and division operations when coding.
      - The purpose of two's compliment is to simplify the process of binary addition and subtraction operations by allowing the representation of both positive/negative integers to be shown in a binary format. 

### Problem 3

-   Why are bitwise operations so important?

## Setting up GitHub

1.  If you do not already have a GitHub account, set one up.
2.  Use the link in the assignment to crate a personalized GitHub classroom project
3.  Clone the project to your computer and complete the assignment there
4.  The Markdown files to fill in will be in the Assignments sub-directory

## Installing and Setting up STM32CubeIDE

Follow the instructions in the "STM32CubeIDE Setup Instructions.pdf" document available in the Files section of Canvas and in the Assignments folder of this repository.

## Deliverables

1.  assignment1_problems1-3.md -- A markdown file containing the answer to Problem 1, 2, and 3
2.  assignment01_term_output.md -- A markdown file containing a screenshot of the Tera Term output from your Hello World project running on your development board.
3.  A folder with your source code for the "Hello World" assignment.

For deliverable 2, since Markdown files are pure text documents, you will need to upload the image to your GitHub folder and provide a link in the markdown file to the image. See the GitHub documentation on how to do this:

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

Provide the URL of your GitHub pull request in Canvas.

# GitHub Classroom Flow
## Cloning and working on project
1. Click on the GitHub Classroom link. This will create your own GitHub repo with starter code for the homework.
2. Clone the repo locally: `git clone <repo>`
3. Create a working branch: `git checkout -b assignment01`
4. Make incremental changes to the code, commit and push. I suggest doing this any time you would like to save the state of the code that you may want to go back to. The number of commits and their content is irrelevant for homework grading (have as many as you would like).
 
```
git add -A :/
git commit -m "A good description of the changes"
git push
<repeat as many times as you'd like>
```

## Create Pull Request
1. Open `<repo>` in a browser. You may already see a "Create new pull request" from your branch if you made recent changes. If not, select "Pull requests" and click "New". Leave `base: main` and modify `compare:` to point to your branch name. Create the new PR.
2. If you find that you need to make more changes, just commit and push new changes to your branch - the PR will be updated.

## Grading
1. DO NOT close or merge the PR - we will do it for you as we're grading.
2. To complete your homework, submit the PR link within Canvas (this step is mandatory - without something in Canvas, I won't be able to grade).
3. If I have any comments, I will leave them in the PR then also point out there are comments in Canvas together with your grade.

## Troubleshooting:
- The first time you click a link for this classroom, you may need to associate your GitHub account to the classroom.
- Some students reported they don't have access: this is a GitHub Classroom bug. If this happens, contact us immediately supplying the repo link as well as your GitHub account name. Create the repos as soon as possible to give us time to address any permissions issue before the assignments are due.
