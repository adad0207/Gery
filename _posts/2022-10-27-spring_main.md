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
- Ahn lab이 켜져있어서 방화벽 문제로 실행이 안됐던 것이였다.
- 그동안 안보였던 xe 리스너
![image](https://user-images.githubusercontent.com/77110648/202911219-7675bc4d-a50f-4ab8-8d47-150a44357d67.png)

