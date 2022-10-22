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

<img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/html5%20-%2314354C.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%2314354C.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/bootstrap%20-%2314354C.svg?&style=for-the-badge&logo=bootstrap&logoColor=white"/> <img src="https://img.shields.io/badge/javascript%20-%2314354C.svg?&style=for-the-badge&logo=javascript&logoColor=white"/> <img src="https://img.shields.io/badge/nodejs%20-%2314354C.svg?&style=for-the-badge&logo=nodejs&logoColor=white"/> <img src="https://img.shields.io/badge/firebase%20-%2314354C.svg?&style=for-the-badge&logo=firebase&logoColor=white"/> <img src="https://img.shields.io/badge/react%20-%2314354C.svg?&style=for-the-badge&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/ipfs%20-%2314354C.svg?&style=for-the-badge&logo=ipfs&logoColor=white"/> <img src="https://img.shields.io/badge/express%20-%2314354C.svg?&style=for-the-badge&logo=express&logoColor=white"/> <img src="https://img.shields.io/badge/lighthouse%20-%2314354C.svg?&style=for-the-badge&logo=lighthouse&logoColor=white"/>


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
<img src="https://github.com/raihankhan-rk/medbase-readme/blob/main/Landing%20Page.png" width="1000"> <img src="https://github.com/raihankhan-rk/medbase-readme/blob/main/About.png" width="1000"> <img src="https://github.com/raihankhan-rk/medbase-readme/blob/main/Our%20Team.png" width="1000"> 
</pre>

### 2. Authentication
<pre>
<img src="https://github.com/raihankhan-rk/medbase-readme/blob/main/Authentication.png" width="1000">
</pre>

### 3. Dashboard
<pre>
<img src="https://github.com/raihankhan-rk/medbase-readme/blob/main/Dashboard.png" width="1000"> 
</pre>


## Link To GitHub Readme

See the code [here](https://github.com/raihankhan-rk/medbase-readme)

## Link To Deployed App

See the deployed app [here](https://medbase-ii.web.app/)
