# Heathcare-summary-report-Tableau
Main focus for this project is to create a dashboard in Tableau with heathcare data.

Firstly click on the link [Heathcare summary report](https://drive.google.com/uc?export=download&id=1QZX0ZmXtwq3w0U8HQFC-Zv8MF9tfAaS7) to download a folder which consist data and Tableau file where the dashboard is already created for your reference.

If you have any issue with creating dashboard you can check the file where dashboard is already created, please note all the worksheets are hidden.

# **Steps** 
Connect to the CSV file Healthcare dataset, which includes the data regarding patients’ blood pressure, BMI, glucose, insulin, and diabetes for patients from the 20+ age group.

  View 1:
	 
Diabetic/Non-diabetic using Shapes
	 
   Use Shapes to show the distribution between diabetic/non-diabetic patients.
	 
   Using the “Outcome” field, write a calculated field by classifying 1 as Diabetic patients and 0 as Non-diabetic patients.
	 
   Show the percent distribution as shown in the expected view.
	 
   Use the color of your choice to differentiate Diabetic Vs. Non-diabetic patients.
	 
   Tooltip should display patient count.
	 
   You can use shapes of your choice or use the below one.
	 
   Format as per your choice.
	 
   Enable Action filters.

View 2:

Patient summary by Blood Pressure category

Use any shape of your choice to show patient summary by blood pressure category.

Show the Patient count and BP category type on the labels.

Use the color of your choice to differentiate Diabetic Vs. Non-diabetic patients.

Format as per your choice.

Enable Action filters.

View 3: 

Create a Histogram to show Body Mass Index (BMI) by Age Groups.

Since we need to build a Histogram, using the Age field, let’s create bins using size 5.

In a Histogram, you will have bins 20, 25, 30, etc. So, the bin size 20 will include age groups between 20-24, and size 25 will include 25-29. So, to be clear let’s edit the aliases of the age groups as it might confuse the users. So, let’s use aliases as shown below or you can create a calculated field for the Age groups.

In case, there are missing values, hide them.

Display the average BMI value on top of each bar and round it to 2 decimals.

View 4: 

Single Bar showing percent distribution of patients by BMI type


Create a calculated field to classify Patients by BMI types.
[BMI]<18.5= 'Underweight'

[BMI]>=18.5 and [BMI]<25 ='Healthy Weight'

[BMI]>=25 and [BMI]<30 = 'Overweight'

[BMI]>=30 ='Obese'

Enable Action filters.


Use the average BMI to color the palette using shades of Red.

View 5: 

Bar Chart showing Patient break down by Blood Pressure and Diabetes

Create a calculated field to only highlight Diabetic patients with High and Low blood pressures.

# Conclusion

Once the dashboard is completed you can see filters are properly alligned and you check all the data according to the age group, blood pressure, diabetic or non diabetic.
