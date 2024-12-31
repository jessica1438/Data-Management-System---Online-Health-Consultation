# Online Medical Consultation System - DAMG-6210 Project

## Overview
This project aims to revolutionize healthcare by providing a robust **Online Medical Consultation System**, streamlining processes such as patient appointments, case management, and doctor-patient interactions. The system leverages an advanced **ERD (Entity Relationship Diagram)** and SQL scripts to create a comprehensive database structure that supports efficient healthcare operations.

## Features
- **Patient Management**: Store and retrieve detailed patient information, including medical history and contact details.
- **Doctor Scheduling**: Manage doctor schedules and appointments seamlessly.
- **Case Records**: Maintain thorough documentation of patient cases, including prescriptions and feedback.
- **Prescription Management**: Track medication orders with dosage, frequency, and doctor recommendations.
- **Feedback Integration**: Collect and analyze patient feedback for quality improvement.
- **Symptom Specialization**: Match symptoms to specialized doctors for accurate and timely consultations.

## Database Design
The project employs a well-structured **Entity Relationship Diagram (ERD)** that defines all key entities and their relationships:
- **Core Entities**:
  - `PatientDetails`, `Doctor`, `Department`, `CaseRecord`, `PrescriptionDetails`
- **Supporting Entities**:
  - `MedicationOrder`, `DoctorAppointmentSchedule`, `ConsultationRoom`, `PatientFeedback`, etc.
  
The ERD ensures scalability and efficiency, enabling seamless data handling for various operations.

## SQL Implementation
The database is implemented using the provided SQL script. Key highlights include:
- Creation of relational tables with appropriate **primary and foreign keys** to ensure data integrity.
- Advanced queries and relationships to support real-time data retrieval and management.
- Automating workflows for case assignments, prescription generation, and appointment bookings.

## Technology Stack
- **Database**: SQL
- **Modeling Tool**: ERD designed using advanced data modeling principles.
- **Languages**: SQL, Python (optional for future extensions)
- **Tools**: PyCharm, Flask (for potential web application interface)

## How to Use
1. **Setup the Database**:
   - Run the SQL script (`DAMG_PROJECT_TEAM4.sql`) in your preferred SQL environment to create the database and all required tables.
   
2. **Data Population**:
   - Populate the tables with relevant data for testing and demonstration.

3. **Interacting with the System**:
   - Utilize SQL queries to interact with the database or integrate the database with a frontend/backend application for real-time usage.

