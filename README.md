"# Tableau_Assignment1" 
Import Titanic Passenger List  csv file into tableau
Cleaned the Data by data Interpreture

Open Worksheet1
Create 1st histogram plot for " Survival Rate Per Class" 
Drag PClass into column & No of records measure to rows
Apply 'Quick table Calculation' to no of records and select 'percentage of Total'
Next Ctrl + drag no of records to 'Label' Marks
Again apply 'Quick table Calculation' to no of records and select 'percentage of Total'
Add Sex into 'filter'
Edit Axis as 'Survived[%]' & Hide 'PClass'
Rename Workbook1 as " Survival Rate Per Class" 

Open Worksheet2 
Create 2nd histogram plot for "Fare Per Passenger " 
Here 1st create bins of fare values to identify easily 
Select Fare Dropdown and select 'create' to 'bins'
Drag 'Fare(Bins)' & 'PClass' to column
'Fare' measures into rows as 'CNT(Fare)' by clincking dropdown and select measure as count
Ctrl + Drag 'CNT(Fare)' to Lebel Marks & 'Sex' dimension to Color Marks
Apply Filter to 'Sex' Dimension
Edit Axis as 'Count Of Passenger' & Hide 'PClass'
Rename Workbook2 as "Fare Per Passenger" 

Open Worksheet3 
Create 3nd histogram plot for "Survival Count Of Different Age Group " 
Here 1st create bins of Age values to identify easily 
Select Age Dropdown and select 'create' to 'bins'
Drag 'Age(Bins)' to column
'Age' measures into rows as 'CNT(Age)' by clincking dropdown and select measure as count
Ctrl + Drag 'CNT(age)' to Lebel Marks & 'Sex' dimension to Color Marks
Apply Filter to 'Sex' Dimension
Hide 'PClass' title
Rename Workbook3 as "Survival Count Of Different Age Group"


1St Goto 'Data Source' and split name column and rename as 'First Name', 'Title' & 'Last Name'
Open Worksheet4
Drag 'First Name', 'Title' & 'Last Name' into rows and 'Survived' into column
Ctrl + Drag 'Survived' from column into 'Color' Marks
Apply Filter to 'Sex' Dimension
Rename Workbook4 as "Passenger List"
