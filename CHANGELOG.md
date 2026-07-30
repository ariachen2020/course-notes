# 更新日誌

## 2026-07-30

網站上線
- 建立課程筆記書架網站，收錄三門 Anthropic Academy 課程筆記：Claude Code in Action、AI Fluency for Small Businesses、Introduction to Claude Cowork
- 建立公開 GitHub repo（ariachen2020/course-notes）並開啟 GitHub Pages
- 網址：https://ariachen2020.github.io/course-notes/

新增筆記
- 新增第四門課「Introduction to Subagents」（2 模組、4 課），放在 /subagents/
- 首頁書架加上對應書卡，封面採用該筆記站的「斥候地形圖」主題

維護
- 移除誤入的 macOS 系統檔 .DS_Store，加入 .gitignore 之後自動忽略

工作流程約定
- 之後在 Claude 桌面版做完新筆記，把 HTML 檔案丟進 course-notes 資料夾（或貼檔案路徑給 Claude Code），說一聲即可自動整理、加書卡、發布
- 首頁書卡是手動維護的：新增筆記資料夾時要同步在 index.html 加卡片
