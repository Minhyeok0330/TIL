# CSS
html이 실제로 표시되는 방법을 기술한다.(디자인적 측면)

## 기초적인 style태그 작성 방법
1. 원라인으로 쓰기
2. style 태그 안에 넣어서 쓰기
3. 파일을 따로 만들어서 파일을 불러오기(모듈화와 같은 개념인듯)
```
 <style>
        h2 {
            color : lightgreen;
        }
    </style>
    <link rel="stylesheet" href="mycss.css">
</head>
<body>
    <h1 style="color: pink">hello</h1>
    <h2>world</h2>
    <h3>its me</h3>

    <p id="first">여기는 본문입니다.</p>
    <p id="second">두번째 본문입니다.</p>
    
    <ul>
        <li id="f" class="a">첫번째</li>
        <li id="s" class="a">두번째</li>
        <li id="t" class="a">세번째</li>
    </ul>
```
h1 : 원라인
h2 : style tag 안에 작성
h3 : 파일 모듈화

### css파일 예시
```
h3 {
    color : blueviolet;
}

p {
    color: orangered
}

#first {
    color:brown
}
#s {
    color:#fda123
}
.a{
    color: #0b0896
}
```
- h3에 대한 정보가 담겨있음
- #은 id=과 같은 의미
- #s 에서 color:#fda123은 컬러의 고유 태그를 의미
- .a 에서 .은 class를 의미 

##
- 데이터 크롤링 시 attribute 정의가 잘 구분 되어 있는 사이트가 용이하다.

## bootstrap
- 홈페이지 편하게 만들 수 있는 CSS 라이브러리