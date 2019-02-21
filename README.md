# Predicting Disease State

## Motivation

In order to provide a proper treatment to a patient we must understand a patient's desease, and we should know a patient's [phenotypes](https://en.wikipedia.org/wiki/Phenotype) There are several strategies fo phenotyping both in supervised and unsupervised methods. In this project, I implemented both type of phenotyping algorithms using Spark.

## Prerequisites

<ul class="skill-list">
	<li>Spark 8G RAM</li>
    <li>Scala</li>
</ul>

## Raw Data 
scala> encounter.show()
+--------------------+--------------------+------------+-----------+------------+--------------------+--------------------+---------------------+--------------------+--------------------+-----------+--------------+-------------+--------------------+--------------------+--------------------+----------------+-----------------+-----------------------+----------------------------+----------------+--------------------+---------------------+------------------+--------+--------------------+---------------+--------------------+
|        Provider_Org|        Encounter_ID|   Member_ID|Provider_ID|Provider_NPI|           Clinic_ID|  Encounter_DateTime|Encounter_Description|                  CC|          Episode_ID|Patient_DOB|Patient_Gender|Facility_Name|       Provider_Name|           Specialty|         Clinic_Type|lab_orders_count|lab_results_count|medication_orders_count|medication_fulfillment_count|vital_sign_count|therapy_orders_count|therapy_actions_count|immunization_count|Has_Appt|           SOAP_Note|consult_ordered|         Disposition|
+--------------------+--------------------+------------+-----------+------------+--------------------+--------------------+---------------------+--------------------+--------------------+-----------+--------------+-------------+--------------------+--------------------+--------------------+----------------+-----------------+-----------------------+----------------------------+----------------+--------------------+---------------------+------------------+--------+--------------------+---------------+--------------------+



All rights are reserved by SUNLAB





