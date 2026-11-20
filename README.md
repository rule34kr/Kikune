# Kikune

**동인음성 작품을 정리하고 감상하기 위한 Android 라이브러리 및 오디오 플레이어입니다.**

Kikune은 동인음성, 일본어 ASMR 등의 오디오 작품을 개인 라이브러리로 관리하고 재생하기 위한 Android 앱입니다.

[English README](README_EN.md)

> **개발 상태:** 초기 개발 단계입니다. [AniZen](https://github.com/salmanbappi/AniZen)을 기반으로 동인음성·오디오 중심 앱으로 개조하고 있습니다. 기능과 구조는 개발 과정에서 변경될 수 있습니다.

## 주요 목표

- 로컬 오디오 작품을 개인 라이브러리로 정리
- 하나의 작품에 여러 트랙을 연결해 관리
- 오디오 재생 및 재생 위치 기억
- 백그라운드 재생과 알림·미디어 컨트롤 지원
- 기존 프로젝트의 유용한 라이브러리 관리, 정렬, 테마, 백업 기능 유지 및 활용

## 개발 범위

초기 개발은 **로컬 오디오 파일 관리와 재생**에 집중합니다.

현재 범위에 포함하지 않는 기능:
- DLsite 연동
- 온라인 작품 카탈로그 및 외부 사이트 검색
- 웹 크롤링
- 외부 소스 및 확장 기능

위 기능은 추후 별도로 검토할 예정입니다.

## 기반 프로젝트

Kikune은 Kotlin과 Jetpack Compose 기반의 Android 미디어 앱인 [AniZen](https://github.com/salmanbappi/AniZen)을 기반으로 개발하는 독립 파생 프로젝트입니다.

원본 프로젝트의 저작권 고지와 적용되는 라이선스 조건을 유지합니다. 자세한 내용은 [LICENSE](LICENSE)와 [NOTICE](NOTICE)를 확인하세요.

## 라이선스

Kikune은 Apache License 2.0을 따릅니다. 자세한 내용은 [LICENSE](LICENSE)를 참고하세요.
