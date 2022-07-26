---
layout: post
title: web project setting
subtitle : start studying java(2)
tags: [IDE, setting, JAVA, Web]
author: Sooyeon Ko
comments : False
---

## 웹 WebProject
1. new->Other->Web->Dynamic Web Project

2. web.xml : 웹 프로젝트의 환경설정의 내용을 가지고 있음(Generate web.xml deployment descriptor check)

3. Open perspective -> JavaEE로 바껴있음<br>

<br>

> #### 환경
> - Standard(pc) : main함수 있음. J2SE(java2[jdk1.2부터] standard edition이라고 부름). 실행시키려면 실행시키는 파일이 반드시 그 컴퓨터에 있어야함(.class같은 파일). application
> - Enterprise(browser) : J2EE(java2 Enterprise edition). 브라우저를 열고 주소창에 주소를 넣고 실행하면 실행됨. 실행하려고 하는 프로그램이 내 컴퓨터에 없어도 되지만 네트워크는 연결돼있어야함. 원격 환경을 의미. 즉, 서비스를 해주는 서버하고 서비스를 이용하는 클라이언트가 떨어져있다는 의미. web application
> Mobile: J2ME(java2 micro edition).

<br>

4. WebContent->WEB-INF->web.xml 에서 환경설정 가능

5. Java 파일은 Java Resources->src에 넣고<br>
나머지는 WebContent에 넣음(image, 동영상, html, css 등등)

6. WebContent 내부에 폴더를 만들어줌<br>
html, img, css 등등

<br>

> #### Web App
> - Front-End(화면, 디자인) : html(문서의 구조, 내용), css(style), javascript
> - Back-End(Logic) : sevlet, jsp
> - Data Layer(Database)

<br>

7. html 파일 만들기(new->HTML file)<br>
encoding<br>
window->Preferences->Encoding검색->General->Workspace->Text file encoding->utf-8<br>
Preferences->Encoding검색->Web->HTML files->Encoding->UTF-8(맨 위)<br>
CSS, JSP도 UTF-8로 변경

8. Window->Web Browser->Chrome
