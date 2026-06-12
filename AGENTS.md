# Fortune Coach — AGENTS.md

## Project

Fortune Coach

定位：

AI 私人命理師 + 每日行動教練。

不是醫療、法律、投資、心理治療或保證預測系統。

它是：

> 用東西方玄學語言包裝的日常陪伴與行動建議工具。

## Working Folder

`/Users/fancymac2018/Documents/Codex/FortuneCoach`

## Source Notes

原始企劃資料在：

`/Users/fancymac2018/Documents/ObsidianV/Fortune Coach`

主要參考：

- `Fortune SeepSeek.md`
- `每日運勢app Chat.md`
- `設計每日運勢的app Gemini.md`
- `Photos/image_4fc5c2e3.png`

## Current Product Stage

Early planning / mobile Web App prototype.

目前不要急著做原生 iOS。

優先順序：

1. 手機版 Web App 原型
2. PWA
3. Capacitor 包 iOS / Android
4. 有市場驗證後再考慮原生重寫

## UI Principles

1. 手機優先，iPhone Safari 優先
2. Android Chrome 必須可用
3. 第一版以單一 HTML 或輕量 Web App 優先
4. 不追求炫技
5. 不做複雜社群
6. 不做 AR 風水
7. 不做過重遊戲化
8. 首頁第一眼要有神秘感與信任感

## UX Principles

1. 輸入越少越好
2. 第一版只問生日、星座、關注主題
3. 每日結果要在 30 秒內看懂
4. 每日建議必須可執行
5. AI 聊天入口要明顯
6. 晚上要能回饋今天準不準
7. 不要讓使用者學術語
8. 深度命理術語只放在進階解析

## Wording Principles

中文語氣：

- 像真人命理師
- 像懂你的生活教練
- 溫柔但不空泛
- 有提醒，但不恐嚇
- 有方向，但不保證
- 避免過度神化
- 避免命定論

不要說：

- 你一定會
- 命中注定
- 不做就會出事
- 今天絕對不能
- 這是唯一答案

可以說：

- 今天比較適合
- 你可以先
- 如果你正在猶豫
- 先觀察，再行動
- 這件事值得再多看一天

## Data Principles

每日行動教練文案必須先進 wording database。

不要把大量文案寫死在程式裡。

文案資料要可以：

- 新增
- 修改
- 停用
- 分類
- 標記語氣
- 標記適用情境

第一版可先用 Markdown / CSV / JSON / XLSX。

之後如果要上線，再轉成正式資料庫。

## First Version Scope

第一版包含：

- 今日首頁
- 今日關鍵字
- 今日運勢分數
- 工作 / 感情 / 財運 / 狀態
- 每日塔羅一張牌
- 每日行動建議
- AI 私人命理師聊天入口
- 晚間運勢驗證

第一版不包含：

- AR 風水
- 社群
- 陌生人配對
- 合盤社交
- 複雜紫微命盤
- 守護靈養成
- 付費訂閱
- App Store 上架

## Coding Rules

1. 優先最小可用原型
2. 不過早重構
3. 不過早導入大型框架
4. 手機版視覺優先
5. 保留日後轉 PWA / iOS shell 的可能
6. 重要文案從 Data 讀取或集中管理
7. 不新增功能，除非使用者明確要求

## Release Checklist

每次版本輸出前確認：

- iPhone Safari 可用
- Android Chrome 可用
- 首頁第一屏不爆版
- 今日運勢正常顯示
- 每日行動建議正常顯示
- AI 命理師入口明顯
- 塔羅入口正常
- 清除資料 / 重填流程正常
- 深色背景下文字可讀
- 按鈕在手機上容易點

## Mission

讓使用者每天打開後，得到一個感覺被理解、又能實際行動的答案。

