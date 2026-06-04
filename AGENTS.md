# AGENTS.md

## 作業ルール

- 公開ページの作業前に外側ディレクトリの `MIMI_PLUS_PLAN.md` と `TECHNICAL_SPEC.md` を確認する。
- App Store 審査向けの Support URL / Privacy Policy URL として使う前提で、医療・診断・治療を想起させる表現を避ける。
- `index.html`、`support.html`、`privacy.html`、`mimi-pages.css` の用語とトーンをそろえる。
- 既存デザインの維持を指定された場合は、レイアウト、余白、色、コンポーネント構造を変更しない。
- スマホ表示では横スクロール、ナビ折り返し、長い日本語コピーのはみ出しを確認する。
- canonical、OGP、Twitter Card、robots.txt、sitemap.xml のプレースホルダーが残っていないか確認する。
- お問い合わせフォーム URL など外部 URL のプレースホルダーは、公開前に実 URL へ差し替える。
- zip ファイルはユーザーが明示的に求めた場合だけ作成する。

## 現行方針

- mimi+ は 1 モードの会話補助アプリ。テレビ・音楽・医療用途には寄せない。
- 無料ユーザーは 1 日 20 分まで。Premium は買い切りで時間制限を解除する。
- 音声データや個人情報は保存・収集しない。音声処理は端末内で完結する。
