# Contributor
Michael METRE 

Trung Hieu TRAN 

Adel KERKABOU

Thi Phuong Lien UNG 
# Introduction
#### Scopes: Optical design of the illumination module with motorized +10 / -20 dioptre ametropia compensation range.

a. Illumination system design:

•	Providing an illumination light with ametropia compensation in order to focus the SLED on the retina (forward direction).

•	Ensuring to test the illumination module functions independently of others module (Beam splitter module, scanning module and detection module). 

b. Optical path innovation:

•	Integrating a Badal system to generate optical delays caused by axial displacement, modeling different refractive errors in the eye. This Badal system provides a round-trip optical path with sequential light reflections off mirrors to double the optical path length.

•	Enabling precise adjustment to align the retinal plane with its emmetropic position.

c. Extended measurement range:

•	Expanding diopter measurement rang to +10/-20 diopters form the current ±4 diopter limit in version 1
    
d. Additional biometer functionality :

•	Adding mobile lens in the illumination module to focus the light to the cornea to have the interior segment signal

# State of the art
1.	Paraxial (symbolic) calculations with Python / Sympy with Badal system -> done (see [Optical calculation by Ray Transfer Matrix (RTM)](#table-of-content) )

2.  Verification of the symbolic expressions in Zemax as well as the tilt and positional tolerances of the mirrors -> done (see [Zemax simulation](#table-of-content))

3.  Designing the alignment procedure -> done (see [Alignement protocol](#table-of-content))

4.	Optical diagram in Fusion sketch -> done (see [Fusion360 sketch](#table-of-content))


Feature |Current instrument (v1)|Premyom instrument (v1.5/v2) ~Summer 2026|Progress |
--- | :-------- |:--------| :-------- 
Ametropia range| -+ 4 dioptre|+10 $/$-20 dioptre| . |
Compensation technology| Mobile [collimator + first lens] within 2-lens telescope| Badal system (mobile mirrors within a fixed telescope)| Calculations + Zemax simulations. Optomechanical design in progress.|
Mobile lens for biometer|Yes|Yes|Being implemented for POC on v1. Optical simulations and optomechanical design done. Manufacturing in progress.
Total length| ~200mm|~200mm|.|

Tab1: Comparison of features and development progress

# Problem statement 

# Table of content
[Optical calculation by Ray Transfer Matrix (RTM)](Optical_Calculation.md)

[Zemax simulation](Zemax_simulation.md)

[Alignement protocol](alignement_protocol.md)

[Fusion360 sketch](Fusion_sketch.md)

# Conclusion 

