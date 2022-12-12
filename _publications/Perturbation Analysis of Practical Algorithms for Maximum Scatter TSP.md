---
title: "Perturbation Analysis of Practical Algorithms for Maximum Scatter TSP"
collection: publications
permalink: /publication/perturbation-analysis-of-algorithms-for-MSTSP
excerpt: "Proposed six simple-to-code, scalable **heuristics** for **NP-hard** Maximum Scatter Travelling Salesman Problem (MSTSP). Studied the reliability of these algorithms in terms of runtime, quality, and stability using **smoothed analysis**, by slightly perturbing the inputs. Observed **practical efficacy** of simple heuristics despite their exponential worst-case complexity due to **polynomial expected runtime**, as the worst-case instances are **sparse** and **rare**. Find [code](https://github.com/sundar7D0/maximum-scatter-TSP)."
date: 2022-01-10
venue: 'Symposium on Algorithm Engineering and Experiments (ALENEX22) by Sundar Raman P, Emil Biju'
paperurl: 'https://epubs.siam.org/doi/abs/10.1137/1.9781611977042.13'
---

In this work, we describe six algorithms for MSTSP with improved formulations of prior work that enhance their real-world efficacy. Further, we perform experimental studies motivated by smoothed analysis to comprehensively evaluate these algorithms in terms of run-time, quality and stability.

The six algorithms that we describe in this work are:

1. Naive Greedy Algorithm
2. Naive Weave Algorithm
3. Hoffmann Weave Algorithm
4. Dirac Algorithm
5. Pure 2-opt Algorithm
6. Randomized 2-opt Algorithm

Our benchmarking experiments can be broadly split into three categories:

1. Closeness of algorithm predictions to the scatter bound
2. Deviation of maximum scatter predictions under perturbation
3. Variation in the runtime of algorithms

Key Contributions:
1. We observe that the Naive Greedy algorithm is very fast and easy-to-implement baseline for MSTSP.
2. We present the Naive Weave and Hoffmann Weave algorithms which introduce an improved formulation of the work by Arkin and Hoffmann to extend their usability to non-regular grids.
3. We introduce Pure 2-opt and Randomised 2-opt as very close approximation algorithms for the MSTSP.
4. We use a real-world dataset augmented using five graph perturbations and evaluated with three edge cost metrics to perform a comprehensive perturbation analysis of the algorithms and compare results on three critical performance measures, namely, the quality, runtime and stability of the algorithms.

Find [code](https://github.com/sundar7D0/maximum-scatter-TSP).
