This article shows typical visualisation tasks I did during my Postdoc and explains use of Kinetic Monte Carlo method (KMC) to simulate system of nucleating and dissolving nanoparticles.
KMC method was written in C++ code that uses LAMMPS (popular molecular dynamics software) as external library. My KMC code is doing all Monte-Carlo calculations and LAMMPS is called in between KMC steps for energy minimisation.
