# JavaScript
'생활코딩' 유튜브 강의를 통한 JavaScript 맛보기!<br><br>

## ● JS 파일 분할
```html
<script src="colors.js"></script>
```
## ● 출력함수
```js
document.write();
```
## ● 버튼 만들기
```js
<input type="button" value="night" onclick="        // 타입: 버튼, 이름: night, event: 클릭 시
  nightdayHandler(this);
">
```
>event의 종류 : onclick, onchange, onkeydown...
## ● 반복문
```js
function LinksSetColor(color){                      // 함수 선언
  var alist = document.querySelectorAll('a');       // alist 변수에 모든 a 태그 저장
  var i = 0;  
  while(i < alist.length){                          // 변수 i가 alist의 길이보다 작을때까지 수행
    alist[i].style.color = color;                   // alist에 차례대로 color를 매개변수 color에 따라 색 변경
    i++;
  }
}
```
## ● 함수의 객체화
```js
var Links = {                                         // links라는 객체에
      setColor:function (color){                      // setColor라는 함수 선언
        var alist = document.querySelectorAll('a');
        var i = 0;
        while(i < alist.length){
            alist[i].style.color = color;
            i++;
        }
      }
    }
```
## ● jQuery의 사용
```js
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.1/jquery.min.js"></script>
```
```js
var Links = {
  setColor:function (color){
     $('a').css('color', color);
  }
}
```
