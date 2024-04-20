# Bike_buyers_analysis (It was a Guided Project)
Following includes the documentation of analysis of the "Bike buyers dataset" which was performed using MS. Excel.

## DATA CLEANING AND PREPARATION

   1. First I identified and removed duplicate records from the dataset. For doing this I select all the data and used remove duplicates function in excel.
   
   2. In this dataset, they have used short forms for the data in  Marital Status ('M' and 'S') and the Gender ('M' and 'F') column which is not good from the perspective of person seeing the dashboard.
      So, To fix this I selected the Marital Status column and used 'Find and Replace' tool by pressing 'Ctrl + H' then i replaced value 'M' for 'Married' and 'S' for 'Single'. I followed same process for the 
      Gender column where i replaced 'M' for 'Male' and 'F' for 'Female'.

   3. Removed Decimal Places from the 'Income' column.  

   4. Checked other columns for spelling errors using filter icon.
   
   5. In Age column there are various values or ages for people. But these values are of little or no use. Because there are so many ages, It will be easy for us to grouped them into Age bracket for using in 
      analysis. So, I created an Age bracket column and using nested IF function to group them: =IF(L2>54,"Old", IF(L2>=31,"Middle Age", IF(L2<31,"Adolescent","Invalid"))).


## DATA ANALYSIS

   Performed data analysis using pivot tables and pivot charts.
   
   1. Created pivot table to basically look at average income of somebody who either bought or did not buy a bike.

       ![1st pivot table](https://github.com/SparshMishra42/Bike_buyers_analysis/assets/143194226/16260d90-8310-4f2e-9f75-c85bc75204df)

   3. Created second pivot table to show the commuting distance of the person buying bike.

       ![2nd pivot table](https://github.com/SparshMishra42/Bike_buyers_analysis/assets/143194226/ff2add77-7131-45e5-a369-ba5225a8eab5)

   5. Final pivot table to find persons in which age bracket purchases a lot of bikes. 

       ![3rd pivot table](https://github.com/SparshMishra42/Bike_buyers_analysis/assets/143194226/d74177b9-767f-4bc7-98c4-08477987be05)


## INSIGHTS


