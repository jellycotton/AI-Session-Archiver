<a id="jp"></a>
**日本語** ・ [English](#en)

# 更新履歴

AI Session Archiver（ASA）の更新履歴です。ASA は **Windows アプリ本体**と **Chrome 拡張機能**の 2 つで動くため、それぞれ分けて記載しています。バージョン番号も別々に進みます。

- **本体**：ストア（BOOTH / Lemon Squeezy）または GitHub の配布ページから入れ替えて更新します。
- **拡張機能**：Chrome ウェブストアから自動で更新されます。手動の操作は不要です。

---

## 本体アプリ（Windows）

3 つの版（ChatGPT 版 / Claude 版 / Gemini 版）で共通の内容です。

### v1.0.5.11（2026-08-11）

- セットアップの案内文を整理しました（配布版では行われない「依存関係のインストール」の記載を削除し、確認画面を 1 つにまとめました）
- 完了画面に、すでに拡張機能を導入済みの場合はそのまま終了してよいことを明記しました

### v1.0.5.10（2026-08-09）

- タグの並び順が正しく保存されなかった不具合の修正

### v1.0.5.9（2026-08-09）

- 更新（新しいバージョンへの入れ替え）時に、タグや保存設定がそのまま引き継がれるようになりました
- 既定の保存先をアプリフォルダの外に変更しました（更新やアンインストール時に保存済みの会話が巻き込まれないように）
- zip を同名フォルダに展開すると二重フォルダになる問題を防ぐため、展開フォルダ名にバージョンを含めました
- セットアップ完了画面と設定画面に、現在のバージョンを表示するようにしました
- リアルタイムキャプチャ中の小窓の幅が伸びていく問題を修正しました

（これより前のバージョンの履歴は記録していません）

---

## Chrome 拡張機能

「ASA Bridge for ChatGPT / Claude / Gemini」の履歴です。バージョンは Chrome の「拡張機能」ページで確認できます。

### 1.0.5.3（2026-07-09）

**3 版共通**

- ツールバーの拡張機能アイコンを押すと「保存」「設定」ボタンが出るようになりました。会話画面に小窓（ウィジェット）が出ていない状況でも操作できます
- 対象のサービス以外のページでアイコンを押した時に、案内を表示するようにしました
- ストア掲載の説明文を更新しました（拡張機能だけでは動作せず、本体アプリが必要であることを明示）

**ChatGPT 版**

- 共有ページ（`/share/`）の保存に対応しました
- 画像が保存物から抜け落ちる不具合をまとめて修正しました。1 回のプロンプトで複数枚生成した時に選ばなかった候補画像も保存し、画像が表示される前に保存した場合の取りこぼしも防ぎます
- グラフを取得して PDF に忠実に描画するようにしました
- ショッピングの商品カルーセルを、横並びのカードとして保存するようにしました
- 複数の画像を、均一な正方タイルの格子で並べて表示するようにしました（HTML / PDF 共通）
- 無料版の広告が会話に挟まると、広告より後の発言が保存されなかった不具合を修正しました
- グループチャットで、他の参加者が添付した画像を実際に表示するようにしました。発言も送信者名付きのブロックに整えています
- 保存ボタンを押した時に一時的に固まる問題を解消しました
- 取得に時間がかかっている間、処理中であることを示す表示を出すようにしました

**Claude 版**

- 共有ページ（`/share/`）の保存に対応しました
- `claude.ai/code`（コード画面）の会話保存に対応しました。この画面にも小窓（ウィジェット）を表示します。なお、この画面はつくりの都合でキャプチャモードが使えないため、該当ボタンは無効表示にしています
- 図（SVG / Mermaid など）を画像として出力に埋め込むようにしました
- 対話型グラフを全タブ分取得し、それぞれ画像として埋め込むようにしました
- ネット上の引用画像を取得し、インターネットに繋がっていなくても見られるよう HTML に埋め込むようにしました
- 複数の画像を、均一な正方タイルの格子で並べて表示するようにしました（HTML / PDF 共通）
- 取得に時間がかかっている間、処理中であることを示す表示を出すようにしました

**Gemini 版**

- 共有ページの保存で、AI の返答や生成画像が抜け落ちる不具合を修正しました。保存タイトルの文字化けもあわせて解消しています
- コード実行で作られたグラフ画像が、保存物で灰色の箱や URL 文字になっていた不具合を修正しました
- ショッピング結果を全形式（HTML / md / txt / PDF）で見やすく整えました。一部のアカウントで画像・商品名・価格がまとめて抜け落ちる不具合も修正しています
- ウェブ引用の画像を出力に埋め込み、出典表示・配置・表示サイズ・説明文を整えました
- 数式を読みやすい形で描画するようにしました
- 引用部分の見た目を、サイト上の表示に合わせました
- 複数の画像を、均一な正方タイルの格子で並べて表示するようにしました（HTML / PDF 共通）

（これより前のバージョンの履歴は記録していません）

---

<a id="en"></a>
[日本語](#jp) ・ **English**

# Changelog

Release history for AI Session Archiver (ASA). ASA has two parts — the **Windows app** and the **Chrome extension** — so they are listed separately. Their version numbers advance independently.

- **App:** updated by replacing your install with a newer download from the stores (BOOTH / Lemon Squeezy) or from GitHub Releases.
- **Extension:** updated automatically by the Chrome Web Store. Nothing to do on your side.

---

## Windows App

The same for all three editions (ChatGPT / Claude / Gemini).

### v1.0.5.11 (2026-08-11)

- Reworded the installer prompts: dropped the dependency-installation notice that never applied to the packaged build, and merged two confirmations into one
- The completion screen now says you can skip the store when the extension is already installed

### v1.0.5.10 (2026-08-09)

- Fixed an issue where the selected tag order was not saved correctly

### v1.0.5.9 (2026-08-09)

- Settings (tags, save preferences, etc.) now carry over when you update to a new version
- The default save folder moved outside the app folder, so your saved conversations are never affected by updates or uninstalls
- The extracted folder name now includes the version number, preventing accidental nested folders when extracting over an old install
- The setup completion screen and the settings screen now show the current version
- Fixed the realtime capture window growing wider as text streamed in

(History before this version is not recorded)

---

## Chrome Extension

For "ASA Bridge for ChatGPT / Claude / Gemini". You can check the installed version on Chrome's Extensions page.

### 1.0.5.3 (2026-07-09)

**All three editions**

- Clicking the extension icon in the toolbar now opens a popup with Save and Settings buttons, so you can still operate ASA when the on-page widget isn't showing
- The popup now shows a short explanation when you click it on a page that isn't a supported service
- Updated the store listing text to state up front that the extension needs the desktop app to work

**For ChatGPT**

- Added support for saving shared pages (`/share/`)
- Fixed a group of issues where images went missing from saved output — alternate images from a multi-image generation are now kept, and images are no longer lost when you save before they finish rendering
- Charts are now captured and drawn faithfully in PDF output
- Shopping carousels are now saved as a row of product cards
- Multiple images are laid out as a grid of uniform square tiles (HTML and PDF)
- Fixed messages after an inline free-plan ad being cut from the saved conversation
- Images attached by other people in group chats are now shown, and each message is formatted as a block with the sender's name
- Fixed the brief freeze when pressing the save button
- A progress indicator now appears when fetching takes longer than usual

**For Claude**

- Added support for saving shared pages (`/share/`)
- Added support for saving conversations on `claude.ai/code`, including the on-page widget. Capture mode cannot work on that screen by design, so its button is shown disabled there
- Diagrams (SVG, Mermaid, and similar) are now embedded in the output as images
- Interactive charts are captured across all their tabs and embedded as images
- Cited images from the web are downloaded and embedded into the HTML, so they still display offline
- Multiple images are laid out as a grid of uniform square tiles (HTML and PDF)
- A progress indicator now appears when fetching takes longer than usual

**For Gemini**

- Fixed AI replies and generated images going missing when saving a shared page, and fixed garbled characters in the saved title
- Fixed charts produced by code execution appearing as a grey box or a raw URL in saved output
- Cleaned up how shopping results are saved across all formats (HTML / md / txt / PDF), and fixed images, product names, and prices being dropped entirely on some accounts
- Cited images from the web are embedded in the output, with tidied source labels, placement, sizing, and captions
- Formulas are now rendered in a more readable form
- Quoted passages now match how they look on the site
- Multiple images are laid out as a grid of uniform square tiles (HTML and PDF)

(History before this version is not recorded)
