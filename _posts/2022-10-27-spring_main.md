---
layout: post
title: "Spring 게시판 만들기."
---
# JavaConfiguration 사용
- web.xml의 파일삭제 및 스프링 관련 파일 삭제
- pom.xml의 수정 및 스프링 버전 변경
- Java 설정 관련 패키지 생성

# 오류
----
- ORA-12505 오류
![image](https://user-images.githubusercontent.com/77110648/202908051-277b0d64-4d3b-44e8-8fb5-522eb7fbcc50.png)
- Oracle listener 문제였다.
- Oracle파일 속 listener.ora 파일에 빨간줄 부분이 EXTPROC1521 이여야하는데 EXTPROC1이였다. (수정)
![image](https://user-images.githubusercontent.com/77110648/202908173-dd28369b-5099-43bb-a2c0-c6094f2feb82.png)
- 정상 접속!
![image](https://user-images.githubusercontent.com/77110648/202908246-0acf408e-2f6e-42c1-a22c-604ef36fe8bb.png)
