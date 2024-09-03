# TeamHRD_K<br/>((`HRD&GROUPWARE SYSTEM` Rest API 개발))
※ 기존에 수행한 https://github.com/choiwanmin/kosta_final_pjt_restapi_backend 프로젝트를 정비 및 정리

## 목차
* [프로젝트 소개](#프로젝트-소개)
* [기술 스택](#기술-스택)
* [주요 기능](#주요-기능)
* [주요 작업 내용](#주요-작업-내용)
* [프로젝트 아키텍쳐](#프로젝트-아키텍쳐)
* [클라이언트 화면 UI](#클라이언트-화면-UI)
* [기타](#기타)

## 프로젝트 소개
> ### 프로젝트 개요
* `java`기반의 `Spring Boot` 프레임워크를 활용한 웹 풀스택 개발 후 `Rest API`로 전환 개발 수행
* 개발 기간 : 2024.05 ~ 2024.07 (약 7주간)
* 개발 구성원 : 5명 (`BE/FE` - 각 담당 영역의 BE/FE 작업을 진행)
> ### 프로젝트 목표
* 팀 및 서비스 목표
  * 사내 사용자가 각기 별개의 작업 환경에서 통합된 하나의 프로젝트를 동시에 수행할 수 있도록 도움을 주는 소프트웨어를 제작
  * 관리자와 사원의 영역을 나누어 업무를 정형화함으로써 업무 생산성 향상을 목적에 둠
* 개인 목표 :

## 기술 스택
|구분|사용 기술|
|:---|:---|
|Front-end|`HTML`, `CSS`, `Javascript`, `Bootstrap`, `Ajax`, `JQuery`, `React`, `npm`|
|Back-end|`Java`, `Maven`, `Spring Boot`, `Spring Data JPA`, `JDBC API`, `Oracle Driver`, `Lombok`, `Spring Security`, `WebSocket` 등|
|DBMS|`Oracle`|
|SEVER|`Apache Tomcat`, `AWS EC2(Ubuntu)`, `Docker` 등|
|IDE|`Eclipse`, `IntelliJ`, `Oracle Sql Developer`|
|SCM|`Git & Github`|
|ETC.|`Notion`, `Kakaotalk`, `ChatGPT` 등|

## 주요 기능

## 주요 작업 내용

## 프로젝트 아키텍쳐

## 클라이언트 화면 UI

<details>
<summary>Front-End 결과물</summary>
<div markdown="1">

Front-End 결과물

</div>
</details>

## 기타
> ### DB ERD

<details>
<summary>DB ERD 보기</summary>
<div markdown="1">

 |![finalpjt_erd](https://github.com/user-attachments/assets/e089ae4f-fe98-44ad-860a-68801e706310)|
 |:---:|
 
</div>
</details>

> ### 프로젝트 구조

<details>
<summary>프로젝트 구조 보기</summary>
<div markdown="1">
 
```
📦kosta_final_pjt_restapi_backend_review
┣ 📂.git
┗ 📂kosta_finalpjt_restapi
┃ ┣ 📂.mvn
┃ ┃ ┗ 📂wrapper
┃ ┃ ┃ ┗ 📜maven-wrapper.properties
┃ ┣ 📂.settings
┃ ┣ 📂src
┃ ┃ ┣ 📂main
┃ ┃ ┃ ┣ 📂java
┃ ┃ ┃ ┃ ┗ 📂com
┃ ┃ ┃ ┃ ┃ ┗ 📂example
┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂demo
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂config
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜mariaDBConfig.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜oracleDBConfig.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂mariadb
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂domains
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜virtual_domains.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜virtual_domains_dto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜virtual_domains_jpa.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂mail
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜mailSenderFactory.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜mailSenderFactoryImpl.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜mail_controller.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜mail_service.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂users
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜virtual_users.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜virtual_users_dao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜virtual_users_dto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜virtual_users_service.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂oracledb
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂auth
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜JwtAuthenticationFilter.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MyFailureHandler.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MySuccessHandler.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MyTokenProvider.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MyUserDetails.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MyUserDetailsService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜SecurityConfiguration.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂charts
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Charts.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChartsController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChartsDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChartsDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChartShare.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜ChartsService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂chat
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Manager
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜BatchConfig.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Message
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Message.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MessageController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MessageDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MessageDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MessageService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜WebFileConfig.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜WebSocketConfig.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Room
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChatRoom.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChatRoomController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChatRoomDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChatRoomDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChatRoomName.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChatRoomNameDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChatRoomNameDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChatRoomNameService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜ChatRoomService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂RoomUser
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜RoomUser.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜RoomUserDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜RoomUserDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜RoomUserService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂depts
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Depts.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DeptsController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DeptsDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DeptsDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DeptsService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Joblvs.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜JoblvsDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜JoblvsDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜JoblvsService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂docx
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Docx.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DocxController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DocxDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DocxDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜DocxService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂members
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EduWorkExperienceInfo.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EduWorkExperienceInfoDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EduWorkExperienceInfoDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EduWorkExperienceInfoService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Members.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MembersController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MembersDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MembersDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜MembersService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂notice
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Notice.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜NoticeController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜NoticeDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜NoticeDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜NoticeService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂users
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Users.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UsersAbstractValidator.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UsersCheckIdValidator.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UsersCheckUsernmValidator.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UsersController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UsersDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UsersDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜UsersEqualPwdValidator.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜UsersService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂weather
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜WeatherController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂workinoutrecords
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ChartDeptMember.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DeptsYearWorkData.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜MemRecord.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜OverWorkData.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜WorkInOutRecord.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜WorkInOutRecordController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜WorkInOutRecordDao.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜WorkInOutRecordDto.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜WorkInOutRecordService.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜HomeController.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜KostaFinalpjtApplication.java
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜ServletInitializer.java
┃ ┃ ┃ ┣ 📂resources
┃ ┃ ┃ ┃ ┗ 📜application.properties
┃ ┃ ┃ ┗ 📂webapp
┃ ┃ ┗ 📂test
┃ ┃ ┃ ┣ 📂java
┃ ┃ ┃ ┃ ┗ 📂com
┃ ┃ ┃ ┃ ┃ ┗ 📂example
┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂demo
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜KostaFinalpjtApplicationTests.java
┃ ┃ ┃ ┗ 📂resources
┃ ┣ 📂target
┃ ┃ ┣ 📂classes
┃ ┃ ┣ 📂generated-sources
┃ ┃ ┣ 📂generated-test-sources
┃ ┃ ┣ 📂kosta_finalpjt-0.0.1-SNAPSHOT
┃ ┃ ┣ 📂m2e-wtp
┃ ┃ ┣ 📂maven-archiver
┃ ┃ ┣ 📂maven-status
┃ ┃ ┣ 📂surefire-reports
┃ ┃ ┣ 📂test-classes
┃ ┃ ┣ 📜kosta_finalpjt-0.0.1-SNAPSHOT.war
┃ ┃ ┗ 📜kosta_finalpjt-0.0.1-SNAPSHOT.war.original
┃ ┣ 📜.classpath
┃ ┣ 📜.factorypath
┃ ┣ 📜.gitignore
┃ ┣ 📜.project
┃ ┣ 📜HELP.md
┃ ┣ 📜mvnw
┃ ┣ 📜mvnw.cmd
┃ ┗ 📜pom.xml
```

</div>
</details>