# 객체지향언어 실습 중간고사

1. 다음의 조건에 맞게 Spring Boot 프로젝트를 생성하세요
   - package명이 kr.ac.mjc.itc[본인학번]
   - Spring Boot 버전은 3.1.5 버전
   - 언어는 Java
   - 빌드도구는 Gradle-Groovy
   - JDK 버전은 17
  
2. mysql 서버에 'itc[본인학번]' 으로 데이터베이스를 생성하고 Spring Boot 에서 이 데이터베이스로 접속하도록 설정하세요

3. @Entity 어노테이션을 이용해서 아래의 스키마를 만족하는 테이블이 생성되도록 만드세요

테이블 명 : Student

컬럼명 : studentNumber
- type : 문자열
- primary key

컬럼명 : name
- type: 문자열
- null을 허용하지 않음

컬럼명 : grade
- type : 정수형


4. Spring Boot로 Rest API가 호출될시 3번문제의 테이블에 값이 저장되도록 만드세요
- method : POST
- url : /api/students
- body(JSON) : {"studentNumber":"2007261051","name":"진용화","grde":1}

