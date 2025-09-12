# Copilot Instructions for shooting

## プロジェクト概要
- このリポジトリは、シンプルなシューティングゲームのWeb実装と、JavaScript学習用のドキュメントを含みます。
- 主要なディレクトリは `game/`（ゲーム本体）と `docs/`（学習用資料）です。

## ディレクトリ構成
- `game/` : シューティングゲームのHTML（`index.html`）と、今後追加されるJS/CSSファイルを格納。
- `docs/` : JavaScriptの基礎やルールを解説するHTML（`index.html`）とスタイル（`style.css`）。

## 開発・デバッグ方法
- ゲームは `game/index.html` をブラウザで直接開いて動作確認します。
- ドキュメントは `docs/index.html` をブラウザで表示。
- JavaScriptの実行・デバッグは、ブラウザの開発者ツール（F12 → Console）を利用。

## コーディング規約・パターン
- HTMLは日本語（lang="ja"）で記述。
- JavaScriptの変数宣言は `let`/`const` を推奨（`var`は非推奨）。
- 文字列はダブルクォーテーション（"）で囲む。
- CSSは `docs/style.css` を参照。

## 重要ファイル例
- `game/index.html` : ゲームのエントリーポイント。`<canvas id="gameCanvas">` を利用。
- `docs/index.html` : JavaScript学習用のサンプルコード・説明あり。
- `docs/style.css` : ドキュメントページのスタイル定義。

## 今後の拡張ポイント
- `game/` ディレクトリに `main.js` などのゲームロジックファイルを追加予定。
- ゲームのロジックは `canvas` API を利用して描画・操作。

## 注意事項
- 外部ライブラリやビルドツールは現状未使用。すべて静的ファイルで構成。
- ディレクトリやファイルの命名はシンプルかつ明確に。

---

このリポジトリのAIエージェントは、上記の構成・ルールに従い、
新規ファイル追加や既存ファイルの編集を行ってください。
