---
title: "VR1Family Charity Aid Services Web Application"
excerpt: "We create a web application which allows aid service  <br/><img src='/images/Aid_service.png' width='500'>"
collection: projects
date: 2023-07-03
---


<div style="display: flex; flex-direction: row; gap: 20px;">
    <span onclick="window.open('https://github.com/XiaoLinZzz/VR1Family-Charity-Aid-Services', '_blank')" style="cursor: pointer;"><img src="https://img.shields.io/badge/Github-000000?style=for-the-badge&logo=github&logoColor=white" alt="Github"></span>
    <span onclick="window.open(https://spmproject.herokuapp.com/', '_blank')" style="cursor: pointer;"><img src="https://img.shields.io/badge/Demo-430098?style=for-the-badge&logo=Heroku&logoColor=white" alt="Github"></span>
</div>


<!-- # VR1Family Charity Aid Services Web Application -->

This is our final project for the course [SWEN90016 Software Processes and Management](https://handbook.unimelb.edu.au/2023/subjects/swen90016) @ The University of Melbourne.

## Tech

<div style="display: flex; flex-direction: row; gap: 10px;">
    <!-- <img src="https://img.shields.io/static/v1?label=Java&message=SE11&color=F7DF1E&style=for-the-badge&logo=Oracle" alt="Java Badge"> -->
    <img src="https://img.shields.io/static/v1?label=VSCode&message=1.60.0&color=007ACC&style=for-the-badge&logo=visual-studio-code" alt="VSCode Badge">
    <img src="https://img.shields.io/static/v1?label=Node.js&message=v14.16.0&color=339933&style=for-the-badge&logo=Node.js" alt="VSCode Badge">
    <img src="https://img.shields.io/static/v1?label=Express&message=2.40.0&color=000000&style=for-the-badge&logo=Express" alt="VSCode Badge">
    <img src="https://img.shields.io/static/v1?label=MongoDB&message=v4.4.4&color=47A248&style=for-the-badge&logo=MongoDB" alt="VSCode Badge">
    <img src="https://img.shields.io/static/v1?label=Heroku&message=V8.1.3&color=430098&style=for-the-badge&logo=Heroku" alt="VSCode Badge">
</div>



## Try our application

<!-- add screenshot -->
![screenshot](/images/Aid_service.png)

Our application is deployed on Heroku. You can try it out [here](https://spmproject.herokuapp.com/). (Due to there is a charge for using Heroku, our demo will expire in June 2023.)


## Features
- Manage aid items, including name, category, quantity, and details
- Manage aid kits, which are collections of aid items
- Manage recipient information, including general and private data
- View and manage aid categories and their respective quantities and statuses
- Basic user interface for easy navigation and data management


## Installation
1. Make sure you have [Node.js](https://nodejs.org/en) and [MongoDB](https://www.mongodb.com/) installed on your machine.

2. Clone the repository:
```
git clone https://github.com/XiaoLinZzz/VR1Family-Charity-Aid-Services.git
```

3. Navigate to the project directory and install dependencies:
```
cd VR1Family-Charity-Aid-Services
npm install
```

4. Create a .env file in the root folder of the project and add the following environment variables:
```
PORT=3001
URL=http://localhost
MONGO_URI=<your_mongodb_connection_string>
```
Replace `<your_mongodb_connection_string>` with the connection string for your MongoDB database.

5. Start the server:
```
npm start
```
The server should now be running on `http://localhost:3001`.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.