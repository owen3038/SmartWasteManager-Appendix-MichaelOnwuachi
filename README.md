

# SmartWasteManager – Project 

**Student Name:** Michael Onwuachi
**Student ID:** 10211100292 
**Institution:** Academic City University  
**Course:** Final Year Project – Design and Implementation of an Automated Scheduling and Billing System for Residential Waste Collection

## Overview
A smart waste collection management system built using Adalo. It supports customer scheduling, billing, payments (via Paystack), and admin management.


## Appendix

### A. App Structure
- **App Builder:** Adalo
- **Frontend:** Adalo components (no-code)
- **Database:** Adalo internal collections
- **Payment Gateway:** Paystack (connected via external URL)

### B. Screens and Functionality

| Screen Name        | Description |
|--------------------|-------------|
| Welcome            | Entry screen for all users |
| Sign Up / Login    | Client and Admin access  |
| Home (Client)      | Schedule pickups, view Pickups, make payments |
| Home (Admin)       | View requests, manage schedules |
| Confirmation       | Post-payment success screen |


### C. External Integrations
- **Paystack:** Redirect after payment → `https://smartwastemanager.adalo.site/confirmation`

### D. Special Logic
- Pickup schedule logged to database and displayed in "History"
- Payments trigger confirmation screen

### E. Screenshots
(Upload screen images here or in a `/screenshots` folder)


### User Collection
- Full Name
- Email
- User Type (Client/Admin)
- Password

### Pickup Requests
- User
- Pickup Date
- Service Type
- Status (Pending,Rescheduled,Completed)


## Link to Live App
[Click to open SmartWasteManager](https://previewer.adalo.com/3883c255-ce04-4d02-b4bd-21faa8710050)



