# Molecular Modelling
by Megan Tran

## Table of Contents
* [Purpose of Program](#Purpose-of-program)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Using the Program](#Using-the-Program)
* [Credits](#Credits)
  
## Purpose of Program
* Practice molecular modelling of particles under specific conditions.
* Understand the application of the Maxwell- Boltzmann Distribution Equation in molecular modelling.
  
## Screenshots

Final Molecular Modelling Plot:

![image](https://github.com/Sonicdaheghod/Molecular_Model_MT/assets/68253811/d60d57ac-7255-4f62-8fee-9d26f06f4ce2)

## Technologies
Languages/ Technologies used:

* Jupyter Notebook
* Python3
  
## Setup

Install the following packages:

```
pip install matplotlib
pip install numpy
```

Import the following packages and libraries:

```
import numpy as np
from matplotlib import pyplot as plt
import math
```

## Using the Program

1) A class is initialized to define properties of theoretical particles that will be modelled in this program, including their size and the temperature with the __init__ function

2) Functions also initialized for the particles' position, velocity, and for plotting them.
3) Print out each molecules' position and velocity as an array using these lines of code respectively.
   ```
   print(mol_dynamics.positions)#prints positions for all 55 particles
   print(mol_dynamics.velocities)#prints velocities for all 55 particles
  
   ```
4) Plot a molecular dynamics simulation. See the screeenshot under "Screenshots".


## Credits

* Source code from [room333](https://www.youtube.com/watch?v=Aez8zNqRKHM&list=PLXCw5VdOQb7iMIWV1HHfy-fzKIWtp78eX&index=2&ab_channel=room333)
