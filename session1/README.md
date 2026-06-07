# AI 勉強会 — 環境構築

## 1. Claude をインストール

**macOS**
[claude.com/download](https://claude.com/download) →「Download for macOS」→ `.dmg` を開き、Claude を「アプリケーション」へドラッグ。

**Windows**
[claude.com/download](https://claude.com/download) →「Download for Windows」→ `.exe` を実行。
※「Code」タブが出ない場合は、先に [Git for Windows](https://git-scm.com/downloads/win) を入れて Claude を再起動。

## 2. 起動後

1. Claude を起動してサインイン（要 Pro / Max 等のサブスク）。
2. **設定 →「Claude Code」→「バイパス権限モードを許可」（英語版: Allow bypass permissions mode）をオン** にする。
3. **「Code」タブ** に移動し、フォルダを選んで、お使いの OS のプロンプトを入力:
   - **macOS**:
     ```
     python3, git, node, npm を Homebrew でインストール、またはアップデートして
     ```
   - **Windows**:
     ```
     python3, git, node, npm を winget でインストール、またはアップデートして
     ```
4. 送信欄の横の **モードセレクター** から **「許可をバイパス」（英語版: Bypass permissions）** を選んで実行（ショートカット: `⌘ / Ctrl + Shift + M`）。

> ※「許可をバイパス」は確認なしで全コマンドを実行します。1 つずつ確認しながら進めたい場合は、このモードを選ばずに進めてください。

## 3. Claude in Chrome 拡張をインストール

ブラウザ（Chrome）を Claude から操作したい場合に追加。

[Chrome ウェブストア — Claude](https://chromewebstore.google.com/detail/claude/fcoeoabgfenejglbffodgkkbkcdhcgfn?hl=ja) →「Chrome に追加」。

[アンケート](https://claude.ai/public/artifacts/929dff6e-69e4-469e-ba31-bddee9cda903)
