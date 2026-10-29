# Voice Live Cost Lab - public snapshot

This repository contains only the generated read-only site and sanitized synthetic evidence.
No backend, Azure connection configuration, credentials or private Foundry measurements are included.

- Six scenarios, English and Mandarin, native and standard voice paths.
- 48 measured conversations: **one run per configuration, not a ten-run average**.
- 48 separate smoke conversations; excluded from measurement statistics.
- 96 timing-v2 stereo PCM WAV recordings: agent left, simulated user right.
- Homepage playback and per-sample duration, response-turn, task-tool and simulator-control counts.
- Interruptions are explicitly not tested (manual half-duplex, no VAD/barge-in).
- Human realism checks stay in the reviewer's browser, not shared approvals.
- Basic maps to the official Standard tier: gpt-realtime-mini native and gpt-4.1-mini cascade.
- Historical list prices, compatible-model calculator, JSON/CSV downloads.
- Provider identifiers are replaced and tool arguments omitted; token counts, costs and audio bytes are unchanged.
- Completion is not task correctness. Audio is for human review, not a quality certification.
- Headline cost excludes simulator, telephony/carrier and infrastructure charges.

The site cannot start billable calls. Pricing is an estimate, not an invoice.
