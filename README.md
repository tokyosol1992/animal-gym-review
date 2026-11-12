# 동물의GYM 동작 검토

모여봐요 동물의GYM 캐릭터를 버전별로 골라 동작을 재생·비교하고, 앱 화면 시안과 버전 보고서를 보는 검토 사이트입니다.

- 주소: https://tokyosol1992.github.io/animal-gym-review/
- 이 저장소는 **빌드 결과만** 담습니다. 원본(모델 제작 과정, 스크립트, 문서)은 비공개 저장소에 있고, 거기서 `python3 scripts/viewer/build-review.py --site`로 만든 `build/site/`를 그대로 올립니다. 이 저장소에서 직접 고치지 않습니다.

## 앞으로 작업하는 곳

앱과 동작검토를 함께 관리하는 개발 원본은 비공개 `tokyosol1992/animal-gym`입니다. 그 저장소의 `apps/review/README.md`에서 설치·빌드·검토·배포를 시작하고 `PROJECT_HISTORY.md`에 기록합니다.

Codex·Claude Code의 개발 환경에는 원본 저장소를 선택합니다. 이 저장소와 기존 공개 주소는 배포용으로 유지하며 모델·공개 버전·기존 이력을 보존합니다. 사이트를 다시 배포할 때는 이 README와 AGENTS.md·CLAUDE.md도 함께 보존합니다.

## 2026-11-12 · 첫 만남·3D 방 항목 게시

동작검토에 `첫 만남·3D 방` 탭을 추가했습니다: https://tokyosol1992.github.io/animal-gym-review/?tab=flow . 실제 Expo 앱의 웹 빌드(`app-preview/`)를 폰 프레임에서 직접 눌러 보는 검토용 항목이며 앱 출시·캐릭터별 동작 승인이 아닙니다. 실제 iOS·Android 기기 성능은 검증하지 않았습니다.

- 소스: 비공개 `animal-gym` PR #45(main `d059b63`), 이 저장소 PR #16(main `3b78f6e`), Pages 실행 성공.
- 기존 공개 25개 버전·모델·이미지·`shared.html`은 바꾸지 않았고 `index.html`·`version.json`·`app-preview/`만 갱신했습니다.
- 다시 게시하거나 이어서 작업할 때는 비공개 원본의 `README.md` 2026-11-12 항목과 `apps/review/README.md`를 읽습니다. 이 저장소에서 직접 고치지 않습니다.

## 2026-11-06 · 개발 원본 이름 변경

개발 원본은 기존 `stretching-app-product`와 동일한 저장소 `animal-gym`으로 이름을 바꿨습니다. 이 공개 저장소 이름과 검토 사이트 주소는 그대로 유지합니다. 변경 이력은 비공개 원본의 `REPOSITORY.md`와 `PROJECT_HISTORY.md`에 보관합니다.
