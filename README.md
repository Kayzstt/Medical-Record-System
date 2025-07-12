# Medical Record System
El Mahsini Aimen
<br>

# Project Summary

## Context
The goal of this project was to develop a secure client/server system for handling patient's medical records, similar to those found in hospitals. The main focus was on implementing robust security measures throughout the system, considering both the security policy and data storage aspects. We had the freedom to choose appropriate protocols, languages, and techniques. The project emphasized the importance of using effective security techniques, regardless of whether they were covered in class or not.

## Functionality
The system operates on a client/server architecture, involving two main actors: the server and the clients driven by users. The server provides several key functionalities, including user registration, user login, and the ability for authenticated users to edit and share medical records when appropriate. The exact implementation details were left to our discretion, allowing us to identify critical security points and employ appropriate measures accordingly.

Here are the main functionalities of the system:

## User Registration and Authentication:

New users can register to the system, providing necessary information and generating authentication credentials (passwords, cryptographic keys, etc.).
User authentication is required to access the system's features, ensuring secure communication between clients and the server.
Different types of users (administrators, doctors, patients) have specific rights and privileges within the system.

## Medical Record Management:

Patients have their own medical records, organized as directories containing various files.
Users can securely access and view their own medical records and for doctors, the records of patients assigned to them.
The system ensures the confidentiality and integrity of medical record files, protecting sensitive information within the records.

## Adding and Deleting Doctors:

Patients can add or remove doctors from their list of appointed doctors.
Approval from the patient is required when doctors initiate the addition process.

## File Management:

Patients can upload files to their medical records, edit the content of existing files, and delete files permanently.
Doctors, with patient approval, can perform file management actions on behalf of the patient.






