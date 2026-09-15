<p align="center">
  <img src="./assets/github_banner.JPG" alt="O-SQZ GitHub banner" width="100%" />
</p>

# 김주형 | Security Consultant & Pentester

웹·모바일 애플리케이션과 AI/LLM 서비스의 취약점을 진단합니다.<br>
재현 가능한 근거로 위험을 설명하고, 공개 보안 기준을 실제 서비스에서 판단 가능한 점검 절차로 재구성하며, 반복되는 진단 업무를 도구로 옮기고 있습니다.

[Portfolio](https://o-sqz.github.io/portfolio/) · [Security Blog](https://o-sqz.tistory.com/)

## Focus

- **Application Security** — 웹, Android/iOS, 소스코드 취약점 진단 및 모의해킹
- **AI/LLM Security** — OWASP·KISA 공개 자료 분석, LLM·Agent 서비스 점검 기준 설계
- **Evidence-oriented Reporting** — 재현 절차, 영향 범위, 개선 방향을 근거 중심으로 문서화
- **Security Tooling** — 반복 수집·정리 절차를 실무 보조 도구로 구현

## Selected Work

| Project | Description | Status |
| --- | --- | --- |
| [PenTri](https://github.com/O-SQZ/pentri) | 웹 진단 중 반복되는 정보 수집을 보조하는 Chrome 확장 | [Chrome Web Store](https://chromewebstore.google.com/detail/pentri/johfegfkdkpbckcekhmkkmhilpmlaeem) 공개 |
| Ovenforge | ADB 연결, 프로젝트 관리, 기초 정적 분석을 지원하는 Android 진단 워크벤치 | Private Alpha · 개발 중 |
| [Top10 Mapping Reporter](https://github.com/O-SQZ/Top10-Mapping-Reporter) | 진단 결과를 OWASP Top 10 기준에 매핑해 정리하는 CLI 도구 | Public |
| [OWASP Top 10 2025 Korean Translation](https://github.com/O-SQZ/Top10-ko) | OWASP Top 10 2025 한국어 번역 기여 | Public |

### PenTri

활성 탭을 대상으로 기술 스택, HTTP 응답 헤더, 폼·입력 필드, 쿠키, JavaScript 보안 패턴, source map 후보 등을 수집합니다. 자동 스캔이나 익스플로잇 대신 승인된 진단의 수동 분석을 보조하는 범위로 설계했으며, 실제 진단에서 이중 인코딩·디코딩, source map 접근 확인, 하드코딩된 키 후보와 XSS 필터링 코드 탐색에 활용하고 있습니다.

### Ovenforge

Android 진단에서 반복되는 환경 구성과 증적 수집을 줄이기 위한 개인 프로젝트입니다. 현재 ADB 연결, 프로젝트 관리, APK 획득 및 기초 정적 분석, 증적·판정 후보 관리가 가능한 비공개 알파를 개발하고 있습니다. 업무에서 사용한 회사 소유 기준이나 고객 자료는 저장소에 포함하지 않습니다.

## Public Activity

- OWASP Top 10 2025 공식 한국어 번역에 GitHub 기반으로 참여했습니다.
- OWASP Top 10 for LLM Applications 자료의 한국어 번역과 용어 정리를 진행하고 있습니다.
- 진단 과정에서 배운 내용과 공개 자료 분석 기록을 [블로그](https://o-sqz.tistory.com/)에 정리합니다.

## Tools & Technologies

`Burp Suite` `OWASP ZAP` `Frida` `SonarQube` `ADB` `Python` `JavaScript` `Git`

> 고객사·회사 소유 자료와 비공개 점검 기준은 공개 저장소에 올리지 않습니다. 공개 프로젝트에는 직접 공개할 수 있는 코드와 자료만 포함합니다.
