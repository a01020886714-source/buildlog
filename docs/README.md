# BuildLog

학습한 내용과 해결한 오류를 기록하는 서비스입니다.

## 문서

- [MVP 초기 논의](./mvp.md)
- [제품 요구사항(PRD)](./PRD.md)
- [기능 동작 설명서(SPEC)](./spec.md)
- [개발 계획(PLAN)](./plan.md)

## 개발 구성

- `frontend/`: React 화면
- `backend/`: Python·FastAPI API 서버
- `database/`: 데이터베이스 관련 파일
- 서비스 데이터베이스: Supabase의 PostgreSQL
- 초기 개발·테스트 데이터베이스: SQLite3

초기에는 Supabase 접속 정보 없이 SQLite3로 구현과 테스트를 진행합니다. 서비스 연결을 위한 환경설정은 분리하고, Supabase 연결 후 주요 기능을 다시 검증합니다. 설치·실행 명령과 환경설정 예시는 Phase 1에서 프로젝트 구성과 함께 작성합니다.
