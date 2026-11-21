# CSS 
    - HTML 요소의 모양과 배치를 정하는 언어
        - 글자 색 , 크기 , 폰트
        - 여백 , 정렬 위치
        - 레이아웃 (Flex , Grid)
            - 화면에 요소를 어떻게 배치?
        - 반응형 디자인
            - 화면 크기에 따라 레이아웃이 자동으로 바뀌는 디자인
    
    - Inline Style (인라인 스타일)
        - HTML 태그 안  style 속성을 이용하여 CSS를 직접 적용하는 방식
        - 장점 / 단점 : 
            - 장점 : 빠르고 간단하게 가능 / 특정 요소만 바로 꾸밀 수 있음 / 우선순위가 높음
            - 단점 : 코드가 지저분해지고 유지보수가 어려움 / 같은 스타일을 반복해서 써야 함 / 재사용 불가

    - Internal CSS (내부 스타일 시트)
        - HTML 문서의 <head>안에 <style>태그를 만들고, 그 안에 CSS를 작성하는 방식
        - 해당 HTML 문서 하나 전체에 적용
        - 선택자를 사용해서 여러 요소를 한번에 꾸미기 가능
        - 인라인 스타일보다 우선순위는 낮고, 외부 스타일 시트와는 작성 순서에 따라 달라짐
        - 장점 / 단점 :
            - 장점 : 한 페이지 안에서 스타일을 한번에 관리 / 별도 CSS 파일 필요X / 선택자로 여러 요소에 일괄 적용
            - 단점 : 다른 HTML 파일에서는 재사용X / HTML 파일이 길어지고 복잡해짐 / 여러 페이지를 만들면 중복 코드 발생

    - Selectors : 여러 HTML 요소에 스타일을 적용할지 지정하는 규칙
        - 전체 selector : *
        - 태그 selector : div
        - 클래스 selector : .class
        - ID selecoor : #id

    - 결합자(관계) Selector
        - 자손 선택자 : div p
            - div안에 있는 모든 p
        - 자식 선택자 : div > p
            - div의 바로 아래 자식 p만
        - 인접 형제 : div + p
            - div 바로 다음에 오는 p 하나
        - 일반 형제 : siv ~ p
            - div 뒤에 오는 모든 형제 p

    - 속성 셀렉터
        - a[herf]: href속성을 가진 a태그 선택
        - input[type="text"]: type 속성이 "text"인 input 태그 선택

    - selector 우선순위
        - !important
        - inline style (style="")
        - id 선택자 (#id)
        - class / 속성 / pseudo-class (.class, [type], :hover)
        - 태그 선택자 (div, p)
        - * (전체 선택자)

    - CSS 박스 
        - 마진 (margin) 
        - 테두리 (border)
        - 패딩 (padding)
        - 콘텐츠 (content)

        - 가로 길이 (width)
        - margin, padding : 박스 바깥 , 안쪽 여백
        - box-sizing : 박스 크기를 계산하는 기준
        - Inline / BLock : 박스가 차지하는 기본 배치 방식