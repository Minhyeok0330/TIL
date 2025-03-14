# html
## tag
- html은 항상 태그 구성으로 작성됨. 태그 안의 태그로 중첩식 사용 가능
```
<html> 
    <p> <strong> contents </strong></p>
    </html>
```
위의 형식

### 자주 사용하는 태그

<div>는 줄바꿈 enter(shift+enter)랑 같은 역할이라고 보면 됨. 그래서 f12열어보면 div가 그렇게 개쳐많구나
영역을 나누고 지정해주는 거라고 보는게 더 맞을 듯

### 속성이 없는 태그
- strong tag는 중요한 내용 체크. 검색 시 strong tag 만 활용으로 용이하게 검색
- ul 중첩 li tag는 순서 상관 없이 리스트업 닷으로 인덱싱
- ol 중첩 li tag는 순서에 맞게 리스트업 넘버로 인덱싱

### 속성이 있는 태그
- a태그는 href 속성에 입력한 주소로 이동하는 기능
```<a href="https://www.google.com/"> google </a>```

- img태그는 이미지를 불러오는 기능
- alt는 경로가 잘못 됐을 때 사진에 대한 설명 첨부
```<img scr="이미지 경로" alt="사진설명">```

 ## form
- input tag 사용자에게 입력값을 받을 수 있는 태그
```
<form action="">
        <label for="title">Name : </label>
        <input type="text" id="title" name="title">
        <br>
        <label for="age">age : </label>
        <input type="number" id="age" name="age">
        <br>
        <label for="email">email : </label>
        <input type="email" id="email" name="email">
        <input type="color">
        
        <input type="submit">
       
```
- input = 기본적인 입력값 받는 tag id, name= key, value와 같다고 생각하면 됨
- label for = input으로 이어지게 만들어주는 tag


- 체크박스 선택할 수 있게 만드는 tag
- checkbox는 다중 선택, radio는 단일 선택
```

<input type="checkbox" value="1">
<input type="checkbox" value="2">
<input type="checkbox" value="3">

<input type="radio" value="1" name="num">
<input type="radio" value="2" name="num">
<input type="radio" value="3" name="num">
```