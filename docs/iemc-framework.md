# IEMC Framework

## Introduction

IEMC stands for Inteligencia Emocional Multimodal Cultural. It is a research framework for interpreting emotion, intent, and narrative meaning from multiple human communication channels while explicitly accounting for cultural context.

The framework is not a single model and not a proprietary scoring system. It is a public conceptual structure for research, documentation, synthetic examples, annotation design, and future benchmarks.

## Problem

Many AI systems interpret emotion as a direct mapping from a signal to a label:

- Raised voice means anger.
- Smile means happiness.
- Positive words mean positive intent.
- Fast pacing means excitement.

These mappings can be useful as first approximations, but they often fail in real communication. Human meaning is layered. Tone can contradict words. Visual performance can exaggerate emotion for humor. Cultural references can invert the apparent meaning of a phrase. Narrative setup can turn a neutral action into a joke, critique, warning, or emotional reveal.

## Hypothesis

The central hypothesis of IEMC is:

> Emotional interpretation improves when multimodal signals are evaluated through cultural and narrative context rather than treated as isolated labels.

This hypothesis implies that a system should not only ask "what emotion is visible?" but also:

- Who is communicating?
- To whom?
- In what cultural setting?
- Through which medium?
- With what narrative buildup?
- Under which social expectations?
- With which possible ironic, humorous, or symbolic meanings?

## Components of the Framework

IEMC separates interpretation into layered components. Each component can produce observations, uncertainty, and competing hypotheses.

## Voice

Voice analysis focuses on how something is said rather than only what is said.

Public research dimensions may include:

- Prosody
- Intensity
- Rhythm
- Pauses
- Pitch movement
- Speaking rate
- Vocal tension
- Laughter or breath patterns

Example:

```text
"Buenisimo, justo lo que faltaba."
```

The text may look positive, but a flat tone, long pause, and lowered pitch could suggest irony or frustration.

## Text

Text analysis focuses on explicit meaning, implied intent, pragmatics, and discourse structure.

Public research dimensions may include:

- Sentiment
- Intent
- Modality
- Politeness
- Sarcasm markers
- Idioms
- Slang
- Code-switching
- Regional phrasing

Example:

```text
"Dale, espectacular."
```

Depending on region, relationship, punctuation, and delivery, this may indicate approval, resignation, annoyance, or ironic acceptance.

## Culture

Cultural context shapes how emotional and narrative cues are interpreted.

Public research dimensions may include:

- Regional idioms
- Shared references
- Humor conventions
- Social hierarchy
- Local media formats
- Platform communities
- Historical context
- Norms around directness and indirectness

Example:

An expression that sounds exaggerated in one country may be normal emphasis in another. A meme format may carry a specific regional joke that is invisible if translated literally.

## Narrative

Narrative context explains how meaning develops over time.

Public research dimensions may include:

- Setup
- Tension
- Reversal
- Payoff
- Character role
- Conflict
- Expectation violation
- Emotional arc

Example:

A short silence before a response can mean confusion, comedic timing, discomfort, or suspense depending on the preceding scene.

## Visual

Visual analysis focuses on nonverbal and scene-level cues.

Public research dimensions may include:

- Facial expression
- Gesture
- Posture
- Gaze
- Scene composition
- Editing rhythm
- On-screen text
- Props
- Social distance
- Visual contrast

Example:

A speaker saying "todo perfecto" while looking away, holding a tense posture, and standing in a chaotic room may communicate the opposite of literal text.

## Multimodal Integration

The integration layer compares signals across modalities and generates interpretation hypotheses.

The goal is not to force all signals into one score. Instead, IEMC encourages structured reasoning:

1. Identify observations per modality.
2. Mark uncertainty and contradictions.
3. Add cultural and narrative context.
4. Generate competing interpretations.
5. Explain why one interpretation is more plausible.
6. Preserve uncertainty when the evidence is insufficient.

## Example Integration

Synthetic scenario:

```text
Text: "Me encanta cuando el sistema se cae justo antes de entregar."
Voice: low pitch, slow rhythm, slight laugh
Visual: speaker looks at camera, raises eyebrows
Context: team video after a failed deadline
Culture: regional use of ironic exaggeration
```

Possible interpretation:

- Literal joy is unlikely.
- Frustrated irony is plausible.
- Humor may be used to reduce group tension.
- The emotional state may combine annoyance, resignation, and social bonding.

## Research Output Format

An IEMC-style output should be interpretable and cautious:

```json
{
  "primary_hypothesis": "ironic frustration",
  "supporting_signals": ["textual contradiction", "vocal pacing", "eyebrow gesture"],
  "cultural_context": "regional ironic phrasing",
  "uncertainty": "medium",
  "alternative_hypotheses": ["humor", "resignation"]
}
```

This is a public research example, not production scoring.

