## Data-Cleaning
Clean and prepare a raw dataset.

## Dataset Description 
The dataset contains 110,526 rows and 14 columns of information about patients and their medical appointments. It includes patient details such as:
-PatientId: Identification of a patient
- AppointmentID: Identification of each appointment
- Gender: Male or Female .
- ScheduledDay: is the day someone called or registered the appointment, this is before appointment
- Appointment day: is the day of the actual appointment
- Age: How old is the patient.
- Neighbourhood: Where the appointment takes place.
- Scholarship: True of False .
- Hipertension: True or False
- Diabetes: True or False
- Alcoholism: True or False
- Handcap: True or False
- SMS_received: None or 1 message sent to the patient.
- No-show: True or False.

##Tools Used
Microsoft Excel 

## Data Cleaning/Preparation 
1. Date Columns:
I Converted all date columns to a standard Excel-recognized format using the DATEVALUE function.

I also Formatted the dates as short dates for readability and consistency.

2. Patient ID Column:

I Converted IDs from scientific/exponential notation to standard numeric format.

I also ensured the data type was set as Number for proper calculations and reference.



3. Boolean Columns:
Replaced 1 and 0 with Yes and No for clarity.


4. Data Types Standardization:

I Confirmed all columns had appropriate data types: numeric, date,Text according to their content.



5. Duplicates and Missing Values:

Checked the dataset for duplicate entries and missing values.

No duplicates or missing values were found, ensuring dataset integrity.


This cleaning process ensured that the dataset is now consistent, accurate, and ready for analysis.

