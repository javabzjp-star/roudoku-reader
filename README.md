> 【現行運用・2026-11-15】正本と完了条件は[Drive正本運用ルール v1.0.0](https://drive.google.com/file/d/1PeAdnvfIF-KYRdlzvpLWSZAQqgPMRBKK/view?usp=drivesdk)、入口は[Driveの00_目次.md](https://drive.google.com/file/d/1foy4xsO0JgCHLI__2LiP599l31DptJP0/view)。保存・受渡し・合言葉・作業完了について本規則を優先する。本文に残るGitHub main正本／push・PR必須／二重保管の旧手順は、その部分を本規則で置き換える。技術仕様・検証・作品条件は引き続き有効。

# 朗読リーダー（roudoku-reader）

EPUB／テキストを、端末内蔵の日本語音声で読み上げる Web リーダー。

- 正本（最新版）：`dist/朗読リーダー_v1.2.0.html`
- `index.html` は GitHub Pages 配信専用の入口で、正本と同一内容。版を上げたら両方を差し替える。
- 公開 URL：https://javabzjp-star.github.io/roudoku-reader/
- 台帳：`javabzjp-star/tool-registry` の TOOLS.md / tools.json に登録。
- v1.2.0：EPUB の表紙画像（cover-image）を読み取り、再生画面の上部に表紙サムネイルを表示するようにした。
- v1.1.0：読み込んだ本と読書位置・設定を端末内に保存し、次回開いたときに自動で復元（再開）できるようにした。本の内容が外部に送信されることはない。
