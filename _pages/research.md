---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Research spans several subdisciplines of earthquake engineering with a focus on ground motion prediction through physics-based methods.

### Research Projects

#### Crustal Velocity and Structural Geology Modelling

The properties and structure of the Earth's subsurface plays a large role in the earthquake ground motions that are observed. The characterisation of the seismic velocities and density of the soil and rock at both the shallow and crustal scale is necessary to understand and model the seismic wave propagation of earthquake-induced waves. This research is ongoing to continually improve our velocity models through more accurate velocity prescriptions, embedded sedimentary basin structures, and inclusion of stochastic randomness through small-scale heterogeneities. The New Zealand Velocity Model (NZVM) can be found here [[Link]](https://github.com/ucgmsim/Velocity-Model):

![CantVM](https://raw.githubusercontent.com/lee-robin/lee-robin.github.io/master/images/foo-bar-identity.jpg)

#### Characteristics and Quality of Ground Motion Records

Earthquake ground motions describe the intensity of shaking through measurements of acceleration or velocity, and form the basis for earthquake demands on engineering structures. The ground motion records are complex signals with amplitude, duration and frequency content characteristics which are important in engineering applications. However, the measured quantities are subject to imperfections through instrument limitations and malfunctions, noise contamination, and complexities with the ground motions themselves. Recently we've developed a neural network which takes in ground motion quality features and provides a quality score. This is an active area of research as we continue to improve our prediction of quality and expand on functionality.

Show time series and fourier amplitude spectra.

#### Ground Motion Simulation Validation

In the advent of high performance computing, physics-based ground motion simulations are quickly becoming an alternative to conventional empirical ground motion models for ground motion prediction. Physics-based ground motion simulations have the inherent advantage of explicitly modelling the earthquake source rupture, seismic wave propgations and near-surface surficial site response, which conventional empirical methods account for simplistically. However, the simulations are only as good as their inputs, assumptions and limitations, and therefore require validation against observations to quantify their predictive capability. This validation also creates a feedback loop which allows for potential improvements to be identified. Current projects include validation of finite fault simulations, validation of subduction slab and interface earthquakes, validation using complex structural models and validation of uncertainty in ground motion simulations.

Show obs vs sim waveforms, and bias and stdev.

#### Physics-based Seismic Hazard Analysis

Seismic hazard analysis is the framework with which the earthquake-induced ground motion hazard is quantified on a site-specific basis. This has conventionally used empirical ground motion models, but the use of physics-based simulations has become a hot research topic in the past decade (e.g. Cybershake). Research in this field include the necessary adjustments to the hazard framework and computational workflow, differences between empirical and physics-based approaches, and functional possibilities due to the physics-based nature.

Plot of Hazard Curve and Hazard Map.
