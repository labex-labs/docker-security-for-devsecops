# Sécurité Docker pour le DevSecOps

## Langues

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![Sécurité Docker pour le DevSecOps](https://course-cover.labex.io/docker-security-for-devsecops.png?lang=fr)](https://labex.io/fr/courses/docker-security-for-devsecops)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/fr/courses/docker-security-for-devsecops)

Un cours pratique sur la sécurité Docker destiné aux apprenants DevSecOps, axé sur l'audit du runtime des conteneurs, l'exposition des ports, les liaisons de débogage, l'accès au socket Docker, les montages bind, les utilisateurs non-root, le mode privilégié, les secrets au runtime, les fuites de jetons lors de la construction et l'hygiène des images. Vous analyserez l'état réel des conteneurs, appliquerez des correctifs ciblés et vérifierez le bon fonctionnement des applications après leur sécurisation.

![docker](https://img.shields.io/badge/docker-whitesmoke?style=for-the-badge&logo=docker)
![devsecops](https://img.shields.io/badge/devsecops-whitesmoke?style=for-the-badge&logo=devsecops)


## Exercices

|   Index | Nom                                                 | Difficulté    | Pratique                                                                                                                                           |
|---------|-----------------------------------------------------|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
|      01 | 🎯  Audit du portail de support                      | Débutant      | <a target='_blank' href='https://labex.io/fr/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>Commencer le Défi</a>          |
|      02 | 🎯  Exposition du point de terminaison des métriques | Débutant      | <a target='_blank' href='https://labex.io/fr/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>Commencer le Défi</a>     |
|      03 | 🎯  Console de débogage locale                       | Débutant      | <a target='_blank' href='https://labex.io/fr/labs/local-debug-console-662476?course=docker-security-for-devsecops'>Commencer le Défi</a>           |
|      04 | 🎯  Socket Docker pour Webhook                       | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>Commencer le Défi</a>         |
|      05 | 🎯  Montage de configuration en lecture seule        | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>Commencer le Défi</a>        |
|      06 | 🎯  Worker d'image non-root                          | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>Commencer le Défi</a>         |
|      07 | 🎯  Collecteur de journaux à privilèges restreints   | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>Commencer le Défi</a> |
|      08 | 🎯  Jeton d'API dans les variables d'environnement   | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>Commencer le Défi</a>              |
|      09 | 🎯  Suppression d'un jeton de build                  | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/build-token-leak-662474?course=docker-security-for-devsecops'>Commencer le Défi</a>              |
|      10 | 🎯  Image de worker plus sécurisée                   | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>Commencer le Défi</a>            |
|      11 | 🎯  Audit de transfert Compose                       | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>Commencer le Défi</a>         |
|      12 | 🎯  Accès interne à la base de données               | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/internal-database-access-662567?course=docker-security-for-devsecops'>Commencer le Défi</a>      |
|      13 | 🎯  Nettoyage du profil administrateur               | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>Commencer le Défi</a>         |
|      14 | 🎯  Dérive de configuration (Override Drift)         | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/override-drift-662568?course=docker-security-for-devsecops'>Commencer le Défi</a>                |
|      15 | 🎯  Limite de partage des téléchargements            | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>Commencer le Défi</a>        |
|      16 | 🎯  Secret Compose à portée limitée                  | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>Commencer le Défi</a>         |
|      17 | 🎯  Segmentation des réseaux de services             | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/split-service-networks-662571?course=docker-security-for-devsecops'>Commencer le Défi</a>        |
|      18 | 🎯  Isolation du cache                               | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/cache-isolation-662563?course=docker-security-for-devsecops'>Commencer le Défi</a>               |
|      19 | 🎯  Contrat de santé (Healthcheck)                   | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>Commencer le Défi</a>          |
|      20 | 🎯  Nettoyage après débogage d'incident              | Avancé        | <a target='_blank' href='https://labex.io/fr/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>Commencer le Défi</a>        |

## À propos de LabEx

[LabEx](https://labex.io) est une plateforme d'apprentissage interactive et pratique dédiée au codage et à la technologie. Elle combine des laboratoires, une assistance IA et des machines virtuelles pour offrir une expérience d'apprentissage pratique sans vidéo. Avec une approche stricte 'Apprendre en Faisant', des environnements en ligne interactifs dans le navigateur avec des vérifications automatisées étape par étape, une organisation structurée du contenu avec le système basé sur l'Arbre de Compétences, et une ressource d'apprentissage croissante de 30 Arbres de Compétences et plus de 6 000 Laboratoires, [LabEx](https://labex.io) offre une éducation pratique complète. La plateforme comprend l'assistant d'apprentissage Labby, construit sur les derniers modèles d'IA, offrant une expérience d'apprentissage conversationnelle.

## Plus

- 🔗 [DevSecOps Cours de Programmation](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [DevSecOps Projets de Programmation](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [DevSecOps Tutoriels Gratuits](https://github.com/labex-labs/devsecops-free-tutorials)

