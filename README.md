# Amagi Translator 發布檔

Windows 桌面的日文圖片 OCR／翻譯工作台 **Amagi Translator** 的安裝檔發布處。

## 下載

到 [Releases](https://github.com/Racious/Amagi-Translator-Releases/releases/latest) 下載最新版的安裝程式（`*_x64-setup.exe`）。

- 安裝後，程式會在啟動時檢查這裡的新版本，經您同意才下載、驗證簽章並安裝。
- 0.1.0 沒有自動更新功能；請手動安裝一次 0.2.0 以後的版本。

## 說明

- 這個倉庫只放發布檔（安裝程式、更新清單 `latest.json` 與簽章），由發布流程自動上傳，不含原始碼。
- 每個安裝檔都以固定的簽章金鑰簽署，程式安裝更新前會驗證簽章，驗證不通過就不會安裝。
