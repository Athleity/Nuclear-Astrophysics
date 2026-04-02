# Nuclear Astrophysics: 45Sc(a,n)48V S-Factor Analysis 
 
[![IAPT NSSP-2025](https://img.shields.io/badge/IAPT-NSSP--2025-blue)](https://github.com/Athleity/Nuclear-Astrophysics-45Sc-S-Factor) 
 
## ?? Overview 
 
This repository contains computational analysis of the astrophysical S-factor and thermonuclear reaction rate for the **45Sc(a,n)49V** reaction. 
 
## ?? Key Physics 
 
The astrophysical S-factor removes the strong energy dependence of the cross-section caused by the Coulomb barrier: 
 
$$S(E) = E \cdot \sigma(E) \cdot e{2\pi\eta}$$ 
 
where $\eta = \frac{Z_1 Z_2 e2}{\hbar v}$ is the Sommerfeld parameter. 
## ?? Repository Structure 
 
``` 
Nuclear-Astrophysics-45Sc-S-Factor/ 
ÃÄÄ data/                           # Experimental and calculated data 
³   ÃÄÄ reaction_rates_45Sc.xlsx    # Cross-sections, S-factors, reaction rates 
³   ÀÄÄ numerical_integration_results.xlsx  # Trapezoidal & Gauss-Legendre results 
ÃÄÄ manuscript/                     # Research papers and presentations 
³   ÃÄÄ manuscript.pdf              # Conference paper (IAPT NSSP-2025) 
³   ÃÄÄ presentation.pdf            # Symposium presentation slides 
³   ÀÄÄ certificate.pdf             # Participation certificate 
ÃÄÄ notebooks/                      # 19 Jupyter notebooks for analysis 
ÃÄÄ graphs/                         # Generated plots (5 categories) 
ÃÄÄ README.md                       # This file 
ÀÄÄ requirements.txt                # Python dependencies 
``` 
## ?? Data Description 
 
### reaction_rates_45Sc.xlsx 
- Experimental cross-sections (mb) vs. lab energy (MeV) 
- Calculated Sommerfeld parameter (?) 
- S-factor values (MeVúbarn) 
- Reaction rates ?sv? for T9 = 0.001 - 11 GK 
 
### numerical_integration_results.xlsx 
- Trapezoidal rule integration (50, 64, 96 points) 
- Gauss-Legendre quadrature (50, 64, 96 points) 
- Maxwell-Boltzmann weighted integrals 
## ??? Requirements 
 
```bash 
pip install numpy scipy matplotlib pandas openpyxl jupyter 
``` 
 
## ?? Key Results 
 
- S-factor shows smooth energy dependence suitable for extrapolation to stellar energies 
- Reaction rates increase exponentially in Gamow window (T9 = 0.1-1 GK) 
- Numerical integration methods (Trapezoidal & Gauss-Legendre) show excellent agreement 
- Error propagation implemented using ?S/S = ?s/s 
## ????? Author 
 
**Priyansh Bhavsar**  
B.S. Physics, Indian Institute of Technology Jodhpur  
 
## ?? Supervisor 
 
**Dr. N. J. Upadhyay**  
Assistant Professor (III), Amity University Maharashtra 
 
## ?? Presentation 
 
This work was presented at the **12th IAPT National Students' Symposium on Physics (NSSP-2025)**  
Department of Physics, Panjab University, Chandigarh (October 10-12, 2025) 
## ?? Citation 
 
```bibtex 
@inproceedings{bhavsar2025astrophysical, 
  title={A Computational Analysis of Experimental Nuclear Reaction Data}, 
  author={Bhavsar, Priyansh and Upadhyay, N.J.}, 
  booktitle={12th IAPT National Students' Symposium on Physics (NSSP-2025)}, 
  year={2025}, 
  organization={Panjab University, Chandigarh} 
} 
``` 
 
--- 
 
