# CSS Box Model
- HTML 요소를 감싸는 상자
- 요소, 패딩, 테두리, 마진으로 구성
- 블록 박스에 적용되며, 인라인 박스로 할 시 width, height, 상하 margin 값은 적용되지 않음

## width
- 요소의 너비 설정
- 속성
  - auto : 기본값으로, 브라우저가 계산하여 지정함
  - min-content : 최소 너비
  - max-content : 컨텐츠 내용의 선호 너비
  - fit-content : ?

## height
- 요소의 높이 설정
- auto : 기본값으로, 브라우저가 계산하여 지정

## padding
- 단축 속성
- `padding-top`. `padding-right`. `padding-bottom`, `padding-left` 순으로 작성

## margin
- 단축 속성
- `margin-top`, `margin-right`, `margin-bottom`, `margin-left` 순으로 작성

## border
- 테두리 지정
- 요소가 차지하는 전체 너비, 높이의 일부
- 단축 속성이며, 선의 두께나 스타일, 색상을 지정할 수 있음
  - `border-weight`, `border-style`, `border-color`

## box-sizing
- content-box : 기본값이며. width, height에 border, padding 포함하지 않음
- border-box : width, height에 border, padding 포함

## overflow, overflow-x, overflow-y
- 박스보다 콘텐츠가 더 커 콘텐츠가 넘칠 경우 어떻게 처리할지 지정
- visible : 기본값이며, 박스를 넘는 콘텐츠를 자르지 않음
- hidden : 요소의 크기만큼 맞추기 위해 잘라내며, 스크롤바 미제공
- scroll : 요소의 크기만큼 잘라내며, 스크롤바 제공
- auto : 자동으로 콘텐츠가 넘칠 경우 스크롤바 노출

## border-radius
- 테두리 경계의 꼭짓점을 둥글게 만들어줌
