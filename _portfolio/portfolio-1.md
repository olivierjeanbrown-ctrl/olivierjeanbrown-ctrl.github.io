---
title: "Analysis Portfolio"
excerpt: "A description of my experience with various statistical analyses."
collection: portfolio
---

White Matter Microstructure (DTI / FSL / TBSS)
------

I processed pediatric DTI data using FSL’s GUI tools to derive FA, AD, RD, and MD metrics. After visual QC, diffusion tensors were fit and analyzed using tract-based spatial statistics (TBSS). Whole-brain voxelwise tests were performed with FSL Randomize (5,000 permutations, TFCE), and significant clusters were identified using the JHU White-Matter Atlas.
Focus: whole-brain microstructure analysis; TFCE permutation testing; atlas-based interpretation.

Resting-State Functional Connectivity (CONN Toolbox)
------

Resting-state fMRI was preprocessed using CONN’s SPM-based pipeline (realignment, slice timing, segmentation, normalization, smoothing), with motion and structural QC. Connectivity was examined via seed-to-voxel and ROI-to-ROI analyses across DMN, CEN, and SN networks, with RFT/FDR cluster corrections.
Focus: network-level FC (DMN/CEN/SN); whole-brain and ROI analyses; longitudinal connectivity change.

Integrated Statistical Modeling (FSL + CONN + R)
------

DTI data were analyzed with FSL’s GLM + TFCE pipeline to test resilience–white matter associations and group moderation (cross-sectional). Resting-state fMRI models in CONN incorporated longitudinal contrasts (72h → 4 weeks) to test resilience × group × time interactions at whole-brain and ROI levels. Follow-up regressions in R clarified interaction effects, slopes, and modality-specific patterns.
Focus: TFCE-based DTI inference; GLM-based longitudinal FC inference; covariate-controlled moderation models.

Behavioural Analyses (R; Mixed-Effects Models)
------

I developed R workflows to clean behavioral datasets, assess assumptions, and fit linear mixed-effects models examining resilience and symptom trajectories. These models tested group × time interactions and associations between behavioral change and imaging outcomes. Scripts demonstrating the workflow are available on my GitHub.
Focus: LME modeling; assumption checks; longitudinal behavioral effects; reproducible R analysis.
