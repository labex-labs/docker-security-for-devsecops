# Segurança Docker para DevSecOps

## Idiomas

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![Segurança Docker para DevSecOps](https://course-cover.labex.io/docker-security-for-devsecops.png?lang=pt)](https://labex.io/pt/courses/docker-security-for-devsecops)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/pt/courses/docker-security-for-devsecops)

Um curso prático de segurança Docker para estudantes de DevSecOps, focado em auditorias de tempo de execução de containers, exposição de portas, bindings de depuração, acesso ao socket do Docker, bind mounts, usuários não root, modo privilegiado, segredos em tempo de execução, vazamento de tokens em tempo de build e higiene de imagens. Você investigará o estado real dos containers, aplicará correções direcionadas e verificará se as aplicações continuam funcionando após o endurecimento (hardening).

![docker](https://img.shields.io/badge/docker-whitesmoke?style=for-the-badge&logo=docker)
![devsecops](https://img.shields.io/badge/devsecops-whitesmoke?style=for-the-badge&logo=devsecops)


## Exercícios

|   Índice | Nome                                        | Dificuldade   | Prática                                                                                                                                          |
|----------|---------------------------------------------|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | 🎯  Auditoria do Portal de Suporte           | Iniciante     | <a target='_blank' href='https://labex.io/pt/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>Iniciar Desafio</a>          |
|       02 | 🎯  Exposição de Endpoint de Métricas        | Iniciante     | <a target='_blank' href='https://labex.io/pt/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>Iniciar Desafio</a>     |
|       03 | 🎯  Console de Depuração Local               | Iniciante     | <a target='_blank' href='https://labex.io/pt/labs/local-debug-console-662476?course=docker-security-for-devsecops'>Iniciar Desafio</a>           |
|       04 | 🎯  Webhook Docker Socket                    | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>Iniciar Desafio</a>         |
|       05 | 🎯  Montagem de Configuração Somente Leitura | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>Iniciar Desafio</a>        |
|       06 | 🎯  Worker de Imagem Não-Root                | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>Iniciar Desafio</a>         |
|       07 | 🎯  Coletor de Logs com Privilégio Mínimo    | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>Iniciar Desafio</a> |
|       08 | 🎯  Token de API em Variáveis de Ambiente    | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>Iniciar Desafio</a>              |
|       09 | 🎯  Build Token Leak                         | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/build-token-leak-662474?course=docker-security-for-devsecops'>Iniciar Desafio</a>              |
|       10 | 🎯  Imagem de Worker Mais Segura             | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>Iniciar Desafio</a>            |
|       11 | 🎯  Auditoria de Transferência do Compose    | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>Iniciar Desafio</a>         |
|       12 | 🎯  Acesso Interno ao Banco de Dados         | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/internal-database-access-662567?course=docker-security-for-devsecops'>Iniciar Desafio</a>      |
|       13 | 🎯  Limpeza de Perfil de Administrador       | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>Iniciar Desafio</a>         |
|       14 | 🎯  Override Drift                           | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/override-drift-662568?course=docker-security-for-devsecops'>Iniciar Desafio</a>                |
|       15 | 🎯  Limite de Upload Compartilhado           | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>Iniciar Desafio</a>        |
|       16 | 🎯  Segredo de Compose com Escopo Definido   | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>Iniciar Desafio</a>         |
|       17 | 🎯  Dividir Redes de Serviço                 | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/split-service-networks-662571?course=docker-security-for-devsecops'>Iniciar Desafio</a>        |
|       18 | 🎯  Isolamento de Cache                      | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/cache-isolation-662563?course=docker-security-for-devsecops'>Iniciar Desafio</a>               |
|       19 | 🎯  Contrato de Healthcheck                  | Intermediário | <a target='_blank' href='https://labex.io/pt/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>Iniciar Desafio</a>          |
|       20 | 🎯  Limpeza de Depuração de Incidente        | Avançado      | <a target='_blank' href='https://labex.io/pt/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>Iniciar Desafio</a>        |

## Sobre LabEx

[LabEx](https://labex.io) é uma plataforma de aprendizagem interativa e prática dedicada à programação e tecnologia. Combina laboratórios, assistência de IA e máquinas virtuais para fornecer uma experiência de aprendizagem prática sem vídeos. Com uma abordagem rigorosa de 'Aprender Fazendo', ambientes online interativos no navegador com verificações automatizadas passo a passo, organização de conteúdo estruturada com o sistema baseado em Árvore de Habilidades, e um recurso de aprendizagem crescente de 30 Árvores de Habilidades e mais de 6.000 Laboratórios, [LabEx](https://labex.io) oferece educação prática integral. A plataforma inclui o assistente de aprendizagem Labby, construído sobre os últimos modelos de IA, fornecendo uma experiência de aprendizagem conversacional.

## Mais

- 🔗 [DevSecOps Cursos de Programação](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [DevSecOps Projetos de Programação](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [DevSecOps Tutoriais Gratuitos](https://github.com/labex-labs/devsecops-free-tutorials)

