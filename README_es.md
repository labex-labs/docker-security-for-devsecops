# Seguridad de Docker para DevSecOps

## Idiomas

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![Seguridad de Docker para DevSecOps](https://course-cover.labex.io/docker-security-for-devsecops.png?lang=es)](https://labex.io/es/courses/docker-security-for-devsecops)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/es/courses/docker-security-for-devsecops)

Un curso práctico de seguridad en Docker para estudiantes de DevSecOps, centrado en auditorías de tiempo de ejecución de contenedores, exposición de puertos, enlaces de depuración, acceso al socket de Docker, montajes de enlace (bind mounts), usuarios no root, modo privilegiado, secretos en tiempo de ejecución, filtración de tokens en tiempo de compilación e higiene de imágenes. Investigarás el estado real de los contenedores, aplicarás correcciones específicas y verificarás que las aplicaciones sigan funcionando correctamente tras el endurecimiento de la seguridad.

![docker](https://img.shields.io/badge/docker-whitesmoke?style=for-the-badge&logo=docker)
![devsecops](https://img.shields.io/badge/devsecops-whitesmoke?style=for-the-badge&logo=devsecops)


## Ejercicios

|   Índice | Nombre                                            | Dificultad   | Práctica                                                                                                                                         |
|----------|---------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | 🎯  Auditoría del Portal de Soporte                | Principiante | <a target='_blank' href='https://labex.io/es/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>Iniciar Desafío</a>          |
|       02 | 🎯  Exposición del endpoint de métricas            | Principiante | <a target='_blank' href='https://labex.io/es/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>Iniciar Desafío</a>     |
|       03 | 🎯  Consola de depuración local                    | Principiante | <a target='_blank' href='https://labex.io/es/labs/local-debug-console-662476?course=docker-security-for-devsecops'>Iniciar Desafío</a>           |
|       04 | 🎯  Webhook Docker Socket                          | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>Iniciar Desafío</a>         |
|       05 | 🎯  Montaje de configuración de solo lectura       | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>Iniciar Desafío</a>        |
|       06 | 🎯  Worker de imágenes sin privilegios de root     | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>Iniciar Desafío</a>         |
|       07 | 🎯  Colector de registros con privilegios mínimos  | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>Iniciar Desafío</a> |
|       08 | 🎯  Token de API en variables de entorno           | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>Iniciar Desafío</a>              |
|       09 | 🎯  Eliminar filtración de token en la compilación | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/build-token-leak-662474?course=docker-security-for-devsecops'>Iniciar Desafío</a>              |
|       10 | 🎯  Imagen de trabajador más segura                | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>Iniciar Desafío</a>            |
|       11 | 🎯  Auditoría de entrega de Compose                | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>Iniciar Desafío</a>         |
|       12 | 🎯  Acceso a base de datos interna                 | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/internal-database-access-662567?course=docker-security-for-devsecops'>Iniciar Desafío</a>      |
|       13 | 🎯  Limpieza del perfil de administrador           | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>Iniciar Desafío</a>         |
|       14 | 🎯  Deriva de configuración (Override Drift)       | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/override-drift-662568?course=docker-security-for-devsecops'>Iniciar Desafío</a>                |
|       15 | 🎯  Límite de Carga Compartida                     | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>Iniciar Desafío</a>        |
|       16 | 🎯  Secreto de Compose con Alcance Limitado        | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>Iniciar Desafío</a>         |
|       17 | 🎯  Segmentación de redes de servicios             | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/split-service-networks-662571?course=docker-security-for-devsecops'>Iniciar Desafío</a>        |
|       18 | 🎯  Aislamiento de Caché                           | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/cache-isolation-662563?course=docker-security-for-devsecops'>Iniciar Desafío</a>               |
|       19 | 🎯  Contrato de Healthcheck                        | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>Iniciar Desafío</a>          |
|       20 | 🎯  Limpieza de depuración tras incidente          | Avanzado     | <a target='_blank' href='https://labex.io/es/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>Iniciar Desafío</a>        |

## Acerca de LabEx

[LabEx](https://labex.io) es una plataforma de aprendizaje interactiva y práctica dedicada a la programación y la tecnología. Combina laboratorios, asistencia de IA y máquinas virtuales para proporcionar una experiencia de aprendizaje práctica sin videos. Con un enfoque estricto de 'Aprender Haciendo', entornos en línea interactivos dentro del navegador con verificaciones paso a paso automatizadas, organización de contenido estructurada con el sistema basado en Árbol de Habilidades, y un recurso de aprendizaje en crecimiento de 30 Árboles de Habilidades y más de 6,000 Laboratorios, LabEx ofrece educación práctica integral. La plataforma incluye al asistente de aprendizaje Labby, construido sobre los últimos modelos de IA, que proporciona una experiencia de aprendizaje conversacional.

## Más

- 🔗 [DevSecOps Cursos de Programación](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [DevSecOps Proyectos de Programación](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [DevSecOps Tutoriales Gratuitos](https://github.com/labex-labs/devsecops-free-tutorials)

