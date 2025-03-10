# ![header](https://capsule-render.vercel.app/api?type=venom&color=0:5C258D,100:4389A2&height=300&section=header&text=Management%20Sysetem&fontColor=black&fontSize=50&stroke=5C258D&strokeWidth=1)

</div> 

## 소개
학생과 직원에 대한 정보를 관리하는 통합 관리 시스템입니다. 

- 프로젝트 소개
- 개발 기간
- 주요 기능
- 프로젝트 클래스 다이어그램
- 기술 스택
- 시연 영상
- 기술적 이슈와 해결 과정
- 프로젝트 팀원

<br>

## 프로젝트 소개 

### Version1: Student Management System  ![Version1 프로젝트 링크](https://github.com/Cmk1031/student_program)

### Version2: Employee Management System ![Version2 프로젝트 링크](https://github.com/Cmk1031/managements_program)

학생과 직원에 대한 통합 관리시스템을 구현하기 앞서 학생 관리 시스템을 Version1, 직원 관리 시스템을 Version2로 계획해 구현하고 통합했습니다. 

Employee Management System은 직원 정보의 저장, 읽기, 변경, 삭제 기능을 제공하고 직위에 따른 연봉 인상률을 적용했습니다. 

<br>

## 개발 기간
- V2: 2024.2.18(화) ~ 2024.2.21(금): Employee System 설계 및 팀 깃허브 설정

- V2: 2024.2.24(월) ~ 2024.3.5(수): 기능 구현

- V2: 2024.3.6(목) ~ 2024.3.10(월): 리팩토링

<br>

## 주요 기능

- 직원 정보 입력

- 직원 정보 조회

- 직원 정보 삭제

- 직원 정보 수정

- 직원 급여 인상

<br>

## 프로젝트 클래스 다이어그램
### 1. Employee

![image](https://github.com/user-attachments/assets/9023c2b8-3111-48ce-9828-811e786c085d)

### 2. Controller

![image](https://github.com/user-attachments/assets/ff7c7b74-c13d-4e7f-a9ce-a7e261cfe12c)

### 3. SalaryService

![image](https://github.com/user-attachments/assets/46a4cfc7-ba1c-4e94-9bf7-c075dbccd8a0)

### 4. Repository

![image](https://github.com/user-attachments/assets/7739ee3a-5e3d-4c63-86bb-d041b7214c02)

### 5. DB ERD

![image](https://github.com/user-attachments/assets/b47e9455-b64b-47be-a719-ceacd5953cfb)

<br>


## ⚙ 기술 스택

### Back-end
<div>
<img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Java.png?raw=true" width="80">
<img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Mysql.png?raw=true" width="80">

</div>

### Tools
<div>
<img src="https://github.com/yewon-Noh/readme-template/blob/main/skills/Github.png?raw=true" width="80">

<br />

## 시연 영상

추가 예정

<br>

## 기술적 이슈와 해결 과정 

1. DB에 접속할 때 필요한 IP 주소와 DB 접근 비밀번호를 사용한 파일을 .gitIgnore에 추가하지 않고 git push 하여 민감 정보를 그대로 깃허브 repository에 저장되는 문제 발생 <br>
-> push 이후 해당 파일을 .gitIgnore에 추가해도 이미 push 되었기 때문에 계속해서 push되는 문제 발견 <br>
-> 깃허브 레포지토리에 캐시 데이터를 삭제 후 .gitIgnore에 추가 <br>
-> 해결 완료 <br>
결론: 깃허브 저장소에 push 하면 안 되는 민감한 정보들은 미리 .gitIgnore에 추가해두자!

2. GitHub 충돌
이전 Version1에서는 git과 gitHub를 사용하긴 했지만 협업에 있어 제 기능을 온전히 사용하진 못했다. 당시의 아쉬움으로 Version2에서는 

   

<br>

## 프로젝트 팀원 







