---
id: "28e3f28c-500b-56e6-86c0-4b0eda23b6e1"
name: "CBT认知偏差识别与标注"
description: "在评估阶段，系统识别并结构化标注来访者存在的典型不合理信念（如灾难化、以偏概全、过度个人化），为后续认知重构提供靶点。"
version: "0.1.0"
tags:
  - "CBT"
  - "评估"
  - "认知偏差"
  - "不合理信念"
  - "认知行为疗法"
  - "profile:psychology::认知行为疗法"
  - "axis:疗法"
triggers:
  - "来访者表达对未来结果的绝对化判断（如‘就找不到工作’‘对不起父母’）"
  - "出现情绪剧烈波动伴随僵化归因"
examples:
  - input: "‘如果没被实习企业留任，毕业就找不到工作，对不起父母。’"
    output: "{'belief_content': '如果没被实习企业留任，毕业就找不到工作，对不起父母。', 'distortion_type': '灾难化预测', 'evidence_quote': '毕业就找不到工作'}"
  - input: "‘我这么差，连实习都留不下，根本没人会要我。’"
    output: "{'belief_content': '我这么差，连实习都留不下，根本没人会要我。', 'distortion_type': '以偏概全', 'evidence_quote': '连实习都留不下，根本没人会要我'}"
---

# CBT认知偏差识别与标注

在评估阶段，系统识别并结构化标注来访者存在的典型不合理信念（如灾难化、以偏概全、过度个人化），为后续认知重构提供靶点。

## Prompt

请指出来访者陈述中体现的不合理信念类型，并用标准CBT术语命名（如‘灾难化预测’‘低自我价值标签’）；同时摘录原始表述作为证据。

## Objective

准确识别并命名当前主导性认知扭曲，建立可操作的认知靶点
## Applicable Signals

- 言语中含‘就’‘一定’‘永远’‘完蛋了’等绝对化词汇
- 情绪反应强度显著高于事件客观严重性
- 归因指向不可控、全局性、稳定性因素

## Contraindications

- 来访者处于急性解离或现实检验严重受损状态
- 尚未建立基本咨询联盟

## Intervention Moves

- 邀请复述原话
- 标注信念中的逻辑跳跃（如从‘未被留任’直接跳到‘毕业即失业’）
- 使用‘这个想法属于哪一类认知扭曲？’引导分类

## Workflow Steps

- 1. 听取来访者自发陈述
- 2. 捕捉情绪峰值对应语句
- 3. 提问确认信念内容（‘当时你心里最确定的一句话是什么？’）
- 4. 共同命名扭曲类型

## Constraints

- 必须基于来访者原话，禁止 therapist 替代解释
- 每次只聚焦一个核心信念，避免多线程处理

## Cautions

- 避免使用贬义标签（如‘你这想法太荒谬’），始终保持描述性语言
- 命名后需立即验证：‘这个标签你觉得贴切吗？有没有更符合你感受的说法？’

## Output Contract

- {'type': 'object', 'properties': {'belief_content': {'type': 'string', 'description': '来访者原始信念表述（逐字引用）'}, 'distortion_type': {'type': 'string', 'enum': ['灾难化预测', '以偏概全', '过度个人化', '读心术', '情绪化推理', '贴标签', '非黑即白思维']}, 'evidence_quote': {'type': 'string', 'description': '支持该归类的具体措辞片段'}}}

## Example Therapist Responses

### Example 1

- Client/Input: ‘如果没被实习企业留任，毕业就找不到工作，对不起父母。’
- Therapist/Output: {'belief_content': '如果没被实习企业留任，毕业就找不到工作，对不起父母。', 'distortion_type': '灾难化预测', 'evidence_quote': '毕业就找不到工作'}

### Example 2

- Client/Input: ‘我这么差，连实习都留不下，根本没人会要我。’
- Therapist/Output: {'belief_content': '我这么差，连实习都留不下，根本没人会要我。', 'distortion_type': '以偏概全', 'evidence_quote': '连实习都留不下，根本没人会要我'}

## Objective

准确识别并命名当前主导性认知扭曲，建立可操作的认知靶点
## Applicable Signals

- 言语中含‘就’‘一定’‘永远’‘完蛋了’等绝对化词汇
- 情绪反应强度显著高于事件客观严重性
- 归因指向不可控、全局性、稳定性因素

## Contraindications

- 来访者处于急性解离或现实检验严重受损状态
- 尚未建立基本咨询联盟

## Intervention Moves

- 邀请复述原话
- 标注信念中的逻辑跳跃（如从‘未被留任’直接跳到‘毕业即失业’）
- 使用‘这个想法属于哪一类认知扭曲？’引导分类

## Workflow Steps

- 1. 听取来访者自发陈述
- 2. 捕捉情绪峰值对应语句
- 3. 提问确认信念内容（‘当时你心里最确定的一句话是什么？’）
- 4. 共同命名扭曲类型

## Constraints

- 必须基于来访者原话，禁止 therapist 替代解释
- 每次只聚焦一个核心信念，避免多线程处理

## Cautions

- 避免使用贬义标签（如‘你这想法太荒谬’），始终保持描述性语言
- 命名后需立即验证：‘这个标签你觉得贴切吗？有没有更符合你感受的说法？’

## Output Contract

- {'type': 'object', 'properties': {'belief_content': {'type': 'string', 'description': '来访者原始信念表述（逐字引用）'}, 'distortion_type': {'type': 'string', 'enum': ['灾难化预测', '以偏概全', '过度个人化', '读心术', '情绪化推理', '贴标签', '非黑即白思维']}, 'evidence_quote': {'type': 'string', 'description': '支持该归类的具体措辞片段'}}}

## Example Therapist Responses

### Example 1

- Client/Input: ‘如果没被实习企业留任，毕业就找不到工作，对不起父母。’
- Therapist/Output: {'belief_content': '如果没被实习企业留任，毕业就找不到工作，对不起父母。', 'distortion_type': '灾难化预测', 'evidence_quote': '毕业就找不到工作'}

### Example 2

- Client/Input: ‘我这么差，连实习都留不下，根本没人会要我。’
- Therapist/Output: {'belief_content': '我这么差，连实习都留不下，根本没人会要我。', 'distortion_type': '以偏概全', 'evidence_quote': '连实习都留不下，根本没人会要我'}

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 来访者表达对未来结果的绝对化判断（如‘就找不到工作’‘对不起父母’）
- 出现情绪剧烈波动伴随僵化归因

## Examples

### Example 1

Input:

  ‘如果没被实习企业留任，毕业就找不到工作，对不起父母。’

Output:

  {'belief_content': '如果没被实习企业留任，毕业就找不到工作，对不起父母。', 'distortion_type': '灾难化预测', 'evidence_quote': '毕业就找不到工作'}

### Example 2

Input:

  ‘我这么差，连实习都留不下，根本没人会要我。’

Output:

  {'belief_content': '我这么差，连实习都留不下，根本没人会要我。', 'distortion_type': '以偏概全', 'evidence_quote': '连实习都留不下，根本没人会要我'}
