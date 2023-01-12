Characterizing Patterns in Antiretroviral Therapy for Individuals with Human Immunodeficiency Virus (HIV)
=============

<img src="https://img.shields.io/badge/Study%20Status-Repo%20Created-lightgray.svg" alt="Study Status: Repo Created">

- Analytics use case(s): **Characterization**
- Study type: **Clinical Application**
- Tags: **OHDSI, HIV, Antiretroviral Therapy**
- Study lead: **Raechel Davis**
- Study lead forums tag: **[redavis](https://forums.ohdsi.org/u/[redavis])**
- Study start date: **January 2023**
- Study end date: **-**
- Protocol: **[HIV_TP](https://github.com/ohdsi-studies/HIVTreatmentPathways/tree/master/documents)**
- Publications: **-**
- Results explorer: **-**

The purpose of  this study is to characterize and evaluate trends in antiretroviral therapy for individuals who have been diagnosed with Human Immunodeficiency Virus. The analysis package has been developed using the CohortPathways and Characterization tools in ATLAS and will be performed in the ATLAS environment.

How to run
=============
### **Requirements:**
- A Database in Common Data Model Version 5
- Configured ATLAS Environment
- ATLAS CohortPathways and Characterization Tools


### **1. Import Study Specifications**

Import the following specifications for each analysis into the ATLAS environment by copying and pasting json txt provided at the following links into the Utilities, Import Tab for each analysis:

- Cohort Pathway 1: **[Single Ingredient Antiretrovirals](https://github.com/ohdsi-studies/HIVTreatmentPathways/blob/master/Study%20Specifications/HIV_Pathway_Single_Ingredient.txt)**
- Cohort Pathway 2: **[Combination Antiretroviral Medications](https://github.com/ohdsi-studies/HIVTreatmentPathways/blob/master/Study%20Specifications/HIV_Pathway_Combo.txt)**

- Characterization: **[Characterization](https://github.com/ohdsi-studies/HIVTreatmentPathways/blob/master/Study%20Specifications/HIV_Characterization.txt)**


### **2. Execute Cohort Pathway 1, Cohort Pathway 2, and Characterization on CDM Transformed Database**


### **3. Return csv Results Files**

Upload the following results files to the study coordinator 
- pathways
- EventCohortCounts
- DistinctEventCohorts
- Condition Group Era Any Time Prior
- Demographics Ethnicity 
- Demographics Age Group 
- Demographics Race
- Demographics Gender
- Demographics Age 
- Demographics Index Year




