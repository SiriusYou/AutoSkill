---
id: "9a289993-cd58-5507-8dd7-acb0c137ba83"
name: "RET自助表填写与反馈修正"
description: "指导求助者填写RET自助表（事件A、信念B、结果C），并在下一次咨询中检查、讨论并修正其不合理信念B的表述。该技能 supports CBT框架内的认知重构。"
version: "0.1.0"
tags:
  - "CBT"
  - "cognitive_restructuring"
  - "homework_feedback"
  - "RET"
  - "人本-存在主义"
  - "profile:psychology::人本_存在主义"
  - "axis:疗法"
  - "kind:parent"
triggers:
  - "client has completed prior psychoeducation on ABC model"
  - "client shows readiness to self-reflect on beliefs"
  - "session is in middle phase of CBT protocol"
examples:
  - input: "求助者填写：A=期末考试前夜失眠；C=心慌、复习中断；B=我必须考第一，否则就完了。"
    output: "修订后B：'我非常希望考出好成绩，但即使没达到目标，也不代表我失败或没有价值。'"
    notes: "聚焦将'必须'转为'希望'，'否则就完了'解构为'后果可承受且非终极'"
---

# RET自助表填写与反馈修正

指导求助者填写RET自助表（事件A、信念B、结果C），并在下一次咨询中检查、讨论并修正其不合理信念B的表述。该技能 supports CBT框架内的认知重构。

## Prompt

1. 确认求助者已理解ABC模型基本结构；2. 提供标准化RET自助表模板（含A/B/C三栏）；3. 引导求助者用具体、可观察的语言填写A（事件）和C（情绪/行为结果）；4. 聚焦识别B中绝对化（必须/应该）、以偏概全（总是/从不）、灾难化等非理性特征；5. 下次咨询时逐项核对，用苏格拉底式提问澄清模糊表述，协助将‘我必须考第一’修正为‘我希望考好，但成绩不定义我的价值’等更弹性表述。

## Objective

facilitate identification and revision of irrational beliefs using structured self-report
## Applicable Signals

- client verbalizes awareness of own thinking patterns
- client completes written reflection without significant avoidance or blank responses
- client uses absolutist language (e.g., 'must', 'should', 'always') when describing expectations

## Contraindications

- client lacks literacy or cognitive capacity for written self-report
- acute crisis or severe depression impairs reflective capacity
- no prior introduction to RET or ABC theory

## Intervention Moves

- content_reaction_on_B
- socratic_questioning_on_belief_elasticity
- reframing_absolutist_language
- collaborative_belief_reformulation

## Workflow Steps

- 1. Introduce RET自助表 purpose and structure
- 2. Model one A-B-C example with non-clinical content
- 3. Assign as between-session task with clear deadline
- 4. At next session: review each column, validate effort, then focus revision on B
- 5. Co-construct revised B-statement that preserves intent but reduces rigidity

## Constraints

- Must not proceed without confirmed ABC conceptual understanding
- B-column entries must be verbatim client language before revision
- No interpretation or labeling of beliefs by therapist prior to client's own articulation

## Cautions

- Avoid correcting B too quickly—prioritize client's ownership of insight
- If multiple B-statements appear, select only 1–2 highest-impact ones for revision per session
- Do not accept vague B (e.g., 'I think bad things') without prompting for specificity

## Output Contract

- Completed RET自助表 with at least one clearly articulated irrational belief (e.g., 'I must get top grades') and therapist-verified correction of its absolutist language into a flexible, preference-based alternative.

## Example Therapist Responses

### Example 1

- Client/Input: 求助者填写：A=期末考试前夜失眠；C=心慌、复习中断；B=我必须考第一，否则就完了。
- Therapist/Output: 修订后B：'我非常希望考出好成绩，但即使没达到目标，也不代表我失败或没有价值。'
- Notes: 聚焦将'必须'转为'希望'，'否则就完了'解构为'后果可承受且非终极'

## Objective

facilitate identification and revision of irrational beliefs using structured self-report
## Applicable Signals

- client verbalizes awareness of own thinking patterns
- client completes written reflection without significant avoidance or blank responses
- client uses absolutist language (e.g., 'must', 'should', 'always') when describing expectations

## Contraindications

- client lacks literacy or cognitive capacity for written self-report
- acute crisis or severe depression impairs reflective capacity
- no prior introduction to RET or ABC theory

## Intervention Moves

- content_reaction_on_B
- socratic_questioning_on_belief_elasticity
- reframing_absolutist_language
- collaborative_belief_reformulation

## Workflow Steps

- 1. Introduce RET自助表 purpose and structure
- 2. Model one A-B-C example with non-clinical content
- 3. Assign as between-session task with clear deadline
- 4. At next session: review each column, validate effort, then focus revision on B
- 5. Co-construct revised B-statement that preserves intent but reduces rigidity

## Constraints

- Must not proceed without confirmed ABC conceptual understanding
- B-column entries must be verbatim client language before revision
- No interpretation or labeling of beliefs by therapist prior to client's own articulation

## Cautions

- Avoid correcting B too quickly—prioritize client's ownership of insight
- If multiple B-statements appear, select only 1–2 highest-impact ones for revision per session
- Do not accept vague B (e.g., 'I think bad things') without prompting for specificity

## Output Contract

- Completed RET自助表 with at least one clearly articulated irrational belief (e.g., 'I must get top grades') and therapist-verified correction of its absolutist language into a flexible, preference-based alternative.

## Example Therapist Responses

### Example 1

- Client/Input: 求助者填写：A=期末考试前夜失眠；C=心慌、复习中断；B=我必须考第一，否则就完了。
- Therapist/Output: 修订后B：'我非常希望考出好成绩，但即使没达到目标，也不代表我失败或没有价值。'
- Notes: 聚焦将'必须'转为'希望'，'否则就完了'解构为'后果可承受且非终极'

## 子技能目录
- [Socratic Debate on Irrational Beliefs](心理咨询/Family技能/人本-存在主义/微技能/Socratic Debate on Irrational Beliefs/SKILL.md) ｜ 适用：Use guided questioning to challenge absolutist and overgeneralized beliefs (e.g., 'must', 'should', 'always', 'never'), helping client detect logical flaws, empirical inconsistencies, and functional consequences of their beliefs.

## 选用规则（微技能目录）
- 当目标、阶段或方法更接近 `Socratic Debate on Irrational Beliefs` 时，优先调用它。 线索：client has identified a specific irrational belief in RET table, client expresses openness to examining belief validity, therapist observes emotional activation linked to belief, CBT, RET

## Files

- `references/children_manifest.json`
- `references/children_map.md`
- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- client has completed prior psychoeducation on ABC model
- client shows readiness to self-reflect on beliefs
- session is in middle phase of CBT protocol

## Examples

### Example 1

Input:

  求助者填写：A=期末考试前夜失眠；C=心慌、复习中断；B=我必须考第一，否则就完了。

Output:

  修订后B：'我非常希望考出好成绩，但即使没达到目标，也不代表我失败或没有价值。'

Notes:

  聚焦将'必须'转为'希望'，'否则就完了'解构为'后果可承受且非终极'
