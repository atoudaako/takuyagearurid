# takuya gear（激エロ たくやGEARウリID ― NOVEL WALKER）

ブラウザで遊べるステルスゲームです。PC・スマホ（横画面）に対応しています。

## GitHub Pages で公開する手順

1. GitHub で新しいリポジトリを作ります（例：`takuya-gear`、公開＝Public）。
2. このフォルダの**中身**（`index.html`、`img/`、`voice/`、`bgm/`、`se/`、`.nojekyll`、この `README.md`）を、リポジトリのいちばん上の階層にアップロードします。
   - ブラウザからなら「Add file → Upload files」で、フォルダごとドラッグ＆ドロップできます。
   - 一度に100ファイルまでしか上げられないため、`voice/` は2回に分けてアップロードしてください。
3. リポジトリの「Settings → Pages」を開き、「Build and deployment」の Source を「Deploy from a branch」、Branch を `main` ／ `/ (root)` にして保存します。
4. 1〜2分ほどで `https://（ユーザー名）.github.io/（リポジトリ名）/` で遊べるようになります。

## フォルダの中身

| 場所 | 内容 |
|---|---|
| `index.html` | ゲーム本体（プログラム・ドット絵・画面のすべて） |
| `img/` | 会話の顔の絵、OP・カットシーン・エンディングの一枚絵、ロゴ（WebP） |
| `voice/` | キャラクターの声（MP3） |
| `bgm/` | BGM（AAC・`.mp4`）と、OP・EDの主題歌（MP3） |
| `se/` | 効果音・ジングル（AAC・`.mp4`） |
| `.nojekyll` | GitHub Pages にファイルをそのまま配信させるための空ファイル |

## メモ

- 記録（セーブ）はブラウザの中（localStorage）に保存されます。端末やブラウザが変わると引き継がれません。
- 文字のフォント（DotGothic16）は Google Fonts から読み込みます。読み込めない環境では、代わりのフォントで表示されます。
- `index.html` をパソコンで直接ダブルクリックして開くと、ブラウザの制限で音声の一部が鳴りません。必ず GitHub Pages などの Web サーバー経由で開いてください。
- 設定の「テスト用」ボタンは、画面上の「STAGE」を15回続けて押すと表示されます。
