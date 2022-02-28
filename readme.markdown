readme.markdown

# Pharmacy Stock Kata


## Table of contents

1. Introduction
2. Requirments
3. Description
4. Running an application


# Introduction

* The application Pharmacy Stock Kata is developed using java script where this application consist the medical Inventory that Displays the list of medications that are in the stock so that the medication could dispensed to the patients and also understand when we need to order more medications from suppliers.

# Requirments

* The application requirments are classified into scenarios where we are able to check medications available in the pharamcy and also the medical inventory

## Scenario - 1

* Provides a pharmacist a list of medications in his formulary so that the medicationns could be dispensed to his patients 
  
  ### Asumptions :
  1. The name of the medication acting as a unique Identifier 
  2. Medication cannot be added to the formulary more than once
   
  ### Acceptance Criteria :
  1. Ability to add the name of the medication to the formulary 
  2. Ability to return a list of medication names in the formulary

## Scenario- 2

* Provides a pharamacist the ability to add medication to the inventory.so that to maintain stock levels of medications in formulary and to understand when is the need to order more medication from supliers.
  
 ### Assumptions :
 1. only medication in the formulary can be added to the stock 
 2. All medications are tablets and stocked in packs of the same strength.
 3. only these packs provided into the sample data list should be used.

### Aceptane Criteria :
1. Ability to add packs for medications already in the formulary list.
2. Ability to list the medications in stock and the quantities.
   
## Sample Data

|      Medication Name       |       Strength     |       Pack size        |
|:---------------------------|:------------------:|-----------------------:|
|  Amoxicillin               |  250mg             |        20              |
|Codeine                     |    30mg            |      10                |
|  Dicloenac                 |       250mg        |       25               |
| Ibuprofen                  |           500mg    |       50               |
| Paracetamol                |       500mg        |      50                |
| Simvastatin                |       10mg         |      10                |
|  Tramadol                  |      50mg          |     100                |
|      Warfarin              |       3mg          |         50             |

# Description :

* Application has been coded based on the scenario informations following the steps given
 1. Add Paracetamol and ibuprofen to formulary
 2. Add Amoxicillin to formulary
 3. Add Codeine, Diclofenac, Simvastatin, Tramadol to formulary
 4. List the names of the Medications in the formulary

* placed the java script as the headtag and by taking an array to store each formulary value
 ### Example : 
   * Add paracetmol and ibuprofen to formulary
     formulary [0] = " Paracetamol";
     formulary [1] = " Ibuprofen";

* Also performed unique operation to an array to allow unique values 
  ### Example : {const unique formulary = [...newset(formulary]}

* Added each formulary to an array and returned list of formularies.
1. Add 100 packs of 50x500mg Paracetamol
2. Add 100 packs of 50x500mg Ibuprofen
3. Add 20 packs of 20x250mg Amoxicillin
4. Add 5 packs of 100x50mg Tramadol
5. Add 20 packs of 10x30mg Codeine
6. Add 10 packs of 10x10mg Simvastatin
7. Add 5 packs of 50x3mg Warfarin
8. List the name, strength, packsize and the total number of packs for all the medication in stock.
### Example output in figure 1 below

|  ## Name       | ## Strength  | ## Pack Size   |  ## Total Packs |
|:---------------|:------------:|:--------------:|----------------:|
| ##Medication A| 1 mg         | 5              |          10     |
| ##Medication B| 5 mg         |  10            |         2       |

* Added each packs to medication and added total paccks 
* output to console
  
# Running Application
   
1. Download the source code and extract the zip file
2. Download or set up any web browser ( Chrome, Safari) that runs java script
3. Dpen the html file located in the source code 
4. The output for the first scenario is available in the console which can be opened using web development in web browser.
5. Refreshing the link in the tab provides the output for second scenario.
 




