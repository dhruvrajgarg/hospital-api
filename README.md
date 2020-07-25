# Hospital API
An API to manage hospital data 
## Routes 
- /doctors/register → with username and password
- /doctors/login → returns the JWT to be used
- /patients/register
- /patients/:id/create_report 
- /patients/:id/all_reports → List all the reports of a patient oldest to latest
- /reports/:status → List all the reports of all the patients filtered by a specific status
## Directory Structure
```
Hospital api
├── config                   # DataBase config file
│   └── mongoose.js
│   └── passport-jwt-strategy.js
│   └── passport-local-strategy.js
├── controllers                # Controllers
│   ├── api
│        └── v1
├── models                   # DataBase Schemas
│   └── patients.js
│   └── Report.js
│   └── User.js
├── index.js                  # Entry point
└── routes                     # Express Router
    └── index.js
    └── api
│        └── v1
|
```
## Setting up in local directory
```
1. Clone Repo in Your Local Machine
2. Extract It
3. Open Folder In Terminal 
4. npm install 
4. npm start 
```

Note :  Sir the reports/:status route workes, i must be missing something in video because i tried it just before video and it was working fine , I did'nt make the video again because the time was about to be up and i did not wanted to end up being late.
