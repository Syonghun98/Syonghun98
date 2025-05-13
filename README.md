![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=300&section=header&text=Welcome%20to%20Yonghun%20GitHub&fontSize=50)

# Data Analyst

## 😜 About Me 😉
데이터를 통해 사용자의 숨겨진 니즈를 발견하고 데이터 기반의 의사결정에 도움을 주는 것을 목표로 합니다. Python, SQL, 머신러닝, 딥러닝 기술을 활용하여 데이터를 분석하고 인사이트 발굴에 기여하고자 합니다. 다양한 프로젝트 경험을 통해 데이터 분석에 필요한 실무 역량을 키우고 있으며 앞으로도 끊임없이 배우고 성장하여 사용자에게 최고의 가치를 제공하는 개발자가 되겠습니다.

## 🛠 Tech Stack
### Languages & Library
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-brightgreen)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-blue)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=Pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-0078D4?style=flat-square&logo=Matplotlib&logoColor=white)

### Frameworks
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=flat-square&logo=LangGraph&logoColor=white)

## 📚 Education
- 한서대학교(4.16/4.5) 무인항공기학과(주전공)/항공소프트웨어공학과(복수전공)
- KT AIVLE-EDU(Data Analysis & AI, 2024.09 ~ 2025.02)
- 멋쟁이사자처럼(Django - 백엔드 개발, 2022.04 ~ 2022.12)

## 🪪 Certifications
- AICE Associate - 2025.02
- 정보처리기사 - 2024.09
- 데이터분석준전문가(ADsP) - 2024.09
- SQL개발자(SQLD) - 2024.09
- 초경량비행장치 조종자 1종 - 2019.04

## 👀 Projects
### 실험군 vs 대조군 수익성 비교 A/B 테스트 분석
실험군(variant)과 대조군(control) 간의 사용자 수익(REVENUE)에 차이가 있는지를 평가하기 위한 A/B 테스트 실험 결과를 분석
- Data: Kaggle [A/B test data](https://www.kaggle.com/datasets/sergylog/ab-test-data/data)
- 목표: variant가 control보다 수익성이 높은지 확인
- 가설: 귀무가설(H0): Control의 수익 == Variant의 수익 / 대립가설(H1): Variant의 수익 > Control의 수익
- 기술: EDA, 중복 제거, Mann–Whitney U 검정
- 결과: 정규분포를 따르지 않음 / p-value > 0.05 → 귀무가설 기각 불가 / 수익의 차이는 통계적으로 유의하지 않음
- [Go to Repository](https://github.com/Syonghun98/ab-testing-revenue-comparison)

### 랜딩 페이지 전환율 A/B 테스트 분석
기존 페이지와 새로운 랜딩 페이지 간 전환율 비교를 위한 데이터 분석
- Data: Kaggle [A/B testing](https://www.kaggle.com/datasets/zhangluyuan/ab-testing)
- 목표: new_page가 old_page보다 전환율이 높은지 확인
- 가설: H0: new_page == old_page / H1: new_page > old_page
- 기술: EDA, 그룹/페이지 불일치 제거, 중복 제거, 카이제곱 검정
- 결과: p-value > 0.05 → 귀무가설 기각 불가 / 전환율 차이는 통계적으로 유의하지 않음
- [Go to Repository](https://github.com/Syonghun98/ab-testing-conversion-rate-analysis)

### 채무 불이행 여부 예측
Dacon "채무 불이행 여부 예측" 해커톤에서 진행되었습니다.
금융 데이터를 활용하여 고객의 채무 불이행 여부(0 또는 1)를 예측하는 분류 문제를 해결하는 것이 목표
- Data: 금융 데이터 (대출 목적, 직장 근속 연수 등)
- 기술: 데이터 스케일링(StandardScaler), 변수 중요도 분석, CatBoost 최적화(Bayesian Search), 단층 신경망(MLP) 실험
- 결과: 데이콘 해커톤 27위 / 1040명 중, AUC 최고 성능 0.638, '대출 목적' 변수 제거 시 성능 향상
- [Go to Repository](https://github.com/Syonghun98/Debt_Default_Prediction_Dacon)

### 애니메이션 추천 시스템 개발
캐글 데이터를 활용해 입력한 애니메이션과 유사한 애니메이션을 추천하는 모델 개발.
- Data: 애니메이션 정보, 사용자 평점 데이터
- 기술: 데이터 전처리(-1 제거, 결측값 처리), 협업 필터링 추천, SVD 모델
- 결과: 사용자 입력 기반 추천 결과 제공, 추후 Full Matrix 구조 메모리 문제 해결 방안 모색
- [Go to Repository](https://github.com/Syonghun98/Animation_Recommendation_System)

### 신규 아파트 주차 수요 예측
- Data: 국토교통부 및 SGIS 데이터를 활용한 신규 아파트 단지 주차 수요 예측
- 기술: KNN, 회귀, DecisionTree, RandomForest, LGB, XGB(GridSearch 최적화)
- 결과: 적정 주차공간 예측 및 데이터 기반 도시 계획 가능성 탐구
- [Go to Repository](https://github.com/Syonghun98/KT_Aivle_School_Project)

### 서울시 대중교통 수요 분석
서울시 대중교통 데이터를 분석하여 신규 버스 정류장 위치를 선정
- Data: 버스 승하차 정보, 유동인구, 주민등록, 업종 데이터
- 기술: 변수 분석, 가설 검증, 최적 정류장 위치 선정
- 결과: 신규 정류장 위치 제안 및 데이터 기반 의사결정
- [Go to Repository](https://github.com/Syonghun98/KT_Aivle_School_Project)

### PICK UP: 채용 어시스턴트 프로젝트
기업의 채용 프로세스를 효율적으로 개선하여 업무 부담을 줄이고 객관적인 지원자 평가를 제공
- 자동화된 평가: LangChain과 LangGraph를 활용한 이력서 분석 및 평가 점수 제공
- 맞춤형 면접 질문 생성: RAG 기법을 적용한 경험 중심, 경력 중심, 기술 중심 질문 생성
- LangChain: PDF 이력서 및 자기소개서에서 핵심 정보 자동 추출 및 임베딩
- LangGraph: 기업의 평가 기준과 과거 데이터 반영한 지원자 역량 분석
- RAG 기법: 정량화된 점수화 및 맞춤형 질문 생성
- [Go to Repository](https://github.com/Aivle08)
  

## 📧 Contact
unknownyh98@gmail.com
