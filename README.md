# Rietveld Refinement and Phase Analysis of Polycrystalline Samples

**Author:** Daksh Garg (Entry No: 2023MMB1410)

## Project Overview
This project focuses on the phase identification and phase fraction determination of polycrystalline samples using X-Ray Diffraction (XRD) data. The structural analysis was performed using the Rietveld refinement technique to fit theoretical models to experimental powder diffraction patterns.

## Software & Tools Used
*   **FullProf Suite:** For executing the Rietveld refinement process.
*   **WinPlotr:** For graphic visualization of powder diffraction patterns and background generation.
*   **EdPCR:** For editing and managing `.pcr` input files during iterative refinement cycles.
*   **OriginPro:** For initial XRD data restructuring and `.dat` file generation.

## Methodology
*   **Data Preparation:** Extracted 2-theta and intensity values from `.xrdml` files using OriginPro.
*   **Background Modeling:** Generated `.bgr` files through linear interpolation of background points in WinPlotr.
*   **Iterative Refinement:** Systematically activated and refined parameters including scale factors, zero-point shifts, lattice constants, and peak shape variables (Pseudo-Voigt).
*   **Validation:** Monitored refinement quality by evaluating the Chi-square reduction and minimizing the residual misfit between observed and calculated intensities.

## Results
*   Successfully refined the crystal structure of BCC Alpha-iron samples (HILT and SURFACE datasets).
*   Achieved optimal convergence with Chi-square values of 4.15 and 5.80 respectively, confirming accurate phase fraction determinations.
