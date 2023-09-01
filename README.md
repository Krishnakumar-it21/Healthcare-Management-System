# HealthStack-System

- An online based platform for multiple hospitals. Ability to track, monitor, and share a patient's health records between all hospitals. Patients can also see information regarding multiple hospitals and doctors, as well as take appointments via online. Pay laboratory tests via online as well as chat with appointed doctors.
- Hackathon Project - Bitshack 2023.
- Django Application

## Tools used:
      1) Front-end: HTML, CSS, Boostrap, Javascript
      2) Back-end: Django (Python web framework)
      3) Database: SQLite
      4) Others: Various APIs, PyPI packages, Ajax 

## Features

- **Users:** Patient, Doctor, Hospital Admin, Lab Worker, Pharmacist

### Patient
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
      
### Doctor 
      1)  Doctor Profile Settings (Add More feature)
      2)  Search multiple Hospital → Doctor register to hospital + upload certificate
      3)  (Once registered by admin) accept or reject patients appointment (mail confirmation send to patient)
      4)  Search patient profile → Create and view Prescription, view report
      5)  Chat with appointed Patient
      
### Hospital Admin
      1)  Admin Dashboard
      2)  Accept or reject doctor registration (view doctor profile to see details)
      3)  CRUD Hospitals (Add more)
      4)  View Hospital List → CRUD Departments within hospital
      5)  CRUD Lab Worker
      6)  CRUD Pharmacist

### Lab worker
      1)  Lab Worker Dashboard
      2)  Create Report for patient.
      3)  Create Tests for hospitals, View Tests

### Pharmacist
      1)  Pharmacist Dashboard
      2)  CRUD Medicines
      3)  Search Medicine


## APIs and PyPI packages used:

#### [Django Rest Framework](https://www.django-rest-framework.org/#installation) - toolkit for building web APIs
#### [Django Widget Tweaks](https://pypi.org/project/django-widget-tweaks/) - tweak form field rendering in templates
#### [Pillow](https://pillow.readthedocs.io/en/stable/index.html) - Python imaging library
#### [Mailtrap API](https://mailtrap.io/blog/django-send-email/) - smtp fake testing server
#### [Django Environ](https://django-environ.readthedocs.io/en/latest/) - protecting credentials online (.env file)
#### [SSLCommerz API](https://github.com/sslcommerz/SSLCommerz-Python) - a payment gateway that provides various payment options in Bangladesh (debit card, credit card, mobile banking, etc.)
#### [Django Debug Toolbar](https://django-debug-toolbar.readthedocs.io/en/latest/installation.html) - configurable set of panels that display various debug information about the current request/response and when clicked
#### [xhtml2pdf](https://xhtml2pdf.readthedocs.io/en/latest/usage.html) - to generate and download pdf documents.

## Installation Details
      1) Create an environment to run django project  
      2) Migrate to create dbsqlite database 
      3) Look for .env.example and settings.py files to see what credentials to set up, and then create .env files
      
      The credentials that you need to set up are: Mailtrap credentials, SSLCommerz Credentials. 

# Some Screenshots

## Home page

<img src="https://user-images.githubusercontent.com/64092765/191188204-39dc320f-ec0f-4634-a8db-4735fd89cec9.png" width="50%">

<img src="https://user-images.githubusercontent.com/64092765/191188212-a48d1616-42ec-4413-bb7f-cf0d6347b165.png" width="50%">

<img src="https://user-images.githubusercontent.com/64092765/191188230-2a57e567-a879-487f-a907-8e6add15c8ca.png" width="50%">




