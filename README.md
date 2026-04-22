# 📂 Live Folder Monitor

![OS](https://img.shields.io/badge/OS-Windows-blue?style=flat-square&logo=windows)
![Language](https://img.shields.io/badge/Language-AutoHotkey_v2-green?style=flat-square&logo=autohotkey)
![Locale](https://img.shields.io/badge/Locale-正體中文-orange?style=flat-square)
![License](https://img.shields.io/badge/License-GPL_v3-red?style=flat-square)
![Latest Release](https://img.shields.io/github/v/release/ArtLife-Software/Live_Folder_Monitor?style=flat-square&color=blue)
![Downloads](https://img.shields.io/github/downloads/ArtLife-Software/Live_Folder_Monitor/total?style=flat-square&logo=github)

[](https://opensource.org/licenses/GPL-3.0)
[](https://www.autohotkey.com/)
[](https://www.microsoft.com/windows)

**Live Folder Monitor** 是一款功能強大的即時資料夾監控工具，基於 AutoHotkey v2 開發。它能追蹤本地或網路路徑（UNC）中的檔案變動（新增、修改、刪除），並提供視覺化的日誌管理與即時通知，非常適合開發人員或需要自動化檔案追蹤的使用者。

## ✨ 核心特色

  * **多路徑監控**：支援同時監控多個不同的資料夾，並可自定義是否包含子資料夾。
  * **網路路徑支援**：完美支援 UNC 路徑（如 `\\Server\Folder`），適合辦公室環境使用。
  * **離線變動偵測**：可開啟「結束時保存狀態」功能，下次啟動時會自動比對關機期間發生的檔案異動。
  * **自定義掃描頻率**：可自由調整掃描間隔（1秒至3600秒）。
  * **視覺化日誌與通知**：
      * 內建 ListView 即時顯示變動資訊。
      * 自動產生日誌檔案（按日期分類）。
      * 具備淡入閃爍效果的自定義 Toast 通知彈窗。
  * **強大右鍵功能**：日誌列表支援直接開啟檔案、定位路徑、複製檔案或將實體檔案移至回收桶。

## 🚀 快速開始

### 1\. 安裝與運行

  * **執行檔**：從 [Releases](https://github.com/ArtLife-Software) 下載最新編譯版本。
  * **腳本運行**：確保已安裝 [AutoHotkey v2.0+](https://www.autohotkey.com/)，下載 `Live_Folder_Monitor.ahk` 後直接執行。

### 2\. 基本操作

1.  點擊 **⚙️ 管理監控路徑**：新增你想要監控的目錄。
2.  點擊 **⏱️ 設定掃描頻率**：調整檢查檔案的時間間隔。
3.  **📌 最上層顯示**：勾選後可將視窗置頂，方便隨時觀察日誌。
4.  **右鍵功能表**：在日誌清單上點擊右鍵，可直接對檔案進行操作。

## 📂 檔案說明

  * `Live_Folder_Monitor.exe`：主程式。
  * `Live_Folder_Monitor_Settings.ini`：存儲監控清單與系統偏好設定。
  * `Snapshots.dat`：存儲檔案快照資訊（若開啟離線偵測功能）。
  * `Logs/`：自動生成的資料夾，存放每日監控記錄（`.txt`）。

## 🛠 開發環境

  * **語言**：AutoHotkey v2.0
  * **平台**：Windows 10 / 11 (x64)
  * **授權**：GPL-3.0 License

## 👤 關於作者

  * **設計開發**：林彥丞
  * **聯絡信箱**：[lin.yancheng@outlook.com](mailto:lin.yancheng@outlook.com)
  * **GitHub**：[ArtLife-Software](https://github.com/ArtLife-Software)
  * **社群交流**：[O & C VBA研究社 (Facebook)](https://www.facebook.com/groups/vba.club)

-----

*Copyright © 2026 林彥丞. Made with ❤️ in Taiwan (R.O.C)*
