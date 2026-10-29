# 🚀 Chrome 瀏覽器與雲端科技特務：20 關極限闖關修練場

這是一個為國中小至高中資訊科技課堂打造的互動式網頁闖關測驗，整合了 **Chrome 快捷鍵實戰**、**Google 搜尋高階語法**、**Google 雲端硬碟權限與管理機制**。

---

## 📌 部署指南

### 一、部署至 GitHub Pages（免費靜態網站託管）

1. **建立 GitHub Repository**
   - 前往 [GitHub.com](https://github.com) 登入您的帳號。
   - 點選右上角的 **「+」** ➔ **「New repository」**。
   - Repository name 輸入：`chrome-tech-agent-game`。
   - 選擇 **Public**（公開），其餘選項保持預設，點選 **Create repository**。

2. **推送代碼至 GitHub**
   在終端機（PowerShell 或 CMD）切換至本專案目錄並執行：
   ```bash
   cd C:\Users\user\.gemini\antigravity\scratch\chrome-tech-agent-game
   git remote add origin https://github.com/您的帳號/chrome-tech-agent-game.git
   git branch -M main
   git push -u origin main
   ```

3. **啟用 GitHub Pages**
   - 進入該 Repository 的 **Settings**（設定）頁面。
   - 左側選單點選 **Pages**。
   - 在 **Build and deployment** 下方的 **Branch**：
     - 分支選擇：`main`
     - 資料夾選擇：`/(root)`
     - 點選 **Save** 儲存。
   - 稍候約 1~2 分鐘，上方會出現您的專屬網址：
     `https://<您的帳號>.github.io/chrome-tech-agent-game/`

---

### 二、部署／嵌入至 Google Sites（Google 協作平台）

Google Sites 支援兩種嵌入方式：

#### 方法 A：直接嵌入 HTML 程式碼（最快速，免設定 GitHub）
1. 開啟 [Google 協作平台 (sites.google.com)](https://sites.google.com/) 並進入您的協作平台編輯頁面。
2. 點選右側面板的 **「插入 (Insert)」** ➔ **「嵌入 (Embed)」**。
3. 在彈出視窗中切換至 **「嵌入程式碼 (Embed code)」** 分頁。
4. 將專案中的 `index.html` 完整程式碼全選複製並貼入。
5. 點擊 **「下一步」** ➔ **「插入」**。
6. 拖曳協作平台中的區塊邊框，拉寬至滿版、並將高度拉長至合適尺寸，最後點選右上角 **「發布」** 即可！

#### 方法 B：透過網址嵌入（搭配 GitHub Pages，未來更新自動同步）
1. 完成上述 GitHub Pages 部署，取得網址（如 `https://<您的帳號>.github.io/chrome-tech-agent-game/`）。
2. 在 Google 協作平台右側點選 **「插入」** ➔ **「嵌入」**。
3. 選擇 **「透過網址 (By URL)」**，貼上您的 GitHub Pages 網址。
4. 選擇 **「全頁 (Whole page)」** ➔ 點擊 **「插入」**。
5. 調整尺寸至滿意大小並發布。

---

## 🎮 關卡架構一覽

### 🌱 階段一：基本技巧（1~10 關）
- 第 1 關：分頁神還原 (`Ctrl + Shift + T`)
- 第 2 關：公用電腦私密瀏覽（無痕模式 `Ctrl + Shift + N`）
- 第 3 關：精準關鍵字包圍戰（半形雙引號 `""`）
- 第 4 關：我的好站收藏夾（加入書籤 `Ctrl + D`）
- 第 5 關：瞬間回彈搜尋列（搜尋結果頁單鍵 `/`）
- 第 6 關：雲端硬碟檔案搬運工（＋新增 ➔ 檔案上傳）
- 第 7 關：雲端空間有極限嗎？（免費 15 GB）
- 第 8 關：以圖搜圖神器（Google 智慧鏡頭）
- 第 9 關：資料夾階層管理概念（子資料夾自動沿用檢視者權限）
- 第 10 關：基本技巧守關檢定（指定文件搜尋 `BTS filetype:pdf`）

### 🔥 階段二：進階技巧（11~20 關）
- 第 11 關：區間數值與地區限定（`牛排館 大安區..信義區`）
- 第 12 關：雲端硬碟權限三重奏（加註者 Commenter）
- 第 13 關：搜尋工具時間篩選魔法（搜尋列「工具」按鈕）
- 第 14 關：雙向備份的核心素養（離線防護與實體備份觀念）
- 第 15 關：快速關閉分頁神技（`Ctrl + W`）
- 第 16 關：雲端檔案共享上限知識（單檔最多 600 個帳號）
- 第 17 關：同時編輯的上限門檻（100 人同時編輯門檻）
- 第 18 關：分頁切換閃電手（瞬間切回第 1 分頁 `Ctrl + 1`）
- 第 19 關：指定網站站內搜尋語法（`雲端運算 site:edu.tw`）
- 第 20 關：特務終極試煉（三合一複合指令：`"生成式AI" site:edu.tw filetype:pdf`）
