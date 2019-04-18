---
layout: post
title:  "식자재 유통 중개 서비스를 위한 개방형 웹 기반 플랫폼"
date:   2019-04-17
description: 산학공동과제로 (주)제이에이치코리아와 함께 진행한 프로젝트입니다.
---

<p class="intro"><span class="dropcap">소</span>규모 외식 사업자와 식자재 유통업자간 효율적인 식자재 대량 유통을 위한 중개 플랫폼입니다. 구조적 문제로는 안정적인 유통 경로 확보가 어려워 시간적, 금전적 비용소요가 발생하고 기술적 문제로는 소상공인들을 위한 유통 체계 및 관리 시스템이 부재합니다. 대책 마련으로는 유통 구조 및 마진 개선을 위한 유통 관리 시스템이 필요하고 개별 소상공인 수요-공급업자 연결을 위한 개방형 플랫폼이 필요합니다.</p>

<hr>

<!-- # Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6 -->

<!-- <blockquote>개발 환경</blockquote> -->

### 개발 기간
* 2018.07.01 ~ 2019.01.31

### 개발 플랫폼
1. Vue.js
2. Spring
3. Mysql
4. Atom(IDE)

### 주요 업무
* Vuetify를 이용한 전반적인 레이아웃 컨트롤
* axios를 이용한 데이터 바인딩 처리

### 개발 내용
* 시스템 구성도
<figure style="text-align: center;"><img src="{{ '/assets/img/산학공동과제_시스템구성도.JPG'}}" style="margin-bottom:0" alt=""><그림 1. 시스템 구성도></figure>
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

* DB 설계
<figure style="text-align: center;"><img src="{{ '/assets/img/산학공동과제_DB.png'}}" style="margin-bottom:0" alt=""><그림 2. DB 설계></figure>

### UI
<figure style="text-align: center;margin: 0"><img src="{{ '/assets/img/산학공동과제_주문목록.png'}}" style="margin-bottom:0" alt=""><그림 3. 주문 목록 이미지></figure>
  - 그림 설명
<figure style="text-align: center;margin: 0"><img src="{{ '/assets/img/산학공동과제_신규발주등록.png'}}" style="margin-bottom:0" alt=""><그림 4. 신규 발주 등록 이미지></figure>

<figure style="text-align: center;margin: 0"><img src="{{ '/assets/img/산학공동과제_배송팀수정.png'}}" style="margin-bottom:0" alt=""><그림 5. 배송팀 수정 이미지></figure>
