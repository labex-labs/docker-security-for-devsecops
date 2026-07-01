# DevSecOps를 위한 Docker 보안

**언어:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ko/courses/docker-security-for-devsecops">
    <img src="https://course-cover.labex.io/docker-security-for-devsecops.png?lang=ko" alt="DevSecOps를 위한 Docker 보안">
  </a>
</p>

컨테이너 런타임 감사, 포트 노출, 디버그 바인딩, Docker 소켓 액세스, 바인드 마운트, 비루트(non-root) 사용자, 권한 있는 모드(privileged mode), 런타임 시크릿, 빌드 타임 토큰 유출 및 이미지 위생을 다루는 DevSecOps 학습자를 위한 실습형 Docker 보안 과정입니다. 실제 컨테이너 상태를 조사하고, 타겟팅된 수정 사항을 적용하며, 보안 강화 후에도 애플리케이션이 정상적으로 작동하는지 검증하게 됩니다.

[LabEx에서 코스 시작](https://labex.io/ko/courses/docker-security-for-devsecops)

## 연습

|   인덱스 | 이름                             | 난이도   | 연습                                                                                                                                     |
|-------|--------------------------------|-------|----------------------------------------------------------------------------------------------------------------------------------------|
|    01 | Support Portal Audit           | 초급    | <a target='_blank' href='https://labex.io/ko/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>도전 시작</a>          |
|    02 | Metrics Endpoint Exposure      | 초급    | <a target='_blank' href='https://labex.io/ko/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>도전 시작</a>     |
|    03 | 로컬 디버그 콘솔                      | 초급    | <a target='_blank' href='https://labex.io/ko/labs/local-debug-console-662476?course=docker-security-for-devsecops'>도전 시작</a>           |
|    04 | Webhook Docker 소켓              | 중급    | <a target='_blank' href='https://labex.io/ko/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>도전 시작</a>         |
|    05 | 읽기 전용 설정 마운트                   | 중급    | <a target='_blank' href='https://labex.io/ko/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>도전 시작</a>        |
|    06 | Non-Root Image Worker          | 중급    | <a target='_blank' href='https://labex.io/ko/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>도전 시작</a>         |
|    07 | 최소 권한 로그 수집기                   | 중급    | <a target='_blank' href='https://labex.io/ko/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>도전 시작</a> |
|    08 | 환경 변수의 API 토큰                  | 중급    | <a target='_blank' href='https://labex.io/ko/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>도전 시작</a>              |
|    09 | 빌드 토큰 유출 해결                    | 중급    | <a target='_blank' href='https://labex.io/ko/labs/build-token-leak-662474?course=docker-security-for-devsecops'>도전 시작</a>              |
|    10 | 더 안전한 워커 이미지 만들기               | 중급    | <a target='_blank' href='https://labex.io/ko/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>도전 시작</a>            |
|    11 | Compose Handoff Audit          | 중급    | <a target='_blank' href='https://labex.io/ko/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>도전 시작</a>         |
|    12 | 내부 데이터베이스 액세스                  | 중급    | <a target='_blank' href='https://labex.io/ko/labs/internal-database-access-662567?course=docker-security-for-devsecops'>도전 시작</a>      |
|    13 | 관리자 프로필 정리                     | 중급    | <a target='_blank' href='https://labex.io/ko/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>도전 시작</a>         |
|    14 | 오버라이드 드리프트 (Override Drift) 해결 | 중급    | <a target='_blank' href='https://labex.io/ko/labs/override-drift-662568?course=docker-security-for-devsecops'>도전 시작</a>                |
|    15 | 공유 업로드 경계 설정                   | 중급    | <a target='_blank' href='https://labex.io/ko/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>도전 시작</a>        |
|    16 | Compose 시크릿 범위 제한              | 중급    | <a target='_blank' href='https://labex.io/ko/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>도전 시작</a>         |
|    17 | 서비스 네트워크 분리                    | 중급    | <a target='_blank' href='https://labex.io/ko/labs/split-service-networks-662571?course=docker-security-for-devsecops'>도전 시작</a>        |
|    18 | 캐시 격리                          | 중급    | <a target='_blank' href='https://labex.io/ko/labs/cache-isolation-662563?course=docker-security-for-devsecops'>도전 시작</a>               |
|    19 | Healthcheck Contract           | 중급    | <a target='_blank' href='https://labex.io/ko/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>도전 시작</a>          |
|    20 | 인시던트 디버그 정리                    | 고급    | <a target='_blank' href='https://labex.io/ko/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>도전 시작</a>        |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

