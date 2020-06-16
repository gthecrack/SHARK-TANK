# SHARK-TANK

# THE PROJECT

    **CLEANING A DATA SET**
    
        The SHARK-TANK PROJECT aims to look into a given dataset that contains noisy information about shark attacks all over the world dating back many years. For this reason the information is not standarized and our work is to get rid of any data that pollutes our results.
        
    **THE TARGET**
    
        Our focus will be directed towards extracting *DATED* attacked instances by Month and Year in order to establish a seasonal occurrence of the attacks. We will also look into the geographical position of the attacks and how they distribute in the same seasonal fashion as before.
        
    **THE PROCESS**
    
        * IMPORT MODULES REQUIRED TO PROCESS THE DATA
        * CHECKING THE COLUMNS TO ASSESS THE DATA
        * LOOKING AT AMOUNT OF NaN VALUES AMONG THE DIFFERENT COLUMNS
        * REMOVAL OF ROWS FULL OF NaN VALUES
        * DROPING COLUMNS WITH DUPLICATE OR IRRELEVANT INFORMATION
        * RENAMING MISPELLED COLUMNS
        * EXTRACTING MM/YY FORMAT FROM DATE
        * WE SPLIT THE MM/YY FORMAT IN TWO SEPARATE COLUMNS
        * WE DROP PREVIOUS DATE COLUMNS AND GET RID OF ROWS THAT ARE COMPLETELY FULL OF NaN VALUES
        * WE COUNT THE ATTACKS PER COUNTRY AND KEEP THOSE WITH MORE THAN 100 INSTANCES
        * WE CREATE A DATAFRAME WITH THE VALUES FROM THE SELECTED COUNTRIES AND DROP THE REST OF THE VALUES
        * WE CREATE A COLUMN WITH THE HEMISPHERE TO WHICH THE COUNTRIES BELONG
        * WE APPLY A DEFINED FUNCTION THAT RETURNS THE SEASON IN WHICH THE ACCIDENT HAPPENED
        * WE APPLY A FUNCTION THAT SEPARATES FATAL INSTANCES BY YES/NO/UNKNOWN
        * WE CREATE A SMALLER DATAFRAME TO WORK WITH
        * WE KEEP THE FATAL INSTANCES EQUAL TO YES TO LOOK AT THE MORTALITY BETWEEN COUNTRIES AND SEASON OF THE ATTACK
        * WE PLOT THE DATA
        * WE CRATE AND EXPORT THE FINAL DATASET
        
     **AUTHOR**
     
         **GERMAN LINARES**