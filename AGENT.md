# 중요한 작업 명령과 사용자 지시

저장소 작업을 시작할 때는 `AGENTS.md`의 협업 규칙을 따른다.

## 사용자 지시

- 중요한 지시와 반복해서 쓸 명령은 작업 중 이 파일에 갱신한다.
- 게임 개발 진행 상황은 `프로젝트설명.md`에 기록한다.
- 해야 할 일과 한 일은 `해야할일목록.md`에 기록한다.
- 푸시 전 커밋 제목과 본문을 한국어로 작성하고 변경 내용과 이유를 설명한다.

## Git 작업 명령

- `git remote -v`로 원격 저장소 주소를 확인한다.
- `git status --short --branch`로 현재 브랜치와 변경 파일을 확인한다.
- `git diff`로 작업 중인 변경을 보고, `git diff --cached`로 커밋할 변경을 검토한다.
- `git diff --check`와 `git diff --cached --check`로 공백 오류를 확인한다.
- `git commit -m "<한국어 제목>" -m "<변경 내용과 이유>"`로 커밋한다.
- `git push`로 현재 브랜치의 커밋을 원격 저장소에 올린다.

## PowerShell에서 문서 읽기

- `Get-Content -LiteralPath '프로젝트설명.md' -Raw -Encoding UTF8`로 한국어 기획 문서를 읽는다.
