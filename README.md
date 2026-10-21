<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:667EEA,100:764BA2&height=200&section=header&text=Minsik%20Kim&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Frontend%20Developer%20%C2%B7%20Product%20Builder&descAlignY=58&descSize=18" width="100%" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&weight=600&size=20&duration=3000&pause=1000&color=667EEA&center=true&vCenter=true&width=520&lines=%EC%82%AC%EC%9A%A9%EC%9E%90+%EA%B2%BD%ED%97%98%EC%97%90%EC%84%9C+%EC%B6%9C%EB%B0%9C%ED%95%B4+%EB%81%9D%EA%B9%8C%EC%A7%80+%EB%A7%8C%EB%93%AD%EB%8B%88%EB%8B%A4;%EB%B3%91%EB%AA%A9%EC%9D%80+%EC%B8%A1%EC%A0%95%ED%95%98%EA%B3%A0%2C+%EC%88%AB%EC%9E%90%EB%A1%9C+%EC%A4%84%EC%9E%85%EB%8B%88%EB%8B%A4;Web+%C2%B7+App+%C2%B7+Kiosk+%C2%B7+AI+Pipeline" alt="Typing SVG" />

<br/>

[![Gmail](https://img.shields.io/badge/msk990719@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:msk990719@gmail.com)
[![GitHub](https://img.shields.io/badge/broBbang2-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/broBbang2)

</div>

<br/>

## 👋 About Me

안녕하세요, 프론트엔드 개발자 **김민식**입니다.

경영학을 전공하면서 AI·빅데이터를 부전공으로 공부했고, 데이터를 다루다 보니 결국 **사람이 직접 만지는 화면**을 만드는 일에 끌려 개발자가 되었습니다.
"이 서비스를 왜 쓰는가"를 먼저 묻는 경영학 습관 덕분에, 기능을 만들 때도 사용자 흐름과 숫자를 함께 봅니다.

스타트업 **데브언리밋**에서 Product Builder로 일하며 하나의 팀에서 웹·앱·키오스크·AI 파이프라인을 모두 맡았고,
기획부터 배포, 실기기 테스트까지 혼자 끝까지 책임지는 방식으로 일해 왔습니다.

- 🖥 웹(Next.js)·앱(React Native)·키오스크까지 **사용자가 닿는 모든 화면**을 만들어 봤습니다
- 📏 느낌이 아니라 **실측으로 병목을 찾고**, 개선 결과를 숫자로 남깁니다
- 🤖 AI 기능을 데모가 아닌 **실제 서비스 흐름 안에** 녹이는 데 관심이 많습니다

<table>
<tr>
<td>🎓 <b>Education</b></td>
<td>우송대학교 경영학 전공 · AI·빅데이터 부전공 <sub>(2018.03 – 2025.08)</sub></td>
</tr>
<tr>
<td>💼 <b>Career</b></td>
<td>(주)데브언리밋 Product Builder <sub>(2026.07 – 2026.10)</sub></td>
</tr>
<tr>
<td>📍 <b>Interest</b></td>
<td>UI/UX · 프론트엔드 성능 · AI 서비스</td>
</tr>
</table>

<br/>

## 📊 Highlights

<div align="center">

| ⏱ AI 프리뷰 대기 | 🔍 태그 필터 응답 | 📱 모바일 결제 바 | 🎞 키오스크 버벅임 |
| :---: | :---: | :---: | :---: |
| **209s → 97s** | **2,007ms → 262ms** | **294px → 82px** | **missed vsync 20 → 8** |
| 54% 단축 | 87% 단축 | 화면 점유 36% → 10% | janky 13.8% → 10.5% |

</div>

<br/>

## 💼 Experience

### (주)데브언리밋 · Product Builder <sub>`2026.07 – 2026.10`</sub>
K-pop 댄스 플랫폼 **Sparky**와 외주 프로젝트 4건을 웹·앱·키오스크에 걸쳐 개발했습니다.

<details open>
<summary><b>🕺 Sparky</b> — K-pop 글로벌 댄스 앱 · <code>React Native</code></summary>
<br/>

- 퀘스트 보드, 순위 화면, 프로필·성향 카드 등 핵심 리텐션 화면 개발 (16개 언어)
- HERO 배너 순환 노출 로직과 노출·클릭 이벤트 수집 API를 앱·서버 양쪽에서 구현
- 이미지 선택기 연속 탭, 해제된 영상 플레이어 참조 등 크래시 원인 추적 및 수정

</details>

<details open>
<summary><b>🎬 AI 댄스 영상 키오스크</b> — <code>React</code> <code>Android</code> <code>iPad</code></summary>
<br/>

- 생성 조건 36가지를 실측해 병목(해상도)을 찾아 **프리뷰 대기 209초 → 97초**
- 실기기 프로파일링으로 그리드 버벅임 해결 — **janky frame 13.81% → 10.54%**, 카드 영상 **3~5MB → 540KB**
- GA4 이벤트 설계로 의상 탐색 → 프리뷰 → 결제까지 퍼널 측정

</details>

<details>
<summary><b>⚙️ 댄스 영상 자동화 파이프라인</b> — <code>Python</code> <code>CUDA</code></summary>
<br/>

- 곡 목록만 넣으면 수집 → 인원 필터 → 난이도 보정 → 캐릭터 합성 → 4K 업스케일 → 누끼 → Drive 업로드·검증까지 자동 처리
- 렌더링 픽셀 연산을 GPU(CuPy)로 옮기고, 곡별 실패를 격리해 실패한 곡만 재처리

</details>

<details>
<summary><b>💃 댄스 스튜디오 예약·결제 웹</b> — <code>Next.js 16</code> <code>React 19</code> <code>Hono</code> · 커밋 845개, 사실상 단독 개발</summary>
<br/>

- 진행 방식(현장·화상)별 요금 테이블 설계와 결제 흐름, 대표·강사 권한 분리 관리자 페이지
- 모바일 결제 바가 화면 36%를 덮던 문제 수정 — **294px → 82px**
- Vitest + Playwright 기반 QA 자동화

</details>

<details>
<summary><b>🎙 음성 분석 서비스 마이그레이션</b> — <code>React</code> <code>Vite</code> <code>Cloud Run</code></summary>
<br/>

- 레거시 서비스를 React로 이전하며 계산 엔진을 분리, **원본 대조 테스트 211개**로 동일성 검증
- 운영 데이터 이전 실행기 구현 (배치 단위 · 승인 게이트 · 멱등 롤백)

</details>

<br/>

## 🚀 Side Project

<table>
<tr>
<td width="100%">

### 🍶 [Choice](https://github.com/broBbang2/choice) — AI 취향 맞춤 주류 추천
술을 처음 접하는 사회초년생이 대화만으로 자기에게 맞는 술을 찾도록 만든 서비스

- 태그 필터링을 DB 쿼리 + GIN 인덱스로 전환 — **2,007ms → 262ms (87%↓)**
- 순차 API 호출을 `Promise.all`로 병렬화해 초기 로딩 단축
- 방문자 집계 2회 호출을 RPC 단일 트랜잭션으로 묶어 정합성 확보
- Upstash Redis IP rate limiting(시간당 10회)으로 토큰 남용 차단
- GPT 응답의 내부 필드명 노출을 감지해 자연어로 후처리

`Next.js` `TypeScript` `Supabase` `OpenAI API` `Zustand` `Upstash Redis`

</td>
</tr>
</table>

<br/>

## 🛠 Tech Stack

<div align="center">

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind&theme=dark" />

**Backend · Infra**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,python,supabase,firebase,gcp&theme=dark" />

**Test · Tools**<br/>
<img src="https://skillicons.dev/icons?i=vitest,figma&theme=dark" />

<sub>+ React Native · Zustand · TanStack Query · Hono · Playwright · Remotion · Storybook · OpenAI API</sub>

</div>

<br/>

## 🌱 Activity

<div align="center">

<!-- 커밋할수록 동물이 생기고 자라는 GitAnimals 농장 -->
<a href="https://github.com/git-goods/gitanimals">
  <img src="https://render.gitanimals.org/farms/broBbang2" width="600" />
</a>

<br/><br/>

<!-- 잔디를 먹는 뱀 (.github/workflows/snake.yml 필요) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/broBbang2/broBbang2/output/github-snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/broBbang2/broBbang2/output/github-snake.svg" />
</picture>

</div>

<br/>

## 🎯 Now

- 🧭 React Native·Next.js 실무 경험을 바탕으로 다음 팀을 찾고 있어요
- 🧪 테스트로 안정성을 담보하는 개발 습관 만들기
- 🎨 UI/UX를 공부하며 디자이너와 같은 언어로 이야기하기

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:764BA2,100:667EEA&height=100&section=footer" width="100%" />
