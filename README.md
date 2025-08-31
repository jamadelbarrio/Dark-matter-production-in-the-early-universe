# Dark-matter-production-in-the-early-universe

This repository contains all the code used for the computations and plots of my master's thesis. Some `.txt` files are also included, as they provide input data required by the code.  

## Contents

- **Temperature**: Plots the entropic degrees of freedom as a function of temperature, as well as the neutrino temperature compared with the rest of the Standard Model (SM) plasma.  
- **Freeze-In** and **Freeze-Out**: Compute specific examples of the Boltzmann equation and plot the results along with the equilibrium values.  
- **Yield_electrons** and **Yield_neutrinos**: Compute the yield produced by electrons or neutrinos as a function of x = m/T, for different values of the dark matter (DM) mass.  
- **Y_e(g_e)** and **Y_nu(g_nu)**: Compute the required coupling strength needed to produce the observed DM abundance for each lepton interaction, across different DM masses. Results are saved as `.txt` files. These can be visualized using **g_Nu_computation(m)** and **g_C_computation(m)**.  
- **Electrons+Neutrinos**: Computes the total yield by combining contributions from charged leptons and neutrinos.  

## Requirements

- Python 3.x  
- Standard scientific libraries: `numpy`, `scipy`, `matplotlib`  

## How to Run

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/Dark-matter-production-in-the-early-universe.git
   cd Dark-matter-production-in-the-early-universe
   ```

2. Run the desired script, for example:  
   ```bash
   python Freeze-In.py
   ```

3. Some scripts require `.txt` data files provided in this repository. Ensure they are in the same directory as the code.  

## Citation

If you use this code or results in your research, please cite this repository or the corresponding master's thesis.  

---
