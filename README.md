<p align="center">
  <img src="assets/muse-logo.png" alt="MUSE logo" width="360">
</p>

<h1 align="center">MUSE</h1>
<h3 align="center">Memory-Based Unified Self-Reference Evolution<br>for Single-Image Dehazing</h3>

<p align="center">
  <a href="#overview">Overview</a> ·
  <a href="#framework">Framework</a> ·
  <a href="#visual-results">Visual Results</a> ·
  <a href="#availability">Availability</a>
</p>

<p align="center">
  <strong>Single-Image Dehazing</strong> &nbsp; / &nbsp; Computer Vision &nbsp; / &nbsp; Image Restoration
</p>

<p align="center">
  <img src="assets/teaser.png" alt="A hazy landscape and visual comparisons with MUSE and other dehazing methods" width="100%">
</p>
<p align="center"><em>Selected visual comparison. Method names and the highlighted region are labeled in the figure.</em></p>

## Overview

**MUSE** studies single-image dehazing under challenging haze conditions, including spatially nonuniform and dense haze. The goal is to recover scene visibility while preserving image structure and a natural appearance.

This repository presents the framework and selected qualitative results from the project. The gallery covers indoor, outdoor, nonuniform-haze, dense-haze, and real-world scenes.

## Framework

<p align="center">
  <img src="assets/framework.png" alt="MUSE framework: initial restoration, progressive self-reference memory, and spatial context integration" width="100%">
</p>
<p align="center"><em>Overview of the MUSE framework.</em></p>

## Visual Results

Select a dataset below to view its comparison figure. Click any figure to inspect it at full resolution. Input images, comparison methods, MUSE outputs, and clear references where available are labeled within each figure.

### Paired benchmarks

<details open>
<summary><strong>I-HAZE · Indoor scenes</strong></summary>
<br>

![Visual comparison on I-HAZE](assets/i-haze.png)

</details>

<details>
<summary><strong>O-HAZE · Outdoor scenes</strong></summary>
<br>

![Visual comparison on O-HAZE](assets/o-haze.png)

</details>

<details open>
<summary><strong>NH-HAZE · Nonuniform haze</strong></summary>
<br>

![Visual comparison on NH-HAZE](assets/nh-haze.png)

</details>

<details>
<summary><strong>Dense-HAZE · Dense haze</strong></summary>
<br>

![Visual comparison on Dense-HAZE](assets/dense-haze.png)

</details>

### Real-world scenes

<details>
<summary><strong>RTTS</strong></summary>
<br>

![Visual comparison on RTTS](assets/rtts.png)

</details>

<details>
<summary><strong>HSTS</strong></summary>
<br>

![Visual comparison on HSTS](assets/hsts.png)

</details>

<details>
<summary><strong>FTD</strong></summary>
<br>

![Visual comparison on FTD](assets/ftd.png)

</details>

## Availability

| Material | Status |
| :--- | :--- |
| Method logo | Available |
| Framework figure | Available |
| Selected visual comparisons | Available |
| Source code and model weights | Not publicly available at this stage |

Publication details and citation information will be added when available.

## Acknowledgments

We acknowledge the authors of the datasets and comparison methods shown in the figures. Dataset images and third-party materials remain subject to their original terms. This repository does not redistribute the underlying datasets.
