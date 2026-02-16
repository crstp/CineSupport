# CineSupport Privacy Policy Site

GitHub Pages で公開するためのシンプルな静的ページです。

## ローカル確認

`index.html` をブラウザで開くと表示できます。

## GitHub Pages デプロイ（最短手順）

1. GitHub リポジトリの `Settings` -> `Pages` を開く
2. `Build and deployment` の `Source` を `GitHub Actions` にする
3. `main` ブランチに push する
4. Actions の `Deploy static site to GitHub Pages` が完了すると公開される

公開URLは通常 `https://<ユーザー名>.github.io/<リポジトリ名>/` です。
マニュアルページは通常 `https://<ユーザー名>.github.io/<リポジトリ名>/manual/` です。

## 変更点

- Tailwind CSS (CDN) で Material 風デザインのプライバシーポリシーページを作成
- `addr.jpg` をサポートメールアドレス画像として表示（`alt` 属性なし）
- GitHub Pages にデプロイする workflow を追加
