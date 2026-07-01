# Безопасность Docker для DevSecOps

**Языки:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ru/courses/docker-security-for-devsecops">
    <img src="https://course-cover.labex.io/docker-security-for-devsecops.png?lang=ru" alt="Безопасность Docker для DevSecOps">
  </a>
</p>

Практический курс по безопасности Docker для специалистов DevSecOps, посвященный аудиту среды выполнения контейнеров, открытым портам, отладочным привязкам, доступу к Docker socket, bind-монтированию, работе без прав root, привилегированному режиму, секретам среды выполнения, утечкам токенов при сборке и гигиене образов. Вы научитесь анализировать реальное состояние контейнеров, применять целевые исправления и проверять работоспособность приложений после их защиты.

[Начать курс на LabEx](https://labex.io/ru/courses/docker-security-for-devsecops)

## Упражнения

|   Индекс | Название                                              | Сложность   | Практика                                                                                                                                          |
|----------|-------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | Аудит портала поддержки                               | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>Начать испытание</a>          |
|       02 | Раскрытие метрик через эндпоинт                       | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>Начать испытание</a>     |
|       03 | Локальная консоль отладки                             | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/local-debug-console-662476?course=docker-security-for-devsecops'>Начать испытание</a>           |
|       04 | Webhook Docker Socket                                 | Средний     | <a target='_blank' href='https://labex.io/ru/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>Начать испытание</a>         |
|       05 | Монтирование конфигурации в режиме «только для чте... | Средний     | <a target='_blank' href='https://labex.io/ru/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>Начать испытание</a>        |
|       06 | Рабочий процесс обработки изображений без прав roo... | Средний     | <a target='_blank' href='https://labex.io/ru/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>Начать испытание</a>         |
|       07 | Сборщик логов с минимальными привилегиями             | Средний     | <a target='_blank' href='https://labex.io/ru/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>Начать испытание</a> |
|       08 | API-токен в переменных окружения                      | Средний     | <a target='_blank' href='https://labex.io/ru/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>Начать испытание</a>              |
|       09 | Устранение утечки токена при сборке                   | Средний     | <a target='_blank' href='https://labex.io/ru/labs/build-token-leak-662474?course=docker-security-for-devsecops'>Начать испытание</a>              |
|       10 | Безопасный образ рабочего процесса                    | Средний     | <a target='_blank' href='https://labex.io/ru/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>Начать испытание</a>            |
|       11 | Аудит передачи стека Compose                          | Средний     | <a target='_blank' href='https://labex.io/ru/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>Начать испытание</a>         |
|       12 | Доступ к внутренней базе данных                       | Средний     | <a target='_blank' href='https://labex.io/ru/labs/internal-database-access-662567?course=docker-security-for-devsecops'>Начать испытание</a>      |
|       13 | Очистка профиля администратора                        | Средний     | <a target='_blank' href='https://labex.io/ru/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>Начать испытание</a>         |
|       14 | Устранение дрейфа конфигурации (Override Drift)       | Средний     | <a target='_blank' href='https://labex.io/ru/labs/override-drift-662568?course=docker-security-for-devsecops'>Начать испытание</a>                |
|       15 | Граница общих загрузок                                | Средний     | <a target='_blank' href='https://labex.io/ru/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>Начать испытание</a>        |
|       16 | Ограничение секретов в Compose                        | Средний     | <a target='_blank' href='https://labex.io/ru/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>Начать испытание</a>         |
|       17 | Разделение сетей сервисов                             | Средний     | <a target='_blank' href='https://labex.io/ru/labs/split-service-networks-662571?course=docker-security-for-devsecops'>Начать испытание</a>        |
|       18 | Изоляция кэша                                         | Средний     | <a target='_blank' href='https://labex.io/ru/labs/cache-isolation-662563?course=docker-security-for-devsecops'>Начать испытание</a>               |
|       19 | Контракт проверки работоспособности (Healthcheck)     | Средний     | <a target='_blank' href='https://labex.io/ru/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>Начать испытание</a>          |
|       20 | Очистка после отладки инцидента                       | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>Начать испытание</a>        |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

