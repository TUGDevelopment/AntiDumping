Read me first

================
SSIS
================
-Initial_Prod is Step 1 to interface Material code from Initial excel file and then update file from Update excel file to generate CONNUM code ->CONNUM BI Report(ConnumG3_Prod.pbix)
-ADG3_PROD is Step 2 to interface sales data both Domestic and Export transaction data to SQL DB then calculate for anti dumping price ->AntiDumpingG3_Prod.pbix

------------------------------------------------------------------------
================
Power BI Report
================
ConnumG3_Prod.pbix 
	--> Generate CONNUM Code and leave admin can export CONNUM List in excel format
AntiDumpingG3_Prod.pbix 
	--> Calculate and compare Domestic sale price and Export sale price and get highest price in domestic and lowest price in Export
and let's admin to re-check to ensure will no export price is lower than local sales