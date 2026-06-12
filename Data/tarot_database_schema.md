# Tarot Database Schema

FortuneCoach v1.0 的塔羅資料庫。

來源檔：

- `Data/tarot_cards_v1_0.json`

App 載入檔：

- `App/assets/data/tarot_cards_v1_0.js`

牌面圖檔：

- `App/assets/tarot/*.svg`

## Table: tarot_cards

| Field | Description |
| --- | --- |
| id | 唯一編號，例如 `major_17_the-star` |
| arcana | `major` / `minor` |
| suit | 小牌組中文，只有 minor 有值 |
| suit_id | 小牌組代號：`wands`、`cups`、`swords`、`pentacles` |
| rank | 小牌階級中文，只有 minor 有值 |
| number | 大牌編號或小牌排序 |
| name_zh | 中文牌名 |
| name_en | 英文牌名 |
| keyword | 今日關鍵字 |
| daily_message | 首頁/塔羅頁使用的白話訊息 |
| action_hint | 今日可執行建議 |
| caution | 溫和提醒，避免恐嚇或命定論 |
| image | App 端使用的牌面 SVG 路徑 |
| symbol | 牌面圖案生成用符號 |

## v1.0 Rules

- 共 78 張牌。
- 每張牌都必須有 `image`。
- 抽今日塔羅時必須顯示對應牌面圖。
- 文案語氣要像真人命理師與生活教練，不保證預測。
- 不使用恐嚇式語氣。
