---
layout: post
title: Ensemble statistics of bedload transport
excerpt: ""
photo: 
image_position: "vertical"
modified:
tags:
comments:
category: research
---

In recent decades, there has been increasing effort toward modeling bedload transport using statistical ensembles for grain velocities, flight distance, and travel times. The forms of these probability distributions are integral to estimating sediment flux, with implications for predicting sediment transport in both natural and engineered systems. In this study, we analyze a high-resolution dataset of grain motions collected from laboratory flume experiments to extract these distributions. We recorded videos of a sand bed exposed to increasing fluid shear ranging from below the nominal threshold stress for grain motion to well above (τ*/τ*cr = 0.78−1.53). We extracted trajectories of a population of sand grains and used a hidden Markov model to predict the states of motion and rest from observed grain velocities. We characterize probability distributions for the activity, velocity, acceleration, flight distance, and travel times of moving grains and largely find agreement with previous studies. Streamwise velocities are well fit by an exponential distribution, accelerations display a Laplace distribution, flight travel times also show an exponential distribution, while flight distances are described by a Weibull distribution. We note, however, that these distributions described our data more poorly for bedload motion at and below the expected threshold of motion, especially for flight travel times, suggesting that bedload dynamics differ in this most intermittent regime. These experimental results provide a reference dataset for validating numerical simulations or analytical solutions for stochastic sediment transport models, especially for flow conditions at and below the nominal critical Shields stress.

![grain_trajectories](/images/research_pics/stress_hist_proj_pics/grain_tracks.png)
*(a) Example sediment trajectories from the particle-tracking analysis overlaid onto an image of the underlying sediment bed; note the appearance of fluorescing sand grains illuminated by the ultraviolet light. These trajectories represent transport conditions over a subset of the sediment bed at 1.2 times the nominal critical Shields stress. Time is reported through color coding with respect to the start of the 45 second video; the flow direction is from left to right. (b) The same sediment trajectories as depicted in panel (a) with markers indicating periods of motion (blue) and rest (red); the yellow-highlighted track is further examined in panel (c). (c) Timeseries of streamwise position (black line) and velocity (red/blue markers) for one example trajectory illustrating segments of motion and rest as identified using a hidden Markov model.*

This project is supported by the Army Research Office (ARO Award #W911NF-23-1-0032). This research is conducted in experimental facilities within the Bob & Norma Street Environmental Fluid Mechanics Lab at Stanford University.
<p align="center">
  <img src="/images/research_pics/logos/ARO.png" width="17%" />
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="/images/research_pics/logos/EFML.png" width="40%" /> 
</p>

#### Publications
**Bodek, S.**, Wang, D., Shattuck, M.D., O'Hern, C.S., and Ouellette, N.T., "Ensemble statistics of bedload transport. Part 1: Grain motion at near-threshold conditions," *submitted* [[preprint](https://essopenarchive.org/doi/abs/10.22541/essoar.15007250/v1)].

**Bodek, S.**, Wang, D., Shattuck, M.D., O'Hern, C.S., and Ouellette, N.T., "Ensemble statistics of bedload transport. Part 2: Stress history effects," *submitted* [[preprint](https://essopenarchive.org/doi/abs/10.22541/essoar.15007251/v1)].

#### Conference Abstracts

**Bodek, S.** and Ouellette, N. T., “Directional stress history effects on sediment motion – from grain wiggles to saltation,” American Geophysical Union (AGU) Fall Meeting, New Orleans, LA, 15–19 December 2025, Talk.
