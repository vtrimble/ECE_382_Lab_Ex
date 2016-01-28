# Descriptive title - Computer Exercise #1 - Introduction to the MSP430 and Code Composer Studio

## By Capt Jeff Falkinburg and Capt Trimble

## Table of Contents (not required but makes things easy to read)
1. [Objectives or Purpose](#objectives-or-purpose)
2. [Preliminary Design](#preliminary-design)
 * [Code](#code)
3. [Software flow chart or algorithms](#software-flow-chart-or-algorithms)
 * [Pseudocode](#pseudocode)
4. [Hardware schematic](#hardware-schematic)
5. [Well-formatted code](#well-formatted-code)
6. [Debugging](#debugging)
7. [Testing methodology or results](#testing-methodology-or-results)
8. [Answers to Lab Questions](#answers-to-lab-questions)
8. [Observations and Conclusions](#observations-and-conclusions)
9. [Documentation](#documentation)
 
### Objectives or Purpose 
This should include a paragraph on what is the goal of this assignment.  Why would your instructor make you do this exercise?

Remember, the purpose of the lab notebook is to communicate EVERYTHING you have done in pursuit of a particular project.  If you are sitting on the bus scribbling on the back of an envelope about your lab design, take a picture of that and include it with your work.  Without adequate documentation, your instructor won’t know what your thought process was and will not be able to grade you properly.  Once you leave the school environment, fellow engineers may need to pick up your project where you left off if you PCA, PCS, get hospitalized, or otherwise find yourself no longer working on something.  You will save your employer/co-workers/replacement a lot of time and money if you have left a detailed record for them to easily understand what you were doing, the approach you took, the tests you performed, and what you learned.  

What if you came back in 10 years and took a look at your lab notebook?  You should be able to follow exactly what was going on and replicate your work.

### Preliminary design
How will you start attacking the problem?
This should include detailed instructions of what you are about to do.  It may include prelab material and also information from the Lab Handout.  Use pictures and data from Lab Handout.  You should be thinking in this readme.  Just because you think wrongly doesn't mean you shouldn't write things down here.

You may also use snippets of code in here as well:

#### Code:

######Assembly Header:
	;-------------------------------------------------------------------------------
	; CompEx 1 - Introduction to the MSP430 and Code Composer Studio
	; Capt Jeff Falkinburg, USAF / 16 Jun 2015 (Start Date) / 16 Jun 2015 (Completion Date)
	;
	; Purpose:  This program is a demonstration of using the CCS IDE to
	; program, assemble, flash, and debug the MSP430.
	; 
	; Documentation: none 
	;-------------------------------------------------------------------------------

#####VHDL Header:
	--------------------------------------------------------------------
	-- Name:<Your Name>
	-- Date:<The date you stated working on the file>
	-- Course:	<The course's name>
	-- File:<This file's name>
	-- HW:	<HW# and name>
	--
	-- Purp:A brief description of what this program does and 
	--	the general solution strategy. 
	--
	-- Doc:	<list the names of the people who you helped>
	-- 	<list the names of the people who assisted you>
	--
	-- Academic Integrity Statement: I certify that, while others may have 
	-- assisted me in brain storming, debugging and validating this program, 
	-- the program itself is my own work. I understand that submitting code 
	-- which is the work of other individuals is a violation of the honor   
	-- code.  I also understand that if I knowingly give my original work to 
	-- another individual is also a violation of the honor code. 
	------------------------------------------------------------------------- 

#####C Header:
	/*--------------------------------------------------------------------
	Name:<Your Name>
	Date:<The date you stated working on the file>
	Course:	<The course's name>
	File:<This file's name>
	HW:	<HW# and name>
	
	Purp:A brief description of what this program does and 
		the general solution strategy. 
	
	Doc:	<list the names of the people who you helped>
			<list the names of the people who assisted you>
	
	Academic Integrity Statement: I certify that, while others may have 
	assisted me in brain storming, debugging and validating this program, 
	the program itself is my own work. I understand that submitting code 
	which is the work of other individuals is a violation of the honor   
	code.  I also understand that if I knowingly give my original work to 
	another individual is also a violation of the honor code. 
	-------------------------------------------------------------------------*/
	
### Software flow chart or algorithms
All coding include a pseudocode flow charts and algorithms defined your code and the algorithms used.  Visio or PowerPoint works well for this!  You can also use Raptor, should you desire to do so.

#### Pseudocode:
Insert pseudocode or flowchart here.  Explain the purpose, e.g. "this is my initial design for the program that will decode the hidden message"

### Hardware schematic
If you are wiring things up you will need to create a schematic for your design.

### Well-formatted code
All your code will be in the code folder and contain headers, comments, and good coding practices.  Please reference the Lab Notebook requirements page.

### Debugging
You should be keeping track of issues as you go along.  I didn't have any problems is not a good answer.  Describe the problems you had and what you did to fix it.  Again this is where I would say commit early and often and start your notebook when you start your code.

### Testing methodology or results
Detail the steps in getting the results you system is designed to achieve.  Have enough detail that someone can come behind and reproduce your results.

If you have a simulation, you should verify that each piece is correct.  You may have an output that changes every 10 ns, but it is vital that you check that each output signal is correct.  This means you MUST go through your simulation graph bit by bit.  This process may get tedious for a long simulation.  In that case, you can take a couple of screenshots and use arrows or a line to indicate the test you are talking about.  ("In figure 2 below, you can see that the inputs A, B, and C are 1, 0, and 1 respectively.  The output signal Y (in purple) has a value of 1.  This matches the fourth row of my truth table.  Figure 3 shows the sixth row of my truth table . . . . All of my simulation outputs have been verified as correct, and the results are in my truth table."

"I tested it and it worked fine" is unacceptable.  How about: "I implemented the truth table on my FPGA.  A switch in the up position represents a 1, and in the down position represents a 0.  The video below shows me testing each possible output in the order of the truth table.  You can see that the outut (the LED) is only illuminated in the 3rd and 7th tests, which matches exactly with my truth table above."

Display your results and describe them in detail so that anyone can understand.  For example Figure 1 below shows a screenshot of a memory dump for RAM from 0x0200 to 0x024E.  You will also describe to the reader what they are looking at.  "In Figure 1 below, you can see that the memory location 0x200 has a value of 0x00, which is what was expected."

![Memory Dump](images/Memory.PNG)
##### Figure 1: Memory Dump Label (Always include figure labels!)

### Answers to Lab Questions
Here is where you would answer any lab questions given in the lab writeup.

### Observations and Conclusions
During this whole assignment, what did you learn?  What did you notice that was noteworthy?  This should be a paragraph starting with the purpose, whether or not you achieved that purpose, what you learned, and how you can use this for future labs.  If you learned other lessons unintentionally, include them as well.  

### Documentation
– always include this.  Any help received on any portion of the assignment, even from an instructor or the internet should be specifically mentioned.
