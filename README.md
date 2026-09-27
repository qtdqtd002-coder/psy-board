# PSY 작업 보드

PSY 프로젝트(메이플풍 2D 횡스크롤 액션 RPG · Unity 6.3 LTS)의 칸반(기획 → 아트 → 개발 → QA → 완료)과 진행 대시보드.

- 사이트: https://qtdqtd002-coder.github.io/psy-board/
- 데이터: `data/board.json` (페이지는 이 파일만 읽는다)
- 페이지 정본: 비공개 저장소 `project_psy/board/index.html` → `tools/board/board.py publish-page` 로 게시
- 갱신: Claude 는 `project_psy/tools/board/board.py`(gh CLI), 사람은 사이트의 «편집»(이 저장소 Contents 쓰기 권한만 가진 fine-grained 토큰)
- 배포: main 에 커밋이 들어오면 GitHub Actions(`deploy-pages.yml`)가 1분 안에 반영

공개 저장소라 이 파일들은 누구나 볼 수 있다 — 비밀·개인정보·미공개 아트는 넣지 않는다.
