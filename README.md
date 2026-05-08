# Uncertainty Principle Simulation Coding Project

In this project, I will be creating a runable simulation for the Heisenburg UNcertainty Princple. This principle states that both positon and momentum cannot be measured with extreme position at the same time. This inherently states that the more precision the postion is taken with, the less precise the momentunm measurement will be. This has nothing to do with our current technological capabilities, it is a property of a wave-like system. This relationship is represented by the relationship, $$\Delta x \Delta p \ge \frac{\hbar}{2}$$

This coding project goes hand and hand with the other project that I am currently working on in Quantum and Advanced Physics Project Lab. I have created a simulation to go along with the physical research that I had done so that I could compare the answers that I get from both. 

The physical project investigates the spatial-momentum uncertainty relation by utilizing focused optical beams as a macroscopic model for quantum wave packets. By employing three distinct light sources: a 405nm violet laser, a 650nm red laser, and a 625nm LED, the study seeks to verify if the Equation 1 limit holds across varying levels of spatial coherence. The experimental objective is to measure the minimum beam waist (position uncertainty) and the resulting farfield divergence (momentum uncertainty) to map the physical boundaries of the Heisenberg inequality and determine how source coherence influences the proximity to the quantum floor.

## Theory 
The uncertainty principle establishes a fundamental "floor" for measurement precision. In optics, a lens that creates a narrower convergence (decreasing ∆x) will increase the momentum uncertainty ∆Px. This relationship is defined by equation 1 Where ℏ ≈ 1.054 × 10−34 J·s.
To calculate momentum uncertainty from observed angular divergence, we utilize the de Broglie relation. Since P = h/λ, any spread in the angle of travel ∆θ results in a spread in the transverse momentum component Px. For small angles, this is expressed as: $$\Delta p_x \approx \frac{h}{\lambda} \sin(\theta)$$

## Experiment Setup
The experiment utilized three distinct sources: a 405nm Violet Laser (Source 1), a 650nm Red Laser (Source 2), and a 625nm Red LED (Source 3). Each source was measured using a digital beam profiling camera mounted on a table to capture the beam’s evolution through space. In the simulation, source three will not be included. This is because source three is an LED and acts in different ways than the lasers. The LED light is much more broad and for this reason I am not sure if I will have issues in coding this. This source of coarse still oblidges to the prinipal, but onces again is very different from the other sources. In the physical set up, a laser shines through a lens. The resulted converging light beam is than measure at the point where the beam waist is at its smallest radius. Thereon, more power measreuments are taken as the beam increases in size and two more measurements are taken at these distances.

## Code Setup and Precursor
I will be putting a bit of code at a time to keep it more organized. At the end of each peice of code I will explain the point of the code and then a the very end I will have the whole code. This code will be able to simulate the experiment that I had done in class. A person with the code should be able to change the wavelength of the source, which will act like a laser not an LED or anything else, touched on above. Said person should also then be able to change $\Delta x$.

## Methods Used
In this code I use the Fast Fourier Transform to simulate the diffraction pattern.

I calculate the intensity profile and measure the width at 13.5% level to dittermine the uncertainty product.

## Downloading External Libraries
To ensure that all of the librares are download I included a code that could be ran to download them all in Project.ipynb 
The libraries that are required include: NumPy (For the array changes and the FFT), Matplotlib (For the display) and SciPy (For the constant and verification)

## To Run The Code
In order to run the code all you need to do is either clone the repository or just copy down the code. If you just copy down the code in Project.ipynb, make sure to also run the libraries download in your repository. The important files in the repository are the README.md and Project.ipynb which holds the information about the code and then the fully functioning code at the end.