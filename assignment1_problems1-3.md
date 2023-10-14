# EMBSYS-310-A-Assignment-01
## EMBSYS 310 A Assignment 1: Hello World
### Author: Richard Castro
### Date: 10/14/2023


## Problem Questions 

### Problem 1

-   [X] Think about the print server and other examples in the Primer
-   [x] What is an embedded system you would like to investigate?
 * One fascinating embedded system to me is energy management system. One that includes the incoming grid power, a generator, an ESS, solar panels, and discharges to your electric car.
-   [x] Describe how you think it works
 * Rudamentary systems with just a backup generator need a basic ATS system. However when you have mutiple incoming sources, and potential high power loads this isn't the case. You need some type of MID, and that device requires a lot of embedded systems. 
- [x] What design challenges and constraints does it present?
* There are a lot of contraints such as: power management laws, power requirements for loads like electric cars, noise supression laws on the incoming power from generators since they're highly inductive, power ratings on releasing power back to the grid, etc.

### Problem 2

-   [x] What is the purpose / advantage of using Two's Complement binary arithmetic?
      - In Engineering it simplifies hardware design, reduces the number of special cases for software, and allows for efficient addition, subtraction, multiplication, and division operations when coding.
      - The purpose of two's complement is to simplify the process of binary addition and subtraction operations by allowing the representation of both positive/negative integers to be shown in a binary format. 

### Problem 3

-   [x] Why are bitwise operations so important?
    - Bitwise operations are important because they provide versatile tools for working with individual bits of data, which is essential in various aspects of embedded systems programming.
        - One of the tools it helps bring to light is binary formatting and manipulation. Datasheets often show the information we need in other number systems and it's essential to be able to work with this data.
        - Another tool that bitwise operations let you use is create bit level algorithms such as bitmaps. Bitwise operations are as fundamental to bitmaps as algebra is to calculus. 



## Create Pull Request
1. Open `<repo>` in a browser. You may already see a "Create new pull request" from your branch if you made recent changes. If not, select "Pull requests" and click "New". Leave `base: main` and modify `compare:` to point to your branch name. Create the new PR.
2. If you find that you need to make more changes, just commit and push new changes to your branch - the PR will be updated.

## Grading
1. DO NOT close or merge the PR - we will do it for you as we're grading.
2. To complete your homework, submit the PR link within Canvas (this step is mandatory - without something in Canvas, I won't be able to grade).
3. If I have any comments, I will leave them in the PR then also point out there are comments in Canvas together with your grade.

