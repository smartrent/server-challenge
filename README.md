# SmartRent Server Engineering Challenge

## Welcome

Welcome to our server engineering challenge!

This challenge is meant for us to learn how you solve and understand problems that you will face. 

## Coding Challenge

For this coding challenge, you will be working on a real world problem we had to solved.  

### Guidelines

- Use the languages you feel most comfortable in
- Refer to Google or documentation as needed

#### Timeframe
We expect most candidates to spend anywhere between 60 and 90 minutes completing the challenge.

### Project Description

Every day we have to import or update 500K residents in our system and it was taking over 12 hours to fully process all the records. Adding more capactiy is a temporary solution that does not scale and will increase costs.

1. You will received a full set of residents data every day 
2. Over 90% of the resident data does not change from day to day. 
3. The resident data can be in any order. 
4. The id of the resident cannot change. 
 
Sample json data
{   
    "id":"3a8a4a7797c1e885f175",                    //  ID
    "firstName":"Candice",                          //  First Name
    "lastName":"Miller",                            //  Last Name
    "unit":287,                                     //  Unit
    "email":"juleslangosh@hermiston.info",          //  Email
    "phone":"274-273-1065"                          //  Phone
}

#### Project
1. 0-day.json, 1-day.json, 2-day.json, etc - Files to simulate each day resident data.

### Acceptance Criteria
1. Provide a list of residents that changed after each import.
2. Provide the time import time after each import.
3. The initial import, should take the longest duration, the sequential imports should be much faster.

### Stretch Goal(s)
1. Provide a list of attributes that changed for resident.
