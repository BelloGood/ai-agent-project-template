# AI Agent Project Template

다른 AI 에이전트와 함께 새 소프트웨어 프로젝트를 시작할 때 사용하는 공개 템플릿입니다.

이 저장소는 제품 목표, 정책, 아키텍처, 디자인, 백로그, 첫 세션 규칙을 문서화하는 기본 형식을 제공합니다.

## 사용 방법

1. 이 저장소를 복사하거나 템플릿으로 사용합니다.
2. `AGENTS.md`에서 `[사용자 입력 필요]` 항목을 실제 프로젝트에 맞게 수정합니다.
3. `docs/PRD.md`에 만들 서비스와 사용자를 설명합니다.
4. `docs/POLICY.md`에 반드시 지킬 원칙과 금지사항을 작성합니다.
5. `docs/ARCHITECTURE.md`에 앱·서버·데이터 흐름을 기록합니다.
6. `docs/BACKLOG.md`에 첫 번째 작업을 등록합니다.
7. AI 에이전트에게 먼저 문서를 읽고 계획을 세우도록 요청합니다.

## 민감한 정보 주의

이 저장소는 공개 저장소입니다. 다음 정보를 절대로 커밋하지 마세요.

- API 키, 비밀번호, 개인 액세스 토큰
- `.env` 파일의 실제 값
- 서비스 계정 JSON 키
- 데이터베이스 원본과 사용자 사진
- 개인정보, 위치정보, 운영 로그
- 배포 서버의 접속 정보

실제 비밀값은 로컬 `.env` 또는 GitHub Actions Secrets에 저장하고, 공개 문서에는 다음처럼 표시합니다.

```text
[사용자 입력 필요]
[비밀값 입력 금지]
[GitHub Secrets에 등록]
```

## 문서 구조

```text
AGENTS.md                 AI 에이전트 작업 규칙
.env.example              환경변수 이름만 기록하는 예시 파일
docs/INDEX.md             문서 안내판
docs/PRD.md               제품 요구사항
docs/ARCHITECTURE.md      시스템 구조와 데이터 흐름
docs/POLICY.md            프로젝트 운영 정책
docs/DESIGN_GUIDE.md      UI·UX 규칙
docs/BACKLOG.md            작업 목록
docs/runbooks/            반복 작업 절차서
```

## 권장 첫 요청

> 이 프로젝트의 `AGENTS.md`와 `docs/INDEX.md`를 먼저 읽어줘. 기존 정책과 충돌하지 않도록 현재 상태를 요약하고, 첫 번째 작업 계획을 만들어줘. 코드를 수정하기 전에 내가 확인할 수 있도록 계획만 보여줘.
