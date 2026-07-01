<div align="center">

# 안녕하세요, 김민식입니다 👋

코드 한 줄도 중요하지만, 모두 함께 협업해 만들고 싶은 프론트엔드 개발자입니다.
문제를 발견하면 원인을 끝까지 추적하고, 해결 과정을 팀원들과 공유하는 것을 중요하게 생각합니다.

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:msk990719@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/broBbang2)

</div>

---

## 🛠 Tech Stack

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### State & Backend
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

### AI & Tools
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white)

---

## 🚀 Featured Project

### 🍶 Choice — AI 기반 취향 맞춤 주류 추천 서비스
> 술을 처음 접하는 사회초년생이 대화를 통해 자신에게 맞는 술을 찾을 수 있도록 설계한 개인 사이드 프로젝트

#### 주요 기능
- OpenAI API 기반 대화형·설문형 두 가지 방식의 주류 추천 시스템
- 날씨 API 연동으로 당일 날씨에 따라 달라지는 홈 화면 추천
- 추천 결과 자동 저장 및 커뮤니티 피드 공유
- IP 기반 rate limiting으로 API 토큰 남용 방지 (시간당 10회 제한)

#### 문제 해결
- 태그 필터링을 클라이언트에서 전체 데이터를 불러와 처리하던 구조를 DB 쿼리로 전환하고 GIN 인덱스를 추가해 응답 시간 **2,007ms → 262ms (87% 단축)**
- 여러 API를 순서대로 호출하던 구조를 Promise.all로 병렬 전환해 초기 로딩 대기 시간 단축
- 방문자 집계 DB 호출 2회를 RPC 단일 트랜잭션으로 통합해 데이터 정합성 개선
- GPT 응답에 내부 필드명이 노출되는 문제를 감지해 자연스러운 문장으로 후처리하는 로직 추가

#### 기술 스택
`Next.js` `TypeScript` `Tailwind CSS` `Supabase` `OpenAI API` `Zustand` `Upstash Redis`

🔗 [Choice GitHub Repository](https://github.com/broBbang2/choice)

---

## 📈 GitHub Activity

![GitHub followers](https://img.shields.io/github/followers/broBbang2?style=social)
![GitHub User's stars](https://img.shields.io/github/stars/broBbang2?style=social)

---

## 🎯 Current Focus
- Next.js App Router 기반 서비스 개발 및 운영
- 성능 병목 원인 분석과 최적화
- AI 기능을 실제 서비스에 자연스럽게 녹여내는 구현
- 팀과 함께 성장하는 협업 문화 만들기
