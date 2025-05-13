---
title: Codes
layout: page
permalink: "/codes"
---

#### GNNOpt
<img src="{{site.baseurl}}/assets/images/GNNOpt.jpg" alt="QERaman" style="height: 200px"/>

An ensemble-embedding graph neural network for direct prediction of optical spectra from crystal structures.

>***Input***: Crystal structure data (e.g. cif file)  
>
>***Output***: Complex dielectric function, absorption coefficient, complex refractive index, and reflectance.
>
>***Machine learning***: Equivariant graph neural networks.
>
>***Applications***: Screening photovoltaic and quantum materials.

Published paper: **N. T. Hung**\*, R. Okabe, A. Chotrattanapituk and M. Li\*, [Universal ensemble-embedding graph neural network for direct prediction of optical spectra from crystal structure](https://doi.org/10.1002/adma.202409175), ***Adv. Mat.*** 36, 2409175-1-11 (2024).

<p><a target="_blank" href="https://github.com/nguyen-group/GNNOpt" class="btn btn-success">Source files of the GNNOpt at <i class="fab fa-github"></i></a></p>



#### QERaman
<img src="{{site.baseurl}}/assets/images/QERaman-logo.png" alt="QERaman" style="height: 200px"/>

An open-source program for computing the first-order resonance Raman spectroscopy based on Quantum ESPRESSO.

>***Compatible***: Quantum ESPRESSO

>***Command***: bands_mat.x, ph_mat.x, raman.x

>***Output***: Electron-photon and electron-phonon matrix elements, first-order resonance Raman tensor and spectra as a function of incident laser energy for linearly- or circularly-polarized light.

Published paper: **N. T. Hung**\*, J. Huang, Y. Tatsumi, T. Yang, and R. Saito\*, [QERaman: An open-source program for calculating resonance Raman spectra based on Quantum ESPRESSO](https://doi.org/10.1016/j.cpc.2023.108967), ***Comput. Phys. Commun.*** 295, 108967 (2024).

<p><a target="_blank" href="https://github.com/nguyen-group/QERaman" class="btn btn-success">Source files of the QERaman at <i class="fab fa-github"></i></a></p>

#### QR2-code
<img src="{{site.baseurl}}/assets/images/QR2-code-logo.jpg" alt="QR2-code" style="height: 200px"/>

A DFT-based program for computation and analysis of the resonant Raman spectra.

>***Compatible***: Quantum ESPRESSO, EPW

>***Command***: epw.x (modified), matdyn.x (modified), phonon sort.x, raman pp.x

>***Output***: Single, double and defect-induced double resonant Raman.

>***Website***: http://qr2-code.com

***Note***: QERaman is based on only Quantum ESPRESSO, while QR2-code is based on both Quantum ESPRESSO and EPW. QERaman has fewer parameters and is simpler than QR2-code. Thus, we recommend QERaman for people who focus only on first-order Raman calculation. If you want to calculate the high-order Raman spectra, the QR2-code is recommended.

Published paper: J. Huang\*, R. Liu, Y. Zhang, **N. T. Hung**\*, H. Guo, R. Saito and Teng Yang\*, [QR2-code: An open-source program for double resonant Raman spectra](https://doi.org/xxx), ***arXiv.xxx.xxx*** submitted.

<p><a target="_blank" href="https://github.com/JoeyyHuang/QR2-code" class="btn btn-success">Source files of the QR2-code at <i class="fab fa-github"></i></a></p>