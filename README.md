사이트 주소 : https://zealous-brahmagupta-7fd61d.netlify.app/

# ☕️ STARBUCKS
스타벅스 랜딩 페이지(홈페이지) <br> <br>
 <img src="https://raw.githubusercontent.com/smmne/starbucks/master/_asset/main_screenshot.jpeg">

 # 문자 인코딩(Character Encoding) 설정
 문자가 인코딩 되는 방식을 설정한다.
 ```HTML
 <meta charset="UTF-8"/>
 ```
 - <code>UTF-8</code> : 초성, 중성, 종성으로 구분하여 문자를 작성(권장)
 - <code>EUC-KR</code> : 하나의 완성된 글자를 인식
 <br>
 
 # 뷰포트(ViewPort) 렌더링 방식 설정
 웹페이지가 화면(Viewport)에 표현되는 방식을 설정한다.<br>
 모바일 환경에서 적용된다.
  ```HTML
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
 ```
 - <code>width=device-width</code> : 화면의 가로 너비를 각 디바이스(Device)의 가로 너비와 동일하게 적용
 - <code>initial-scale=1.0</code> : 화면의 초기 화면 배율(확대 정도)을 설정
 - <code>user-scalable=no</code> : 사용자가 디바이스 화면을 확대/축소할 수 있는지 설정
 - <code>maximum-scale=1</code> : 사용자가 화면을 확대할 수 있는 최대값
 - <code>minimum-scale=1</code> : 사용자가 화면을 축소할 수 있는 최소값
  <br>

 # 오픈 그래프(The Open Graph Protocol)
 웹페이지가 소셜 미디어(페이스북 등)로 공유될 때 우선적으로 활용되는 정보를 지정한다. <br> <br>
 Slack -  <br>
 <img src="https://raw.githubusercontent.com/smmne/starbucks/master/_asset/slack_message_og_example.jpeg"> <br> <br>
 KakaoTalk -  <br>
<img src="https://raw.githubusercontent.com/smmne/starbucks/master/_asset/slack_message_og_example.jpeg">
 <br>

```HTML
<meta property="og:type" content="website" />
<meta property="og:site_name" content="Starbucks" />
<meta property="og:title" content="Starbucks Coffee Korea" />
<meta property="og:description" content="스타벅스는 세계에서 가장 큰 다국적 커피 전문점으로, 64개국에서 총 23,187개의 매점을 운영하고 있습니다." />
<meta property="og:image" content="./images/starbucks_seo.jpg" />
<meta property="og:url" content="https://starbucks.co.kr" />
 ```
- <code>og:type</code> : 페이지의 유형(E.g, <code>website</code>, <code>video.movie</code>)
- <code>og:site_name</code> : 속한 사이트의 이름
- <code>og:title</code> : 페이지의 이름(제목)
- <code>og:description</code> : 페이지의 간단한 설명
- <code>og:image</code> : 페이지의 대표 이미지 주소(URL)
- <code>og:url</code> : 페이지의 주소(URL)
<br>

# 트위터 카드(Twitter Cards)
웹페이지가 소셜 미디어(트위터)로 공유될 때 우선적으로 활용되는 정보를 지정한다.
```HTML
<meta property="twitter:card" content="summary" />
<meta property="twitter:site" content="Starbucks" />
<meta property="twitter:title" content="Starbucks Coffee Korea" />
<meta property="twitter:description" content="스타벅스는 세계에서 가장 큰 다국적 커피 전문점으로, 64개국에서 총 23,187개의 매점을 운영하고 있습니다." />
<meta property="twitter:image" content="./images/starbucks_seo.jpg" />
<meta property="twitter:url" content="https://starbucks.co.kr" />
```
- <code>twitter:card</code> : 페이지(카드)의 유형(E.g <code>summary</code>, <code>player</code>)
- <code>twitter:site</code> : 속한 사이트의 이름
- <code>twitter:title</code> : 페이지의 이름(제목)
- <code>twitter:description</code> : 페이지의 간단한 설명
- <code>twitter:image</code> : 페이지의 대표 이미지 주소(URL)
- <code>twitter:url</code> : 페이지 주소(URL)
<br>

# Favicon(파비콘, favorites icons)
웹페이지를 나타내는 아이콘, 웹페이지의 로고를 설정한다.<br>
대부분의 경우 루트 경로에 <code>favicon.ico</code> 파일을 위치하면 자동으로 로딩하기 때문에 <code><link /></code>를 작성할 필요가 없다. <code>favicon.png</code> 파일을 사용하려면 다음과 같이 <code><link />를 작성해야 한다.</code>

> 파비콘 이미지는 루트 경로에 있어야 한다.
```HTML
<!-- <link rel="shortcut icon" href="favicon.ico /> -->
<link rel="icon" href="./favicon.png" />
```
- <code>favicon.ico</code> 64 x 64 (px) 또는 32 x 32 또는 16 x 16
- <code>favicon.png</code> 500 x 500 (px)<br><br>
<img src="https://raw.githubusercontent.com/smmne/starbucks/master/favicon.ico"><br>
<img src="https://raw.githubusercontent.com/smmne/starbucks/master/favicon.png">
<br>

# .ico 
이미지를 업로드하면 손쉽게 <code>.ico</code> 파일을 제작할 수 있다.

[iconifier.net](iconifier.net)
<br>

# Reset.css
각 브라우저의 기본 스타일을 초기화 한다.
```HTML
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css" />
```
<br>

# Google Fonts
페이지에서 사용할 '나눔고딕' 폰트를 지정한다.
> 폰트 라이선스 꼭 확인
[Google Fonts](https://fonts.google.com/)에서 고른 폰트 파일을 가져온다.
```CSS
body {
    font-family: 'Nanum Gothic', sans-serif;
}
```
<br>

# Google Material Icons
[구글에서 제공하는 머터리얼 아이콘](https://fonts.google.com/icons?selected=Material+Icons)을 무료로 사용할 수 있다.<br>
[Getting started for web](https://material.io/develop/web/getting-started)
```HTML
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons" />
```
다음과 같이 사용할 수 있다.
```HTML
<div class="material-icons">upload</div>
```
<br>

# GSAP & ScrollToPlugin
[GSAP(The GreenSock Animation Platform](https://greensock.com/gsap/)은 자바스크립트로 제어하는 타임라인 기반의 애니메이션 라이브러리이다. [ScrollToPlugin](https://greensock.com/scrolltoplugin/)은 스크롤 애니메이션을 지원하는 GSAP 플러그인이다.
```HTML
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.5.1/gsap.min.js" integrity="sha512-IQLehpLoVS4fNzl7IfH8Iowfm5+RiMGtHykgZJl9AWMgqx0AmJ6cRWcB+GaGVtIsnC4voMfm8f2vwtY+6oPjpQ==" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.5.1/ScrollToPlugin.min.js" integrity="sha512-nTHzMQK7lwWt8nL4KF6DhwLHluv6dVq/hNnj2PBN0xMl2KaMm1PM02csx57mmToPAodHmPsipoERRNn4pG7f+Q==" crossorigin="anonymous"></script>
```
[.to() ]

