---
title: "Spring MVC의 흐름 파악 및 어노테이션"
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


<br>
1.http://localhost:8080/root/hello.do (요청 URL) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br>


<br>
2.Web.xml 설정(*.do)을 읽고 dispatcherServlet 으로 이동<br>
-HandlerMapping 갔다옴<br>
<br>
3.Controller 이동<br>
-ModelAndView <br>
<br>
4.dispatcherServlet 으로 이동<br>
<br>

5.ViewReader<br>
-dispatcherServlet 참조
<br>

6.dispatcherServlet 으로 이동<br>
<br>
7.View<br>
-화면에 뿌려주기


<hr>
*@ModelAttribute SumDTO / Model / ModelMap
<hr>
* @ResoinseBody 태그 사용시 바로 dispatcher -> controller -> view
<hr>
*Bean<br>
@Component<br><br>
아래 있는 어노테이션/태그는 @Component를 포함하고있음 (중복 사용시 Error 발생 할 수 있음)
<br>
&lt;Bean><br>
@Service<br>
@Repository<br>
@Controller<br>



