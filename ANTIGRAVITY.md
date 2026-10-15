# ANTIGRAVITY.md - 專案導覽與架構說明

## 1. 專案背景
本專案依據高中/國中小資訊科技與視覺藝術跨域教學需求開發，旨在讓學生擺脫「提示詞不知該怎麼寫」的困境，透過系統化的十維度選單架構，體驗結構化 Prompt Engineering 的威力。

- **線上體驗**：[https://kadotw-lab.github.io/ai-prompt-generator/](https://kadotw-lab.github.io/ai-prompt-generator/)
- **原始碼儲存庫**：[https://github.com/kadotw-lab/ai-prompt-generator](https://github.com/kadotw-lab/ai-prompt-generator)

---

## 2. 檔案架構

```
20261015_AI 繪圖提示詞探索實驗室/
├── index.html                  # 核心單一網頁應用程式 (含完整 CSS 與 JS)
├── polar_bear_painting.jpg     # 頂部橫欄主角繪畫 3D 插圖
├── polar_bear_character.png    # 主角原創角色三視圖設定圖 (備存)
├── teacher_huang.png           # 導師角色設計圖 (備存)
├── README.md                   # 專案中文使用說明書
├── AGENTS.md                   # AI 助理開發與協作維護指南
├── ANTIGRAVITY.md              # 專案結構與導航文檔
├── handoff.md                  # 接續交接記錄
├── DEVELOPMENT_LOG.md          # 完整對話開發日誌
└── .gitignore                  # Git 忽略設定
```

---

## 3. 十大面向架構

1. **畫面主題 (Subject)**：核心角色或場景描述，支援範本快速帶入。
2. **畫面文字 (Text in Image)**：支援指定嵌入文字、12 種出現位置、7 種字體風格。
3. **畫面尺寸 (Aspect Ratio)**：1:1、16:9、9:16、4:3、3:4、2:1、21:9。
4. **繪畫媒材與立體材質 (Medium & Material)**：水彩、油畫、色鉛筆、水墨、紙雕、黏土等 25 種。
5. **動畫卡通與工作室 (Animation & Studios)**：吉卜力、皮克斯、新海誠、日漫黑白等 14 種。
6. **鏡頭角度與構圖 (Camera Angle & Shot)**：特寫、半身、全身、俯視、仰角、鳥瞰等 13 種。
7. **攝影特色與光影 (Lighting & Photography)**：電影劇照、黃金時刻、魔幻時刻、逆光輪廓等 13 種。
8. **經典藝術流派 (Art Movements)**：印象派、後印象派、超現實主義、浮世繪等 14 種。
9. **藝術家大師風格 (Artist Style)**：梵谷、莫內、慕夏、達利、草間彌生等 12 位。
10. **畫質渲染與精細度 (Quality & Modifiers)**：極致細節、大師傑作、8K、Unreal Engine 5 等 6 種。
