# Form 
## form 기본 양식
```
<form action="주소">
    <p> 아이디: <input type="text" name="id" value="아이디를 입력하시오"></p>
    <p> 비밀번호 : <input type="password" name="pw" value="비밀번호를 입력하시오"></p>
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
## 항목 선택
```
<form action="주소"
    <h1>항목 선택</h1>
    <select name="전송할 이름">
        <option value="1">1번</option>
        <option value="2">2번</option>
        <option value="3">3번</option>
    </select>
</form>
```
* 'name'에는 선택된 정보가 어떤 이름으로 제출될 지 정함
* 'option value'는 각 옵션을 컴퓨터가 어떤 정보로 받아들일 지 정함
+ <img src="https://github.com/frontStudy/img/blob/master/select.PNG" width=115px height=70px>
