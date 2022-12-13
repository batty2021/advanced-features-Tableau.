# advanced-features-Tableau.
Learn advanced techniques on interpreting the data and preparing them for analysis using Tableau Desktop 

# EXERCISES:
- create a top ten list
- create a route map
- create animated bar charts and scatttor plots
- create complex charts , like calender charts, and area charts 
- create dashboard with a sankey diagram that includes actions

to create calculated fields we should do;
  - Adjust chart depths
  - filter unwanted points
  - apply multiple functions
  TO do;
  - the filters set by user
  - the values avilable in the field
 
 PARAMETERS are a workbook variable. it coluld be;
   - Number
   - Date/time
   - Boolean
   - String
  - Parameters are User-Generated Values , it controles an indivisual view . by utlizing the parameter a user can change
  measures , dimentions as well as provide dynamic filters in a report without having to compromise the structure of the 
  original data source. 
  - parametrs only exist within the workbook so they do not change the original data , we can also use it anywhere in a 
  workbook weather that be as a view or as a dashboard
  
  # how do parameters differ from Filters?
  Prameters are Quicker than filters because they are retained in memory. However filters ping your data sources every time
  they are used, interms of coverage parameters can be used at any place within  a workbook while filters are specific to indivisuals 
  sheets or vies unless they are added to a dashboard which then reqires further configuration on linking when choosing values parameters 
  can only handle a single value in contrast to filters which can handle multiple selections, lastly parametrs can be used in canculations whereas
  Filters cannot.
  # PARAMETRS sample use cases;
  - Static filter 
  - Top N
     - Dynamic date dimension
     - Dynamic chart measure
     
  # LOD(Level of Detail) Exppressions
   - Alters how specific or how broad a visualization or data set can be.
   - Controls over the level of granularity you want to compute on a calculated field.
   - Enables users to apply aggregations that have different granularities compared to that of the current visualizations.
   - shows 2 measures with different leveles on the same view.
 - 3 types of LOD Expressions
    - Fixed 
    - Include 
    - Exclude
    
    # GROUPS 
     - are useful for highlighting certain memebers
     - correct data errors or combine dimention memers from the data sources
     - will not change the original data sources
     
     # SETS
      - are custom fields that define a subset of data based on some conditions. can be either FIXED or DYNAMIC.
      
    # Difference between the two  
  # GROUPS	                                                                                                             

•	Manual	                                                                                                           
•	Can take in both dimensions & measures	                                                                          
•	Processed like dimension filters	                                                                                 
•	Can be combined 	                                                                                                 
•	Can not 	                                                                                                         
     
  #	SETS

•	Fixed/Dynamic

•	Can only handle Dimensions

•	Processed before dimension filters

•	Has multiple combination methods 

•	Can be used on expressions & operations

     
    
    
    
    
   
   
   
   
   
   
  
  
  
  
  
   
