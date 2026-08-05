# Rion Studio

[English](../README.md) | [繁體中文](README.zh-TW.md) | [简体中文](README.zh-CN.md) | 日本語

![Rion Studio banner showing isolated roles, browser workspaces, and assistive controls](../.github/assets/rion-studio-github-preview-1280x640.jpg)

**Web ゲーム向けのクロスプラットフォームなランチャー兼補助ワークスペースです。**

Rion Studio は、Web ゲームのプレイヤーが各ロール、ブラウザーセッション、ウィンドウ配置を 1 つのデスクトップ App で整理できるようにします。専用のブラウザーロールを作成し、ゲーム画面を直接開き、プレイを自分で管理しながら反復的な手作業を減らせます。

## ダウンロード

- [macOS 版をダウンロード](https://github.com/rion-tw/rion-studio/releases/latest/download/Rion.Studio-mac.dmg)
- [Windows 版をダウンロード](https://github.com/rion-tw/rion-studio/releases/latest/download/Rion.Studio-win.exe)

これらのリンクは、最新の GitHub Release に添付されたインストーラーを指します。ダウンロードが 404 になる場合は、[latest release](https://github.com/rion-tw/rion-studio/releases/latest) を開き、release アセットのアップロードが完了していることを確認してください。

### macOS へのインストール

macOS App は ad-hoc コード署名を使用し、notarization は行いません。DMG を開き、Rion Studio を Applications にドラッグして起動してください。初回起動がブロックされた場合は、DMG が Rion Studio 公式 GitHub Release から取得したもので、公開 checksum が一致するときに限り、「システム設定 → プライバシーとセキュリティ → このまま開く」を使用してください。

### Windows へのインストール

Windows インストーラーは当初の配布方式に合わせて未署名のままです。SmartScreen の警告が表示される場合があります。Rion Studio 公式 GitHub Release から取得し、公開 checksum が一致するインストーラーに限って続行してください。

## Rion Studio を使う理由

Web ゲームでは、複数のアカウント、ブラウザウィンドウ、保存されたブラウザーセッション、反復的な操作を同時に扱うことがよくあります。Rion Studio は、その散らばったワークフローを集中して扱えるコントロールデスクに変えます。

- 各ゲームロールを、それぞれ隔離されたブラウザセッションに保ちます。
- 毎回セットアップし直す代わりに、保存済みのウィンドウレイアウトへ戻れます。
- キー入力、クリック、待機、ループなどの小さな補助マクロを、あなたの監督下で実行できます。
- パスワードは App に保存しません。Rion Studio が保存するのはブラウザセッションデータだけです。

## 機能

### 隔離されたロールブラウザ

ゲームアカウント、キャラクター、タスクごとにロールを作成できます。各ロールは専用のブラウザディレクトリを持つため、セッションは分離されたまま個別に起動できます。

### ゲームを直接起動

ロールと起動ワークスペースは、設定されたゲーム URL を常に直接開きます。Rion Studio はロールのログイン状態を保存、判定、表示せず、再ログインフローも提供しません。

### 起動ワークスペース

ロールを起動ワークスペースにまとめ、それぞれにウィンドウレイアウトを割り当てられます。単一ロールを起動することも、準備済みの配置で複数ロール構成をまとめて起動することもできます。

### 人が監督するマクロ

キー入力、クリック、待機、繰り返し間隔からコンパクトな補助マクロを作成できます。マクロは、あなたがその場にいて監督し、ゲームを操作し続ける状態で、反復的な手入力を減らすために設計されています。

## 法的事項とフェアユースに関する注意

Rion Studio は独立した汎用ランチャー兼、人が監督する補助ツールです。ゲーム、認証事業者、第三者プラットフォームとの提携や承認関係はありません。対象サービスの規則に従い、無人 bot、アンチチート回避、バグ悪用、妨害、違法行為に使用しないでください。

- [利用規約](legal/terms.ja.md)
- [プライバシー通知](legal/privacy.ja.md)
- [公正利用規則](legal/fair-use.ja.md)
- [第三者ソフトウェア通知](legal/THIRD_PARTY_NOTICES.md)

## サポートとフィードバック

[公開配布リポジトリ](https://github.com/rion-tw/rion-studio)は Rion Studio のダウンロードおよび製品サポート窓口です。
製品の不具合報告や機能要望には
[GitHub Issues](https://github.com/rion-tw/rion-studio/issues) を使用してください。ソースコードの Pull Request は受け付けていません。
適切な連絡先については [`../SUPPORT.md`](../SUPPORT.md) と [`../SECURITY.md`](../SECURITY.md) を参照してください。
