---
layout: page
title: Epigenetic Biomarkers in Kidney Cancer
description: Identifying DNA methylation signatures predictive of immunotherapy response in metastatic clear-cell renal cell carcinoma
img: assets/img/epigenetics_ccrcc.jpg
importance: 2
category: work
related_publications: true
---

## Background

Metastatic clear-cell renal cell carcinoma (ccRCC) represents a major clinical challenge, with variable responses to immune checkpoint inhibitors (ICIs). My research addresses the critical need to predict treatment response through epigenetic profiling.

## The BIONIKK Trial

This work is based on the **BIONIKK clinical trial** (NCT02960906), the first academic personalized clinical trial in metastatic ccRCC assessing patient response to:

- Nivolumab monotherapy
- Ipilimumab + Nivolumab (Ipi/Nivo)
- Sunitinib

## Key Discoveries

### 1. Tumor Enhancer Demethylation (TED) Phenotype

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ted_phenotype.jpg" title="TED phenotype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

**Key findings**:

- Identified a novel ccRCC subgroup defined by tumor enhancer demethylation
- Strongly associated with **primary resistance** to first-line Ipi/Nivo therapy
- Characterized by aggressive clinical features and poor outcomes
- Frequent sarcomatoid differentiation

**Molecular mechanisms**:

- TET1 promoter demethylation
- Activation of epithelial-mesenchymal transition (EMT)
- IL-6/JAK/STAT3 signaling activation
- Distinctive TME: immune activation + immunosuppression, fibroblast enrichment, endothelial depletion

**Publication**: Lu et al., _Clinical Cancer Research_ (2022)

### 2. Epigenetic Silencing Index (iMES)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/imes_framework.jpg" title="iMES framework" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

**Objective**: Predict primary resistance to immune checkpoint inhibitors

**Approach**:

- Developed a methylation-based epigenetic silencing index (iMES)
- Validated across independent ccRCC cohorts
- Robust predictor of immunotherapy response

**iMES-high tumor characteristics**:

- Non-permissive tumor microenvironment
- Concurrent immune activation and suppression
- EZH2 activation
- Frequent BAP1 or SETD2 alterations
- Epigenetic silencing of VEGF receptor genes
- Reduced endothelial component in TME

**Clinical significance**: Challenges the prevailing belief that ccRCC with angiogenic signature benefits solely from anti-angiogenic agents

**Publication**: Lu et al., _Cell Reports Medicine_ (2023)  
**Software**: [iMES R package](https://github.com/xlucpu/iMES)

## Clinical Impact

These complementary epigenetic biomarker frameworks enable:

- **Robust prediction** of immunotherapy response
- **Treatment stratification** for personalized therapy selection
- **Mechanistic understanding** of resistance mechanisms

## Recognition

- **Editorial**: Zhou and Kim, _Clinical Cancer Research_ (2023) - "Viewing RCC with a DNA Methylation Lens ENHANCES Understanding of ICI Resistance"
- **Oral presentations**:
  - ARC Symposium for Signatures in Cancer Immunotherapy (Paris, 2023)
  - 1ères Journées de recherche en Immuno-Oncologie (Strasbourg, 2025)
  - 12th FMTS Scientific Meeting (Strasbourg, 2025)
- **Award**: Young Researcher Oncology Prize (2025)

## Future Directions

The identification of TED and iMES provides a foundation for:

- Epigenetic biomarker-driven clinical trials
- Development of combination therapies targeting epigenetic vulnerabilities
- Personalized treatment selection in metastatic ccRCC
