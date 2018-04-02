# Mathematical Equations Solver
Mathematical Equation Solver is a command line application run using python to solve the Mathematical equations present in an image and output the solutions to console.

Ex:
  If an image consists of equations such as:
    6 * 4
    24549 + 8634893
    45/9
    
  the output to console looks like:
    6 * 4 = 24
    24549 + 8234893 = 8659442
    45 / 9 = 5
    

This command line utility named EquationSolver.py when run by using following command:
        python3 EquationSolver.py --image [image_path]
Gives output solutions to all the equations in the image file to console.

## Pre-Requisites:
------------------
   ### Python(version 3):
          - Image , PIL
          - Pytesseract
          - argparse
          - sys
          - os
          - opencv
          - keras
          
The command line utility should be run with the help of following command:
         python3 EquationSolver.py --image [image_path]
        
EquationSolver is the python script file
--image is command line argument to read from an image file
[image path] is the path of the image in which all the Mathematical equations are present.

