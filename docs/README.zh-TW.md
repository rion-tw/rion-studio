# Rion Studio

[English](../README.md) | 繁體中文 | [简体中文](README.zh-CN.md) | [日本語](README.ja.md)

![Rion Studio banner showing isolated roles, browser workspaces, and assistive controls](../.github/assets/rion-studio-github-preview-1280x640.jpg)

**跨平台的網頁遊戲啟動器與輔助工作區。**

Rion Studio 幫助網頁遊戲玩家在一個桌面 App 中整理每個角色、瀏覽器工作階段與視窗版面。你可以建立專用的瀏覽器角色、直接開啟遊戲畫面，並在主動掌控遊玩時減少重複的手動操作。

## 下載

- [下載 macOS 版](https://github.com/rion-tw/rion-studio/releases/latest/download/Rion.Studio-mac.dmg)
- [下載 Windows 版](https://github.com/rion-tw/rion-studio/releases/latest/download/Rion.Studio-win.exe)

這些連結會指向最新 GitHub Release 附加的安裝檔。如果下載時出現 404，請開啟[最新 release](https://github.com/rion-tw/rion-studio/releases/latest)，確認 release 資產已完成上傳。

### macOS 安裝

macOS App 使用 ad-hoc 程式碼簽章，不進行 notarization。請開啟 DMG、將 Rion Studio 拖到 Applications 後啟動。macOS 可能阻擋首次啟動；只有在 DMG 來自 Rion Studio 官方 GitHub Release，且公開的 checksum 相符時，才使用「系統設定 → 隱私權與安全性 → 強制打開」。

### Windows 安裝

Windows 安裝程式維持最初發佈方式，不使用 Authenticode 簽章。Windows 可能顯示 SmartScreen 警告；只有在安裝程式來自 Rion Studio 官方 GitHub Release，且公開的 checksum 相符時才繼續。

## 為什麼使用 Rion Studio

網頁遊戲經常讓玩家同時處理多個帳號、瀏覽器視窗、保存的瀏覽器工作階段與重複的例行操作。Rion Studio 將這些分散的流程整理成一個專注的控制台：

- 讓每個遊戲角色維持各自隔離的瀏覽器工作階段。
- 回到已儲存的視窗版面，不必每次重新配置。
- 在你的監督下執行小型輔助巨集，例如按鍵、點擊、延遲與循環。
- 不把密碼存進 App。Rion Studio 只儲存瀏覽器工作階段資料。

## 功能

### 隔離角色瀏覽器

為每個遊戲帳號、角色或任務建立一個角色。每個角色都有自己的瀏覽器目錄，因此工作階段會保持分離，並可獨立啟動。

### 直接啟動遊戲

角色與啟動工作區一律直接開啟設定好的遊戲網址。Rion Studio 不保存、判斷或顯示角色的登入狀態，也不提供重新登入流程。

### 啟動工作區

將角色分組成啟動工作區，並為每個角色指定視窗版面。你可以啟動單一角色，或一次啟動完整的多角色配置，回到已準備好的排列方式。

### 人為監督的巨集

使用按鍵、點擊、延遲與重複間隔建立精簡的輔助巨集。巨集的設計目標是在你仍然在場、監督並操作遊戲時，減少重複的手動輸入。

## 法律與合理使用聲明

Rion Studio 是獨立的一般用途啟動器及人工監督輔助工具，與任何遊戲、身分驗證服務或第三方平台均無隸屬或背書關係。請遵守目標服務規則，且不得用於無人 bot、反作弊規避、漏洞利用、干擾或違法活動。

- [使用條款](legal/terms.zh-TW.md)
- [隱私權聲明](legal/privacy.zh-TW.md)
- [公平使用規範](legal/fair-use.zh-TW.md)
- [第三方軟體聲明](legal/THIRD_PARTY_NOTICES.md)

## 支援與意見回饋

[公開發佈倉庫](https://github.com/rion-tw/rion-studio)是 Rion Studio 的下載與產品支援入口。
產品錯誤回報與功能建議請使用
[GitHub Issues](https://github.com/rion-tw/rion-studio/issues)。我們不接受原始碼 Pull Request；
請參閱 [`../SUPPORT.md`](../SUPPORT.md) 與 [`../SECURITY.md`](../SECURITY.md) 選擇正確的聯絡管道。
