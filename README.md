# 배서하 포트폴리오


## 📌 Intro
<br>
안녕하세요. <br>
신입개발자 배서하입니다.

## 📌 Projects
### 1. [IC_Mall](https://github.com/RowenKim/ICTeam.git) - github 주소
> 신선 식품 판매 쇼핑몰
* [AWS 서버 링크](http://15.164.244.62:8080/icmall/all/vegetable)
* [기능 작동 영상, 간략한 설명 PPT](https://docs.google.com/presentation/d/1J9ulvn62EGtyRAE-XLZkV6Y2RU2fnBg8aDb-4TOJSLs/edit?usp=sharing)
* 기간: 2021.09.18 ~ 10.14
* 참여 인원: 4명
* 역할: Front-end 총괄, 메인페이지, 장바구니, 결제 부분 기능 구현, AWS 서버 구축
* 사용 기술: JAVA11, JSON, springboot, MySQL5, Javascript,  jsoup, MyBatis, JSTL, KakaoAPI
* 주요 개발 내용: <br>
· jsoup을 이용하여 11번가 야채 상품 크롤링 <br>
· 메인페이지, 카테고리 페이지 등 Mysql DB 화면 구현<br>
· 장바구니, 주문하기 등 데이터 DB에 저장, DB의 주문 상태 결제완료 -> 결제 취소로 업데이트<br>
· 장바구니에서 주문하기 클릭시 장바구니의 상품들 Mysql DB에서 삭제, 주문하기 클릭시 주문하기 상품들 DB에서 삭제<br>
· JSTL을 사용하여 결제 완료일때만 주문취소요청 버튼 보이도록 구현<br>
* 문제 해결 경험:<br>
· 쇼핑몰에 보여줄 상품들의 데이터를 크롤링으로 가져오자는 의견이 모아진 상황에서 모두 자바로 크롤링 하는 법을 배운적이 없었습니다. <br>
  구글링과 유튜브 강의를 참고 jsoup을 이용하여 11번가 상품 정보를 가져올 수 있었습니다.
· Git 을 활용하여 프로젝트 진행 중 Commit을 하지않고, Pull을 실행하여 작성했던 결과물들이 다 없어졌는데 개발자 오픈 톡방에 질문하여 Eclipse자체의 기록기능으로 복구시킬 수 있었습니다.<br>
· 로컬 서버로 띄우는 것 보다 다른사람도 들어가보고 작동할 수 있도록 AWS를 이용하여 서버를 띄워봤지만 완벽하게는 띄우지 못했습니다.<br>





