---
description: First Project
layout: "simple"
summary: "Lattice structures have become ever more popular in modern structural design, as they generally provide high strength-to-weight ratios. However, certain designs also prove to be effective in suppressing waves of specific frequencies, allowing lattice materials to be used as for instance noise isolators."
title: "Developing analytical models for dynamic analysis of lattice structures"
---

<center>
    <div style="display:flex;align-items:center;justify-content:center">
         <div style="flex:1;padding-right:0px;align:center">
              <img src="/projects/cse/fem_vs_sem.png" width="350"/>
         </div>
         <div style="flex:1;padding-left:0px;">
            <img src="/projects/cse/examples_beams.png" width="350"/>
        </div>
    </div>

**Left**: Comparison of dispersion curves obtained by SEM and FEM; FEM(n) indicates result when n finite elemenents are used [1]; **Right**: Examples of beam-like lattice structures and their respective unit cell [2]
</center>

Lattice structures have become ever more popular in modern structural design, as they generally provide high strength-to-weight ratios. However, certain designs also prove to be effective in suppressing waves of specific frequencies, allowing lattice materials to be used as for instance noise isolators. Numerical analysis with for instance the Finite Element Method (FEM) is often used to understand these properties.

Recent developments in the Spectral Element Method (SEM) show good promise for a significantly more efficient and more accurate alternative to FEM when it comes to treating wave behaviour in lattice structures. This report discusses the functioning of SEM and describes an implementation of it. The frequency response and band structure of several lattice structures are analyzed using this method and the results are compared with FEM.

[1] U. Lee, “Vibration analysis of one-dimensional structures using the spectral transfer matrix method,” Engineering Structures, vol. 22, pp. 681–690, June 2000.

[2] U. Lee, Spectral element method in structural dynamics. Singapore ; Hoboken, NJ: J. Wiley & Sons Asia, 2009.