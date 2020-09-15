# MRE134

Brain magnetic resonance elastography (MRE) data were collected using the Resoundant actuator system (https://www.resoundant.com/) at a single actuation frequency of 50 Hz.

Maps are reported as the shear stiffness, μ, (kPa) and damping ratio, ξ, defined as:

μ =2|G*|2/(G'+|G*|)

ξ=G"/2G'

with G' representing the storage, G" the loss, and |G*| the magnitude of the complex shear modulus.

Individual shear stiffness and damping ratio images were coregistered to the MNI 2mm template using Advanced Normalization Tools (ANTS).

MRE134_Stiffness3D is a zipped NifTi file that corresponds to the average shear stiffness from 134 young adult participants in MNI space (91 x 109 x 91). Spatial resolution is 2mm x 2mm x 2mm.

MRE134_Damping3D is a zipped NifTi file that corresponds to the average damping ratio (dimensionless) of the brain from 134 young adult participants in MNI space (91 x 109 x 91). Spatial resolution is 2mm x 2mm x 2mm.

Demographic data from each participant is also provided as an excel file (MRE134_Demographics)



For further details see:
Hiscox LV, McGarry MDJ, Schwarb H,et al. Standard-space atlas of the viscoelastic properties of thehuman brain. Hum Brain Mapp. 2020;1–19.https://doi.org/10.1002/hbm.25192
