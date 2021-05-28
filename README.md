# Publication
_In preparation_

This software accompanies the publication

**Coupled antigen and BLIMP1 asymmetric division with a large segregation between daughter cells recapitulates the temporal transition from memory B cells to plasma cells and transzone migration in the germinal center.**

Elena Merino Tejero, Danial Lashgari, Rodrigo García-Valiente, Jiaojiao He, Philippe A. Robert,  Michael Meyer-Hermann, Jeroen E.J. Guikema, Huub Hoefsloot, Antoine H.C. van Kampen

# Project
## AsymmetricDivision

This repository includes code ONLY of the multiscale model of plasma cell diferentiation in Germinal Centers. The Agent-based
model is based on Mafalda, which is based on [Hyphasma](https://www.helmholtz-hzi.de/en/research/research-topics/immune-response/systems-immunology/our-research/) (e.g., Michael-Meyer Hermann, 2012).  
The GRN is based on Martinez et al., 2012. It is posible to simulate 2 scenarios: Plasma cell diferentiation based on 
Ag inheritance or on BLIMP1 level.

CD40 signal can is dependent on affinity (=affinity*50). 
Different polarity levels fo reach TF can be defined through bcinflow09.par by modifying the following parameters:
 .  BLIMP1 polarity for B cell dividing Ag Asymmetrically [0-1]
 .  IRF4 polarity for B cell dividing Ag Asymmetrically [0-1]
 .  BCL6 polarity for B cell dividing Ag Asymmetrically [0-1]


In the main code Simulations 3 to 6 (Coupled asymmetric division) can be simulated.  Two additional branches where created for the remaininng simulations:
 . Uncoupled asymmetric division (Simulations 7 to 9)
 . Symmetric Ag (a/symmetric TF) division (Simulations 1 and 2)

## Software
All software is written in C++

## References
* Martínez, M. R., Corradin, A., Klein, U., Álvarez, M. J., Toffolo, G. M., di Camillo, B., … Stolovitzky, G. A. (2012). Quantitative modeling of the terminal differentiation of B-cells and mechanisms of lymphomagenesis. Proceedings of the National Academy of Sciences, 109(7), 2672–2677. 
* Meyer-Hermann, M., Mohr, E., Pelletier, N., Zhang, Y., Victora, G. D., & Toellner, K. M. (2012). A theory of germinal center b cell selection, division, and exit. Cell Reports, 2(1), 162–174. 

