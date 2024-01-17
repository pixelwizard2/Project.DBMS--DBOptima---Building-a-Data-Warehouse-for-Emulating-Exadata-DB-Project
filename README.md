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
- (1.1) Schema Creation

![1 2 데이터 기본 통계치 확인](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Building-a-Data-Warehouse-for-Emulating-Exadata-DB-Project/assets/138272416/58aacd70-b617-424e-853f-bfc0ac3565d3)
- (1.2) Basic Statistical Data Verification

![1 3 특정 조건을 만족하는 데이터 찾기](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing-with-Exadata-Inspired-Exploration/assets/138272416/75ded393-b291-4ac0-b143-44e0793de833)
- (1.3) Identifying Data that Meets Specific Conditions

![1 4 데이터 정렬하기](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Building-a-Data-Warehouse-for-Emulating-Exadata-DB-Project/assets/138272416/b083da3a-8f66-4ed3-8cdb-2ae6f63087ed)
- (1.4) Sorting Data



**(2) Database Performance Monitoring & Query Performance Evaluation and Tuning**

![2-1  MySQL의 데이터 디렉터리 경로를 확인하는 쿼리 실행](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing-with-Exadata-Inspired-Exploration/assets/138272416/5f238f65-d30f-4a2e-9383-007f34e58cec)
- (2-1) Executing Queries to Verify MySQL Data Directory Path

![2-2  스로우 쿼리 로그(Slow Query Log) 활성화](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing-with-Exadata-Inspired-Exploration/assets/138272416/6d510909-a9fa-43c1-b2f9-190caedb186d)
- (2-2) Activating Slow Query Log

![2-3  슬로우 쿼리 로그 생성 및 실시간 성능 모니터링](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing-with-Exadata-Inspired-Exploration/assets/138272416/7070e96d-d90c-4d4f-9703-9bcf134eba06)
- (2-3) Generating Slow Query Logs and Real-Time Performance Monitoring

![2-4  LSTAT 컬럼에 대한 인덱스 효율성 분석(성능 향상 없음)](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing-with-Exadata-Inspired-Exploration/assets/138272416/e28b4e0e-e0f0-48c2-af1b-360fc452e0e2)
- (2-4) Analyzing Index Efficiency for LSTAT Column (No Performance Improvement)

![2-5   LSTAT 컬럼에 인덱스를 추가, 검색 성능 향상 시도(시간 개선 없음)](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing-with-Exadata-Inspired-Exploration/assets/138272416/57a51bdb-3c57-4eee-ac2a-3e76e68cfffa)
- (2-5) Attempting to Improve Search Performance by Adding an Index to LSTAT Column (No Time Improvement)

![2-6  LSTAT 범위 쿼리에 대한 인덱스 튜닝으로 성능 개선 확인됨](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing-with-Exadata-Inspired-Exploration/assets/138272416/c2432db4-5aff-4341-9bfd-97d47a268cf9)
- (2-6) Improved Performance Confirmed by Tuning Index for LSTAT Range Query



**(3) Data Security and Encryption Techniques**

![데이터 보안 강화를 위한 AES 암호화 향상](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing-with-Exadata-Inspired-Exploration/assets/138272416/345f86d0-849b-4c26-b44f-bbcddedb5e35)
- (3-1) Enhancing Data Security with Advanced AES Encryption



**(4) Data Integrity Maintenance and Recovery Strategy**

![데이터베이스 복구 전략 및 코드 실행 과정에서 중복 키 관련 에러가 발생하였으며, 이를 해결하기 위해 INSERT IGNORE 및 ON DUPLICATE KEY UPDATE를 활용하여 중복 레코드를 처리하였습니다](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing-with-Exadata-Inspired-Exploration/assets/138272416/56ff1f80-496d-4f0e-9956-8fbebcfb3925)
- (4.1) Database Recovery Strategy and Error Resolution During Code Execution, Handling Duplicate Records Using INSERT IGNORE and ON DUPLICATE KEY UPDATE



**(5) Large Data Processing (+Data Warehouse Construction)**

![5-1   데이터베이스에서 테이블 생성, 데이터 적재, 및 범위별 파티션 설정을 위한 SQL 작업](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing--Exadata-Inspired/assets/138272416/0ca08907-a68d-4bd3-bdf8-aef893bb04bf)
- (5-1) SQL Work for Table Creation, Data Loading, and Range Partitioning in Database

![5-2  데이터 웨어하우스 구축을 위한 파티션 정보 조회 쿼리](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing--Exadata-Inspired/assets/138272416/cf845a85-7c6d-48b2-93a3-ea94f59719bf)
- (5-2) Querying Partition Information for Data Warehouse Construction

![5-3  데이터 웨어하우스 구축 과정  'housing_new' 테이블 파티션 조회 단계](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing--Exadata-Inspired/assets/138272416/dca7a294-250e-4d7f-86c9-0906b6370c90)
- (5-3) Data Warehouse Construction Process, Querying Partitions of 'housing_new' Table

![5-4(1)  데이터 초기 적재 및 차원, 사실 테이블 생성 쿼리](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing--Exadata-Inspired/assets/138272416/115ffb67-a9ce-4191-bb73-3f8e89987c61)
![5-4(2)](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing--Exadata-Inspired/assets/138272416/a1810ad6-c167-4a49-b693-ad49c3c04b16)
- (5-4) Initial Data Loading and Creation of Dimension and Fact Tables

![5-5  new_schema 스키마에서 housing 테이블의 처음 10개 레코드 조회](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing--Exadata-Inspired/assets/138272416/24ea9f9f-3020-4c16-8ea3-b7e21b1292be)
- (5-5) Querying the First 10 Records of the Housing Table in the New_schema Schema

![5-6  데이터 웨어하우스 쿼리 실행 및 활용](https://github.com/pixelwizard2/Project.DBMS--ExaProve---Foundational-Data-Warehousing--Exadata-Inspired/assets/138272416/81a22599-a834-4e22-a4fb-834c5f6ae9af)
- (5-6) Executing and Utilizing Data Warehouse Queries



## 5. Expected Results and Learning Points (예상 결과 및 학습 포인트)
The completed project is expected to yield the following results:

- Experience in writing and optimizing queries for complex datasets
- Enhanced ability to respond to real-world work environment incidents and performance tuning
- A deeper understanding of database security enhancement
- Development of practical cases for maintaining data integrity and recovery strategies
- Implementation of predictive models for data-based decision-making support



## 6. Project Expansion Plans (프로젝트 확장 계획)
After the completion of the project, the following expansions are planned:

- Developing a decision support system based on data analysis results and insights
- Acquiring skills in data movement and transformation between databases through DB migration scenarios
- Strengthening database security expertise through additional security feature implementation and practice



## 7. Conclusion and Expected Effects (결론 및 기대 효과)
This project aims to deepen the expertise of a database administrator and improve skills in managing and optimizing complex database systems. It will demonstrate advanced technical capabilities and problem-solving skills required in a data-centric business environment.
