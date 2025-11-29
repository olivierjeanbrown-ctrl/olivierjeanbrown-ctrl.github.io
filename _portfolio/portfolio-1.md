---
title: "Analysis Portfolio"
excerpt: "My detailed experience with various statistical analyses."
collection: portfolio
---

Behavioural Analyses (R; Mixed-Effects Models)
------

I developed R workflows to clean behavioral datasets, assess assumptions, and fit linear mixed-effects models examining resilience and symptom trajectories. These models tested group × time interactions and associations between behavioral change and imaging outcomes. I used SQL to aggregate and extract variables of interest for organization, time, and efficiency. Scripts demonstrating the workflow are available on my GitHub.
Focus: LME modeling; assumption checks; longitudinal behavioral effects; reproducible R analysis.

Integrated Statistical Modeling (FSL + CONN + R)
------

I preprocessed DTI data using bash scripting in combination with FSL. I then analyzed DTI data (FA, MD, AD, and RD) with FSL’s GLM + TFCE pipeline to test resilience–white matter associations and group moderation (cross-sectional). 
Focus: TFCE-based DTI inference; covariate-controlled moderation models.

White Matter Microstructure (DTI / FSL / TBSS)
------

I processed pediatric DTI data using FSL’s GUI tools to derive FA, AD, RD, and MD metrics. After visual QC, diffusion tensors were fit and analyzed using tract-based spatial statistics (TBSS). Whole-brain voxelwise tests were performed with FSL Randomize (5,000 permutations, TFCE), and significant clusters were identified using the JHU White-Matter Atlas.
Focus: whole-brain microstructure analysis; TFCE permutation testing; atlas-based interpretation.

Resting-State Functional Connectivity (CONN Toolbox)
------

I preprocessed resting-state fMRI using FMRIPrep and CONN’s SPM-based pipeline (realignment, slice timing, segmentation, normalization, smoothing), with motion and structural QC. Connectivity was examined via seed-to-voxel and ROI-to-ROI analyses across DMN, CEN, and SN networks, with RFT/FDR cluster corrections .Resting-state fMRI models in CONN incorporated longitudinal contrasts (72h → 4 weeks) to test resilience × group × time interactions at whole-brain and ROI levels. Follow-up regressions in R clarified interaction effects, slopes, and modality-specific patterns.
Focus: network-level FC (DMN/CEN/SN); whole-brain and ROI analyses; GLM-based longitudinal FC; longitudinal connectivity change.
![Published fMRI Figure Sample](/images/rsfmri.PNG)




