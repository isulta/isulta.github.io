---
title: "Visualizations"
permalink: /visualizations/
---
## Alpha Quadrant simulation

<video width="500" autoplay loop muted playsinline>
    <source src="/media/AlphaQ_499_downsampledp.webm" type="video/webm">
    Your browser does not support the video tag.
</video>

Shown is the dark matter distribution at $z=0$ of a $(256\ \mathrm{Mpc}/h)^3$ gravity-only simulation run by the Cosmological Physics and Advanced Computing group at Argonne National Laboratory. 
The visualization includes only a fraction of total particles processed in the simulation.

**The following set of visualizations study the largest dark matter halo found in AlphaQ at $z=0$.**
All visualizations were created using [ParaView](https://www.paraview.org/).

### Halo particle tracking

<video width="500" controls muted>
    <source src="/media/AlphaQ_halo_formation.webm" type="video/webm">
    Your browser does not support the video tag.
</video>

The formation of the massive $\sim 10^{15}$ $M_\odot/h$ halo is visualized.
The particles that formed the halo at $z=0$ were tracked back to $z \sim 10$.
At each step, particles belonging to halos found at that step are brightly colored.

### Core tracking

<video width="500" controls muted>
    <source src="/media/AlphaQ_core_tracking.webm" type="video/webm">
    Your browser does not support the video tag.
</video>

The massive halo was formed by mergers of smaller halos over the course of the simulation.
This visualization shows the trajectories of the 'cores' (central particles) of these smaller halos as they merged to form the massive halo at $z=0$.
The plot has been overlaid with the $z=0$ downsampled particle distribution near the halo.

### Supercluster halo

<video width="500" controls muted>
    <source src="/media/AlphaQ_halo.webm" type="video/webm">
    Your browser does not support the video tag.
</video>

The dark matter distribution of the massive halo is shown. 
The Friends-of-Friends algorithm was used to identify the halo at $z=0$.
The dense core and surrounding satellite halos are visible.