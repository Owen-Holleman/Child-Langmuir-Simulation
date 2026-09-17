# Child-Langmuir-Simulation
Uses Euler's method, Poisson's equation, bisection method, and more to determine the maximum current in a diode

# Context
As onboarding for Dr. Peng Zhang's Plasma, Beams, and Interface Science Group, at the University of Michigan, Yves Heri, my grad student advisor tasked me with using python to determine the maximum current in a diode and how it changes with the voltage at the anode as well as the distance between the plates. What is eventually numerically derived is the Child-Langmuir law which related the maximum current density to V0^(3/2) [where V0 is the voltage at anode] and d^(-2) [where d is the distance between plates.]

# Installation
1. Download Anaconda
Go to the Anaconda Distribution download page.
Select your operating system (Windows / macOS / Linux).
Download the Python 3.x installer (choose the 64-bit version unless you have a specific reason not to).

2. Install Anaconda for Windows
Run the downloaded .exe file.
Click through the setup wizard, accepting the license agreement.
When prompted, choose "Just Me" (recommended) for the install type.
Leave the default install location unless you need to change it.
On the Advanced Installation Options screen, you can leave "Add Anaconda to my PATH environment variable" unchecked (Anaconda recommends this) — you'll instead use the Anaconda Prompt to run commands.
Click Install and wait for the process to finish.

3. Verify the Installation

Open a terminal (or Anaconda Prompt on Windows) and run:

bash
conda --version

You should see output like conda 24.x.x. If the command isn't recognized, restart your terminal or double-check that Anaconda was added to your PATH during installation.

4. Launch Jupyter Notebook

Jupyter Notebook comes pre-installed with Anaconda. To launch it:

bash
jupyter notebook

This will:

Start a local Jupyter server
Automatically open a new tab in your default web browser at http://localhost:8888

From there, you can navigate to a project folder and create a new notebook via New → Python 3 (ipykernel).

# Usage
There are two sweeps for V0 and d in there. For other examples you could try changing the values of the sweep and the constants that go along with those sweeps.

# Contribution
As previously mentioned, this was done as an onboarding task given to me by Yves Heri. He created the general outline of what to do while I, Owen Holleman, implemented the code itself. 
