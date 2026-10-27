# Classroom Manager 릴리스

강의실 PC 관리 프로그램(강사 콘솔·학생 PC 에이전트)의 **설치 파일 배포용** 저장소입니다. 소스 코드는 비공개 저장소에 있습니다.

- `ClassroomAgent-win-x64.zip` — 학생 PC 에이전트(서비스) + 세션 헬퍼
- `ClassroomConsole-win-x64.zip` — 강사 PC 콘솔
- `manifest.json` / `manifest.json.sig` — 파일 해시 목록과 릴리스 서명. 설치된 프로그램은 서명을 검증한 뒤에만 자동 업데이트합니다.

설치된 콘솔·에이전트는 최신 릴리스를 1시간마다 확인해 스스로 업데이트합니다.
