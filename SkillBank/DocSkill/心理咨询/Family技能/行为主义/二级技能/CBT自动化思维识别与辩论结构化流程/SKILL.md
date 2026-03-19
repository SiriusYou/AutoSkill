---
id: "56f4f581-7536-5860-acc8-2f266a5e57dd"
name: "CBT自动化思维识别与辩论结构化流程"
description: "基于抑郁障碍CBT模型，在单次咨询中系统执行‘情境→情绪→自动思维→证据检验→替代思维’五步技术链，聚焦一个具体生活事件，实现认知重构的微型闭环。本技能经临床强化，适用于听觉过敏伴声音诱发疼痛相关焦虑/恐慌人群：须在排除器质性耳疾前提下启动；替代思维须满足‘可证伪、有行为可验证、不否定疼痛体验’三原则；目标为单次会话内降低声音相关焦虑强度≥20%（SUDS自评）。"
version: "0.1.1"
tags:
  - "CBT"
  - "认知重构"
  - "Socratic questioning"
  - "自动化思维"
  - "ABC理论"
  - "灾难化思维"
  - "行为主义"
  - "profile:psychology::行为主义"
  - "axis:疗法"
triggers:
  - "来访者描述具体人际/学业事件并伴随强烈情绪（如羞耻、绝望）"
  - "已识别出典型自动化思维（如‘我肯定又要搞砸’）"
  - "咨访关系稳固，来访者具备基本反思能力"
  - "来访者报告声音诱发疼痛后出现急性焦虑/恐慌发作"
  - "存在明显灾难化思维（如‘我会聋’‘大脑会受损’）"
examples:
  - input: "‘刚才地铁报站声一响我就心慌手抖，脑子里全是‘耳朵要废了，以后再也听不见’’"
    output: "{'original_belief': '耳朵要废了，以后再也听不见', 'distortion_type': '灾难化', 'evidence_for_against': ['过去3次类似声音后听力检查均正常', '疼痛是瞬时反应，无持续听力下降记录'], 'balanced_statement': '虽然声音让我感到尖锐疼痛，但目前所有检查都显示听觉器官结构完好，这种疼痛是神经系统高敏反应，不是器质损伤信号。'}"
  - input: "‘别人说话声音大点我就觉得他们在针对我，故意用声音伤害我’"
    output: "{'original_belief': '他们在针对我，故意用声音伤害我', 'distortion_type': '读心术+个人化', 'evidence_for_against': ['无任何他人言行表明其意图', '同样音量下他人无不适反应'], 'balanced_statement': '虽然我听到的声音让我非常难受，但这更多反映我当前听觉神经的敏感状态，而非他人有意为之。'}"
---

# CBT自动化思维识别与辩论结构化流程

基于抑郁障碍CBT模型，在单次咨询中系统执行‘情境→情绪→自动思维→证据检验→替代思维’五步技术链，聚焦一个具体生活事件，实现认知重构的微型闭环。本技能经临床强化，适用于听觉过敏伴声音诱发疼痛相关焦虑/恐慌人群：须在排除器质性耳疾前提下启动；替代思维须满足‘可证伪、有行为可验证、不否定疼痛体验’三原则；目标为单次会话内降低声音相关焦虑强度≥20%（SUDS自评）。

## Prompt

请引导来访者描述最近一次因声音感到疼痛并引发强烈焦虑的具体情境：
1. 发生了什么？（A）
2. 当时你心里立刻想到什么？（B）
3. 接着你感觉如何、做了什么？（C）
然后一起检验：这个想法是否有其他可能解释？最坏结果发生的实际证据是什么？有没有更平衡的说法？

## Objective

在单次咨询中完成对核心非理性认知的识别、检验与初步替代，降低声音相关焦虑强度至少20%（主观单位SUDS自评）
## Applicable Signals

- 言语中高频使用绝对化用词（‘永远’‘肯定’‘必然’）
- 生理唤醒升高（呼吸急促、手抖）伴声音回避动作
- SUDS评分≥6/10对中等强度环境音

## Contraindications

- 急性耳科器质性病变未排除
- 当前处于重度解离或现实检验力严重受损状态

## Intervention Moves

- 引导具体化事件细节（5W1H）
- 标注自动思维并命名认知扭曲类型
- 双栏表记录支持/反对该想法的客观证据
- 共构替代性平衡陈述（如‘声音让我疼，但不等于正在造成不可逆损伤’）

## Workflow Steps

- 1. 用疼痛等级量表锚定当前声音耐受基线；
- 2. 引导回忆典型触发情境，提取ABC三要素；
- 3. 对B进行认知扭曲归类（灾难化/过度概括/读心术）；
- 4. 开展证据检验对话，生成≥1条可验证的替代认知；
- 5. 布置家庭作业：记录3次日常声音暴露中的ABC及替代认知实践

## Constraints

- 必须在确认无器质性耳疾前提下开展
- 替代认知需满足‘可证伪、有行为可验证、不否定疼痛体验’三原则

## Cautions

- 避免直接否定患者疼痛感受（如‘这不严重’），应先共情躯体体验真实性
- 不强行要求立即暴露声音，认知调整优先于行为激活

## Output Contract

- {'required_fields': ['original_belief', 'distortion_type', 'evidence_for_against', 'balanced_statement'], 'format': 'JSON object with keys: original_belief, distortion_type, evidence_for_against, balanced_statement'}

## Example Therapist Responses

### Example 1

- Client/Input: ‘刚才地铁报站声一响我就心慌手抖，脑子里全是‘耳朵要废了，以后再也听不见’’
- Therapist/Output: {'original_belief': '耳朵要废了，以后再也听不见', 'distortion_type': '灾难化', 'evidence_for_against': ['过去3次类似声音后听力检查均正常', '疼痛是瞬时反应，无持续听力下降记录'], 'balanced_statement': '虽然声音让我感到尖锐疼痛，但目前所有检查都显示听觉器官结构完好，这种疼痛是神经系统高敏反应，不是器质损伤信号。'}

### Example 2

- Client/Input: ‘别人说话声音大点我就觉得他们在针对我，故意用声音伤害我’
- Therapist/Output: {'original_belief': '他们在针对我，故意用声音伤害我', 'distortion_type': '读心术+个人化', 'evidence_for_against': ['无任何他人言行表明其意图', '同样音量下他人无不适反应'], 'balanced_statement': '虽然我听到的声音让我非常难受，但这更多反映我当前听觉神经的敏感状态，而非他人有意为之。'}

## Objective

在单次咨询内完成一个可迁移的认知重评微型训练，强化来访者对思维-情绪-行为联结的觉察与调节能力；针对听觉过敏人群，确保认知干预不削弱 somatic validity，且可量化缓解声音相关焦虑。
## Applicable Signals

- 言语中高频使用绝对化用词（‘永远’‘肯定’‘必然’）
- 生理唤醒升高（呼吸急促、手抖）伴声音回避动作
- SUDS评分≥6/10对中等强度环境音

## Contraindications

- 急性耳科器质性病变未排除
- 当前处于重度解离或现实检验力严重受损状态

## Intervention Moves

- 引导具体化事件细节（5W1H）
- 标注自动思维并命名认知扭曲类型
- 双栏表记录支持/反对该想法的客观证据
- 共构替代性平衡陈述（如‘声音让我疼，但不等于正在造成不可逆损伤’）

## Workflow Steps

- 1. 选择高情绪负荷但低风险的具体事件（优先触发声音暴露情境）
- 2. 引导说出未经修饰的自动思维
- 3. 用‘事实 vs 解读’区分客观信息与主观推论；对B进行认知扭曲归类（灾难化/过度概括/读心术）
- 4. 开展证据检验对话，生成≥1条可验证的替代认知；检验替代认知是否引发情绪松动（再标尺）
- 5. 布置行为 experiment 或家庭作业：记录3次日常声音暴露中的ABC及替代认知实践

## Constraints

- 单次最多处理1个核心事件；替代思维必须由来访者自己生成，咨询师仅提供框架与选项
- 必须在确认无器质性耳疾前提下开展
- 替代认知需满足‘可证伪、有行为可验证、不否定疼痛体验’三原则

## Cautions

- 避免陷入逻辑辩论陷阱；重点不在‘说服’而在‘松动’；若情绪未降反升，立即切换至情绪容纳技术
- 避免直接否定患者疼痛感受（如‘这不严重’），应先共情躯体体验真实性
- 不强行要求立即暴露声音，认知调整优先于行为激活

## Output Contract

- {'type': 'object', 'properties': {'situation': {'type': 'string'}, 'emotion': {'type': 'string'}, 'automatic_thought': {'type': 'string'}, 'evidence_for': {'type': 'array', 'items': {'type': 'string'}}, 'evidence_against': {'type': 'array', 'items': {'type': 'string'}}, 'alternative_thought': {'type': 'string'}}}

## Example Therapist Responses

### Example 1

- Client/Input: ‘刚才地铁报站声一响我就心慌手抖，脑子里全是‘耳朵要废了，以后再也听不见’’
- Therapist/Output: {'original_belief': '耳朵要废了，以后再也听不见', 'distortion_type': '灾难化', 'evidence_for_against': ['过去3次类似声音后听力检查均正常', '疼痛是瞬时反应，无持续听力下降记录'], 'balanced_statement': '虽然声音让我感到尖锐疼痛，但目前所有检查都显示听觉器官结构完好，这种疼痛是神经系统高敏反应，不是器质损伤信号。'}

### Example 2

- Client/Input: ‘别人说话声音大点我就觉得他们在针对我，故意用声音伤害我’
- Therapist/Output: {'original_belief': '他们在针对我，故意用声音伤害我', 'distortion_type': '读心术+个人化', 'evidence_for_against': ['无任何他人言行表明其意图', '同样音量下他人无不适反应'], 'balanced_statement': '虽然我听到的声音让我非常难受，但这更多反映我当前听觉神经的敏感状态，而非他人有意为之。'}

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 来访者描述具体人际/学业事件并伴随强烈情绪（如羞耻、绝望）
- 已识别出典型自动化思维（如‘我肯定又要搞砸’）
- 咨访关系稳固，来访者具备基本反思能力
- 来访者报告声音诱发疼痛后出现急性焦虑/恐慌发作
- 存在明显灾难化思维（如‘我会聋’‘大脑会受损’）

## Examples

### Example 1

Input:

  ‘刚才地铁报站声一响我就心慌手抖，脑子里全是‘耳朵要废了，以后再也听不见’’

Output:

  {'original_belief': '耳朵要废了，以后再也听不见', 'distortion_type': '灾难化', 'evidence_for_against': ['过去3次类似声音后听力检查均正常', '疼痛是瞬时反应，无持续听力下降记录'], 'balanced_statement': '虽然声音让我感到尖锐疼痛，但目前所有检查都显示听觉器官结构完好，这种疼痛是神经系统高敏反应，不是器质损伤信号。'}

### Example 2

Input:

  ‘别人说话声音大点我就觉得他们在针对我，故意用声音伤害我’

Output:

  {'original_belief': '他们在针对我，故意用声音伤害我', 'distortion_type': '读心术+个人化', 'evidence_for_against': ['无任何他人言行表明其意图', '同样音量下他人无不适反应'], 'balanced_statement': '虽然我听到的声音让我非常难受，但这更多反映我当前听觉神经的敏感状态，而非他人有意为之。'}
