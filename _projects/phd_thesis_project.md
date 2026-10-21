---
layout: page
title: PhD Thesis
description: Theoretical analysis of diffusion flames and development of a Large Eddy Simulation model for turbulent hydrogen diffusion flames
img: assets/img/personal/illustation_thesis.png
importance: 1
category: work
related_publications: true
---

{% comment %}
AL-FOLIO PROJECT PAGE — EDITING NOTES
- Save this file in your website repository under _projects/ (e.g., _projects/1_phd_thesis.md).
- Replace assets/img/personal/illustation_thesis.png with your own cover image, or remove the `img` field.
- Replace all [PLACEHOLDER] fields with verified information before publication.
- The `related_publications` option can be linked to papers in _bibliography/papers.bib.
{% endcomment %}

## Overview

My PhD research focuses on **Computational Fluid Dynamics (CFD) applied to reactive flows**, with particular emphasis on the **modeling of turbulent hydrogen–air diffusion flames**. The project combines a detailed physical characterization of these flames with the development and assessment of a numerical modeling approach.

**Laboratory:** [CERFACS](https://cerfacs.fr/en/home/)  
**Institution:** MEGeP  
**Period:** 2023 – 2026  
**Supervisors:** Thierry Poinsot – Nicolas Bertier  
**Thesis title:** Theoretical analysis of diffusion flames and development of a Large Eddy Simulation model for turbulent hydrogen diffusion flames


## Scientific context and motivation

Hydrogen is attracting increasing interest as a potential low-carbon fuel for future gas turbines and aeronautical propulsion systems. However, its distinctive properties, including high reactivity, fast chemical kinetics, and strong molecular diffusivity, introduce significant challenges for combustion modeling. In particular, hydrogen combustion can involve extremely thin diffusion flame fronts, whose structure is strongly influenced by local strain and pressure.

Large Eddy Simulation (LES) offers a promising compromise between computational cost and physical accuracy for studying turbulent combustion in realistic configurations. Nevertheless, at high pressures, the characteristic thickness of hydrogen diffusion flames can become significantly smaller than the available computational grid resolution. As a result, even the flame structures expected to be resolved by LES may be inadequately represented, leading to numerical inaccuracies.

**While existing combustion models primarily focus on flame–turbulence interactions, they do not necessarily guarantee adequate spatial resolution of diffusion flame fronts. Addressing this limitation is therefore essential for developing reliable predictive tools for turbulent hydrogen combustion.**

Conducted within the PHYDROGEN project, a collaboration involving CERFACS, ONERA, and DGAC, this PhD research aims to improve the physical understanding and numerical modeling of hydrogen–air diffusion flames, with particular emphasis on flame strain, density variations, and spatial resolution in LES.

## Research objectives

The main objective of this PhD is to **develop a reliable Large Eddy Simulation (LES) model for turbulent hydrogen–air diffusion flames**, with particular emphasis on ensuring adequate spatial resolution of flame fronts under challenging operating conditions.

To achieve this goal, the research is structured around three main objectives:

1. **Improve the physical understanding of laminar diffusion flames.** Investigate the influence of flame strain on the structure and behavior of hydrogen–air diffusion flames. This includes establishing a consistent definition of strain (Chapter 2) and extending classical theoretical approaches to account for the strong density variations characteristic of hydrogen combustion (Chapter 3).

2. **Characterize the impact of spatial resolution on numerical simulations.** Identify the minimum resolution required to accurately capture diffusion flame fronts and assess how insufficient resolution affects flame structure, heat release, and combustion dynamics. This investigation involves both steady laminar flames and unsteady flame–vortex interactions (Chapter 4).

3. **Develop and evaluate a dedicated LES combustion model.** Design a model capable of dynamically adjusting diffusion flame thickness to maintain adequate spatial resolution on the computational grid. The proposed **Diffusion Front Thickness Control (DFTC)** approach is evaluated through laminar and turbulent configurations, with particular attention to preserving relevant flame properties and combustion behavior (Chapter 5).

Together, these objectives aim to establish a stronger physical and numerical foundation for the predictive simulation of turbulent hydrogen diffusion flames in practical combustion systems.

## Methodology

### Physical characterization

[DESCRIBE THE FLAME CONFIGURATIONS, PARAMETERS INVESTIGATED, AND PHYSICAL DIAGNOSTICS.]

### Numerical framework

[DESCRIBE THE CFD METHODS, COMBUSTION MODELING FRAMEWORK, NUMERICAL TOOLS, AND VALIDATION STRATEGY.]

### Model development and evaluation

[EXPLAIN THE PROPOSED MODEL, ITS ASSUMPTIONS, HOW IT WAS EVALUATED, AND THE REFERENCE CASES.]

## Selected results

[SUMMARIZE 2–4 MAJOR FINDINGS. QUANTIFY RESULTS WHERE POSSIBLE AND DISTINGUISH PHYSICAL FINDINGS FROM MODEL PERFORMANCE.]

{% comment %}
 Optional figure: uncomment after uploading assets/img/thesis_result_1.png.
<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/thesis_result_1.png" title="Thesis result" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  [FIGURE 1 CAPTION: physical quantity, configuration, and key interpretation.]
</div>
{% endcomment %}

## Scientific contributions

- **Physical understanding:** [MAIN CONTRIBUTION TO THE CHARACTERIZATION OF HYDROGEN–AIR DIFFUSION FLAMES.]
- **Modeling:** [MAIN ORIGINAL MODELING CONTRIBUTION.]
- **Numerical assessment:** [KEY VALIDATION OR COMPARISON RESULT.]

## Publications and communications

- **Journal article:** [FULL CITATION AND PUBLICATION STATUS], *Combustion and Flame*. [DOI / LINK]
- **Conference contributions:** [CONFERENCE NAME, YEAR, TITLE, ORAL/POSTER].
- **PhD thesis:** Not available yet, you can ask me the current version by mail.

<!-- If your bibliography is configured, cite an entry with:
     {% cite YOUR_BIBTEX_KEY %}
     and maintain the matching entry in _bibliography/papers.bib.
-->

## Resources

- [Thesis manuscript](THESIS_URL)
- [Related publication](PUBLICATION_URL)
- [Research laboratory](LAB_URL)

<!-- Delete links that are not yet available. -->
