
# Assignment 1 Problem 1

-   Think about the print server and other examples in the Primer

-   What is an embedded system you would like to investigate?

-   Describe how you think it works

-   What design challenges and constraints does it present

## Write your answer below:
  - One fascinating embedded system to me is energy management system. One that includes the incoming grid power, a generator, an ESS, solar panels, and discharges to your electric car.
  - How I would describe it works is, basic home energy systems with just a backup generator need a basic ATS(Automatic Transfer Switch). However, when you have mutiple incoming power sources, and potential high power output loads this isn't the case. You need some type of MID(Microgrid Interconnect Device), which requires a lot of embedded systems. These are very complex devices that my current company actually tried designing one for a year, before the renewable energy group got dissolved. It works by monotoring and controlling all of the inputs/outputs coming from it, and by using internal logic to determine what is the most efficient way to distribute its energy among the microgrid it's apart of. The microgrid being my house that's connected to the grid, a generator, an electric car, solar panels, electric storage system(ESS), and my home loads.
  - There are a lot of contraints such as: power management laws, power requirements for loads like electric cars, noise supression laws on the incoming power from generators since they're highly inductive, power ratings on releasing power back to the grid (grid compliance), and it has to have safety measures .
---
# Assignment 1 Problem 2

-   What is the purpose / advantage of using Two's Complement binary arithmetic?
  
## Write your answer below:
  - In Engineering the advantage of two's compliment implementation is simplifiying hardware design, reducing the number of special cases in software, and allowing for efficient addition, subtraction, multiplication, and division operations when coding.
  - The purpose of two's complement is to simplify the process of binary arithmetic operations by allowing the representation of both positive/negative integers to be shown in a binary format. 


---
# Assignment 1 Problem 3

-   Why are bitwise operations so important?

## Write your answer below:
  -  When I took digital systems back in uni, we dicussed logic in computer systems. Basic logic gates include: NOT, AND, OR, XOR, NOR, and NAND. These gates allow me to perform digital computation which actually lets me design systems that have inputs that I want to condition in order to get some type of predictable output response. Hence in software these bitwise operations actually run on the same principles (logic gates), and allow me to once again design systems with predictable output responses to certain inputs. In embedded systems this is particularily useful since you need to use bitwise operations in order to work with differnt peripherals. For example setting up a pin on the development board as an LED will need to be programmed to be an output, use some type of internal clock, and we will need to write to it as well to turn it on/off. None of these instructions would be possible without proper bitwise operations. One quick example for being able to set a bit is by using the bitwise OR operator, which will need to be done to certain registers in order to configure peripherals accordingly. 
