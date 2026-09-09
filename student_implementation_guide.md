# 學員實操指南：如何使用「口氣」教學工具

## 🎯 5 種給學員的方式（由簡到難）

---

## 方式 1️⃣：**Google Drive 分享**（最簡單 ⭐⭐）
**難度：低｜耗時：2 分鐘｜需要：Google 帳號**

### 步驟
```
1. 上傳檔案到 Google Drive
   ✓ tone_teaching_guide.md → Google Docs（自動轉換）
   ✓ tone_interactive_tool.html → 上傳保存

2. 分享連結給學員
   □ 右鍵點選檔案 → 分享
   □ 改成「任何有連結的人都可以檢視」
   □ 複製連結

3. 學員操作
   □ 打開連結
   □ Markdown 檔案：直接看，記重點
   □ HTML 工具：直接在瀏覽器上操作（下拉選項、看例子）
```

### 優點
- ✅ 學員不用下載
- ✅ 隨時隨地都能打開
- ✅ HTML 工具可以直接互動

### 缺點
- ❌ 需要網路
- ❌ 需要 Google 帳號

### 分享連結長這樣
```
https://drive.google.com/file/d/[FILE_ID]/view
```

---

## 方式 2️⃣：**GitHub 托管**（推薦 ⭐⭐⭐⭐⭐）
**難度：中｜耗時：5 分鐘｜需要：GitHub 帳號**

### 為什麼推薦
- ✅ HTML 工具可以直接在瀏覽器上執行（不用下載）
- ✅ 學員只需點一個連結
- ✅ 版本控制，可以隨時更新
- ✅ 完全免費，速度快

### 步驟

#### 第 1 步：建立 GitHub Repository
```
1. 登入 GitHub → 點 New Repository
2. 名稱：tone-teaching-tool（或任意名稱）
3. 勾選 "Public"
4. 按 "Create repository"
```

#### 第 2 步：上傳檔案
```
方法 A：直接上傳（最簡單）
1. 進入 repo → 點 "Add file" → "Upload files"
2. 拖拉或選擇：
   ✓ tone_teaching_guide.md
   ✓ tone_interactive_tool.html
   ✓ 任何需要的圖片資源
3. 寫 commit message：「Initial upload」
4. 點 "Commit changes"

方法 B：用 Git 指令（給進階用戶）
```bash
git clone https://github.com/你的用戶名/tone-teaching-tool.git
cd tone-teaching-tool

# 把檔案複製進去
cp tone_teaching_guide.md .
cp tone_interactive_tool.html .

git add .
git commit -m "Initial upload"
git push
```
```

#### 第 3 步：學員怎麼用

**方式 A：直接看 HTML 工具（推薦！）**
```
1. 給學員這個連結：
   https://raw.githack.com/你的用戶名/tone-teaching-tool/main/tone_interactive_tool.html

2. 學員點開→直接就能用
   ✓ 下拉選場景
   ✓ 看 7 種口氣的對比
   ✓ 完全不用下載
```

**方式 B：看教學指南**
```
1. 學員進入 repo 首頁
2. 點 tone_teaching_guide.md 檔案
3. GitHub 自動渲染 Markdown
4. 可以邊看邊做筆記
```

### 分享給學員的完整連結
```
📖 教學指南：
https://github.com/你的用戶名/tone-teaching-tool/blob/main/tone_teaching_guide.md

🎮 互動工具（直接用，不用下載）：
https://raw.githack.com/你的用戶名/tone-teaching-tool/main/tone_interactive_tool.html

📥 完整資源包（所有檔案）：
https://github.com/你的用戶名/tone-teaching-tool
```

### 優點
- ✅ HTML 工具可以直接在瀏覽器上跑（無縫體驗）
- ✅ 可以分版本，容易更新
- ✅ 學員不用下載、不用安裝
- ✅ 支援行動裝置、平板、桌面
- ✅ 完全免費

### 缺點
- ❌ 需要會用 GitHub（但我會教）
- ❌ 需要網路

---

## 方式 3️⃣：**直接下載 ZIP**（最方便 ⭐⭐⭐）
**難度：低｜耗時：3 分鐘｜需要：無**

### 步驟

#### 第 1 步：打包成 ZIP
```
1. 建立一個資料夾：tone-teaching-materials
2. 把這些檔案放進去：
   ✓ tone_teaching_guide.md
   ✓ tone_interactive_tool.html
   ✓ README.txt（說明檔，見下方）

3. 用 7-Zip 或 WinRAR 壓縮成 .zip
4. 檔名：tone-teaching-materials.zip
```

#### 第 2 步：建立 README.txt（超重要！）
```
【口氣教學工具使用說明】

📖 檔案清單：
- tone_teaching_guide.md → 教學指南（用記事本或 Markdown 編輯器打開）
- tone_interactive_tool.html → 互動工具（用瀏覽器打開）

🎮 如何使用互動工具：
1. 找到 tone_interactive_tool.html
2. 用瀏覽器打開（Chrome / Safari / Firefox / Edge 都可以）
3. 下拉選單選擇場景
4. 看 7 種口氣的實際範例
5. 體會同一任務不同口氣的差異

📚 如何看教學指南：
1. 找到 tone_teaching_guide.md
2. 用任何文字編輯器打開（Word / 記事本 / Markdown 編輯器）
3. 建議搭配互動工具一起看

❓ 常見問題：
Q: HTML 工具打不開？
A: 確認用的是「瀏覽器」（Chrome/Safari/Firefox），不是「記事本」

Q: MD 文件亂碼？
A: 用「Markdown 編輯器」打開（Typora / VS Code），或貼到 Google Docs

Q: 可以改動檔案嗎？
A: 可以！複製一份自己用。

💡 建議流程：
1. 先看 tone_teaching_guide.md 瞭解理論
2. 打開 tone_interactive_tool.html 看實際例子
3. 自己試試不同的場景
4. 拿起自己的工作案例，試試不同口氣
```

#### 第 3 步：分享給學員
```
方式 A：Email 附件
- 新增附件 → 選 tone-teaching-materials.zip
- 寫一句話說明：「這是課堂教材，下載後用瀏覽器打開 HTML 檔案」

方式 B：雲端硬碟（Google Drive / OneDrive / Dropbox）
- 上傳 .zip 檔案
- 分享連結給全班

方式 B：USB 隨身碟
- 複製資料夾進去
- 上課時發給學員
```

### 學員的打開步驟
```
1. 下載 tone-teaching-materials.zip
2. 解壓縮（右鍵→解壓縮）
3. 打開資料夾
4. 【重要】用瀏覽器打開 tone_interactive_tool.html
   ✓ Windows：雙擊 HTML 檔 → 自動用瀏覽器開啟
   ✓ Mac：雙擊 HTML 檔 → 自動用 Safari 打開
5. 享受互動式教學！
```

### 優點
- ✅ 學員下載後離線也能用
- ✅ 完全不需要帳號、不需要網路
- ✅ 方便寄送、方便保存

### 缺點
- ❌ 檔案較大（但只有幾百 KB）
- ❌ 需要學員自己解壓縮
- ❌ 更新困難（要重新寄送 ZIP）

---

## 方式 4️⃣：**Notion 整合**（專業感 ⭐⭐⭐⭐）
**難度：中｜耗時：10 分鐘｜需要：Notion 帳號**

### 步驟

#### 第 1 步：在 Notion 建立頁面
```
1. 登入 Notion → 新建頁面
2. 頁面名稱：「口氣提示語教學」
3. 加入以下區塊：

【區塊 1】簡介
- 貼一段簡介文字

【區塊 2】教學內容
- 把 tone_teaching_guide.md 的內容複製貼進去
- Notion 會自動格式化

【區塊 3】互動工具
- 插入 Embed → 貼上 HTML 代碼
  （或用 GitHub 連結嵌入 iframe）

【區塊 4】練習題
- 建立 Database，裡面是學員的練習紀錄
```

#### 第 2 步：Notion 怎麼嵌入 HTML
```
方法：用 Iframe 嵌入

1. 在 Notion 頁面點 "+"
2. 搜尋 "Embed"
3. 選 "Embed"
4. 貼上這段代碼：

<iframe 
  src="https://raw.githack.com/你的/tone-teaching-tool/main/tone_interactive_tool.html"
  width="100%" 
  height="800"
  style="border: none; border-radius: 10px;">
</iframe>

5. 按 Enter
6. HTML 工具直接在 Notion 裡面可以用！
```

#### 第 3 步：分享給學員
```
1. Notion 頁面 → 點右上角 "Share"
2. 改成 "Anyone with the link"
3. 複製連結給學員
4. 學員打開連結→直接看到你設計的完整課程
```

### 優點
- ✅ 整合式教學平台
- ✅ 可以加入練習題、進度追蹤
- ✅ 專業美觀
- ✅ 支援協作（學員可在 Notion 裡做筆記）

### 缺點
- ❌ 需要網路
- ❌ 設置比較複雜

---

## 方式 5️⃣：**LMS 或線上課程平台**（企業級 ⭐⭐⭐⭐⭐）
**難度：高｜耗時：30 分鐘｜適合：企業內訓**

可以整合到這些平台：

### Google Classroom
```
1. 建立班級 → 加入學員
2. 課程作業：
   ✓ 上傳教學 PDF 版本
   ✓ 貼上 GitHub HTML 工具連結
   ✓ 指派練習作業

3. 學員可以在班級裡提交作業
4. 你可以給 feedback
```

### 企業訓練平台（Moodle / 企業內部系統）
```
1. 上傳資源
   ✓ tone_teaching_guide.md → PDF 化
   ✓ tone_interactive_tool.html → 內嵌或連結

2. 設計互動測驗
   ✓ 測驗題：「以下哪個場景應該用什麼口氣？」

3. 追蹤學員進度
   ✓ 誰完成了學習
   ✓ 誰提交了練習
   ✓ 成績統計
```

---

## 📋 快速對比表：選哪一種給學員？

| 方式 | 難度 | 速度 | 網路 | 更新 | 互動性 | 推薦指數 |
|------|------|------|------|------|--------|--------|
| **Google Drive** | ⭐ | 2分 | 必需 | 中等 | 高 | ⭐⭐⭐ |
| **GitHub** | ⭐⭐ | 5分 | 必需 | 非常好 | 高 | ⭐⭐⭐⭐⭐ |
| **ZIP 下載** | ⭐ | 3分 | 不需 | 困難 | 高 | ⭐⭐⭐ |
| **Notion** | ⭐⭐⭐ | 10分 | 必需 | 很好 | 非常高 | ⭐⭐⭐⭐ |
| **LMS 平台** | ⭐⭐⭐ | 30分 | 必需 | 很好 | 非常高 | ⭐⭐⭐⭐⭐ |

### 我的建議
```
👉 小班教學（10人以內）
   → 用 GitHub 或 ZIP 下載
   → 簡單、不用維護

👉 中班教學（10-50人）
   → 用 GitHub + Google Classroom
   → 有追蹤功能，易於分享

👉 大班教學（50人以上）或企業內訓
   → 用 LMS 平台（Moodle / 企業系統）
   → 完整的學習管理
```

---

## 🎬 各方式的「課堂流程」

### 流程 A：GitHub 方式（推薦）
```
課前（5分鐘）
□ 做好 GitHub repo
□ 測試 HTML 工具可以正常打開
□ 準備連結（貼在簡報最後一頁）

課中（45分鐘）
□ 0-5分：開場，問「什麼是口氣」
□ 5-15分：展示 HTML 工具（用投影機秀給全班看）
          - 切換不同場景
          - 對比 7 種口氣
          - 讓學員發現差異
□ 15-30分：講解教學指南內容
□ 30-40分：分組練習（給他們提示語範本）
□ 40-45分：抽簽分享，我批評改進

課後（隨時）
□ 分享 GitHub 連結給學員
□ 學員隨時可以打開複習
□ 有問題可以在 GitHub issue 發問
```

### 流程 B：ZIP 下載方式
```
課前（5分鐘）
□ 準備好 ZIP 檔案
□ 測試所有學員電腦都能打開 HTML

課中（45分鐘）
□ 0-5分：開場
□ 5-15分：投影機展示 HTML 工具
□ 15-30分：講解教學指南
□ 30-40分：分組練習
□ 40-45分：分享與回饋
□ 45-50分：發 USB/寄 ZIP 檔案

課後
□ 學員離線也能複習
□ 建議開個群組，讓他們有問題可以問
```

---

## 💡 製作學員版的「檢查清單」

在分享前，幫學員準備一份簡單的操作卡：

```markdown
【口氣教學 - 學員快速入門】

🎮 第 1 步：打開工具
□ 用瀏覽器打開 tone_interactive_tool.html
  （不是記事本！用 Chrome / Safari / Firefox）

📖 第 2 步：看教學指南
□ 打開 tone_teaching_guide.md
□ 讀 7 種口氣的定義
□ 記下「記憶法」與「簡短口訣」

🧠 第 3 步：體驗互動工具
□ 選一個場景（如「客訴回復」）
□ 切換不同口氣，看看哪些詞彙改變了
□ 哪個口氣最適合這個場景？為什麼？

✍️ 第 4 步：自己練習
□ 拿你工作中的一個任務
□ 試試用 3 種不同的口氣寫一遍
□ 比較哪個最有效

❓ 有問題嗎？
□ 看教學指南的「常見問題」段落
□ 或寄信給講師
```

---

## 🎯 完整交付清單

給學員時，確保包含：

```
✅ 檔案清單
  ☑ tone_teaching_guide.md
  ☑ tone_interactive_tool.html
  ☑ README.txt（使用說明）

✅ 分享方式
  ☑ GitHub 連結（優先）
  ☑ 或 ZIP 下載（備選）

✅ 學習資源
  ☑ 操作卡
  ☑ 練習題範本
  ☑ Q&A 連結

✅ 聯繫方式
  ☑ 問題討論群組
  ☑ 反饋表單
  ☑ Office hour
```

---

## 📞 給講師的最後提醒

### 上課前測試清單
```
□ 在自己電腦上測試所有檔案都能打開
□ 投影機能正常顯示 HTML 工具
□ 練習用的網路連接穩定
□ 準備備用方案（如 USB 隨身碟 + ZIP）
□ 學員名單確認
```

### 分享後的追蹤
```
□ 確認所有學員都收到資源
□ 問有沒有人打不開
□ 建立反饋管道（Email / 群組）
□ 根據反饋更新教材
```

---

**現在選一種方式給學員吧！** 🚀
