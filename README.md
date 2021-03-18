# 🔹웹툴🔹이미지 텍스트 편집기 ver2.1

>https://github.com/DragooCho/ImageTextEditor        
 p5js로 구현했던 **이미지 텍스트 편집기**를 순수 자바스크립트로 재구현 했습니다.

<br />

## 1. 제작 기간 & 참여 인원
- 2021년 3월 15일 ~ 3월 18일
- 개인 프로젝트

<br />

## 2. 사용 기술
#### `Front-end`
  - javascript 
  - HtML5canvas

<br />

## 3. 핵심 기능
이 서비스의 핵심 기능은 **자유로운 텍스트 조작 기능**입니다.  
사용자가 로컬 내에 가지고 있는 이미지 파일을 선택하고        
입력창에 원하는 글자를 원하는 위치에 입력하고 따라 붙인후        
저장하는 버튼을 누르면 끝입니다.         
<br />
조작을 최대한 단순하게 구현했으며    
자연스러운 사용자 경험을 유도했습니다.

<br />

## 4. 부가 기능

텍스트의 `색상`, `사이즈`, `폰트타입`을 정해진 `옵션창` 및 `슬라이더`로 조절 가능합니다.
<br />
<br />


## 5. 구현하면서 힘들었던 점

- `p5.js`의 라이브러리 없이 순수 자바스크립트로 구현을 목표로 한 프로젝트 입니다.       
- 완료한 캔버스이미지를 파일로 저장하는 작업이 가장 까다로웠습니다.         
  해당 주소를 겍체화 시키고 임의로 만들어진 노드에 대입시켜야 하는 까다로운 로직밖에 없었습니다.         
- 다운로드 버튼에 addEventListener의 속성을 쓰면 에러가 일어났기에 대신 html의 onclick을 이용했습니다.      
  원인은 여전히 알 수 없었습니다. 
- HTMLCanvasElement.toBlob()의 메서드는 로직이 간결했지만       
  이미지의 사이즈가 조금이라도 많으면 오류가 일어나기에 dataURL를 조작하는 방법으로 바꾸었습니다.

<br />
<br />

## ver2.1 변경점

1. 세로로 보기에 최적화됬던 홈페이지 디자인을 가로 중심의 디자인으로 변경했습니다.


