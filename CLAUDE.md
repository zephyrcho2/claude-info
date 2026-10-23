# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 저장소 성격

코드가 아닌 문서 저장소다. 빌드·린트·테스트 명령은 없다. `claude-info.md` 하나에 사용자가 실제로 쓰는 Claude Code 팁, 설정, 명령어를 누적 정리한다. 원격은 `git@github.com:zephyrcho2/claude-info.git`(`main`)이다.

## claude-info.md 작성 규칙

- 모든 내용은 한국어로 쓴다.
- 새 항목은 새 파일을 만들지 말고 `claude-info.md`의 알맞은 `##` 섹션에 추가한다. 맞는 섹션이 없으면 새 `##` 섹션을 만든다.
- "명령어" 섹션은 명령어마다 `### \`/명령어\`` 제목 아래에 다음 세 항목을 둔다.
  - `- **기능:**` 명령어가 하는 일
  - `- **용도:**` 언제 쓰는지
  - `- **사용법:**` 입력 방법과 옵션
- 명령어는 사용자가 알려 준 순서대로 덧붙인다.
