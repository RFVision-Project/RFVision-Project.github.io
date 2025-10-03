<link rel="stylesheet" href="static/css/fontawesome.all.min.css">

# Diffusion²: Turning 3D Environments into Radio Frequency Heatmaps

<div align="center">

<!-- GitHub Button -->
<span class="link-block">
  <a href="https://github.com/kyoungjunpark/Diffusion2" target="_blank"
     class="external-link button is-normal is-rounded is-dark">
    <span class="icon" style="vertical-align: middle; margin-right: 6px;">
      <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="24" alt="GitHub"/>
    </span>
    <span style="vertical-align: middle; font-weight: bold;">View Code</span>

  </a>
    <!-- ArXiv button -->
  <a href="https://arxiv.org/abs/2510.02274" target="_blank"
     class="external-link button is-normal is-rounded is-dark" style="margin-left: 10px;">
    <span class="icon" style="vertical-align: middle; margin-right: 6px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/7a/ArXiv_logo_2022.png" width="40" alt="arXiv"/>
    </span>
    <span style="vertical-align: middle; font-weight: bold;">View Paper</span>
  </a>
</span>

</div>


## Overview

<div align="center">
<img src="./test/overview.png" alt="Overview" width="1000"/>
</div>

This project provides **RF-based human movement and 3D environment datasets** with APs, Wi-Fi, and mmWave measurements. The goal is to model and analyze RF signals for motion and environment understanding.

---

## RF Images

| Overshot  | 77 GHz |
|  :------:  | :----: |
| <img src="./test/FMCW_1/overshot.png" height=150> | <img src="./test/FMCW_1/0.png" height=100> |
| <img src="./test/FMCW_2/overshot.png" height=150> | <img src="./test/FMCW_2/0.png" height=100> |

**Note:** Star icon <img src="./test/AP.png" height=20> in overshot images represents the AP. Each overshot shows 10 different FMCW frequencies.

---

## RF Videos

| <img src="./test/video/0.gif" height="100"> | <img src="./test/video/1.gif" height="100"> | <img src="./test/video/h1.gif" height="100"> | <img src="./test/video/h2.gif" height="100"> |
|:-------------------------------------------:|:-------------------------------------------:|:-------------------------------------------:|:-------------------------------------------:|
| <img src="./test/video/2.gif" height="100"> | <img src="./test/video/3.gif" height="100"> | <img src="./test/video/h3.gif" height="100"> | <img src="./test/video/h4.gif" height="100"> |

---

## Real Experiments

### 1) Conference Room
![Conference Room](./test/real/real_scenario_1_fix_nerf.png)

### 2) Apartment
![Apartment](./test/real/real_scenario_2_fix_nerf.png)

### 3) Office
![Office](./test/real/real_scenario_3_fix_nerf.png)

**Note:** Measurements were performed in the white-box area in each environment.
