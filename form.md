# Form 
## form 기본 양식
```
<form action="">
    <p> 아이디: <input type="text" name=" " value=" "></p>
    <p> 비밀번호 : <input type="password" name=" " value=" "></p>
    <input type="submit">
</form>
```
* form action에는 'submit'을 통해 제출한 정보가 보내지는 주소가 들어감
* input type이 'text'면 입력하는 정보가 화면상에 나타나고, 'password'면 모자이크 처리
+ <img src="https://github.com/frontStudy/img/blob/master/form_id%26pw.PNG" width=200px height=100px>
  <br/>
* 'name'에는 제출하는 정보의 분류(이름)이 들어감
* 'value'에는 입력 전 default값을 프로그래머가 지정 가능<br/> <br/>
## text 입력
```
<p>textarea :
            <textarea cols="" rows="">default value</textarea>
</p>
```
* text창 생성, 'cols'는 text창의 행 길이, 'rows'는 열 길이 
* default value에는 아무것도 입력하지 않았을 때 나오는 문자를 프로그래머가 지정 가능
##
