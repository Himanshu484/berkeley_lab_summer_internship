
# Leveraging LLM-Generated Embeddings for Topic Modeling and Survival Analysis of Obstructive Sleep Apnea Patients

**Summer 2024 Research Project**  
**Lawrence Berkeley National Laboratory - Applied Mathematics and Computational Research Division**

## Data and Code Access Restrictions

**IMPORTANT**: The data and code for this project are **RESTRICTED FOR PUBLIC ACCESS** due to:
- Sensitive clinical data privacy requirements
- MIMIC-IV database access restrictions requiring credentialing
- Institutional policies at Lawrence Berkeley National Laboratory
- HIPAA compliance and patient confidentiality protections

This repository contains **only** the research poster and presentation materials.

## Overview

This repository contains the poster and presentation materials from my summer internship research project at Lawrence Berkeley National Laboratory. The work focuses on analyzing clinical narratives from Obstructive Sleep Apnea (OSA) patients using advanced topic modeling techniques and survival analysis [1].

## Research Summary

### Background
Obstructive Sleep Apnea (OSA) is a prevalent sleep disorder affecting breathing during sleep and leading to severe health issues like cardiovascular disease and hypertension [1]. This study leveraged the MIMIC-IV database to analyze clinical narratives from discharge notes of OSA patients [1].

### Methodology
- **Dataset**: 51,865 clinical notes from 14,915 OSA patients (8,918 male, 5,997 female) [1]
- **Computational Resources**: Utilized the Perlmutter supercomputer for large-scale data processing
- **Topic Modeling**: Applied BERTopic with GatorTron embeddings for clinical text analysis [1]
- **Analysis Techniques**: Combined topic modeling with Kaplan-Meier survival analysis [1]

### Key Findings
- **Topic Identification**: Initially identified 350 topics, refined to 166 distinct categories through hierarchical clustering [1]
- **Clinical Themes**: Identified key themes including:
  - Neurological symptoms
  - Cardiac issues  
  - Surgical procedures
  - Psychiatric concerns
  - Dehydration symptoms [1]
- **Temporal Analysis**: Revealed evolution of clinical themes from 1987 to 2012, showing increased focus on cardiovascular complications [1]
- **Survival Analysis**: Different clinical themes showed varying impacts on patient survival rates over 12 years [1]

### Research Hypothesis
Advanced topic modeling using Large Language Models, combined with survival analysis, can uncover critical clinical themes and significant factors that affect patient outcomes in OSA management [1].

## Repository Contents

**Poster**: Research poster presented at the Computing Sciences Summer Session  
**Presentation**: Slides from the summer research presentation

## Data and Code Restrictions

**The underlying dataset and analysis code are NOT available in this repository and are RESTRICTED FOR PUBLIC ACCESS due to:**

- **Clinical Data Privacy**: MIMIC-IV contains sensitive patient health information
- **Institutional Policies**: Lawrence Berkeley National Laboratory access restrictions
- **Regulatory Compliance**: HIPAA and other healthcare data protection requirements
- **Database Licensing**: MIMIC-IV requires proper credentialing and institutional approval

**For data access**: Researchers must apply directly to PhysioNet for MIMIC-IV database access with appropriate credentials and institutional approval.

## Research Impact

This work provides novel insights into OSA management and identifies significant factors affecting patient survival, with potential applications for:
- Tailored treatment strategies for OSA patients
- Improved clinical decision-making
- Enhanced understanding of OSA comorbidities and their temporal evolution

## Acknowledgments

- **Institution**: Lawrence Berkeley National Laboratory, Applied Mathematics and Computational Research Division
- **Computational Resources**: Perlmutter supercomputer
- **Database**: MIMIC-IV clinical database
- **Collaborator**: Destinee Morrow, Lawrence Berkeley National Laboratory [1]

---

*This research was conducted during Summer 2024 as part of the Computing Sciences Summer Session at Lawrence Berkeley National Laboratory.*

**Note**: Only poster and presentation materials are shared in this repository. Data and code remain restricted for public access.
