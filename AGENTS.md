# AGENTS.md - 專案協作與維護指南

## 專案概要
- **專案名稱**：AI 繪圖提示詞探索實驗室 (AI Prompt Generator)
- **建立日期**：2026-10-15
- **專案路徑**：`C:\AI_Agent專案資料夾\【Antigravity專案】\20261015_AI 繪圖提示詞探索實驗室`
- **正式發佈網址**：https://kadotw-lab.github.io/ai-prompt-generator/
- **GitHub 儲存庫**：https://github.com/kadotw-lab/ai-prompt-generator

---

## 角色與原則 (Agent Guidelines)

1. **單一檔案 HTML 設計 (Single-Page Vanilla Web App)**：
   - 核心邏輯、樣式與互動皆包裝在 `index.html` 內，確保無需任何伺服器環境或 build 工具，雙擊即可直接離線執行。
   - 所有外部資源與圖檔使用相對路徑引用（例如 `polar_bear_painting.jpg`）。
2. **美感與視覺規範**：
   - 背景色調：米紙護眼暖米底（`#f7f3eb`）搭配細微手帳格紋。
   - 主色調：探索深藍（`#2c4468`）、米色工裝（`#e8dcc6`）、暖棕皮革（`#8f583f`）、手繪標籤黃（`#f8e5c2`）。
   - 頂部橫欄：左側常駐 3D 精緻白熊畫圖插圖，右側呈現標籤與介紹。
3. **學生友善度 (Pedagogical Focus)**：
   - 全中英雙語對照，適合課堂單字與美感教學。
   - 包含三種輸出模式：Midjourney 指令、通用英文標籤、教學雙語對照表。
4. **Git 與發佈流程**：
   - 主要分支為 `main`。
   - 修改完成後提交並推送至 `origin main`，GitHub Pages 會自動觸發部署更新。
