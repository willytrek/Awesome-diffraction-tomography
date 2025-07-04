# Awesome-diffraction-tomography

A curated list of resources on diffraction tomography.

## Disclaimer

This list is compiled during our paper survey about diffraction tomography and is not meant to be exhaustive. The list is organized so that we can easily navigate different topics in diffraction tomography. Thank [Brian Chao](https://github.com/bchao1)'s template.

## Table of Contents

- [Background, Theory, and Survey](#background-theory-and-survey)  
  - [Background and Theory](#background-and-theory)  
  - [Survey Papers](#survey-papers)

- [Optical Diffraction Tomography (ODT)](#optical-diffraction-tomography-odt)

- [Intensity Diffraction Tomography (IDT)](#intensity-diffraction-tomography-idt)  
  - [Historical Development (Pre-2010)](#historical-development-pre-2010)  
  - [Non‑Interferometric Phase Retrieval](#non‑interferometric-phase-retrieval)  
    - [FP-Based Methods](#fp-based-methods)  
    - [TIE and Combined Methods](#tie-and-combined-methods)  
  - [3D Optical Transfer Function (Weak Scattering)](#3d-optical-transfer-function-weak-scattering)  
  - [Multi-Layer Recursive Forward Model (Multiple Scattering)](#multi-layer-recursive-forward-model-multiple-scattering)  
  - [Deep Learning Approaches](#deep-learning-approaches)  
    - [Accurate Forward Physical Imaging Model](#accurate-forward-physical-imaging-model)  
    - [Auto-Diff Accelerated 3D RI Reconstruction](#auto-diff-accelerated-3d-ri-reconstruction)  
    - [Neural Re-parameterization of 3D RI](#neural-re-parameterization-of-3d-ri)  
    - [Direct Optimization with Physics-Based Models](#direct-optimization-with-physics-based-models)  
  - [Combined Modalities and Applications](#combined-modalities-and-applications)

- [Labs and Researchers](#labs-and-researchers)

- [Talks, Lectures, and Tutorials](#talks-lectures-and-tutorials)

## Background, Theory, and Survey
### Background and Theory
- [**Introduction to Fourier Optics**](https://books.google.com.tw/books/about/Introduction_to_Fourier_Optics.html?id=QllRAAAAMAAJ&redir_esc=y) by Joseph W. Goodman is a great book to learn the basics of wave propagation.

- [**Three-Dimensional Structure Determination of Semi-Transparent Objects from Holographic Data**](https://www.sciencedirect.com/science/article/pii/0030401869900522)  
Wolf, E. (1969). *Optics Communications*, 1(4), 153-156.

- [**New Approach to Optical Diffraction Tomography Yielding a Vector Equation of Diffraction Tomography and a Novel Tomographic Microscope**](https://onlinelibrary.wiley.com/doi/full/10.1046/j.0022-2720.2001.00980.x)  
Lauer, V. (2002). *Journal of Microscopy*, 205(2), 165-176.

- [**Tomographic Diffractive Microscopy: Basics, Techniques and Perspectives**](https://www.tandfonline.com/doi/full/10.1080/09500340.2010.493622)  
Haeberlé, O., Belkebir, K., Giovaninni, H., & Sentenac, A. (2010). *Journal of Modern Optics*, 57(9), 686-699.

### Survey Papers
- [**The Theory of Diffraction Tomography**](https://arxiv.org/pdf/1507.00466) | _[CODE](https://github.com/RI-imaging/ODTbrain)_  
Müller, P., Schürmann, M., & Guck, J. (2015). *arXiv preprint arXiv:1507.00466*.

## Optical diffraction tomography (ODT)

This section mainly focuses on the optical diffraction tomography.

#### Others

## Intensity diffraction tomography (IDT)
This section mainly focuses on the intensity diffraction tomography.

### Historical Development (Pre-2010)

- [**Phase-Retrieval and Intensity-Only Reconstruction Algorithms for Optical Diffraction Tomography**](https://opg.optica.org/josaa/fulltext.cfm?uri=josaa-10-5-1086&id=4618)  
Maleki, M. H., & Devaney, A. J. (1993). *Journal of the Optical Society of America A*, 10(5), 1086-1092.

- [**Diffraction Tomography Without Phase Information**](https://opg.optica.org/ol/abstract.cfm?uri=OL-27-21-1890)  
Gbur, G., & Wolf, E. (2002). *Optics Letters*, 27(21), 1890-1892.

- [**Hybrid Diffraction Tomography Without Phase Information**](https://opg.optica.org/josaa/abstract.cfm?uri=JOSAA-19-11-2194)  
Gbur, G., & Wolf, E. (2002). *Journal of the Optical Society of America A*, 19(11), 2194-2202.

- [**Statistically Principled Use of In-Line Measurements in Intensity Diffraction Tomography**](https://opg.optica.org/josaa/fulltext.cfm?uri=josaa-24-3-626&id=127065)  
Huang, Y., & Anastasio, M. A. (2007). *Journal of the Optical Society of America A*, 24(3), 626-642.


### Non‑interferometric Phase Retrieval (Fourier diffraction theory)

#### Fourier Ptychography (FP) -based 

- [**Diffraction Tomography with Fourier Ptychography**](https://opg.optica.org/optica/fulltext.cfm?uri=optica-3-8-827&id=348069)  
Horstmeyer, R., Chung, J., Ou, X., Zheng, G., & Yang, C. (2016). *Optica*, 3(8), 827-835.

- [**Wide-Field High-Resolution 3D Microscopy with Fourier Ptychographic Diffraction Tomography**](https://www.sciencedirect.com/science/article/pii/S0143816619318421)  
Zuo, C., Sun, J., Li, J., Asundi, A., & Chen, Q. (2020). *Optics and Lasers in Engineering*, 128, 106003.

#### Intensity Transport Equation (ITE)
#### Combined Transport of Intensity Equation (TIE) and Fourier Ptychography (FP)


### 3D Optical Transfer Function (Weak scattering)

- [**High-Throughput Intensity Diffraction Tomography with a Computational Microscope**](https://opg.optica.org/boe/fulltext.cfm?uri=boe-9-5-2130&id=385347) | _[CODE](https://github.com/bu-cisl/High-Throughput-IDT?tab=readme-ov-file)_  
Ling, R., Tahir, W., Lin, H.-Y., Lee, H., & Tian, L. (2018). *Biomedical Optics Express*, 9, 2130-2141.

- [**High-Speed In Vitro Intensity Diffraction Tomography**](https://www.spiedigitallibrary.org/journals/advanced-photonics/volume-1/issue-6/066004/High-speed-in-vitro-intensity-diffraction-tomography/10.1117/1.AP.1.6.066004.full)   | _[CODE](https://github.com/bu-cisl/IDT-using-Annular-Illumination?tab=readme-ov-file)_  
Li, J., Matlock, A., Li, Y., Chen, Q., Zuo, C., & Tian, L. (2019). *Advanced Photonics*, 1(6), 066004-066004.

### Multi‑layer Recursive Forward Propagation Model (Multiple scattering)

- [**High-Resolution 3D Refractive Index Microscopy of Multiple-Scattering Samples from Intensity Images**](https://opg.optica.org/optica/fulltext.cfm?uri=optica-6-9-1211&id=418751#articleFigures) | _[CODE](https://github.com/Waller-Lab/multi-slice?tab=readme-ov-file)_  
Chowdhury, S., Chen, M., Eckert, R., Ren, D., Wu, F., Repina, N., & Waller, L. (2019). *Optica*, 6, 1211-1219.

- [**Multi-Layer Born Multiple-Scattering Model for 3D Phase Microscopy**](http://opg.optica.org/optica/fulltext.cfm?uri=optica-7-5-394&id=431219) | _[CODE](https://github.com/Waller-Lab/multi-layer-born?tab=readme-ov-file)_  
Chen, M., Ren, D., Liu, H.-Y., Chowdhury, S., & Waller, L. (2020). *Optica*, 7, 394-403.

- [**High-Fidelity Intensity Diffraction Tomography with a Non-Paraxial Multiple-Scattering Model**](https://opg.optica.org/oe/fulltext.cfm?uri=oe-30-18-32808&id=495495) | _[CODE](https://github.com/bu-cisl/SSNP-IDT?tab=readme-ov-file)_  
Zhu, J., Wang, H., & Tian, L. (2022). *Optics Express*, 30, 32808-32821.

- [**Multiple-Scattering Simulator-Trained Neural Network for Intensity Diffraction Tomography**](https://opg.optica.org/oe/fulltext.cfm?uri=oe-31-3-4094&id=525403)  | _[CODE](https://github.com/bu-cisl/IDTNet)_  
Matlock, A., Zhu, J., & Tian, L. (2023). *Optics Express*, 31(3), 4094-4107.


### Deep learning
#### Formulation of an accurate forward physical imaging model
#### Auto-Diff Accelerated 3D RI Reconstruction

- [**Refractive Index Tomography with a Physics-Based Optical Neural Network**](https://opg.optica.org/boe/fulltext.cfm?uri=boe-14-11-5886&id=541011)  
Yang, D., Zhang, S., Zheng, C., Zhou, G., Hu, Y., & Hao, Q. (2023). *Biomedical Optics Express*, 14(11), 5886-5903.

- [**Differentiable Imaging Meets Adaptive Neural Dropout: An Advancing Method for Transparent Object Tomography**](https://arxiv.org/abs/2502.19314)  | _[CODE](https://github.com/yang980130/Enhancing-Optical-Diffraction-Tomography-with-Physics-Guided-Adaptive-Dropout-Neural-Networks/tree/master)_  
Yang, D., Zhang, S., Sun, J., Zuo, C., & Hao, Q. (2025). *arXiv preprint*, arXiv:2502.19314.
#### Neural Re-parameterization of 3D RI

- [**Diffraction Tomography with a Deep Image Prior**](https://opg.optica.org/oe/fulltext.cfm?uri=oe-28-9-12872&id=430210)  | _[CODE](https://github.com/kevinczhou/deep-prior-diffraction-tomography)_   
Zhou, K. C., & Horstmeyer, R. (2020). *Optics Express*, 28(9), 12872-12896.

- [**Recovery of Continuous 3D Refractive Index Maps from Discrete Intensity-Only Measurements Using Neural Fields**](https://www.nature.com/articles/s42256-022-00530-3)  | _[CODE](https://github.com/wustl-cig/DeCAF)_   
Liu, R., Sun, Y., Zhu, J., Tian, L., & Kamilov, U. S. (2022). *Nature Machine Intelligence*, 4(9), 781-791.

- [**Dynamic Multiplexed Intensity Diffraction Tomography Using a Spatiotemporal Regularization-Driven Disorder-Invariant Multilayer Perceptron**](https://opg.optica.org/oe/fulltext.cfm?uri=oe-32-22-39117&id=561408)  
Luo, H., Chen, H., Xu, J., Wan, M., Zhong, L., Lu, X., & Tian, J. (2024). *Optics Express*, 32(22), 39117-39133.



- [**Neural-Field-Assisted Transport-of-Intensity Phase Microscopy: Partially Coherent Quantitative Phase Imaging under Unknown Defocus Distance**](https://opg.optica.org/prj/fulltext.cfm?uri=prj-12-7-1494&id=552941)  
Jin, Y., Lu, L., Zhou, S., Zhou, J., Fan, Y., & Zuo, C. (2024). *Photonics Research*, 12(7), 1494-1501.


#### Direct Optimization with Physics-Based Models

#### Physics-Based Model


### Combine with other imaging characters
- [**Bond-Selective Intensity Diffraction Tomography**](https://www.nature.com/articles/s41467-022-35329-8) | _[CODE](https://github.com/buchenglab/BS-IDT)_  
Zhao, J., Matlock, A., Zhu, H., et al. (2022). *Nature Communications*, 13, 7767.

## Labs and Researchers

- [Computational Biophotonics Laboratory, UNC Chapel Hill](http://www.nicolaspegard.com/index.php)

- [Computational Imaging Group, KAUST](https://vccimaging.org/publications.html)

### IDT 
- [Computational Imaging Systems Lab, Boston University](https://sites.bu.edu/tianlab/)
- [Computational Imaging Lab, UC Berkeley](https://www.laurawaller.com/)
- [Smart Computational Imaging (SCI) Laboratory, NUST](https://www.scilaboratory.com/)

## Talks, Lectures, and Tutorials
- [Diffraction Tomography: Computational Optical Imaging](https://www.youtube.com/watch?v=B4nYL-4e2zI)  
   David J. Brady,Arizona Camera Lab, 2024

## Contributing
If you would like to contribute to this list, please follow these steps:
1. [Create a new issue](https://github.com/willytrek/Awesome-diffraction-tomography/issues).
2. Explain in the issue why the paper/book/talk is relevant and under which category the resource should be placed.


