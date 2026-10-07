# 檔案總管顯示 DWG 版本欄位

在 Windows 檔案總管顯示「DWG 版本」與「DWG 格式代碼」，方便查看及排序 AutoCAD 圖檔。不需要安裝 AutoCAD。

## 下載

**[下載安裝包 DwgVersionColumn.zip](https://github.com/kv1012tiger/DwgVersionColumn/releases/latest/download/DwgVersionColumn.zip)**

[版本與下載頁面](https://github.com/kv1012tiger/DwgVersionColumn/releases/latest)

適用 Windows 10／11 x64，安裝需要系統管理員權限。

## 安裝與使用

1. 下載 ZIP 並完整解壓縮，保留 `bin` 與 `scripts` 資料夾。
2. 雙擊 `2_Install.bat`，出現 Windows 系統管理員權限提示時選「是」。
3. 顯示 `[OK] Installed.` 後，在重啟檔案總管提示輸入 `Y`，按 Enter。桌面與工作列可能短暫消失。
4. 開啟 DWG 所在資料夾，切換為「詳細資料」。
5. 在「名稱」等欄位標題按右鍵，選「其他…／更多…」。
6. 勾選「DWG 版本」與「DWG 格式代碼」，按「確定」。
7. 點擊「DWG 格式代碼」欄位標題即可排序。

解除安裝：執行 `3_Uninstall.bat`，依提示操作。

## 說明

「DWG 版本」表示檔案儲存格式，不一定是建立圖檔的 AutoCAD 年份。本工具只查看版本，不能轉換格式。

下載包提供 DWG 版本欄位功能。內含安裝與解除安裝 BAT、必要的 DLL／格式描述／輔助程式、PowerShell 安裝腳本及使用說明。

分享時請提供完整 ZIP，不能只提供 BAT。
