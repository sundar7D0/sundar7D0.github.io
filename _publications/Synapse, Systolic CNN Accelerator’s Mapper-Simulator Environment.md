---
title: "Synapse, Systolic CNN Accelerator’s Mapper-Simulator Environment"
collection: publications
permalink: /publication/synapse-mapper-simulator-for-inference-accelerator
excerpt: "For [ShaktiMAAN](https://github.com/iitm-sysdl/SHAKTIMAAN), an open-source **systolic inference accelerator** effort at [RISE](https://shakti.org.in/) lab, I designed a python compiler that schedules instructions given network, architecture configuration, and an event-driven, analytical, data-flow accurate simulator. This infrastructure helped address challenges in hardware verification, bottleneck analysis, design-space trade-offs, and **compiler optimization** for our accelerator. Further, **Deep Reinforcement Learning agents** (using PPO optimization algorithm) were used along with mapper-simulator to evaluate and explore the design space (tunable hardware/software knobs like buffer-size, loop-order, etc.) of our hardware to map DL networks **∼10%** more efficiently than existing heuristics on our hardware. Find [slides](https://drive.google.com/file/d/1NnDDXgM6h1zbRrv5gJUAIdI9pAYBtN9T/view?usp=sharing), [code](https://github.com/sundar7D0/Synapse).
"
date: 2021-06-10
venue: 'IIT Madras Bachelor Research Thesis presentation forum by Sundar Raman P'
paperurl: 'https://drive.google.com/file/d/1PMTwZhSbaysdSdLks98JykyDDe_itRQa/view?usp=sharing'

---


Systolic arrays are one of the most popular compute substrates within DL accelerators today, as they provide extremely high efficiency for running dense matrix multiplications by re-using operands through local data shifts. One such effort by [RISE lab](https://shakti.org.in/) at IIT Madras is [ShaktiMAAN](https://github.com/iitm-sysdl/SHAKTIMAAN), an open-source DNN accelerator for inference on edge devices based on systolic arrays. The complexity of this accelerator poses a variety of challenges in:
1. Hardware verification
2. Bottleneck analysis using performance modelling
3. Design space trade-offs
4. Efficient mapping strategy
5. Compiler optimizations

To tackle the above, I built Synapse (SYstolic CNN Accelerator’s MaPper-Simulator Environment): a versatile python based mapper-simulator environment. 


## Key Contributions:

* Mapper that generates instruction trace given any workload, knob values for a targeted architecture.
* Functional simulator cost model for ShaktiMAAN.
* A RL agent that interacts with the mapper-simulator environment to search through the design space to find optimal hardware (array, buffer size), software (network folds, loop order) co-design knobs.

Find [thesis](https://drive.google.com/file/d/1PMTwZhSbaysdSdLks98JykyDDe_itRQa/view?usp=sharing), [slides](https://drive.google.com/file/d/1NnDDXgM6h1zbRrv5gJUAIdI9pAYBtN9T/view?usp=sharing), [code](https://github.com/sundar7D0/Synapse).
