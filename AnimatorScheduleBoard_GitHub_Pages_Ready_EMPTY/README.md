# Animator Schedule Board

제작 - みやそ

## GitHub Pages 업로드용 빈 데이터 버전

이 패키지는 공개 업로드용으로 초기화된 버전입니다.

- 샘플 작품명 `カグラバチ` 제거
- 샘플 컷 번호 제거
- 샘플 TIME / 尺 제거
- 기본 JSON을 빈 프로젝트 / 빈 화수 / 빈 CUT 10줄로 초기화
- 민감한 작업 데이터 JSON은 포함하지 않음

## 업로드 방법

1. 이 ZIP을 압축 해제합니다.
2. `index.html`, `README.md`, `animator_schedule_default.json`을 GitHub 저장소에 업로드합니다.
3. GitHub 저장소의 Settings → Pages에서 `main` 브랜치 `/root`를 선택합니다.
4. 생성된 GitHub Pages 링크로 접속하면 됩니다.

## 데이터 저장 안내

앱에서 입력한 데이터는 각 사용자의 브라우저 localStorage에 저장됩니다.
같은 링크에 접속해도 다른 사람의 데이터와 자동 연동되지 않습니다.
데이터 이동은 JSON 내보내기 / 가져오기로 수동 처리합니다.
