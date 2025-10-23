# Healthcare Data in SQL and Visualization in Tableau

This healthcare analytics project uses SQL queries to explore various use cases such as patient volumes, emergency room throughput, and procedures.

The sample data is generated from Synthea and not associated with a specific electronic healthcare record platform. This data is not reflective of any current or past performance or clinical data for any patient, health system, insurance provider, or any other entity. All data is fake and made available for educational purposes only.

In this project first of all I look at volumes, which give an idea of how much activity is going on with the healthcare system and help identify opportunities for growth or where further support might be needed.

Sample questions:

1.How many encounters did we have before the year 2020?

2.How many distinct patients did we treat before the year 2020?

3.How many distinct encounter classes are documented?

4.How many inpatient/ ambulatory encounters did we have before the year 2020?

Then I look at who our patients are.

Sample questions:

1.What is our patient mix by gender, race and ethnicity?

2.What about age?

3.How many states and zip codes do we treat patients from?

4.Which state, zip, and county do we treat the most patients from?

5.What is our patient mix for patients who had an inpatient encounter in 2019?

6.How many inpatient encounters did we have in the entire dataset where the patient was at least 21 years old at the time of the encounter start?

Next, I'd like to know what is happening in the ER. I check ER throughput (a key indicator of volume, patient access, and system’s ability to support its community).

Sample questions:

1.How many emergency encounters did we have in 2019?

2.What conditions were treated in those encounters?

3.What was the emergency throughput and how did that vary by condition treated?

4.How many emergency encounters did we have before 2020?

5.Which condition was most documented for emergency encounters before 2020?

6.How many conditions for emergency encounters before 2020 had average ER throughputs above 100 minutes?

Next, I want to see what cost of care looks like for our patients. Because cost of care varies by many factors including care received and healthcare insurance coverage. The financial impact of these costs can significantly affect each patient.

Sample questions:

1.What is total claim cost for each encounter in 2019?

2.What is total payer coverage for each encounter in 2019?

3.Which encounter types had the highest cost?

4.Which encounter types had the highest cost covered by payers?

5.Which payer had the highest claim coverage percentage (total payer coverage/ total claim cost) for ambulatory encounters before 2020?

6.Then I look at what procedures we are performing. Many patient treatments may involve various procedures. Analyzing this information can help us identify 

.what procedures are needed most to guide further expansion of support to meet evolving healthcare needs.

Sample questions:

1.How many different types of procedures did we perform in 2019?

2.How many procedures were performed across each care setting (inpatient/ambulatory)?

3.Which organizations performed the most inpatient procedures in 2019?

4.How many Colonoscopy procedures were performed before 2020?

5.Compare our total number of procedures in 2018 to 2019. Did we perform more procedures in 2019 or less?

6.Which organizations performed the most Auscultation of the fetal heart procedures before 2020?

7.Which race had the highest number of procedures done in 2019?

8.Which race had the highest number of Colonoscopy procedures performed before 2020?

Finally I want to look at blood pressure management. Blood pressure is a key indicator of cardiovascular health.

Sample questions:

1.How many patients had documented uncontrolled hypertension at any time in 2018 and 2019?

2.Which providers treated patients with uncontrolled hypertension in 2018 and 2019?

3.What medications were given to patients with uncontrolled hypertension?

4.If we used a lower cut off of 135/85 for hypertension than the 140/90 discussed in the lecture, how many patients would have been documented hypertension at any time across 2018 or 2019?

5.What was the most commonly prescribed medication to the patients with hypertension (as identified as having a BP over 140/90 at any point in 2018 or 2019)?

6.Which race had the highest total number of patients with a BP of 140/90 before 2020?

7.Which race had the highest percentage of blood pressure readings that were above 140/90 and taken before 2020?

In this healthcare analytics project, I build some dashoboards in tableau for flu shots, emergency room visits, and encounters.

[View Flu Shot Dashboard](https://public.tableau.com/app/profile/shreya.suman4841/viz/ImmunizationDashboard_17610346455430/RunningSumofFluShots2019)

