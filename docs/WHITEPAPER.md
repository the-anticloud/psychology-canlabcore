# Technical Whitepaper — CANLABCORE

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/canlab/CanlabCore
**Category:** PSYCHOLOGY

## Abstract

This whitepaper describes the Anticloud integration of `CANLABCORE` (Neuroimaging and psychological data analysis)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local therapy session transcription — never leaves device
2. AIOSS patient record audit chain (HIPAA-aligned)
3. AES-256 encryption for all session notes and assessments
4. Single-binary clinic deployment with no cloud dependency
5. Zero-telemetry: removes all upstream analytics and data sharing
6. Offline sentiment and risk assessment inference
7. Anonymized local analytics replacing cloud reporting dashboards
8. Audit log for every record access (GDPR Article 30 aligned)

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.