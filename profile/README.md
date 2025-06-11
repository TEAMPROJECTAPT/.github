<!-- 상단 배너 -->
<p align="center">
 <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=160&section=header&text=조선대학교%20산학프로젝트1-10조&fontSize=36&fontAlignY=35&desc=Machine%20Learning-Based%20Phishing%20Website%20Detection%20Project&descAlign=60&descAlignY=52&descSize=22" alt="banner"/>
</p>


<p align="center">
  <img src="https://img.shields.io/badge/Phishing%20QR%20Detection-Active-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Last_Update-2025.06.10-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/ML-Python-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Flask-Deploy-black?style=flat-square&logo=flask"/>
</p>

---

## 📚 Repository Links

- [GitLab](https://git.chosun.ac.kr/iap1-2025/class-06/team-10)
- [main](https://github.com/TEAMPROJECTAPT/main)
- [앱 Repo (GitHub)](https://github.com/TEAMPROJECTAPT/app)

---

## 🕹️ Quick Index

- [프로젝트 개요](#프로젝트-개요)
- [팀 구성/역할](#팀-구성역할)
- [진행 현황](#진행-현황)
- [개발 일정](#개발-일정)
- [기술 스택](#기술-스택)
- [브랜치](#브랜치)
- [주요 기능](#주요-기능)
- [주요 코드/스크립트](#주요-코드스크립트)
- [데이터셋 안내](#데이터셋-안내)
- [프로젝트 회고](#프로젝트-회고)
- [설치/실행 가이드](#설치실행-가이드)

---

## 📝 프로젝트 개요

**QR코드 기반 피싱 사이트를 머신러닝으로 탐지/차단하는 실시간 시스템 개발 프로젝트입니다.**

- **목표:**  
  - 최신 데이터 기반 피싱 URL 자동 탐지  
  - QR코드 연동 어플리케이션 개발  
  - 실시간 서버 배포/운영

---

## 👥 팀 구성/역할

<div align="center">

| 🏆 역할          | 🙋‍ 팀원              |
|:----------------:|:---------------------|
| Team Leader/ML Dev     | **정제윤**            |
| Data/App   | **임정훈**            |
| Data/ML  | **박진우**            |
|       | **강보석**            |
|       | **김민지**            |

</div>

---

## ⏳ 진행 현황

<details>
<summary>진행 내역 보기</summary>

| 📅 날짜         | 🟢 완료             | 🟡 진행중/계획      |
|:---------------:|:-------------------|:-------------------|
| 2025.04~06      | 최신 데이터 수집/정제<br>특징 추출 함수 구현<br>`2025_URL_DATASET` 완성<br>모델 성능 비교/최적화<br>QR앱 개발<br>AWS 서버 구축(로컬 서버로 구축)|  |

</details>

---

## 📅 개발 일정

> 프로젝트 전체 기간 : 2025.03.04 ~ 2025.06.09

---

## 🛠️ 기술 스택

**Backend / ML**  
&nbsp;&nbsp;[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python)](https://www.python.org/)  
&nbsp;&nbsp;[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)](https://pandas.pydata.org/)  
&nbsp;&nbsp;[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn)](https://scikit-learn.org/)  
&nbsp;&nbsp;[![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=for-the-badge&logo=xgboost)](https://xgboost.readthedocs.io/)  
&nbsp;&nbsp;[![LightGBM](https://img.shields.io/badge/LightGBM-028858?style=for-the-badge)](https://lightgbm.readthedocs.io/)  
&nbsp;&nbsp;[![CatBoost](https://img.shields.io/badge/CatBoost-FAAB00?style=for-the-badge)](https://catboost.ai/)  
&nbsp;&nbsp;[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib)](https://matplotlib.org/)  
&nbsp;&nbsp;[![Seaborn](https://img.shields.io/badge/Seaborn-76B900?style=for-the-badge)](https://seaborn.pydata.org/)
&nbsp;&nbsp;[![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask)](https://flask.palletsprojects.com/)

**Infra**  
&nbsp;&nbsp;[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)  
&nbsp;&nbsp;[![GitLab](https://img.shields.io/badge/GitLab-FCA121?style=for-the-badge&logo=gitlab&logoColor=white)](https://gitlab.com/)  
&nbsp;&nbsp;[![VSCode](https://img.shields.io/badge/VS%20Code-0078d7?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)



---

## 🗂️ 브랜치

### 🔀 Branches

- `main` : 통합 관리(최종/배포)
- `test` : 각 구성원이 본인 개발에 필요한 브랜치를 생성해 작업 후, 최종적으로 main 브랜치에 병합하는 방식으로 운영

---

## 💻 주요 기능

| 주요 기능                    | 간단 설명                                          |
|:----------------------------|:--------------------------------------------------|
| 실시간 URL 피싱 탐지         | QR코드 등에서 추출된 URL 실시간 ML 기반 탐지        |
| 피처 추출 자동화             | 데이터 수집~분석까지 전과정 스크립트화             |
| SHAP 기반 피처 가중치 분석   | 데이터/모델별 중요 특징 해석                        |
| QR코드 앱                    | 모바일 QR 리더 앱 (웹 연결 및 결과 표시)           |
| 서버 배포/운영(로컬 서버로 구축)                | 서버 자동 배포 및 모니터링                          |

---

## 🛠️ 주요 코드/스크립트

| 파일명                        | 설명                                                        |
|:------------------------------|:------------------------------------------------------------|
| `extract_features_1_22.py`    | 피처 1 ~ 22 추출                                            |
| `extract_features_23_26.py`   | 피처 23 ~ 26 추출                                           |
| `extract_valid_urls.py`       | 유효한 정상 URL 필터링                                      |
| `feature_analysis_shap.py`    | 피처별 가중치 분석 (SHAP 기반)                              |
| `optuna_vc_optimization.py`   | Optuna 기반 Voting Classifier 하이퍼파라미터 최적화         |
| `phishing_detector.py`        | 피싱 URL 탐지 메인 모델/함수                                |
| `server.py`                   | Flask 기반 API 서버                                        |
| `vc_drop_one_feature_out.py`  | Voting Classifier drop-one-feature 분석 (중요도 평가)       |

---

## 📦 데이터셋 안내

| 파일명                             | 설명                                       |
|:-----------------------------------|:-------------------------------------------|
| `2025_URL_DATASET.csv`             | 최신 데이터 기반 메인 데이터셋              |
| `features_1_22.csv`                | 1 ~ 22번 특징 추출값                        |
| `features_23_26.csv`               | 23 ~ 26번 특징 추출값                       |
| `top-1m.csv`                       | Tranco 순위 기반 Top 사이트 데이터           |
| `phish_score.csv`                  | PhishStats 수집 피싱 URL                    |
| `shap_weighted_feature_importance.csv` | SHAP 기반 TOP 20 피쳐 가중치 데이터    |

---

## 💭 프로젝트 회고

- **장점/성과**  
  - 데이터 파이프라인 및 ML 모델 자동화 경험  
  - QR 스캔 앱과 로컬 서버 간 연동 시스템 구현 
  - 팀 협업, 코드 공유·문서화에 익숙해짐

- **아쉬운 점/개선점**  
  - 실제 악성 피싱 URL 대응 지속 필요  
  - 앱/웹 배포·UX 고도화 남아 있음  
  - 커뮤니케이션 툴 더 적극 활용 필요

---

## ⚙️ 설치/실행 가이드

- **1. 소스 코드 클론**
git clone https://git.chosun.ac.kr/iap1-2025/class-06/team-10

- **2. 가상환경 생성 및 활성화**
    ```cmd
    python -m venv venv
    venv\Scripts\activate
    ```
    
- **3. 패키지 설치**
pip install -r requirements.txt

- **4. API 키 입력**
extract_features_23_26.py 파일 내 GOOGLE_API_KEY 값 입력

- **5. 서버 실행(루트 디렉토리에서 실행)**
python script/server.py

- **6. 앱 설치**
    ```cmd
    1. Android Studio 설치
    2. 아래 GitHub 저장소 클론:
       https://github.com/TEAMPROJECTAPT/app
    3. MainActivity.kt 파일에서 내부 IP 주소로 수정
    4. 앱 빌드 및 Android 기기에 설치
    ```

