# Introduction
This directory contains the SCA power traces generated from SAKURA-X boards.

# Directory Structure
.
├── README.md
├── layout_encap.pdf
├── tvla_FFT_protected.pdf
├── tvla_FFT_unprotected.pdf
├── tvla_GEF_protected.pdf
└── tvla_GEF_unprotected.pdf

├── TVLA on Gaussian Elimination
  ├── GEF_protected_m0_fixed
  ├── GEF_protected_m1_random
  ├── GEF_unprotected_m0_fixed
  ├── GEF_unprotected_m1_random
├── TVLA on additive FFT
  ├── FFT_protected_m0_fixed
  ├── FFT_protected_m1_random
  ├── FFT_unprotected_m0_fixed
  ├── FFT_unprotected_m1_random
├── READE.md


# Description
* GEF_protected_m0_fixed: power traces with SCA countermeasures, Test Vector Leakage Analysis (TVLA) fixed t-test
* GEF_protected_m1_random: power traces with SCA countermeasures, TVLA random t-test
* GEF_unprotected_m0_fixed: power traces without SCA countermeasures, Test Vector Leakage Analysis (TVLA) fixed t-test
* GEF_unprotected_m1_random: power traces without SCA countermeasures, TVLA random t-test
* FFT_protected_m0_fixed: power traces with SCA countermeasures, Test Vector Leakage Analysis (TVLA) fixed t-test
* FFT_protected_m1_random: power traces with SCA countermeasures, TVLA random t-test
* FFT_unprotected_m0_fixed: power traces without SCA countermeasures, Test Vector Leakage Analysis (TVLA) fixed t-test
* FFT_unprotected_m1_random: power traces without SCA countermeasures, TVLA random t-test
* traces_xxx.mat: the power traces data, can be opened by matlab. Each file has 50 power traces (50 rows, each row contains one power trace)
