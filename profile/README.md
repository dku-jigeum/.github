# 🗳️ 지금참여 (JigeumChamyeo)

> **AI 기반 정치 참여 플랫폼** — 국회 의안·청원·입법예고를 한곳에 모아,
> 시민에게 관심사 맞춤 추천과 AI 분석·챗봇을 제공합니다. *내 관심사로, 지금 바로.*

단국대학교 오픈소스 기초 프로젝트입니다. 흩어진 입법 공공데이터를 하나로 통합하고,
AI가 쉬운 말로 요약·분석해 시민이 마감 전에 참여할 수 있도록 돕습니다.

## 📂 레포지토리

| 레포 | 설명 | 스택 |
| --- | --- | --- |
| [**BE**](https://github.com/dku-jigeum/BE) | 백엔드 서버 · 데이터 수집 배치 · AI 에이전트 | Java · Spring Boot · PostgreSQL(pgvector) |
| [**FE**](https://github.com/dku-jigeum/FE) | 사용자 웹 UI · 개인화 피드 · 챗봇 | TypeScript · React · Vite · Tailwind |

## ✨ 주요 기능

- 📥 공공데이터 자동 수집 (Spring Batch · 매일 자정)
- 🎯 pgvector 기반 관심사 맞춤 추천 피드 + 필터버블 해소
- 🤖 자체 구현 ReAct AI 에이전트 (EXAONE 3.5) — 법안 영향 분석 · 챗봇
- ⏰ 마감 임박 알림 (FCM · D-7/3/1)

## 🛠️ 기술 스택

- **Backend** Spring Boot · Java 17 · PostgreSQL + pgvector · Spring Batch
- **Frontend** React · TypeScript · Vite · Tailwind CSS
- **AI** EXAONE 3.5 (로컬 Ollama) · ReAct · RAG
- **협업** GitHub · Jira · Confluence

## 📚 문서

프로젝트 문서(회의록 · 발표 자료 · 기술 문서 · API 명세)는 **Confluence**에서 관리합니다.

👉 **[지금참여 Confluence 스페이스](https://dankook-opensource-project.atlassian.net/wiki/spaces/MFS/overview)**

## 👥 팀

| 이름 | 역할 |
| --- | --- |
| parksehyn (박세현) | 팀장 · Backend · AI |
| 전세린 | Frontend |
| 김정원 | Frontend |
