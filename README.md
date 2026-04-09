# PDF 閱讀器 PWA

雙頁 PDF 閱讀器，支援 Apple Pencil 選字、Claude AI 對話。

## 方法一：Terminal（Git 指令）

### 前置：安裝 Git
- Mac：`xcode-select --install`
- Windows：https://git-scm.com 下載安裝

### 步驟

```bash
# 1. 進入這個資料夾
cd pwa-pdf-reader

# 2. 初始化 Git
git init

# 3. 加入所有檔案
git add .

# 4. 第一次 commit
git commit -m "first commit"

# 5. 到 GitHub 建立新 repo（網頁操作）
#    https://github.com/new
#    名稱填 pdf-reader，選 Public，不要勾任何初始化選項

# 6. 連結遠端 repo（把下面換成你的 GitHub 帳號）
git remote add origin https://github.com/你的帳號/pdf-reader.git

# 7. 推上去
git branch -M main
git push -u origin main
```

### 開啟 GitHub Pages
```bash
# 推完之後去網頁設定（只需要做一次）：
# GitHub repo → Settings → Pages
# Source: Deploy from a branch
# Branch: main / (root) → Save
```

網址會是：`https://你的帳號.github.io/pdf-reader`

---

### 之後更新檔案只需要三行

```bash
git add .
git commit -m "update"
git push
```

---

## 方法二：GitHub 網頁上傳（不需要 Terminal）

1. 前往 https://github.com/new 建立新 repo
2. 點「uploading an existing file」
3. 把所有檔案拖進去上傳
4. 點「Commit changes」

---

## 安裝到 iPad 主畫面

1. iPad Safari 開啟 `https://你的帳號.github.io/pdf-reader`
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
