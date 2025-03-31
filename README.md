# Predictive modeling to uncover Parkinson’s disease characteristics that delay diagnosis

This repository contains the relevant source code used in the publication:

**Predictive modeling to uncover Parkinson’s disease characteristics that delay diagnosis** (Tom Hähnel, Tamara Raschka, Jochen Klucken, Enrico Glaab, Jean-Christophe Corvol, Björn H. Falkenburger & Holger Fröhlich. npj parkinson's disease. 2025. DOI: 10.1038/s41531-025-00923-2).

Please refer to this publication for further information.

The repository contains the following code:

**calc_baseline_symptoms.Rmd**: Code for calculating the correlations of baseline symptoms with patient-reported time to diagnosis and subsequent metaanalyses.

**calc_metaanalyses.Rmd**: Code for calculating meta-analyses of demographic and clinical features across the three study cohorts.

**calc_predict_timezero.Rmd**: Code for calculating the correlations of predicted symptoms at time=0 on the common disease timescale with model-derived timeshifts as well as subsequent meta-analyses.

**outcomes_categories.csv**: Mapping of clinical scores to clinical domains used within the other scripts.

Note, that the code is constructed so that parts of the analysis can be run independently. This allows for execution on separate machines, since the three datasets are, at least in part, only available on remote machines. Therefore, intermediate results must be copied between local and remote machines.

Additional code for training the Latent time joint mixed-effects model (LTJMM) and the progression subtypes can be obtained from https://github.com/SCAI-BIO/PD-progression-types and the corresponding publication **Progression subtypes in Parkinson’s disease identiﬁed by a data-driven multicohort analysis** (Tom Hähnel, Tamara Raschka, Stefano Sapienza, Jochen Klucken, Enrico Glaab, Jean-Christophe Corvol, Björn H. Falkenburger & Holger Fröhlich. npj parkinson's disease. 2024. DOI: 10.1038/s41531-024-00712-3).
