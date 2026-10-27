# vocal-practice (소미쌤 앱 개인 사본)

보컬 연습 웹앱. 원본(somissam.github.io/somi_ssam)에서 분리한 독립 인스턴스.
- Firebase(Firestore)·GitHub 프로젝트 ID: `vocal-practice` — 원본 서버와 데이터가 오가면 안 됨
- 스택: 순수 HTML/JS (빌드 없음)

## 먼저 읽을 문서 (이미 저장소에 있음 — 내용을 여기 중복하지 않음)
1. `HANDOVER.md` 현재 상태 → 2. `WORK_GUIDE.md` 작업 규칙(최우선) → 3. `ROADMAP.md` 할 일
- 완료 이력 `COMPLETED.md`, 등록대장 설계 `등록대장_설계도.md`, 휴식반 테스트 `REST_CLASS_TEST.md`
- 작업에 필요한 문서·파일만 읽을 것 (전부 훑기 금지)

## 핵심 규칙 요약
- WORK_GUIDE의 순서 준수: 설계를 말로 먼저 → 사용자 확인 → 코딩 → 검증 (단, 답이 정해진 px·색·템포 미세조정은 바로 수정)
- 코드 의심 전 `node practice_log_system_check.js`부터 실행. 패턴 관련은 `node vocal_lab_pattern_check.js`
- 수정한 JS는 `node --check`
- 시킨 것 외에 고치지 말 것. 멀쩡한 코드를 문제로 만들지 말 것
- 비밀번호·학생 정보는 코드에 넣지 말 것
- 작업은 브랜치에서 하고, 사용자가 "배포해줘"라고 할 때만 `main`에 반영
- 답변은 결론 먼저, 짧게, 한국어로
