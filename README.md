# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Caden Anderson Brolen Gumb
## Lab Summary
In both parts 1 and 2 we reinforced our knowledge of deriving minimization
functions using K-Maps. In the same parts we learned how to implement the same
function into two modules. In part 3 we learned how to create a top module
in order to connect all inputs and outputs using the desired functions we
previously derived. We also learned how to use a wire to connect an output
of one function to an input of another function. In part 4 we learned how to 
map certain LEDs and PINs to our specified switches and outputs, using the
constraint file.
## Lab Questions

### 1 - Explain the role of the Top Level file.
    * The Top level file acts as the root of the design hierarchy, declaring inputs, outputs, & other important information to be passed into other files.

### 2 - Explain the function of the Constraints file.
    * The Constraint file is used to specify physical requirements for synthesis to ensure the final circuit acts how it is meant to.

### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
It doesn't appear that there was a right and wrong option for either options. In the case of Part A., 
the Minterm and Maxterm functions were the exact same. Although there were fewer groupings when finding
the minterm. Therefor minterm more than likely would've been our choice for Part A. While the equations
in part B were different from each other, there truly was no distinct advantage to either process. Both
the Minterm and Maxterm K-Map processes yeilded three grouping of four and both functions resulted in
same amount of terms and operations. Yet, if a choice is required, the Minterm process had clearer groupings.

