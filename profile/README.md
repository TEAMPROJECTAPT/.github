# 조선대학교 산학프로젝트1 

## 프로젝트 활동 내역
[Main Repository](https://github.com/TEAMPROJECTAPT/main)

[App Repository](https://github.com/TEAMPROJECTAPT/app)

## 프로젝트 개요
머신러닝을 활용해 QR코드 기반 피싱 사이트를 실시간으로 탐지·차단하는 시스템을 구현하는 프로젝트입니다.

### 팀장
- **정제윤**

### 팀원
- **임정훈**
- **박진우**
- **강보석**
- **김민지**

### 진행 완료
최신 데이터 수집 및 특징 추출 함수 구현 완료.

최신 데이터 기반 2025_URL_DATASET 구성 완료.


### 진행 중
모델 성능 비교 및 최적화 진행 중  

QR 코드 어플리케이션 개발 중 

AWS 서버 구축 진행 중

### 기능별 스크립트 설명

`extract_features_1_22.py`  
피쳐 1 ~ 22 추출

`extract_features_23_26.py` 
피쳐 23 ~ 26 추출

`extract_valid_urls.py`  
유효한 정상 URL 필터링

### 데이터셋 설명

`2025_URL_DATASET.csv`  
최신 데이터 기반 데이터셋

`features_1_22.csv`  
특징 추출 1 ~ 22

`features_23_26.csv`  
특징 추출 23 ~ 26

`top-1m.csv`  
Tranco 기반 순위 데이터

`phish_score.csv`  
PhishStats에서 수집한 피싱 URL 데이터

