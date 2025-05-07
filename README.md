**Optical Diffraction Tomography with Gradient Data Support** 

GRAD-EWALD is a fork of EWALD [https://github.com/biopto/EWALD], an open-source software for Optical Diffraction Tomography (ODT) reconstruction. This version introduces support for gradient-based data (shearing holography/DIC), enabling tomographic reconstruction of the refractive index derivative in the shearing direction.
The theoretical foundation of Gradient Optical Diffraction Tomography (GODT) are provided in *J. Winnik, P. Zdankowski, M. Stefaniuk, A. Ahmad, C. Zuo, B. S. Ahluwalia, M. Trusiak "Gradient Optical Diffraction Tomography," arXiv preprint arXiv:2411.08423 (2024)* [https://arxiv.org/abs/2411.08423].

GRAD-EWALD has been tested with **transmission**, **single wavelengths**, **"limited angle" configuration** (angular scanning of the laser beam with stationary sample and camera) and **direct inversion (DI)** solver.
 

### Installation

1. Download the repository
2. Download an example measurement dataset: [Sinogram_GODT.mat](https://zenodo.org/records/15356313).
3. Run the GODT.m file in Matlab


### Licensing

The code is shared under GPLv3 license. If you use this code, please cite one of the following papers, depending on your application:

- if you use DI or GP reconstruction methods in transmission, please cite:

[1] W. Krauze, P. Makowski, M. Kujawińska, and A. Kuś, “Generalized total variation iterative constraint strategy in limited angle optical diffraction tomography,” Opt. Express 24(5), 4924–4936 (2016).

- if you use GPSC in transmission, please cite:

[2] W. Krauze "Optical diffraction tomography with finite object support for the minimization of missing cone artifacts," Biomed. Opt. Express 11(4), 1919-1926 (2020).

- if you use multiwavelength modality, please cite:

[3] P. Ossowski et al. "Near-infrared, wavelength, and illumination scanning holographic tomography," Biomed. Opt. Express 13(11), 5971-5988 (2022).

- if you use the reflection mode, please cite:

[4] W. Krauze, P. Ossowski, M. Nowakowski, M. Szkulmowski, M. Kujawińska "Enhanced QPI functionality by combining OCT and ODT methods," Proc. SPIE 11653, 19-24 (2021).

- for gradient-based measurements using this fork of the code, please cite:

[5] J. Winnik, P. Zdankowski, M. Stefaniuk, A. Ahmad, C. Zuo, B. S. Ahluwalia, M. Trusiak "Gradient Optical Diffraction Tomography," arXiv preprint arXiv:2411.08423 (2024).


**GRAD-EWALD is a fork of the EWALD-repository [https://github.com/biopto/EWALD], originally developed by:**

**Main contributors:**
- Piotr L. Makowski (2014-2018)
- Paweł Ossowski (2020-2022)
- Wojciech Krauze (2016-now)

**Other contributors:** 
- Michał Ziemczonok 
- Piotr Stępień

**Gradient support was added by**
- Juliana Winnik

