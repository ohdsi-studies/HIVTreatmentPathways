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
- A Database in the Common Data Model (atleast Version 5)
- Configured ATLAS Environment with capability to execute CohortPathways and Characterization Tools


### **1. Import Study Specifications**

Import the following specifications for each analysis into the ATLAS environment by copying and pasting json txt provided into the Utilities, Import Tab for each analysis:

- Cohort Pathway 1: **[Single Ingredient Antiretrovirals](https://github.com/ohdsi-studies/HIVTreatmentPathways/blob/master/StudySpecifications/HIV_Single_CP.txt)**
- Cohort Pathway 2: **[Combination Antiretroviral Medications](https://github.com/ohdsi-studies/HIVTreatmentPathways/blob/master/StudySpecifications/HIV_Combo_TP.txt)**

- Characterization: **[Characterization](https://github.com/ohdsi-studies/HIVTreatmentPathways/blob/master/StudySpecifications/HIV_Characterization.txt)**


### **2. Execute Cohort Pathway 1, Cohort Pathway 2, and Characterization on CDM Transformed Database**
Facilitate the analysis under the Execution tab and click Generate

### **3. Return csv Results Files**

Upload the following results files to the study coordinator 
- pathways
- EventCohortCounts
- DistinctEventCohorts
- All Characterization Results




