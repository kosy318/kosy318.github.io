---
layout: post
title: About Conditional Statement(조건문)
subtitle : start studying java(5)
tags: [JAVA, Conditional Statement, JAVA 공부]
author: Sooyeon Ko
comments : False
---

#### 조건문(Conditional Statement)
- if(논리형, 비교식, Method call)
- switch(정수호환, Enum, Class Object[Byte, short, Character, Integer, String], Method Call)
  ```java
  switch(expr){
    ...
  }
  ```
  expr은 반드시 정수형(int, byte, short, char, jdk 7 이상부터는 String도 가능)이어야함

> && 나 || 는 앞을 계산해서 전체 결과가 나오면 뒤에 것을 확인안함 (short circuit logic)<br>
> & 나 |와 같이 한개짜리는 결론이 났어도 뒤에도 확인함

#### 반복문 for 구성
for(변수 초기화; 반복 조건; 증감식){ 실행문 }<br>

#### for vs while
###### for
- 초기값, 조건식, 증감식의 위치가 명확
- 반복의 회수가 명확한 경우
- index의 증감 활용

###### while
- 반복의 회수가 불명확한 경우
- index보다는 break, continue 활용

#### 배열
동일한 타입의 변수를 여러 개 사용하면..<br>
- 변수의 수 증가
- 코드의 길이 증가<br>
<br>

- 반복문 적용 불가
- 변수의 수가 동적으로 결정될 경우, 사용 불가<br>
<br>

배열(Array)로 동일 타입 변수 묶어서 사용하기
- 배열이란? 동일한 타입의 데이터 0개 이상을 하나의 연속된 메모리 공간에서 관리하는 것
- 요소에 접근하는 속도가 매우 빠르다
- 한번 생성하면 크기 변경 불가
