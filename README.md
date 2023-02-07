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
- Protocol: **[HIV Treatment Pathway](https://github.com/ohdsi-studies/HIVTreatmentPathways/blob/master/documents/HIV_TP_OHDSI_StudyProtocolTemplateV4.docx)**
- Publications: **-**
- Results explorer: **-**

The purpose of  this study is to characterize and evaluate trends in antiretroviral therapy for individuals who have been diagnosed with Human Immunodeficiency Virus. The analysis package has been developed using the CohortPathways and Characterization tools in ATLAS and will be performed in the ATLAS environment.

How to run
=============
### **Requirements:**
- A Database in the Common Data Model (>= Version 5)
- Configured ATLAS Environment with capability to execute CohortPathways and Characterization Tools


### **1. Import Study Specifications**

Import the following specifications for each analysis into ATLAS by copying and pasting json .txt provided into the Utilities, Import Tab for each analysis:

- Cohort Pathway 1: **[Single Ingredient Antiretrovirals](https://github.com/ohdsi-studies/HIVTreatmentPathways/blob/master/StudySpecifications/HIV_SingleIngred_Pathway.txt)**
- Cohort Pathway 2: **[Combination Antiretroviral Medications](https://github.com/ohdsi-studies/HIVTreatmentPathways/blob/master/StudySpecifications/HIV_Combination_Pathway.txt)**

note: the minimum cell count default is 1

- Characterization: **[Characterization](https://github.com/ohdsi-studies/HIVTreatmentPathways/blob/master/StudySpecifications/HIV_Characterization.txt)**


### **2. Execute Cohort Pathway 1, Cohort Pathway 2, and Characterization on CDM Transformed Database**
Facilitate the analysis under the Execution tab and click 'Generate'

### **3. Return csv Results Files**

Share the following .csv results files with the study coordinator (Raechel): 
- pathways
- EventCohortCounts
- DistinctEventCohorts
- All Characterization Results files

A secure file transfer protocol can be implemented to facilitate the sharing of the results files as requested by data partners- please reach out to raechel.davis@yale.edu



