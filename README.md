# PROJECT MODI
> 패션 MD 업무 효율화를 위한 AI 기반 실무형 솔루션

<p align="center">
  <img src="https://github.com/KpmgFuture-Academy/fa02_fin_MODI/blob/main/img/modi_logo.png" width="300"/>
</p>

> 빠르게 변화하는 패션 시장에서, 패션 MD들은 반복적인 서류 업무와 트렌드 조사로 인해 전략적 의사결정에 집중하기 어려운 환경에 처해 있습니다.  
> MODI는 이러한 문제를 해결하기 위해 만들어진 **AI 기반 실무형 업무 자동화 솔루션**입니다.  
> OCR + NLP + Vector Search 기술을 활용해 문서 기반의 일정을 자동 추출하고, 글로벌 트렌드 분석을 자동화함으로써  
> **패션 MD들이 더 전략적인 업무에 집중할 수 있도록 지원합니다.**

---

## 👥 Team Members

| <img src="https://github.com/KpmgFuture-Academy/fa02_fin_MODI/blob/main/img/jh.png" width="130"/> | <img src="https://github.com/KpmgFuture-Academy/fa02_fin_MODI/blob/main/img/yj.png" width="130"/> | <img src="https://github.com/KpmgFuture-Academy/fa02_fin_MODI/blob/main/img/jy.png" width="130"/> | <img src="https://github.com/KpmgFuture-Academy/fa02_fin_MODI/blob/main/img/nr.png" width="130"/> |
|:--:|:--:|:--:|:--:|
| **박정훈**<br>PL · BE · DBA · FE<br>🧠 시스템 통합 / DB / 프론트 일부<br>[![GitHub](https://img.shields.io/badge/GitHub-junghoon-181717?logo=github)](https://github.com/ezypzylemon) | **지연주**<br>PM · DA · UX<br>📋 기획 / 데이터 분석 및 수집 / 사용자 경험 설계<br>[![GitHub](https://img.shields.io/badge/GitHub-yeonju-181717?logo=github)](https://github.com/y47love) | **박지윤**<br>PM · DA · UX<br>📊 기획 / 데이터 분석 및 수집 / 사용자 경험 설계<br>[![GitHub](https://img.shields.io/badge/GitHub-jiyoon-181717?logo=github)](https://github.com/Yuni-JiyoonPark) | **서누리**<br>BE · FE · UI · OCR<br>💻 백엔드 / 프론트 / UI / OCR<br>[![GitHub](https://img.shields.io/badge/GitHub-nuri-181717?logo=github)](https://github.com/NURI-S0320) |

| 이름             | 역할 요약 |
|-----------------|--------------------------------------------------------|
| **박정훈** (PL, DBA, FE)       | 🧠 Team Lead, DB 설계 및 관리, 프론트 일부 구현, 시스템 통합, Vector DB 설계, 백엔드 개발|
| **지연주** (PM, DA, UX)    | 📋 프로젝트 기획 및 아이데이션 리드, 데이터 분석 및 수집, 데이터 전처리, 프롬프트 엔지니어링, 사용자 경험 설계(UX) |
| **박지윤** (PM, DA, UX)    | 📊 프로젝트 기획 및 설계, 데이터 분석 및 수집, 데이터 전처리, RAG 및 시각화 기능 구현, 텍스트 정성 분석, 사용자 경험 설계(UX) |
| **서누리** (BE, FE, UI, OCR)   | 💻 백엔드 개발, 프론트 구현, UI 화면 구성, OCR 개발 |

### 🗂 역할 약어 설명

| 약어 | 설명                         |
|------|----------------------------|
| PL   | Project Leader             |
| PM   | Project Manager            |
| FE   | Frontend Engineer          |
| BE   | Backend Engineer           |
| DA   | Data Analyst               |
| DBA  | Database Administrator     |
| UX   | User Experience Designer   |
| UI   | User Interface Designer    |

---

## 🛠 기술 스택

### 📊 데이터 및 분석

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Kiwi 형태소 분석기](https://img.shields.io/badge/Kiwi-Tokenize-FFB6C1?logoColor=white)
![TF-IDF](https://img.shields.io/badge/TF--IDF-분석-FFD700)
![NetworkX](https://img.shields.io/badge/NetworkX-그래프분석-6495ED)
![GPT-4o-mini](https://img.shields.io/badge/LLM-GPT--4o--mini-blueviolet?logo=openai)

### 🧠 AI & OCR

![Google Cloud Vision API](https://img.shields.io/badge/Google_Vision_OCR-F44336?logo=googlecloud&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-검색_기반_생성-F57C00?logo=openai&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-벡터DB-008080?logo=qdrant)

### 💻 백엔드

![Flask](https://img.shields.io/badge/Flask-2.2-black?logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Relational_DB-4479A1?logo=mysql&logoColor=white)

### 📊 프론트엔드

![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## 📌 주요 기능 요약

| 기능 | 설명 |
|------|------|
| 🧾 **문서 기반 일정 자동 추출** | OCR을 통해 Order/Invoice에서 날짜, 항목, 수량 등 핵심 정보 자동화 |
| 📊 **트렌드 분석 대시보드** | Vogue, WWD, W Korea 등 매거진 기반 트렌드 자동 분석 (TF-IDF / 네트워크 분석) |
| 🔎 **임베딩 기반 검색기** | 사용자 질의에 대해 유사 문서 자동 탐색 및 요약 (RAG 기반) |
| 🧠 **자동화 리포트 생성기** | 뉴스/상품 데이터 기반 트렌드 리포트를 자연어로 생성 |
| 🧮 **항목별 자동 비교기** | 주문서 vs 인보이스 비교 및 불일치 자동 하이라이팅 표시 |

---

## 🎯 핵심 성과

- 평균 응답 점수 4.2 / 5.0  
- 사용자 80% 긍정 응답: "정보 탐색 속도 향상", "문서 자동처리 만족"
- 반복 작업 최소화 → 전략적 업무 비중 증가

---

## 🎥 프로젝트 데모 영상

[![MODI 데모 영상 1](https://img.youtube.com/vi/UMZ-141DHKk/0.jpg)](https://youtu.be/UMZ-141DHKk)  
[![MODI 데모 영상 2](https://img.youtube.com/vi/z22HRCvOL4Q/0.jpg)](https://youtu.be/z22HRCvOL4Q?si=5krFlcWnS2Nb-t5_)

---

## 🧭 시스템 아키텍처 (최종 흐름)

사용자  
 └─ ① 문서 업로드 (Order / Invoice PDF, 이미지, 키워드)  
     ├─ [OCR] Google Vision API  
     │     └─ 구매서 / 인보이스에서 핵심 정보 추출 (날짜, 품목, 수량 등)  
     │  
     ├─ [RAG 검색 & GPT-4o 요약]  
     │     └─ 유사 문서 검색 → GPT-4o-mini로 요약 생성 → 키워드 강조  
     │  
     └─ [대시보드 시각화]  
           ├─ 일정 추출 결과 캘린더 표시  
           ├─ 항목 불일치 자동 비교 표시  
           └─ 사용자 맞춤 우선순위 알림 제공

외부 수집기 (크롤러)  
 └─ ② 매거진 / 뉴스 데이터 수집  
     ├─ [크롤링] Selenium + BeautifulSoup  
     │     └─ Vogue / WWD / 무신사 / Google RSS 등에서 기사 수집  
     │  
     ├─ [본문 정제 + 전처리]  
     │     └─ HTML 제거, 이모지 제거, 줄바꿈 처리 등  
     │  
     ├─ [형태소 분석 및 키워드 추출]  
     │     └─ Kiwi 기반 명사 추출 및 토큰화  
     │  
     ├─ [DB 저장]  
     │     ├─ MySQL (title, content, upload_date, source 등)  
     │     └─ 형태소 결과도 `tokens` 컬럼 또는 별도 테이블에 저장  
     │  
     └─ [임베딩 및 분석]  
           ├─ TF-IDF / 네트워크 그래프 분석  
           └─ 문서 임베딩 후 Qdrant 저장 → 검색 & 대시보드 연계