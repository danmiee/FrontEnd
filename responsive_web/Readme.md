<hr/>

# HTML 문서작성
* 섹션 구분
* 접근성 고려한 태그 활용 및 내용작성
* 외부자료 연결
  + CSS
  + 웹아이콘 : fontawesome
  + 웹폰트 : 구글웹폰트

<hr/>

# CSS 작성
* 1개 파일에 많은 내용이 적혀있어 확인 및 수정 불편<br>
   ---> 파일 구분 필요

<hr/>

# Media Queries 작성
* @media only screen
    and (min-width:$px)
    and (max-width:$px) {}
  + 미지원 웹브라우저 반응
    - only : 미디어쿼리를 무시하고 실행하지 않음
    - not : not 다음에 지정한 미디어 유형 제외
  + 사용 디바이스
    - all : 모든 미디어 유형
    - print : 인쇄장치
    - screen : 컴퓨터나 스마트폰 화면
    - etc. : tv, aural, braile, handeld, projection, tty, emmbossed
  + 너비, 높이 속성
    - width/height : 웹문서
    - min-width / min-height : 웹페이지 최소값
    - max-width / max-height : 웹페이지 최대값
    - 기타<br>
      device-width/device-height<br>
      min-device-width(height) / max-device-width(height)<br>
      
<hr/>
