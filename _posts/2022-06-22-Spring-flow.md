---
title: "Spring MVC의 흐름 파악"
excerpt: "Spring MVC의 순서를 파악해보기"
 
categories:
  - Spring       
tags:
  - [ Spring, MVC ]  
toc: true
 
date: 2022-06-22
last_modified_at: 2022-06-22
---

<h1>Spring MVC Flow<h2>
* @ResoinseBody 태그 사용시 바로 dispatcher -> controller -> view

<br>
http://localhost:8080/root/hello.do (요청 URL) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>

Web.xml 설정을 읽고 dispatcherServlet 으로 이동<br>
<br>
