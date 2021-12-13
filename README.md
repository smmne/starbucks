# ☕️ STARBUCKS
스타벅스 랜딩 페이지(홈페이지)

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
 웹페이지가 소셜 미디어(페이스북 등)로 공유될 때 우선적으로 활용되는 정보를 지정한다.
```HTML
<meta property="og:type" content="website" />
<meta property="og:site_name" content="Starbucks" />
<meta property="og:title" content="Starbucks Coffee Korea" />
<meta property="og:description" content="스타벅스는 세계에서 가장 큰 다국적 커피 전문점으로, 64개국에서 총 23,187개의 매점을 운영하고 있습니다." />
<meta property="og:image" content="./images/starbucks_seo.jpg" />
<meta property="og:url" content="https://starbucks.co.kr" />
 ```
- <code>og:type</code> : 페이지의 유형(E.g, website, video.movie)
- <code>og:site_name</code> : 속한 사이트의 이름
- <code>og:title</code> : 페이지의 이름(제목)
- <code>og:description</code> : 페이지의 간단한 설명
- <code>og:image</code> : 페이지의 대표 이미지 주소(URL)
- <code>og:url</code> : 페이지의 주소(URL)
