<p align="center">
  <img src="assets/icon_256.png" width="96" height="96" alt="Explorer Toolbox icon">
</p>

<h1 align="center">Explorer Toolbox</h1>

<p align="center">Convert files right from the Windows Explorer right-click menu.<br>
Windows Explorer の右クリックメニューから、そのままファイル変換。</p>

<p align="center"><a href="#english">English</a> | <a href="#japanese">日本語</a></p>

This repository is the **download page for Explorer Toolbox**. It contains no
source code (closed-source software) — just the installer, published under
[Releases](../../releases).

---

<a id="english"></a>
## English

### What is this?

Explorer Toolbox adds a right-click menu to Windows Explorer for converting
image files (PNG / JPEG / WebP) without opening a separate app or website.

- Right-click one or more image files, pick a target format, done
- Conversion runs **entirely locally** — nothing is uploaded anywhere
- Convert a single file or a whole multi-file selection at once

### Install

1. Download the latest `ExplorerToolboxSetup-*.exe` from [Releases](../../releases)
2. Run it and follow the installer
3. Windows SmartScreen may show a warning since the installer isn't
   code-signed yet — click **More info**, then **Run anyway**
4. Follow the installer prompts (a Windows admin-permission prompt is normal)

### Usage

1. Right-click one or more PNG / JPEG / WebP files
2. **On Windows 11**: click **Show more options** at the bottom of the menu
   first — that's where it currently lives. (Getting it into the modern
   top-level menu requires packaging + a code-signing certificate, which
   isn't in place yet, so no promises on timing.)
3. Choose **Explorer Toolbox** → **Convert** → the format you want
4. The converted file appears in the same folder as `<original-name>_convert.<ext>`

### Uninstall

Settings → Apps → Explorer Toolbox → Uninstall, like any other app.

### System Requirements

Windows 10 / 11 (64-bit). No extra runtime installs required.

### Feedback

This is an early release — bug reports, requests, and "would you pay for
X" opinions are all welcome. Please use
[Issues](../../issues) on this repo.

### License

Explorer Toolbox is proprietary (closed-source) software. See the EULA
bundled with the installer for terms of use.

---

<a id="japanese"></a>
## 日本語

### これは何？

Explorer Toolbox は、Windows Explorer の右クリックメニューに直接「ファイル変換」を
追加する軽量ユーティリティです。

- 画像ファイル（PNG / JPEG / WebP）を右クリック → 変換したい形式を選ぶだけ
- 変換は**完全にローカルで完結**。ファイルはどこにもアップロードされません
- 複数ファイルをまとめて選択して、一括変換も可能

### インストール方法

1. [Releases](../../releases) ページから最新の `ExplorerToolboxSetup-*.exe` をダウンロード
2. ダウンロードしたファイルをダブルクリックして実行
3. Windows SmartScreen の警告が出た場合（未署名アプリのため表示されることがあります）:
   「**詳細情報**」→「**実行**」をクリックして進めてください
4. インストーラの指示に従って進めるだけで完了です（管理者権限の確認画面が出ます）

### 使い方

1. PNG / JPEG / WebP のいずれかのファイルを右クリック（複数選択も可）
2. **Windows 11の場合**: メニュー下部の「**その他のオプションを確認**」をクリック
   （現時点ではここに表示されます。Windows 11のトップレベルメニューに出すには
   別途パッケージ化とコード署名証明書が必要なため、現時点では対応時期は未定です）
3. 「**Explorer Toolbox**」→「**Convert**」→ 変換したい形式を選択
4. 同じフォルダに `<元のファイル名>_convert.<拡張子>` として変換後のファイルが生成されます

### アンインストール

「設定」→「アプリ」→「Explorer Toolbox」から通常のアプリと同じ方法でアンインストールできます。

### 動作環境

Windows 10 / 11 (64bit)。追加のランタイムのインストールは不要です。

### フィードバック

まだリリースしたばかりです。不具合報告・要望・「これは有料でも使うか」といった
ご意見も歓迎します。このリポジトリの[Issues](../../issues)からお願いします。

### ライセンス

Explorer Toolbox はプロプライエタリ（closed-source）ソフトウェアです。利用条件は
インストーラに含まれるEULA（使用許諾契約書）を参照してください。
