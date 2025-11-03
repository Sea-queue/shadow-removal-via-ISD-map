# Shadow Removal via Illuminant Spectral Direction(ISD) Estimation

We aim to recover the true scene appearance by eliminating cast shadows while preserving material color. This would improve the downstream computer vision tasks such as autonomous driving and robotic vision.

---

## 📌 Overview

- Annotation tool: we developed the tool to labele raw 16-bit linear images.
- Customized model: MambaVision backbone + Feature Pytramid Network like head for ISD map estimation.
- End-to-End pipeline: annotation tool + customized model + training & evalutaion.

---

## 🎬 Log Chromaticity Image via ISD Map
<p align="center">
  <img src="images/12_shah_haard_041.png" alt="img1" width="90%" />
</p>

<p align="center">
  <img src="images/19_manushi_manushi_012.png" alt="img1" width="90%" />
</p>
