---
layout: page
title: 시작하기
---

토스 웹 스타일 가이드는 [Bootstrap](//bootstrapk.com)을 바탕으로 토스의 웹 서비스에 맞게 수정된 CSS & Javascrpt 문서입니다. 
아래 코드를 복사하고 붙여넣으세요. 토스의 웹 스타일 가이드 문서(CSS)는 [CDN](https://ko.wikipedia.org/wiki/%EC%BD%98%ED%85%90%EC%B8%A0_%EC%A0%84%EC%86%A1_%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC) 방식으로 웹서버에서 제공됩니다.

## CSS & JS

진행중인 프로젝트가 있다면, 아래 코드를 빈 html문서에 붙여넣으세요.

{% highlight html %}

<!-- Toss CSS Framework CDN -->
<link href="https://cdn.rawgit.com/kkCheon/tossframe/master/assets/stylesheets/tossframe.css" rel="stylesheet">

<!-- Toss JS Framework CDN -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
<script src="https://cdn.rawgit.com/kkCheon/tossframe/master/assets/javascripts/tossframe.js"></script>

{% endhighlight %}

## 기본 템플릿

지금 새 프로젝트를 시작한다면, 아래 코드를 빈 html문서에 붙여넣으세요.


{% highlight html %}

<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- 위 3개의 메타 태그는 *반드시* head 태그의 처음에 와야합니다; 어떤 다른 콘텐츠들은 반드시 이 태그들 *다음에* 와야 합니다 -->
    <title>Toss Web Framework</title>
    
    <!-- Toss Framework CDN // CSS 문서의 맨 처음에 와야 합니다;-->
    <link href="https://cdn.rawgit.com/kkCheon/tossframe/master/assets/stylesheets/tossframe.css" rel="stylesheet">

  </head>
  <body>
    <h1 class="text-center">Hello World!</h1>




    <!-- 내용을 작성하세요. -->
    


        
    <!-- Toss JS Framework CDN -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
    <script src="https://cdn.rawgit.com/kkCheon/tossframe/master/assets/javascripts/tossframe.js"></script>


  </body>
</html>

{% endhighlight %}