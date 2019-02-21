# Predicting Disease State

## Motivation

In order to provide a proper treatment to a patient we must understand a patient's desease, and we should know a patient's [phenotypes](https://en.wikipedia.org/wiki/Phenotype) There are several strategies fo phenotyping both in supervised and unsupervised methods. In this project, I implemented both type of phenotyping algorithms using Spark.

## Prerequisites

<ul class="skill-list">
	<li>Spark 8G RAM</li>
    <li>Scala</li>
</ul>

## Raw Data 

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



All rights are reserved by SUNLAB





