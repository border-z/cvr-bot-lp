# CVR Bot LP

業界別アポどりコンバージョンボット のランディングページ群。

## ページ一覧

| ファイル | 業種 | URL |
|---|---|---|
| `detective-agency.html` | 探偵事務所 | https://stupendous-praline-2c2747.netlify.app/detective-agency.html |
| `accounting-firm.html` | 会計事務所 | https://stupendous-praline-2c2747.netlify.app/accounting-firm.html |
| `cosmetic-medical.html` | 美容医療 | https://stupendous-praline-2c2747.netlify.app/cosmetic-medical.html |

## ホスティング

**Netlify**（無料プラン）

- サイト名: `stupendous-praline-2c2747`
- ベース URL: https://stupendous-praline-2c2747.netlify.app
- デプロイ: GitHub (`border-z/cvr-bot-lp`) の `main` ブランチへの push で自動デプロイ
- フォーム受信: Netlify Forms（月100件まで無料）→ [Dashboard](https://app.netlify.com) > Forms で確認

## アクセス解析

**Cloudflare Web Analytics**（無料）

- トークン: `530a65597db14673ae20daeeb411bc89`
- ダッシュボード: https://dash.cloudflare.com → Analytics > Web Analytics
- 全3ページ共通トークンで計測

## フォーム仕様

各ページのフォームは Netlify Forms で受信。フォーム名と収集フィールドは以下の通り。

| ページ | `name` | フィールド |
|---|---|---|
| 探偵 | `detective-trial` | office-name, contact-name, email, phone |
| 会計 | `accounting-trial` | office-name, contact-name, email, phone |
| 美容医療 | `beauty-trial` | clinic-name, contact-name, email, phone |

Netlify Dashboard > Forms > Notifications からメール通知を設定可能。
