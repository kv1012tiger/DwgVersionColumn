# 檔案總管顯示 DWG 版本欄位

在 Windows 檔案總管顯示「DWG 版本」與「DWG 格式代碼」，方便查看及排序 AutoCAD 圖檔。不需要安裝 AutoCAD。

## 下載

**[下載最新安裝包 DwgVersionColumn.zip](https://github.com/kv1012tiger/DwgVersionColumn/releases/latest/download/DwgVersionColumn.zip)**

[版本與下載頁面](https://github.com/kv1012tiger/DwgVersionColumn/releases/latest)

目前版本為 **v1.0.1 圖形安裝版**。適用 Windows 10／11 x64，安裝需要系統管理員權限。

## 安裝與更新

1. 下載 ZIP 並完整解壓縮。
2. 開啟 `DwgVersionColumnSetup.exe`，按「安裝／更新」。
3. 出現 Windows 系統管理員權限提示時選「是」。
4. 完成後先儲存工作，再登出並登入 Windows，或重新啟動電腦。
5. 開啟 DWG 所在資料夾，切換為「詳細資料」。
6. 在「名稱」等欄位標題按右鍵，選「其他…／更多…」。
7. 勾選「DWG 版本」與「DWG 格式代碼」，按「確定」。點擊「DWG 格式代碼」欄位標題即可排序。

已安裝舊版者可直接按「安裝／更新」，不需要先解除安裝。

## 解除安裝

開啟同一個 `DwgVersionColumnSetup.exe`，按「解除安裝」，依提示操作。請保留安裝程式。

## 說明

「DWG 版本」表示檔案儲存格式，不一定是建立圖檔的 AutoCAD 年份。本工具只查看版本，不能轉換格式。

v1.0.1 下載包包含圖形安裝程式與使用說明；必要的 DLL 與格式描述已內嵌，不含 BAT、PowerShell 或 VBS 腳本。GitHub 自動附加的 Source code 壓縮檔不是安裝包。

舊 v1.0.0 ZIP 曾被 Defender 攔截，請改用最新版本。候選圖形安裝包已完成一次本機 Defender 掃描，未新增偵測紀錄；這不代表 Microsoft 已撤銷舊 ZIP 的偵測，也不保證所有電腦的防毒結果相同。
