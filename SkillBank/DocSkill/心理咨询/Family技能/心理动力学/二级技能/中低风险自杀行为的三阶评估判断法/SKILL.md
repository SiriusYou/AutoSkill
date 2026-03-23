---
id: "35129496-022b-5a0b-a79c-a031d34853ba"
name: "中低风险自杀行为的三阶评估判断法"
description: "依据行为细节（如分颗拆药而非冲动吞服）、情绪线索（内疚感浮现）、意图稳定性（主动中止并表达放弃）三要素综合判定非冲动型、未遂型自杀行为为中低风险，并明确必须启动持续监测与动态再评估。"
version: "0.1.0"
tags:
  - "自杀风险"
  - "心理动力学评估"
  - "结构化判断"
  - "中低风险"
  - "心理动力学"
  - "profile:psychology::心理动力学"
  - "axis:疗法"
  - "class:心理动力学"
  - "kind:child"
  - "document_merge_state:active"
  - "canonical:true"
triggers:
  - "来访者报告未遂自杀行为但无即刻自伤行动"
  - "行为呈现明显控制性与反思性特征"
  - "咨询中期出现与依恋冲突相关的攻击转向自身"
examples:
  - input: "来访者说：‘我买了头孢，一颗一颗拆开，数到第七颗就停了，后来觉得对不起爸妈，把药倒了。’"
    output: "{'risk_level': 'medium-low', 'evidence_summary': ['行为具控制性（分颗拆药）', '浮现内疚情绪（对不起爸妈）', '意图不稳定（主动中止并处置药物）'], 'monitoring_required': true, 'next_review_within_days': 3}"
    notes: "符合全部三要素，判定中低风险；需3日内复评"
---

# 中低风险自杀行为的三阶评估判断法

依据行为细节（如分颗拆药而非冲动吞服）、情绪线索（内疚感浮现）、意图稳定性（主动中止并表达放弃）三要素综合判定非冲动型、未遂型自杀行为为中低风险，并明确必须启动持续监测与动态再评估。

## Prompt

当来访者报告非冲动型、未遂型自杀行为时，系统评估以下三要素：（1）行为细节：是否呈现计划性/控制性动作（如分次拆药、保留药盒、未一次性服药）；（2）情绪线索：行为过程中或之后是否出现内疚、后悔、恐惧等自我调节性情绪；（3）意图稳定性：是否主动中止行为、寻求帮助或表达放弃意愿。三者同时存在，可初步判定为中低风险，但仍须启动持续监测与动态再评估。

## Objective

对非冲动型、未遂型自杀行为进行结构化风险分级
## Applicable Signals

- 分次操作药物
- 行为后内疚陈述
- 主动中止并透露细节
- 将自杀行为与关系冲突联结

## Contraindications

- 来访者处于急性激越或现实检验严重受损状态
- 存在明确、具体、可执行的再自杀计划
- 有既往高致命性自杀未遂史且本次行为模式高度相似

## Intervention Moves

- 命名情绪线索（如‘你当时感到内疚，这说明你在保护自己’）
- 探索行为背后的客体关系含义（如‘那个不允许你爱好的父母，在那一刻是否也变成了你心里必须服从的声音？’）
- 协同制定简明监测协议（如每周确认一次安全状态、识别早期预警信号）

## Workflow Steps

- 确认行为事实细节（时间、方式、环境、他人在场情况）
- 识别并标注情绪线索（尤其内疚、羞耻、矛盾感等自我调节性情绪）
- 评估意图稳定性（是否主动停止、是否求助、是否表达悔意或希望）
- 整合三要素，给出风险等级判断（中低），同步说明‘需持续监测’为必要条件
- 与来访者共同约定短期安全观察要点及复评节点

## Constraints

- 不替代标准化自杀量表（如C-SSRS），仅作为临床直觉的结构化锚点
- 不用于免除安全预案（如紧急联系人确认、危机热线提醒）
- 不适用于儿童青少年无监护人知情场景

## Cautions

- 避免将‘内疚’简单解读为‘安全信号’——需考察其是否伴随自我惩罚倾向
- 警惕‘分颗拆药’背后可能隐藏的试探性控制幻想（如‘我掌控死亡节奏’）
- 该判断法依赖咨询师对反移情的觉察（如自身愤怒/无力感是否干扰评估）

## Output Contract

- {'risk_level': "string (enum: ['low', 'medium-low', 'medium', 'medium-high', 'high'])", 'evidence_summary': 'array of 3 strings, each mapping to one of the three criteria', 'monitoring_required': 'boolean', 'next_review_within_days': 'integer (1–7)'}

## Example Therapist Responses

### Example 1

- Client/Input: 来访者说：‘我买了头孢，一颗一颗拆开，数到第七颗就停了，后来觉得对不起爸妈，把药倒了。’
- Therapist/Output: {'risk_level': 'medium-low', 'evidence_summary': ['行为具控制性（分颗拆药）', '浮现内疚情绪（对不起爸妈）', '意图不稳定（主动中止并处置药物）'], 'monitoring_required': true, 'next_review_within_days': 3}
- Notes: 符合全部三要素，判定中低风险；需3日内复评

## Objective

对非冲动型、未遂型自杀行为进行结构化风险分级
## Applicable Signals

- 分次操作药物
- 行为后内疚陈述
- 主动中止并透露细节
- 将自杀行为与关系冲突联结

## Contraindications

- 来访者处于急性激越或现实检验严重受损状态
- 存在明确、具体、可执行的再自杀计划
- 有既往高致命性自杀未遂史且本次行为模式高度相似

## Intervention Moves

- 命名情绪线索（如‘你当时感到内疚，这说明你在保护自己’）
- 探索行为背后的客体关系含义（如‘那个不允许你爱好的父母，在那一刻是否也变成了你心里必须服从的声音？’）
- 协同制定简明监测协议（如每周确认一次安全状态、识别早期预警信号）

## Workflow Steps

- 确认行为事实细节（时间、方式、环境、他人在场情况）
- 识别并标注情绪线索（尤其内疚、羞耻、矛盾感等自我调节性情绪）
- 评估意图稳定性（是否主动停止、是否求助、是否表达悔意或希望）
- 整合三要素，给出风险等级判断（中低），同步说明‘需持续监测’为必要条件
- 与来访者共同约定短期安全观察要点及复评节点

## Constraints

- 不替代标准化自杀量表（如C-SSRS），仅作为临床直觉的结构化锚点
- 不用于免除安全预案（如紧急联系人确认、危机热线提醒）
- 不适用于儿童青少年无监护人知情场景

## Cautions

- 避免将‘内疚’简单解读为‘安全信号’——需考察其是否伴随自我惩罚倾向
- 警惕‘分颗拆药’背后可能隐藏的试探性控制幻想（如‘我掌控死亡节奏’）
- 该判断法依赖咨询师对反移情的觉察（如自身愤怒/无力感是否干扰评估）

## Output Contract

- {'risk_level': "string (enum: ['low', 'medium-low', 'medium', 'medium-high', 'high'])", 'evidence_summary': 'array of 3 strings, each mapping to one of the three criteria', 'monitoring_required': 'boolean', 'next_review_within_days': 'integer (1–7)'}

## Example Therapist Responses

### Example 1

- Client/Input: 来访者说：‘我买了头孢，一颗一颗拆开，数到第七颗就停了，后来觉得对不起爸妈，把药倒了。’
- Therapist/Output: {'risk_level': 'medium-low', 'evidence_summary': ['行为具控制性（分颗拆药）', '浮现内疚情绪（对不起爸妈）', '意图不稳定（主动中止并处置药物）'], 'monitoring_required': true, 'next_review_within_days': 3}
- Notes: 符合全部三要素，判定中低风险；需3日内复评

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 来访者报告未遂自杀行为但无即刻自伤行动
- 行为呈现明显控制性与反思性特征
- 咨询中期出现与依恋冲突相关的攻击转向自身

## Examples

### Example 1

Input:

  来访者说：‘我买了头孢，一颗一颗拆开，数到第七颗就停了，后来觉得对不起爸妈，把药倒了。’

Output:

  {'risk_level': 'medium-low', 'evidence_summary': ['行为具控制性（分颗拆药）', '浮现内疚情绪（对不起爸妈）', '意图不稳定（主动中止并处置药物）'], 'monitoring_required': true, 'next_review_within_days': 3}

Notes:

  符合全部三要素，判定中低风险；需3日内复评
