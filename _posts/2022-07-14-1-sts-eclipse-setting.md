---
layout: post
title: sts/eclipse setting
subtitle : start studying java(1)
tags: [IDE, setting, JAVA]
author: Sooyeon Ko
comments : False
---

1. 설치<br>
zulu(jdk), apache(서버, c\ssafy 안에 풀었음), 
https://download.springsource.com/release/STS/3.9.14.RELEASE/dist/e4.15/spring-tool-suite-3.9.14.RELEASE-e4.15.0-win32-x86_64.zip (sts: spring tool suite, 안에 eclipse가 있음)다운 및 설치

2. apache 설정<br>
sts 아래 Servers tab->왼쪽클릭->new->버전 9.0 선택->next->폴더 선택->finish

3. project 생성<br>
sts: new->other->java>java project<br>
OpenPerspective->Java(오른쪽 위)<br>

4. 패키지, class 생성(psvm 체크)

5. Project 가져오기<br>
Import->Import->General->Existing Projects into Workspace->Select root directory(압축 푼 상태) Select archive file(압축된 상태)->finish

6. eclipse.ini(sts.ini) 파일 내에 -Dfile.encoding=UTF-8 추가

<br>
<hr>
<br>

- 글꼴 스타일 지정 하는 법 : <br>window 메뉴->preferences(환경설정)->General->Appearance->Colors and Fonts->Basic->Text Font->edit

- ctrl+shift+(+/-) : 글자 크기 조정

- ctrl+space : 자동완성<br>
- run as->Java Application : 실행

- ctrl+alt+위아래 : 복사
- alt+위아래 : 줄단위 이동
- ctrl+d : 줄삭제
- ctrl+shift+f : format
- ctrl+shift+/ : 주석

- ctrl+shift+O : import
