# Project.DBMS--ExaProve---Foundational-Data-Warehousing-with-Exadata-Inspired-Exploration
Exadata DB 모방을 위한 데이터 웨어하우스 구축 프로젝트(MySQL 활용)
 
<p align="right">
  <a href="https://blog.naver.com/pixelwizard/223321757202">
    <img src="https://img.shields.io/badge/한국어%20번역본-03C75A?style=flat-square&logo=Naver&logoColor=white" alt="네이버 블로그">
  </a> </p>  
  
![사진1](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Building-a-Data-Warehouse-for-Emulating-Exadata-DB-Project/assets/138272416/3e7851bf-7bf6-4bc6-bbc3-1f10dc658082)

 
**※ Development Period : 2024.01.12 ~ 2024.01.15 (30h)**
<br> <br> <br>

## 1. Project Overview (프로젝트 개요)

This project utilizes a housing dataset to explore the role of a database administrator and practice key functions and optimization strategies of Database Management Systems (DBMS). By emulating the advanced features required in high-end database systems like Exadata DB within a MySQL environment, this mini project aims to enhance the management and optimization skills for complex database systems. The primary focus is on gaining an in-depth technical understanding of database performance monitoring, tuning, security management, backup, and recovery.

![포스터 2](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Building-a-Data-Warehouse-for-Emulating-Exadata-DB-Project/assets/138272416/876a8494-09cb-4034-ad26-badd96a4505e)


## 2. Project Objective (프로젝트 목적)
The goal of this project is to master simple data CRUD operations and develop a deep technical understanding and problem-solving skills. The project is designed to demonstrate the ability to derive business insights based on data analysis and apply solutions in a real work environment.



## 3. Technical Background and Utilized Techniques(기술적 배경 및 활용 기술)
The project is built on the following technical background:

## Basic Skills (Completed)
Schema Creation and Data Verification
Database Performance Monitoring & Query Performance Evaluation and Tuning
Data Security and Encryption Techniques
Data Integrity Maintenance and Recovery Strategy
Large Data Processing (+Data Warehouse Construction)


## Advanced Skills (Planned)**

**(1) High Availability Setup**

Objective: To ensure continuous availability and data integrity of the database.
Reason for Selection: Preventing data loss during failures and ensuring uninterrupted service is critical in all large-scale database systems. This mirrors the high availability features of Exadata.

**(2) Disaster Recovery Plan**

Objective: To develop swift and effective data recovery methods for data loss scenarios.
Reason for Selection: The ability to protect and recover data in any disaster situation is a core aspect of Exadata DB management.

**(3) Security Enhancement Project**

Objective: To strengthen database security and minimize security vulnerabilities.
Reason for Selection: Database security is crucial in advanced systems like Exadata. We will practice enhancing security levels through user rights management, encryption, and SQL injection prevention techniques.

**(4) Automation and Monitoring**

Objective: To automatically monitor database status and detect potential issues in advance.
Reason for Selection: Implementing a system similar to Exadata's 'Smart Metrics' for continuous monitoring of database performance and health.



## 4. Project Implementation (프로젝트 구현)
The project was carried out in the following stages:


**(1) Schema Creation and Data Verification**

![1 1 스키마 생성](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Building-a-Data-Warehouse-for-Emulating-Exadata-DB-Project/assets/138272416/efddc071-fb89-4054-9ef7-90c414db3c30)
(1.1) Schema Creation

![1 2 데이터 기본 통계치 확인](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Building-a-Data-Warehouse-for-Emulating-Exadata-DB-Project/assets/138272416/58aacd70-b617-424e-853f-bfc0ac3565d3)
(1.2) Basic Statistical Data Verification

![1 3 특정 조건을 만족하는 데이터 찾기](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Building-a-Data-Warehouse-for-Emulating-Exadata-DB-Project/assets/138272416/)
(1.3) Identifying Data that Meets Specific Conditions

![1 4 데이터 정렬하기](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Building-a-Data-Warehouse-for-Emulating-Exadata-DB-Project/assets/138272416/b083da3a-8f66-4ed3-8cdb-2ae6f63087ed)
(1.4) Sorting Data


**(2) Database Performance Monitoring & Query Performance Evaluation and Tuning**
(2-1) Executing Queries to Verify MySQL Data Directory Path
(2-2) Activating Slow Query Log
(2-3) Generating Slow Query Logs and Real-Time Performance Monitoring
(2-4) Analyzing Index Efficiency for LSTAT Column (No Performance Improvement)
(2-5) Attempting to Improve Search Performance by Adding an Index to LSTAT
Column (No Time Improvement)

(2-6) Improved Performance Confirmed by Tuning Index for LSTAT Range Query
(3) Data Security and Encryption Techniques
(3-1) Enhancing Data Security with Advanced AES Encryption
(4) Data Integrity Maintenance and Recovery Strategy
(4.1) Database Recovery Strategy and Error Resolution During Code Execution, Handling Duplicate Records Using INSERT IGNORE and ON DUPLICATE KEY UPDATE
(5) Large Data Processing (+Data Warehouse Construction)
(5-1) SQL Work for Table Creation, Data Loading, and Range Partitioning in Database
(5-2) Querying Partition Information for Data Warehouse Construction
(5-3) Data Warehouse Construction Process, Querying Partitions of 'housing_new' Table
(5-4) Initial Data Loading and Creation of Dimension and Fact Tables
(5-5) Querying the First 10 Records of the Housing Table in the New_schema Schema
(5-6) Executing and Utilizing Data Warehouse Queries
Expected Results and Learning Points
The completed project is expected to yield the following results:

Experience in writing and optimizing queries for complex datasets
Enhanced ability to respond to real-world work environment incidents and performance tuning
A deeper understanding of database security enhancement
Development of practical cases for maintaining data integrity and recovery strategies
Implementation of predictive models for data-based decision-making support
Project Expansion Plans
After the completion of the project, the following expansions are planned:

Developing a decision support system based on data analysis results and insights
Acquiring skills in data movement and transformation between databases through DB migration scenarios
Strengthening database security expertise through additional security feature implementation and practice
Conclusion and Expected Effects
This project aims to deepen the expertise of a database administrator and improve skills in managing and optimizing complex database systems. It will demonstrate advanced technical capabilities and problem-solving skills required in a data-centric business environment.
