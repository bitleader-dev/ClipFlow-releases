# 개인정보처리방침

**시행일:** 2026년 4월 14일
**최종 수정일:** 2026년 4월 14일

BitLeader inc. (이하 "회사")는 ClipFlow 애플리케이션(이하 "앱")을 운영하고 있습니다. 본 개인정보처리방침은 앱 사용 시 정보가 어떻게 처리되는지 설명합니다.

## 요약

**ClipFlow는 어떠한 개인정보도 수집, 전송 또는 공유하지 않습니다.** 모든 클립보드 데이터는 사용자의 기기에만 저장됩니다.

## 수집하지 않는 정보

- 클립보드 내용을 수집하지 **않습니다**
- 개인정보를 수집하지 **않습니다**
- 사용 분석이나 텔레메트리를 추적하지 **않습니다**
- 쿠키 또는 추적 기술을 사용하지 **않습니다**
- 연락처, 캘린더 또는 기타 개인 데이터에 접근하지 **않습니다**

## 로컬에 저장되는 데이터

ClipFlow는 다음 데이터를 사용자의 기기에 로컬로 저장합니다:

| 데이터 | 위치 | 목적 |
|--------|------|------|
| 클립보드 기록 | `%LocalAppData%\ClipFlow\Clipboard\` | 핵심 기능 |
| 앱 설정 | `%LocalAppData%\ClipFlow\settings.json` | 사용자 환경설정 |
| 클립보드 이미지 | `%LocalAppData%\ClipFlow\Clipboard\images\` | 이미지 클립 저장 |
| 임시 파일 | `%LocalAppData%\ClipFlow\temp\` | 드래그 앤 드롭 작업 |

이 데이터는 사용자의 기기에만 저장되며 어떤 서버로도 전송되지 않습니다.

## 네트워크 통신

ClipFlow는 다음의 네트워크 요청을 수행합니다:

- **업데이트 확인**: 앱 시작 시 GitHub Releases API(`api.github.com`)에 접속하여 새 버전을 확인합니다. 이 요청에는 앱의 사용자 에이전트 문자열("ClipFlow-Updater")만 포함되며 개인정보는 전송되지 않습니다.
- **업데이트 다운로드**: 업데이트가 있을 경우 GitHub에서 업데이트 패키지를 다운로드합니다.

이 외의 네트워크 통신은 발생하지 않습니다.

## 제3자 서비스

- **GitHub** (Microsoft): 업데이트 배포 목적으로만 사용됩니다. [GitHub 개인정보처리방침](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)이 적용됩니다.
- **Microsoft Store** (Store를 통해 설치한 경우): [Microsoft 개인정보처리방침](https://privacy.microsoft.com/ko-kr/privacystatement)이 적용됩니다.

## 데이터 삭제

ClipFlow가 저장한 모든 데이터를 삭제하려면:

1. 애플리케이션을 제거합니다
2. `%LocalAppData%\ClipFlow\` 폴더를 삭제합니다

## 아동 보호

ClipFlow는 13세 미만의 아동으로부터 고의로 어떠한 정보도 수집하지 않습니다.

## 방침 변경

본 개인정보처리방침은 수시로 변경될 수 있습니다. 변경 사항은 이 페이지에 "최종 수정일"을 업데이트하여 게시됩니다.

## 문의

본 개인정보처리방침에 관한 질문이 있으시면 아래로 연락해 주세요:

- GitHub Issues: [https://github.com/bitleader-dev/ClipFlow-releases/issues](https://github.com/bitleader-dev/ClipFlow-releases/issues)

---

&copy; 2026 BitLeader inc. All rights reserved.
