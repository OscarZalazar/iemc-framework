# IEMC Framework

**Inteligencia Emocional Multimodal Cultural**

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-research%20draft-orange.svg)](ROADMAP.md)
[![Version](https://img.shields.io/badge/version-v0.1.0-lightgrey.svg)](ROADMAP.md)

IEMC Framework is an open research framework for interpreting emotional and narrative meaning across multiple modalities:

- Vocal emotion
- Textual intent
- Visual signals
- Narrative context
- Cultural context

The project focuses on the gap between raw multimodal classification and human-level interpretation. A phrase, tone, face, scene, or joke can change meaning depending on culture, timing, audience, medium, and narrative setup. IEMC proposes a structured way to reason about those layers without assuming that emotion is universal, static, or fully captured by a single signal.

> This repository contains public documentation and research material. It does not contain proprietary code from OZD Engine or ONE ADS.

## Problem

Current AI systems are strong at detecting isolated patterns, but they often struggle when meaning depends on cultural cues, irony, humor, social norms, or narrative progression. A smile may indicate joy, politeness, embarrassment, sarcasm, or social discomfort. A sentence may be supportive in one context and ironic in another. A viral video may be funny because of timing, shared references, or regional identity rather than literal content.

IEMC treats emotional interpretation as a multimodal and culturally situated task.

## Why Cultural Context Matters

Emotion and intent are not only biological signals. They are also shaped by:

- Language variety and local idioms
- Regional humor and irony
- Social expectations
- Historical and media references
- Platform-specific formats
- Community norms

Without cultural context, models can overfit to surface cues and miss the human reason a message works.

## Why Multimodal Analysis Matters

Text alone can miss tone. Voice alone can miss narrative intent. Visual signals alone can miss cultural meaning. IEMC encourages layered analysis across modalities, then integrates them into an interpretable hypothesis rather than a single opaque score.

## Use Cases

- Video Understanding
- AI Assistants
- Content Analysis
- Media Intelligence
- AdTech
- Education
- Research

## Repository Contents

- `docs/iemc-framework.md` - technical framework overview
- `docs/use-cases.md` - practical public use cases
- `docs/ozd-overview.md` - public conceptual OZD Engine overview without proprietary IP
- `research/WHITEPAPER_DRAFT.md` - initial theoretical whitepaper draft
- `examples/sample_input.json` - synthetic example input
- `examples/sample_output.json` - synthetic example output
- `ROADMAP.md` - public roadmap

## Non-Goals

This repository does not publish:

- Private code
- API keys
- `.env` files
- Proprietary algorithms
- Private prompts
- Production scoring logic
- Internal configurations
- Secrets

## License

Apache License 2.0. See [LICENSE](LICENSE).

