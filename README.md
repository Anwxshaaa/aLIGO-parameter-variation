# Advanced LIGO Noise Budget

## aLIGO noise budget with parameter variations using PyGWinC

In this project I recreated the Advanced LIGO noise budgets using [`pygwinc`](https://git.ligo.org/gwinc/pygwinc) package, and modified two of the key parameters.

🎯 Aim: To understand how modifications in certain key design parameters affect the sensitivity curve of the detector

📋 Procedure:

- Using `pygwinc`, I printed the actual values of Laser Power and Arm Length of the detector.
- Modifing **two parameters** for multiple values:
  - Laser power (`ifo.Laser.Power`)
  - Arm Length (`ifo.Infrastructure.Length`)
- Compared resulting sensitivity curves

NOTE: In case of variation in arm length, to ensure optical stability, the mirror curvatures (ITM and ETM) are scaled with the arm length.



🛰️ This work was submitted as part of my MSc dissertation on Laser Interferometry for Gravitational Wave Detection at the University of Glasgow.


















