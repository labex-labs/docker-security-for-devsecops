# DevSecOpsのためのDockerセキュリティ

**言語:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ja/courses/docker-security-for-devsecops">
    <img src="https://course-cover.labex.io/docker-security-for-devsecops.png?lang=ja" alt="DevSecOpsのためのDockerセキュリティ">
  </a>
</p>

DevSecOps学習者向けのハンズオン形式のDockerセキュリティコースです。コンテナのランタイム監査、ポート公開、デバッグ用バインディング、Dockerソケットへのアクセス、バインドマウント、非rootユーザーの利用、特権モード、ランタイムシークレット、ビルド時のトークン漏洩、イメージの健全性管理といったトピックを網羅しています。実際のコンテナ環境を調査し、適切な修正を適用した上で、セキュリティ強化後もアプリケーションが正常に動作することを確認します。

[LabEx でコースを開始](https://labex.io/ja/courses/docker-security-for-devsecops)

## 演習

|   インデックス | 名前                    | 難易度   | 練習                                                                                                                                        |
|----------|-----------------------|-------|-------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | サポートポータルの監査           | 初級    | <a target='_blank' href='https://labex.io/ja/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>チャレンジを開始</a>          |
|       02 | メトリクスエンドポイントの公開       | 初級    | <a target='_blank' href='https://labex.io/ja/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>チャレンジを開始</a>     |
|       03 | ローカルデバッグコンソール         | 初級    | <a target='_blank' href='https://labex.io/ja/labs/local-debug-console-662476?course=docker-security-for-devsecops'>チャレンジを開始</a>           |
|       04 | Webhook Docker Socket | 中級    | <a target='_blank' href='https://labex.io/ja/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>チャレンジを開始</a>         |
|       05 | 読み取り専用設定マウント          | 中級    | <a target='_blank' href='https://labex.io/ja/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>チャレンジを開始</a>        |
|       06 | 非ルートユーザーによる画像ワーカーの実行  | 中級    | <a target='_blank' href='https://labex.io/ja/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>チャレンジを開始</a>         |
|       07 | 最小権限のログコレクター          | 中級    | <a target='_blank' href='https://labex.io/ja/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>チャレンジを開始</a> |
|       08 | 環境変数内の API トークン       | 中級    | <a target='_blank' href='https://labex.io/ja/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>チャレンジを開始</a>              |
|       09 | ビルドトークンの漏洩対策          | 中級    | <a target='_blank' href='https://labex.io/ja/labs/build-token-leak-662474?course=docker-security-for-devsecops'>チャレンジを開始</a>              |
|       10 | より安全なワーカーイメージ         | 中級    | <a target='_blank' href='https://labex.io/ja/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>チャレンジを開始</a>            |
|       11 | Compose Handoff Audit | 中級    | <a target='_blank' href='https://labex.io/ja/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>チャレンジを開始</a>         |
|       12 | 内部データベースへのアクセス        | 中級    | <a target='_blank' href='https://labex.io/ja/labs/internal-database-access-662567?course=docker-security-for-devsecops'>チャレンジを開始</a>      |
|       13 | 管理プロファイルのクリーンアップ      | 中級    | <a target='_blank' href='https://labex.io/ja/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>チャレンジを開始</a>         |
|       14 | オーバーライドのドリフト          | 中級    | <a target='_blank' href='https://labex.io/ja/labs/override-drift-662568?course=docker-security-for-devsecops'>チャレンジを開始</a>                |
|       15 | 共有アップロード境界            | 中級    | <a target='_blank' href='https://labex.io/ja/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>チャレンジを開始</a>        |
|       16 | Compose シークレットのスコープ制限 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>チャレンジを開始</a>         |
|       17 | サービスネットワークの分割         | 中級    | <a target='_blank' href='https://labex.io/ja/labs/split-service-networks-662571?course=docker-security-for-devsecops'>チャレンジを開始</a>        |
|       18 | キャッシュの分離              | 中級    | <a target='_blank' href='https://labex.io/ja/labs/cache-isolation-662563?course=docker-security-for-devsecops'>チャレンジを開始</a>               |
|       19 | ヘルスチェックのコントラクト        | 中級    | <a target='_blank' href='https://labex.io/ja/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>チャレンジを開始</a>          |
|       20 | インシデントデバッグのクリーンアップ    | 上級    | <a target='_blank' href='https://labex.io/ja/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>チャレンジを開始</a>        |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

