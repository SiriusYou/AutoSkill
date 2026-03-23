---
id: "592c48dd-573b-5d92-a52d-03ac86a21c79"
name: "SUDS-Guided Exposure Pacing"
description: "A micro-intervention where the therapist uses real-time SUDS ratings to calibrate pacing, validate distress, and decide whether to continue, pause, or repeat segments of imaginal exposure."
version: "0.1.0"
tags:
  - "imaginal exposure"
  - "SUDS"
  - "distress regulation"
  - "behavioral pacing"
  - "行为主义"
  - "profile:psychology::行为主义"
  - "axis:疗法"
  - "class:行为主义"
  - "kind:child"
  - "document_merge_state:active"
  - "canonical:true"
triggers:
  - "Client provides a SUDS rating ≥70 mid-exposure"
  - "Client pauses or shows physiological arousal (sweating, tearfulness)"
  - "Therapist observes incongruence between reported SUDS and behavioral cues"
examples:
  - input: "Client: 'The truck hits us on the back left side door... (pauses, sweating)'"
    output: "Therapist: 'What’s your SUDS right now?'"
    notes: "SUDS elicitation triggered by pause + physiological cue"
  - input: "Client: '100.'"
    output: "Therapist: 'That’s completely expected at this part — let’s stay right here for 30 more seconds, then check again.'"
    notes: "Normalization + time-bound continuation directive"
  - input: "Client: '70.'"
    output: "Therapist: 'I know how hard that was — you did a great job. Are you ready to try that part again?'"
    notes: "Validation + explicit invitation to repeat"
---

# SUDS-Guided Exposure Pacing

A micro-intervention where the therapist uses real-time SUDS ratings to calibrate pacing, validate distress, and decide whether to continue, pause, or repeat segments of imaginal exposure.

## Prompt

Elicit SUDS mid-exposure; interpret the value in context of expected distress trajectory; normalize it verbally; then explicitly state the next behavioral step (e.g., 'stay here for 30 more seconds', 'let’s pause and ground', or 'try that segment again') — all while maintaining empathic presence and safety framing.

## Objective

Anchor exposure delivery to client’s subjective distress level to maintain therapeutic window and prevent overwhelm.
## Applicable Signals

- SUDS ≥70 during memory narration
- physiological signs of arousal (tearfulness, sweating, shallow breathing)
- narrative pause longer than 5 seconds without prompting

## Contraindications

- Client refuses SUDS self-reporting
- Client is dissociated or non-responsive
- SUDS scale has not been previously calibrated with the client

## Intervention Moves

- eliciting SUDS with open timing ('What’s your SUDS right now?')
- normalizing the rating ('That’s expected at this point')
- linking rating to action ('You’re at 100 — let’s stay here for 30 more seconds before checking again')

## Workflow Steps

- 1. Elicit current SUDS rating using standardized 0–100 scale
- 2. Acknowledge and normalize the rating in relation to exposure phase
- 3. Observe behavioral and physiological cues for congruence
- 4. Verbally name the rating and explicitly state the next micro-action (continue, pause, repeat, or ground)
- 5. Confirm client’s capacity to proceed (e.g., 'Are you ready to keep going?')

## Constraints

- Must occur only after SUDS scale has been introduced and practiced in prior session(s)
- SUDS check must be timed mid-narrative—not only at start/end
- No interpretation beyond normalization and action-linking; avoid reassurance or premature reframing

## Cautions

- Avoid interpreting SUDS as 'progress' or 'failure'; treat it solely as pacing data
- Do not override client’s expressed inability to continue, even if SUDS is <70
- If SUDS drops rapidly (<30 sec), verify grounding status before proceeding

## Output Contract

- Therapist names the SUDS value, normalizes it, and explicitly links next action — and client resumes narrative or confirms readiness.

## Example Therapist Responses

### Example 1

- Client/Input: Client: 'The truck hits us on the back left side door... (pauses, sweating)'
- Therapist/Output: Therapist: 'What’s your SUDS right now?'
- Notes: SUDS elicitation triggered by pause + physiological cue

### Example 2

- Client/Input: Client: '100.'
- Therapist/Output: Therapist: 'That’s completely expected at this part — let’s stay right here for 30 more seconds, then check again.'
- Notes: Normalization + time-bound continuation directive

### Example 3

- Client/Input: Client: '70.'
- Therapist/Output: Therapist: 'I know how hard that was — you did a great job. Are you ready to try that part again?'
- Notes: Validation + explicit invitation to repeat

## Objective

Anchor exposure delivery to client’s subjective distress level to maintain therapeutic window and prevent overwhelm.
## Applicable Signals

- SUDS ≥70 during memory narration
- physiological signs of arousal (tearfulness, sweating, shallow breathing)
- narrative pause longer than 5 seconds without prompting

## Contraindications

- Client refuses SUDS self-reporting
- Client is dissociated or non-responsive
- SUDS scale has not been previously calibrated with the client

## Intervention Moves

- eliciting SUDS with open timing ('What’s your SUDS right now?')
- normalizing the rating ('That’s expected at this point')
- linking rating to action ('You’re at 100 — let’s stay here for 30 more seconds before checking again')

## Workflow Steps

- 1. Elicit current SUDS rating using standardized 0–100 scale
- 2. Acknowledge and normalize the rating in relation to exposure phase
- 3. Observe behavioral and physiological cues for congruence
- 4. Verbally name the rating and explicitly state the next micro-action (continue, pause, repeat, or ground)
- 5. Confirm client’s capacity to proceed (e.g., 'Are you ready to keep going?')

## Constraints

- Must occur only after SUDS scale has been introduced and practiced in prior session(s)
- SUDS check must be timed mid-narrative—not only at start/end
- No interpretation beyond normalization and action-linking; avoid reassurance or premature reframing

## Cautions

- Avoid interpreting SUDS as 'progress' or 'failure'; treat it solely as pacing data
- Do not override client’s expressed inability to continue, even if SUDS is <70
- If SUDS drops rapidly (<30 sec), verify grounding status before proceeding

## Output Contract

- Therapist names the SUDS value, normalizes it, and explicitly links next action — and client resumes narrative or confirms readiness.

## Example Therapist Responses

### Example 1

- Client/Input: Client: 'The truck hits us on the back left side door... (pauses, sweating)'
- Therapist/Output: Therapist: 'What’s your SUDS right now?'
- Notes: SUDS elicitation triggered by pause + physiological cue

### Example 2

- Client/Input: Client: '100.'
- Therapist/Output: Therapist: 'That’s completely expected at this part — let’s stay right here for 30 more seconds, then check again.'
- Notes: Normalization + time-bound continuation directive

### Example 3

- Client/Input: Client: '70.'
- Therapist/Output: Therapist: 'I know how hard that was — you did a great job. Are you ready to try that part again?'
- Notes: Validation + explicit invitation to repeat

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- Client provides a SUDS rating ≥70 mid-exposure
- Client pauses or shows physiological arousal (sweating, tearfulness)
- Therapist observes incongruence between reported SUDS and behavioral cues

## Examples

### Example 1

Input:

  Client: 'The truck hits us on the back left side door... (pauses, sweating)'

Output:

  Therapist: 'What’s your SUDS right now?'

Notes:

  SUDS elicitation triggered by pause + physiological cue

### Example 2

Input:

  Client: '100.'

Output:

  Therapist: 'That’s completely expected at this part — let’s stay right here for 30 more seconds, then check again.'

Notes:

  Normalization + time-bound continuation directive

### Example 3

Input:

  Client: '70.'

Output:

  Therapist: 'I know how hard that was — you did a great job. Are you ready to try that part again?'

Notes:

  Validation + explicit invitation to repeat
