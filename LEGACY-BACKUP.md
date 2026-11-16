# 이전 공용 설정 보관

이 브랜치는 예전 Corne+Cornix 공용 동글 설정의 기록과 비상용 파일을 보존합니다. Corne의 기본 main 설정은 변경하지 않습니다.

- `shared-config-legacy.bundle`: 이전 `JinmuGo/zmk-config`의 Git 전체 이력 백업 (마지막 main `0a728f26249520284d0a3e3865beb943491e2b2a`). 복구: `git clone shared-config-legacy.bundle restored-shared-config`.
- `Corne-emergency-kit.zip`: 이전 공용 50-position 설정을 사용하는 Corne 단독 및 복구 펌웨어. zip 내부 안내문과 장치별 파일 이름을 반드시 확인하세요. 설정 초기화 시 페어링 정보가 삭제됩니다.

별도 OLED 모듈에 대한 west 참조는 과거 스냅샷이므로 독립 빌드하려면 해당 모듈이 별도로 필요합니다. 현재 Cornix 화면 소스는 `zmk-config-cornix`에 보관합니다.

- `cornix-dongle-legacy.bundle`: 독립 Cornix 동글 저장소 Git 이력 백업 (`6b5e72c`).
- `dongle-display-legacy.bundle`: 수정한 동글 디스플레이 포크 Git 이력 백업 (`f70bab4` 포함).

Git bundle은 코드와 커밋 이력을 보관하지만 GitHub의 이슈, PR 댓글, Actions 실행 기록은 포함하지 않습니다. 각 번들은 `git clone <파일명> <복원할_디렉터리>`로 열 수 있습니다.
