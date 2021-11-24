
#   COVID VACCINATION BOOKING SYSTEM

## Requirements
  
## Introduction

  ##### This application is mainly used to register for covid vaccines,it is the best way to get the vaccines.The leverage of this application is used for register for vaccines ,tracking the information,listing the type of dose,suggesting the healthcare after getting vaccines and when will be the second dose,downloading the certificate. It is mainly focused on whether the people get vaccinated or not. The covid vaccination booking system is mainly used to find the availability of the vaccine in the particular area,If the vaccine is available for someone,then continue to the registration process. To register the vaccine by using aadar number. To track the availablity of the vaccine,if all the personal details are correct then process of booking the covid vaccine is done.
  
 ## Research
  
   ##### The covid vaccination booking system achieved in various language but, In this i achieved in c programming. It is the greatest way to achieve. In this everything will be stored in local system and the existing project are stored in live server,in that sometimes the server will chance to low.
  
  ## Features
       
   #####  • Easy to use,store,track,edit,download by using this application.
   #####  • Easy to store the data,because of storing this in local system.
   #####  • Identify the information is easy.
   #####  • Excellent registration process.
   
## Advantage:
   
   #####  • To check the availability of vaccine.
   #####  • To book the vaccine easily.
   #####  • Track the details easily.
   #####  •  Ttrack the level of dose and date.
 
## Disadvantage:
  
   #####  • To indentifing the person who is already registered or not.
   #####  • SMS or Call verification is not available.

## SWOT ANALYSIS:

 ### STRENGTH

   #####  • The booking of vaccination is really easy.
   #####  • Tracking the details of the vaccinated person.
   #####  • check the availability.
  
 ### WEAKNESS
   
   #####  • To storing the details of the person is difficult.
   #####  • If the person who don't have the correct credential is hard to register.
 
 ### OPPORTUNITIES
 
   #####  • To store all the information of the person.

 ### THREATS
 
  #####  • Verification of the Credential is one the threat.

## 4W's and 1H:
 
 ### WHO
  
   ##### • People who want to get vaccine.
     
### WHAT
  
   ##### • Booking covid vaccinations.
     
### WHERE
 
   ##### •To where you want to get vaccinate in nearby.
     
### WHEN
  
   ##### • Specified duration present when you registered vaccine.
    
### HOW
   
   ##### • By registering yourself in online application.

## High Level Requirements:

  |  ID    |  DESCRIPTION                  |  STATUS       |
  | :---   |  :---:                        |  ---:         |
  | HR01   | Availability of vaccines      | Implemented   |
  | HR02   | Checking the level of dose    | Implemented   |
  | HR03   | Duration of get vaccination   | Implemented   |
  | HR04   | Identify the type of dose     | Implemented   |
  | HR05   | Identifing the credentials    | Implemented   |
 

## Low Level Requirements:

  |  ID    |  DESCRIPTION                             |  STATUS             |
  | :---   |  :---:                                   |  ---:               |
  | LR01   | Checking the availability of vaccine     | Implemented         |
  | LR02   | suggesting the health care               | Implemented         |
  | LR03   | Tracking the information                 | Implemented         |
  

# Architecture

   - Behavioural diagram
   - structural diagram

# Tools
  
  - Draw.io 
                                
# UML diagram

## Behavioural

![Test Image 5](https://github.com/sumithra18/M1_Covid_Vaccination_Booking_System/blob/main/2_Design/behavioural.png)
  
  
## Structural
![Test Image 6](https://github.com/sumithra18/M1_Covid_Vaccination_Booking_System/blob/main/2_Design/Structural%20diagram.png)


# Implementation
## Introduction
This folder conatins all the coding files as well as the resources and testing files neede for proper execution of program

## Instructions to execute
1. Clone my repository
2. Go to 3_Implementation folder
3. Make sure your system meets all software and hardware requirements
4. Run "make run" command in terminal for main code execution
5. Run "make run_test" command in terminal for test code execution.

## Folder Structure

| Column 1 Header | Column 2 Header | 
| --------------- | --------------- |
| Inc | All header files |
| Src | Main source code for system | 
| test | All source code and data for testing purposes | 


# Covid Vaccination Registration
## High Level Test Plan


Test ID  | Description | Input | Expected output | Actual Output
--- | --- | --- | --- |---
01 | Check patient registration status | 123 (aadhar no)| {-1} | (not found)
02 | Check patient registration status | 123 (aadhar no)| {0,1} | ( found)
03 | Check patient vaccination status | 3 (patient id)| {>0} | (vaccinated)



## Low Level Test Plan
Test ID  | Description | Input | Expected output | Actual Output
--- | --- | --- | --- |---
01 | Check patient registration status | 125 (aadhar no)| 0 | 0(registered, not vaccinated)
02 | Check patient registration status | 130 (aadhar no)| 1 | 1 (registered, vaccinated)
03 | Check patient vaccination status | 3 (patient id)| 1 | 1 (first dose)
04 | Check patient vaccination status | 3(patient id| 2 | 2(first dose)
05 | Check patient vaccination status | 3 (patient id)| 3 | 3 (second dose)


