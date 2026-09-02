안녕하세요, 박민지입니다 👋

12년차 프론트엔드 개발자로, 서비스 구조 설계와 성능 최적화를 주로 다뤄왔습니다. 레거시 아키텍처를 개선하고, 반복 작업을 자동화하는 개발 환경을 직접 설계·구축하는 일에 강점이 있습니다. 최근에는 생성형 AI를 실무 워크플로우와 사이드 프로젝트에 실제로 적용하는 데 집중하고 있습니다.

## 지금 관심 있는 것

- AI 코딩 도구(Claude Code, Cursor)를 개발 워크플로우에 녹여, 반복 작업을 줄이고 설계·코드 품질에 더 집중하는 방식
- LLM 기반 서비스의 프롬프트·응답 구조 설계, 그리고 그 결과를 데이터로 검증하는 일
- AI 도구가 "쓸 수 있다"를 넘어 실제로 팀과 현업에 정착하기까지의 간극을 좁히는 일

## 대표 프로젝트

### 🔮 [Yongshin Halmom](https://github.com/patiencendiligence/yongshinhalmom) — AI 라이프스타일 리포트
생년월일 등 사용자 입력을 구조화해 LLM에 전달하고, 개인화된 라이프스타일 리포트를 생성하는 서비스입니다. 기획, 프론트엔드/백엔드 개발, 프롬프트 설계를 전부 담당했습니다.
비정형적인 사용자 입력으로 인한 응답 품질 편차를 줄이기 위해 프롬프트 구조를 반복적으로 검증·수정했고, FAQ schema와 SEO 최적화를 적용해 실제 검색 유입 데이터로 효과를 측정하고 있습니다.

### 🀄 [냥루미큐브](https://github.com/patiencendiligence/nyang-rummikub) — 실시간 멀티플레이 웹 게임
설치나 회원가입 없이 URL 접속만으로 방을 만들고 바로 플레이할 수 있는 루미큐브입니다.
Socket.IO로 방(room) 단위 이벤트 시스템을 구성해 타일 이동·턴 전환·조합 유효성 검증 결과를 모든 클라이언트에 실시간 동기화했습니다. 번들러는 Vite를 선택해 개발 서버 시작 속도와 HMR 성능을 확보했고, Express와 단일 서버로 묶어 정적 리소스 서빙과 실시간 통신을 함께 처리함으로써 배포·운영 복잡도를 최소화했습니다 (Render 단일 인스턴스 배포).

### 📖 [Buddha-skill](https://github.com/patiencendiligence/buddha-skill) — Claude Code Skill
클로드 코드의 스킬 중 하나로, 부처님의 가르침과 선(禪)의 대화 전통(禪問答, 코안식 질문)에서 영감을 받았습니다. 무엇이든 물어보세요. 하지만 답을 기대하지는 마세요.

선문답 형식의 대화형 Claude Code Skill로, Skill의 트리거 조건과 응답 제약을 직접 설계하며 AI 에이전트 워크플로우를 구축해본 사이드 프로젝트입니다. "정답을 주지 않는 것"이 의도된 동작이라는 점에서, 일반적인 태스크 자동화 스킬과는 다른 제약 조건 설계가 필요했습니다.

## Stack

**실무**: TypeScript · React · Next.js · Vue.js · GraphQL · Storybook · AWS
**사이드 프로젝트**: Socket.IO · Vite · Chrome Extension API

## Experience

10개 이상 조직에서 12년간 프론트엔드 개발자로 일하며, 레거시 아키텍처 개선(번들 사이즈 18.6% 감소), 배포 안정화 체계 구축(핫픽스 발생 80% 감소), 개발 자동화 도구 도입(GraphQL codegen, Storybook 기반 컴포넌트 생성 자동화) 등을 진행했습니다. 회사 프로젝트는 코드 공개가 어려워 이 프로필에는 담지 못했습니다 — 자세한 실무 경험은 이력서로 안내드립니다.

## Contact

[patiencendiligence@gmail.com](mailto:patiencendiligence@gmail.com)
