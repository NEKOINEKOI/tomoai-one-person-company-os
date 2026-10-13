# TOMOAI 一人公司操作系统

一个给独立创始人、创作者、独立开发者、一人公司用的操作 skill。

大多数商业建议是写给「有资金、有时间、有团队的公司」看的。这个 skill 恰恰相反——一个人，注意力有限，想法太多，真正需要决定的是「下一步做什么」。

让 Agent 不再给泛泛的创业鸡汤，而是像一个实战的业务操盘手：诊断当前阶段，选对模块，给出一个具体的下一步行动。

## 为什么做这个

一人公司通常死于顺序错误，不是死于不够聪明。

先做了再验证。offer 还没想清楚就追流量。流程还没跑通就开始自动化。商业闭环还没搞懂就开始降价。情绪崩溃时做转向决策。

TOMOAI 一人公司操作系统的存在，就是让顺序别乱：

```
验证 → 做最小 offer → 找首批客户 → 定价 → 用 AI 系统化 → 复盘迭代
```

## 五大模块

| 你的情况 | 用哪个模块 |
| --- | --- |
| "这个想法是真需求还是我自己脑补的？" | `idea-validation.md` |
| "最小能测试或卖钱的版本是什么？" | `mvp-templates.md` |
| "我没粉丝，第一批客户从哪来？" | `first-customers.md` |
| "我要的是发布清单，不是空泛的增长建议" | `launch-toolkit.md` |
| "这个 offer 该怎么定价？" | `pricing-model.md` |
| "怎么把流量变成收入和复购？" | `pricing-toolkit.md` |
| "AI 到底该在哪帮我？" | `ai-workflow.md` |
| "哪些 AI 工具和工作流对一人公司有用？" | `ai-toolkit.md` |
| "我是该继续、转向、还是止损？" | `minimalist-review.md` |
| "怎么做一次轻量复盘？" | `review-toolkit.md` |

## 怎么用

跟你的 Agent 说：

```text
用 $tomoai-one-person-company-os 帮我看看这个产品想法值不值得做
```

```text
用 $tomoai-one-person-company-os 帮我设计一个 7 天能卖出去的最小 MVP
```

```text
用 $tomoai-one-person-company-os 帮我找前 20 个付费客户
```

```text
用 $tomoai-one-person-company-os 复盘我现在的业务，决定继续、转向还是止损
```

## 你会拿到什么

根据你的问题，skill 可能产出：

- 当前阶段诊断
- 核心瓶颈诊断
- 验证计划
- MVP 范围
- 首批客户计划
- 定价建议
- AI 工作流地图
- 继续 / 转向 / 止损的复盘结论
- 7 天 / 30 天行动计划

默认产出都是可以直接执行的。帮你想下一步怎么动，不是再攒一个框架。

## 设计理念

这个 skill 用渐进式加载：

- `SKILL.md` 保持精简，只负责路由。
- 详细的业务模块放在 `references/` 里。
- Agent 只读当前问题需要的那个模块。

这样既保持轻量，又有足够的操作深度，能覆盖一人公司从想法到迭代的完整生命周期。

## 文件结构

```
tomoai-one-person-company-os/
  SKILL.md                          # 路由层 + 操作规则
  agents/openai.yaml                # UI 元数据
  references/
    idea-validation.md              # 想法验证与 MVP 设计
    mvp-templates.md                # MVP 模板
    first-customers.md              # 冷启动与首批客户
    launch-toolkit.md              # 发布工具包
    pricing-model.md               # 定价策略与商业闭环
    pricing-toolkit.md             # 定价工具包
    ai-workflow.md                  # AI 工具与自动化工作流
    ai-toolkit.md                   # AI 工具包
    minimalist-review.md            # 极简复盘与迭代
    review-toolkit.md               # 复盘工具包
```

## 安装

支持 Claude Code、Codex、WorkBuddy、Cursor 等所有兼容开放 skill 标准的 Agent：

```bash
git clone https://github.com/NEKOINEKOI/tomoai-one-person-company-os ~/.workbuddy/skills/tomoai-one-person-company-os
```

Agent 不支持 Skill 也没关系，直接把 `tomoai-one-person-company-os/SKILL.md` 贴进对话即可。

## 五条核心原则

1. **先验证，再构建** —— 别花三个月做出来才发现没人要
2. **先跑通一个商业闭环，再追规模** —— 一个能赚钱的闭环 > 十个不赚钱的想法
3. **内容、社群、产品、定价、交付、复盘是一套系统** —— 不是六件孤立的事
4. **AI 是杠杆，不是判断力的替代品** —— 它放大你的能力，不替你做决定
5. **不要在情绪低谷期做重大业务决策** —— 先稳住，再决策

## 许可协议

本项目仅用于**个人学习与研究**，**禁止任何形式的商业使用**。

- ✅ **允许**：个人学习、研究、复制、修改、非商业性分享
- ❌ **禁止**：销售、出租、集成到付费产品、提供有偿服务、任何商业环境使用
- 📋 **要求**：保留原作者署名

详见 [LICENSE](LICENSE)。

---

<div align="center">

**扫码关注公众号「智井AI」**

<img src="https://raw.githubusercontent.com/NEKOINEKOI/tomoai-skills/main/docs/zhijing-ai-qrcode.png" alt="智井AI 公众号二维码" width="240" />

</div>

<div align="center">

Made by [@NEKOINEKOI](https://github.com/NEKOINEKOI)

</div>
