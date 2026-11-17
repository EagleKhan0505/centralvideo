# Central de Vídeos

**Preparing video content for my AI assistants through a local workflow that I can tune and optimize.**

[Português](README.md) · [Gustavo Amaral](https://github.com/EagleKhan0505)

## Motivation

The AI assistants I used could not always accept or interpret video directly. I built Central de Vídeos to turn a recording into organized speech, selected frames, on-screen text and timestamped evidence that my AI workflows can consume.

The local processing uses my existing computer and local models, without an additional video-analysis subscription or paid processing API. I can adjust sampling, coverage and resource use for each task.

## Implemented capabilities

- Local interface for ingestion, progress tracking and reviewing outputs.
- Audio transcription, frame selection, OCR and visual-analysis components.
- Timestamped evidence linked to the source recording.
- Configurable processing profiles and sampling budgets.
- Reuse of compatible results, checkpoints and execution history.
- Structured exports for downstream AI analysis.

## My contribution

I identified the need, defined the workflow and guided tool integration and AI-assisted development. I use output inspection, testing and bottleneck analysis to drive improvements.

## Current stage

Local application under development, with real-video processing and evaluation records. A long-lecture profile is implemented; multi-hour recordings still require validation. Sampling affects coverage, and generated text and interpretations require review.

**Technologies:** Python, FFmpeg, faster-whisper, OCR, local models and Ollama.

This repository presents the project. Application source code, model files and working videos are kept private.
