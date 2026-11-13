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

## Release path

1. Make a dedicated GitHub repository named `evidence-bound-adversarial-verification`.
2. Upload the contents and verify recorded SHA-256 identities.
3. Enable the repository in Zenodo's GitHub integration.
4. Publish a GitHub release tagged `v0.1.0`.
5. Check that Zenodo created the archived record, then add the actual DOI to the website and citation metadata in a separately versioned update. **Do not invent a DOI.**

**Website:** https://brendonrcoleman.com/methods/ebav/ (Netlify production deploy for website PR #11 reported READY on 2026-11-13).  
**Citation status:** DOI not yet issued.
