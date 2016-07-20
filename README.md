# Airbnb Copy

## 프로젝트 선정 이유

저는 웹 프로그래밍을 제대로 배운 적이 없습니다. 하지만, 2015년 주니어 디자인 프로젝트 시간에 제가 맡은 부분이 기획, DB 설계와 UI/UX 부분이었습니다. UI 구현은 평소에 해보고 싶었다고 말하고 다녔지만, 접근 방법을 몰라서 미루고 있었던 찰나에 기회가 왔습니다. w3 school 에서 HTML 부터 javascript 기본 등등을 빠르게 학습하고, 여러 튜토리얼 그리고 구글링을 통하여 공부하고, 실제 Airbnb 사이트를 필요한 기능들만 추려서 재구성을 하는 작업을 했습니다. 페이지를 카피하는 것도 능력이 있어야 한다고 생각했기 때문에 선정하였습니다. 실제 Back-end 부분은 여기서 제가 참여하지 않았기 때문에 Front-end 부분만 선정하였습니다. jQuery-mobile, Bootstrap, Javascript, Ajax, HTML5, CSS3 등 그 이외의 여러 프레임워크들과 라이브러리를 사용하여 구성하였습니다. 디테일한 css 를 제외하고는 거의 대부분의 기본 기능들과 디자인이 실제 Airbnb 와 같습니다.

## 프로젝트 요약

- 로그인/검색/예약/소개글/추천 여행지/후기모음/최근 상품/문의란/구글 지도 등의 기능을 디자인합니다.
- 검색/경매 목록도 있습니다.
- 각각의 호스트들의 페이지도 있습니다.
- 호스팅에 사용되는 7단계도 자세히 구현하였습니다.

## 프로젝트 풀이

- 구글 지도 표시

google map API 스크립트 추가 -> google map 초기화 좌표 값 js 추가 -> google map 을 보여주는 추가 -> google map 클릭 시 좌표 값 얻어오는 함수 추가

- jQuery Mobile 로 DatePicker 구현

제이쿼리 css 추가 -> 제이쿼리 datepicker 추가를 위한 메소드 정의 및 추가

## 프로젝트 소감

이 프로젝트에서 제가 맡은 부분은 어떻게 보면, 그렇게 대단한 부분이 아닐 수도 있습니다. 하지만, 웹 페이지를 만드는데 디자이너가 없다는 건 꽤나 큰 핸디캡입니다. 때문에 자초하여 나섰습니다. 실제 Back-end 는 다른 학우들이 파이썬과 스프링으로 구현하여 제가 이 곳에 기술하기는 어렵습니다. 그래서 FRONT-END 개발자와 디자이너가 어떤 일을 하는지 대략적으로 배울 수 있는 기회였습니다. 제가 Github 에 올려놓은 소스를 확인하면, 꽤나 화려한 페이지들이 나옵니다. 만약 Ruby on Rails 로 짠 코드였다면, 훨씬 양이 줄었을 수도 있습니다. 반복되는 부분은 다 제외가 되니까 말입니다. 하지만, 직접 하나하나 html, css, javascript 코드를 써내려가면서, 끊임없는 테스트를 거쳐서 만든 페이지들입니다. 물론 설계 중심의 수업이라서 실제로 구현하여 사용되는 프로그램은 아니지만, html, bootstrap 사용방법, javascript 충돌 문제를 다루는 방법 등등을 가장 low 단계에서 배울 수 있었다는 점에서 하나의 작품이라고 저는 생각합니다.
