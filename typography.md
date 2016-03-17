---
layout: page
title: 글꼴
---

토스의 서체는 [스포카 한 산스](http://spoqa-han-sans.com)를 사용합니다.
글꼴 파일은 이미 스타일 가이드에 포함되어 있습니다.

## 목차

* Will be replaced with the ToC, 
{:toc}

## 헤드라인

`h1`부터 `h6`까지의 헤드라인은 모두 기본 글자의 크기인 `16px`에 비례하도록 설계하였습니다. 
따라서 기본 글자의 크기와 줄 간격을 변경하면, 나머지 글자들도 알맞게 수정됩니다.

{% example html %}
<div class="col-12">
    <h1>h1. 토스는 금융 서비스입니다.(41px)</h1>
    <h2>h2. 토스는 금융 서비스입니다.(34px)</h2>
    <h3>h3. 토스는 금융 서비스입니다.(28px)</h3>
    <h4>h4. 토스는 금융 서비스입니다.(20px)</h4>
    <h5>h5. 토스는 금융 서비스입니다.(16px)</h5>
    <h6>h6. 토스는 금융 서비스입니다.(14px)</h6>
</div>
{% endexample %}


## 두께

`strong` 태그를 사용하면 글자를 강조할 수 있습니다.
클래스 이름에 `Thin`, `Regular`, `Bold`를 추가하여 글자의 두께를 조절할 수 있습니다.

{% example html %}

<h4 class="thin">Thin. 얇은 font-weight가 필요하다면 class에 thin을 추가해보세요.</h4>
<h4 class="regular">Regular. 기본 font-wight가 필요하다면 class에 regular를 추가해보세요.</h4>
<h4 class="bold">Bold. 두꺼운 font-weight가 필요하다면 class에 bold를 추가해보세요.</h4>
{% endexample %}


## 문단 & 줄간격

아래 문단은 css style을 적용하지 않은 기본적인 문단과 글줄의 간격입니다.
- 기본적으로 글줄 간격은 (`line-height:1.6`)으로 지정되어있습니다. 
- 문단의 간격은 (글자 크기 x 글줄) 만큼 지정되어있어습니다.

{% example html %}
  <h1>토스의 블로그</h1>

  <h3>통일된 디자인 가이드가 필요하다. </h3>
  <p>그 가이드는 그려야 할 필요가 없는 것이다. 웹페이지 제작 시간을 단축하고, 고민해야할 부분에 더 시간을 할애할 필요가 있다. 늘 공통적으로 쓰이는 콤포넌트들을 매번 새로 작성하는 것은 비효율적이다.</p>

  <h3>디자이너가 직접 할 수 밖에 없다.</h3>
  <p>토스의 특성상, 프론트-앤드 개발을  그렇다면, 코드에 대한 숙련도가 낮은 상황에서도 쉽게 작성할 수 있도록 해야 한다. 코드를 모르는 디자이너가, 직접 웹페이지를 작성하기까지의 시간을 단축해야한다.</p>

{% endexample %}


## 정렬

왼쪽 정렬은 기본값으로 설정되어있으며,
가운데 정렬이나 오른 쪽 정렬을 원한다면 각각 text-center, text-right클래스를 정렬하고 싶은 개체의 부모요소에 적용해주면 됩니다.

{% example html %}
  
<div class="col-12 highlight text-left">
<p>클래스 이름에 "text-left"를 추가해보세요. 왼쪽으로 정렬됩니다.</p>
</div>
<div class="col-12 highlight text-center">
<p>클래스 이름에 "text-center"를 추가해보세요. 가운데로 정렬됩니다.</p>
</div>
<div class="col-12 highlight text-right">
<p>클래스 이름에 "text-right"를 추가해보세요. 오른쪽으 정렬됩니다.</p>
</div>

{% endexample %}

## 부트스트랩 요소

더 자세한 내용은 [여기](http://bootstrapk.com/css/#리드-문단-)를 눌러 확인하세요.

{% example html %}
<p class="lead">리드 Class를 사용하여 문단을 강조합니다.</p>
<p>당신은 <mark>강조할</mark> 텍스트에 mark 태그를 사용할 수 있습니다.</p>
<p><del>이 텍스트줄은 삭제된 텍스트로 다뤄짐을 의미합니다.</del></p>
<p><s>이 텍스트줄은 더 이상 정확하지 않다고 다뤄짐을 의미합니다.</s></p>
<p><ins>이 텍스트줄은 문서에 추가분으로 다뤄짐을 의미합니다.</ins></p>
<p><u>이 텍스트줄은 밑줄이 그어질것입니다</u></p>
<p><small>이 텍스트는 작게 보이도록 되어 있습니다.</small></p>
<p><strong>두꺼운 텍스트로 렌더링 됩니다</strong></p>
<p><em>이탤릭체로 렌더링 됩니다</em></p>
<blockquote>
  <p>인용문을 작성할 수 있습니다.</p>
</blockquote>
{% endexample %}





