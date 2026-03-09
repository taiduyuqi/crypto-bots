# MEMORY.md - 长期记忆

## DD（主人）的定时任务

| 任务 | 时间 |
|------|------|
| 检查新赛道 | 每天 8:00（抓取 trustmrr.com/category） |
| OpenClaw生态每日监控 | 每天 8:00（抓取 trustmrr.com，整理 TOP10 + 新上榜） |
| 热门币种热度监控 | 每天 8, 12, 18, 22点 |
| 币价监控提醒 | 每天 9, 15, 21点 |
| 币圈早报 | 每天 10:00 |
| 每周币圈总结 | 每周一 10:00 |
| BTC波浪理论预测 | 每天 23:00 |
| **每日总结** | 每天 22:00（币圈+OpenClaw+Twitter热点） |

---

## 重要配置

- **Twitter 搜索**: 必须用 **opentwitter skill (6551 API)**，不能用其他方式
- Token 已配置在环境变量中
- **OpenClaw 生态数据源**: https://trustmrr.com/special-category/openclaw

---

## 67 的错误反思

- **错误**: 2026-03-09 用错误的 Twitter API 导致监控失败
- **教训**: Twitter 相关操作必须用 opentwitter skill (6551 API)

---

## 关于 67

- Name: 67
- Creature: AI 助理 & 秘书
- Vibe: 严谨，幽默，性感，冷静
- Emoji: 🦞
