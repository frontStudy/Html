# 주요 태그 

<br/>

## _1. 단락_

<br/>

```
<p>The language is written in the form of HTML elements consisting of tags enclosed in angle brackets . Browsers do not display the HTML tags and scripts, but use them to interpret the content of the page.</p>
```

<p>The language is written in the form of HTML elements consisting of tags enclosed in angle brackets . Browsers do not display the HTML tags and scripts, but use them to interpret the content of the page.</p>

## _2. 줄 바꿈_

<br/>

```
<br/>

줄

<br/>

바꾸기
```

<br/>

줄

<br/>

바꾸기

## _3. 사진_

```
<img src="img.jpg" height="300" alt="빈이미지" title="빈 이미지">
```

<img src=" " height = "300px" width="300px" />

## _4. 표_


기본 : 

```
<table border="1>
    <tr>
        <td>이름</td>     <td>성별</td>   <td>주소</td>
    </tr>
    <tr>
        <td>최진혁</td>  <td>남</td>      <td >청주</td>
    </tr>
    <tr>
        <td>최유빈</td>  <td>여</td>      <td>청주</td>
    </tr>
</table>
```

<table border="1">
    <thead>
        <tr>
            <th>이름</th>     <th>성별</th>   <th>주소</th> 
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>최진혁</td>  <td>남</td>      <td >청주</td>
        </tr>
        <tr>
            <td>최유빈</td>  <td>여</td>      <td>청주</td> 
        </tr>
    </tbody>

</table>

<br/>

 의미론적인 접근:
 
 ```
 <table border="1">
    <thead>
        <tr>
            <th>이름</th>     <th>성별</th>   <th>주소</th> <th>회비</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>최진혁</td>  <td>남</td>      <td rowspan="2"> 청주</td> <td>1000</td>  <--- 청주를 세로로 2칸 사용
        </tr>
        <tr>
            <td>최유빈</td>  <td>여</td>      <td>500</td>                              <--- 위에서 청주가 내려왔으므로 기입 안해도 됨
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td colspan="3">합계</td> <td>1500</td>                                     <--- 합계 가로로 3칸 사용
        </tr>
    </tfoot>
</table>
 ```
 
  <table border="1">
    <thead>
        <tr>
            <th>이름</th>     <th>성별</th>   <th>주소</th> <th>회비</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>최진혁</td>  <td>남</td>      <td rowspan="2"> 청주</td> <td>1000</td>
        </tr>
        <tr>
            <td>최유빈</td>  <td>여</td>      <td>500</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td colspan="3">합계</td> <td>1500</td>
        </tr>
    </tfoot>
</table>

 
 
