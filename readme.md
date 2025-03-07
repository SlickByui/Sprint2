## Overview

**Project Title**: Random Walk Numerical Model

**Project Description**: Numerical model that simulates random walk cycle of N particles in three
dimensions within a finite square container.

**Project Goals**:
 Requirements:
  Has the following:
    1. Conditionals      [x]
    2. Loops             [x]
    3. Functions         [x]
    4. Classes           [x]
    5. Data structure from STL (such as a vector, list, or map) [x]
  Stretch:
    - Modify your program to read and write to a file.                                        [x]
    - Modify your program to demonstrates inheritance with virtual functions.                 [x]
    - Modify your program to use the new and delete operators to dynamically create objects.  [x]

## Instructions for Build and Use

Steps to build and/or run the software:

To Build
1. Make sure GNU compiler is installed
2. Run 'g++ -o main.exe main.cpp randomWalk.cpp' inside the project directory

To Run
1. Execute 'main.exe' in project directory
2. After program finishes, open gnuplot
3. run command load 'rplot.gnuplot' to create the plot of the mean squared plot
4. run command load 'animate.gnuplot' to create the animation

Instructions for using the software:

1. You can vary parameters such as the size of the box and the number of particle/ walks inside of main.cpp
2. You can change the step size inside of randomWalk.cpp by changing dr

## Development Environment 

To recreate the development environment, you need the following software and/or libraries with the specified versions:

* gnu compiler
* any code editing software (VIM, notepad++, VSCode, etc.)
* GNUplot
* standard C++ libraries

## Useful Websites to Learn More

I found these websites useful in developing this software:

* [C++ Documentation](https://cplusplus.com/doc/)
* [Chat GPT](https://chatgpt.com/)   //Useful for specific debugging
* [King James Bible](https://www.kingjamesbibleonline.org/)  //very helpful for further debugging

## Future Work

The following items I plan to fix, improve, and/or add to this project in the future:

* [ ] Optimize code to run faster (currently at 3 mins, down from 6.5 mins)
* [ ] Clean up code to make more readable
* [ ] Further debugging to make sure code output is exactly correct