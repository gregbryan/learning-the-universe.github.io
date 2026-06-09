---
layout: page
title: Compressing SFHs
description: Compressed Star Formation Histories
img:
importance: 1
category: Synthetic Observations
related_publications: true
---

We developed and validated a method to compress simulated star formation histories (SFHs) from the SC-SAM outputs by projecting them onto a dense basis. This approach decomposes the native 2D age–metallicity grids into star formation and metallicity histories with minimal loss of information. The resulting non-parametric SFHs are represented as tuples of mass, SFR, and time, allowing for a factor of several hundred reduction in data volume while preserving photometric accuracy within science-driven tolerances.

This compression is critical for enabling efficient storage and forward modeling of SFHs across our large CAMELS-SAM suite {% cite 2023ApJ...954...11P %}, which includes thousands of semi-analytic simulations in $$(100\,\mathrm{Mpc}/h)^3$$ volumes. The method is fully implemented and benchmarked against multiple compression strategies (e.g., GP-SFH, NMF, IOB), with ongoing work optimizing binning schemes and parameter counts for specific science goals. See also {% cite 2025ApJ...994..174I %} for a study of how feedback shapes star formation histories across the CAMELS simulations.
