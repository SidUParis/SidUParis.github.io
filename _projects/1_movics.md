---
layout: page
title: MOVICS
description: Multi-Omics Integration and Visualization in Cancer Subtyping
img: assets/img/movics.jpg
importance: 1
category: work
github: https://github.com/xlucpu/MOVICS
related_publications: true
---

## Overview

**MOVICS** (Multi-Omics Integration and VIsualization in Cancer Subtyping) is a comprehensive R package designed to address a central challenge in cancer research: the robust integration and interpretation of multi-omics data for tumor subtyping.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/movics_workflow.jpg" title="MOVICS workflow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    MOVICS integrates multiple omics layers to identify clinically meaningful tumor subtypes.
</div>

## Key Features

- **Comprehensive Integration**: Implements 10 state-of-the-art multi-omics clustering algorithms
- **Downstream Analysis**: Structured analyses for cancer subtype characterization and interpretation
- **Reproducible Framework**: Transforms high-dimensional, heterogeneous data into biologically interpretable tumor phenotypes
- **Clinical Relevance**: Enables systematic exploration of tumor heterogeneity in a clinically meaningful manner

## Impact

Since its release, MOVICS has achieved broad adoption within the scientific community:

- **197 citations** reflecting its methodological impact and generalizability
- **145+ GitHub stars** and **45+ forks** demonstrating strong open-source engagement
- Used by research groups worldwide for cancer subtyping studies

## MOVICShiny

Building on MOVICS's success, I developed **MOVICShiny**, an interactive Shiny application that lowers the barrier to multi-omics analysis for researchers with limited programming expertise.

- **Web Application**: [http://www.movics-cpu.com:3838/](http://www.movics-cpu.com:3838/)
- **Currently used by 20+ research groups** internationally
- Published in _Clinical and Translational Medicine_

## Resources

- **GitHub Repository**: [xlucpu/MOVICS](https://github.com/xlucpu/MOVICS)
- **Documentation**: Comprehensive vignettes and tutorials
- **Publication**: Lu et al., _Bioinformatics_ (2020)
- **MOVICShiny Publication**: Zhu et al., _Clinical and Translational Medicine_ (2024)

## Applications

MOVICS has been applied to various cancer types including:

- Upper tract urothelial carcinomas (UTUC)
- Bladder cancer (UBC)
- Clear-cell renal cell carcinoma (ccRCC)
- Multiple other solid tumors

The framework enables researchers to:

- Identify molecular subtypes associated with clinical outcomes
- Characterize tumor microenvironment heterogeneity
- Predict treatment response
- Discover novel therapeutic targets
