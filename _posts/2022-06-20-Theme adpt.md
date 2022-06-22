---
layout: post
title: "Jekyll 테마 적용법"
date: 2022-06-20 19:20:23 +0900
category: ETC
---

<h1>Jekyll 테마 적용법</h1>

<br> 
<ol>
<li>Readme 파일 생성하여 최초 commit 진행 후 git clone 을 통해 로컬로 폴더 생성</li> 
<br>
<li>테마파일 다운로드 후 폴더에 덮어쓰기</li> 


<li>아래 코드 순서대로 Ruby CMD 창에 적기</li>



<div class="colorscripter-code" style="color:#f0f0f0;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; position:relative !important;overflow:auto"><table class="colorscripter-code-table" style="margin:0;padding:0;border:none;background-color:#272727;border-radius:4px;" cellspacing="0" cellpadding="0"><tr><td style="padding:6px;border-right:2px solid #4f4f4f"><div style="margin:0;padding:0;word-break:normal;text-align:right;color:#aaa;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="line-height:130%">1</div><div style="line-height:130%">2</div><div style="line-height:130%">3</div><div style="line-height:130%">4</div><div style="line-height:130%">5</div><div style="line-height:130%">6</div><div style="line-height:130%">7</div><div style="line-height:130%">8</div><div style="line-height:130%">9</div><div style="line-height:130%">10</div><div style="line-height:130%">11</div><div style="line-height:130%">12</div><div style="line-height:130%">13</div><div style="line-height:130%">14</div><div style="line-height:130%">15</div><div style="line-height:130%">16</div><div style="line-height:130%">17</div><div style="line-height:130%">18</div></div></td><td style="padding:6px 0;text-align:left"><div style="margin:0;padding:0;color:#f0f0f0;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="padding:0 6px; white-space:pre; line-height:130%">gem&nbsp;install&nbsp;jekyll</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">(강제설치&nbsp;sudo&nbsp;gem&nbsp;install&nbsp;jekyll)</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">gem&nbsp;install&nbsp;jekyll&nbsp;bundler</div><div style="padding:0 6px; white-space:pre; line-height:130%">gem&nbsp;install&nbsp;github<span style="color:#0086b3"></span><span style="color:#ff3399">-</span>pages</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">jekyll&nbsp;new&nbsp;.<span style="color:#0086b3"></span><span style="color:#ff3399">/</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">bundle&nbsp;install</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">bundler&nbsp;<span style="color:#0086b3"></span><span style="color:#ff3399">-</span><span style="color:#0086b3"></span><span style="color:#ff3399">&gt;</span>&nbsp;버전&nbsp;오류&nbsp;발생시</div><div style="padding:0 6px; white-space:pre; line-height:130%">bundle&nbsp;update&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">bundle&nbsp;add&nbsp;webrick&nbsp;<span style="color:#0086b3"></span><span style="color:#ff3399">-</span><span style="color:#0086b3"></span><span style="color:#ff3399">&gt;</span>&nbsp;오류&nbsp;시</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">bundle&nbsp;install</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">bundle&nbsp;<span style="color:#4be6fa">exec</span>&nbsp;jekyll&nbsp;serve</div></div></td><td style="vertical-align:bottom;padding:0 2px 4px 0"><a href="http://colorscripter.com/info#e" target="_blank" style="text-decoration:none;color:white"><span style="font-size:9px;word-break:normal;background-color:#4f4f4f;color:white;border-radius:10px;padding:1px">cs</span></a></td></tr></table></div>
<li>아래 주소가 확인 되면 push 하여 마무리!</li></ol>


![이미지](main/img/2022-06-22-10-26-31.png)
