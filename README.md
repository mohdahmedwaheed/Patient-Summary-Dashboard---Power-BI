# Patient Summary Dashboard - Power BI

## Project Overview
The Patient Summary Dashboard is a Power BI project designed to provide a quick, comprehensive view of patient information and health metrics. It integrates data from two separate tables and uses a unique Admission Number as a primary key to join them, creating a unified view for healthcare professionals to make quick, informed decisions.

## Key Features
## General Patient Details:

Displays patient demographic information including Name, Age, Gender, Admission Number, Admission & Discharge Dates, ICU Duration, and Stay Duration.

Indicators for habits such as Alcohol and Smoking status.

## Blood Reports:

Key health metrics like Glucose, HB, Heart Failure indicators, Creatinine levels, Chest Infection, Pulmonary Embolism, and others.

Vital health data provided in a clear, easy-to-understand format.

## Outcome Summary:

Final discharge outcome displayed with a summary status to facilitate follow-up decisions.

Data Model

## The dashboard pulls data from two interconnected tables:
1. Patient admission information (12,244 records)
    - Admission_No (unique identifier)
    - Patient_Name
      
2. Clinical Data Dataset: This dataset contains 15,757 clinical records, each linked to a patient through the Admission_No. The dataset includes various clinical variables such as medical history (e.g., Diabetes, Hypertension), lab results (e.g., BNP, Creatine), and treatment outcomes (e.g., Discharge_Date, Outcome).


These tables are linked using Admission Number as the primary key to create a comprehensive view of each patient’s journey and health status.

## Technologies Used
Power BI: For data modeling, dashboard design, and visualization.

Data Integration: Combined two distinct data sources into a single dashboard by establishing a primary key relationship.

Data Visualization: Created various visual elements to represent patient data in a meaningful and user-friendly way.

## Visualizations
Patient Summary Section: Displays demographic and stay-related information.

Blood Reports Section: Shows lab values and medical conditions.

Health Status Summary: Provides an easy-to-read condition summary to guide follow-up care.

## Usage
This dashboard is designed for healthcare environments where rapid access to patient data is critical. It helps healthcare providers assess patient conditions at a glance and enables quick decision-making for patient care and follow-up planning.

## Getting Started
Import the Data: Use the provided CSV files to import data into Power BI.

Set Up Relationships: Ensure that the Admission Number is set as the primary key to link both tables.

Customize Visuals: Adapt the visuals based on specific needs or preferences for your healthcare setting.

## Contributing
If you have suggestions or improvements, feel free to fork this repository and submit a pull request. Contributions are always welcome!


