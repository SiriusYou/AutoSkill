---
id: "92258943-4f58-52f2-bdcb-5bf567e67bfb"
name: "抑郁初访转诊沟通脚本"
description: "将精神科转诊建议转化为来访者可接受、去污名化、具操作性的临床沟通策略。"
version: "0.1.0"
tags:
  - "CBT"
  - "医教协同"
  - "去污名化"
  - "转诊沟通"
  - "认知行为疗法"
  - "profile:psychology::认知行为疗法"
  - "axis:疗法"
triggers:
  - "确认中度及以上抑郁症状"
  - "SCL-90抑郁分≥2.5"
  - "存在明显生理性症状（失眠/厌食/精力枯竭）"
examples:
  - input: "来访者说：‘我只是心情不好，吃药太夸张了。’"
    output: "‘心情不好背后可能有大脑化学物质的变化，就像血糖低会心慌一样自然。药不是改变性格，是帮身体先稳住——这样咱们下次聊‘怎么重建生活节奏’时，你会更有力气。’"
    notes: "用生理类比消解道德化解读"
---

# 抑郁初访转诊沟通脚本

将精神科转诊建议转化为来访者可接受、去污名化、具操作性的临床沟通策略。

## Prompt

使用三段式表达：1）正常化（‘很多抑郁症朋友都会经历类似的身体和情绪变化，就像感冒发烧需要看内科一样’）；2）必要性（‘药物能帮大脑神经递质更快恢复平衡，让后续谈话更有效’）；3）行动支持（‘我可以帮你查附近三甲医院精神科放号时间，或陪你第一次挂号’）。

## Objective

提升转诊依从性，降低病耻感，强化治疗联盟
## Applicable Signals

- 来访者否认‘生病’概念
- 对‘吃药’表现出强烈抵触
- 将情绪问题归因为‘意志薄弱’

## Contraindications

- 来访者已规律服药并稳定复诊
- 明确拒绝任何医疗介入且无风险

## Intervention Moves

- 类比解释
- 生理机制简述
- 提供具体支持选项

## Workflow Steps

- 正常化→必要性→行动支持

## Constraints

- 不承诺疗效（如‘吃了就好’）
- 不贬低心理咨询作用（如‘你这得靠药，谈话没用’）

## Cautions

- 避免使用‘精神病’‘疯’等标签词
- 不将转诊等同于‘你很严重’的评判

## Output Contract

- {'referral_accepted': 'boolean', 'support_offered': 'string'}

## Example Therapist Responses

### Example 1

- Client/Input: 来访者说：‘我只是心情不好，吃药太夸张了。’
- Therapist/Output: ‘心情不好背后可能有大脑化学物质的变化，就像血糖低会心慌一样自然。药不是改变性格，是帮身体先稳住——这样咱们下次聊‘怎么重建生活节奏’时，你会更有力气。’
- Notes: 用生理类比消解道德化解读

## Objective

提升转诊依从性，降低病耻感，强化治疗联盟
## Applicable Signals

- 来访者否认‘生病’概念
- 对‘吃药’表现出强烈抵触
- 将情绪问题归因为‘意志薄弱’

## Contraindications

- 来访者已规律服药并稳定复诊
- 明确拒绝任何医疗介入且无风险

## Intervention Moves

- 类比解释
- 生理机制简述
- 提供具体支持选项

## Workflow Steps

- 正常化→必要性→行动支持

## Constraints

- 不承诺疗效（如‘吃了就好’）
- 不贬低心理咨询作用（如‘你这得靠药，谈话没用’）

## Cautions

- 避免使用‘精神病’‘疯’等标签词
- 不将转诊等同于‘你很严重’的评判

## Output Contract

- {'referral_accepted': 'boolean', 'support_offered': 'string'}

## Example Therapist Responses

### Example 1

- Client/Input: 来访者说：‘我只是心情不好，吃药太夸张了。’
- Therapist/Output: ‘心情不好背后可能有大脑化学物质的变化，就像血糖低会心慌一样自然。药不是改变性格，是帮身体先稳住——这样咱们下次聊‘怎么重建生活节奏’时，你会更有力气。’
- Notes: 用生理类比消解道德化解读

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 确认中度及以上抑郁症状
- SCL-90抑郁分≥2.5
- 存在明显生理性症状（失眠/厌食/精力枯竭）

## Examples

### Example 1

Input:

  来访者说：‘我只是心情不好，吃药太夸张了。’

Output:

  ‘心情不好背后可能有大脑化学物质的变化，就像血糖低会心慌一样自然。药不是改变性格，是帮身体先稳住——这样咱们下次聊‘怎么重建生活节奏’时，你会更有力气。’

Notes:

  用生理类比消解道德化解读
