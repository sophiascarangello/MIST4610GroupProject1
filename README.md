# MIST4610 Group 6 Project 1

# Team Name:
47114 Group 6

# Team Members:
Samuel Miller

Sophia Scarangello

Arika Chiluvuri

Riley Eckstrom

Owen Donnelly

Michael Banks



# Problem Description

# Data Model
<img width="409" alt="image" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/150087690/756139c3-4a81-4cc8-a5e1-fddacc2ee280">

# Data Dictionary
<img width="681" alt="Screenshot 2024-03-26 at 6 39 05 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/80c54b27-49d2-41a5-9132-a86579cc36eb">
<img width="691" alt="Screenshot 2024-03-26 at 6 39 27 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/2cd7ce30-e672-4dc2-87cb-9cf3a665dc76">
<img width="679" alt="Screenshot 2024-03-26 at 6 39 43 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/aea9df11-608d-4b44-8111-e10ec650d959">
<img width="687" alt="Screenshot 2024-03-26 at 6 40 02 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/96b1be21-90b6-48a8-a8b2-629ea704deb6">
<img width="684" alt="Screenshot 2024-03-26 at 6 40 20 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/564e76d5-7cc0-4b3b-93e8-449df09114de">
<img width="683" alt="Screenshot 2024-03-26 at 6 40 36 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/3e36dafc-3008-4c6e-bea5-ddb0dcf6e1a5">
<img width="690" alt="Screenshot 2024-03-26 at 6 41 04 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/c8c68966-1b4c-4c45-838f-54a731bc68a3">
<img width="696" alt="Screenshot 2024-03-26 at 6 41 17 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/9ac5639e-56b2-4bf4-afe2-cbc088cf944c">
<img width="689" alt="Screenshot 2024-03-26 at 6 41 31 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/cfce7023-6756-43ca-9dfe-89f2795e82ea">
<img width="687" alt="Screenshot 2024-03-26 at 6 41 42 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/c8d9e571-35c6-4a86-a64f-cf993bb50260">
<img width="686" alt="Screenshot 2024-03-26 at 6 41 54 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/cee4b9e8-5777-485d-bbda-9801d2d0d10f">
<img width="685" alt="Screenshot 2024-03-26 at 6 42 08 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163004723/fd18d128-c1ec-4200-821b-d565b03f2c9d">


# Queries
<img width="488" alt="image" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/163002732/af3ae506-840a-462a-8413-b023f901070c">

1. List the patient's first and last name combined for patients whose total bill amount is greater than the average bill amount of the insurance company they belong to.

Justification: This query helps the urgent care manager identify patients with higher than average bills for their insurance company. It can be used to analyze billing patterns, negotiate rates with insurance providers, and identify potential billing issues.
<img width="877" alt="Screenshot 2024-03-26 at 6 28 48 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/131375287/c92520bb-fc1c-497c-ac48-4569277c81f7">

2. List the medical staff's first name and specialty who treat patients that are female and don't use State Farm insurance.

Justification: This query helps the manager identify the medical staff and their specialties that cater to a specific demographic of patients. It can be used for resource allocation, staff training, and understanding patient preferences.
<img width="877" alt="Screenshot 2024-03-26 at 6 29 32 PM" src="https://github.com/SamuelMiller2/MIST4610GroupProject1/assets/131375287/386917b6-18b7-4485-8d3b-ccba7fd045aa">

3. List the patient's visit time, medication name, duration, and pharmacy name for patients who have 2 or more appointments. Group by patientID.

Justification: This query helps the manager identify patients with multiple appointments and their associated medications and pharmacies. By grouping the results by patient instead of visit time, we can still monitor medication adherence, pharmacy partnerships, and patient follow-up for patients with frequent visits. This information can be used to optimize patient care, ensure medication compliance, and strengthen relationships with pharmacies.

4. Print out the patient's full name and the number of payments they have made that were greater than $5,000 dollars.

Justification: This query helps the manager identify patients who have made payments higher than five thousand dollars. It can be used to analyze payment patterns, identify potential billing errors, and recognize patients who may be struggling financially.

5. Write a query to list the number of patients each specialty has seen.

Justification: This query helps the manager assess the workload of each specialty group and identify any potential staffing issues. It can be used for performance evaluations, resource allocation, and staff training.

6. Write a query to list the name of the pharmacy, the pharmacy phone number, and count the number of patients each pharmacy is responsible for if the patient's prescription is Xanax. List the pharmacies in alphabetical order.

Justification: This query helps the manager identify pharmacies that dispense a specific medication and the number of patients they serve. It can be used to monitor medication usage, pharmacy partnerships, and patient care.

7. Find the full patient names and the reason for visit for patients who had a visit but were not prescribed anything. Order the patients by their age, youngest to oldest.

Justification: This query helps the manager identify patients who visited the urgent care but did not receive any prescriptions. It can be used to analyze patient care, identify potential missed diagnoses, and improve patient outcomes.

8. Write a query that identifies patients with unpaid or pending bills and their total bill amount.

Justification: This helps the manager track the payment status of patient bills and identify any outstanding balances. They can be used for financial reporting, collections, and patient communication.

9. Write a query that lists the most commonly diagnosed conditions and their frequencies from greatest to least.

Justification: This query helps the manager identify the most common conditions treated at the urgent care. It can be used for resource allocation, staff training, and patient education.

10. Write a query that identifies the staff members and how many prescriptions they have written. Include their job title and specialty.
Justification: This query helps the urgent care manager identify the staff members who are the most active in prescribing medications. It can be used to analyze prescribing patterns, identify potential over-prescribing, and ensure that staff members are practicing within their scope of practice. By including the job title and specialty, the manager can also assess if the prescribing patterns align with the staff member's role and expertise.

# Database Information

