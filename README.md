# 朗読リーダー（roudoku-reader）

EPUB／テキストを、端末内蔵の日本語音声で読み上げる Web リーダー。

- 正本（最新版）：`dist/朗読リーダー_v1.2.0.html`
- `index.html` は GitHub Pages 配信専用の入口で、正本と同一内容。版を上げたら両方を差し替える。
- 公開 URL：https://javabzjp-star.github.io/roudoku-reader/
- 台帳：`javabzjp-star/tool-registry` の TOOLS.md / tools.json に登録。
- v1.2.0：EPUB の表紙画像（cover-image）を読み取り、再生画面の上部に表紙サムネイルを表示するようにした。
- v1.1.0：読み込んだ本と読書位置・設定を端末内に保存し、次回開いたときに自動で復元（再開）できるようにした。本の内容が外部に送信されることはない。
