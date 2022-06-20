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



```ruby
gem install jekyll
gem install jekyll bundler
gem install github-pages


jekyll new ./

bundle install
-> 버전 오류 발생시 bundler
-> 오류 시 bundle update
-> bundle add webrick

bundle install

bundle exec jekyll serve


강제설치
(sudo gem install jekyll)
```
<li>아래 주소가 확인 되면 push 하여 마무리!</li></ol>

![](2022-06-20-23-52-35.png)
