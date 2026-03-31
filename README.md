# Blue Straggler Formation from Binary Evolution

This project explores the formation and observational signatures of **blue straggler stars** using numerical simulations of stellar and binary evolution.

The simulations are based on the **Binary Star Evolution (BSE)** code and are used to study how blue stragglers form, evolve, and appear in stellar populations.

---

## Overview

Blue stragglers are stars that appear **hotter and more luminous than the main-sequence turnoff**, suggesting they are younger than the rest of the population. One leading formation channel is **binary evolution**, where mass transfer or mergers rejuvenate a star.

This project investigates:

- When blue stragglers form and how long they live  
- How their lifetime depends on binary parameters  
- How many are expected in a stellar population  
- How they appear observationally in an HR diagram  

---

## Project Structure

The project consists of several scripts/notebooks:

### 1. Blue Straggler Formation Times
Computes when a blue straggler forms and disappears in a binary system as a function of initial separation.

### 2. Blue Straggler Lifetime vs Separation
Calculates how the **lifetime of blue stragglers** depends on:
- initial semi-major axis  
- donor star mass  

### 3. Population Synthesis
Simulates a population of binaries and computes:
- the number of blue stragglers at a given time  
- their mass relative to the turnoff mass  

### 4. HR Diagram with Blue Stragglers
Generates a synthetic stellar population and overlays blue stragglers to show how they can be identified observationally:
- blue stragglers appear beyond the main-sequence turnoff  
- luminosity vs effective temperature (HR diagram)  

---

## Methods

- Binary evolution simulations using external **BSE code**
- Numerical interpolation for turnoff mass estimation
- Monte Carlo sampling of stellar populations:
 - Initial mass function (IMF)
 - Mass ratio distribution
 - Period distribution
- Classification of stellar evolutionary stages
- Data analysis and visualization using Python

---

## Technologies

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook (optional)

---

## Requirements

This project depends on the **Binary Star Evolution (BSE)** code.

The scripts call the executable via:

./bse

### Important:
- The BSE executable is **not included** in this repository  
- You must install and compile BSE separately  

---

## Notes on Robustness

Some simulations may fail for extreme parameters.  
These cases are handled in the code to avoid crashes.

---

## Example Output

The project produces:

- Time intervals of blue straggler formation  
- Lifetime vs separation plots  
- Population frequency (number of BS formed after time t)  
- HR diagrams showing blue stragglers beyond the turnoff  

---

## Motivation

This project combines:
- physics-based modeling  
- numerical simulation  
- data analysis  
- visualization  

It demonstrates how computational methods can be used to connect **theory and observation** in astrophysics.

---

## Author

Emilie Desrochers Karlsson  

---.
