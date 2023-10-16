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
 * Basic home energy systems with just a backup generator need a basic ATS(Automatic Transfer Switch).  However, when you have mutiple incoming power sources, and potential high power output loads this isn't the case. You need some type of MID(Microgrid Interconnect Device), which requires a lot of embedded systems. These are very complex devices that  my current company actually tried designing one for a year, before the renewable energy group got dissolved. It works by monotoring and controlling all of the inputs/outputs coming from it, and to be able to use energy as efficiently as possible. 
- [x] What design challenges and constraints does it present?
* There are a lot of contraints such as: power management laws, power requirements for loads like electric cars, noise supression laws on the incoming power from generators since they're highly inductive, power ratings on releasing power back to the grid (grid compliance), and it has to have safety measures .

### Problem 2

-   [x] What is the purpose / advantage of using Two's Complement binary arithmetic?
      - In Engineering it simplifies hardware design, reduces the number of special cases for software, and allows for efficient addition, subtraction, multiplication, and division operations when coding.
      - The purpose of two's complement is to simplify the process of binary addition and subtraction operations by allowing the representation of both positive/negative integers to be shown in a binary format. 

### Problem 3

-   [x] Why are bitwise operations so important?
    - When I took digital systems back in uni, we dicussed logic in computer systems. Basic logic gates include: NOT, AND, OR, XOR, NOR, and NAND. These gates allow me to perform digital computation which actually lets me design systems that have inputs that I want to condition in order to get some type of predictable output response. Hence in software these bitwise operations actually run on the same principles (logic gates), and allow me to once again design systems with predictable output responses to certain inputs. In embedded systems this is particularily useful since you need to use bitwise operations in order to work with differnt peripherals. For example setting up a pin on the development board as an LED will need to be programmed to be an output, use some type of internal clock, and we will need to write to it as well to turn it on/off. Noneof these instructions would be possible without proper bitwise operations. 



## Create Pull Request
1. Open `<repo>` in a browser. You may already see a "Create new pull request" from your branch if you made recent changes. If not, select "Pull requests" and click "New". Leave `base: main` and modify `compare:` to point to your branch name. Create the new PR.
2. If you find that you need to make more changes, just commit and push new changes to your branch - the PR will be updated.

## Grading
1. DO NOT close or merge the PR - we will do it for you as we're grading.
2. To complete your homework, submit the PR link within Canvas (this step is mandatory - without something in Canvas, I won't be able to grade).
3. If I have any comments, I will leave them in the PR then also point out there are comments in Canvas together with your grade.

