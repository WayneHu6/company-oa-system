# company-oa-system

## Introduction
### Enterprise Office Automation (OA) System Based on WeChat Mini Program

This system aims to provide convenient office services for enterprise employees through the WeChat Mini Program, including but not limited to attendance check-in, task management, salary inquiry, and more. It also provides a backend management system for enterprise managers to manage employee information, leave records, etc.

#### Functional Structure Diagram
Management End
[](./images/m1.png)
Client End
[](./images/c1.png)

## Software Architecture
The system is divided into three ends: Client End (WeChat Mini Program), Management End (Web Application), and Service End.

- **Client End**: Implemented using native WeChat Mini Program, provided for use by enterprise employees.
- **Management End**: Implemented using the Layui framework, provided for enterprise managers to perform various management operations.
- **Service End**: Built using the Java SpringBoot framework, responsible for handling business logic and data interaction.

##### Technology Stack Used:
- **Client End**: WeChat Mini Program
- **Management End**: HTML, CSS, JavaScript, Layui, Ajax, jQuery
- **Service End**: Java JDK8, SpringBoot, Mybatis
- **Database**: MySQL
- **Development Tools**: Idea, HBuilderX, WeChat Mini Program Developer Tool, XAMPP, Navicat

## Installation Guide
1. Start the MySQL service, create a database named `company_oasystem`, and import the database file `company_oasystem.sql`.
2. Open the `CompanyOAServer` project in Idea, modify the database connection information in `application.yml`, then start the project.
3. Open the management end project `CompanyOAManager` in HBuilderX, adjust the server configuration within `AppConfig.js`, and set up a web server (such as Nginx or Apache; XAMPP integrated environment is recommended).
4. Use the WeChat Mini Program Developer Tool to open the `CompanyOA` project, edit the server address and port number in the `request.js` file, then run the project.
5. Test the login of both the client and management ends to ensure the system operates normally.

## Effect Diagrams
- **Client End**
  ![](./images/c2.png)
  ![](./images/c3.png)
  ![](./images/c4.png)
  ![](./images/c5.png)
  ![](./images/c6.png)
  ![](./images/c7.png)
  ![](./images/c8.png)
  ![](./images/c9.png)
  ![](./images/c10.png)
  ![](./images/c11.png)
  ![](./images/c12.png)
  ![](./images/c13.png)
  ![](./images/c14.png)
  ![](./images/c15.png)
  ![](./images/c16.png)
- **Management End**
  ![](./images/m2.png)
  ![](./images/m3.png)
  ![](./images/m4.png)
  ![](./images/m5.png)
  ![](./images/m6.png)
  ![](./images/m7.png)

## Resources
#### Feature Overview
![](./images/d2.png)
#### Client UI Concept
![](./images/d3.png)
#### Database Entity Design
![](./images/d1.png)

#### Final Words
All codes and databases are proprietary and not open source. If you find them useful, please give us a star and contact me, thank you! !!! For learning and exchange only, do not use commercially or for illegal purposes! Should you encounter any issues during deployment, feel free to contact me. Custom development and technical support are also available upon request.
Email: 1373577355@qq.com
WeChat: Awake778

#### Technical Support Charges Apply
Everyone's time is precious, no freeloaders please!!!
![](./images/wx.jpg)

# Technical Support Options
- Option 1: I will develop according to requirements, deploy it, provide a brief explanation, and be available for any technical questions afterwards.
- Option 2: Work alongside me, I'll guide you through the process, explaining as we go. Any technical questions post-development can be asked, minor adjustments are free of charge.

### Our Technology Stack:
#### Frontend Technologies
- **Web Development**: VUE, Element, Bootstrap, LayUI
- **WeChat Mini Program**: Native development, Taro
- **Mobile App Development**:
    - Android（Java）
    - iOS（Swift）
- **Cross-platform Development**: uniapp

#### Backend Technologies
- **Java Ecosystem**:
    - Frameworks: Spring, SpringBoot, SpringSecurity
    - Data Persistence: MyBatis, JPA
- **Other Backend Languages**: PHP, Python, Node.js

#### Database Management
- **Relational Databases**: MySQL, SQLServer, SQLite, Oracle
- **Non-relational Databases**: MongoDB
- **Caching & Searching**: Redis, ElasticSearch

#### Server & Deployment
- **Operating System Deployment, Maintenance & Debugging**: Linux, Windows
- **Containerization & Orchestration**: Docker deployment, Kubernetes (k8s) deployment
- **Web Server Configuration**: Nginx, Apache, Tomcat, IIS
- **CI/CD & Version Control**: Jenkins deployment, Git deployment, SVN deployment

#### Other Technical Skills
- **Data Analysis**: Java-based analysis tools, Python-based analysis tools
- **Web Scraping Development**: Based on Java
- **Automated Testing**: Interface testing (based on Java), Automated testing (based on Java)
- **Automated Operations & Monitoring**:
    - Automated deployment (based on Java)