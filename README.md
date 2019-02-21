# Predicting Disease State

## Motivation

In order to provide a proper treatment to a patient we must understand a patient's desease, and we should know a patient's [phenotypes](https://en.wikipedia.org/wiki/Phenotype) There are several strategies fo phenotyping both in supervised and unsupervised methods. In this project, I implemented both type of phenotyping algorithms using Spark.

## Prerequisites

<ul class="skill-list">
	<li>Spark 8G RAM</li>
    <li>Scala</li>
</ul>

## Raw Data 

**medication_orders**
root
 |-- Provider_Org: string (nullable = true)
 |-- Member_ID: string (nullable = true)
 |-- Last_Filled_Date: string (nullable = true)
 |-- Drug_Name: string (nullable = true)
 |-- Drug_NDC: string (nullable = true)
 |-- Status: string (nullable = true)
 |-- Sig: string (nullable = true)
 |-- Route: string (nullable = true)
 |-- Dose: string (nullable = true)
 |-- Units: string (nullable = true)
 |-- Order_ID: string (nullable = true)
 |-- Order_Date: string (nullable = true)
 |-- Qty_Ordered: string (nullable = true)
 |-- Refills: string (nullable = true)
 |-- Order_Provider_ID: string (nullable = true)
 |-- Order_Provider_Name: string (nullable = true)
 |-- Medication_Type: string (nullable = true)
 |-- Encounter_ID: string (nullable = true)



All rights are reserved by SUNLAB





