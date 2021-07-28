---
title: "Research"
permalink: /research/
---

## Massive galaxy formation and AGN feedback

There are several unanswered questions related to how galaxies that are roughly more massive than our own Milky Way formed.
We haven't fully understood their quenched star formation rates, the supermassive black holes (SMBHs) that live at their centers, and the role of SMBH feedback, i.e. active galactic nuclei (AGN) feedback.

Advised by Professor Claude-André Faucher-Giguère, I am studying the formation of massive galaxies using the cosmological hydrodynamical [FIRE (Feedback in Realistic Environments)](https://fire.northwestern.edu/) simulations.
One topic I am focusing on at the moment is the gas that encapsulates galaxies.
I plan to perform a comparison of the properties of massive gaseous halos (e.g. density, temperature, and pressure profiles) in simulations with X-ray and SZ (Sunyaev-Zeldovich) effect observations. 
For this analysis, I am using FIRE simulations which include a variety of models of AGN feedback.

## Modeling halo substructure in extreme-scale cosmology simulations

![Subhalos and cores](/images/SMACC.gif)

I have given a number of [talks](/talks) about this project.
{: .notice}

Galaxies in our universe form inside objects known as dark matter halos.
Over billions of years, halos grow by absorbing smaller halos, while the halos that are absorbed become subhalos. 
Due to the often complex halo merging histories, tracking these subhalos over billions of years poses a challenge when analyzing the largest simulations of dark matter.

Working as a post-bac student in the [Cosmological Physics and Advanced Computing (CPAC)](https://cpac.hep.anl.gov/) Group at Argonne National Laboratory and advised by Dr. Salman Habib and Dr. Katrin Heitmann, I helped develop Subhalo Mass-loss Analysis using Core Catalogs (SMACC), a new approach to tracking dark matter substructure that has several advantages over subhalo finding methods.
SMACC works by adding a mass model to halo merger trees in simulations using "core tracking."

With the goal of efficiently running SMACC on extreme-scale simulations, I developed a [parallel MPI-based implementation](https://github.com/isulta/smacc-parallel).
I implemented SMACC on the Last Journey and Farpoint Simulations run at Argonne, and produced catalogs of proxy subhalos.