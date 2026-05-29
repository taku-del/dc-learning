# dc-learning

クラウドストレージ製品向けのインタラクティブ学習コンテンツ集。  
Salesforce Experience Cloud 上で GitHub Pages 経由で配信。

## コンテンツ一覧

| ファイル | 内容 | 行数 |
|---|---|---:|
| `index.html` | トップページ（コンテンツ一覧・業種別フィルタ） | 658 |
| `index-industry-test.html` | トップページ（業種フィルタテスト版） | 659 |
| `initial-setup.html` | 初期設定ガイド | 1,667 |
| `file-sharing.html` | ファイル共有方法の選び方 | 1,365 |
| `security-check.html` | セキュリティ設定チェック | 1,544 |
| `guest-permissions.html` | ゲスト招待 権限設定ガイド | 1,442 |
| `supply-chain-check.html` | セキュリティ対策評価制度 対応度チェック | 1,714 |
| `browser-guide.html` | ドライブ→ブラウザ併用ガイド | 2,468 |
| `link-to-guest.html` | リンク→ゲスト移行ガイド | 2,272 |
| `industry-guide.html` | 業種別活用ガイド | 1,997 |
| `company-rollout.html` | 全社展開ガイド | 1,640 |
| `file-server-migration.html` | ファイルサーバー移行ガイド | 1,640 |
| `shield-security.html` | SHIELD セキュリティガイド | 1,642 |
| `storage-tiering.html` | ストレージ階層化ガイド | 1,728 |
| `drive-troubleshooting.html` | ドライブ トラブル解決ガイド | 1,520 |

**合計: 15ファイル / 約24,000行**

## 技術スタック

- HTML / CSS / JavaScript（各ファイル単体で完結）
- GitHub Pages でホスティング
- Salesforce Experience Cloud の Visualforce ページ経由で iframe 配信

## セットアップ

1. `COLLECT_ENDPOINT` 変数に Power Automate の HTTP トリガー URL を設定（回答収集用）
2. GitHub Pages を有効化（Settings → Pages → main branch）
3. Experience Cloud の Visualforce ページから iframe で参照
