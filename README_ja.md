# DevSecOpsのためのDockerセキュリティ

## 言語

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![DevSecOpsのためのDockerセキュリティ](https://course-cover.labex.io/docker-security-for-devsecops.png?lang=ja)](https://labex.io/ja/courses/docker-security-for-devsecops)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ja/courses/docker-security-for-devsecops)

DevSecOps学習者向けのハンズオン形式のDockerセキュリティコースです。コンテナのランタイム監査、ポート公開、デバッグ用バインディング、Dockerソケットへのアクセス、バインドマウント、非rootユーザーの利用、特権モード、ランタイムシークレット、ビルド時のトークン漏洩、イメージの健全性管理といったトピックを網羅しています。実際のコンテナ環境を調査し、適切な修正を適用した上で、セキュリティ強化後もアプリケーションが正常に動作することを確認します。

![docker](https://img.shields.io/badge/docker-whitesmoke?style=for-the-badge&logo=docker)
![devsecops](https://img.shields.io/badge/devsecops-whitesmoke?style=for-the-badge&logo=devsecops)


## 演習

|   インデックス | 名前                       | 難易度   | 練習                                                                                                                                        |
|----------|--------------------------|-------|-------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | 🎯  サポートポータルの監査           | 初級    | <a target='_blank' href='https://labex.io/ja/labs/support-portal-audit-662472?course=docker-security-for-devsecops'>チャレンジを開始</a>          |
|       02 | 🎯  メトリクスエンドポイントの公開       | 初級    | <a target='_blank' href='https://labex.io/ja/labs/metrics-endpoint-exposure-662477?course=docker-security-for-devsecops'>チャレンジを開始</a>     |
|       03 | 🎯  ローカルデバッグコンソール         | 初級    | <a target='_blank' href='https://labex.io/ja/labs/local-debug-console-662476?course=docker-security-for-devsecops'>チャレンジを開始</a>           |
|       04 | 🎯  Webhook Docker Socket | 中級    | <a target='_blank' href='https://labex.io/ja/labs/webhook-docker-socket-662481?course=docker-security-for-devsecops'>チャレンジを開始</a>         |
|       05 | 🎯  読み取り専用設定マウント          | 中級    | <a target='_blank' href='https://labex.io/ja/labs/read-only-config-mount-662479?course=docker-security-for-devsecops'>チャレンジを開始</a>        |
|       06 | 🎯  非ルートユーザーによる画像ワーカーの実行  | 中級    | <a target='_blank' href='https://labex.io/ja/labs/non-root-image-worker-662478?course=docker-security-for-devsecops'>チャレンジを開始</a>         |
|       07 | 🎯  最小権限のログコレクター          | 中級    | <a target='_blank' href='https://labex.io/ja/labs/least-privilege-log-collector-662475?course=docker-security-for-devsecops'>チャレンジを開始</a> |
|       08 | 🎯  環境変数内の API トークン       | 中級    | <a target='_blank' href='https://labex.io/ja/labs/api-token-in-env-662473?course=docker-security-for-devsecops'>チャレンジを開始</a>              |
|       09 | 🎯  ビルドトークンの漏洩対策          | 中級    | <a target='_blank' href='https://labex.io/ja/labs/build-token-leak-662474?course=docker-security-for-devsecops'>チャレンジを開始</a>              |
|       10 | 🎯  より安全なワーカーイメージ         | 中級    | <a target='_blank' href='https://labex.io/ja/labs/safer-worker-image-662480?course=docker-security-for-devsecops'>チャレンジを開始</a>            |
|       11 | 🎯  Compose Handoff Audit | 中級    | <a target='_blank' href='https://labex.io/ja/labs/compose-handoff-audit-662564?course=docker-security-for-devsecops'>チャレンジを開始</a>         |
|       12 | 🎯  内部データベースへのアクセス        | 中級    | <a target='_blank' href='https://labex.io/ja/labs/internal-database-access-662567?course=docker-security-for-devsecops'>チャレンジを開始</a>      |
|       13 | 🎯  管理プロファイルのクリーンアップ      | 中級    | <a target='_blank' href='https://labex.io/ja/labs/admin-profile-cleanup-662562?course=docker-security-for-devsecops'>チャレンジを開始</a>         |
|       14 | 🎯  オーバーライドのドリフト          | 中級    | <a target='_blank' href='https://labex.io/ja/labs/override-drift-662568?course=docker-security-for-devsecops'>チャレンジを開始</a>                |
|       15 | 🎯  共有アップロード境界            | 中級    | <a target='_blank' href='https://labex.io/ja/labs/shared-upload-boundary-662570?course=docker-security-for-devsecops'>チャレンジを開始</a>        |
|       16 | 🎯  Compose シークレットのスコープ制限 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/scoped-compose-secret-662569?course=docker-security-for-devsecops'>チャレンジを開始</a>         |
|       17 | 🎯  サービスネットワークの分割         | 中級    | <a target='_blank' href='https://labex.io/ja/labs/split-service-networks-662571?course=docker-security-for-devsecops'>チャレンジを開始</a>        |
|       18 | 🎯  キャッシュの分離              | 中級    | <a target='_blank' href='https://labex.io/ja/labs/cache-isolation-662563?course=docker-security-for-devsecops'>チャレンジを開始</a>               |
|       19 | 🎯  ヘルスチェックのコントラクト        | 中級    | <a target='_blank' href='https://labex.io/ja/labs/healthcheck-contract-662565?course=docker-security-for-devsecops'>チャレンジを開始</a>          |
|       20 | 🎯  インシデントデバッグのクリーンアップ    | 上級    | <a target='_blank' href='https://labex.io/ja/labs/incident-debug-cleanup-662566?course=docker-security-for-devsecops'>チャレンジを開始</a>        |

## LabEx について

[LabEx](https://labex.io) は、コーディングとテクノロジーに特化したインタラクティブな実践学習プラットフォームです。ラボ、AI 支援、仮想マシンを組み合わせて、ビデオなしの実践的な学習体験を提供します。動画なしの独自の実践ラボによる厳格な「実践による学習」アプローチ、ブラウザ内のインタラクティブなオンライン環境で自動化されたステップバイステップのチェック機能、スキルツリーベースのシステムによる構造化されたコンテンツ組織、30 のスキルツリーと 6,000 以上のラボを含む成長し続ける学習リソースにより、[LabEx](https://labex.io) は包括的な実践教育を提供します。プラットフォームには、最新の AI モデルを基盤とした学習アシスタント Labby が含まれており、対話型学習体験を提供します。

## その他

- 🔗 [DevSecOps プログラミングコース](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [DevSecOps プログラミングプロジェクト](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [DevSecOps 無料チュートリアル](https://github.com/labex-labs/devsecops-free-tutorials)

