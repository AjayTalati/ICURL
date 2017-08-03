# Reinforcement learning in intensive care

Code for reinforcement learning applied to the management of intravenous fluids and vasopressors in sepsis, in intensive care patients.

Author: Dr Matthieu Komorowski, Imperial College London, 2016-2017 - m.komorowski14@imperial.ac.uk

This repository contains PostgreSQL and Matlab code to:
1. define cohorts of patients fulfilling the sepsis-3 definition in two databases: MIMIC-III (https://mimic.physionet.org/) and eICU-RI (not publicly available in full, subset available here: http://eicu-crd.mit.edu/)
2. extract the data of interest from both databases
3. build a Markov Decision Process model from the MIMIC-III dataset and identify an optimal policy
4. test the optimal policy identified on the eICU-RI dataset
5. computes the main results and key figures
