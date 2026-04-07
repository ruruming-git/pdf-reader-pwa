# PDF 閱讀器 PWA

雙頁 PDF 閱讀器，支援 Apple Pencil 選字、Claude AI 對話。

## 上架到 GitHub Pages（免費）

### 步驟一：建立 GitHub 帳號
前往 https://github.com 註冊免費帳號。

### 步驟二：建立新 Repository
1. 點右上角「+」→「New repository」
2. Repository name 填：`pdf-reader`
3. 選「Public」
4. 點「Create repository」

### 步驟三：上傳檔案
1. 點「uploading an existing file」
2. 把這個資料夾裡的所有檔案拖進去：
   - index.html
   - manifest.json
   - sw.js
   - icons/ 資料夾（整個拖入）
3. 點「Commit changes」

### 步驟四：開啟 GitHub Pages
1. 進入 Repository → Settings
2. 左側選「Pages」
3. Source 選「Deploy from a branch」
4. Branch 選「main」→「/ (root)」
5. 點「Save」

### 步驟五：等 1-2 分鐘
網址會是：`https://你的帳號名.github.io/pdf-reader`

---

## 安裝到 iPad 主畫面

1. iPad Safari 開啟上面的網址
2. 點分享按鈕（方框加箭頭）
3. 選「加入主畫面」
4. 完成！從主畫面開啟就是全螢幕 App 模式 ✓

---

## 功能
- 📖 雙頁 / 單頁模式
- ✏️ Apple Pencil 點選文字
- 🤖 Claude AI 解釋、翻譯、對話
- 👆 左右滑動翻頁
- 🔍 雙指縮放
- ⌨️ 外接鍵盤方向鍵翻頁
- 📴 離線可用（Service Worker 快取）
