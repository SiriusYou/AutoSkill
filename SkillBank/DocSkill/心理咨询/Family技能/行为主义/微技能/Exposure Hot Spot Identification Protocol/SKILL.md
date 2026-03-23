---
id: "c19b9bf9-e74f-5c23-8066-787732eba64e"
name: "Exposure Hot Spot Identification Protocol"
description: "A therapist micro-skill to identify, label, and flag high-arousal moments ('hot spots') within a trauma narrative during imaginal exposure for later targeted processing."
version: "0.1.0"
tags:
  - "imaginal exposure"
  - "PTSD"
  - "trauma processing"
  - "SUDS"
  - "行为主义"
  - "profile:psychology::行为主义"
  - "axis:疗法"
  - "class:行为主义"
  - "kind:child"
  - "document_merge_state:active"
  - "canonical:true"
triggers:
  - "Client pauses unusually long (>5 sec) during memory narration"
  - "Client displays acute somatic response (sweating, tearfulness, voice breaking) without prompting"
  - "SUDS spikes ≥30 points within one narrative clause"
examples:
  - input: "Client pauses 8 seconds after saying 'The truck hits us on the back left side door...'"
    output: "Therapist notes in chart: 'Hot spot: \"truck hits back left door — son’s seat\"', no verbal comment"
    notes: "Pause exceeds 5 sec; somatic signs present (sweating, tearful); SUDS rose from 100→70 mid-pause — qualifies as hot spot."
  - input: "Client says 'My son was sitting there' and begins sobbing uncontrollably, SUDS jumps from 60 to 95"
    output: "Therapist writes: 'Hot spot: \"son was sitting there\"', then says gently: 'That part came up strongly — we’ll come back to it.'"
    notes: "SUDS Δ = 35; acute somatic response; therapist names only briefly and future-oriented to avoid re-traumatizing."
---

# Exposure Hot Spot Identification Protocol

A therapist micro-skill to identify, label, and flag high-arousal moments ('hot spots') within a trauma narrative during imaginal exposure for later targeted processing.

## Prompt

While conducting imaginal exposure, observe for three objective behavioral/physiological markers: (1) unprovoked pause >5 seconds, (2) acute somatic response (e.g., sweating, tearfulness, voice breaking), or (3) SUDS spike ≥30 points within one narrative clause. When any occurs, silently note the exact phrase or timestamp in session notes as a hot spot (e.g., 'truck hits left door — son’s seat'). Only name it aloud if client is stable and ready for meta-cognitive reflection; otherwise, withhold labeling to preserve exposure flow.

## Objective

Systematically detect and document narrative segments that elicit disproportionate distress or physiological reactivity to prioritize in subsequent sessions.
## Applicable Signals

- unprompted pause >5 sec
- sweating/tearfulness/voice break
- SUDS Δ ≥30 in one clause

## Contraindications

- Client is narrating calmly with stable SUDS
- Therapist has not yet established baseline SUDS anchors
- Client explicitly resists labeling or revisiting parts of memory

## Intervention Moves

- silent timestamp/phrase notation
- optional verbal naming only if client shows readiness for meta-cognition

## Workflow Steps

- Observe for ≥1 applicable signal during exposure
- Confirm signal is not prompted by therapist interruption
- Record precise narrative phrase or timestamp as hot spot in notes
- Withhold verbal labeling unless client demonstrates cognitive stability and openness

## Constraints

- Must occur *during* active imaginal exposure
- Requires pre-established SUDS scale anchoring
- No interpretation or reframing permitted at this step

## Cautions

- Do not interrupt exposure flow to label; delay naming until natural pause or post-exposure debrief
- Avoid premature meta-cognitive framing if client is still in state-dependent arousal

## Output Contract

- A timestamped or verbatim-quoted hot spot annotation in session notes (e.g., 'truck hits back left door — son’s seat'), with optional real-time verbal naming only if client is cognitively accessible and consents to reflection.

## Example Therapist Responses

### Example 1

- Client/Input: Client pauses 8 seconds after saying 'The truck hits us on the back left side door...'
- Therapist/Output: Therapist notes in chart: 'Hot spot: "truck hits back left door — son’s seat"', no verbal comment
- Notes: Pause exceeds 5 sec; somatic signs present (sweating, tearful); SUDS rose from 100→70 mid-pause — qualifies as hot spot.

### Example 2

- Client/Input: Client says 'My son was sitting there' and begins sobbing uncontrollably, SUDS jumps from 60 to 95
- Therapist/Output: Therapist writes: 'Hot spot: "son was sitting there"', then says gently: 'That part came up strongly — we’ll come back to it.'
- Notes: SUDS Δ = 35; acute somatic response; therapist names only briefly and future-oriented to avoid re-traumatizing.

## Objective

Systematically detect and document narrative segments that elicit disproportionate distress or physiological reactivity to prioritize in subsequent sessions.
## Applicable Signals

- unprompted pause >5 sec
- sweating/tearfulness/voice break
- SUDS Δ ≥30 in one clause

## Contraindications

- Client is narrating calmly with stable SUDS
- Therapist has not yet established baseline SUDS anchors
- Client explicitly resists labeling or revisiting parts of memory

## Intervention Moves

- silent timestamp/phrase notation
- optional verbal naming only if client shows readiness for meta-cognition

## Workflow Steps

- Observe for ≥1 applicable signal during exposure
- Confirm signal is not prompted by therapist interruption
- Record precise narrative phrase or timestamp as hot spot in notes
- Withhold verbal labeling unless client demonstrates cognitive stability and openness

## Constraints

- Must occur *during* active imaginal exposure
- Requires pre-established SUDS scale anchoring
- No interpretation or reframing permitted at this step

## Cautions

- Do not interrupt exposure flow to label; delay naming until natural pause or post-exposure debrief
- Avoid premature meta-cognitive framing if client is still in state-dependent arousal

## Output Contract

- A timestamped or verbatim-quoted hot spot annotation in session notes (e.g., 'truck hits back left door — son’s seat'), with optional real-time verbal naming only if client is cognitively accessible and consents to reflection.

## Example Therapist Responses

### Example 1

- Client/Input: Client pauses 8 seconds after saying 'The truck hits us on the back left side door...'
- Therapist/Output: Therapist notes in chart: 'Hot spot: "truck hits back left door — son’s seat"', no verbal comment
- Notes: Pause exceeds 5 sec; somatic signs present (sweating, tearful); SUDS rose from 100→70 mid-pause — qualifies as hot spot.

### Example 2

- Client/Input: Client says 'My son was sitting there' and begins sobbing uncontrollably, SUDS jumps from 60 to 95
- Therapist/Output: Therapist writes: 'Hot spot: "son was sitting there"', then says gently: 'That part came up strongly — we’ll come back to it.'
- Notes: SUDS Δ = 35; acute somatic response; therapist names only briefly and future-oriented to avoid re-traumatizing.

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- Client pauses unusually long (>5 sec) during memory narration
- Client displays acute somatic response (sweating, tearfulness, voice breaking) without prompting
- SUDS spikes ≥30 points within one narrative clause

## Examples

### Example 1

Input:

  Client pauses 8 seconds after saying 'The truck hits us on the back left side door...'

Output:

  Therapist notes in chart: 'Hot spot: "truck hits back left door — son’s seat"', no verbal comment

Notes:

  Pause exceeds 5 sec; somatic signs present (sweating, tearful); SUDS rose from 100→70 mid-pause — qualifies as hot spot.

### Example 2

Input:

  Client says 'My son was sitting there' and begins sobbing uncontrollably, SUDS jumps from 60 to 95

Output:

  Therapist writes: 'Hot spot: "son was sitting there"', then says gently: 'That part came up strongly — we’ll come back to it.'

Notes:

  SUDS Δ = 35; acute somatic response; therapist names only briefly and future-oriented to avoid re-traumatizing.
