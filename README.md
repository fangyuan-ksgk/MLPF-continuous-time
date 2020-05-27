# MLPF-continuous-time

This repository contains code of numerical simulations for the paper "Multilevel Particle Filters for the Non-Linear Filtering Problem in Continuous Time", link is here: https://arxiv.org/abs/1907.06328. This paper has been accepted for publication in
Statistics and Computing. 

The code is R language, Particle Filter, Multilevel Particle Filter with both maximally resampling and Wasserstein resampling are coded for each of the four models in the simulation section.

For each model, generate the data first, then run the section to obtain true value approximation, then we could test out PF, MLPF with maximally coupled resampling and MLPF with Wasserstein resampling. Detailed explanation could be find in the files.

Packages requirements: e1071, LaplaceDeconv, methods, pracma, stats, base. The author uses Rstudio, Version 1.2.1335.

Many thanks to my collaborators: Prof. Ajay Jasra and Prof. Jeremy Heng.

P.S. The author is planning to upload a python version of the code soon.

@Fangyuan_ksgk
