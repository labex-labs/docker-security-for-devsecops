# 面向 DevSecOps 的 Docker 安全实践

## 支持语言

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![面向 DevSecOps 的 Docker 安全实践](https://course-cover.labex.io/docker-security-for-devsecops.png?lang=zh)](https://labex.io/zh/courses/docker-security-for-devsecops)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/zh/courses/docker-security-for-devsecops)

这是一门专为 DevSecOps 学习者设计的 Docker 安全实战课程。内容涵盖容器运行时审计、端口暴露、调试绑定、Docker 套接字访问、绑定挂载、非 root 用户运行、特权模式、运行时密钥管理、构建时令牌泄露以及镜像合规性等核心主题。你将深入分析真实的容器状态，应用针对性的修复方案，并验证应用程序在加固后的稳定性。

![docker](https://img.shields.io/badge/docker-whitesmoke?style=for-the-badge&logo=docker)
![devsecops](https://img.shields.io/badge/devsecops-whitesmoke?style=for-the-badge&logo=devsecops)


## 练习

|   序号 | 名称                       | 难度   | 练习                                                                                                                                    |
|------|--------------------------|------|---------------------------------------------------------------------------------------------------------------------------------------|
|   01 | 🎯  支持门户审计                | 初级   | <a target='_blank' href='https://labex.io/zh/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>开始挑战</a>          |
|   02 | 🎯  指标端点暴露                | 初级   | <a target='_blank' href='https://labex.io/zh/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>开始挑战</a>     |
|   03 | 🎯  本地调试控制台               | 初级   | <a target='_blank' href='https://labex.io/zh/labs/local-debug-console-662476?course=docker-security-for-devsecops'>开始挑战</a>           |
|   04 | 🎯  Webhook Docker Socket | 中级   | <a target='_blank' href='https://labex.io/zh/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>开始挑战</a>         |
|   05 | 🎯  只读配置挂载                | 中级   | <a target='_blank' href='https://labex.io/zh/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>开始挑战</a>        |
|   06 | 🎯  非 Root 权限镜像工作进程       | 中级   | <a target='_blank' href='https://labex.io/zh/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>开始挑战</a>         |
|   07 | 🎯  最小权限日志收集器             | 中级   | <a target='_blank' href='https://labex.io/zh/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>开始挑战</a> |
|   08 | 🎯  API Token in Env      | 中级   | <a target='_blank' href='https://labex.io/zh/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>开始挑战</a>              |
|   09 | 🎯  构建令牌泄露                | 中级   | <a target='_blank' href='https://labex.io/zh/labs/build-token-leak-662474?course=docker-security-for-devsecops'>开始挑战</a>              |
|   10 | 🎯  构建更安全的 Worker 镜像      | 中级   | <a target='_blank' href='https://labex.io/zh/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>开始挑战</a>            |
|   11 | 🎯  Compose 移交审计          | 中级   | <a target='_blank' href='https://labex.io/zh/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>开始挑战</a>         |
|   12 | 🎯  内部数据库访问               | 中级   | <a target='_blank' href='https://labex.io/zh/labs/internal-database-access-662567?course=docker-security-for-devsecops'>开始挑战</a>      |
|   13 | 🎯  管理配置文件的清理             | 中级   | <a target='_blank' href='https://labex.io/zh/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>开始挑战</a>         |
|   14 | 🎯  覆盖配置漂移                | 中级   | <a target='_blank' href='https://labex.io/zh/labs/override-drift-662568?course=docker-security-for-devsecops'>开始挑战</a>                |
|   15 | 🎯  共享上传边界                | 中级   | <a target='_blank' href='https://labex.io/zh/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>开始挑战</a>        |
|   16 | 🎯  作用域受限的 Compose 密钥     | 中级   | <a target='_blank' href='https://labex.io/zh/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>开始挑战</a>         |
|   17 | 🎯  拆分服务网络                | 中级   | <a target='_blank' href='https://labex.io/zh/labs/split-service-networks-662571?course=docker-security-for-devsecops'>开始挑战</a>        |
|   18 | 🎯  缓存隔离                  | 中级   | <a target='_blank' href='https://labex.io/zh/labs/cache-isolation-662563?course=docker-security-for-devsecops'>开始挑战</a>               |
|   19 | 🎯  健康检查契约                | 中级   | <a target='_blank' href='https://labex.io/zh/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>开始挑战</a>          |
|   20 | 🎯  事故调试清理                | 高级   | <a target='_blank' href='https://labex.io/zh/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>开始挑战</a>        |

## 关于 LabEx

[LabEx](https://labex.io) 是一个专注于编程和技术的交互式动手学习平台。它结合了实验室、AI 辅助和虚拟机，提供无视频的实践学习体验。采用严格的'边学边做'方法，浏览器内的交互式在线环境具有自动化的逐步检查，基于技能树的结构化内容组织系统，以及不断增长的学习资源（包含 30 个技能树和超过 6,000 个实验），[LabEx](https://labex.io) 提供全面的实践教育。该平台包含基于最新 AI 模型构建的学习助手 Labby，提供对话式学习体验。

## 更多

- 🔗 [DevSecOps 编程课程](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [DevSecOps 编程项目](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [DevSecOps 免费教程](https://github.com/labex-labs/devsecops-free-tutorials)

