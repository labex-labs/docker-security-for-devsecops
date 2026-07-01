# Segurança Docker para DevSecOps

**Idiomas:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/pt/courses/docker-security-for-devsecops">
    <img src="https://course-cover.labex.io/docker-security-for-devsecops.png?lang=pt" alt="Segurança Docker para DevSecOps">
  </a>
</p>

Um curso prático de segurança Docker para estudantes de DevSecOps, focado em auditorias de tempo de execução de containers, exposição de portas, bindings de depuração, acesso ao socket do Docker, bind mounts, usuários não root, modo privilegiado, segredos em tempo de execução, vazamento de tokens em tempo de build e higiene de imagens. Você investigará o estado real dos containers, aplicará correções direcionadas e verificará se as aplicações continuam funcionando após o endurecimento (hardening).

[Iniciar curso no LabEx](https://labex.io/pt/courses/docker-security-for-devsecops)

## Exercícios

|   Índice | Nome                                     | Dificuldade   | Prática                                                                                                                                          |
|----------|------------------------------------------|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | Auditoria do Portal de Suporte           | Iniciante     | <a target='_blank' href='https://labex.io/pt/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>Iniciar Desafio</a>          |
|       02 | Exposição de Endpoint de Métricas        | Iniciante     | <a target='_blank' href='https://labex.io/pt/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>Iniciar Desafio</a>     |
|       03 | Console de Depuração Local               | Iniciante     | <a target='_blank' href='https://labex.io/pt/labs/local-debug-console-662476?course=docker-security-for-devsecops'>Iniciar Desafio</a>           |
|       04 | Webhook Docker Socket                    | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>Iniciar Desafio</a>         |
|       05 | Montagem de Configuração Somente Leitura | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>Iniciar Desafio</a>        |
|       06 | Worker de Imagem Não-Root                | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>Iniciar Desafio</a>         |
|       07 | Coletor de Logs com Privilégio Mínimo    | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>Iniciar Desafio</a> |
|       08 | Token de API em Variáveis de Ambiente    | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>Iniciar Desafio</a>              |
|       09 | Build Token Leak                         | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/build-token-leak-662474?course=docker-security-for-devsecops'>Iniciar Desafio</a>              |
|       10 | Imagem de Worker Mais Segura             | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>Iniciar Desafio</a>            |
|       11 | Auditoria de Transferência do Compose    | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>Iniciar Desafio</a>         |
|       12 | Acesso Interno ao Banco de Dados         | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/internal-database-access-662567?course=docker-security-for-devsecops'>Iniciar Desafio</a>      |
|       13 | Limpeza de Perfil de Administrador       | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>Iniciar Desafio</a>         |
|       14 | Override Drift                           | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/override-drift-662568?course=docker-security-for-devsecops'>Iniciar Desafio</a>                |
|       15 | Limite de Upload Compartilhado           | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>Iniciar Desafio</a>        |
|       16 | Segredo de Compose com Escopo Definido   | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>Iniciar Desafio</a>         |
|       17 | Dividir Redes de Serviço                 | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/split-service-networks-662571?course=docker-security-for-devsecops'>Iniciar Desafio</a>        |
|       18 | Isolamento de Cache                      | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/cache-isolation-662563?course=docker-security-for-devsecops'>Iniciar Desafio</a>               |
|       19 | Contrato de Healthcheck                  | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>Iniciar Desafio</a>          |
|       20 | Limpeza de Depuração de Incidente        | Avançado      | <a target='_blank' href='https://labex.io/pt/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>Iniciar Desafio</a>        |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

