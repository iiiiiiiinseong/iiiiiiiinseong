<h1 align="center">Hi, I'm Inseong 👋</h1>

<p align="center">
  <b>Data Scientist · AI Service Engineer</b><br/>
 데이터와 AI로 비즈니스 가치를 만드는 개발자, <b>양인성</b>입니다.
</p>

---

## 👨‍💻 About Me

- Hospitality 도메인과 AI를 함께 공부한 비즈니스 언어와 기술을 모두 아는 AI Engineer입니다.  
- 생성형 AI, RAG, Multi-Agent Workflow를 활용해 실제 서비스에 가까운 프로토타입과 PoC를 만드는 것에 집중하고 있습니다.  
- 데이터 수집 → 모델링 → 해석 가능한 분석 → 대시보드/에이전트 서빙까지 End-to-End 파이프라인을 설계·구현합니다.  
- 서울시 빅데이터 분석 공모전 2등을 달성하며, 데이터로 도시/비즈니스 문제를 풀어본 경험이 있습니다.  

---

## 🚀 What I’m Building

### Travel Agent — AI 트립 플래너 PoC (2025.10 ~ 2025.11)
> “여행 고민 대신 입력만” 하면 취향 맞춤 일정을 완성해 주는 Multi-Agent 여행 플래너

- 목적지, 예산, 인원, 여행 스타일만 입력하면 맞춤형 여행 일정을 자동 생성  
- Master Agent가 여행지·항공·숙소·액티비티 Agent를 오케스트레이션하는 A2A(Agent-to-Agent) 구조 설계  
- MCP Server를 통해 지도, 리뷰, 가격 등 외부 데이터 소스 실시간 연동  
- Stack: `Python` · `FastAPI` · `Streamlit` · `LangGraph` · `MCP` · `Docker`

---

### Finance Agent — 금융 Multi-Agent RAG 시스템 PoC (2025.07 ~ 2025.09)
> 질문에서 상품 가입까지 끊김 없는 경험을 제공하는 AI 금융 컨시어지

- GPT Classifier + Router로 질의를 분류하고, FAQ / 상품 비교 / 가입 상담 Agent로 분배  
- `FAISS` + `BM25`를 조합한 하이브리드 Retrieval 및 메타데이터 필터링으로 검색 품질 향상  
- `RAGAS`, `RAGChecker`를 활용한 RAG 평가 파이프라인 구축 (예: Faithfulness 85% 수준 달성)  
- Stack: `Python` · `LangGraph` · `LangChain` · `FAISS` · `OpenAI API` · `Streamlit` · `RAGAS` · `RAGChecker` · `MCP`

---

## 🧠 Projects

### 호텔 리뷰 평점 민감도 요인 분석 (2025.05 ~ 2025.07)
> 비정형 리뷰 기반, 호텔 등급별 서비스 속성 중요도 & 민감도 분석 파이프라인

- SBERT + UMAP + HDBSCAN으로 다국어 리뷰 토픽 모델링 파이프라인 구축  
- GPT-4o-mini 기반 Few-shot Prompting으로 서비스 속성/감성 Multi-Aspect 자동 태깅 시스템 구현  
- `XGBoost` + `SHAP`으로 속성별 평점 기여도를 정량화, PRCA & AIPA 프레임워크로 Penalty/Reward 민감도 분석 수행  
- Stack: `Python` · `SBERT` · `UMAP` · `HDBSCAN` · `XGBoost` · `SHAP` · `OpenAI API` · `Scikit-learn` · `Pandas`

---

### 관광객 인구통계 기반 맞춤형 관광지 추천 (2024.03 ~ 2024.06)
> 관광객 특성에 맞는 관광지 추천 + 최적 경로를 제시하는 추천 시스템

- 인구통계(성별, 연령대, 소득, 여행스타일 등) + 방문지(체류시간, 만족도 등) 기반 데이터 모델링  
- `CatBoost Regressor`로 만족도 예측 모델 구축, Random Search + K-Fold로 성능 튜닝  
- 예측된 만족도를 활용해 Top-N 관광지 추천 및 `Dijkstra` 기반 경로 최적화 수행  
- Stack: `Python` · `Pandas` · `Scikit-learn` · `CatBoost` · `Numpy` · `Folium` · `Matplotlib`

---

### 카페 녹원 디지털 전환 컨설팅 (2023.12 ~ 2024.02)
> 오프라인 카페의 운영 효율화를 위한 데이터 기반 IT 컨설팅 프로젝트 (PM)

- 다수 배달 플랫폼 매출 데이터를 수집하는 크롤러 개발 및 통합 DB 구축  
- 메뉴 엔지니어링 알고리즘으로 4분면 메뉴 포지셔닝 분석 및 추천/개선 메뉴 자동 도출  
- 온·오프라인 매출을 통합한 대시보드와 제약조건 기반 근무 스케줄 자동화 시스템 설계  
- Stack: `Python` · `Selenium` · `BeautifulSoup` · `Pandas` · `PuLP`

---

## 💼 Career & Experience

### 🏢 PwC 컨설팅 — 인턴 (2025.11 ~ 2026.01)
- 국내 제조 선도기업 S사 생성형 AI 서비스 고도화 프로젝트  
 - 내부 문서 기반 질의응답 에이전트 성능 자동화 스크립트 개발, 테스트 시간 70% 단축
 - 에이전트 응답 품질 개선을 위한 프롬프트 및 백터데이터베이스 설계

### 🏫 경희대학교 H&T 애널리틱스센터 — 학부연구생 / 인턴 (2023.10 ~ 2024.02)
- 인바운드 관광객 수요예측 베이스 모델 개발  
  - 크롤링 자동화로 데이터베이스 구축  
  - `CatBoost`, `XGBoost`, `LSTM` 등 다양한 모델 빌드 및 튜닝  

### 📊 BACS 비즈니스 애널리틱스 컨설팅 학회 (2023.09 ~ 2024.08)
- 7기 학회원 → 8대 학회장  
- 비즈니스 컨설팅 프레임워크 스터디 및 케이스 발표  
- Python 기반 데이터 마이닝 강의 진행 & 커리큘럼 설계  
- 데이터분석 공모전/카페 컨설팅 등 다수 데이터 분석·컨설팅 프로젝트 리딩

---

## 🏅 Awards

### 2024 서울시 빅데이터캠퍼스 분석 공모전 — 빅데이터혁신융합대학상(2등)
- 공모 주제: 서울시 도시문제 해결을 위한 빅데이터 활용 방안 제시
- 제안 내용: 서울시의 열섬현상 완화를 위한 쿨링로드 우선 설치 입지 분석
- 분석 및 구현 내용:
  - 서울시 기상·도로·교통량·인구 등 공공데이터 기반 쿨링로드 설치 후보지 도출
  - LISA 분석으로 열섬 집중 지역 탐지 및 공간적 상관성 분석  
  - 도시 환경 시나리오별 TOPSIS 다기준 의사결정 알고리즘 적용
- 수상확인: <a href="https://bigdata.seoul.go.kr/noti/selectNoti.do?r_id=P260&bbs_seq=737&ac_type=A1&sch_type=&sch_text=&currentPage=1">link</a>

---

## 📬 Contact

- Email: dlstjd6401@naver.com
- GitHub: https://github.com/iiiiiiiinseong

