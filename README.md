# 객체지향언어 실습 중간고사

1. 다음의 조건에 맞게 Spring Boot 프로젝트를 생성하세요
- package 이름 : kr.ac.mjc.itc[본인학번]
- Spring Boot 버전 : 3.1.5
- 언어 : Java
- 빌드도구 : Gradle-Groovy
- JDK 버전 : 17
  
2. mysql 서버에 'itc[본인학번]' 으로 데이터베이스를 생성하고 Spring Boot 에서 이 데이터베이스로 접속하도록 설정하세요

3. @Entity 어노테이션을 이용해서 아래의 스키마를 만족하는 테이블이 생성되도록 만드세요

테이블 명 : Student

컬럼명 : student_number
- type : 문자열
- primary key

컬럼명 : name
- type: 문자열
- null을 허용하지 않음

컬럼명 : grade
- type : 정수형


4. Spring Boot로 StudnetController 를 만들고 Rest API가 호출될시 3번문제의 테이블에 값이 저장되도록 만드세요
- method : POST
- url : /api/students
- body(JSON) : {"studentNumber":"2007261051","name":"진용화","grde":1}
![image](https://github.com/JinYongHwa/sprintboot-midterm1/assets/21700482/65c4a732-2088-44e6-915b-88203f7c5df3)


5. Spring Boot로 StudentViewController 를 만들고 "/students" 로 접속했을때  위에서 입력한 학생 데이터가 나오도록 만드세요

![image](https://github.com/JinYongHwa/sprintboot-midterm1/assets/21700482/822182eb-18fe-4a88-a48c-d93469c5f390)




