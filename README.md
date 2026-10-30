# 김효주

만든 기능이 실제로 나아졌는지 숫자로 확인하고 넘어갑니다.

<p>
  <img src="assets/badges/python.svg" alt="Python" height="25" />
  <img src="assets/badges/fastapi.svg" alt="FastAPI" height="25" />
  <img src="assets/badges/langgraph.svg" alt="LangGraph" height="25" />
  <img src="assets/badges/spring.svg" alt="Spring Boot" height="25" />
  <img src="assets/badges/postgres.svg" alt="PostgreSQL" height="25" />
  <img src="assets/badges/actions.svg" alt="GitHub Actions" height="25" />
</p>

<br>

## 프로젝트

**[KeepIt](https://github.com/oojoyhh/KeepIt)** — AI 링크 아카이빙

저장한 링크를 AI가 분류하고 요약해 자연어로 찾습니다.  
**5인 팀 프로젝트 · 기획·백엔드 통합·주간 리포트 API·검색 품질 평가 담당**

검색에 LLM 리랭킹을 넣을지 정하려고 문서 **129건**과 질문 **107개**로 비교 환경을 만들었습니다.
정답이 1위로 나온 질문은 **66개에서 88개**로 늘었고, 상위 5건 안에 정답이 있는 질문은 **96개에서 94개**로 줄었습니다.
사용자가 상위 몇 건만 본다는 점을 근거로 적용했고, 빠진 2건은 점수 하한 문제로 기록해 남겼습니다.

`Python` `FastAPI` `Supabase` `pgvector` `RAG`

<br>

**[대타구함](https://github.com/oojoyhh/daetaguham)** — 교대 관리 서비스

대타 요청부터 지원, 승인, 근무표 반영까지 연결합니다.
기획과 DB, API 설계를 맡고 구현은 AI 코딩 도구로 진행한 뒤
E2E와 통합 테스트, GitHub Actions로 검증했습니다.

[데모 보기 ↗](https://oojoyhh.github.io/daetaguham/)

`Java` `Spring Boot` `PostgreSQL` `GitHub Actions`

<br>

**[StudySpot](https://github.com/oojoyhh/spot-agent)** — 스터디카페 입지 추천

같은 상권이라도 함께 비교한 후보에 따라 점수가 달라지면 추천을 믿을 수 없다고 보고,
6개 지표의 기준을 고정해 같은 입력에 같은 결과가 나오게 만들었습니다.

`Python` `Pydantic` `LangChain`

<br>

**[KV-cache 평가 Agent](https://github.com/oojoyhh/skala-KV-cache)** — 기술 평가 보고서 자동화

근거 인용과 참고문헌을 연결하는 PDF 보고서 생성 로직을 구현했습니다.

`Python` `LangGraph` `fpdf2`

<br>

## 경험

**법무법인(유) 율촌 · 지식관리팀 인턴** &nbsp; 2025.01 – 2025.06

매주 약 600건의 자료 대조를 COUNTIFS와 INDEX/MATCH 배열수식으로
자동 판정하게 바꾸고 절차를 문서화했습니다.
주 5일에 걸치던 확인이 2일 흐름으로 줄었습니다.

<br>

## 기록

[SKALA 학습](https://github.com/oojoyhh/skala-log) ·
[알고리즘](https://github.com/oojoyhh/algo-log) ·
[리포트 자동화 봇](https://github.com/oojoyhh/report_bot)
