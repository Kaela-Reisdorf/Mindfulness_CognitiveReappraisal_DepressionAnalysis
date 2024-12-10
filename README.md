# Mindfulness and Cognitive Reappraisal as predictors of Depression: A Secondary Analysis of the Replication Study of Troy et al. (2017) University of Minnesota - Twin Cities
This project explores the relationship between mindfulness, depressive symptoms, habitual cognitive reappraisal, and cognitive reappraisal strategies.

## Background
The dataset is from a replication study conducted at the University of Minnesota - Twin Cities. All analyses are conducted based off the subset "troyAnalysis_subset" pulled from the original dataset.

## Features
**Data Source**: Replication Study of Troy et al. (2017) University of Minnesota - Twin Cities

**Research Focus**: 
1. Mindfulness as a moderator in the relationship between cognitive reappraisal and depression symptoms. 
    Hypothesis: Individuals will show a stronger negative relationship between cognitive reappraisal and depressive symptoms as there levels of mindfulness increase.
   
2. Habitual cognitive reappraisal as a mediator in the relationship between mindfulness and depressive symptoms.
    Hypothesis: As HCRA and Mindfulness increase, depressive symptoms decrease.

3. Cognitive reappraisal and mindfulness as independent predictors to depressive symptoms.
    Hypothesis: CRA & mindfulness independently predict depressive symptoms.
   
**Tools Used**: Rstudio for data scrubbing, analysis, and visuals.

## Data Details
The subset focuses on the following measures:

-**Mindfulness Attention Awareness Scale** 

-**Cognitive Reappraisal Ability (CRA) Questionnaire**

-**Habitual Cognitive Reappraisal Use (ERQ subscale)**

-**Depressive Symptoms (CES-D)**

Additional columns include demographic information.

## Usage
1. Be sure R is installed and download items from repository
2. Install required R packages (tidyverse, dplyr, ggplot2, emmeans, rempsyc, easystats, interactions, mediation)

## Results
- Mindfulness has a significant direct effect to depressive symptoms.
- Mindfulness showed no significance as a moderator to cognitive reappraisal and depressive symptoms.
- Habitual cognitive reappraisal showed no significance as a mediator to mindfulness and depressive symptoms.

## Limitations
- Limited in sample size, impacting generalizability
- Self-reported measures are subject to bias
