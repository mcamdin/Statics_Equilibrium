# Support Reaction Solver for Simply Supported Beams

## Overview
This project uses Python to solve support reactions for a simply supported beam. The code takes user inputs for beam length, support locations, and applied loads. It then uses static equilibrium equations to solve for the support reactions.

## Objective
- Solve for support reactions using Python
- Use equilibrium equations from statics
- Check if the beam satisfies equilibrium
- Practice writing simple engineering code in Jupyter Notebook

## What the Code Does
- Asks the user for the beam length
- Asks for the locations of Support A and Support B
- Allows the user to enter multiple loads
- Stores the load information in a pandas DataFrame
- Calculates:
  - Reaction Ax
  - Reaction Ay
  - Reaction By
- Checks equilibrium using:
  - Sum of forces in the x-direction
  - Sum of forces in the y-direction
  - Sum of moments

## Key Concepts Used
- Static equilibrium
- Support reactions
- Moments about a point
- Force balance
- Simply supported beams

## Packages Used
- pandas

## How to Run
1. Open `Statics_Project.ipynb` in Jupyter Notebook.
2. Run each cell from top to bottom.
3. Enter the beam length, support locations, and load values when asked.
4. View the calculated support reactions.
5. Check the equilibrium results printed by the code.

## Files Included
- `Statics_Project.ipynb` - main Jupyter Notebook file
- `README.md` - project description

## Example Problem
The notebook also includes an example beam problem with two downward point loads. This example shows how the code calculates the reactions and checks that the beam is in equilibrium.

## Notes
This project focuses on basic 2D statics. The loads are entered in pounds, and the beam dimensions are entered in feet. The code assumes a simply supported beam with Support A and Support B.
