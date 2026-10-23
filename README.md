<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:667EEA,100:764BA2&height=200&section=header&text=Minsik%20Kim&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Frontend%20%C2%B7%20AI%20Developer&descAlignY=58&descSize=18" width="100%" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&weight=600&size=20&duration=3000&pause=1000&color=667EEA&center=true&vCenter=true&width=520&lines=%EC%82%AC%EC%9A%A9%EC%9E%90+%EA%B2%BD%ED%97%98%EC%97%90%EC%84%9C+%EC%B6%9C%EB%B0%9C%ED%95%B4+%EB%81%9D%EA%B9%8C%EC%A7%80+%EB%A7%8C%EB%93%AD%EB%8B%88%EB%8B%A4;%EB%B3%91%EB%AA%A9%EC%9D%80+%EC%B8%A1%EC%A0%95%ED%95%98%EA%B3%A0%2C+%EC%88%AB%EC%9E%90%EB%A1%9C+%EC%A4%84%EC%9E%85%EB%8B%88%EB%8B%A4;Web+%C2%B7+App+%C2%B7+AI" alt="Typing SVG" />

<br/>

[![Gmail](https://img.shields.io/badge/msk990719@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:msk990719@gmail.com)
[![GitHub](https://img.shields.io/badge/broBbang2-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/broBbang2)

</div>

<br/>

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

## 👋 About Me

안녕하세요, 프론트엔드 개발자 **김민식**입니다.
"이 서비스를 왜 쓰는가"를 먼저 묻고, 기능을 만들 때도 사용자 흐름과 숫자를 함께 봅니다.

- 🖥 웹(Next.js)·앱(React Native)·키오스크까지 **사용자가 닿는 모든 화면**을 만들어 봤습니다
- 📏 느낌이 아니라 **실측으로 병목을 찾고**, 개선 결과를 숫자로 남깁니다
- 🤖 AI를 데모가 아닌 **실제 서비스 흐름 안에** 녹이고, 모델 위에 얹는 **제품 로직**을 직접 설계합니다

<br/>

## 📊 Highlights

<div align="center">

| ⏱ AI 프리뷰 대기 | 🔍 태그 필터 응답 | ⚫ 바둑 급수 추정 | 🎞 키오스크 버벅임 |
| :---: | :---: | :---: | :---: |
| **209s → 97s** | **2,007ms → 262ms** | **20수 만에 89%** | **missed vsync 20 → 8** |
| 54% 단축 | 87% 단축 | ±1급 이내 적중 | janky 13.8% → 10.5% |

</div>

<br/>

## 🤖 AI Projects

<table>
<tr>
<td width="100%">

### ⚫ [Let's learn Go](https://github.com/broBbang2/Let-s-learn-Go) — 나와 같이 성장하는 적응형 바둑 AI
> 너무 강해서 재미없는 바둑 AI 대신, 내 실력을 **수 단위로 추정**하고 그 급수 사람이 둘 법한 **사람 같은 실수**를 하는 상대

- KataGo를 두뇌로 쓰고, 그 위에 **사용자 모델 + 난이도 조절** 두 층을 직접 설계
- 매 수마다 베이즈 갱신으로 20급~9단 급수 추정 — **20수 만에 89%가 ±1급 이내**
- 난이도 v1 → v2 → v3 개선: 손실 크기만 맞추던 v2(사람 top-3 일치 **9~30%**)를 human 모델 기반 v3로 바꿔 **70~78%**
- 판 결과로 보정 계수를 갱신해 사용자 승률 **45%** 근처로 수렴하도록 설계
- 측정 지표가 급수 순서를 뒤집던 문제를 추적해 접전 국면 기준으로 재정의, 리그전 판당 **90초 → 59초**
- 표준 라이브러리만으로 서버·프론트 구현, 가짜 KataGo로 엔진 없이 도는 **테스트 98개**

`Python` `KataGo` `Bayesian Inference` `Glicko-2` `SVG`

</td>
</tr>
</table>

<details open>
<summary><b>📷 <a href="https://github.com/broBbang2/MSCV">MSCV</a></b> — 아이폰 실시간 사물 인식 · <code>YOLO</code> <code>SAM</code> <code>CoreML</code> · 🚧 진행 중</summary>
<br/>

- 데이터 0장에서 시작해 수집 → 라벨링 → 학습 → 개선 → 온디바이스 배포까지 객체 탐지 파이프라인 전체를 직접 구축
- 정확도(mAP)와 속도(FPS)를 매 단계 함께 측정, SAM 텍스트 프롬프트 자동 라벨링과 액티브 러닝까지 계획

</details>

<details>
<summary><b>🎨 <a href="https://github.com/broBbang2/Personal-Color">Personal-Color</a></b> — 퍼스널 컬러 분류 모델</summary>
<br/>

- AI·빅데이터 공부를 시작하며 만든 첫 분류 모델 프로젝트

</details>

<br/>

## 🚀 Service Projects

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

## 🍶 Personal Project

<table>
<tr>
<td width="100%">

### 🍶 [Choice](https://github.com/broBbang2/give-me-recommend) — AI 취향 맞춤 주류 추천
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

**AI · ML**<br/>
<img src="https://skillicons.dev/icons?i=python,pytorch,opencv&theme=dark" />

**Test · Tools**<br/>
<img src="https://skillicons.dev/icons?i=vitest,figma&theme=dark" />

<sub>+ React Native · Zustand · TanStack Query · Hono · Playwright · Remotion · Storybook<br/>+ KataGo · YOLO · SAM · CoreML · OpenAI API</sub>

</div>

<br/>

## 🎯 Now

- 📷 MSCV — 직접 모은 데이터로 YOLO 파인튜닝하고 아이폰 온디바이스로 올리기
- 🧪 테스트로 안정성을 담보하는 개발 습관 만들기
- 🎨 UI/UX를 공부하며 디자이너와 같은 언어로 이야기하기

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:764BA2,100:667EEA&height=100&section=footer" width="100%" />
