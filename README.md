# mckinsey-12-prompts

> 价值 $115,500+ 的 12 个顶级商业咨询提示词系统，帮你省下请麦肯锡的钱

12 个提示词覆盖 4 大模块，互相交叉验证，形成完整战略决策链。

## 核心框架

```
模块一：宏观扫描与市场洞察（上帝视角）
  1. 麦肯锡 — 市场规模估算 TAM/SAM/SOM
  2. 尼尔森 — 消费趋势预测雷达
  3. 埃森哲 — 数字化颠覆风险评估

模块二：竞争格局与企业战略（知己知彼）
  4. 贝恩 — 竞争格局图谱
  5. 哈佛商业评论 — SWOT 深度剖析
  6. 德勤 — 行业基准测试
  7. Forrester — 新市场进入可行性

模块三：客户体验与品牌营销（以客户为中心）
  8. BCG — 客户细分引擎
  9. 凯度 — 品牌定位审计
  10. 麦肯锡 — 客户旅程映射

模块四：产品变现与增长落地（转化为现金流）
  11. 高盛 — 定价策略模型
  12. Gartner — GTM 市场进入策略
```

## 交叉验证网络

```
TAM → 竞争格局 → 市场进入 → GTM
趋势 → 颠覆评估 → SWOT → 定价
客户细分 → 品牌定位 → 客户旅程
基准测试 → 验证所有模块的假设
```

12 个提示词不是独立的，它们之间有数据流动和交叉验证关系。执行多模块时自动对比数据一致性。

## 安装

```bash
# Claude Code / Codex / Hermes
npx skills add mastercodeai/mckinsey-12-prompts

# 或手动
git clone https://github.com/mastercodeai/mckinsey-12-prompts.git
cp -r mckinsey-12-prompts ~/.claude/skills/
```

## 使用

```
# 单模块
帮我做市场规模分析，我的商业构想是 XX

# 多模块交叉分析（推荐）
我想进入 XX 市场，帮我做个全面分析

# 全链路战略分析
帮我做一个完整的商业战略分析
```

## 12 个提示词价值

| 来源 | 提示词 | 传统估值 |
|------|--------|---------|
| 麦肯锡 | TAM/SAM/SOM 市场规模 | $8,000 |
| 尼尔森 | 消费趋势预测 | $10,000 |
| 埃森哲 | 颠覆风险评估 | $15,000 |
| 贝恩 | 竞争格局图谱 | $5,000 |
| 哈佛商业评论 | SWOT 深度剖析 | $3,000 |
| 德勤 | 行业基准测试 | $15,000 |
| Forrester | 市场进入可行性 | $20,000 |
| BCG | 客户细分 | $7,500 |
| 凯度 | 品牌定位审计 | $9,000 |
| 麦肯锡 | 客户旅程映射 | $5,000 |
| 高盛 | 定价策略 | $6,000 |
| Gartner | GTM 策略 | $12,000 |
| **总计** | | **$115,500+** |

## License

MIT

---

## 更多AI实战工具

这个项目是 **零一AI编程出海** 开源工具链的一部分。

### 4个开源Skill，覆盖学习、决策、商业分析、知识管理

| 项目 | 功能 | 安装 |
|------|------|------|
| [ai-learn-any-skill](https://github.com/mastercodeai/ai-learn-any-skill) | 5步AI学习闭环，SMART+SQ3R+费曼+KISS | `npx skills add mastercodeai/ai-learn-any-skill` |
| [thinking-7-frameworks](https://github.com/mastercodeai/thinking-7-frameworks) | 7个顶级思维框架，马斯克/芒格/贝索斯同款 | `npx skills add mastercodeai/thinking-7-frameworks` |
| [mckinsey-12-prompts](https://github.com/mastercodeai/mckinsey-12-prompts) | 12个商业咨询提示词，价值$115,500 | `npx skills add mastercodeai/mckinsey-12-prompts` |
| [books-skills](https://github.com/mastercodeai/books-skills) | 66本书蒸馏的AI知识库，8大领域 | `hermes skills install mastercodeai/books-skills` |

### 关注公众号「零一AI编程出海」

回复「**工具包**」免费获取《AI Agent Skill 实战手册》PDF，包含4个项目的完整使用指南和实战案例。

### License

MIT
