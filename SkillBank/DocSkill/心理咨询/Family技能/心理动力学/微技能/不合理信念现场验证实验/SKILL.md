---
id: "c578371b-cd10-5424-a584-bae5115d3db9"
name: "不合理信念现场验证实验"
description: "在咨询中协同求助者设计并实施现场行为实验（如当面询问同伴对其社交表现的真实评价），用实证反馈瓦解其核心不合理信念，建立理性自我认知。"
version: "0.1.0"
tags:
  - "CBT"
  - "行为实验"
  - "认知重构"
  - "现场验证"
  - "心理动力学"
  - "profile:psychology::心理动力学"
  - "axis:疗法"
  - "class:心理动力学"
  - "kind:child"
  - "document_merge_state:active"
  - "canonical:true"
triggers:
  - "求助者表达对他人负面评价的固着性担忧（如'他们觉得我是个怪物'）"
  - "出现可观察的自我贬低语言且缺乏现实依据"
  - "情绪反应强度显著高于实际社交情境的客观风险"
examples:
  - input: "求助者坚信：'只要我开口说话，别人立刻觉得我很奇怪，想远离我。'"
    output: "咨询师邀请两位室友当面回答：'她平时跟你们说话时，有没有让你觉得不自在或想躲开？' 两人均答：'没有，她说话挺自然的，有时还蛮幽默。' 求助者记录：'我以为她们忍着，其实根本没感觉。' 共同形成替代句：'大多数人不会特别注意我说话的样子，更不会因此否定我。'"
    notes: "聚焦可观察行为，回避价值判断类提问"
  - input: "求助者预测：'我发言时一定会发抖，大家会觉得我很懦弱。'"
    output: "咨询师请两位同学回忆最近一次求助者发言场景，问：'当时注意到她身体有明显发抖吗？' 回答：'没注意，只记得她说得挺清楚。' 求助者反思：'我把紧张感放大成所有人都看见了。' 替代句：'我的主观紧张感 ≠ 他人观察到的外显症状。'"
    notes: "用'是否观察到'替代'是否觉得'，降低评价性压力"
---

# 不合理信念现场验证实验

在咨询中协同求助者设计并实施现场行为实验（如当面询问同伴对其社交表现的真实评价），用实证反馈瓦解其核心不合理信念，建立理性自我认知。

## Prompt

与求助者共同选定1–2名信任的同龄人（如同班或同宿舍同学），在求助者在场的情况下，向其直接提问：'当她和你们交谈时，是否表现出脸红、发抖等不自然状态？' 然后引导求助者即时倾听、记录并对比他人反馈与其原有想象的差异；随后协助其识别认知偏差，命名不合理信念（如'他们会嘲笑我'），并共同构建更符合现实的替代性陈述。

## Objective

disconfirm irrational beliefs about social evaluation
## Applicable Signals

- verbalized catastrophic predictions
- avoidance linked to imagined judgment
- low self-efficacy in social appraisal

## Contraindications

- active suicidal ideation or severe dissociation
- lack of baseline rapport or safety agreement
- peer context with known hostility or bullying history

## Intervention Moves

- selecting credible peer informants
- structuring real-time feedback collection
- guided discrepancy analysis
- co-constructing reality-based self-statements

## Workflow Steps

- 1. 协同求助者确认具体不合理信念（如'我说话时他们会讨厌我'）
- 2. 共同选择1–2名关系中性/正向的同龄人作为反馈来源
- 3. 在求助者全程在场前提下，向被选者提出结构化、非诱导性问题
- 4. 引导求助者即时记录他人反馈与自身预期的差异
- 5. 共同命名认知扭曲类型（如读心术、灾难化），并撰写1条简明理性替代句

## Constraints

- 必须确保被访者知情同意且无压力；不得使用录音或书面记录他人评价
- 实验须在安全、私密、可控环境中进行；避免公开场合施加额外羞耻感
- 每次仅聚焦1个核心信念，不叠加多个验证任务

## Cautions

- 警惕求助者将中性反馈曲解为否定（如'她们没说好，就是不好'），需同步处理解释偏差
- 若反馈引发强烈羞耻或退缩，立即暂停并启动情绪调节支持
- 避免让被访者评价求助者的'是否正常'，而聚焦于可观察行为（如'脸红''说话停顿'）

## Output Contract

- {'required_fields': ['identified irrational belief', 'peer feedback verbatim (de-identified)', 'discrepancy noted by client', 'co-created rational alternative statement'], 'validation_rules': ['所有 names, IDs, locations de-identified', 'no clinical diagnosis stated in output', 'rational statement must be testable and behaviorally anchored']}

## Example Therapist Responses

### Example 1

- Client/Input: 求助者坚信：'只要我开口说话，别人立刻觉得我很奇怪，想远离我。'
- Therapist/Output: 咨询师邀请两位室友当面回答：'她平时跟你们说话时，有没有让你觉得不自在或想躲开？' 两人均答：'没有，她说话挺自然的，有时还蛮幽默。' 求助者记录：'我以为她们忍着，其实根本没感觉。' 共同形成替代句：'大多数人不会特别注意我说话的样子，更不会因此否定我。'
- Notes: 聚焦可观察行为，回避价值判断类提问

### Example 2

- Client/Input: 求助者预测：'我发言时一定会发抖，大家会觉得我很懦弱。'
- Therapist/Output: 咨询师请两位同学回忆最近一次求助者发言场景，问：'当时注意到她身体有明显发抖吗？' 回答：'没注意，只记得她说得挺清楚。' 求助者反思：'我把紧张感放大成所有人都看见了。' 替代句：'我的主观紧张感 ≠ 他人观察到的外显症状。'
- Notes: 用'是否观察到'替代'是否觉得'，降低评价性压力

## Objective

disconfirm irrational beliefs about social evaluation
## Applicable Signals

- verbalized catastrophic predictions
- avoidance linked to imagined judgment
- low self-efficacy in social appraisal

## Contraindications

- active suicidal ideation or severe dissociation
- lack of baseline rapport or safety agreement
- peer context with known hostility or bullying history

## Intervention Moves

- selecting credible peer informants
- structuring real-time feedback collection
- guided discrepancy analysis
- co-constructing reality-based self-statements

## Workflow Steps

- 1. 协同求助者确认具体不合理信念（如'我说话时他们会讨厌我'）
- 2. 共同选择1–2名关系中性/正向的同龄人作为反馈来源
- 3. 在求助者全程在场前提下，向被选者提出结构化、非诱导性问题
- 4. 引导求助者即时记录他人反馈与自身预期的差异
- 5. 共同命名认知扭曲类型（如读心术、灾难化），并撰写1条简明理性替代句

## Constraints

- 必须确保被访者知情同意且无压力；不得使用录音或书面记录他人评价
- 实验须在安全、私密、可控环境中进行；避免公开场合施加额外羞耻感
- 每次仅聚焦1个核心信念，不叠加多个验证任务

## Cautions

- 警惕求助者将中性反馈曲解为否定（如'她们没说好，就是不好'），需同步处理解释偏差
- 若反馈引发强烈羞耻或退缩，立即暂停并启动情绪调节支持
- 避免让被访者评价求助者的'是否正常'，而聚焦于可观察行为（如'脸红''说话停顿'）

## Output Contract

- {'required_fields': ['identified irrational belief', 'peer feedback verbatim (de-identified)', 'discrepancy noted by client', 'co-created rational alternative statement'], 'validation_rules': ['All names, IDs, locations de-identified', 'no clinical diagnosis stated in output', 'rational statement must be testable and behaviorally anchored']}

## Example Therapist Responses

### Example 1

- Client/Input: 求助者坚信：'只要我开口说话，别人立刻觉得我很奇怪，想远离我。'
- Therapist/Output: 咨询师邀请两位室友当面回答：'她平时跟你们说话时，有没有让你觉得不自在或想躲开？' 两人均答：'没有，她说话挺自然的，有时还蛮幽默。' 求助者记录：'我以为她们忍着，其实根本没感觉。' 共同形成替代句：'大多数人不会特别注意我说话的样子，更不会因此否定我。'
- Notes: 聚焦可观察行为，回避价值判断类提问

### Example 2

- Client/Input: 求助者预测：'我发言时一定会发抖，大家会觉得我很懦弱。'
- Therapist/Output: 咨询师请两位同学回忆最近一次求助者发言场景，问：'当时注意到她身体有明显发抖吗？' 回答：'没注意，只记得她说得挺清楚。' 求助者反思：'我把紧张感放大成所有人都看见了。' 替代句：'我的主观紧张感 ≠ 他人观察到的外显症状。'
- Notes: 用'是否观察到'替代'是否觉得'，降低评价性压力

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 求助者表达对他人负面评价的固着性担忧（如'他们觉得我是个怪物'）
- 出现可观察的自我贬低语言且缺乏现实依据
- 情绪反应强度显著高于实际社交情境的客观风险

## Examples

### Example 1

Input:

  求助者坚信：'只要我开口说话，别人立刻觉得我很奇怪，想远离我。'

Output:

  咨询师邀请两位室友当面回答：'她平时跟你们说话时，有没有让你觉得不自在或想躲开？' 两人均答：'没有，她说话挺自然的，有时还蛮幽默。' 求助者记录：'我以为她们忍着，其实根本没感觉。' 共同形成替代句：'大多数人不会特别注意我说话的样子，更不会因此否定我。'

Notes:

  聚焦可观察行为，回避价值判断类提问

### Example 2

Input:

  求助者预测：'我发言时一定会发抖，大家会觉得我很懦弱。'

Output:

  咨询师请两位同学回忆最近一次求助者发言场景，问：'当时注意到她身体有明显发抖吗？' 回答：'没注意，只记得她说得挺清楚。' 求助者反思：'我把紧张感放大成所有人都看见了。' 替代句：'我的主观紧张感 ≠ 他人观察到的外显症状。'

Notes:

  用'是否观察到'替代'是否觉得'，降低评价性压力
