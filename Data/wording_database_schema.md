# Wording Database Schema

每日行動教練需要先建立 wording database。

第一版可以先用 Markdown 或試算表管理，之後再轉 JSON / database。

## Table: daily_action

| Field | Description |
| --- | --- |
| id | 唯一編號，例如 `work_001` |
| status | `active` / `paused` / `draft` |
| category | 工作、感情、財運、健康、人際、自我成長 |
| situation | 適用情境，例如「適合保守」、「適合主動」、「情緒容易急」 |
| energy_level | `low` / `medium` / `high` |
| tone | 溫柔提醒、直接建議、安定陪伴、行動教練 |
| keyword | 今日關鍵字，例如「順勢而為」 |
| title | 建議標題 |
| short_advice | 首頁顯示的短句 |
| action_task | 今天可以做的一個具體行動 |
| avoid | 今天建議避免的行為 |
| why | 白話原因，不要太玄 |
| cta_question | 引導使用者問 AI 命理師的問題 |
| tags | 方便篩選，例如 `work,decision,calm` |
| updated_at | 更新日期 |
| notes | 內部備註 |

## Example

| Field | Content |
| --- | --- |
| id | `work_001` |
| status | `active` |
| category | 工作 |
| situation | 適合保守 |
| energy_level | `medium` |
| tone | 溫柔提醒 |
| keyword | 先觀察 |
| title | 先觀察，再出手 |
| short_advice | 今天不一定適合硬碰硬。先聽完對方的意思，你會更容易找到突破口。 |
| action_task | 重要訊息晚 30 分鐘再回。 |
| avoid | 避免在情緒上來時立刻做決定。 |
| why | 今天的能量比較適合整理資訊，不適合正面衝突。 |
| cta_question | 要不要我幫你看今天適不適合談這件事？ |
| tags | `work,decision,communication` |
| updated_at | `2026-06-11` |
| notes | 首頁可用 |

## Suggested Categories

- 工作
- 感情
- 財運
- 健康
- 人際
- 自我成長
- 家庭
- 情緒
- 決策

## First Content Goal

第一批先做 150-300 條。

每個主要類別至少 20 條。

