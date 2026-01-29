**TITLE:**
PEDIATRIC LUPUS FLARE PREDICTION WITH GENE-EXPRESSION DATA USING MACHINE LEARNING

**Abstract:**
Systemic Lupus Erythematosus (SLE) is an autoimmune disease that affects both children and adults.  Younger people with SLE tend to have greater disease severity and progression.  One of the difficulties of properly treating this condition is the unpredictability of “flares”, or periods of sudden worsening of symptoms.  Frequent flares are associated with progressive organ damage and worsening health.  Currently, there is no reliable way to predict flares.  Studies have shown that numerous gene activities are associated with lupus pathophysiology.  Therefore, this study explores whether changes in gene-expression patterns up to 90 days before flare onset can help predict lupus flares.  To explore this, longitudinal pediatric lupus gene-expression data obtained from the publicly available NCBI-GEO database was preprocessed, feature-selected, and then used to train common classification machine learning models.  Each model’s performance was then evaluated on the held-out test data sets.  The average number of days between office visits that were used to assess lupus pre-flare status was 44.5 days.  The superior performance of linear models compared to nonlinear ones in this study suggest that predictive patterns for flares exist and are driven largely by distributed, additive gene-expression patterns rather than sparse, threshold-based, highly interactive, or complex ones.  Future studies should further develop and validate linear models for lupus flare prediction.  If successful, these models can provide a valuable window of time for medical intervention which can potentially prevent or reduce the severity and impact of flares.

**Dataset:**
NCBI GEO: GSE65391 (Illumina HumanHT-12 v4.0, GPL10558)

**Notebooks:**
1. loading + preprocessing data
2. feature selection
3. ML model training + evaluation

