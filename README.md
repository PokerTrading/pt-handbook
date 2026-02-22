# Poker Trading · 策略手册

> 把交易变成一场有规则的牌局。

👉 **[full-strategy-v4.4.0.md](full-strategy-v4.4.0.md)** — 编译版全书（一个文件读完所有内容）

## 这是什么

Poker Trading 是一套基于 Volume Profile + 拍卖市场理论的完整交易决策系统。
它用德州扑克的语言重新定义交易流程——选桌、读牌、下注、止损、下桌，每一步都有规则。

## 目录

| 章节 | 主题 | 文件 |
|------|------|------|
| 前言 | 策略定位与适用范围 | [ch0](chapters/ch0-preface.md) |
| 第一章 | 新世界 · 拍卖理论与VP基础 | [ch1](chapters/ch1-world.md) |
| 第二章 | 工具箱 · 三大工具详解 | [ch2](chapters/ch2-tools.md) |
| 第三章 | 坐哪桌 · 桌风+偏见+共振 | [ch3](chapters/ch3-table-read.md) |
| 第四章 | 等发牌 · 信号识别与验牌 | [ch4](chapters/ch4-signal.md) |
| 第五章 | 牌好吗 · 牌型+牌力+纹理 | [ch5](chapters/ch5-hand.md) |
| 第六章 | 算笔账 · 甜点位+SL+TP+R:R | [ch6](chapters/ch6-math.md) |
| 第七章 | 怎么打 · 仓位+入场+四街管理 | [ch7](chapters/ch7-play.md) |
| 第八章 | 活下来 · 风控+熔断+心态 | [ch8](chapters/ch8-survive.md) |
| 第九章 | 你的第一手牌 · 五大实战案例 | [ch9](chapters/ch9-walkthrough.md) |
| 进阶 | 极简牌谱 | [ch10](chapters/ch10-minimal.md) |

**核心参考文档：**
- [Model Overview](core/model-overview.md) — 一页纸总览
- [术语表](core/glossary.md) — Poker Trading ↔ 交易术语对照
- [牌局配置](core/game-setup.md) — 品种×牌桌最佳实践
- [速查卡包](core/quick-cards.md) — 实盘速查

## 核心概念

| 扑克术语 | 交易含义 |
|---------|---------|
| 牌桌 | 时间周期（波段/短线/日内/分时段） |
| 桌风 | 趋势方向（Flow颜色 + VA迁移） |
| 发牌 | 边界信号（AC突破 / RE拒绝 / Excess） |
| 牌力 | 信号质量（AA/KK/AK/AQ） |
| 下注 | 入场（前置/分街） |
| 三组 | 仓位管理（安全组/价值组/贪婪组） |
| 止损 | SL（结构止损 / 数学止损） |

## 已验证品种

黄金(XAUUSD) · 白银(XAGUSD) · BTC · ETH

> Volume Profile 数据充足的品种均可适用

## 新手起步

1. 读 ch0 前言，了解这套系统的定位
2. 按顺序读 ch1-ch8
3. 读 ch9 看完整案例
4. 用 AQ 级仓位开始前 100 笔训练（Ch8§8.13）
5. 100 笔后看规则遵守率，不看盈亏

## 版本

**v4.4.0** · 全书3061行 · 73文件

---

⚠️ 本策略仅供学习参考，不构成投资建议。交易有风险，盈亏自负。
