---
title: "Management Platform for Cleaning Services"
excerpt: "Led the development of a comprehensive cleaning service management platform using React Native for mobile, React.js for web portal. Implemented <b>real-time staff tracking</b>, <b>shift management</b>, and <b>automated reporting</b> features while collaborating with stakeholders through Figma-driven design process. <br/><img src='/images/manager_pj/Cover.png' width='500'>"
collection: projects
date: 2024-07-22
---

<!-- {/_ Logo and Title Section _/} -->

<h2 align="center">The Shadow Manager</h2>

<!-- Badges Section -->
<div align="center" style="display: flex; gap: 10px; justify-content: center;">
  <a href="http://sm-webportal.s3-website-ap-southeast-2.amazonaws.com/">
    <img
      src="https://img.shields.io/static/v1?label=Web%20Portal&message=v1.0.0&style=for-the-badge&color=61DBFB&logo=google-chrome"
      alt="Web Portal"
    />
  </a>
</div>

## 📖 Introduction

The Shadow Manager is an in-development software system, comprised of a cross-platform mobile app and admin portal, to be used by Xpress Cleaning for internal management of its staff, contracts, and data generated during cleaning shifts. This project is undertaken by a team of five students at the University of Melbourne for the subject Software Project (COMP90082) over a period of twelve weeks consisting of four sprints. This cover page acts as an overview for all project documentation and contains essential links. For more documents, please refer to our [Confluence](https://cp-redback.atlassian.net/wiki/spaces/SD/overview?homepageId=163953).

## 👋 Our Team

<div className="table-container">
  <table>
    <thead>
      <tr>
        <th>Member</th>
        <th>Email</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Ziming Wang</td>
        <td>
          <a href="mailto:zimiwang@student.unimelb.edu.au">
            zimiwang@student.unimelb.edu.au
          </a>
        </td>
      </tr>
      <tr>
        <td>Lujie Ma</td>
        <td>
          <a href="mailto:lujiem@student.unimelb.edu.au">
            lujiem@student.unimelb.edu.au
          </a>
        </td>
      </tr>
      <tr>
        <td>Zheng Liu</td>
        <td>
          <a href="mailto:zlliu5@student.unimelb.edu.au">
            zlliu5@student.unimelb.edu.au
          </a>
        </td>
      </tr>
      <tr>
        <td>Siyuan Wang</td>
        <td>
          <a href="mailto:swwa5@student.unimelb.edu.au">
            swwa5@student.unimelb.edu.au
          </a>
        </td>
      </tr>
      <tr>
        <td>Dylan Cookson-Mleczko</td>
        <td>
          <a href="mailto:dcooksonmlec@student.unimelb.edu.au">
            dcooksonmlec@student.unimelb.edu.au
          </a>
        </td>
      </tr>
    </tbody>
  </table>
</div>

## 📦 Where is it Deployed?

For deployment info, please refer to the [Deployment Page](https://cp-redback.atlassian.net/wiki/spaces/SD/pages/1736746/Deployment+CI+CD) on our Confluence.

### Web Version

Our web application is deployed and accessible at: [Web](http://sm-webportal.s3-website-ap-southeast-2.amazonaws.com/)

### Demo Account

For testing purposes, you can use the following credentials:

**Admin Account**

- Username: admin@test.com
- Password: password

**Cleaner Account**

- Username: Siyuan@test.com
- Password: wsy123

## 📦 How to Run and How to Deploy Everything?

Please visit our [Final Delivery & How to run & deploy](https://cp-redback.atlassian.net/wiki/spaces/SD/pages/41025547/Final+Delivery+How+to+run+deploy) page on Confluence for a comprehensive guide on each module's setup and deployment.

## 🛜 API Documentation

For API details, please refer to our [API Documentation](https://cp-redback.atlassian.net/wiki/spaces/SD/pages/14942294/API+Document) on Confluence.

## 🌲 Our Folder Structure

Our project follows a client-server architecture with a clear separation between frontend and backend. Here's our structure:

```plaintext
CP-REDBACK/
├── docs/                        # Project documentation.
├── frontend/                    # Frontend codebase.
│   ├── my-app/                  # React Native app.
│   │   ├── components/          # Reusable React components.
│   │   ├── pages/               # React components that represent entire pages.
│   │   ├── scripts/             # Utility scripts and helper functions.
│   │   ├── hooks/               # Custom React hooks for shared logic across components.
│   │   ├── ...                  # Other folders and files in the React Native app.
│   └── Web/                     # Web portal frontend.
│       ├── src/                 # Source files for the web application.
│       │   ├── components/      # Reusable components specific to this web app.
│       │   ├── assets/          # Static files like images, fonts, etc.
│       │   ├── pages/           # Components representing full pages in this web app.
│       │   ├── ...              # Other folders and files in the web application.
├── backend/                     # Backend codebase.
│   ├── .mvn/wrapper/            # Maven wrapper files.
│   ├── logs/                    # Log files.
│   ├── src/
│   │   └── main/
│   │       └── java/com/backend/shadowmanager/
│   │           ├── config/      # Configurations.
│   │           ├── controller/  # API Controllers.
│   │           ├── mapper/      # MyBatis Mappers.
│   │           ├── model/       # Data Models.
│   │           ├── security/    # Security Configs.
│   │           ├── service/     # Service Layer.
│   │           └── utils/       # Utility Classes.
│   ├── resources/               # Resource files (properties, XML).
│   ├── test/                    # Test cases.
│   ├── .gitignore               # Git ignore rules.
│   ├── README.md                # Documentation.
│   ├── mvnw / mvnw.cmd          # Maven wrapper scripts.
│   └── pom.xml                  # Maven project config.
└
```

## 📅 Sprint Timelines

- **🏁 Sprint 1**: _2024-07-22 to 2024-08-23_
- **🔄 Sprint 2**: _2024-08-23 to 2024-09-20_
- **🚀 Sprint 3**: _2024-09-20 to 2024-10-18_
- **🎯 Sprint 4**: _2024-10-18 to 2024-11-01_

## Screenshots

Here are some examples of screenshots.

<p align="center">
  <img width="350" src="/images/manager_pj/Cover.png" alt=""/> &nbsp;&nbsp;
  <img width="350" src="/images/manager_pj/account.png" alt=""/> &nbsp;&nbsp;
  <img width="350" src="/images/manager_pj/map.png" alt=""/> &nbsp;&nbsp;
  <img width="350" src="/images/manager_pj/report.png" alt=""/> &nbsp;&nbsp;
  <img width="350" src="/images/manager_pj/shift-management.png" alt=""/> &nbsp;&nbsp;
</p>

## 📚 Additional Documentation

- 🎨 [Design Document](https://www.figma.com/design/vilqKC8tQj35St633QagE4/App-%2B-Web-Design?node-id=9612-20076&t=ftfhEzzLX8qSjr0c-1): Our design Figma file.
- 📝 [Changelog](https://github.com/feit-comp90082/CP-RedBack/blob/main/CHANGELOG.md): Our changelog.
- 📕 [Coding Convention](https://github.com/feit-comp90082/CP-RedBack/blob/main/docs/Conventions.md): Our coding convention.
- 📱 [Native App Documentation](https://github.com/feit-comp90082/CP-RedBack/blob/main/Frontend/my-app/README.md): Details about our React Native app.
- 🌐 [Web Portal Documentation](https://github.com/feit-comp90082/CP-RedBack/blob/main/Frontend/Web/README.md): Information on the web portal frontend.
- 💻 [Backend Documentation](https://github.com/feit-comp90082/CP-RedBack/blob/main/backend/README.md): Technical details about the backend system.
- ⛅ [Deployment Documentation](https://cp-redback.atlassian.net/wiki/spaces/SD/pages/1736746/Deployment+CI+CD): Information about our deployment
- 🔍 [Code Review Policy](https://cp-redback.atlassian.net/wiki/spaces/SD/pages/16089098/Code+Review): How we conduct our code review
- 📝 [Pull Request Checklist](https://github.com/feit-comp90082/CP-RedBack/blob/main/docs/PullRequestChecklist.md): Checklist for pull requests.
