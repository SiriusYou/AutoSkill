---
id: "409bba1f-76c7-531f-bfda-7258acdceaa2"
name: "Systematic Desensitization Protocol for Test Anxiety"
description: "A structured, stepwise exposure protocol combining relaxation training and client-generated hierarchical imaginal exposure to reduce conditioned anxiety responses to exam-related stimuli. Used when cognitive insight is present but situational anxiety persists despite understanding its irrationality."
version: "0.1.1"
tags:
  - "behaviorism"
  - "exposure"
  - "relaxation"
  - "test_anxiety"
  - "systematic_desensitization"
  - "imaginal_exposure"
  - "行为主义"
  - "profile:psychology::行为主义"
  - "axis:疗法"
  - "class:行为主义"
  - "kind:child"
  - "document_merge_state:active"
  - "canonical:true"
triggers:
  - "Client reports intact insight but unchanged test anxiety"
  - "Anxiety is tied to specific exam-related stimuli (e.g., entering考场, seeing math problems)"
  - "Client can reliably self-report anxiety on 0–100 scale"
  - "Client reports intact insight but persistent test-specific anxiety"
  - "Client can reliably self-report subjective anxiety level (e.g., 0–100 scale)"
examples:
  - input: "Client says: 'I know it's irrational, but my heart races just thinking about sitting at the desk.'"
    output: "Therapist responds: 'Let’s ground that feeling — can you take three slow breaths with me? Then, picture just walking into the room — nothing else yet. What’s your number from 0 to 100?'"
    notes: "Anchor to concrete sensory detail before scaling."
  - input: "Client reports SUDS=65 during level-3 imagery and shoulders tense."
    output: "Therapist responds: 'Let’s pause — bring attention back to your breath. Squeeze and release your fists twice. Now gently return to the doorway scene — no need to go further yet.'"
    notes: "Reinforce relaxation before reattempting same level."
---

# Systematic Desensitization Protocol for Test Anxiety

A structured, stepwise exposure protocol combining relaxation training and client-generated hierarchical imaginal exposure to reduce conditioned anxiety responses to exam-related stimuli. Used when cognitive insight is present but situational anxiety persists despite understanding its irrationality.

## Prompt

1. Confirm client is relaxed (e.g., via diaphragmatic breathing or progressive muscle relaxation). 2. Co-construct an anxiety hierarchy (1–6) of exam-related stimuli, ordered from least to most anxiety-provoking. 3. Guide client to imagine level-1 stimulus while maintaining relaxation; assess subjective anxiety (0–100 scale). 4. Only advance to next level when self-reported anxiety ≤40 and physical relaxation is sustained. 5. Repeat imaginal exposure per level until criterion is met. 6. Assign homework: daily relaxation + imaginal rehearsal of highest mastered level, progressing toward level 6.

## Objective

Reduce conditioned anxiety response to exam stimuli via graduated imaginal exposure under relaxation
## Applicable Signals

- Client verbalizes understanding of irrational beliefs but shows no reduction in situational anxiety
- Client endorses vivid, controllable mental imagery of exam scenes
- Client demonstrates ability to self-monitor physiological arousal

## Contraindications

- Acute suicidal ideation or panic disorder with agoraphobia present
- Client cannot achieve or maintain relaxed state
- Anxiety is primarily driven by unresolved trauma or identity-level meaning conflicts

## Intervention Moves

- relaxation_induction
- hierarchy_coconstruction
- graded_imaginal_exposure
- anxiety_scaling
- relaxation_maintenance_check

## Workflow Steps

- Assess current relaxation capacity and recent practice adherence
- Review and refine 6-level anxiety hierarchy anchored to concrete exam stimuli
- Induce deep relaxation using standardized script (e.g., PMR or breath focus)
- Guide imaginal exposure to level-1 stimulus; pause to assess SUDS (0–100) and physical tension
- Repeat exposure until SUDS ≤40 AND observable relaxation (e.g., steady breathing, soft jaw) is maintained
- Progress sequentially only upon criterion met; do not skip levels
- End session with reinforcement of mastery and assignment of level-appropriate homework

## Constraints

- Must use consistent 0–100 anxiety scale across sessions
- No exposure without verified relaxation baseline
- Hierarchy must be stimulus-specific—not abstract (e.g., 'seeing the math problem' not 'failing')

## Cautions

- Avoid rushing progression — repeated failure at one level indicates need to adjust relaxation method or hierarchy granularity
- Monitor for subtle avoidance cues (e.g., vague language, laughter, topic shift) during imagery
- Do not interpret imagery content; focus solely on anxiety intensity and somatic state

## Output Contract

- Client independently imagines level-6 exam scenario with self-reported anxiety ≤40/100 while demonstrating sustained physical relaxation (e.g., regular breathing, relaxed facial muscles, no fidgeting)

## Example Therapist Responses

### Example 1

- Client/Input: Client says: 'I know it's irrational, but my heart races just thinking about sitting at the desk.'
- Therapist/Output: Therapist responds: 'Let’s ground that feeling — can you take three slow breaths with me? Then, picture just walking into the room — nothing else yet. What’s your number from 0 to 100?'
- Notes: Anchor to concrete sensory detail before scaling.

### Example 2

- Client/Input: Client reports SUDS=65 during level-3 imagery and shoulders tense.
- Therapist/Output: Therapist responds: 'Let’s pause — bring attention back to your breath. Squeeze and release your fists twice. Now gently return to the doorway scene — no need to go further yet.'
- Notes: Reinforce relaxation before reattempting same level.

## Objective

Reduce conditioned anxiety response to exam stimuli via graduated imaginal exposure under relaxed state
## Applicable Signals

- Client verbalizes understanding of irrational beliefs but shows no reduction in situational anxiety
- Client endorses vivid, controllable mental imagery of exam scenes
- Client demonstrates ability to self-monitor physiological arousal
- Verbal report of 'knowing it's irrational but still feeling anxious'
- Physiological signs of anticipatory anxiety before exams (e.g., sweating, nausea, insomnia)
- Anxiety localized to exam context—not generalized

## Contraindications

- Acute suicidal ideation or panic disorder with agoraphobia present
- Client cannot achieve or maintain relaxed state
- Anxiety is primarily driven by unresolved trauma or identity-level meaning conflicts
- Client unable to sustain focused imagination for >30 seconds
- No established relaxation anchor established in prior session

## Intervention Moves

- relaxation_induction
- hierarchy_coconstruction
- graded_imaginal_exposure
- anxiety_scaling
- relaxation_maintenance_check

## Workflow Steps

- Assess current relaxation capacity and recent practice adherence
- Review and refine 6-level anxiety hierarchy anchored to concrete exam stimuli
- Induce deep relaxation using standardized script (e.g., PMR or breath focus)
- Guide imaginal exposure to level-1 stimulus; pause to assess SUDS (0–100) and physical tension
- Repeat exposure until SUDS ≤40 AND observable relaxation (e.g., steady breathing, soft jaw) is maintained
- Progress sequentially only upon criterion met; do not skip levels
- Assess relaxation capacity and anxiety scaling fidelity
- Co-build 6-point exam-related anxiety hierarchy
- Reinforce relaxation response until stable
- Conduct imaginal exposure from Level 1 upward, pausing at ≤40/100
- Anchor success with somatic calm (breath, posture, tension release)
- Assign targeted homework integrating relaxation + imagery + cognitive review

## Constraints

- Must use consistent 0–100 anxiety scale across sessions
- No exposure without verified relaxation baseline
- Hierarchy must be stimulus-specific—not abstract (e.g., 'seeing the math problem' not 'failing')
- Must be delivered within a session where relaxation has already been practiced and stabilized
- Imagery must be client-generated—not therapist-scripted—to preserve ecological validity
- No level advancement without dual confirmation: subjective rating ≤40/100 AND objective calm

## Cautions

- Avoid rushing progression — repeated failure at one level indicates need to adjust relaxation method or hierarchy granularity
- Monitor for subtle avoidance cues (e.g., vague language, laughter, topic shift) during imagery
- Do not interpret imagery content; focus solely on anxiety intensity and somatic state
- Avoid rushing hierarchy progression—even with high motivation; regression is therapeutic, not failure
- Do not combine with intense cognitive debate *during* exposure—separate phases are essential

## Output Contract

- Client independently imagines level-6 exam scenario with self-reported anxiety ≤40/100 while demonstrating sustained physical relaxation (e.g., regular breathing, relaxed facial muscles, no fidgeting)

## Example Therapist Responses

### Example 1

- Client/Input: Client says: 'I know it's irrational, but my heart races just thinking about sitting at the desk.'
- Therapist/Output: Therapist responds: 'Let’s ground that feeling — can you take three slow breaths with me? Then, picture just walking into the room — nothing else yet. What’s your number from 0 to 100?'
- Notes: Anchor to concrete sensory detail before scaling.

### Example 2

- Client/Input: Client reports SUDS=65 during level-3 imagery and shoulders tense.
- Therapist/Output: Therapist responds: 'Let’s pause — bring attention back to your breath. Squeeze and release your fists twice. Now gently return to the doorway scene — no need to go further yet.'
- Notes: Reinforce relaxation before reattempting same level.

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- Client reports intact insight but unchanged test anxiety
- Anxiety is tied to specific exam-related stimuli (e.g., entering考场, seeing math problems)
- Client can reliably self-report anxiety on 0–100 scale
- Client reports intact insight but persistent test-specific anxiety
- Client can reliably self-report subjective anxiety level (e.g., 0–100 scale)

## Examples

### Example 1

Input:

  Client says: 'I know it's irrational, but my heart races just thinking about sitting at the desk.'

Output:

  Therapist responds: 'Let’s ground that feeling — can you take three slow breaths with me? Then, picture just walking into the room — nothing else yet. What’s your number from 0 to 100?'

Notes:

  Anchor to concrete sensory detail before scaling.

### Example 2

Input:

  Client reports SUDS=65 during level-3 imagery and shoulders tense.

Output:

  Therapist responds: 'Let’s pause — bring attention back to your breath. Squeeze and release your fists twice. Now gently return to the doorway scene — no need to go further yet.'

Notes:

  Reinforce relaxation before reattempting same level.
