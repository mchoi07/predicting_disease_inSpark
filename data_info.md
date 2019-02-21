## Raw Data (From CSV)

I had 4 differnt raw data of patients. 

**medication_orders** </br>
 |-- Provider_Org: string (nullable = true) </br>
 |-- Member_ID: string (nullable = true) </br>
 |-- Last_Filled_Date: string (nullable = true) </br>
 |-- Drug_Name: string (nullable = true) </br>
 |-- Drug_NDC: string (nullable = true)</br>
 |-- Status: string (nullable = true)</br>
 |-- Sig: string (nullable = true)</br>
 |-- Route: string (nullable = true)</br>
 |-- Dose: string (nullable = true)</br>
 |-- Units: string (nullable = true)</br>
 |-- Order_ID: string (nullable = true)</br>
 |-- Order_Date: string (nullable = true)</br>
 |-- Qty_Ordered: string (nullable = true)</br>
 |-- Refills: string (nullable = true)</br>
 |-- Order_Provider_ID: string (nullable = true)</br>
 |-- Order_Provider_Name: string (nullable = true)</br>
 |-- Medication_Type: string (nullable = true)</br>
 |-- Encounter_ID: string (nullable = true)</br>
 
**lab_result** </br>
 |-- Provider_Org: string (nullable = true)</br>
 |-- Member_ID: string (nullable = true)</br>
 |-- Date_Collected: string (nullable = true)</br>
 |-- Test_ID: string (nullable = true)</br>
 |-- Specialty: string (nullable = true)</br>
 |-- Panel: string (nullable = true)</br>
 |-- Test_LOINC: string (nullable = true)</br>
 |-- Test_Name: string (nullable = true)</br>
 |-- Date_Resulted: string (nullable = true)</br>
 |-- Specimen: string (nullable = true)</br>
 |-- Result_LOINC: string (nullable = true)</br>
 |-- Result_Name: string (nullable = true)</br>
 |-- Result_Status: string (nullable = true)</br>
 |-- Result_Description: string (nullable = true)</br>
 |-- Numeric_Result: string (nullable = true)</br>
 |-- Units: string (nullable = true)</br>
 |-- Abnormal_Value: string (nullable = true)</br>
 |-- Reference_Range: string (nullable = true)</br>
 |-- Order_ID: string (nullable = true)</br>
 |-- Provider_ID: string (nullable = true)</br>
 |-- Encounter_ID: string (nullable = true)</br>
 
**encounter** </br>
 |-- Provider_Org: string (nullable = true)</br>
 |-- Encounter_ID: string (nullable = true)</br>
 |-- Member_ID: string (nullable = true)</br>
 |-- Provider_ID: string (nullable = true)</br>
 |-- Provider_NPI: string (nullable = true)</br>
 |-- Clinic_ID: string (nullable = true)</br>
 |-- Encounter_DateTime: string (nullable = true)</br>
 |-- Encounter_Description: string (nullable = true)</br>
 |-- CC: string (nullable = true)</br>
 |-- Episode_ID: string (nullable = true)</br>
 |-- Patient_DOB: string (nullable = true)</br>
 |-- Patient_Gender: string (nullable = true)</br>
 |-- Facility_Name: string (nullable = true)</br>
 |-- Provider_Name: string (nullable = true)</br>
 |-- Specialty: string (nullable = true)</br>
 |-- Clinic_Type: string (nullable = true)</br>
 |-- lab_orders_count: string (nullable = true)</br>
 |-- lab_results_count: string (nullable = true)</br>
 |-- medication_orders_count: string (nullable = true)</br>
 |-- medication_fulfillment_count: string (nullable = true)</br>
 |-- vital_sign_count: string (nullable = true)</br>
 |-- therapy_orders_count: string (nullable = true)</br>
 |-- therapy_actions_count: string (nullable = true)</br>
 |-- immunization_count: string (nullable = true)</br>
 |-- Has_Appt: string (nullable = true)</br>
 |-- SOAP_Note: string (nullable = true)</br>
 |-- consult_ordered: string (nullable = true)</br>
 |-- Disposition: string (nullable = true)</br>

**encounter_dx**
 |-- Provider_Org: string (nullable = true)</br>
 |-- code: string (nullable = true)</br>
 |-- vocab: string (nullable = true)</br>
 |-- description: string (nullable = true)</br>
 |-- severity: string (nullable = true)</br>
 |-- Encounter_ID: string (nullable = true)</br>
 
 ## Feature Selection
 
**medical_dataframe**
 |-- patientID: string (nullable = true) </br>
 |-- date: string (nullable = true) </br>
 |-- medicine: string (nullable = true) </br>
 
**lab_dataframe**
 |-- patientID: string (nullable = true) </br>
 |-- date: string (nullable = true) </br>
 |-- testName: string (nullable = true) </br>
 |-- value: double (nullable = true) </br>
 
**diag_dataframe**
 |-- patientId: string (nullable = true) </br>
 |-- date: string (nullable = true) </br>
 |-- code: string (nullable = true) </br>
