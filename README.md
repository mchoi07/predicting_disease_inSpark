# Predicting Disease State

## Motivation

In order to provide a proper treatment to a patient we must understand a patient's desease, and we should know a patient's [phenotypes](https://en.wikipedia.org/wiki/Phenotype) There are several strategies fo phenotyping both in supervised and unsupervised methods. In this project, I implemented both type of phenotyping algorithms using Spark.

## Raw Data

Please read the data_info.md file

## Feature Engineering 

1. Selecting feature from Raw Data

**medical_dataframe**</br>
 |-- patientID: string (nullable = true) </br>
 |-- date: string (nullable = true) </br>
 |-- medicine: string (nullable = true) </br>
 
**lab_dataframe**</br>
 |-- patientID: string (nullable = true) </br>
 |-- date: string (nullable = true) </br>
 |-- testName: string (nullable = true) </br>
 |-- value: double (nullable = true) </br>
 
**diag_dataframe**</br>
 |-- patientId: string (nullable = true) </br>
 |-- date: string (nullable = true) </br>
 |-- code: string (nullable = true) </br>
 
 2. Convert RDD to RDD </br>
 ```{scara}
case class Diagnostic(patientID: String, date: Date, code: String)
case class LabResult(patientID: String, date: Date, testName: String, value: Double)
case class Medication(patientID: String, date: Date, medicine: String)

val medication: RDD[Medication] = sql_med.as[Medication].rdd
val labResult: RDD[LabResult] = sql_lab_b.as[LabResult].rdd
val diagnostic: RDD[Diagnostic] = sql_diag.as[Diagnostic].rdd

 ```
 


## Prerequisites

<ul class="skill-list">
	<li>Spark 8G RAM</li>
    <li>Scala</li>
</ul>



All rights are reserved by SUNLAB





