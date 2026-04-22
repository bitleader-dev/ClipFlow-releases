<p align="center">
  <img src="assets/icon-256.png" width="128" alt="ClipMemory Icon" />
</p>

<h1 align="center">ClipMemory</h1>

<p align="center">
  <strong>Windows 11을 위한 모던 클립보드 관리자</strong>
</p>

<p align="center">
  <a href="https://github.com/bitleader-dev/ClipMemory-releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/bitleader-dev/ClipMemory-releases?style=flat-square" alt="Latest Release" />
  </a>
  <a href="https://github.com/bitleader-dev/ClipMemory-releases/releases/latest">
    <img src="https://img.shields.io/github/downloads/bitleader-dev/ClipMemory-releases/total?style=flat-square" alt="Downloads" />
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%2011-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/.NET-9.0-purple?style=flat-square" alt=".NET" />
</p>

<p align="center">
  <a href="README.md">🇺🇸 English</a>
</p>

---

## 소개

ClipMemory는 시스템 트레이에 상주하는 경량 클립보드 관리자입니다. 복사하는 모든 것 — 텍스트, 이미지, 파일 등 — 을 자동으로 저장하고, 클립보드 기록을 즉시 검색하고 재사용할 수 있습니다.

WinUI 3으로 제작되어 Windows 11 네이티브 경험을 제공합니다.

## 주요 기능

- **클립보드 기록** — 텍스트, 이미지, 파일, 리치 콘텐츠 자동 저장
- **스트립 카드 UI** — 빠른 탐색을 위한 비주얼 카드 인터페이스
- **고정 & 즐겨찾기** — 중요한 항목을 항상 접근 가능하게
- **태그 & 검색** — 태그와 전문 검색으로 클립 정리 및 검색
- **드래그 앤 드롭** — 클립을 다른 앱으로 바로 드래그
- **다중 포맷 지원** — 텍스트, RTF, HTML, 이미지, 파일 목록 등
- **OCR** — 이미지에서 텍스트 추출 (Windows OCR 활용)
- **페이스트 스택** — 여러 항목을 큐에 넣고 순서대로 붙여넣기
- **규칙 엔진** — 사용자 정의 규칙으로 자동 태그/자동 고정
- **키보드 단축키** — 빠른 접근을 위한 글로벌 핫키
- **자동 업데이트** — Velopack을 통한 백그라운드 자동 업데이트

## 스크린샷

<!-- TODO: 스크린샷 추가 -->
<!--
<p align="center">
  <img src="assets/screenshot-main.png" width="600" alt="ClipMemory 메인 UI" />
</p>
-->

## 설치 방법

### 설치 프로그램 (권장)

1. [최신 릴리즈](https://github.com/bitleader-dev/ClipMemory-releases/releases/latest)에서 **`ClipMemory-win-Setup.exe`** 다운로드
2. 설치 프로그램 실행 — 관리자 권한 불필요
3. `%LocalAppData%\ClipMemory\`에 설치되며 바탕화면과 시작 메뉴에 바로가기 생성

### 포터블 (Portable)

1. [최신 릴리즈](https://github.com/bitleader-dev/ClipMemory-releases/releases/latest)에서 **`ClipMemory-win-Portable.zip`** 다운로드
2. 원하는 폴더에 압축 해제
3. `ClipMemory.exe` 실행

> **참고:** 포터블 버전은 자동 업데이트를 지원하지 않습니다.

<!--
### Microsoft Store

<a href="https://apps.microsoft.com/store/detail/TODO">
  <img src="https://get.microsoft.com/images/ko-kr%20dark.svg" width="200" alt="Microsoft Store에서 다운로드" />
</a>
-->

## 시스템 요구사항

- Windows 11 22H2 이상 (빌드 22621+)
- x64 프로세서
- 약 150 MB 디스크 공간

## 제거 방법

- **설치 버전**: 설정 > 앱 > 설치된 앱 > ClipMemory > 제거
- **포터블 버전**: 폴더를 삭제하면 됩니다

앱 데이터는 `%LocalAppData%\ClipMemory\`에 저장됩니다. 이 폴더를 삭제하면 모든 설정과 기록이 제거됩니다.

## 지원

버그를 발견하셨거나 기능 요청이 있으시면 [이슈](https://github.com/bitleader-dev/ClipMemory-releases/issues)를 등록해 주세요.

## 법적 고지

- [개인정보처리방침](docs/PRIVACY.ko.md)
- [이용약관](docs/TERMS.ko.md)
- [라이선스](LICENSE)

---

<p align="center">
  &copy; 2026 BitLeader Corp. All rights reserved.
</p>
