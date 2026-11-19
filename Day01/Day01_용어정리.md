# HTML 정리
## 1. 태그
    - HTML 문서에서 내용의 의미과 구조를 브라우저에 알려주는 표시
    
## 2. 문서 기본 구조
```html
    -<!DOCTYPE html>   ---> 문서가 HTML문서임을 브라우저에 알림
    <html>             ---> HTML 문서의 최상위 태그 (모든 요소 포함)
        <head>         ---> 화면에 직접적으로 보이지 않는 설정 영역
                       ---> 제목 , 문자 , 인코딩 , CSS , 메타 정보 등
           <title>      -|
             My Page     | --> 브라우저 탭에 표시되는 제목 
           </title>     -| --> 검색 결과 제목으로도 사용
        </head>        ---> head영역 끝
        <body>         ---> 브라우저 화면에 실제로 보이는 내용 영역
                       ---> 텍스트 , 이미지 , 버튼 등 위치
          Hello, HTML  ---> body 안의 텍스트 내용
                       ---> 브라우저에 그대로 표시
        </body>  
    </html>            ---> 각각 body와 html 영역의 끝
```
### 3. 자주 사용하는 태그(tag)
```html
    - <p> (paragraph): 문단 
    - <h1> ~ <h6> : 제목 크기 (h1이ㅣ 가장 큼) 
        <h1> : #
        <h2> : ##
    - <hr> : 가로선 (구분선)
    - <li> : list 목록 
        - <ol> : 순서가 있는 리스트
        - <ul> : 순서가 없는 리스트
    - <table> : 표 전체를 감싸는 틀
    - <tr> : 행 (가로줄)
    - <th> : 제목 칸 (굵게 , 가운데 정렬)
    - <td> : 내용 칸
    - <a> : 하이퍼링크 입력
    - ...등 

### Anchor : 닻 (a)
    - <a href="https://google.com">구글</a>
### Base : 
```html
    - Head : 제목 (페이지이름) -메파 데이터
    - Body : HTML의 내용을 보여줌

### Form :
    - <form action="주소">
        <input type"email" name="q" placeholder="이메일 입력하세요">
    - 사용자로부터 데이터를 입력 받는 양식을 만듦

### Table : 
    -<thead>
        <tr>
           <th>
           </th>
        </tr>
     </thead>
     <tbody>
        <tr>
           <td>
           </td>
        </tr>
     </tbody>