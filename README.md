# DEKU BODY v1.1

黒×蛍光グリーンのスマホ対応筋トレ記録アプリ。重量・回数、セットチェック、履歴、バックアップをブラウザ内で管理します。

## GitHub Pages で公開
1. GitHubで新しい公開リポジトリ `deku-body` を作成。
2. このフォルダ内の `index.html`、`manifest.webmanifest`、`icon.svg`、`sw.js` をリポジトリのルートにアップロード。
3. Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save。
4. 公開URL（通常 `https://ユーザー名.github.io/deku-body/`）をSafariで開く。
5. iPhone Safariの共有メニューから「ホーム画面に追加」。

## 注意
- 記録はブラウザのlocalStorageに保存。端末間同期なし。ブラウザデータを消すと消失するため、定期的にJSONバックアップをエクスポートしてください。
- Service WorkerはHTTPS公開後に動作し、アクセス済みのアプリ画面をオフラインでも表示しやすくします。初回アクセスには通信が必要です。
- 現時点ではChatGPTとの自動連携なし。
