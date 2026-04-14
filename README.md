# book-proposal2

책 저술 기획을 위한 멀티 에이전트 하네스. 초기 아이디어(한 문장 또는 막연한 주제)를 받아 4라운드 수렴 사이클로 **출판사 제출 가능 수준의 저술 기획안 초안**을 산출한다.

## 구성

- `CLAUDE.md` — 하네스 트리거 규칙과 변경 이력.
- `book-proposal-agent-team-prompt.md` — 7개 전문 에이전트(컨셉/페르소나/시장/구조/리서치/비평/통합) 팀 정의와 산출 포맷.
- `.claude/` — Claude Code 로컬 설정.
- `.omc/` — oh-my-claudecode 설정.

## 사용법

Claude Code에서 "책 기획", "목차 설계", "독자 페르소나", "경쟁 도서 분석" 등의 키워드로 요청하면 `book-proposal-planning` 스킬이 자동 실행된다.

## 에이전트 팀

1. **Concept Strategist** — 로그라인 · 핵심 약속 · USP
2. **Reader Persona Expert** — 1·2차 독자와 독자 여정
3. **Market Analyst** — 경쟁 도서 스캔과 포지셔닝
4. **Structure Architect** — 목차와 챕터별 논지 설계
5. **Content Researcher** — 사례 · 데이터 · 인용 수집
6. **Editorial Critic** — 적대적 검토 (필수 게이트)
7. **Lead Editor** — 최종 기획안 초안 통합
