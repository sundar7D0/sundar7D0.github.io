---
layout: archive
title: "Technical Projects"
permalink: /projects/
author_profile: true
---

## Cube, an assistive device for the visually-impaired
* [Cube](https://www.jamesdysonaward.org/en-IN/2020/project/cube/) is a **seamless assistive device for the blind** to help them learn, type, read in braille & navigate easily. 
* Arrived at this solution after having pretotyped **several experiments**, making many agile working prototypes and testing them with blind from NGOs.
* Selected as an **incubatee** by [Nirmaan](https://nirmaan.iitm.ac.in/), a pre-incubation cell at IITM, where we attended workshops by silicon valley VCs, analyzed product-market fit & received ∼$5000 to develop the initial prototype. Find [video](https://youtu.be/LKwTY97eouc), [media](https://drive.google.com/drive/folders/1HBeBY-nXRQ0f0Sl53vqzE_TpwBGjkS2y?usp=sharing), [field-test](https://drive.google.com/file/d/1F0XEBxL4sAShRLck5TZ5tbYVnmEnXO4o/view?usp=sharing).

<img src='/images/blink_prototype.jpeg' align="center" width="480" height="300" style="vertical-align:right;margin:0px 30px">
 
## Smart-bin
* Designed a smart waste-segregator bin to categorize waste into 4 types: paper, composite, plastic & wet-waste, to tackle the **waste-segregation problem** at the very root.
* Trained **DL models** to demarcate waste with **∼95%** accuracy. 
* Implemented the **electronics-subsystem** with servos to control bin lids, RFID scanners to scan IDs, BeagleBone AI board to run DL models at edge, LCD to display bin no. and SMPS for power management.
* Field tested at Campus Cafe, IITM. Find [slides](https://drive.google.com/drive/folders/1dT3ZZ_8g_MOizgmEKLXDApM6tMJDBB5u?usp=sharing), [video](https://drive.google.com/file/d/1eWksJXGUBuACYEtR6RTmr3X5HRkNl-WT/view?usp=sharing), [code](https://github.com/sundar7D0/smart-bin).

<img src='/images/Smart_bin_prototype.png' align="center" width="480" height="300" style="vertical-align:right;margin:0px 30px">

## Accelerating bouncing balls using CUDA DSL
* **1.5× speed-up** of a 2D balls-collision game by splitting the rendering into multiple windows, each of which is handled by a CUDA thread.
* Used **OpenGL** for graphics.
* Utilized pinned memory, texture buffer, read/write coalescing, ternary operator to reduce thread divergence, stream kernels, **atomically updated list for ball-states**, cache-efficient nested for-loop, nvprof profiler. Play the [game](https://covidchaos.github.io/), find [code](https://github.com/sundar7D0/covid-chaos).

<img src='/images/Ball Bounce.png' align="center" width="480" height="300" style="vertical-align:right;margin:0px 30px">
