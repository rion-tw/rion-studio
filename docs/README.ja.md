# Rion Studio

[English](../README.md) | [繁體中文](README.zh-TW.md) | [简体中文](README.zh-CN.md) | 日本語

![Rion Studio banner showing isolated roles, browser workspaces, and assistive controls](../.github/assets/rion-studio-github-preview-1280x640.jpg)

**Web ゲーム向けのクロスプラットフォームなログインランチャー兼補助ワークスペースです。**

Rion Studio は、Web ゲームのプレイヤーが各ロール、ログインセッション、ブラウザレイアウトを 1 つのデスクトップ App で整理できるようにします。専用のブラウザロールを作成し、ログインの手間を減らし、使い慣れたウィンドウ配置を起動し、プレイを自分で管理しながら反復的な手作業を減らせます。

## ダウンロード

- [macOS 版をダウンロード](https://github.com/rion-tw/rion-studio/releases/latest/download/Rion.Studio-mac.dmg)
- [Windows 版をダウンロード](https://github.com/rion-tw/rion-studio/releases/latest/download/Rion.Studio-win.exe)

これらのリンクは、最新の GitHub Release に添付されたインストーラーを指します。ダウンロードが 404 になる場合は、[latest release](https://github.com/rion-tw/rion-studio/releases/latest) を開き、release アセットのアップロードが完了していることを確認してください。

### macOS へのインストール

macOS ベータビルドは ad-hoc 署名を使用しており、Apple Developer ID で notarization されていません。DMG を開き、Rion Studio を Applications にドラッグしてから、一度起動してみてください。macOS によってブロックされた場合は、**System Settings > Privacy & Security** を開き、Rion Studio の **Open Anyway** をクリックしてください。

**Open Anyway** が表示されず、ダウンロード元を信頼できる場合は、Terminal で次の一度限りの代替コマンドを使用できます。

```bash
xattr -dr com.apple.quarantine "/Applications/Rion Studio.app"
```

この代替コマンドは Rion Studio から quarantine 属性だけを削除します。App を notarization するものではなく、Gatekeeper をシステム全体で無効化するものでもありません。

## Rion Studio を使う理由

Web ゲームでは、複数のアカウント、ブラウザウィンドウ、ログイン状態、反復的な操作を同時に扱うことがよくあります。Rion Studio は、その散らばったワークフローを集中して扱えるコントロールデスクに変えます。

- 各ゲームロールを、それぞれ隔離されたブラウザセッションに保ちます。
- 毎回セットアップし直す代わりに、保存済みのウィンドウレイアウトへ戻れます。
- 必要に応じて、システム Chrome で慎重なサインインフローを完了できます。
- キー入力、クリック、待機、ループなどの小さな補助マクロを、あなたの監督下で実行できます。
- パスワードは App に保存しません。Rion Studio が保存するのはブラウザセッションデータだけです。

## 機能

### 隔離されたロールブラウザ

ゲームアカウント、キャラクター、タスクごとにロールを作成できます。各ロールは専用のブラウザディレクトリを持つため、セッションは分離されたまま個別に起動できます。

### よりスムーズなログインフロー

一部のサービスは、自動化制御されたブラウザ内でのサインインをブロックします。Rion Studio は同じロールディレクトリをシステム Chrome で開いてログインし、その後、通常の内蔵ブラウザを起動する前に保存済みセッションを検証できます。

### 起動ワークスペース

ロールを起動ワークスペースにまとめ、それぞれにウィンドウレイアウトを割り当てられます。単一ロールを起動することも、準備済みの配置で複数ロール構成をまとめて起動することもできます。

### 中国向け CDN 互換モード

Google がホストするリソースへ接続できないネットワークで、読み込みを改善します。任意で有効にできる互換モードは、制限された接続を自動検出し、内蔵ブラウザと外部 Chrome のセッションで、対応する Google Fonts、Hosted Libraries、reCAPTCHA、Gravatar、Bootstrap、jQuery のリソース URL を接続可能な代替先へ置き換えます。これは特定リソースの URL を書き換える機能であり、VPN やプロキシサービスではありません。

### 人が監督するマクロ

キー入力、クリック、待機、繰り返し間隔からコンパクトな補助マクロを作成できます。マクロは、あなたがその場にいて監督し、ゲームを操作し続ける状態で、反復的な手入力を減らすために設計されています。

## 法的事項とフェアユースに関する注意

Rion Studio は独立した汎用ランチャー兼、人が監督する補助ツールです。ゲーム、認証事業者、第三者プラットフォームとの提携や承認関係はありません。対象サービスの規則に従い、無人 bot、アンチチート回避、バグ悪用、妨害、違法行為に使用しないでください。

- [利用規約](legal/terms.ja.md)
- [プライバシー通知](legal/privacy.ja.md)
- [公正利用規則](legal/fair-use.ja.md)
- [第三者ソフトウェア通知](legal/THIRD_PARTY_NOTICES.md)

## サポートとフィードバック

このリポジトリは Rion Studio の公開ダウンロードおよび製品サポート窓口です。
製品の不具合報告や機能要望には [GitHub Issues](https://github.com/rion-tw/rion-studio/issues) をご利用ください。
ソースコードの Pull Request は受け付けていません。適切な連絡先は
[`../SUPPORT.md`](../SUPPORT.md) と [`../SECURITY.md`](../SECURITY.md) をご確認ください。
