---
title: Spanish Vowels Detector
date: 2021-10-28T03:49:06.426Z
summary: An algorithm to detect vowels using a wavelet decomposition tree
draft: false
featured: false
tags:
  - Signal Processing
links:
  - url: https://github.com/vegabs/vowels-detection
    name: Code
    icon_pack: fab
    icon: github
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: Detector's UI.
---
An algorithm to detect all the spanish vowels (a, e, i, o & u) from audio signals using a Six-level wavelet decomposition tree. To detect the vowels, a comparison of the energies of the last frequency bands of the tree is carried out. Implemented using MATLAB and UI designed using GUIDE.