# Adaptive Optics Image Analysis Software Suite

This documentation provides an overview and usage instructions for a suite of open-source software tools developed for analysis of adaptive optics (AO) retinal images.

---

## Overview

AO retinal imaging enables visualization of retinal cells at cellular resolution, including cone photoreceptors and retinal pigment epithelial (RPE) cells. Quantitative analysis of these images requires reliable tools for cell detection and  segmentation.

This software suite provides user-friendly tools that integrate automated algorithms with interactive editing capabilities to support accurate and reproducible analysis of AO images.

---

## Software Packages

The suite consists of three independent software tools:

### Cone Detection ML
- Artificial intelligence (AI) assisted detection of cone photoreceptors in AO non-confocal split detection images.
- Github link: [https://github.com/NIH-NEI/ConeDetectionML/tree/main](https://github.com/NIH-NEI/ConeDetectionML/tree/main)

### Cone Segmentation ML
- AI assisted segmentation of cone photoreceptors in AO non-confocal split detection images.
- Github link: [https://github.com/NIH-NEI/ConeSegmentationML/tree/main](https://github.com/NIH-NEI/ConeSegmentationML/tree/main)

### RPE Detection
- AI assisted detection of retinal pigment epithelial (RPE) cells from AO enhanced indocyanine green images.
- Github link: [https://github.com/NIH-NEI/RPE_Detection/tree/main](https://github.com/NIH-NEI/RPE_Detection/tree/main)

---

## Key Features

- Standalone executable applications (no external dependencies required)
- Support for both automated and interactive workflows
- Cross-platform compatibility (Windows and macOS)
- Structured outputs for downstream quantitative analysis
- Designed for both research and non-expert users

---

## Getting Started

To begin using the software:

1. Download the appropriate software package from the GitHub repositories.
2. Launch the executable file for your operating system.
3. Load AO images and run detection or segmentation using the built-in tools.

---

## Intended Use

These software tools are designed for research purposes only and are not intended for clinical diagnosis or treatment. Please see the individual Github links for the License.

---

## Citation

If you use this software in your research, please cite the following publications.

- V. Das et al. "Open source software suite for cell detection and segmentation of adaptive optics retinal imaging", Translational Vision Science and Technology.

The publications specific to the software packages:

- **Cone Detection ML**: J. Liu et al. "Active cell appearance model induced generative adversarial networks for annotation-efficient cell segmentation and identification on adaptive optics retinal images." IEEE Transactions on Medical Imaging 40.10 (2021): 2820-2831.
- **Cone Segmentation ML**: J. Liu et al. "Active cell appearance model induced generative adversarial networks for annotation-efficient cell segmentation and identification on adaptive optics retinal images." IEEE Transactions on Medical Imaging 40.10 (2021): 2820-2831.
- **RPE Detection**: J. Liu et al. "Spatially aware dense-linkNet based regression improves fluorescent cell detection in adaptive optics ophthalmic images." IEEE Journal of Biomedical and Health Informatics 24.12 (2020): 3520-3528.

---

## Support

For questions, issues, or feature requests, please refer to the GitHub repositories.

