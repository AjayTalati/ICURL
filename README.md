# Reinforcement learning in intensive care

Code for reinforcement learning for sepsis treatment in ICU

Author: Dr Matthieu Komorowski, Imperial College London, 2016-2017 - m.komorowski14@imperial.ac.uk

This repository contains PostgreSQL and Matlab code to:
1. define cohorts of patients fulfilling the sepsis-3 definition in two databases: MIMIC-III (https://mimic.physionet.org/) and eICU-RI (not publicly available in full, subset available here: http://eicu-crd.mit.edu/)
2. extract the data of interest from both databases
3. build the Markov Decision Process from the MIMIC-III dataset
4. test the optimal policy identified on the eICU-RI dataset
5. computes the main results and key figures
