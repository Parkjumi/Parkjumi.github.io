---
layout: post
title:  "식자재 유통 중개 서비스를 위한 개방형 웹 기반 플랫폼"
date:   2019-04-17
description: 산학공동과제로 (주)제이에이치코리아와 함께 진행한 프로젝트입니다.
---

<p class="intro"><span class="dropcap">소</span>규모 외식 사업자와 식자재 유통업자간 효율적인 식자재 대량 유통을 위한 중개 플랫폼입니다. 구조적 문제로는 안정적인 유통 경로 확보가 어려워 시간적, 금전적 비용소요가 발생하고 기술적 문제로는 소상공인들을 위한 유통 체계 및 관리 시스템이 부재합니다. 대책 마련으로는 유통 구조 및 마진 개선을 위한 유통 관리 시스템이 필요하고 개별 소상공인 수요-공급업자 연결을 위한 개방형 플랫폼이 필요합니다.</p>

<hr style="border: solid 1.2px #2e8b57">

<!-- # Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6 -->

<!-- <blockquote>개발 환경</blockquote> -->

#### 개발 기간
* 2018.07.01 ~ 2019.01.31

#### 개발 인원
* 5명

#### 개발 플랫폼
1. Vue.js
2. Spring
3. Mysql
4. Atom(IDE)

#### 주요 업무
* Vuetify를 이용한 전반적인 레이아웃 컨트롤
* axios를 이용한 데이터 바인딩 처리
* 플랫폼 관리자 요구사항 정의

#### 시스템 구성도
<figure style="text-align: center;margin:0"><img src="{{ '/assets/img/산학공동과제_시스템구성도.JPG'}}" style="margin-bottom:0" alt=""><그림 1. 시스템 구성도></figure>
1. Front-End
 - 웹 또는 모바일 기기로 접근할 수 있는 HTML5 웹표준 호환 UI/UX
 - 식자재 데이터 및 업무 관련 데이터 관리 기능 개발
 - 데이터 시각화 콘텐츠 제공 모듈 개발
 - 주문-결제 시스템과 연동 기능 개발
2. Open type Back-End Platform
 - 범용성 및 호환성 보장하는 개방형 REST API 모듈
 - Back-End 보안 모듈
 - 데이터베이스 관리 모듈
3. Database
 - REST API 호환 관계형 데이터베이스 구축

#### 데이터베이스 설계
<figure style="text-align: center;"><img src="{{ '/assets/img/산학공동과제_DB.png'}}" style="margin-bottom:0" alt=""><그림 2. DB 설계></figure>

#### RESTful Document
<figure style="text-align: center;"><img src="{{ '/assets/img/주문검색조회.png'}}" style="margin-bottom:0"><그림 3. RESTful api Document></figure>

#### 구현 결과
<figure style="text-align: center;margin: 0"><img src="{{ '/assets/img/산학공동과제_주문목록.png'}}" style="margin-bottom:0" alt=""><그림 4. 주문 목록 이미지></figure>
그림 4은 주문 목록 메인 화면을 나타낸다. 좌측에는 항상 고정되어 있는 주문관리, 매입관리, 상품관리, 거래처관리, 배송팀관리, 공지사항 메뉴 컴포넌트가 있다. 그 중 주문 관리 하위 메뉴에는 주문 목록이 있다. 주문 목록에는 기간과 검색어를 선택하여 검색할 수 있다. 목록을 보면 주문일시, 주문번호, 거래처 이름, 배송팀, 영업팀, 총 주문수량, 결제수단, 주문금액, 주문상태를 볼 수 있다. 신규주문 등록을 누르게 되면 주문을 할 수 있는 페이지가 나오고 목록 중 하나의 주문을 누르게 되면 상세내용을 볼 수 있다.

<figure style="text-align: center;margin: 0"><img src="{{ '/assets/img/산학공동과제_신규발주등록.png'}}" style="margin-bottom:0" alt=""><그림 5. 신규 발주 등록 이미지></figure>
그림 5는 매입 관리 하위 메뉴에 있는 발주 관리, 매입처 관리 중 발주 관리에서 볼 수 있다. 주문관리와 마찬가지로 신규 발주를 누르게 되면 발주를 등록할 수 있는 페이지가 나온다. 발주 정보를 입력하게 되는데 매입처 선택을 누르게 되면 등록된 매입처 목록이 나온다. 매입처를 선택하고 납기일자 및 비고를 입력할 수 있다. 하위에서는 상품추가를 누르게 되면 매입처에 등록된 상품들이 나오게 된다. 사용자가 추가하게 되고 바로 하위 목록에 추가된 상품들이 나오고 발주 등록을 할 수 있다.  

<figure style="text-align: center;margin: 0"><img src="{{ '/assets/img/산학공동과제_배송팀수정.png'}}" style="margin-bottom:0" alt=""><그림 6. 배송팀 수정 이미지></figure>
그림 6에서는 배송팀 관리 하위 메뉴에 있는 배송팀 목록에서 배송팀 정보 하나를 누르게 되면 상세페이지에 들어가게 된다. 등록되어 있던 배송팀 정보가 출력되며 기본 정보 및 배송 담당자 정보를 수정할 수 있다. 

#### 파급효과
1. **외식업계**
  - 개방형 식자재 유통관리 플랫폼 구축
  - 안정적인 삭자재 확보 체계 확보
  - 식자재 구입 비용 감소
  - 배송 비용 감소
  - 소상공인 권익 보호 효과
2. **IT 산업**
  - 개방형 웹 플랫폼 요소기술 확보
  - IT 융합 기반 기술 확보
  - IT 융합 서비스 분야 경쟁력 향상
  - 웹 플랫폼 관련 인재 양성
