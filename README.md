# SCCD: Shift-Variant Color-Coded Diffractive Spectral Imaging System

### [Project Page](https://jorgebaccauis.github.io/) | [Paper](https://www.osapublishing.org/optica/fulltext.cfm?uri=optica-8-11-1424&id=464500)

[Henry Arguello](https://scholar.google.com/citations?hl=es&user=R7gjbGIAAAAJ), [Samuel Pinilla](https://scholar.google.com/citations?hl=es&user=yGayy7sAAAAJ), [Yifan (Evan) Peng](http://stanford.edu/~evanpeng/), [Hayato Ikoma](https://scholar.google.com/citations?hl=es&user=ls53M1kAAAAJ), [Jorge Bacca](https://scholar.google.com/citations?hl=es&user=I5f1HjEAAAAJ), and [Gordon Wetzstein](http://stanford.edu/~gordonwz/)

This repository contains the scripts associated with the paper "Shift-Variant Color-Coded Diffractive Spectral Imaging System".

## Abstract
State-of-the-art snapshot spectral imaging (SI) systems introduce color-coded apertures (CCA) into their setups to obtain a flexible spatial-spectral modulation, allowing spectral information to be reconstructed from a set of coded measurements. Besides the CCA, other optical elements, such as lenses, prisms, beam splitters, are usually employed making systems large and impractical. Recently, diffractive optical elements (DOEs) have partially replaced refractive lenses to drastically reduce the size of the SI devices. The sensing model of these systems is represented as a projection modeled by a spatially shift-invariant convolution between the unknown scene and a point spread function (PSF) at each spectral band. However, the height maps of the DOE are the only free parameters that offer changes in the spectral modulation, which causes the ill-posedness of the reconstruction to increase significantly. To overcome this challenge, our work explores the advantages of the spectral modulation of an optical setup composed of a DOE and a CCA. Specifically, the light is diffracted by the DOE and then filtered by the CCA, located close to the sensor. A shift-variant property of the proposed system is clearly evidenced, resulting in a different PSF for each pixel, where a symmetric structure constraint is imposed on the CCA to reduce the high number of resulting PSFs. Additionally, we jointly design the DOE and the CCA parameters with a fully differentiable image formation model using an end-to-end approach to minimize the deviation between the true and reconstructed image over a large set of images. Simulation shows that the proposed system improves the spectral reconstruction quality in up to 4dB compared with current state-of-the-art systems. Finally, experimental results with a fabricated prototype in indoor and outdoor scenes validated the proposed system, where it can recover up to 49 high fidelity spectral bands in the 420-660 nm. 

## Citation
If you find our work useful in your research, please cite:

```
@article{arguello2021shift,
title={Shift-variant color-coded diffractive spectral imaging system},
author={Arguello, Henry and Pinilla, Samuel and Peng, Yifan and Ikoma, Hayato and Bacca, Jorge and Wetzstein, Gordon},
journal={Optica},
volume={8},
number={11},
pages={1424--1434},
year={2021},
publisher={Optical Society of America}
}
```

## Contact
If you have any questions, please contact

* Henry Arguello, 
* Samuel Pinilla, 
* Yifan (Evan) Peng, evanpeng@stanford.edu
* Hayato Ikoma, 
* Jorge Bacca, 
* Gordon Wetzstein, gordon.wetzstein@stanford.edu 
