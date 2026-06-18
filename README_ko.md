# DevSecOps를 위한 Docker 보안

## 언어

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![DevSecOps를 위한 Docker 보안](https://course-cover.labex.io/docker-security-for-devsecops.png?lang=ko)](https://labex.io/ko/courses/docker-security-for-devsecops)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ko/courses/docker-security-for-devsecops)

컨테이너 런타임 감사, 포트 노출, 디버그 바인딩, Docker 소켓 액세스, 바인드 마운트, 비루트(non-root) 사용자, 권한 있는 모드(privileged mode), 런타임 시크릿, 빌드 타임 토큰 유출 및 이미지 위생을 다루는 DevSecOps 학습자를 위한 실습형 Docker 보안 과정입니다. 실제 컨테이너 상태를 조사하고, 타겟팅된 수정 사항을 적용하며, 보안 강화 후에도 애플리케이션이 정상적으로 작동하는지 검증하게 됩니다.

![docker](https://img.shields.io/badge/docker-whitesmoke?style=for-the-badge&logo=docker)
![devsecops](https://img.shields.io/badge/devsecops-whitesmoke?style=for-the-badge&logo=devsecops)


## 연습

|   인덱스 | 이름                                | 난이도   | 연습                                                                                                                                     |
|-------|-----------------------------------|-------|----------------------------------------------------------------------------------------------------------------------------------------|
|    01 | 🎯  Support Portal Audit           | 초급    | <a target='_blank' href='https://labex.io/ko/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>도전 시작</a>          |
|    02 | 🎯  Metrics Endpoint Exposure      | 초급    | <a target='_blank' href='https://labex.io/ko/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>도전 시작</a>     |
|    03 | 🎯  로컬 디버그 콘솔                      | 초급    | <a target='_blank' href='https://labex.io/ko/labs/local-debug-console-662476?course=docker-security-for-devsecops'>도전 시작</a>           |
|    04 | 🎯  Webhook Docker 소켓              | 중급    | <a target='_blank' href='https://labex.io/ko/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>도전 시작</a>         |
|    05 | 🎯  읽기 전용 설정 마운트                   | 중급    | <a target='_blank' href='https://labex.io/ko/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>도전 시작</a>        |
|    06 | 🎯  Non-Root Image Worker          | 중급    | <a target='_blank' href='https://labex.io/ko/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>도전 시작</a>         |
|    07 | 🎯  최소 권한 로그 수집기                   | 중급    | <a target='_blank' href='https://labex.io/ko/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>도전 시작</a> |
|    08 | 🎯  환경 변수의 API 토큰                  | 중급    | <a target='_blank' href='https://labex.io/ko/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>도전 시작</a>              |
|    09 | 🎯  빌드 토큰 유출 해결                    | 중급    | <a target='_blank' href='https://labex.io/ko/labs/build-token-leak-662474?course=docker-security-for-devsecops'>도전 시작</a>              |
|    10 | 🎯  더 안전한 워커 이미지 만들기               | 중급    | <a target='_blank' href='https://labex.io/ko/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>도전 시작</a>            |
|    11 | 🎯  Compose Handoff Audit          | 중급    | <a target='_blank' href='https://labex.io/ko/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>도전 시작</a>         |
|    12 | 🎯  내부 데이터베이스 액세스                  | 중급    | <a target='_blank' href='https://labex.io/ko/labs/internal-database-access-662567?course=docker-security-for-devsecops'>도전 시작</a>      |
|    13 | 🎯  관리자 프로필 정리                     | 중급    | <a target='_blank' href='https://labex.io/ko/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>도전 시작</a>         |
|    14 | 🎯  오버라이드 드리프트 (Override Drift) 해결 | 중급    | <a target='_blank' href='https://labex.io/ko/labs/override-drift-662568?course=docker-security-for-devsecops'>도전 시작</a>                |
|    15 | 🎯  공유 업로드 경계 설정                   | 중급    | <a target='_blank' href='https://labex.io/ko/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>도전 시작</a>        |
|    16 | 🎯  Compose 시크릿 범위 제한              | 중급    | <a target='_blank' href='https://labex.io/ko/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>도전 시작</a>         |
|    17 | 🎯  서비스 네트워크 분리                    | 중급    | <a target='_blank' href='https://labex.io/ko/labs/split-service-networks-662571?course=docker-security-for-devsecops'>도전 시작</a>        |
|    18 | 🎯  캐시 격리                          | 중급    | <a target='_blank' href='https://labex.io/ko/labs/cache-isolation-662563?course=docker-security-for-devsecops'>도전 시작</a>               |
|    19 | 🎯  Healthcheck Contract           | 중급    | <a target='_blank' href='https://labex.io/ko/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>도전 시작</a>          |
|    20 | 🎯  인시던트 디버그 정리                    | 고급    | <a target='_blank' href='https://labex.io/ko/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>도전 시작</a>        |

## LabEx 소개

[LabEx](https://labex.io) 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다. 비디오 없는 독점적인 실습 실험실로 엄격한 '실습을 통한 학습' 접근 방식, 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인, 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성, 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스로, [LabEx](https://labex.io) 는 종합적인 실습 교육을 제공합니다. 플랫폼에는 최신 AI 모델을 기반으로 구축된 학습 도우미 Labby 가 포함되어 대화형 학습 경험을 제공합니다.

## 더 보기

- 🔗 [DevSecOps 프로그래밍 코스](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [DevSecOps 프로그래밍 프로젝트](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [DevSecOps 무료 튜토리얼](https://github.com/labex-labs/devsecops-free-tutorials)

