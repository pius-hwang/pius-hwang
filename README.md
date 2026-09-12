<!-- pius-hwang/pius-hwang/README.md -->

## Pius Hwang

스타트업 프로젝트 리드(PL) 출신 풀스택 프리랜서.
AI 제품(LLM 에이전트 · RAG · 실시간 스트리밍)과 SaaS 웹을 만듭니다.

📍 South Korea · 🌐 [piusdev.com](https://piusdev.com) · 💼 [LinkedIn](https://linkedin.com/in/pius-hwang) · 🔬 [ORCID](https://orcid.org/0009-0008-2011-2604)

---

### 최근 작업

**[Plit](https://plit.io)** · AI 캐릭터 챗 플랫폼

`NestJS 11` `Prisma 7` `PostgreSQL 18 (pgvector)` `Next.js 16` `Gemini` `Clerk` `Redis`

POST 기반 SSE 스트리밍 채팅, pgvector + RRF 하이브리드 검색 장기기억, AI 파이프라인 실패를 전제로 한 선차감-환불 멱등 결제를 설계하고 구현했습니다. 기획부터 배포·운영까지 단독으로 맡고 있습니다.

**클라이언트 프로젝트** · 웹 서비스 FE · BE · AI 상담 챗봇 *(계약상 비공개)*

`FastAPI` `SQLAlchemy 2 (async)` `Procrastinate` `PostgreSQL (pgvector)` `Next.js` `TanStack Query` `Tailwind` `next-intl`

그래프형 LLM 에이전트(노드 · 툴 · 프롬프트 분리)와 RAG 검색 계층을 맡아 PII 마스킹과 회귀 평가 스위트까지 붙였습니다.
비동기 작업 큐 기반 외부 데이터 수집 파이프라인과 다국어 프론트엔드를 함께 구축했습니다.

### 공개한 것

- **[seavoyage](https://github.com/pius-hwang/seavoyage)** — 해상 최단항로 탐색 Python 패키지. 커스텀 제한구역(GeoJSON) 적용. [PyPI](https://pypi.org/project/seavoyage/)
- **[ai-agent](https://github.com/pius-hwang/ai-agent)** — ruff 정적 분석 + Claude tool-use 루프를 결합한 코드 리뷰 에이전트
- **[vulnrun](https://github.com/pius-hwang/vulnrun)** — 단계별 웹 취약점 연습장. 의도적으로 취약한 앱 8종, 표준 라이브러리만 사용
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

### 스택

**언어** `TypeScript` `Python` `Ruby` `C#` `Kotlin` `Shell`

**프론트엔드** `Next.js` `React` `Svelte` `Vite` `Tailwind` `TanStack Query` `Zustand` `Capacitor`

**백엔드** `NestJS` `FastAPI` `Django` `Rails` `Prisma` `SQLAlchemy` `Procrastinate`

**데이터** `PostgreSQL` `pgvector` `TimescaleDB` `Redis`

**AI** `LangGraph` `Gemini` `Claude API` `OpenAI Embeddings` `RAG` `Langfuse`

**인프라** `Docker` `Vercel` `Render` `Cloudflare` `Coolify` `Traefik` `GitHub Actions` `Sentry / GlitchTip`

---

> 아래 기여 그래프의 대부분은 클라이언트 작업과 자체 제품이라 비공개 저장소입니다.
> 코드를 봐야 판단이 서는 상황이면 연락 주세요. NDA 범위 안에서 워크스루를 드립니다.
> 📮 piushwang@piusdev.com
