---
id: "b1c3dc15-58df-51ac-94a3-7b1ee3e740ac"
name: "CBT家庭作业布置：认知-行为双轨任务"
description: "在CBT咨询中，系统布置两类家庭作业：认知类（反思不合理信念影响）与行为类（腹式呼吸放松训练），形成认知-行为协同干预闭环。"
version: "0.1.0"
tags:
  - "CBT"
  - "homework"
  - "cognitive monitoring"
  - "relaxation training"
  - "认知行为疗法"
  - "profile:psychology::认知行为疗法"
  - "axis:疗法"
triggers:
  - "完成ABC领悟后进入技能巩固阶段"
  - "求助者有可操作的身体觉察基础"
  - "需强化咨询内外一致性"
examples:
  - input: "我总担心明天开会说错话，心跳加快，手心出汗。"
    output: "Cognitive task: 'What's the worst thing that could happen if I say something awkward? How likely is it? What's a more balanced view?'\\nBehavioral task: 'Practice 4-2-6 breathing before bed, then try once before tomorrow's meeting.'"
    notes: "Links cognitive content directly to somatic cue"
---

# CBT家庭作业布置：认知-行为双轨任务

在CBT咨询中，系统布置两类家庭作业：认知类（反思不合理信念影响）与行为类（腹式呼吸放松训练），形成认知-行为协同干预闭环。

## Prompt

为了把今天讨论的内容真正用起来，请完成两项小练习：① 晚上花5分钟写下今天最困扰你的一件事，再写出你当时的想法，以及这个想法如何影响了你的情绪和行为；② 睡前做3分钟腹式呼吸（吸气4秒→屏息2秒→呼气6秒），并在白天情绪上升时主动使用。

## Objective

增强求助者对认知-情绪-behavior联结的现实觉察，并提供即时生理调节工具
## Applicable Signals

- willingness to try small experiments
- report of somatic anxiety symptoms
- repeated emotional escalation in daily life

## Contraindications

- respiratory condition contraindicating breath-holding
- severe dissociation impairing interoceptive awareness

## Intervention Moves

- prescribing dual-domain task
- modeling breath timing
- normalizing homework resistance

## Workflow Steps

- 1. Explain rationale: 'Thoughts shape feelings, but body signals also feed back to mind'
- 2. Demonstrate abdominal breathing with count guidance
- 3. Co-create realistic timing (e.g., 'start with one bedtime session')
- 4. Preempt barriers: 'If you forget, just notice that thought—and that’s data too'

## Constraints

- Homework must be time-bound (<10 min/day) and concrete; avoid open-ended journaling without scaffolding

## Cautions

- Never assign breathwork without checking for panic history or trauma-related breath aversion

## Output Contract

- {'written_cognitive_reflection_submitted': True, 'breath_practice_attempted_at_least_once': True}

## Example Therapist Responses

### Example 1

- Client/Input: 我总担心明天开会说错话，心跳加快，手心出汗。
- Therapist/Output: Cognitive task: 'What's the worst thing that could happen if I say something awkward? How likely is it? What's a more balanced view?'\nBehavioral task: 'Practice 4-2-6 breathing before bed, then try once before tomorrow's meeting.'
- Notes: Links cognitive content directly to somatic cue

## Objective

增强求助者对认知-情绪-behavior联结的现实觉察，并提供即时生理调节工具
## Applicable Signals

- willingness to try small experiments
- report of somatic anxiety symptoms
- repeated emotional escalation in daily life

## Contraindications

- respiratory condition contraindicating breath-holding
- severe dissociation impairing interoceptive awareness

## Intervention Moves

- prescribing dual-domain task
- modeling breath timing
- normalizing homework resistance

## Workflow Steps

- 1. Explain rationale: 'Thoughts shape feelings, but body signals also feed back to mind'
- 2. Demonstrate abdominal breathing with count guidance
- 3. Co-create realistic timing (e.g., 'start with one bedtime session')
- 4. Preempt barriers: 'If you forget, just notice that thought—and that’s data too'

## Constraints

- Homework must be time-bound (<10 min/day) and concrete; avoid open-ended journaling without scaffolding

## Cautions

- Never assign breathwork without checking for panic history or trauma-related breath aversion

## Output Contract

- {'written_cognitive_reflection_submitted': True, 'breath_practice_attempted_at_least_once': True}

## Example Therapist Responses

### Example 1

- Client/Input: 我总担心明天开会说错话，心跳加快，手心出汗。
- Therapist/Output: Cognitive task: 'What's the worst thing that could happen if I say something awkward? How likely is it? What's a more balanced view?'\nBehavioral task: 'Practice 4-2-6 breathing before bed, then try once before tomorrow's meeting.'
- Notes: Links cognitive content directly to somatic cue

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 完成ABC领悟后进入技能巩固阶段
- 求助者有可操作的身体觉察基础
- 需强化咨询内外一致性

## Examples

### Example 1

Input:

  我总担心明天开会说错话，心跳加快，手心出汗。

Output:

  Cognitive task: 'What's the worst thing that could happen if I say something awkward? How likely is it? What's a more balanced view?'\nBehavioral task: 'Practice 4-2-6 breathing before bed, then try once before tomorrow's meeting.'

Notes:

  Links cognitive content directly to somatic cue
