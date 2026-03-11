# Test Plan: <Short Descriptive Test Name>

## 1. Metadata
- **Test ID:** LSS-XXX / LTS-XXX / LMS-XXX
- **Business Unit:** LSS | LTS | LMS | Premium
- **Test Type:** A/B | Multivariate | Personalization | Auto‑Target
- **Surface / Page:** Homepage | Product Page | Pricing | Landing Page
- **Platform:** LEM | Legacy | NGW
- **Tooling:** Adobe Target, Adobe Analytics
- **Status:** Draft | QA | Live | Complete
- **Primary Owner:** 
- **Stakeholders:** 
- **Created:** YYYY‑MM‑DD
- **Last Updated:** YYYY‑MM‑DD

---

## 2. Background & Context
Briefly explain **why this test exists**.
- What problem or opportunity are we addressing?
- What insight, data, or request triggered this test?
- Is this BAU optimization, strategic validation, or exploratory learning?

---

## 3. Hypothesis
**If** we <change / experience>,  
**then** <expected user behavior or outcome>,  
**because** <user insight or rationale>.

Example:  
> If we clarify the primary CTA value proposition above the fold, then demo clicks will increase, because users currently lack confidence in what happens after clicking.

---

## 4. Test Design
### Control
- Description of current experience

### Variant(s)
- **Variant A:**  
- **Variant B (if applicable):**

### Experience Rules
- What specifically changes?
- What explicitly does *not* change?

---

## 5. Audience & Targeting
- **Traffic Allocation:** XX% Control / XX% Variant
- **Eligibility:** Authenticated | Anonymous | Geo | Segment
- **Exclusions:** Internal traffic, bots, etc.

---

## 6. Measurement Plan
### Primary Success Metric
- Metric name (e.g., CTA CTR, Demo Starts)
- Analytics source (AA event / Target metric)

### Secondary Metrics
- Conversion rate
- Down‑funnel impact
- Guardrails (bounce, latency, errors)

### Statistical Approach
- Confidence threshold (e.g., 95%)
- Minimum detectable effect (if known)

---

## 7. Risks & Dependencies
- Tracking risks
- Platform dependencies (LEM, NGW, SEO)
- Legal / Brand constraints

---

## 8. QA & Validation
- Visual QA completed (Y/N)
- Tracking validated (Y/N)
- Cross‑browser/device checked (Y/N)

---

## 9. Decision Criteria
- What constitutes a **win**?
- What constitutes **no‑decision**?
- What triggers **rollback**?

---

## 10. Timeline & Owners
- **QA Complete By:** 
- **Go‑Live:** 
- **Decision Date:** 
- **Readout Owner:** 

---

## 11. Post‑Test Learnings (Complete After Test)
- Outcome summary
- Key learnings
- Recommended next action
``