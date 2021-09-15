## 1. About This Project
Since COVID-19, a lot of families and groups choose to make food for themselves rather than going out to eat.<br /> 
There are a lot of recipes out there but there are some special recipes that only the cook knows.<br /> 
This app helps people share their own recipes and also communicate their everyday life. Like Instagram, <br />
it has a feature that a user can follow another user. Also,  a user can block another user.<br /> 
There is also a feature of direct messaging to people who the user follows. 

## 2. Non-functional Requirements:
#### Architecture
Our platform will be separated into frontend and backend. We will be using firebase to handle all the background processing and will hold all of our user data; for the front end we will be using react native to handle all the user input and the visualization of our android app. 

#### Performance
Based on our hosting server, we expect to support about 200,000 simultaneous users connections, about 800,000 recipes. Furthermore, we guarantee a response time of at most 20s for any get request.

#### Security
It’s important to keep user’s data safe and secure. We want the authenticated users to have access to their own user information and all relevant information only. We are using Firebase to store user data and encrypt sensitive information. 

#### Usability
Simple and easy navigation gives easy access to different age groups. The app structure works very similarly to other communication applications which users will get along with the app quickly.

#### Hosting/Deployment
Only the backend (realtime database for messaging and stable database for posting) needed to be hosted on the server, we plan to host direct messaging through “Firestore Database” and posting through “RealTime Database” in firebase.


## 3. Non-Functional Issues

```
Architecture: Client-Server
Language: Python
Frontend Framework: React Native
Data Platform: Firebase
```

## 4. Design Details

<img src="https://github.com/harachoi/harachoi.github.io/blob/master/assets/images/CookIO/cookio-design_details.PNG" width="80%" align="center">

## 3. Views & Source Codes

<!-- #### 1) View U.S. COVID-19 Statistics 
- The user can select one state and another state to compare.

    [Source Code](https://github.com/harachoi/VaxTrax/blob/main/Pages/CompareUS.md)

#### 2) View U.S. COVID-19 Statistics 
- The user can see the detailed progress of vaccination of regions of each state selected.

    [Source Code](https://github.com/harachoi/VaxTrax/blob/main/Pages/US_Province.md)

#### 3) View World Vaccination by Manufacturers
- The user can select one manufacurer and see which countries have used by the timeline.

    [Source Code](https://github.com/harachoi/VaxTrax/blob/main/Pages/US_Province.md) -->
