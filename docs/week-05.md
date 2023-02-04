---
title: 5주차
layout: default
nav_order: 2
---


## 5 주차

### 모듈 5-1: 데이터프레임의 요약 


-  데이터프레임을 이용하여 새로운 정보를 만드는 방법

    + 새로운 열 만들기
    + `sum` 메소드를 이용한 행과 열의 합계
    + 열에 대한 요약 통계

- [온라인 노트](https://uos-bigdata.github.io/bigdatabook/chapters/04/dataframe-summary.html)

### 모듈 5-2: 그룹별 요약 

- 메소드 `groupby( by=...)`는 지정된 열의 값으로 데이터프레임을 그룹화(group)
- 그룹별로 요약 통계량 생성

+ [온라인 노트](https://uos-bigdata.github.io/bigdatabook/chapters/04/dataframe-summary.html)


### 모듈 5-3: 데이터프레임의 결합

- 두개의 데이터프레임을 공통된 식별자를 기준으로 결합하는 방법
    + `pd.merge()` 함수를 사용
    + 선택문 `on=` 에 두 데이터프레임에 결합의 기준이 되는 열이름, 즉 식별자(key, identifier,..)을 문자열로 지정해준다. 
    + 결합의 기준으로 사용되는 식별자는 두 개의 데이터프레임에 모두 존재해야 한다.
    + `how=` 을 이용하여 두 갱의 데이터프레임 중 기준이 되는 데이터프레임을 지정

+ [온라인 노트](https://uos-bigdata.github.io/bigdatabook/chapters/04/dataframe-merge.html#id5)
 
### 모듈 5-4: 데이터프레임에 대한 방법 복습 


+ [슬라이드](/slides/dataframe.pdf)
 

