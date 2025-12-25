# OneStop.25
ai powered personal reflection and milestone analytics platform

onestop.25 is a high-performance personal analytics system that converts everyday activity into structured insights, micro-wins, and cultural-style feedback loops. it blends real-time data pipelines, serverless ai orchestration, and a brutalist interaction layer to create a private yearly operating system. it is very much optimised for mobile experience and uses custom ui/ux (no gradients)

# what it does

onestop.25 tracks personal activity, behavioral patterns, and reflective inputs, then generates:

- ai-driven milestone summaries and progress signals

- aura analytics that score social confidence gains and losses

- non-repeating cultural insights using ai memory deduplication

- interactive “wrapped-style” visualizations with instant feedback loops

- real-time personalization based on historical state and user profile evolution

- the system is designed to feel like a living dashboard of 2025 and a calming planner for 2026.

# core features

# 1. aura analytics engine

- converts real-life moments into gain and loss events with weighted scoring

- enforces strict ai schema validation with automatic fallbacks

- prevents repetition using history-aware prompting and content deduplication

- produces structured moment objects ready for instant claiming and state mutation

# 2. ai milestone generator

- builds identity-driven milestone narratives using full user psychographics

- integrates bucket history and prior reflections to avoid stale outputs

- supports rate-limited, per-user ai flows with schema-validated output guarantees

# 3. real-time interaction layer

- framer-motion driven micro-interactions for instant visual feedback

- ultra-narrow viewport optimization for low-end mobile devices

- zero-latency ui updates synchronized with firestore state

# 4. persistence and state integrity

- every action is stored as immutable event history

- prevents duplicate generation across sessions

- supports full session rehydration on reload without recomputation

# system architecture

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/a7ed1baf-448d-4042-a45c-5827a1eccb0e" />


# technology stack

# frontend

- react

- framer motion

- custom css system with 5000+ lines of layout logic

- render deployment with spa rewrite rules

# backend

- firebase cloud functions gen2

- firestore realtime database

- firebase authentication

# ai orchestration

- genkit framework

- google gemini flash models

- schema-validated output pipelines

- per-user ai rate limiting

- history-aware prompt construction

# how it works

- user activity is captured and persisted as structured state events

- ai generation flows pull full user psychographics plus historical aura memory

- prompts are dynamically constructed to prevent repetition

- ai output is schema-validated and sanitized before delivery

- fallback logic guarantees output consistency even during model failure

- ui consumes events and renders instant feedback without page reloads

# performance design

- ultra-narrow viewport support for screens under 340px

- full realtime firestore streaming

- cold-start tolerant ai functions with retry-safe execution

- zero-blocking frontend updates through optimistic ui mutation

# project philosophy

onestop.25 is not a productivity tracker.
it is a private behavioral operating system built to surface momentum, confidence shifts, and cultural signals that normal analytics never capture.

it is engineered as an event-driven ai system rather than a static dashboard.
