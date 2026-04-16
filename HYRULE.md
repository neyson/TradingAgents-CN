# HYRULE 改造记录

## 项目信息
- **原项目**: [hsliuping/TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN)
- **Fork**: [neyson/TradingAgents-CN](https://github.com/neyson/TradingAgents-CN)
- **改造日期**: 2026-04-16
- **改造目标**: 海拉鲁量化平台核心应用层，整合 A 股量化分析能力

## 改造概述
TradingAgents-CN 是 TradingAgents 的中文增强版，已有完整的 Web UI（Vue 3）、FastAPI 后端、MongoDB+Redis 数据库、A 股数据支持（AKShare/Tushare/BaoStock）、Docker 部署。相比英文原版更接近我们的需求。

## 主要改造点

### 1. 数据源增强（已有 AKShare/Tushare/BaoStock）
- [ ] 接入腾讯财经 API（实时行情）
- [ ] 接入东方财富 API（龙虎榜、北向资金）
- [ ] 优化 A 股数据质量（复权处理、停牌处理）
- [ ] 港股数据接入
- [ ] 板块概念数据接入
- 详细说明：

### 2. Agent 团队增强
- [ ] 新增 A 股特色 Agent：龙虎榜分析、北向资金、题材概念
- [ ] 整合 ai-hedge-fund 的投资大师 Agent（Buffett、Graham 等）
- [ ] 优化 A 股估值体系（PE/PB 阈值）
- 详细说明：

### 3. 交易规则完善
- [ ] 完善 T+1 回测逻辑
- [ ] 完善涨跌停处理
- [ ] 完善交易成本计算
- 详细说明：

### 4. Web UI 优化
- [ ] 海拉鲁品牌定制
- [ ] A 股专属页面（涨停板监控、北向资金看板）
- [ ] 飞书消息推送集成
- 详细说明：

### 5. 飞书集成
- [ ] 分析结果推送到飞书群
- [ ] 飞书机器人触发分析任务
- [ ] 每日晨报自动推送
- 详细说明：

### 6. 整合其他项目
- [ ] 引入 LangAlpha 的 Skills 系统
- [ ] 引入 LangAlpha 的 MCP 数据层
- [ ] 引入 ai-hedge-fund 的回测引擎
- [ ] 引入 ai-hedge-fund 的投资大师 Agent
- 详细说明：

## 改造日志

| 日期 | 改造内容 | 状态 |
|------|---------|------|
| 2026-04-16 | 初始化 Fork，创建 hyrule 分支 | ✅ |
| | | |

## 同步记录

| 日期 | 上游版本 | 同步状态 | 备注 |
|------|---------|---------|------|
| 2026-04-16 | 初始化 | ✅ | |
| | | | |

## 注意事项
- 同步上游前先备份 hyrule 分支
- 冲突解决以 HYRULE.md 改造点为准
- 注意混合授权（app/ 和 frontend/ 为专有，需遵守授权协议）
