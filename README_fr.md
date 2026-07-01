# Sécurité Docker pour le DevSecOps

**Langues:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/fr/courses/docker-security-for-devsecops">
    <img src="https://course-cover.labex.io/docker-security-for-devsecops.png?lang=fr" alt="Sécurité Docker pour le DevSecOps">
  </a>
</p>

Un cours pratique sur la sécurité Docker destiné aux apprenants DevSecOps, axé sur l'audit du runtime des conteneurs, l'exposition des ports, les liaisons de débogage, l'accès au socket Docker, les montages bind, les utilisateurs non-root, le mode privilégié, les secrets au runtime, les fuites de jetons lors de la construction et l'hygiène des images. Vous analyserez l'état réel des conteneurs, appliquerez des correctifs ciblés et vérifierez le bon fonctionnement des applications après leur sécurisation.

[Commencer le cours sur LabEx](https://labex.io/fr/courses/docker-security-for-devsecops)

## Exercices

|   Index | Nom                                              | Difficulté    | Pratique                                                                                                                                           |
|---------|--------------------------------------------------|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
|      01 | Audit du portail de support                      | Débutant      | <a target='_blank' href='https://labex.io/fr/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>Commencer le défi</a>          |
|      02 | Exposition du point de terminaison des métriques | Débutant      | <a target='_blank' href='https://labex.io/fr/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>Commencer le défi</a>     |
|      03 | Console de débogage locale                       | Débutant      | <a target='_blank' href='https://labex.io/fr/labs/local-debug-console-662476?course=docker-security-for-devsecops'>Commencer le défi</a>           |
|      04 | Socket Docker pour Webhook                       | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>Commencer le défi</a>         |
|      05 | Montage de configuration en lecture seule        | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>Commencer le défi</a>        |
|      06 | Worker d'image non-root                          | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>Commencer le défi</a>         |
|      07 | Collecteur de journaux à privilèges restreints   | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>Commencer le défi</a> |
|      08 | Jeton d'API dans les variables d'environnement   | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>Commencer le défi</a>              |
|      09 | Suppression d'un jeton de build                  | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/build-token-leak-662474?course=docker-security-for-devsecops'>Commencer le défi</a>              |
|      10 | Image de worker plus sécurisée                   | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>Commencer le défi</a>            |
|      11 | Audit de transfert Compose                       | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>Commencer le défi</a>         |
|      12 | Accès interne à la base de données               | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/internal-database-access-662567?course=docker-security-for-devsecops'>Commencer le défi</a>      |
|      13 | Nettoyage du profil administrateur               | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>Commencer le défi</a>         |
|      14 | Dérive de configuration (Override Drift)         | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/override-drift-662568?course=docker-security-for-devsecops'>Commencer le défi</a>                |
|      15 | Limite de partage des téléchargements            | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>Commencer le défi</a>        |
|      16 | Secret Compose à portée limitée                  | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>Commencer le défi</a>         |
|      17 | Segmentation des réseaux de services             | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/split-service-networks-662571?course=docker-security-for-devsecops'>Commencer le défi</a>        |
|      18 | Isolation du cache                               | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/cache-isolation-662563?course=docker-security-for-devsecops'>Commencer le défi</a>               |
|      19 | Contrat de santé (Healthcheck)                   | Intermédiaire | <a target='_blank' href='https://labex.io/fr/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>Commencer le défi</a>          |
|      20 | Nettoyage après débogage d'incident              | Avancé        | <a target='_blank' href='https://labex.io/fr/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>Commencer le défi</a>        |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

