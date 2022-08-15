# ActivationFreeEnergy
Tutorial accompanying the paper: Dietschreit, J. C. B. et al., J. Chem. Phys, 2022, "From Free-Energy Profiles to Activation Free Energies"

The Jupyter notebook shows how the example presented in Section V.C was analyzed. It shows:
- how to compute the CV value, CV gradient, and inverse CV mass from the simulation trajectory
- how to recover the unbiased Boltzmann weights of all frames from an eABF simulation via MBAR
- how to compute the CV-conditioned ensemble averages, e.g., to get the orthogonality criterion D_s(z)


## Necessary Python3 packages
- numpy 1.21.2
- matplotlib 3.4.3
- pytorch 1.9.1
- seaborn 0.11.2
- pandas 1.3.3
- mdtraj 1.9.7
- ase 3.22.1
