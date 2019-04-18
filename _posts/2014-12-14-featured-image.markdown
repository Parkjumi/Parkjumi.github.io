---
layout: post
title:  "플립 러닝에 기반한 e-그룹 학습 시스템"
date:   2019-04-18
description: 졸업프로젝트 "플립 러닝에 기반한 e-그룹 학습 시스템" 입니다.
---

<p class="intro"><span class="dropcap">주</span>입식 강의로는 미래형 인재를 키우기 어렵기 때문에 e-러닝의 진화로 주입식 교육의 반대인 플립러닝이 이슈화되고 있다. 주입식 교육에서는 교사의 일방적인 주도성을 가지며 학생의 생동감, 흥미, 능력, 필요를 전혀 무시하는 단점이 있다. 이를 해소하기 위해 본 논문에서는 그룹 스터디 활동에 플립 러닝 방식을 적용함으로써 스스로 학습을 유도하는 시스템을 제시한다. 대표 학생은 활동 기간 동안 교사 역할과 함께 책임자가 되고, 수업  할 자료를 공유할 수 있는데 학생들은 자료마다 질문을 남길 수 있다. 대표 학생이 질문 확인을 함으로써 학생 진도를 확인할 수 있다.</p>

<hr>

<!-- # Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6 -->

<!-- <blockquote>개발 환경</blockquote> -->

### 개발 기간
* 2018.03.01 ~ 2018.08.31

### 개발 플랫폼
1. Node.js
2. jQuery
3. Mysql
4. Semantic UI
5. Atom(IDE)

### 주요 업무
* 데이터베이스 설계 및 개발
* 보류

### 시스템 개념도
학생은 주제에 맞는 스터디 그룹을 등록하여 함께하고 싶은 학생들과 함께 그룹을 형성하게 된다. 관리자의 승인에 의해 스터디 그룹은 운영할 수 있게 된다. 교사 역할은 교사 학습 기간 내에 학습을 하고 자료를 등록한다. 자료는 첨부파일(ppt, 한글 파일 등)과 동영상을 올릴 수 있다. 교사 역할 학생만이 학생, 자료, 스터디 관리를 할 수 있는 권한이 생긴다. 그림.1은 제안 서비스 개념도를 나타낸다.
<figure style="text-align: center;"><img src="{{ '/assets/img/시스템 개념도.png'}}" style="margin-bottom:0" alt=""><그림 1. 시스템 개념도></figure>

### 시스템 클래스
그림 2과 3은 그룹 학습 시스템의 클래스 구성도를 보여주다. 그림 2는 스터디 등록 클래스 다이어그램 화면(스터디 등록, 학생 승인, 스터디 그룹 정보)을 나타낸다. 스터디 등록을 하기 위해서는 학생 정보와 그룹의 정보를 관리자에게 승인 받아야 한다. 학생 승인 화면에서는 학생들의 정보 및 목록을 볼 수 있으며 승인 여부를 확인 할 수 있다. 스터디 그룹 정보에서는 스터디에 관한 정보를 확인 할 수 있다.
<figure style="text-align: center;"><img src="{{ '/assets/img/시스템클래스1.png'}}" style="margin-bottom:0" alt=""><그림 2. 스터디 인증 다이어그램></figure>
그림 4는 그룹 스터디 클래스 다이어그램 화면(스터디 메인, 자료 수정, 자료 등록, 스터디 설정, 학생 회원가입)을 나타낸다. 스터디 메인 화면에서는 자료, 스터디, 공지사항, 질문 등을 한 번에 확인이 가능하다. 
<figure style="text-align: center;"><img src="{{ '/assets/img/시스템클래스2.png'}}" style="margin-bottom:0" alt=""><그림 3. 그룹 스터디 다이어그램></figure>

### UI
<figure style="text-align: center;margin: 0"><img src="{{ '/assets/img/산학공동과제_주문목록.png'}}" style="margin-bottom:0" alt=""><그림 3. 주문 목록 이미지></figure>
  - 그림 설명
<figure style="text-align: center;margin: 0"><img src="{{ '/assets/img/산학공동과제_신규발주등록.png'}}" style="margin-bottom:0" alt=""><그림 4. 신규 발주 등록 이미지></figure>

<figure style="text-align: center;margin: 0"><img src="{{ '/assets/img/산학공동과제_배송팀수정.png'}}" style="margin-bottom:0" alt=""><그림 5. 배송팀 수정 이미지></figure>
