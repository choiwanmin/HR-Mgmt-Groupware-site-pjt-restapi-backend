# TeamHRD_K<br/>(`HRD&GROUPWARE SYSTEM` Rest API 개발)
*※ 기존에 수행한 https://github.com/choiwanmin/kosta_final_pjt_restapi_backend 프로젝트를 정비 및 정리*

## 목차
* [프로젝트 소개](#프로젝트-소개)
* [기술 스택](#기술-스택)
* [주요 기능](#주요-기능)
* [프로젝트 아키텍쳐](#프로젝트-아키텍쳐)
* [클라이언트 화면 UI](#클라이언트-화면-UI)
* [기타](#기타)

## 프로젝트 소개
> ### 프로젝트 개요
* `java`기반의 `Spring Boot` 프레임워크를 활용한 웹 풀스택 개발 후 `Rest API`로 전환 개발 수행
* 개발 기간
  * Fullstack 작업 기간 : 2024.05.24 ~ 2024.06.26 (34일)<br/>*(Fullstack 작업 repository - https://github.com/choiwanmin/kosta_final_pjt_fullstack_review)*
  * Rest-API 전환 작업 기간 : 2024.07.03 ~ 2024.07.14 (12일)
* 개발 구성원 : 5명 (`BE/FE` - 각 담당 영역의 BE/FE 작업을 진행)
> ### 프로젝트 목표
* 팀 및 서비스 목표
  * 사내 사용자가 각기 별개의 작업 환경에서 통합된 하나의 프로젝트를 동시에 수행할 수 있도록 도움을 주는 소프트웨어를 제작
  * 관리자와 사원의 영역을 나누어 업무를 정형화함으로써 업무 생산성 향상을 목적에 둠

## 기술 스택
|구분|사용 기술|
|:---|:---|
|Front-end|`HTML`, `CSS`, `Javascript`, `Bootstrap`, `Ajax`, `JQuery`, `React`, `npm`|
|Back-end|`Java`, `Maven`, `Spring Boot`, `Spring Data JPA`, `JDBC API`, `Oracle Driver`, <br/>`Lombok`, `Spring Security`, `WebSocket` 등|
|DBMS|`Oracle`|
|Server|`Apache Tomcat`, `AWS EC2(Ubuntu)`, `Docker` 등|
|IDE|`Eclipse`, `IntelliJ`, `Oracle Sql Developer`|
|SCM|`Git & Github`|
|ETC.|`Notion`, `Kakaotalk`, `ChatGPT` 등|

## 주요 기능
> ### 인사 관리 기능

  <details>
  <summary>인사 관리 기능 보기</summary>
  <div markdown="1">
  
  * 사원 정보 관리 기능
    * 시스템 로그인 정보 관리
    * 인사 정보 관리
    * 시스템 승인 상태 관리
  * 근태 관리 기능
    * 사원 개인별 출퇴근 기록
    * 출퇴근 기록 조회 및 휴가 관리
    * 관리자 및 부서장은 부서별 근태 기록 조회 및 통계 제공
  * 조직 관리
    * 부서 관리
    * 직급 관리 
  
  </div>
  </details>
  
> ### 협업 도구 기능

  <details>
  <summary>협업 도구 기능 보기</summary>
  <div markdown="1">
  
  * 공지 게시판 기능
    * 전체 및 부서별 조회 및 작성 기능 
  * 실시간 메신저 기능
    * 실시간 1:1 메신저 및 그룹 메신저 제공
    * 현재 대화 참여자 정보 조회
    * 메신저 및 메시지 관리를 통한 최신화
  * 전자 문서 기능
    * 문서 기본 양식 제공으로 빠른 문서 작성
    * 결재 권한 및 순서를 제공해 원격 결재 시스템 제공
    * 내가 작성한 문서 모아보기 기능
    * 결재 문서 현황 확인 제공
  * 스케줄러 기능
    * 사내 또는 개인 주요 일정관리 기능 제공
    * 일정 추가시 달력과 간트차틍 적용하여 편의성 제공
    * 임직원간 일정 공유 기능 제공
  * 메일 기능
    * 그룹웨어 자체 메일 서버 제공
    * 자체 도메인 제공으로 사내메일 사용 가능
    * 메일함에서 받은 메일 관리
    * 반송, 공유 등 편의 기능 제공

 </div>
 </details>

## 프로젝트 아키텍쳐
|![finalpjt_architecture](https://github.com/user-attachments/assets/fda679aa-ceae-4c2e-b0f2-0e44103fd022)|
|:---:|

## 클라이언트 화면 UI
*※ 2024/07/15 기준 데이터 UI*
*(Front-End 작업 repository - https://github.com/choiwanmin/kosta_final_pjt_restapi_frontend_review)*

> ### 메인 관련 페이지

<details>
<summary>메인 관련 페이지 보기</summary>
<div markdown="1">
 
 |메인(로그인)|회원가입|
 |:---:|:---:|
 |![finalpjt_restapi_ui (2)](https://github.com/user-attachments/assets/01b69e1e-4e31-402c-a052-68c32ed0515b)|![finalpjt_restapi_ui (3)](https://github.com/user-attachments/assets/24bc0505-904a-43ad-be8b-6879ec16967d)|

</div>
</details>

> ### 관리자 페이지

<details>
<summary>관리자 페이지 보기</summary>
<div markdown="1">
 
 |관리자 메인|사원 근태 관리(근무 시간)|
 |:---:|:---:|
 |![finalpjt_restapi_ui (4)](https://github.com/user-attachments/assets/7cb75388-8c42-46d3-b18c-5c0101c7735a)|![finalpjt_restapi_ui (5)](https://github.com/user-attachments/assets/285c7427-8fe5-4577-9040-e53d781ab5aa)|

 |사원 근태 관리(초과 근무)|사원 근태 관리(부서 선택)|
 |:---:|:---:|
 |![finalpjt_restapi_ui (6)](https://github.com/user-attachments/assets/93b8ae50-fa55-4022-ba76-2fa1de54dcfa)|![finalpjt_restapi_ui (7)](https://github.com/user-attachments/assets/009d5462-e9d5-4180-b24c-58d3749dca7e)|

 |직원 목록|사용자 로그인 정보|사용자 로그인 정보 수정|직원 이력 정보|직원 이력 정보 수정|
 |:---:|:---:|:---:|:---:|:---:|
 |![finalpjt_restapi_ui (14)](https://github.com/user-attachments/assets/c8ba853f-739b-4795-9d68-893b0ec43e79)|![finalpjt_restapi_ui (15)](https://github.com/user-attachments/assets/d7fcbf54-484d-48d9-b5f5-ce2cbc3116cf)|![finalpjt_restapi_ui (17)](https://github.com/user-attachments/assets/8af0a902-4ea5-48ba-81ad-1d67cbae0ae0)|![finalpjt_restapi_ui (16)](https://github.com/user-attachments/assets/4aeb8bde-ff84-49da-a374-c52280c81cce)|![finalpjt_restapi_ui (18)](https://github.com/user-attachments/assets/bc865875-1b9c-4121-b3e9-3b0dbc67e4fd)|

 |부서 목록|부서 추가|
 |:---:|:---:|
 |![finalpjt_restapi_ui (1)](https://github.com/user-attachments/assets/7a64af12-5ec0-400f-a381-0a4a89ad75a4)|![finalpjt_restapi_ui (19)](https://github.com/user-attachments/assets/d79c02fc-2bd7-4ed8-b392-5bb1f8d12aaa)|

 |직급 목록|직급 추가|
 |:---:|:---:|
 |![finalpjt_restapi_ui (20)](https://github.com/user-attachments/assets/497d1c4f-3908-496e-914a-fb595025b59c)|![finalpjt_restapi_ui (21)](https://github.com/user-attachments/assets/9a8f2127-01d5-470d-9078-8a86e88387de)|
 
</div>
</details>

> ### 직원 페이지

<details>
<summary>직원 메인 페이지 보기</summary>
<div markdown="1">

 |직원 메인|출퇴근 관리|
 |:---:|:---:|
 |![finalpjt_restapi_ui (8)](https://github.com/user-attachments/assets/718a3dfd-bee5-4f0f-a770-274ee45a131e)|![finalpjt_restapi_ui (11)](https://github.com/user-attachments/assets/d73141ae-1a13-4102-9d73-ee9567db253c)|

 |내 로그인 정보|내 이력 정보|
 |:---:|:---:|
 |![finalpjt_restapi_ui (9)](https://github.com/user-attachments/assets/f2e02f53-52a2-4b78-947b-4435c26bd3d9)|![finalpjt_restapi_ui (10)](https://github.com/user-attachments/assets/e9c40465-f0f2-4cc3-a766-07f8cd899942)|

 |부서장(직원) 메인|부서 근태관리|
 |:---:|:---:|
 |![finalpjt_restapi_ui (12)](https://github.com/user-attachments/assets/65057be0-de1f-477b-8252-62235ae3c8a2)|![finalpjt_restapi_ui (13)](https://github.com/user-attachments/assets/65a8307a-f2a3-42ae-a8a7-7ecab4cc0662)|
 
</div>
</details>

<details>
<summary>공지 게시판 페이지 보기</summary>
<div markdown="1">

 |공지 게시판(전체공지)|공지작성|공지 게시판(부서공지)|
 |:---:|:---:|:---:|
 |![finalpjt_restapi_ui (23)](https://github.com/user-attachments/assets/fe40ddad-292a-43fe-9660-82f62c79f057)|![finalpjt_restapi_ui (24)](https://github.com/user-attachments/assets/f8f1bf7d-fc76-46b3-b85c-17dc5ad26210)|![finalpjt_restapi_ui (25)](https://github.com/user-attachments/assets/022d49ae-7b50-47de-9c31-db718bf9deed)|

</div>
</details>

<details>
<summary>메신저 페이지 보기</summary>
<div markdown="1">

 |메신저 메인|대화 상대 초대|
 |:---:|:---:|
 |![finalpjt_restapi_ui (26)](https://github.com/user-attachments/assets/bce0fd65-464e-4c8a-bd2d-05c87748f092)|![finalpjt_restapi_ui (27)](https://github.com/user-attachments/assets/9a198e81-6d36-4625-acd6-2355f10add76)|

 |1:1 대화|그룹 대화|
 |:---:|:---:|
 |![finalpjt_restapi_ui (35)](https://github.com/user-attachments/assets/62b925be-00b6-450a-bd40-c5174aeea891)|![finalpjt_restapi_ui (29)](https://github.com/user-attachments/assets/e6ffda21-b6e0-42ef-a43f-34fdeb31c191)|

 |대화방 이름 변경|대화 상대 정보 조회|
 |:---:|:---:|
 |![finalpjt_restapi_ui (30)](https://github.com/user-attachments/assets/f75f8ee0-0d12-4c9d-b492-86e389f16149)|![finalpjt_restapi_ui (31)](https://github.com/user-attachments/assets/3aa47fd4-6d90-449d-868f-23818081924b)|

</div>
</details>

<details>
<summary>문서 페이지 보기</summary>
<div markdown="1">

 |문서함 메인|문서 작성|문서 상세 페이지|
 |:---:|:---:|:---:|
 |![finalpjt_restapi_ui (34)](https://github.com/user-attachments/assets/310c2dd2-c5e8-437b-ad62-61f6dcdcb955)|![finalpjt_restapi_ui (33)](https://github.com/user-attachments/assets/67a3e576-a6fd-40d2-ad25-27d2d83890c6)|![finalpjt_restapi_ui (32)](https://github.com/user-attachments/assets/cb11a938-3b15-443e-ad22-c11046070921)|
 
</div>
</details>

<details>
<summary> 스케줄러 페이지 보기</summary>
<div markdown="1">
 
</div>
</details>

<details>
<summary> 메일 페이지 보기</summary>
<div markdown="1">
 
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

> ### 프로젝트 흐름도

<details>
<summary>프로젝트 흐름도 보기</summary>
<div markdown="1">

 |![finalpjt_flow](https://github.com/user-attachments/assets/f1341d66-8b9d-4328-b079-1e86b2c1b0c9)|
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
