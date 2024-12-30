# MonteCarlo-Radiation-Dose
Monte Carlo simulation for radiation dose calculation in a water phantom
# Monte Carlo Radiation Dose Simulation

This project is a simulation of radiation dose deposition in a water phantom using Monte Carlo techniques. It aims to model photon interactions such as Compton scattering, photoelectric absorption, Rayleigh scattering, and pair production to compute 3D dose distributions. This project showcases the practical application of Monte Carlo methods in medical physics and radiation therapy.

---

## Key Features

- **Photon Transport Simulation:** Models the transport and interactions of photons in a voxelized water phantom.
- **Physics-Based Interactions:** Simulates Compton scattering, photoelectric absorption, Rayleigh scattering, and pair production.
- **3D Dose Distribution:** Generates a 3D grid representing the dose deposited in each voxel.
- **Visualizations:** Includes graphical plots of dose distribution for analysis.

---

## How It Works

The simulation follows these steps:
1. Photons are generated with a specified energy (e.g., 10 MeV) and randomly placed within the phantom.
2. The transport of each photon is simulated until it loses all energy or exits the phantom.
3. Energy deposition is calculated based on interaction probabilities for the relevant physical processes.
4. The dose is normalized to provide a realistic distribution within the phantom.

---

## Results and Outputs

The simulation outputs include:
- **Normalized 3D dose distribution data.**  
- **Plots** illustrating the dose deposition within the water phantom.



---

## Applications

This simulation can be used for:
- **Medical Physics Training:** Understanding radiation transport and dose deposition.
- **Validation:** Comparing Monte Carlo results with experimental or clinical data.
- **Portfolio Building:** Demonstrating technical and computational expertise.

---

## Future Directions

- Simulate dose deposition in heterogeneous phantoms (e.g., tissue-equivalent materials).  
- Incorporate electron transport for more detailed simulations.  
- Extend visualizations to 3D rendering for advanced analysis.

---


## Acknowledgments

This project is inspired by the principles of radiation therapy and medical physics, utilizing Monte Carlo techniques to provide insights into photon interactions and dose deposition.
