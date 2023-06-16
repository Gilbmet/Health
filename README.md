HealthStack-System

    An online based platform for multiple hospitals. Ability to track, monitor, and share a patient's health records between all hospitals. Patients can also see information regarding multiple hospitals and doctors, as well as take appointments via online. Pay laboratory tests via online as well as chat with appointed doctors.
    Software Engineering Project
    
    Tools used:

  1) Front-end: HTML, CSS, Boostrap, Javascript
  2) Back-end: Django (Python web framework)
  3) Database: SQLite
  4) Others: Various APIs, PyPI packages, Ajax 

Features

    Users: Patient, Doctor, Hospital Admin, Lab Worker, Pharmacist

Patient

  1)  Search multiple Hospital → Department List → Search for Doctors
  2)  Doctor Profile → Book Appointment
  3)  Pay Appointment + Mail Confirmation 
  4)  Search all Doctors in all hospitals
  5)  Chat with appointed Doctor
  6)  View Prescription, Download Prescription (PDF)
  7)  Choose which tests to pay (Cart System, payment + mail confirmation)
  8)  View Report, Download Report (PDF)
  9)  Give Doctor Review
  10) Search for Medicines in Medical Shop (Pharmacy)
  11) Select which medicines to purchase (Cart system), pay total amount for medicines (payment + mail confirmation)

Doctor

  1)  Doctor Profile Settings (Add More feature)
  2)  Search multiple Hospital → Doctor register to hospital + upload certificate
  3)  (Once registered by admin) accept or reject patients appointment (mail confirmation send to patient)
  4)  Search patient profile → Create and view Prescription, view report
  5)  Chat with appointed Patient

Hospital Admin

  1)  Admin Dashboard
  2)  Accept or reject doctor registration (view doctor profile to see details)
  3)  CRUD Hospitals (Add more)
  4)  View Hospital List → CRUD Departments within hospital
  5)  CRUD Lab Worker
  6)  CRUD Pharmacist

Lab worker

  1)  Lab Worker Dashboard
  2)  Create Report for patient.
  3)  Create Tests for hospitals, View Tests

Pharmacist

  1)  Pharmacist Dashboard
  2)  CRUD Medicines
  3)  Search Medicine

APIs and PyPI packages used:
Django Rest Framework - toolkit for building web APIs
Django Widget Tweaks - tweak form field rendering in templates
Pillow - Python imaging library
Mailtrap API - smtp fake testing server
Django Environ - protecting credentials online (.env file)
SSLCommerz API - a payment gateway that provides various payment options in Bangladesh (debit card, credit card, mobile banking, etc.)
Django Debug Toolbar - configurable set of panels that display various debug information about the current request/response and when clicked
xhtml2pdf - to generate and download pdf documents.
Installation Details

  1) Create an environment to run django project  
  2) Migrate to create dbsqlite database 
  3) Look for .env.example and settings.py files to see what credentials to set up, and then create .env files
  
  The credentials that you need to set up are: Mailtrap credentials, SSLCommerz Credentials. 
![Screenshot 2023-06-16 at 10 12 03](https://github.com/Gilbmet/Health/assets/111015509/7a5b6cdf-d454-4eea-a956-474d022e6221)
![Screenshot 2023-06-16 at 10 13 00](https://github.com/Gilbmet/Health/assets/111015509/91f618db-64d7-44c3-9888-dc9b9504535a)
![Screenshot 2023-06-16 at 10 13 45](https://github.com/Gilbmet/Health/assets/111015509/891faf6a-d852-4e67-8617-9b10219cd08f)
![Screenshot 2023-06-16 at 10 14 28](https://github.com/Gilbmet/Health/assets/111015509/c8e5f940-c6f0-4ade-90b3-c4fd7096d9d2)
![Screenshot 2023-06-16 at 10 15 08](https://github.com/Gilbmet/Health/assets/111015509/bfec2dda-954b-4a34-8b35-163ec54e69b0)
![Screenshot 2023-06-16 at 10 15 46](https://github.com/Gilbmet/Health/assets/111015509/1b8a6969-8934-4ff1-bd6b-2a73f85223e2)
![Screenshot 2023-06-16 at 10 16 25](https://github.com/Gilbmet/Health/assets/111015509/89fc4509-522a-480e-af56-35636aa25a34)
![Screenshot 2023-06-16 at 10 17 03](https://github.com/Gilbmet/Health/assets/111015509/1ae74f79-0647-4b5a-b8e4-08f1c8ad5f79)
![Screenshot 2023-06-16 at 10 17 44](https://github.com/Gilbmet/Health/assets/111015509/f5da8b37-3b42-4be0-a81a-45007fb2dc2d)
![Screenshot 2023-06-16 at 10 18 20](https://github.com/Gilbmet/Health/assets/111015509/1af32aa3-de6d-45ea-b458-80ad10947826)
![Screenshot 2023-06-16 at 10 19 00](https://github.com/Gilbmet/Health/assets/111015509/14a60ecf-6ba1-4200-8c71-29dec1dd187c)
![Screenshot 2023-06-16 at 10 19 53](https://github.com/Gilbmet/Health/assets/111015509/1f102be4-a809-473d-ac84-3d40b05e62e4)

