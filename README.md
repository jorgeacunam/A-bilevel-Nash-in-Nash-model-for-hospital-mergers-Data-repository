# A-bilevel-Nash-in-Nash-model-for-hospital-mergers-Data-repository
Dataset to run the baseline scenario and instructions to generate the alternative scenarios.

## Tables
The excel file attached to this repository contains five different tables representing the backbone to replicate the analysis presented in the manuscript. 

## Data
The following is the list of tables and descriptions:

Hospitals data (TABLE 1):  
  1) Set of insurers' networks (Parameter z_ij). 1 if the hospital is in-network, 0 otherwise.   
  2) Quality of care (score).
  3) Distance to patients of purchasing power class alpha (score).
  4) Set of health systems. 1 if the hospital belongs to the health system, 0 otherwise.
  5) Cost of treating a patient with diagnosis k. Two datasets need to be purchased (SID and CCR)\
   https://www.hcup-us.ahrq.gov/db/state/siddbdocumentation.jsp \
   https://www.hcup-us.ahrq.gov/db/ccr/costtocharge.jsp
  
Diagnosis data (TABLE 2):  
  1) Severity weight applied to reimbursement rates (w_k).
  2) Probability of needing treatment with diagnosis k. One dataset needs to be purchased (SID)\
   https://www.hcup-us.ahrq.gov/db/state/siddbdocumentation.jsp
  
Metal data (TABLE 3):  
  1) Maximum acceptable policy price per metal level. 

Patients data (TABLE 4):  
  1) Demand of customers (1.2 million) in Hillsborough County per purchasing power class alpha. One dataset needs to be purchased (SID) https://www.hcup-us.ahrq.gov/db/state/siddbdocumentation.jsp 
  2) The purchasing power class is based on the median household income of each patient.
  
Insurer data (TABLE 5):  
  1) Net income rate of each insurer.
  2) Weight or importance assigned by customers of class alpha to each insurer's network.
  3) Weight or importance assigned by customers of class alpha to the premium of each insurer. 
  
Instructions to generate alternative scenarios:
 1) A set of instructions is included in the excel file to modify the dataset and replicate the alternative scenarios
    
Feel free to contact me if you have any questions about implementation.
