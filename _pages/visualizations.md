---
title: "Visualizations"
permalink: /visualizations/
---

{% include toc %}

## Alpha Quadrant Simulation

<img src="/images/AlphaQ_499_downsampledp.gif" alt="AlphaQ Simulation" align="right" width="450">

Shown is the dark matter distribution at $z=0$ of a $(256\ \mathrm{Mpc}/h)^3$ gravity-only simulation run by the Cosmological Physics and Advanced Computing group at Argonne National Laboratory. 
The visualization includes only a fraction of total particles processed in the simulation.

**The following set of visualizations study the largest dark matter halo found in AlphaQ at $z=0$.**
All visualizations were created using [ParaView](https://www.paraview.org/).

### Halo particle tracking

{% include video id="k7R7lfLpY-0" provider="youtube" %}

The formation of the massive $\sim 10^{15}$ $M_\odot/h$ halo is visualized.
The particles that formed the halo at $z=0$ were tracked back to $z \sim 10$.
At each step, particles belonging to halos found at that step are brightly colored.

### Core tracking

{% include video id="1Zj5t_5B8tc" provider="youtube" %}

The massive halo was formed by mergers of smaller halos over the course of the simulation.
This visualization shows the trajectories of the 'cores' (central particles) of these smaller halos as they merged to form the massive halo at $z=0$.
The plot has been overlaid with the $z=0$ downsampled particle distribution near the halo.

### Supercluster halo

{% include video id="iGWrdOzw9us" provider="youtube" %}

The dark matter distribution of the massive halo is shown. 
The Friends-of-Friends algorithm was used to identify the halo at $z=0$.
The dense core and surrounding satellite halos are visible.

## Shrinking sphere halo centering

{% include video id="y_OzSfFcaDg" provider="youtube" %}

Due to the irregular shapes and nonuniform densities of dark matter halos, accurately finding their center points can be challenging.
This visualization demonstrates the 'shrinking sphere' halo centering algorithm of [Power et al. 2003](https://ui.adsabs.harvard.edu/abs/2003MNRAS.338...14P/abstract).
The algorithm works by repeatedly finding the center of mass of a sphere as its radius is decreased.

Here, the shrinking sphere algorithm is applied to the [FIRE](https://fire.northwestern.edu/) massive galaxy A8 simulation at $z=1$.
The dark matter and gas distributions are shown in the left and right panels, respectively.

## FIRE halo

{% include video id="YSbsGKp6xCs" provider="youtube" %}