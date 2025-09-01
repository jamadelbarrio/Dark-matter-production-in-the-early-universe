# Dark-matter-production-in-the-early-universe

This repository contains all the code used for the computations and plots of my master's thesis. Some `.txt` files are also included, as they provide input data required by the code.  

## Contents

- **Temperature.ipynb**: Plots the entropic degrees of freedom as a function of temperature, as well as the neutrino temperature compared with the rest of the Standard Model (SM) plasma.  
- **Freeze-In.ipynb** and **Freeze-Out.ipynb**: Compute specific examples of the Boltzmann equation and plot the results along with the equilibrium values.  
- **Yield_electrons.ipynb** and **Yield_neutrinos.ipynb**: Compute the yield produced by electrons or neutrinos as a function of x = m/T, for different values of the dark matter (DM) mass.  
- **Y_e(g_e).ipynb** and **Y_nu(g_nu).ipynb**: Compute the required coupling strength needed to produce the observed DM abundance for each lepton interaction, across different DM masses. Results are saved as `.txt` files. These can be visualized using **g_Nu_computation(m).ipynb** and **g_C_computation(m).ipynb**.  
- **Electrons+Neutrinos.ipynb**: Computes the total yield by combining contributions from charged leptons and neutrinos.  

## Requirements

- Python 3.x  
- [Jupyter Notebook](https://jupyter.org/)  
- Standard scientific libraries: `numpy`, `scipy`, `matplotlib`  

## How to Run

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/Dark-matter-production-in-the-early-universe.git
   cd Dark-matter-production-in-the-early-universe
   ```

2. Start Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```

3. In the Jupyter interface, open the desired notebook (e.g., `Freeze-In.ipynb`) and run the cells interactively.  

Alternatively, to execute a notebook from the command line without opening the interface:  
   ```bash
   jupyter nbconvert --to notebook --execute Freeze-In.ipynb
   ```

4. Some notebooks require `.txt` data files provided in this repository. Ensure they are in the same directory as the notebooks.  

## Citation

If you use this code or results in your research, please cite this repository or the corresponding master's thesis.  

---
