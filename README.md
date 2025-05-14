# md-lammps-metallicglass
This repository contains a complete Molecular Dynamics (MD) simulation of the Zr₄₇Cu₄₆Al₇ metallic glass system using LAMMPS. The project includes simulation scripts, atomic configuration outputs, and a detailed report analyzing structural and thermal behavior through RDF, Voronoi tessellation, and atomic radius estimation. All results were post-processed and visualized using OVITO.

## Overview

This project simulates and investigates the thermal and structural evolution of the Zr₄₇Cu₄₆Al₇ metallic glass using Molecular Dynamics in LAMMPS. By replicating a realistic thermal cycle—including heating to 2100 K, equilibration, and controlled cooling to 300 K—the simulation provides insights into the atomic behavior of this ternary metallic glass. A combination of advanced post-processing techniques is employed to analyze short- and medium-range order (via RDF), local atomic environments (via Voronoi tessellation), and effective atomic radii (via surface mesh volume estimation). All analyses and visualizations were conducted using OVITO.
This repository is ideal for researchers and students exploring glassy metals, MD simulations, or post-processing workflows in computational materials science.

## Repository Structure

    lammps-script/          → LAMMPS input script and EAM potential file for ZrCuAl simulation  
    lammps-dumps/           → Output dump files from heating, cooling, and equilibration phases  
    DOCUMENT.pdf            → Full simulation report with methodology, analysis, and figures 

Each folder contains the necessary files to run, analyze, and interpret the molecular dynamics simulation of Zr₄₇Cu₄₆Al₇ metallic glass using LAMMPS and post-processing tools.

## Simulation Features

    Initial Configuration: Random distribution of atoms based on atomic percentages (Zr: 47%, Cu: 46%, Al: 7%)

    Energy Minimization: Conjugate gradient method

    Thermal Processing:

        Heating from 300 K to 2100 K

        Equilibration at 2100 K

        Cooling from 2100 K to 300 K

        Final equilibration at 300 K

    Post-Simulation Analyses:

        Radial Distribution Function (RDF): Examines short- and medium-range order

        Voronoi Tessellation: Identifies icosahedral clusters and local atomic structures

        Atomic Radius Estimation: Based on surface mesh analysis using OVITO

## Documentation

The accompanying report DOCUMENT.pdf provides a detailed explanation of the simulation methodology, including:

    Simulation box setup

    LAMMPS input parameters

    Post-processing analysis techniques

    Discussion of results with supporting visuals:

        RDF plots

        Voronoi structures

        Atomic radius estimates

## Author

This project was developed and implemented by Roozbeh Aghabarari during Spring 2024.

## Acknowledgements

Special thanks to Dr. Rouhollah Tavakoli for his guidance and support throughout this project.

## Contact

For any questions, suggestions, or collaboration opportunities:

    Email: ro.aghabarari@gmail.com

    Website: www.roozbehaghabarari.com

## License

This repository is intended for academic and educational purposes. If you reference or build upon this work in your own projects, please ensure proper attribution to the author.