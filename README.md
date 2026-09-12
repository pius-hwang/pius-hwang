<!-- pius-hwang/pius-hwang/README.md -->

## Pius Hwang

스타트업 프로젝트 리드(PL) 출신 풀스택 프리랜서.
기획부터 배포까지, 기술로 비즈니스를 성장시키는 개발 파트너입니다.
AI 제품(LLM 에이전트 · RAG · 실시간 스트리밍)과 SaaS 웹을 주로 만듭니다.

📍 South Korea · 🌐 [piusdev.com](https://piusdev.com) · 💼 [LinkedIn](https://linkedin.com/in/pius-hwang) · 🔬 [ORCID](https://orcid.org/0009-0008-2011-2604)

---

### 만든 것

| 제품 | 무엇인가 | 스택 |
|---|---|---|
| **[ArchiFit](https://archifit.io)** | 드래그앤드롭으로 시스템 아키텍처를 설계하고 AI 가 소크라테스식으로 채점·피드백하는 학습 SaaS | Next.js 16 · Django 5 · Gemini · PostgreSQL |
| **[Scavhaven](https://scavhaven.com)** | 종말물 방치형 RPG. 결정론적 시뮬레이션 기반 밸런싱 | React 19 · Vite · Zustand · Capacitor |
| **Quik** | URL 단축 + 클릭 분석 + 팀 협업 | Next.js · PostgreSQL · Upstash |
| **Plit** *(개발 중)* | 한국형 1:1 AI 캐릭터 챗 플랫폼. 호감도 · 장기기억 · 케미 스킬 | NestJS 11 · Prisma 7 · pgvector · Gemini |
| **사주팔자** *(개발 중)* | 사주 계산 · 대운 · 오행 분석 웹앱 + Turbo Native 안드로이드 | Rails 8 · Hotwire · Kamal |

각 제품의 설계 결정과 실패 기록은 [piusdev.com](https://piusdev.com) 에 케이스 스터디로 정리해 두었습니다.

### 공개한 것

- **[seavoyage](https://github.com/pius-hwang/seavoyage)** — 해상 최단항로 탐색 Python 패키지. 커스텀 제한구역(GeoJSON) 적용 지원. [PyPI](https://pypi.org/project/seavoyage/)
- **[ai-agent](https://github.com/pius-hwang/ai-agent)** — ruff 정적 분석 + Claude tool-use 루프를 결합한 코드 리뷰 에이전트
- **[SeoulMate](https://github.com/pius-hwang/SeoulMate)** — 외국인 대상 AI 서울 생활 도우미 (Gemini 3 Seoul Hackathon 출품)

### 기록

기술 결정의 근거와 운영에서 깨진 것들을 글로 남깁니다. ([전체 보기](https://piusdev.com/blog))

<!-- BLOG-POST-LIST:START -->
- [Prisma 7 + NestJS 11 + PostgreSQL 18 + pgvector: ORM과 벡터 검색의 실전 통합 전략](https://piusdev.com/blog/plit-prisma7-nestjs11-pgvector)
- [LLM 기반 콘텐츠 생성 파이프라인과 어드민 CMS 아키텍처](https://piusdev.com/blog/plit-admin-cms-ai-generation)
- [AI 파이프라인 실패 시 결제 안전성 설계: 선차감-환불 패턴과 멱등 트랜잭션](https://piusdev.com/blog/plit-billing-safety-idempotency)
- [POST 기반 SSE 스트리밍과 Zustand 스토어 분리로 설계한 실시간 채팅 아키텍처](https://piusdev.com/blog/plit-post-sse-zustand)
- [AI 인터랙티브 스토리의 호감도 시스템 설계: 행동 가이드, 이벤트 분기, 상태 복원](https://piusdev.com/blog/plit-affinity-system)
<!-- BLOG-POST-LIST:END -->

### 일하는 방식

- 기획 → 스키마 → 구현 → 배포 → 모니터링까지 한 사람이 책임집니다
- 인프라를 직접 굴립니다: Docker · Coolify · Cloudflare Tunnel · Traefik · self-hosted GlitchTip
- 문서와 ADR 을 남깁니다. 인수인계 가능한 코드를 전제로 씁니다

### 스택

`TypeScript` `Python` `Next.js` `React` `NestJS` `FastAPI` `Django` `Rails`
`PostgreSQL` `pgvector` `TimescaleDB` `Redis` `Prisma` `SQLAlchemy`
`LangGraph` `Gemini` `Claude API` `Docker` `Vercel` `Render` `Cloudflare`

---

> 아래 기여 그래프의 대부분은 클라이언트 작업과 자체 제품이라 비공개 저장소입니다.
> 코드를 봐야 판단이 서는 상황이면 연락 주세요. NDA 범위 안에서 워크스루를 드립니다.
> 📮 piushwang@piusdev.com
