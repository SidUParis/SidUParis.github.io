---
layout: page
title: Tumor Microenvironment in Bladder Cancer
description: TME-based classification and immunotherapy biomarker development in urothelial bladder carcinoma
img: assets/img/bladder_tme.jpg
importance: 5
category: work
related_publications: true
---

## Overview

This research focuses on the critical role of the **tumor microenvironment (TME)** in modulating treatment response in bladder cancer, with emphasis on predicting immunotherapy sensitivity through comprehensive transcriptomic profiling.

---

## Background

Bladder cancer exhibits significant heterogeneity in immune contexture and treatment response. Understanding TME composition and immune cell states is essential for:

- Predicting immunotherapy response
- Patient stratification
- Identification of therapeutic targets

---

## Large-Scale TME Profiling

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bladder_tme_classification.jpg" title="TME classification" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Study Design

- Analyzed transcriptomic profiles from **~4,000 bladder cancer samples**
- Comprehensive multi-cohort integration
- Focus on immune cell infiltration and activation states

### Objectives

1. Develop TME-based classification system
2. Predict immunotherapy sensitivity
3. Identify biomarkers for treatment selection

---

## TME-Based Classification

### Classification Framework

Developed a robust classification distinguishing:

**1. Immune-depleted tumors**

- Low immune cell infiltration
- "Desert" or "excluded" phenotypes
- Poor immunotherapy response

**2. Immune-infiltrated tumors** - further stratified into:

- **Activated immune state**:
  - High effector T cell signatures
  - Favorable prognosis
  - Enhanced immunotherapy response
- **Exhausted immune state**:
  - Immune checkpoint expression
  - T cell dysfunction markers
  - Variable treatment response

### Clinical Significance

This classification:

- Predicts **immunotherapy sensitivity**
- Informs **treatment selection**
- Provides **prognostic stratification**

---

## Multi-Omics Consensus Ensemble

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/consensus_ensemble.jpg" title="Consensus ensemble" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Approach

Integrated multiple data layers:

- Transcriptomics
- Copy number alterations
- Mutation profiles
- DNA methylation

### Key Findings

**Muscle-invasive bladder cancer (MIBC) subtypes**:

- Refined classification with stratified prognosis
- Distinct TME characteristics
- **Differential sensitivity** to frontline therapies:
  - Chemotherapy
  - Immunotherapy
  - Targeted agents

**Publication**: Lu, Meng et al., _Clinical and Translational Medicine_ (2021)

---

## Immune Gene Pair-Based Signature

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/immune_pairs.jpg" title="Immune gene pairs" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Innovation

- Developed **robust immune gene pair-based signature**
- Platform-independent approach
- Addresses technical batch effects

### Applications

1. **Prognosis stratification**
2. **Treatment personalization**
3. **Risk assessment**

### Advantages

- Robust across platforms
- Simple implementation
- Clinically actionable

**Publication**: Lu, Meng et al., _Clinical and Translational Medicine_ (2021)

---

## Immunotherapy Response Prediction

### Methodological Approach

Analyzed immune contexture features:

- Immune cell composition
- Activation markers
- Checkpoint expression
- Stromal signatures

### Key Discoveries

**Predictive factors for immunotherapy response**:

1. High CD8+ T cell infiltration
2. Activated (not exhausted) immune phenotype
3. Low immunosuppressive cell populations
4. Permissive stromal microenvironment

**Non-responder characteristics**:

- Immune exclusion mechanisms
- High regulatory T cell infiltration
- TGF-β pathway activation
- Stromal barriers

**Publication**: Meng, Lu et al., _Molecular Therapy - Oncolytics_ (2021)

---

## Clinical Applications

### Treatment Selection

The TME classification framework enables:

- **Immunotherapy candidates**: Activated immune-infiltrated tumors
- **Chemotherapy consideration**: Immune-depleted tumors
- **Combination strategies**: Exhausted immune state tumors

### Biomarker Development

Identified biomarkers for:

- Treatment response prediction
- Patient stratification in clinical trials
- Monitoring of treatment effects

### Risk Stratification

TME features provide:

- Prognostic information beyond clinical staging
- Recurrence risk assessment
- Metastatic potential prediction

---

## Conceptual and Statistical Challenges

This work introduced me to:

- **Biomarker development** in heterogeneous patient populations
- **Statistical methods** for high-dimensional data integration
- **Clinical translation** of molecular findings
- **Multi-cohort validation** strategies

---

## Impact on Field

### Methodological Contributions

- Platform-independent signature development
- Robust TME classification framework
- Integration strategies for multi-cohort studies

### Clinical Relevance

- Addresses key question: **Who will respond to immunotherapy?**
- Provides actionable biomarkers
- Informs clinical trial design

---

## Key Publications

1. Lu, Meng et al. Multi-omics consensus ensemble refines the classification of muscle-invasive bladder cancer. _Clinical and Translational Medicine_ (2021)

2. Lu, Meng et al. Prognosis stratification and personalized treatment in bladder cancer through a robust immune gene pair-based signature. _Clinical and Translational Medicine_ (2021)

3. Meng, Lu et al. Tumor immune microenvironment-based classifications of bladder cancer for enhancing the response rate of immunotherapy. _Molecular Therapy - Oncolytics_ (2021)

---

## Future Directions

- Spatial transcriptomics for TME architecture
- Single-cell resolution of immune cell states
- Longitudinal monitoring of TME dynamics
- Integration with epigenetic profiling
- Validation in prospective clinical trials
