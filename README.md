<h1 align="center">
             🟢MedBase🟢
</h1>

![image](https://github.com/raihankhan-rk/medbase-readme/blob/main/MedBase%20Cover.jpg)


## Overview of the App

<table>
<tr>
<td>
MedBase is an online platform to maintain medical records of a patient. It runs on the IPFS - InterPlanetary File System protocol making it accessible even from a anywhere across the globe! All the patients will have an account on MedBase with a unique id assigned to them. The unique id can then be used from any hospital/clinic across the world to upload or retreive the patient's medical records easily. IPFS is a P2P protocol much like Blockchain, hence once a record is uploaded, it can never be deleted. This ensures that no medical record of any patient can be forged.
</td>
</tr>
</table>

There are 2 main sections in the app as follows -

1. <b>Patient Authentication</b> - This section will be used to authenticate the ptients via phone no. We've used Phone no. as our method of authentication so that later on we can implement Aadhaar authentication to make sure that no patient has more than one account on MedBase. 

2. <b>Dashboard</b> - The Dashboard will contain a table of all the Medical records of the patient that has been uploaded till date. The records will be sorted in the order of date uploaded. From the dashboard, anyone can upload or retreive any medical document of the patient who's account is logged in. Besides this, the dashboard will also contain a card which we call the "MedBase Card", which will have the basic user details and a 12 digit unique id, which can be used in the hospitals to retreive the patient's data.


## Tech Stack Used -

<img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/html5%20-%2314354C.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%2314354C.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/bootstrap%20-%2314354C.svg?&style=for-the-badge&logo=bootstrap&logoColor=white"/>

## Libraries Used -

<img src="https://img.shields.io/badge/numpy%20-%2314354C.svg?&style=for-the-badge&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/pandas%20-%2314354C.svg?&style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/plotly%20-%2314354C.svg?&style=for-the-badge&logo=plotly&logoColor=white"/> <img src="https://img.shields.io/badge/pickle%20-%2314354C.svg?&style=for-the-badge&logo=pickle&logoColor=white"/> <img src="https://img.shields.io/badge/nltk%20-%2314354C.svg?&style=for-the-badge&logo=nltk&logoColor=white"/> <img src="https://img.shields.io/badge/tensorflow%20-%2314354C.svg?&style=for-the-badge&logo=tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/flask%20-%2314354C.svg?&style=for-the-badge&logo=flask&logoColor=white"/> 

<img src="https://img.shields.io/badge/javascript%20-%2314354C.svg?&style=for-the-badge&logo=javascript&logoColor=white"/>

## Structure Of The Project

The home page of the application contains -
  1. <b>Landing Page</b> - Here users can get started with using our application
  2. <b>About the product</b> - A brief description of what and how our product works.
  3. <b>Our Team</b> - This section contains the photos of the team members.

The Authentication page of the application contains -
  1. <b>Sign In Option</b> - Here the patient will enter his phone no. in order to login to view the dashboard. <b>Note - </b> We don't have a separate sign up page for the patients. To make the process even simpler, we integrated both login and signup in one page itself. If the user is not registered, he will be prompted to sign up.

## Future Prospects

- <b>Aadhaar Authentication</b> - This will ensure that no patient has more than one account on MedBase.
- <b>ML Incorporation</b> - We will add an OCR model to ensure that no similar documents are uploaded with different digital stamps.

## UI Of The Web Application

### 1. Home Page
<pre>
<img src="https://user-images.githubusercontent.com/78029145/181441355-4324ecab-e617-4439-a0f9-8a7ff01324f4.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181441418-023a5926-a8e4-4534-9770-fd55ee3ce5c2.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181441511-e645e907-d71e-4602-9c17-27cba1420fdf.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181441970-832c9ace-9dbb-4308-bed6-d062247f4147.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181442072-e3e87b33-f36d-413c-9649-27a4387e2744.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181442147-caf6dfdd-f696-4ab3-a298-8d32313476a6.png" width="1000"> 
</pre>

### 2. Social Media Section
<pre>
<img src="https://user-images.githubusercontent.com/78029145/181442605-3aa75389-bc37-47e3-9a61-fafc3a883033.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181442623-377b9dc9-adc3-4091-a21a-9770278d3745.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181444492-36fa33ac-2ae3-43ad-a724-5b5776374212.png" width="1000">
</pre>

### 3. Top Products
<pre>
<img src="https://user-images.githubusercontent.com/78029145/181443175-447222b4-88a2-460e-8dc5-6de1a4446e34.png" width="1000"> 
</pre>

### 4. Big Billion Days Section
<pre>
<img src="https://user-images.githubusercontent.com/78029145/181445122-c06045a3-0a09-409e-ae3e-a998f62c3bbe.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181445500-59bd19e6-6b65-4c39-8bd7-46d4a8f6d510.png" width="1000"> <img src="https://user-images.githubusercontent.com/78029145/181444896-495bea4b-5808-4a1a-8542-cf86ea449420.png" width="1000">
</pre>

## Run Locally

1.1 `git clone <repo link>`

1.2 `cd ManageIt`

1.3 `flask run`

## Link To GitHub Readme

See the code [here](https://github.com/BhaswatiRoy/FlipAnalyse)

## Link To Deployed App

See the deployed app [here](https://mighty-dusk-36159.herokuapp.com/)
