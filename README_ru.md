# Безопасность Docker для DevSecOps

## Языки

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![Безопасность Docker для DevSecOps](https://course-cover.labex.io/docker-security-for-devsecops.png?lang=ru)](https://labex.io/ru/courses/docker-security-for-devsecops)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ru/courses/docker-security-for-devsecops)

Практический курс по безопасности Docker для специалистов DevSecOps, посвященный аудиту среды выполнения контейнеров, открытым портам, отладочным привязкам, доступу к Docker socket, bind-монтированию, работе без прав root, привилегированному режиму, секретам среды выполнения, утечкам токенов при сборке и гигиене образов. Вы научитесь анализировать реальное состояние контейнеров, применять целевые исправления и проверять работоспособность приложений после их защиты.

![docker](https://img.shields.io/badge/docker-whitesmoke?style=for-the-badge&logo=docker)
![devsecops](https://img.shields.io/badge/devsecops-whitesmoke?style=for-the-badge&logo=devsecops)


## Упражнения

|   Индекс | Название                                                 | Сложность   | Практика                                                                                                                                          |
|----------|----------------------------------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | 🎯  Аудит портала поддержки                               | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>Начать Испытание</a>          |
|       02 | 🎯  Раскрытие метрик через эндпоинт                       | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>Начать Испытание</a>     |
|       03 | 🎯  Локальная консоль отладки                             | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/local-debug-console-662476?course=docker-security-for-devsecops'>Начать Испытание</a>           |
|       04 | 🎯  Webhook Docker Socket                                 | Средний     | <a target='_blank' href='https://labex.io/ru/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>Начать Испытание</a>         |
|       05 | 🎯  Монтирование конфигурации в режиме «только для чте... | Средний     | <a target='_blank' href='https://labex.io/ru/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>Начать Испытание</a>        |
|       06 | 🎯  Рабочий процесс обработки изображений без прав roo... | Средний     | <a target='_blank' href='https://labex.io/ru/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>Начать Испытание</a>         |
|       07 | 🎯  Сборщик логов с минимальными привилегиями             | Средний     | <a target='_blank' href='https://labex.io/ru/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>Начать Испытание</a> |
|       08 | 🎯  API-токен в переменных окружения                      | Средний     | <a target='_blank' href='https://labex.io/ru/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>Начать Испытание</a>              |
|       09 | 🎯  Устранение утечки токена при сборке                   | Средний     | <a target='_blank' href='https://labex.io/ru/labs/build-token-leak-662474?course=docker-security-for-devsecops'>Начать Испытание</a>              |
|       10 | 🎯  Безопасный образ рабочего процесса                    | Средний     | <a target='_blank' href='https://labex.io/ru/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>Начать Испытание</a>            |
|       11 | 🎯  Аудит передачи стека Compose                          | Средний     | <a target='_blank' href='https://labex.io/ru/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>Начать Испытание</a>         |
|       12 | 🎯  Доступ к внутренней базе данных                       | Средний     | <a target='_blank' href='https://labex.io/ru/labs/internal-database-access-662567?course=docker-security-for-devsecops'>Начать Испытание</a>      |
|       13 | 🎯  Очистка профиля администратора                        | Средний     | <a target='_blank' href='https://labex.io/ru/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>Начать Испытание</a>         |
|       14 | 🎯  Устранение дрейфа конфигурации (Override Drift)       | Средний     | <a target='_blank' href='https://labex.io/ru/labs/override-drift-662568?course=docker-security-for-devsecops'>Начать Испытание</a>                |
|       15 | 🎯  Граница общих загрузок                                | Средний     | <a target='_blank' href='https://labex.io/ru/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>Начать Испытание</a>        |
|       16 | 🎯  Ограничение секретов в Compose                        | Средний     | <a target='_blank' href='https://labex.io/ru/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>Начать Испытание</a>         |
|       17 | 🎯  Разделение сетей сервисов                             | Средний     | <a target='_blank' href='https://labex.io/ru/labs/split-service-networks-662571?course=docker-security-for-devsecops'>Начать Испытание</a>        |
|       18 | 🎯  Изоляция кэша                                         | Средний     | <a target='_blank' href='https://labex.io/ru/labs/cache-isolation-662563?course=docker-security-for-devsecops'>Начать Испытание</a>               |
|       19 | 🎯  Контракт проверки работоспособности (Healthcheck)     | Средний     | <a target='_blank' href='https://labex.io/ru/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>Начать Испытание</a>          |
|       20 | 🎯  Очистка после отладки инцидента                       | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>Начать Испытание</a>        |

## О LabEx

[LabEx](https://labex.io) - это интерактивная практическая обучающая платформа, посвященная программированию и технологиям. Она объединяет лаборатории, ИИ-помощь и виртуальные машины для обеспечения практического обучения без видео. Со строгим подходом 'Учись делая', интерактивными онлайн-средами в браузере с автоматизированными пошаговыми проверками, структурированной организацией контента с системой на основе Дерева Навыков, и растущим учебным ресурсом из 30 Деревьев Навыков и более 6,000 Лабораторий, [LabEx](https://labex.io) предлагает всестороннее практическое образование. Платформа включает ассистента обучения Labby, построенного на последних моделях ИИ, обеспечивающего разговорный опыт обучения.

## Больше

- 🔗 [DevSecOps Курсы программирования](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [DevSecOps Проекты программирования](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [DevSecOps Бесплатные туториалы](https://github.com/labex-labs/devsecops-free-tutorials)

