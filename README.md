# Prism-for-tistory
티스토리에 코드블럭이 쉽게 적용될수있도록 변경한 Prism
 ``` html
<head>
 
  ...
 
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hiwebtool/prism-for-tistory/prism.css">
</head>
<body>

...

  <script src="https://cdn.jsdelivr.net/gh/hiwebtool/prism-for-tistory/prism.js"></script>
</body>
```
이 두 코드만 붙여넣으면 완료
### js 코드는 body 맨 마지막에 붙여넣으세요

body 마지막에 안붙여넣으면 오류가 발생할수 있습니다.


### 티스토리 신 편집기에서 기본제공하는 언어만 일단 지원 추가 언어는 추가로 스크립트를 넣어야 됩니다.
기본 js코드 뒤로 넣어주세요
 ``` html
<head>
 
  ...
 
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hiwebtool/prism-for-tistory/prism.css">
</head>
<body>

...

  <script src="https://cdn.jsdelivr.net/gh/hiwebtool/prism-for-tistory/prism.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/hiwebtool/prism-for-tistory/prism-sql.js"></script>
</body>
```
#
