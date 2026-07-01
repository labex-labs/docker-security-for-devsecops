# Seguridad de Docker para DevSecOps

**Idiomas:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/es/courses/docker-security-for-devsecops">
    <img src="https://course-cover.labex.io/docker-security-for-devsecops.png?lang=es" alt="Seguridad de Docker para DevSecOps">
  </a>
</p>

Un curso práctico de seguridad en Docker para estudiantes de DevSecOps, centrado en auditorías de tiempo de ejecución de contenedores, exposición de puertos, enlaces de depuración, acceso al socket de Docker, montajes de enlace (bind mounts), usuarios no root, modo privilegiado, secretos en tiempo de ejecución, filtración de tokens en tiempo de compilación e higiene de imágenes. Investigarás el estado real de los contenedores, aplicarás correcciones específicas y verificarás que las aplicaciones sigan funcionando correctamente tras el endurecimiento de la seguridad.

[Iniciar curso en LabEx](https://labex.io/es/courses/docker-security-for-devsecops)

## Ejercicios

|   Índice | Nombre                                         | Dificultad   | Práctica                                                                                                                                         |
|----------|------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | Auditoría del Portal de Soporte                | Principiante | <a target='_blank' href='https://labex.io/es/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>Iniciar desafío</a>          |
|       02 | Exposición del endpoint de métricas            | Principiante | <a target='_blank' href='https://labex.io/es/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>Iniciar desafío</a>     |
|       03 | Consola de depuración local                    | Principiante | <a target='_blank' href='https://labex.io/es/labs/local-debug-console-662476?course=docker-security-for-devsecops'>Iniciar desafío</a>           |
|       04 | Webhook Docker Socket                          | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>Iniciar desafío</a>         |
|       05 | Montaje de configuración de solo lectura       | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>Iniciar desafío</a>        |
|       06 | Worker de imágenes sin privilegios de root     | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>Iniciar desafío</a>         |
|       07 | Colector de registros con privilegios mínimos  | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>Iniciar desafío</a> |
|       08 | Token de API en variables de entorno           | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>Iniciar desafío</a>              |
|       09 | Eliminar filtración de token en la compilación | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/build-token-leak-662474?course=docker-security-for-devsecops'>Iniciar desafío</a>              |
|       10 | Imagen de trabajador más segura                | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>Iniciar desafío</a>            |
|       11 | Auditoría de entrega de Compose                | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>Iniciar desafío</a>         |
|       12 | Acceso a base de datos interna                 | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/internal-database-access-662567?course=docker-security-for-devsecops'>Iniciar desafío</a>      |
|       13 | Limpieza del perfil de administrador           | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>Iniciar desafío</a>         |
|       14 | Deriva de configuración (Override Drift)       | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/override-drift-662568?course=docker-security-for-devsecops'>Iniciar desafío</a>                |
|       15 | Límite de Carga Compartida                     | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>Iniciar desafío</a>        |
|       16 | Secreto de Compose con Alcance Limitado        | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>Iniciar desafío</a>         |
|       17 | Segmentación de redes de servicios             | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/split-service-networks-662571?course=docker-security-for-devsecops'>Iniciar desafío</a>        |
|       18 | Aislamiento de Caché                           | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/cache-isolation-662563?course=docker-security-for-devsecops'>Iniciar desafío</a>               |
|       19 | Contrato de Healthcheck                        | Intermedio   | <a target='_blank' href='https://labex.io/es/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>Iniciar desafío</a>          |
|       20 | Limpieza de depuración tras incidente          | Avanzado     | <a target='_blank' href='https://labex.io/es/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>Iniciar desafío</a>        |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

