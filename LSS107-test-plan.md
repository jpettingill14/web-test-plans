# Test Plan: LSS Homepage Hero CTA Optimization

## 1. Metadata
- **Test ID:** LSS-107
- **Business Unit:** LSS
- **Test Type:** A/B
- **Surface / Page:** Homepage
- **Platform:** LEM
- **Tooling:** Adobe Target, Adobe Analytics
- **Status:** Live
- **Primary Owner:** Web Testing & Optimization
- **Stakeholders:** Web Marketing, UX, DGO
- **Created:** 2026‑02‑12
- **Last Updated:** 2026‑03‑01

---

## 2. Background & Context
Homepage hero drives a high volume of traffic but underperforms downstream conversion relative to mid‑page CTAs. Prior tests suggest messaging clarity is a stronger lever than visual treatment.

---

## 3. Hypothesis
If we clarify the primary value proposition and expected outcome of clicking the hero CTA, then demo starts will increase, because users currently lack clarity on what happens after clicking.

---

## 4. Test Design
### Control
- Existing hero headline and generic “Request a Demo” CTA

### Variant A
- Updated headline focused on outcome
- CTA updated to “See How Teams Use LinkedIn”

---

## 5. Audience & Targeting
- **Traffic Allocation:** 50% Control / 50% Variant
- **Eligibility:** Anonymous + Authenticated
- **Exclusions:** Internal traffic

---

## 6. Measurement Plan
### Primary Metric
- Demo Starts (AA event)

### Secondary Metrics
- Hero CTA CTR
- Bounce rate
- Time to first interaction

---

## 7. Risks & Dependencies
- Reliant on LEM hero component stability
- SEO review required due to headline change

---

## 8. QA & Validation
- Visual QA: ✅
- Tracking QA: ✅
- Cross‑browser QA: ✅

---

## 9. Decision Criteria
- Win if Variant increases demo starts by ≥5% with 95% confidence
- No‑decision if neutral impact
- Rollback if bounce rate increases by >10%

---

## 10. Timeline & Owners
- **Go‑Live:** 2026‑02‑18
- **Decision Date:** 2026‑03‑04
- **Readout Owner:** Jonathan Pettingill

---

## 11. Post‑Test Learnings
_TBD_
