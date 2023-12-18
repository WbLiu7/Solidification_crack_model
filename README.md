# Solidification_crack_model
A software for solidification cracking assessment.
This software is based on our recently proposed solidification cracking model that considers solid bridge fracture:
Liu, Wenbin, et al. "Modeling solidification cracking: A new perspective on solid bridge fracture", submitted.


# Installation
This software was built on the Matlab 2019, and its running needs the support from Matlab Runtime.

The corresponding Runtime could be automatically downloaded during the installation, or you can manually install Runtime (9.6) from "https://ww2.mathworks.cn/products/compiler/matlab-runtime.html".


# Functions
This software can be used to calculate three behaviors of binary alloys during solidification, including
(1) Solidification curve;
(2) Competition between stress accumulation and solid bridge strength growth at the root of dendrites;
(3) Crack susceptibility.

These calculations are based on the given material parameters and thermal conditions.


# Parameters definition
C0: the given solute concentration
Max C0: the upper limit of C0 in the calculation of (3)
alpha: the dimensionless back-diffusion parameter
Tm: the melting tempearture of pure metals
TE: the eutetic temperature
CSM: the maximum solid solubility
CE: the eutectic composition
fs(coh): the solid fraction at the coherency point
fs(brid): the solid fraction at the solid-bridging point
sigma_0: the bridge strength at fs=1
G: temperature gradient
V: solidification velocity
d: grain size
d_ave: average grain size
phi: the parameter pertaining to the median of grain size distribution

Besides the parameters listed above, the rest of material parameters that are not frequently adjusted needs to be loaded from a file. we offer an example of Al-Cu alloys. 
