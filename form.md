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
* default value에는 아무것도 입력하지 않았을 때 나오는 문자를 프로그래머가 지정 가능<br/> <br/>
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
* 'select name='뒤에 multiple을 추가하여 다중선택을 ctrl키로 가능하게 할 수는 있으나, 체크박스 사용 권장<br/> <br/>
## Radio&Checkbox
```
<form action="주소">
            <p>
                <h1>단일선택</h1>
                1번 : <input type="radio" name="n" value="1">
                2번 : <input type="radio" name="n" value="2" checked>
                3번 : <input type="radio" name="n" value="3">
            </p>
            <p>
                <h1>다중선택</h1>
                병우 : <input type="checkbox" name="name" value="fuck">
                최재 : <input type="checkbox" name="name" value="nice" checked>
                찬욱 : <input type="checkbox" name="name" value="study worm" checked>
            </p>
            <input type="submit">
        </form>
```
* radio는 'name'별로 하나만 선택, checkbox는 'name'별로 다중선택 가능
* 'checked'를 해주면 default값으로 선택되어있는 것을 지정 가능 
+ <img src="https://github.com/frontStudy/img/blob/master/radio%26checkbox.PNG" width=200px height=180px><br/> <br/>
## Button
```
<form action="http://localhost/form.php">
        <input type="text">
        <input type="submit" value="전송">
        <input type="button" value="버튼" onclick="alert('hello world')">
        <input type="reset">
```
* 'alert('hello world')'부분은 JavaScript
+ <img src="https://github.com/frontStudy/img/blob/master/button.PNG" width=140px height=70px><br/> <br/>
## 숨겨진 정보
```
<input type="hidden" name=" " value=" ">
```
* 어떠한 정보를 'submit'을 통해 입력받은 정보와 함께 서버로 전송하고 싶지만, 그 어떠한 정보를<br/>굳이 UI에 보여주고 싶지 않을 때 사용하는 코드<br/> <br/>
## Label
```
<label for id_txt>text:</label>
<input id_txt type="text" name="id" value="default value">
```
* 항목을 지정해서 lable화 가능
* radio나checkbox를 체크할 때 글자 부분을 클릭해도 체크가 되게끔 설정가능<br> <br/>

