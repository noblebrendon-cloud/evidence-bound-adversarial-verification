# Evidence-Bound Adversarial Verification (EBAV)

**v0.1.0 — Field Method / Working Paper**  
**Author:** Brendon R. Coleman  
**Date:** 2026-11-13  
**License:** CC BY 4.0 (documentation and templates)

**Core invariant:** No claim may authorize a greater action than the evidence supporting that claim establishes.

**Protocol:** Construct → Freeze → Challenge → Classify → Correct → Reverify → Authorize.

EBAV is a proposed governance method for AI-assisted software verification and release. It integrates established inspection, mutation testing, software provenance, reproducible-build, and change-control practices. Its proposed contribution is the composition and explicit claim/evidence/authority contract. It is not a new security standard, certification, penetration-test service, or validated comparative research result.

## Contents

- `PAPER.md`: formal working paper with prior art, protocol model, JIK case account, validity limits, and citations
- `PAPER.pdf`: typeset working paper
- `PAPER.docx`: editable manuscript
- `protocol/EBAV-PROTOCOL.md`: reusable operating specification
- `protocol/VALIDATION-PLAN.md`: prospective research/evaluation protocol
- `templates/gate-decision.example.json`: non-operational evidence template
- `templates/REVIEW-MATRIX.csv`: review record template
- `CITATION.cff`: machine-readable citation metadata
- `.zenodo.json`: Zenodo-specific release metadata (takes precedence over `CITATION.cff` in Zenodo)
- `CHANGELOG.md`, `LICENSE.md`, `SHA256SUMS`

## Publication and evidence boundary

The Jesus Is King case is retrospective and drawn from supplied review reports; restricted primary infrastructure evidence is not bundled. This repository intentionally includes no credentials, secret values, interactive console challenges, provider tokens, or operational authorization to run any JIK tooling.

## Archived release and citation

- **Original GitHub release:** https://github.com/noblebrendon-cloud/evidence-bound-adversarial-verification/releases/tag/v0.1.0
- **Zenodo version DOI:** https://doi.org/10.5281/zenodo.24210752 (shown as Published in the connected Zenodo repository on November 13, 2026).
- **Source commit associated with the immutable v0.1.0 tag:** `a3fc4a415e31eff6595447e5b58ac68bb2353080`.
- **Website:** https://brendonrcoleman.com/methods/ebav/
- **Citation:** Coleman, Brendon R. (2026). *Evidence-Bound Adversarial Verification (EBAV): A Governed Field Method for AI-Assisted Software Verification and Release* (Version 0.1.0). Zenodo. https://doi.org/10.5281/zenodo.24210752

**Evidence boundary:** The Zenodo integration screenshot establishes the Published status, title, version, and DOI; a separate public Zenodo file-by-file verification was not available through this session. The GitHub release tag's 16 files had already been verified against the version 0.1.0 integrity manifest.

The v0.1.0 tag is preserved. The branch `main` may contain post-release citation/status annotations and a separately regenerated `SHA256SUMS`; those updates are not silently substituted into the archived v0.1.0 release.
