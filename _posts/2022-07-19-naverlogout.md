---
title: "네아로 로그아웃"
excerpt: "네이버아이디 로그아웃 구현"
 
categories:
  - Project       
tags:
  - [ spring, springboot, yml, study ]  
toc: true
 
date: 2022-07-19
last_modified_at: 2022-07-19
---

<h1>네이버 아이디 로그아웃 구현</h1>

네이버 아이디는 'https://nid.naver.com/nidlogin.logout' 해당 페이지로 리다이렉트를 해야 완전한 로그아웃 구현가능


<br>
따라서 해당 페이지에서 윈도우 창으로 url에 리다이렉트 후 윈도우 창을 닫는 식으로 코드를 구현하였다.

<div class="colorscripter-code" style="color:#f0f0f0;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; position:relative !important;overflow:auto"><table class="colorscripter-code-table" style="margin:0;padding:0;border:none;background-color:#272727;border-radius:4px;" cellspacing="0" cellpadding="0"><tr><td style="padding:6px;border-right:2px solid #4f4f4f"><div style="margin:0;padding:0;word-break:normal;text-align:right;color:#aaa;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="line-height:130%">1</div><div style="line-height:130%">2</div><div style="line-height:130%">3</div><div style="line-height:130%">4</div><div style="line-height:130%">5</div><div style="line-height:130%">6</div><div style="line-height:130%">7</div><div style="line-height:130%">8</div><div style="line-height:130%">9</div><div style="line-height:130%">10</div><div style="line-height:130%">11</div><div style="line-height:130%">12</div><div style="line-height:130%">13</div></div></td><td style="padding:6px 0;text-align:left"><div style="margin:0;padding:0;color:#f0f0f0;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="padding:0 6px; white-space:pre; line-height:130%">&lt;script&nbsp;type="text/javascript"&gt;</div><div style="padding:0 6px; white-space:pre; line-height:130%">$(function(){</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;//window.open('https://nid.naver.com/nidlogin.logout',&nbsp;'네이버아이디&nbsp;로그아웃',&nbsp;'top=10,&nbsp;left=10,&nbsp;width=500,&nbsp;height=600,&nbsp;status=no,&nbsp;menubar=no,&nbsp;toolbar=no,&nbsp;resizable=no');</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;//window.close();</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;top.window.open('https://nid.naver.com/nidlogin.logout',&nbsp;'네이버아이디&nbsp;로그아웃',&nbsp;'top=10,&nbsp;left=10,&nbsp;width=500,&nbsp;height=600,&nbsp;status=no,&nbsp;menubar=no,&nbsp;toolbar=no,&nbsp;resizable=no').close();</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;top.window.opener=self;</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;top.self.close();</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;//alert('stop');</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;location.href="/ReseltProject/";</div><div style="padding:0 6px; white-space:pre; line-height:130%">});</div><div style="padding:0 6px; white-space:pre; line-height:130%">&lt;/script&gt;</div></div><div style="text-align:right;margin-top:-13px;margin-right:5px;font-size:9px;font-style:italic"><a href="http://colorscripter.com/info#e" target="_blank" style="color:#4f4f4ftext-decoration:none">Colored by Color Scripter</a></div></td><td style="vertical-align:bottom;padding:0 2px 4px 0"><a href="http://colorscripter.com/info#e" target="_blank" style="text-decoration:none;color:white"><span style="font-size:9px;word-break:normal;background-color:#4f4f4f;color:white;border-radius:10px;padding:1px">cs</span></a></td></tr></table></div>

<br>
주석 표시된 코드의 경우 창이 닫히지 않는 문제로 인하여,
<br>
아래 활성화된 코드로 창을 닫아주고 메인페이지로 이동하였다.