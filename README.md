# Uncertainty Principle Simulation Coding Project
In this project I will be making a coded simulation of a physical lab experiment that I had done in another class. In this class I was confirming the uncertainty princple using lenses and lasers. With this being said, this coded simulation will use fft to try and simulate the lab results. With a Delta x value, one will be able to simulate a Delta Px value and then confirm the uncertainty principle. The code will do all of this. 

# Important Sections
There are only three main parts of this repository: README.md, FinalProject.ipynb,LICENSE, and uncertaintysetup.png. The readme give a dense text outline for this project. The finalproject gives a more broad explanation and the code for the simulation along with the external libraries download. The License section highlights the lisencing part. The uncertaintysetup is a picture of my physical lab setup. There are also the two graph outputs. Output1.png being violet and Output2.png being red.

## Code Setup and Precursor
I will be putting a bit of code at a time to keep it more organized. At the end of each peice of code I will explain the point of the code and then a the very end I will have the whole code. This code will be able to simulate the experiment that I had done in class. A person with the code should be able to create new sources. Said person should also then be able to change $\Delta x$. 

## Methods Used
In this code I use the Fast Fourier Transform to simulate the diffraction pattern.
I calculate the intensity profile and measure the width at 13.5% level apposed a 50% ful wave half max value to determine the uncertainty product. This will allow for a more accurate measurement.

# Expected Outputs
From this code there are a couple of different outputs. For each source in the file, there will be one output with the laser type, momentum spread, uncertainty product (This is what we are finding), the uncertainty limit and whether the limit was satisfied. There are also two graph outputs expected. As mentioned these are the graph output.png's in this repository. They will paste below the code however.

## Downloading External Libraries
To ensure that all of the librares are download I included a code that could be ran to download them all in Project.ipynb 
The libraries that are required include: NumPy (For the array changes and the FFT), Matplotlib (For the display) and SciPy (For the constant and verification)

## To Run The Code
In order to run the code, just copy down the code. If you copy down the code in Project.ipynb, make sure to also run the libraries download in your repository. The important files in the repository are the README.md and Project.ipynb which holds the information about the code and then the fully functioning code at the end.