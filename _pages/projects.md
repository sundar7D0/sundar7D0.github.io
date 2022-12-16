---
layout: archive
title: "Technical Projects"
permalink: /projects/
author_profile: true
---
This page portrays projects done at Center for Innovation ([CFI](https://cfi.iitm.ac.in/)) for fun, real-world challenges using off-the-shelf hardware and software components. Refer [LinkedIn](https://www.linkedin.com/in/sundar2000) for info. about my professional experiences.

## Cube, an assistive device for the visually-impaired
* [Cube](https://www.jamesdysonaward.org/en-IN/2020/project/cube/) is a **seamless assistive device for the blind** to help them learn, type, read in braille & navigate easily. 
* Arrived at this solution after having pretotyped **several experiments**, making many agile working prototypes and testing them with blind from NGOs.
* Selected as an **incubatee** by [Nirmaan](https://nirmaan.iitm.ac.in/), a pre-incubation cell at IITM, where we attended workshops by silicon valley VCs, analyzed product-market fit & received ∼$5000 to develop the initial prototype. Find [video](https://youtu.be/LKwTY97eouc), [media](https://drive.google.com/drive/folders/1HBeBY-nXRQ0f0Sl53vqzE_TpwBGjkS2y?usp=sharing), [field-test](https://drive.google.com/file/d/1F0XEBxL4sAShRLck5TZ5tbYVnmEnXO4o/view?usp=sharing), [article](https://medium.com/@nirmaan_iitm/blink-a-deep-tech-startup-working-on-a-portable-text-to-braille-interactive-device-at-nirmaan-67a7c4cd7646).

<img src='/images/blink_prototype.jpeg' align="center" width="480" height="300" style="vertical-align:right;margin:0px 30px">
 
## Smart-bin
* Designed a smart waste-segregator bin to categorize waste into 4 types: paper, composite, plastic & wet-waste, to tackle the **waste-segregation problem** at the very root.
* Trained **DL models** to demarcate waste with **∼95%** accuracy. 
* Implemented the **electronics-subsystem** with servos to control bin lids, RFID scanners to scan IDs, BeagleBone AI board to run DL models at edge, LCD to display bin no. and SMPS for power management.
* Field tested at Campus Cafe, IITM. Find [slides](https://drive.google.com/drive/folders/1dT3ZZ_8g_MOizgmEKLXDApM6tMJDBB5u?usp=sharing), [video](https://drive.google.com/file/d/1eWksJXGUBuACYEtR6RTmr3X5HRkNl-WT/view?usp=sharing), [code](https://github.com/sundar7D0/smart-bin).

<img src='/images/Smart_bin_prototype.png' align="center" width="480" height="300" style="vertical-align:right;margin:0px 30px">

## Accelerating bouncing balls using CUDA DSL
* **1.5× speed-up** of a **2D balls-collision game** by splitting the rendering into multiple windows, each of which is handled by a CUDA thread.
* Used **OpenGL** for graphics.
* Utilized pinned memory, texture buffer, read/write coalescing, ternary operator to reduce thread divergence, stream kernels, **atomically updated list for ball-states**, cache-efficient nested for-loop, nvprof profiler. Play the [game](https://covidchaos.github.io/), find [code](https://github.com/sundar7D0/cuda-bouncing-balls).

<img src='/images/Ball Bounce.png' align="center" width="480" height="300" style="vertical-align:right;margin:0px 30px">

## Automatic Cooking Machine (in collaboration with [Butterfly](https://www.butterflyindia.com/))
* Worked on revamping/improvising the application, mechanical, electronics, electrical stack of AutoChef-v1.0 developed by Butterfly to design **AutoChef-v2.0**. Exact details are **confidential**. Find [certificate](/images/Autochef_Certificate.pdf).

<img src='/images/butterfly_acm.PNG' align="center" width="480" height="300" style="vertical-align:right;margin:0px 30px">

## Sulabh: A gateway for accessibility
* To make websites truly accessible, we proposed Sulabh, a web app that asks users to choose the kind of assistance/feature (instead of choosing disability) category they would aspire, a few of which are given below:
1. **Voice Assistance**: Screen structure & screen reader, voice recognition & commands, navigation cues, prioritizes errors!
2. **Gesture Based Assistance**: Eye and facial movement tracker for cursor movement and keyboard control;
3. **Image/Video Captions**, Automatic site maps & Hyperlinks briefing assistance;
4. **Appearance Settings**: Brightness, font, font & button size, line & paragraph spacing, color scheme & contrast control;
5. Feature for even more “Easy Access & Understanding”: Search, spelling & meaning assistant, keyboard shortcuts for thumbnails and bookmarks, block popups, highlighting keywords, **refreshable braille display support** for the blind-deaf, etc.
*  This work was appreciated by the **Ministry of Rural Development, Government of India** and reached the finals of **Smart India Hackathon - 2020**.
* Find [slides](https://drive.google.com/file/d/1_WXYELWDVeiwf3lYjPxyJHQ-5P73Zk9b/view?usp=sharing), [flow-chart](https://docs.google.com/presentation/d/1g30mrwJuWM8Azmi5lHu2ObM2WvNzK6pTISDG4bERhPs/edit?usp=sharing).

<img src='/images/sulabh_app.jpg' align="center" width="480" height="300" style="vertical-align:right;margin:0px 30px">


## ATBERT: Multi-modal music classifier
* Since music can be classified based on genre, beats, themes, etc. and it is difficult to obtain huge labelled data, a **self-supervised** (to learn music representation with limited labelled data) **multi-modal** (multiple inputs from similar distributions is similar to more data) **transformer** (to tackle long range sequence dependence; parallelizable, reduced computations) will be **efficient**.
* **Correct Pair Prediction (CPP)** is used to help model learn **cross-modal** dynamics. Model tries to predict whether a pair of audio-text embeddings corresponds to the same music or different. One **binary classifier** which takes in audio-text summary embedding and a random-time multi-modal encoder output are passed through an external 2 layer, non-linear head to classify.
* **Info-Noise-Contrastive-Estimation (InfoNCE)** loss is also used where a **audio-text pair** is classified into positive/negative class where negative classes are sampled from a mini-batch based on a **novel CANS-Similar** (L2 norm based) method. Find [code](https://github.com/sundar7D0/ATBERT).

<img src='/images/atbert.png' align="center" width="480" height="300" style="vertical-align:right;margin:0px 30px">

## Cloud Beacon: IoT for seamless local broadcast
* To share data anywhere, to anyone **within proximity** without actually having to connecting to the network (to **avoid security issues**). Find [concept doc](/images/EE03_CLOUD_BEACON.pdf).
* Use-cases include museums, malls, etc. where information about nearby **artifacts** can be displayed on phone without the user connecting to the open network.

<img src='/images/cloud_beacon_poster.PNG' align="center" width="480" height="300" style="vertical-align:right;margin:0px 30px">
