---
id: "37a3e288-3b0f-547b-ba8b-25425a395b6b"
name: "CBT自动化思维识别引导微技能"
description: "在CBT稳定改变阶段，针对来访者难以区分情绪、认知、自动化思维与事实的问题，采用渐进式提问与情境锚定技术，协助其逐层识别三要素（触发情境-自动思维-情绪反应）"
version: "0.1.0"
tags:
  - "CBT"
  - "自动化思维"
  - "识别训练"
  - "渐进引导"
  - "认知行为疗法"
  - "profile:psychology::认知行为疗法"
  - "axis:疗法"
triggers:
  - "来访者混淆情绪与认知"
  - "无法区分自动化思维与客观事实"
  - "咨询进入CBT稳定改变阶段"
examples:
  - input: "Q同学说：‘我这次小组汇报肯定又搞砸了，大家肯定觉得我很差劲。’"
    output: "自动化思维：‘我肯定搞砸了’‘大家肯定觉得我很差劲’；情绪：焦虑、羞耻；情境：刚结束小组汇报"
    notes: "不纠正‘肯定’，先标记为自动化思维样本"
  - input: "来访者说：‘我一说话就脸红，说明我特别没用。’"
    output: "自动化思维：‘我一说话就脸红→我特别没用’；情绪：尴尬、自我贬低；情境：课堂发言后"
    notes: "需拆解隐含的中间信念链"
---

# CBT自动化思维识别引导微技能

在CBT稳定改变阶段，针对来访者难以区分情绪、认知、自动化思维与事实的问题，采用渐进式提问与情境锚定技术，协助其逐层识别三要素（触发情境-自动思维-情绪反应）

## Prompt

请回想刚才提到的那个让你感到[具体情绪]的情境。当时发生了什么？你心里第一时间闪过了什么想法？这个想法出现时，身体和情绪有什么反应？

## Objective

提升来访者对自动化思维的觉察与区分能力
## Applicable Signals

- 言语模糊如‘我就是不行’
- 情绪反应远超事件强度
- 频繁使用绝对化用语

## Contraindications

- 急性危机状态
- 严重解离或现实检验受损

## Intervention Moves

- 情境回溯提问
- 情绪命名确认
- 思维捕捉复述
- 事实核查对比

## Workflow Steps

- 1. 锚定具体情境事件
- 2. 命名即时情绪体验
- 3. 捕捉未加反思的首念
- 4. 区分‘我想’与‘事实是’

## Constraints

- 必须基于来访者真实生活事件
- 每次只聚焦一个微情境
- 避免解释性语言，坚持描述性反馈

## Cautions

- 不可代来访者定义思维内容
- 警惕将 therapist 解读误作来访者自动化思维

## Output Contract

- {'recognized_automated_thought': 'string', 'linked_emotion': 'string', 'context_event_summary': 'string'}

## Example Therapist Responses

### Example 1

- Client/Input: Q同学说：‘我这次小组汇报肯定又搞砸了，大家肯定觉得我很差劲。’
- Therapist/Output: 自动化思维：‘我肯定搞砸了’‘大家肯定觉得我很差劲’；情绪：焦虑、羞耻；情境：刚结束小组汇报
- Notes: 不纠正‘肯定’，先标记为自动化思维样本

### Example 2

- Client/Input: 来访者说：‘我一说话就脸红，说明我特别没用。’
- Therapist/Output: 自动化思维：‘我一说话就脸红→我特别没用’；情绪：尴尬、自我贬低；情境：课堂发言后
- Notes: 需拆解隐含的中间信念链

## Objective

提升来访者对自动化思维的觉察与区分能力
## Applicable Signals

- 言语模糊如‘我就是不行’
- 情绪反应远超事件强度
- 频繁使用绝对化用语

## Contraindications

- 急性危机状态
- 严重解离或现实检验受损

## Intervention Moves

- 情境回溯提问
- 情绪命名确认
- 思维捕捉复述
- 事实核查对比

## Workflow Steps

- 1. 锚定具体情境事件
- 2. 命名即时情绪体验
- 3. 捕捉未加反思的首念
- 4. 区分‘我想’与‘事实是’

## Constraints

- 必须基于来访者真实生活事件
- 每次只聚焦一个微情境
- 避免解释性语言，坚持描述性反馈

## Cautions

- 不可代来访者定义思维内容
- 警惕将 therapist 解读误作来访者自动化思维

## Output Contract

- {'recognized_automated_thought': 'string', 'linked_emotion': 'string', 'context_event_summary': 'string'}

## Example Therapist Responses

### Example 1

- Client/Input: Q同学说：‘我这次小组汇报肯定又搞砸了，大家肯定觉得我很差劲。’
- Therapist/Output: 自动化思维：‘我肯定搞砸了’‘大家肯定觉得我很差劲’；情绪：焦虑、羞耻；情境：刚结束小组汇报
- Notes: 不纠正‘肯定’，先标记为自动化思维样本

### Example 2

- Client/Input: 来访者说：‘我一说话就脸红，说明我特别没用。’
- Therapist/Output: 自动化思维：‘我一说话就脸红→我特别没用’；情绪：尴尬、自我贬低；情境：课堂发言后
- Notes: 需拆解隐含的中间信念链

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 来访者混淆情绪与认知
- 无法区分自动化思维与客观事实
- 咨询进入CBT稳定改变阶段

## Examples

### Example 1

Input:

  Q同学说：‘我这次小组汇报肯定又搞砸了，大家肯定觉得我很差劲。’

Output:

  自动化思维：‘我肯定搞砸了’‘大家肯定觉得我很差劲’；情绪：焦虑、羞耻；情境：刚结束小组汇报

Notes:

  不纠正‘肯定’，先标记为自动化思维样本

### Example 2

Input:

  来访者说：‘我一说话就脸红，说明我特别没用。’

Output:

  自动化思维：‘我一说话就脸红→我特别没用’；情绪：尴尬、自我贬低；情境：课堂发言后

Notes:

  需拆解隐含的中间信念链
