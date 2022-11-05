# CSS
'생활코딩' 유튜브 강의를 통한 CSS 맛보기!

## ● css 파일 분할
```html
<link rel="stylesheet" href="style.css">
```
>파일 분할 사용하지 않을경우 : <style></style> 태그 사용

## ● 무색무취의 태그
```html
<div>     // 줄바꿈 o

</div>
```
```html
<span>     // 줄바꿈 x

</span>
```

## ● 우선순위
id 태그 > 클래스 태그 > 일반 태그

### a. id 태그
한 코드 내 한번만 가능함
```css
#active{
  color:red;
}
```

### b. 클래스 태그
```css
.saw {
  color:gray;
}
```

### c. 일반 태그
```css
h1 {
  font-size:45px;
}
```

## 문단 내 style 변경
```html
<p style="margin-top:80px;">HTML PAGES</p>
```

## 차지하는 크기
### a. block level element
화면 전체 사용

### b. inline element ex) a 태그
자신의 크기만큼을 사용

>강제로 변경
```css
  display:block;
  display:inline;
  display:none;
```

## 테두리
```css
h1{
  border:5px red solid;
  padding:20px;
  margin:20px;
  display:block;
  width:100px;
}
```

## 주석처리
```html
<!--
border-width:5px;
border-color:red;
border-style:solid;
-->
```
```c
// Cascading Style Sheets (<a href="https://ko.wikipedia.org/wiki/CSS">CSS</a>)
```

## 미디어 쿼리 (반응형 디자인)
화면의 크기에 따라 웹페이지의 요소들이 반응하여 동작
```css
@media(max-width:800px){    //screen의 크기가 800px 보다 작으면
  #grid {
    display:none;
  }
```
