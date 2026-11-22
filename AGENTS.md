# 저장소 작업 지침

## 프로젝트 개요
- 중학생 2명과 코딩 선생님이 함께 만드는 코딩 교육용 마을 성장 게임이다.
- 원격 저장소: https://github.com/JJDLABCODING/code_village.git
- 기획의 원문은 `프로젝트설명.md`, 정리된 스토리 초안은 `story.md`에서 관리한다.
- 게임은 탑다운 시점이며, 화면 왼쪽은 게임 화면, 오른쪽은 블록 조립 영역으로 구성한다.
- 플레이어는 방향키와 마우스로 주인공을 조작하고, 주민의 행동은 직업별 블록 코딩으로 지정한다.

## 협업 규칙
- 사용자에게 설명할 때는 한국어를 기본으로 사용한다.
- 푸시 전 커밋 제목과 본문을 한국어로 작성하고 변경 내용과 이유를 구체적으로 설명한다.
- 중요한 사용자 지시와 반복해서 쓸 작업 명령이 생기거나 바뀌면, 작업을 마치기 전에 별도 요청 없이 `AGENT.md`에 추가하거나 갱신한다. 비밀 정보와 일회성 실행 로그는 기록하지 않는다.
- 게임 개발 단계나 구현 상태가 달라지면 `프로젝트설명.md`의 게임 개발 진행 상황에 날짜와 변경 내용을 기록한다.
- 할 일이 생기면 `해야할일목록.md`의 해야 할 일에 추가하고, 완료한 일은 한 일로 옮긴다.
- 스토리는 확정된 설정이 아닌 초안이다. 새로운 제안과 확정된 요구사항을 구별한다.
- 학생들이 이해하고 수정할 수 있도록 작고 명확한 단위로 구현하고 설명한다.
- 원본 기획 문서를 임의로 덮어쓰지 않는다. 한국어 문서는 UTF-8로 읽고 저장한다.

## 현재 저장소 상태
- 초기화 시 원격 저장소에 브랜치나 커밋이 없었다.
- 구현 코드, 게임 엔진, 패키지 관리자, 빌드 및 테스트 명령은 아직 정해지지 않았다. 도구나 명령을 추측해서 기록하지 않는다.
- 기술 스택을 도입하면 실제 디렉터리 구조와 설치·실행·검증 명령을 `AGENT.md`에 갱신한다.
- 코드 변경 후에는 해당 변경에 적합한 검증을 수행하고, 실행하지 못한 검증은 명시한다.

## Coding Style & Naming Conventions

Follow the conventions of the chosen language and framework, and use the project's formatter or linter once configured. Prefer descriptive names and small modules that make game behavior and block actions easy for student contributors to understand. Use consistent English identifiers in code; write player-facing Korean text in the project's chosen localization/content files rather than scattering it through logic.

## Testing Guidelines

No test framework or coverage requirement is configured yet. Add tests alongside the first implemented features, name them to identify the behavior under test, and record the command needed to run them here. Verify gameplay changes in the relevant local run workflow once one exists.

## Commit & Pull Request Guidelines

Write detailed commit messages in Korean, as requested in `프로젝트설명.md`. State the change and its purpose; for example: `마을 주민의 농사 블록 동작 추가 — 지정된 구역에서 작물을 재배하도록 구현`. Pull requests should summarize the gameplay or tooling change, include test or manual verification results, link related issues when available, and attach screenshots or a short recording for visible UI/gameplay changes.
