# 妙哉裝修網 專案-建築業功能網站整合專案 - 母版 V1.0
本專案旨在建立一個統一視覺與邏輯的建築業工具平台。所有子系統（如智慧建築、防水工程等）均套用「智慧建築取分管理器」的 UI 框架。
## 專案架構 (Structure)
- `index.html`          - 專案總入口（導覽導向頁面）
- `building_score.html` - 智慧建築取分管理器 (子功能範例)
- `assets/`             - 靜態資源目錄
    - `css/`            - 存放全站統一風格樣式 (theme.css)
    - `js/`             - 存放核心邏輯與子功能腳本 (core.js, chart.js)
    - `images/`         - 存放 Logo、icon 及建築示意圖
    - `music/`          - 存放系統提示音效
- `docs/`               - 存放開發手冊與規範

## 統一佈局規範 (Standardization)
1. **框架顏色**：採用深色漸層底色 (`--bg: #0b0f14`) 配上高對比面板 (`--panel: #121923`)[cite: 1]。
2. **圓弧坡度**：面板統一使用 `border-radius: 16px`；按鈕與輸入框為 `10px`[cite: 1]。
3. **左上擺放**：Logo 統一尺寸為 `80x80px`，位於 `.app-header` 最左側[cite: 1]。
4. **文字大小**：標題 `50px`、區塊標題 `18px`、內文 `15px`[cite: 1]。

## 目錄結構
- `index.html` — 首頁（主控/導覽）
- `waterproof.html` — 防水工程成本估算
- `building_score.html` — 智慧建築2024版分數選單
- `building_cost.html` — 智慧建築成本估算器
- `green_score.html` — 綠建築取分確認區
- `green_cost.html` — 綠建築成本估算器
- `mud.html` — 泥作工程成本估算
- `water_electric.html` — 水電工程成本估算
- `weak_current.html` — 弱電工程成本估算
- `woodwork.html` — 木工工程成本估算
- `backup_01.html` — 備用頁1
- `backup_02.html` — 備用頁2
- `backup_03.html` — 備用頁3
- `backup_04.html` — 備用頁4
- `assets/`
  - `images/` — 圖片
  - `videos/` — 影片
  - `music/` — 音樂
  - `js/` — JavaScript 程式
  - `css/` — 樣式表
- `README.md` — 本專案目錄與簡介
- `歸檔說明.txt` — 整個專案資料歸檔結構中文說明

## 各網頁功能說明

- 智慧建築、綠建築、各裝修工種工程成本估算
- 導覽選單帶你快速前往各功能
- 請參考每個 html 頁面上的說明
