# Credential Body Scoring Output — All 16 Workflow Clusters

*Generated March 2026 | Scoring Rubric v2*
*Source: Cluster_Agent_Prompt_v2.md + Credential_Body_Scoring_Rubric.md*

**Composite Formula:** Total = (Dim 1 x 0.50) + (Dim 2 x 0.30) + (Dim 3 x 0.20)
- **Dim 1** (Quality) = (Rigor + Domain Fit) / 2
- **Dim 2** (Prestige) = Gate A + Gate B + Gate C
- **Dim 3** (Breadth) = (Geo Reach + Mid-Career Density) / 2

**Note:** All scoring agents relied on training data (cutoff ~May 2025). Web verification was unavailable. Lower-confidence items are flagged as UNSCORED where appropriate.

---

## Cluster 1: Investment Banking / Valuation (~62 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| IB / Valuation | CFA Institute (CFA Charter) | 9 | 7 | 8.0 | 4 | 3 | 3 | 10 | 10 | 7 | 8.5 | **8.70** |
| IB / Valuation | American Society of Appraisers (ASA BV) | 7 | 9 | 8.0 | 2 | 1 | 3 | 6 | 4 | 6 | 5.0 | **6.80** |
| IB / Valuation | CBV Institute (CBV) | 7 | 10 | 8.5 | 4 | 0 | 1 | 5 | 2 | 7 | 4.5 | **6.65** |
| IB / Valuation | AICPA (ABV) | 7 | 8 | 7.5 | 2 | 1 | 3 | 6 | 2 | 6 | 4.0 | **6.35** |
| IB / Valuation | NACVA (CVA) | 5 | 9 | 7.0 | 2 | 1 | 1 | 4 | 2 | 7 | 4.5 | **5.60** |
| IB / Valuation | CAIA Association (CAIA Charter) | 7 | 4 | 5.5 | 2 | 1 | 1 | 4 | 8 | 7 | 7.5 | **5.45** |
| IB / Valuation | Corporate Finance Institute (FMVA) | 3 | 9 | 6.0 | 0 | 0 | 0 | 0 | 6 | 4 | 5.0 | **4.00** |

### Calibration Notes
No scores were changed from the initial pass. All scores survived calibration as originally set.

### Sanity Check Flags
- **CAIA Geographic Reach (8):** Credited 4 regions but the 4th region (Latin America or Africa) lacks concrete evidence; if only 3 regions confirmed, score drops to 6, Dim 3 drops to 6.5, Total drops to 5.25.
- **CFI/FMVA Geographic Reach (6):** Scored on the basis of online global presence rather than documented institutional infrastructure (exam centers, chapters); a stricter reading of the rubric could justify a lower score.
- **CBV Gate A (4):** Scored as genuinely gatekeeping in Canada, but the gatekeeping effect is geographically limited to one country; if the rubric intends "globally gatekeeping," this should be 2, which would drop Dim 2 to 3, and Total to 6.05.

### UNSCORED Items
- **ASA Geographic Reach:** International presence beyond US/Canada is undocumented from available evidence; scored 4 (2 regions) but true regional count may differ. Needs inquiry: formal chapters or exam centers in Europe, Asia, Latin America, or Africa.
- **CAIA 4th region:** Cannot confirm Latin America or Africa presence with concrete evidence. Needs inquiry.
- **CFI/FMVA Geographic Reach:** Online-only global presence makes traditional geographic scoring uncertain. Needs inquiry on whether online-only reach should be scored differently under this rubric.

### Regions Credited

| Organization | Regions Credited | Count | Basis |
|---|---|---|---|
| CFA Institute | USA/Canada, Latin America, Europe, Asia, Africa | 5 | Published directory of 160+ local societies spanning all world regions; exam centers on every continent |
| ASA BV | USA, Canada | 2 | US-headquartered with domestic chapters; some Canadian members; no documented institutional infrastructure beyond North America |
| CBV Institute | Canada | 1 | Canadian institution exclusively; no documented presence outside Canada |
| AICPA (ABV) | USA | 1 | Requires US CPA licensure; essentially US-only credential |
| NACVA (CVA) | USA | 1 | US-based organization; training and membership primarily domestic |
| CAIA Association | USA/Canada, Europe, Asia, +1 uncertain | 4 | Documented membership in North America, Europe (UK, Switzerland), Asia (Hong Kong, Singapore, India); 4th region unconfirmed |
| CFI (FMVA) | Global online (no institutional infrastructure) | 3 (estimated) | Online platform with users across multiple continents but no local chapters, exam centers, or regional membership structures |

---

## Cluster 2: Asset Management / Portfolio (~30 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Asset Mgmt / Portfolio | CFA Institute (CFA) | 10 | 9 | 9.5 | 4 | 3 | 3 | 10 | 10 | 8 | 9.0 | **9.55** |
| Asset Mgmt / Portfolio | GARP (FRM) | 8 | 6 | 7.0 | 4 | 1 | 3 | 8 | 10 | 7 | 8.5 | **7.60** |
| Asset Mgmt / Portfolio | CFP Board (CFP) | 7 | 5 | 6.0 | 4 | 3 | 3 | 10 | 6 | 7 | 6.5 | **7.30** |
| Asset Mgmt / Portfolio | CAIA Association (CAIA) | 7 | 7 | 7.0 | 2 | 1 | 1 | 4 | 8 | 8 | 8.0 | **6.30** |
| Asset Mgmt / Portfolio | Investments & Wealth Inst. (CIMA) | 7 | 8 | 7.5 | 2 | 1 | 1 | 4 | 2 | 9 | 5.5 | **6.05** |

### Calibration Notes
- CFA Institute is the clear #1 for this cluster by a wide margin (~2 points). Level III curriculum is built around portfolio management and investment analysis.
- FRM vs. CFP ordering tension: FRM (#2 at 7.60) edges CFP (#3 at 7.30) despite CFP's perfect Dim 2 score. FRM has higher domain fit (6 vs 5) and stronger geographic reach (10 vs 6).
- CFP's Domain Fit at 5 reflects that portfolio management is roughly 15-20% of the CFP exam.
- CAIA at 6.30 is dragged down by low pitch credibility (Dim 2 = 4).
- CIMA at 6.05 has the highest domain fit after CFA (8) and the best seniority density (9), but is severely limited by US-only geographic reach.

### Sanity Check Flags
- **CAIA Geo Reach:** Scored at 8 (4 regions) but moderate confidence on Latin America presence. If not confirmed, Total drops to 6.10.
- **CFP Geo Reach via FPSB:** CFP Board is US-only, but FPSB affiliates exist globally. Credited 3 regions. Could shift +/-0.5 depending on whether FPSB affiliates count.
- **GARP Gate C at 3:** GARP is ~30 years old. If stricter "decades" interpretation requires 30+, drops to 1, Dim 2 drops to 6, Total drops to 7.00.
- **CFP vs. FRM rank is soft** (7.30 vs 7.60). Close enough to invert with minor scoring changes.

### UNSCORED Items
- **CAIA Geo Reach -- Latin America:** Unable to verify documented meaningful CAIA presence in Latin America. Confidence: MODERATE.
- **CIMA Geo Reach -- International:** Confident CIMA is overwhelmingly US-based (scored 2). Confidence: HIGH.

### Regions Credited

| Credential Body | USA & Canada | Latin America | Europe | Asia | Africa | Regions |
|---|---|---|---|---|---|---|
| CFA Institute (CFA) | YES | YES | YES | YES | YES | 5 |
| GARP (FRM) | YES | YES | YES | YES | YES | 5 |
| CFP Board (CFP) | YES | Partial (via FPSB) | YES (via FPSB) | YES (via FPSB) | Partial (via FPSB) | 3 |
| CAIA Association (CAIA) | YES | UNSCORED | YES | YES | NO | 3-4 |
| Investments & Wealth Inst. (CIMA) | YES | NO | NO | NO | NO | 1 |

---

## Cluster 3: Private Equity / VC (~34 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Private Equity / VC | CFA Institute (CFA) | 10 | 5 | 7.5 | 4 | 3 | 3 | 10 | 10 | 7 | 8.5 | **8.45** |
| Private Equity / VC | CAIA Association (CAIA) | 7 | 9 | 8.0 | 2 | 1 | 1 | 4 | 6 | 8 | 7.0 | **6.60** |
| Private Equity / VC | ILPA | 3 | 9 | 6.0 | 2 | 0 | 3 | 5 | 6 | 5 | 5.5 | **5.60** |

### Calibration Notes
- CFA domain fit (5): PE/VC content is roughly 5-10% of CFA curriculum. Score of 5 reflects "broader domain including this."
- CAIA Gate C (1) vs ILPA Gate C (3): ILPA sets industry-wide standards (ILPA Principles adopted across global PE) and engages with regulators. CAIA is smaller without standard-setting influence.
- ILPA Rigor (3): Training programs lack a formal multi-stage examination with pass/fail gating.
- CFA scoring highest despite not being PE/VC-specific is driven by the 30% pitch credibility weight.

### Sanity Check Flags
- No university was scored, consistent with Rule 4.
- No parent/sub-chapter double-counting.
- Web verification unavailable. Core facts used are well-established and stable.

### UNSCORED Items
- **NVCA:** Trade/lobbying association; no exam-based credential.
- **BVCA:** Regional (UK) trade association; no exam-based credential.
- **ACG:** Membership organization; no formal exam-based credential.

### Regions Credited

| Credential Body | Regions Credited | Count |
|---|---|---|
| CFA Institute | USA/Canada, Europe, Asia, Latin America, Africa | 5 |
| CAIA Association | USA/Canada, Europe, Asia | 3 |
| ILPA | USA/Canada, Europe, Asia | 3 |

---

## Cluster 4: Hedge Fund / Public Markets (~24 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Hedge Fund / Public Markets | CFA Institute | 9 | 8 | 8.5 | 4 | 3 | 3 | 10 | 10 | 8 | 9.0 | **9.05** |
| Hedge Fund / Public Markets | CAIA Association | 7 | 7 | 7.0 | 2 | 1 | 3 | 6 | 8 | 8 | 8.0 | **6.90** |
| Hedge Fund / Public Markets | GARP (FRM) | 8 | 4 | 6.0 | 2 | 1 | 3 | 6 | 10 | 7 | 8.5 | **6.50** |
| Hedge Fund / Public Markets | CMT Association | 7 | 5 | 6.0 | 2 | 1 | 1 | 4 | 6 | 7 | 6.5 | **5.50** |

### Calibration Notes
No scores were changed during calibration. Flagged but not changed: CAIA Gate C scored 3. Founded 2002 (24 years old). "Decades of history" met technically but narrowly.

### Sanity Check Flags
- CFA dominance at 9.05 is appropriate for buy-side equity research workflows.
- GARP vs. CAIA gap is narrow (6.50 vs. 6.90). CAIA's higher Domain Fit (7 vs. 4) offset by GARP's higher Rigor (8 vs. 7) and wider Geo Reach (10 vs. 8).
- CFA Domain Fit at 8 vs. potential 9: Many CFA charterholders work outside hedge fund public markets. Filtering need confirms 8, not 9.

### UNSCORED Items
- **CAIA Latin America presence:** Would resolve whether Geo Reach should be 8 or 10.
- **FRM seniority skew in Asia:** GARP's FRM popular among early-career in India/China. Could affect Mid-Career Density.

### Regions Credited

| Credential Body | USA & Canada | Latin America | Europe | Asia | Africa | Count |
|---|---|---|---|---|---|---|
| CFA Institute | Yes | Yes | Yes | Yes | Yes | 5 |
| CAIA Association | Yes | No | Yes | Yes | Yes | 4 |
| GARP (FRM) | Yes | Yes | Yes | Yes | Yes | 5 |
| CMT Association | Yes | No | Yes | Yes | No | 3 |

---

## Cluster 5: Commercial Banking / Lending (~15 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Commercial Banking / Lending | CFA Institute | 10 | 5 | 7.50 | 2 | 3 | 3 | 8 | 10 | 7 | 8.50 | **7.85** |
| Commercial Banking / Lending | GARP (FRM) | 8 | 4 | 6.00 | 2 | 1 | 3 | 6 | 10 | 8 | 9.00 | **6.60** |
| Commercial Banking / Lending | RMA (CRC) | 6 | 9 | 7.50 | 4 | 0 | 1 | 5 | 2 | 9 | 5.50 | **6.35** |
| Commercial Banking / Lending | ACCA | 8 | 4 | 6.00 | 0 | 1 | 3 | 4 | 10 | 7 | 8.50 | **5.90** |
| Commercial Banking / Lending | ABA / ICB (CLBB) | 5 | 8 | 6.50 | 2 | 0 | 3 | 5 | 2 | 8 | 5.00 | **5.75** |
| Commercial Banking / Lending | LIBF | 6 | 8 | 7.00 | 2 | 0 | 1 | 3 | 4 | 7 | 5.50 | **5.50** |

### Calibration Notes
No scores were changed during the calibration pass. Rigor ordering (CFA > ACCA = GARP > RMA = LIBF > ABA) is defensible. Gate B of 3 assigned only to CFA. Domain Fit ordering (RMA > ABA = LIBF > CFA > ACCA = GARP) correctly places RMA first.

### Sanity Check Flags
- **CFA #1 vs RMA #3:** CFA's composite (7.85) exceeds RMA's (6.35) despite RMA having dramatically higher domain fit (9 vs 5) and the only de facto required credential (Gate A = 4). Gap driven by CFA's recognition and reach. **Recommend treating RMA as operational sourcing lead and CFA as pitch credibility anchor.**
- **GARP #2 ahead of RMA #3:** GARP's global reach (10 vs 2) outweighs lower domain fit (4 vs 9). For actual lending practitioner sourcing, FRM holders require more filtering than CRC holders.

### UNSCORED Items
- **LIBF Seniority (scored 7):** Moderate confidence. Could shift to 6 or 8 with evidence.
- **LIBF Geo Reach (scored 4 / 2 regions):** If Africa confirmed, score rises to 6 and TOTAL to 5.70.

### Regions Credited

| Organization | USA & Canada | Latin America | Europe | Asia | Africa | Regions |
|---|---|---|---|---|---|---|
| CFA Institute | Yes | Yes | Yes | Yes | Yes | 5 |
| GARP (FRM) | Yes | Yes | Yes | Yes | Yes | 5 |
| ACCA | Yes | Yes | Yes | Yes | Yes | 5 |
| LIBF | No | No | Yes | Yes | No | 2 |
| RMA (CRC) | Yes | No | No | No | No | 1 |
| ABA / ICB (CLBB) | Yes | No | No | No | No | 1 |

---

## Cluster 6: FP&A / Corporate Finance (~25 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| FP&A / Corp Finance | CFA Institute (CFA) | 10 | 6 | 8.0 | 4 | 3 | 3 | 10 | 10 | 7 | 8.5 | **8.70** |
| FP&A / Corp Finance | IMA (CMA) | 7 | 8 | 7.5 | 4 | 1 | 3 | 8 | 10 | 8 | 9.0 | **7.95** |
| FP&A / Corp Finance | AICPA/CIMA (CGMA) | 5 | 7 | 6.0 | 2 | 1 | 3 | 6 | 10 | 7 | 8.5 | **6.50** |
| FP&A / Corp Finance | AFP (FPAC) | 6 | 10 | 8.0 | 2 | 0 | 1 | 3 | 4 | 9 | 6.5 | **6.20** |
| FP&A / Corp Finance | AFP (CTP) | 6 | 5 | 5.5 | 2 | 0 | 1 | 3 | 4 | 8 | 6.0 | **4.85** |

### Calibration Notes
- CFA vs CMA spread (0.75 pts): CFA wins on pitch credibility (Gate B = 3). CMA wins on domain fit (8 vs 6) and seniority alignment (8 vs 7).
- CGMA rigor score of 5 reflects dual-pathway problem: CPA add-on (low) vs CIMA pathway (high).
- FPAC perfect domain fit (10) offset by weak pitch credibility (Dim 2 = 3). Literally built for FP&A but launched 2014, ~2,000-3,000 holders.
- AFP appears twice (FPAC and CTP): distinct certifications with separate exams and candidate pools.

### Sanity Check Flags
- **CFA domain fit = 6 may feel low.** CFA was designed for investment analysts, not internal FP&A practitioners. Budgeting, forecasting, variance analysis are not primary CFA exam topics. Score of 6 defensible.
- **CGMA rigor = 5 may undervalue the CIMA pathway.** If sourcing targets CIMA-qualified professionals (UK/Commonwealth), effective rigor is higher.
- **CTP at 4.85 is borderline for inclusion.** Included because treasury/cash management workflows are part of this cluster.

### UNSCORED Items
- ACCA, CISI, GARP/FRM considered and excluded (lower domain fit or tangential).

### Regions Credited

| Credential Body | USA & Canada | LatAm | Europe | Asia | Africa | Count |
|---|---|---|---|---|---|---|
| CFA Institute (CFA) | Yes | Yes | Yes | Yes | Yes | 5 |
| IMA (CMA) | Yes | Yes | Yes | Yes | Yes | 5 |
| AICPA/CIMA (CGMA) | Yes | Yes | Yes | Yes | Yes | 5 |
| AFP (FPAC) | Yes | No | Marginal | No | No | 2 |
| AFP (CTP) | Yes | No | Marginal | No | No | 2 |

---

## Cluster 7: Accounting / Audit (~14 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Accounting / Audit | AICPA (CPA) | 9 | 10 | 9.5 | 4 | 3 | 3 | 10 | 4 | 8 | 6.0 | **8.95** |
| Accounting / Audit | ACCA | 9 | 8 | 8.5 | 4 | 1 | 3 | 8 | 10 | 7 | 8.5 | **8.35** |
| Accounting / Audit | ICAEW (ACA) | 9 | 8 | 8.5 | 4 | 1 | 3 | 8 | 4 | 8 | 6.0 | **7.85** |
| Accounting / Audit | IIA (CIA) | 7 | 7 | 7.0 | 2 | 1 | 3 | 6 | 10 | 8 | 9.0 | **7.10** |
| Accounting / Audit | ISACA (CISA) | 6 | 4 | 5.0 | 4 | 1 | 3 | 8 | 10 | 8 | 9.0 | **6.70** |
| Accounting / Audit | IMA (CMA) | 6 | 5 | 5.5 | 2 | 1 | 1 | 4 | 6 | 8 | 7.0 | **5.35** |

### Calibration Notes
- IMA Geo Reach adjusted from 8 to 6 during calibration. Africa presence leans heavily Middle East.
- ACCA vs ICAEW: Both scored Dim 1 = 8.5 and Dim 2 = 8; ACCA pulls ahead solely on Dim 3 (geographic reach).
- AICPA Domain Fit at 10: Rare but justified. Month-end close, SOX testing, audit workpapers, revenue recognition are exact CPA activities.

### Sanity Check Flags
None. Final ordering aligns with how the accounting/audit profession is structured.

### UNSCORED Items
None. Weakest evidence point is IMA's Africa geographic presence (addressed by downward adjustment).

### Regions Credited

| Credential Body | USA & Canada | Latin America | Europe | Asia | Africa | Regions |
|---|---|---|---|---|---|---|
| AICPA (CPA) | Yes | No | No | Yes | No | 2 |
| ACCA | Yes | Yes | Yes | Yes | Yes | 5 |
| ICAEW (ACA) | No | No | Yes | Yes | No | 2 |
| IIA (CIA) | Yes | Yes | Yes | Yes | Yes | 5 |
| ISACA (CISA) | Yes | Yes | Yes | Yes | Yes | 5 |
| IMA (CMA) | Yes | No | Yes | Yes | No | 3 |

---

## Cluster 8: Insurance (~14 workflows) — US Partnership Required

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Insurance | Society of Actuaries (SOA) -- FSA/ASA | 10 | 7 | 8.5 | 4 | 3 | 3 | 10 | 10 | 6 | 8.0 | **8.85** |
| Insurance | Casualty Actuarial Society (CAS) -- FCAS/ACAS | 10 | 8 | 9.0 | 4 | 3 | 1 | 8 | 4 | 6 | 5.0 | **7.90** |
| Insurance | The Institutes -- CPCU | 8 | 10 | 9.0 | 4 | 1 | 1 | 6 | 4 | 8 | 6.0 | **7.50** |
| Insurance | Georgia State University -- RMI Program | 7 | 9 | 8.0 | 2 | 0 | 1 | 3 | 2 | 7 | 4.5 | **5.80** |
| Insurance | American College of Financial Services -- CLU | 7 | 7 | 7.0 | 2 | 1 | 1 | 4 | 2 | 8 | 5.0 | **5.70** |
| Insurance | National Alliance -- CIC | 5 | 8 | 6.5 | 2 | 0 | 1 | 3 | 2 | 8 | 5.0 | **5.15** |
| Insurance | LOMA -- FLMI | 5 | 7 | 6.0 | 2 | 0 | 1 | 3 | 6 | 5 | 5.5 | **5.00** |
| Insurance | RIMS -- RIMS-CRMP | 4 | 6 | 5.0 | 2 | 0 | 1 | 3 | 4 | 8 | 6.0 | **4.60** |

### Calibration Notes
- Rigor ordering confirmed: SOA (10) = CAS (10) > CPCU (8) > CLU (7) = GSU (7) > FLMI (5) = CIC (5) > RIMS-CRMP (4).
- Domain Fit: CPCU (10) > GSU (9) > CIC (8) = CAS (8) > SOA (7) = CLU (7) = FLMI (7) > RIMS-CRMP (6). CPCU earns the rare 10 because its 8-exam curriculum maps almost 1:1 onto P&C insurance operations.
- Gate B: SOA and CAS both receive 3 (rubric cites "actuary" as example). CPCU receives 1.
- Gate C split: SOA = 3 (global institution, 80+ countries, IAA member). CAS = 1 (legitimate but ~9,000 members, concentrated North America).
- SOA vs CAS gap (0.95 points): Driven entirely by SOA's superior Gate C and Geo Reach.

### Sanity Check Flags
- **SOA/CAS overlap:** Both share preliminary exams (P/1 and FM/2). Should divide workflows (SOA for life/health, CAS for P&C) to avoid sourcing same people.
- **CPCU domain fit 10:** Confident -- 8-exam curriculum maps 1:1 onto P&C insurance operations. If workflows skew heavily quantitative/actuarial, revisit downward to 9.
- **Georgia State university exception:** Meets "undisputed #1" threshold per rubric. Ranked #1 in RMI by industry surveys for decades.
- **All 8 organizations are US-headquartered,** satisfying the "US Partnership Required" constraint.
- **RIMS-CRMP domain adjacency:** Credential holders are corporate risk managers (insurance buyers), not insurance industry professionals.
- **CLU life-insurance specificity:** Domain fit of 7 assumes workflows include life insurance content. If predominantly P&C, CLU should drop to 5-6.

### UNSCORED Items
- IFoA (UK): Not scored -- fails "US Partnership Required" constraint. Would score competitively otherwise.
- ARM, AINS, AU, AIC: Not scored separately (Institutes sub-designations, double-counting exclusion).
- ChFC: Not scored (American College sub-designation, double-counting).

### Regions Credited

| Credential Body | USA & Canada | Latin America | Europe | Asia | Africa | Regions | Geo Score |
|---|---|---|---|---|---|---|---|
| SOA -- FSA/ASA | Yes | Yes | Yes | Yes | Yes | 5 | 10 |
| LOMA -- FLMI | Yes | Yes | Yes | No | No | 3 | 6 |
| CAS -- FCAS/ACAS | Yes | No | No | No | No | 2 | 4 |
| The Institutes -- CPCU | Yes | No | No | No | No | 2 | 4 |
| RIMS -- RIMS-CRMP | Yes | No | No | Yes | No | 2 | 4 |
| CLU | Yes | No | No | No | No | 1 | 2 |
| National Alliance -- CIC | Yes | No | No | No | No | 1 | 2 |
| Georgia State -- RMI | Yes | No | No | No | No | 1 | 2 |

---

## Cluster 9: Risk Management (~15 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Risk Management | GARP -- FRM | 9 | 8 | 8.50 | 4 | 3 | 3 | 10 | 10 | 8 | 9.00 | **9.05** |
| Risk Management | ISACA -- CRISC | 6 | 7 | 6.50 | 4 | 1 | 3 | 8 | 10 | 7 | 8.50 | **7.35** |
| Risk Management | PRMIA -- PRM | 7 | 8 | 7.50 | 2 | 1 | 1 | 4 | 6 | 8 | 7.00 | **6.35** |
| Risk Management | IRM -- IRMCert/CMIRM | 6 | 9 | 7.50 | 2 | 1 | 1 | 4 | 6 | 8 | 7.00 | **6.35** |
| Risk Management | RIMS -- RIMS-CRMP | 5 | 9 | 7.00 | 2 | 1 | 1 | 4 | 4 | 9 | 6.50 | **6.00** |
| Risk Management | PMI -- PMI-RMP | 5 | 5 | 5.00 | 2 | 1 | 3 | 6 | 10 | 7 | 8.50 | **6.00** |
| Risk Management | ASIS International -- CPP | 7 | 4 | 5.50 | 2 | 1 | 1 | 4 | 6 | 9 | 7.50 | **5.45** |
| Risk Management | The Institutes -- ARM | 6 | 7 | 6.50 | 2 | 0 | 1 | 3 | 2 | 6 | 4.00 | **4.95** |

### Calibration Notes
- Gate B = 3 for GARP FRM: Borderline call. FRM is the most recognized risk-specific credential globally. If reduced to 1, total drops to 8.45 -- still first by wide margin.
- ISACA CRISC scored specifically, not ISACA broadly. ISACA's institutional weight (Gate C = 3) benefits CRISC through parent infrastructure.
- PRMIA PRM and IRM tied at 6.35: Genuinely comparable -- different but equivalent profiles.
- PMI-RMP institutional halo: Gate C = 3 and Geo = 10 driven by parent PMI organization, not PMI-RMP's own small holder base.

### Sanity Check Flags
- FRM Gate B = 3: Most aggressive score in the table. Verify whether non-specialist unprompted recognition is justified.
- PMI-RMP institutional halo: PMI's massive infrastructure inflates PMI-RMP relative to the credential's own small footprint.
- ASIS CPP domain tangentiality: Domain Fit = 4 is weakest in table. Inclusion justified because security risk is a legitimate sub-domain.

### UNSCORED Items
None. ISO 31000 certifications, CFA Institute, SOA ERM considered and excluded.

### Regions Credited

| Credential Body | USA/Canada | LatAm | Europe | Asia | Africa | Regions |
|---|---|---|---|---|---|---|
| GARP -- FRM | Yes | Yes | Yes | Yes | Yes | 5 |
| ISACA -- CRISC | Yes | Yes | Yes | Yes | Yes | 5 |
| PMI -- PMI-RMP | Yes | Yes | Yes | Yes | Yes | 5 |
| PRMIA -- PRM | Yes | No | Yes | Yes | No | 3 |
| IRM | No | No | Yes | Yes | Yes | 3 |
| ASIS -- CPP | Yes | No | Yes | Yes | No | 3 |
| RIMS -- RIMS-CRMP | Yes | No | Yes | No | No | 2 |
| The Institutes -- ARM | Yes | No | No | No | No | 1 |

---

## Cluster 10: Compliance / Regulatory (~15 workflows) — Partially US-Specific

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Compliance / Regulatory | IAPP (CIPP/CIPM/CIPT) | 6 | 8 | 7.0 | 4 | 1 | 3 | 8 | 8 | 7 | 7.5 | **7.40** |
| Compliance / Regulatory | ACAMS (CAMS) | 6 | 7 | 6.5 | 4 | 1 | 3 | 8 | 10 | 7 | 8.5 | **7.35** |
| Compliance / Regulatory | SCCE/HCCA (CCEP/CHC) | 7 | 10 | 8.5 | 4 | 1 | 1 | 6 | 4 | 8 | 6.0 | **7.25** |
| Compliance / Regulatory | IIA (CIA) | 9 | 6 | 7.5 | 2 | 1 | 3 | 6 | 10 | 7 | 8.5 | **7.25** |
| Compliance / Regulatory | ICA (Diploma in Compliance) | 7 | 8 | 7.5 | 2 | 0 | 1 | 3 | 6 | 8 | 7.0 | **6.05** |
| Compliance / Regulatory | ABA (CRCM) | 7 | 7 | 7.0 | 4 | 1 | 0 | 5 | 2 | 8 | 5.0 | **6.00** |

### Calibration Notes
- Rigor: IIA CIA (9) is the clear ceiling. SCCE, CRCM, ICA cluster at 7. ACAMS and IAPP at 6.
- Domain Fit: SCCE at 10 -- sole organization whose entire purpose is corporate compliance program management. IAPP and ICA at 8 are sub-domain-specific. IIA CIA at 6 is adjacent (auditors evaluate compliance, don't operate it).
- Gate B: No compliance credential reaches the "non-specialist recognizes" threshold of 3. Every org scored 1 except ICA at 0.
- Tight cluster at top: Four organizations within 0.15 points (7.25-7.40). Genuine parity with different trade-offs.

### Sanity Check Flags
- **SCCE Domain Fit 10:** Rare score. Justified -- SCCE/HCCA exists solely to credential compliance and ethics officers.
- **IIA CIA Domain Fit 6:** Could be argued as 5 or 7. CIAs audit compliance programs but don't design them.
- **CRCM Geo Reach 2:** Lowest geo score. Tests US banking regulations; structurally incapable of international relevance.
- **Cluster marked "partially US-specific":** Benefits SCCE and CRCM more than scoring formula captures.

### UNSCORED Items
None. NASBA/CPA, GRC Institute, ISACA (CISA/CRISC) considered and excluded.

### Regions Credited

| Credential Body | US & Canada | Latin America | Europe | Asia | Africa | Regions |
|---|---|---|---|---|---|---|
| IAPP | Yes | Emerging | Yes | Yes | Limited | 4 |
| ACAMS | Yes | Yes | Yes | Yes | Yes | 5 |
| SCCE/HCCA | Yes | No | Limited | No | No | 2 |
| IIA (CIA) | Yes | Yes | Yes | Yes | Yes | 5 |
| ICA | Limited | No | Yes | Yes | Yes | 3 |
| ABA (CRCM) | Yes | No | No | No | No | 1 |

---

## Cluster 11: Treasury (~14 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Treasury | AFP / CTP | 6 | 10 | 8.0 | 4 | 1 | 3 | 8 | 4 | 9 | 6.5 | **7.70** |
| Treasury | ACT (UK) | 8 | 9 | 8.5 | 2 | 1 | 3 | 6 | 6 | 8 | 7.0 | **7.45** |
| Treasury | CFA Institute | 9 | 4 | 6.5 | 2 | 3 | 3 | 8 | 10 | 7 | 8.5 | **7.35** |
| Treasury | GARP / FRM | 7 | 4 | 5.5 | 0 | 1 | 3 | 4 | 10 | 8 | 9.0 | **5.75** |
| Treasury | ACCA | 8 | 3 | 5.5 | 0 | 1 | 3 | 4 | 10 | 6 | 8.0 | **5.55** |

### Calibration Notes
No scores changed. Rigor ordering (CFA 9 > ACCA 8 = ACT 8 > FRM 7 > CTP 6) reflects exam-stage count and study burden. Domain Fit ordering (CTP 10 > ACT 9 >> CFA 4 = FRM 4 > ACCA 3) reflects sharp divide between purpose-built treasury credentials and generalist finance credentials.

### Sanity Check Flags
- **CFA vs. ACT gap compression:** CFA (7.35) within 0.10 of ACT (7.45) despite Domain Fit of 4 vs. 9. For sourcing treasury practitioners, ACT is almost certainly better. Known artifact of weighting structure.
- **AFP/CTP geographic limitation:** Scores highest overall but weakest geographic reach (Geo 4). ACT may be better international partner despite lower composite.

### UNSCORED Items
- **AFP/CTP Geo Reach (scored 4):** Confirm whether AFP has formal presence in Asia beyond Gulf states or in Europe. If confirmed, Geo Reach moves to 6, Total to 7.90.
- **ACT Africa presence:** If weaker than believed, Geo Reach could drop to 4, Total to 7.25.

### Regions Credited

| Credential Body | USA & Canada | Latin America | Europe | Asia | Africa | Regions |
|---|---|---|---|---|---|---|
| AFP / CTP | Yes | No | No | Yes | No | 2 |
| ACT (UK) | No | No | Yes | Yes | Yes | 3 |
| CFA Institute | Yes | Yes | Yes | Yes | Yes | 5 |
| GARP / FRM | Yes | Yes | Yes | Yes | Yes | 5 |
| ACCA | Yes | Yes | Yes | Yes | Yes | 5 |

---

## Cluster 12: Tax (~3 workflows) — US-Specific

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Tax | AICPA (CPA) | 9 | 7 | 8.0 | 4 | 3 | 3 | 10 | 2 | 8 | 5.0 | **8.00** |
| Tax | NAEA (Enrolled Agent) | 6 | 9 | 7.5 | 2 | 1 | 1 | 4 | 2 | 7 | 4.5 | **5.85** |
| Tax | IPT (CMI) | 5 | 5 | 5.0 | 0 | 0 | 1 | 1 | 2 | 7 | 4.5 | **3.70** |
| Tax | ACAT (ATP/ATA) | 4 | 6 | 5.0 | 0 | 0 | 0 | 0 | 2 | 6 | 4.0 | **3.30** |

### Calibration Notes
- ACAT Domain Fit reduced from 7 to 6 during calibration. Original score equated ACAT with CPA; "structured products" workflow implies complexity beyond basic 1040 preparation.

### Sanity Check Flags
- **EA Dim 2 vs. sourcing utility mismatch:** EA scores 4 on pitch credibility vs CPA's 10, creating 2.15-point gap. However, every EA practices tax (no filtering needed), whereas only a fraction of CPAs specialize in tax. **Pitch strategy may benefit from pairing both -- lead with CPA for credibility, source from EA for precision.**

### UNSCORED Items
None. Cluster is narrow, US-specific, and well-documented.

### Regions Credited

| Credential Body | USA & Canada | Latin America | Europe | Asia | Africa | Regions |
|---|---|---|---|---|---|---|
| AICPA (CPA) | Yes | No | No | No | No | 1 |
| NAEA (EA) | Yes | No | No | No | No | 1 |
| IPT (CMI) | Yes | No | No | No | No | 1 |
| ACAT (ATP/ATA) | Yes | No | No | No | No | 1 |

*All four organizations scored 1 region. Structural to the "US-Specific" nature of the Tax cluster.*

---

## Cluster 13: Strategy / Management Consulting (~12 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Strategy / Mgmt Consulting | CMC -- ICMCI | 8 | 9 | 8.5 | 2 | 1 | 3 | 6 | 10 | 7 | 8.5 | **7.75** |
| Strategy / Mgmt Consulting | CGMA -- CIMA/AICPA | 9 | 5 | 7.0 | 2 | 1 | 3 | 6 | 10 | 8 | 9.0 | **7.10** |
| Strategy / Mgmt Consulting | ChMC -- CMI (UK) | 8 | 8 | 8.0 | 2 | 1 | 1 | 4 | 4 | 7 | 5.5 | **6.30** |
| Strategy / Mgmt Consulting | CBAP -- IIBA | 7 | 5 | 6.0 | 2 | 1 | 1 | 4 | 8 | 8 | 8.0 | **5.80** |
| Strategy / Mgmt Consulting | SPP -- ASP | 5 | 8 | 6.5 | 0 | 0 | 0 | 0 | 2 | 7 | 4.5 | **4.15** |
| Strategy / Mgmt Consulting | BSP -- BSI | 4 | 5 | 4.5 | 0 | 0 | 0 | 0 | 4 | 6 | 5.0 | **3.25** |

### Calibration Notes
- CMC vs ChMC: ICMCI (Swiss-registered international federation) and CMI (UK royal-chartered body) are genuinely separate organizations. No double-counting violation. Flag for sourcing deduplication in UK market.
- CGMA domain fit tension: Highest rigor (9) but only 5 on domain fit. CIMA's center of gravity is management accounting.
- Gate B ceiling: No credential in this cluster scores Gate B = 3. Management consulting lacks a universally recognized credential.
- SPP and BSP at Dim 2 = 0: Severe but accurate. Not recommended as sourcing partners.
- CMC/ChMC seniority skew: Both scored 7. Credentials skew toward independent/senior consultants (10-20+ years).

### Sanity Check Flags
- CMC Gate B = 1 vs CGMA Gate B = 1. Neither passes the non-specialist recognition bar.
- ChMC Geo = 4 may be generous. ChMC specifically is overwhelmingly UK. Strict scoring could drop to 2.
- CBAP Africa = N. IIBA has emerging African chapter presence; if verified, Geo could increase to 10.

### UNSCORED Items
- Prosci: Training-completion credential (workshop + test). Excluded.
- PMP, CFA, Six Sigma: Wrong cluster.
- AMCF, MCA, SMS: Trade/academic bodies, not credentialing organizations.

### Regions Credited

| Credential Body | USA & Canada | LatAm | Europe | Asia | Africa | Regions |
|---|---|---|---|---|---|---|
| CMC (ICMCI) | Yes | Yes | Yes | Yes | Yes | 5 |
| CGMA (CIMA/AICPA) | Yes | Yes | Yes | Yes | Yes | 5 |
| ChMC (CMI, UK) | No | No | Yes | Partial | Partial | 2 |
| CBAP (IIBA) | Yes | Yes | Yes | Yes | No | 4 |
| SPP (ASP) | Yes | No | No | No | No | 1 |
| BSP (BSI) | Yes | No | No | Partial | No | 2 |

---

## Cluster 14: Due Diligence / Transaction Advisory (~5 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Due Diligence / Txn Advisory | CFA Institute (CFA) | 9 | 7 | 8.0 | 4 | 3 | 3 | 10 | 10 | 8 | 9.0 | **8.80** |
| Due Diligence / Txn Advisory | AICPA (CPA + ABV) | 9 | 8 | 8.5 | 4 | 3 | 1 | 8 | 4 | 8 | 6.0 | **7.85** |
| Due Diligence / Txn Advisory | ACCA | 8 | 6 | 7.0 | 4 | 1 | 3 | 8 | 10 | 7 | 8.5 | **7.60** |
| Due Diligence / Txn Advisory | ASA (ASA-BV) | 7 | 7 | 7.0 | 2 | 0 | 1 | 3 | 4 | 8 | 6.0 | **5.60** |
| Due Diligence / Txn Advisory | AM&AA (CM&AA) | 4 | 9 | 6.5 | 2 | 0 | 1 | 3 | 4 | 8 | 6.0 | **5.35** |
| Due Diligence / Txn Advisory | NACVA (CVA) | 6 | 8 | 7.0 | 2 | 0 | 1 | 3 | 2 | 7 | 4.5 | **5.30** |

### Calibration Notes
- CFA vs. CPA+ABV Rigor (both 9): Different structures, comparable total burden. Both justified at 9.
- CM&AA Domain Fit (9) vs. Rigor (4): Widest rigor-fit gap. Only credential literally designed for M&A transaction advisory, but short training program and non-challenging exam cap rigor at 4.
- ACCA Domain Fit (6): General accounting qualification, not DD-specific. High total (7.60) driven by global institutional weight.
- Seniority -- CM&AA adjusted from 9 to 8 during calibration (senior skew).
- Gate B = 3 awarded only to CFA and CPA.
- AICPA Gate C = 1 despite domestic prestige: Limited international footprint.

### Sanity Check Flags
- **CFA Domain Fit (7) may appear low.** Charter designed for investment analysis, not DD/TA specifically. Level II covers valuation extensively, but portfolio management and ethics pull center of gravity away.
- No double-counting. No universities included.

### UNSCORED Items
None. All six organizations scored with sufficient confidence.

### Regions Credited

| Credential Body | USA & Canada | LatAm | Europe | Asia | Africa | Regions |
|---|---|---|---|---|---|---|
| CFA Institute | Yes | Yes | Yes | Yes | Yes | 5 |
| ACCA | Yes | Yes | Yes | Yes | Yes | 5 |
| AICPA (CPA + ABV) | Yes | Limited | No | No | No | 2 |
| ASA (ASA-BV) | Yes | No | Limited | No | No | 2 |
| AM&AA (CM&AA) | Yes | Limited | Limited | No | No | 2 |
| NACVA (CVA) | Yes | No | No | No | No | 1 |

---

## Cluster 15: Process / Operations Consulting (~8 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Process / Ops Consulting | ASQ (American Society for Quality) | 8 | 8 | 8.0 | 4 | 1 | 3 | 8 | 10 | 8 | 9.0 | **8.20** |
| Process / Ops Consulting | PMI (Project Management Institute) | 7 | 4 | 5.5 | 4 | 3 | 3 | 10 | 10 | 8 | 9.0 | **7.55** |
| Process / Ops Consulting | ABPMP International | 6 | 9 | 7.5 | 2 | 0 | 1 | 3 | 10 | 8 | 9.0 | **6.45** |
| Process / Ops Consulting | ASCM (formerly APICS) | 6 | 5 | 5.5 | 2 | 1 | 3 | 6 | 10 | 8 | 9.0 | **6.35** |
| Process / Ops Consulting | ACMP (Assoc. of Change Mgmt Professionals) | 7 | 6 | 6.5 | 2 | 0 | 1 | 3 | 10 | 8 | 9.0 | **5.95** |
| Process / Ops Consulting | IIBA (Intl Institute of Business Analysis) | 7 | 5 | 6.0 | 2 | 0 | 1 | 3 | 10 | 7 | 8.5 | **5.60** |

### Calibration Notes
No scores were changed during calibration. All sub-scores survived the comparative checks. Rigor ordering (ASQ 8 > PMI = ACMP = IIBA 7 > ABPMP = ASCM 6) is defensible. Domain Fit ordering (ABPMP 9 > ASQ 8 > ACMP 6 > ASCM = IIBA 5 > PMI 4) correctly places ABPMP first as the credential most specifically designed for business process management.

### Sanity Check Flags
- **PMI ranking #2 despite Domain Fit of 4.** Total of 7.55 driven almost entirely by perfect Dim 2 (10). Naming "PMP" in a pitch for process/operations consulting may raise "but that's project management" objection. ABPMP (domain fit 9, total 6.45) and ACMP (domain fit 6, total 5.95) rank lower despite being more directly relevant. Mathematically correct but **human review recommended** on whether PMI's prestige premium is warranted for this cluster's sourcing needs.

### UNSCORED Items
None.

### Regions Credited

| Credential Body | USA & Canada | Latin America | Europe | Asia | Africa | Regions |
|---|---|---|---|---|---|---|
| ASQ | Yes | Yes | Yes | Yes | Yes | 5 |
| PMI | Yes | Yes | Yes | Yes | Yes | 5 |
| ABPMP | Yes | Yes | Yes | Yes | Yes | 5 |
| ASCM (APICS) | Yes | Yes | Yes | Yes | Yes | 5 |
| ACMP | Yes | Yes | Yes | Yes | Yes | 5 |
| IIBA | Yes | Yes | Yes | Yes | Yes | 5 |

---

## Cluster 16: Analytics / Quantitative (~6 workflows)

| Workflow Cluster | Credential Body | Rigor (1-10) | Domain Fit (1-10) | Dim 1 | Gate A (0/2/4) | Gate B (0/1/3) | Gate C (0/1/3) | Dim 2 | Geo Reach (1-10) | Seniority (1-10) | Dim 3 | TOTAL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Analytics / Quantitative | RSS -- CStat (Chartered Statistician) | 7 | 8 | 7.5 | 2 | 1 | 3 | 6 | 6 | 6 | 6.0 | **6.75** |
| Analytics / Quantitative | ASA -- PStat (Accredited Professional Statistician) | 7 | 8 | 7.5 | 2 | 1 | 3 | 6 | 4 | 6 | 5.0 | **6.55** |
| Analytics / Quantitative | INFORMS -- CAP (Certified Analytics Professional) | 6 | 9 | 7.5 | 2 | 0 | 1 | 3 | 4 | 8 | 6.0 | **5.85** |
| Analytics / Quantitative | SAS Institute -- SAS Certified Data Scientist | 4 | 6 | 5.0 | 2 | 1 | 1 | 4 | 10 | 5 | 7.5 | **5.20** |

### Calibration Notes
No scores were changed during calibration. All gaps between adjacent organizations reviewed and found defensible.

### Sanity Check Flags
- **INFORMS CAP has highest Domain Fit (9) yet ranks third** due to Dim 2 = 3. If the Anthropic buyer is an ML team lead familiar with INFORMS, pitch credibility penalty may be overstated. Flag for human review.
- **Cluster ceiling effect:** All four organizations score between 5.20 and 6.75. No dominant gatekeeper credential exists for analytics/quantitative work. Sourcing may need to rely more on technical skill assessment (GitHub, Kaggle, portfolio review) than credential body partnerships alone.

### UNSCORED Items
- INFORMS CAP Geo Reach: Europe credited with lower confidence. If not confirmed, Total drops to 5.65.
- ASA PStat membership numbers: Active holder count could not be verified. If very small (<1,000), practical sourcing utility is limited.
- RSS CStat Africa/Asia presence: Commonwealth connections credited for 3 regions. Live verification would strengthen score.

### Regions Credited

| Credential Body | Regions Credited | Basis |
|---|---|---|
| RSS -- CStat | 3: Europe, Asia, Africa | UK HQ; Commonwealth countries (India, Singapore, Hong Kong, Malaysia); South Africa, Kenya, Nigeria |
| ASA -- PStat | 2: USA & Canada, Europe (marginal) | US HQ and chapters; some international membership but no formal chapter infrastructure |
| INFORMS -- CAP | 2: USA & Canada, Europe (marginal) | US HQ, US testing centers; EURO-INFORMS conferences |
| SAS Institute | 5: USA & Canada, Europe, Asia, Latin America, Africa | Offices in US, UK, Germany, France; Japan, China, India, Singapore; Brazil, Mexico; South Africa |

---

## Cross-Cluster Summary: Top-Ranked Organizations by Cluster

| # | Cluster | #1 Organization | Score | #2 Organization | Score |
|---|---|---|---|---|---|
| 1 | IB / Valuation | CFA Institute | 8.70 | ASA BV | 6.80 |
| 2 | Asset Mgmt / Portfolio | CFA Institute | 9.55 | GARP/FRM | 7.60 |
| 3 | PE / VC | CFA Institute | 8.45 | CAIA | 6.60 |
| 4 | Hedge Fund / Public Markets | CFA Institute | 9.05 | CAIA | 6.90 |
| 5 | Commercial Banking / Lending | CFA Institute | 7.85 | GARP/FRM | 6.60 |
| 6 | FP&A / Corporate Finance | CFA Institute | 8.70 | IMA/CMA | 7.95 |
| 7 | Accounting / Audit | AICPA/CPA | 8.95 | ACCA | 8.35 |
| 8 | Insurance | SOA (FSA/ASA) | 8.85 | CAS (FCAS/ACAS) | 7.90 |
| 9 | Risk Management | GARP/FRM | 9.05 | ISACA/CRISC | 7.35 |
| 10 | Compliance / Regulatory | IAPP | 7.40 | ACAMS | 7.35 |
| 11 | Treasury | AFP/CTP | 7.70 | ACT (UK) | 7.45 |
| 12 | Tax | AICPA/CPA | 8.00 | NAEA/EA | 5.85 |
| 13 | Strategy / Mgmt Consulting | CMC/ICMCI | 7.75 | CGMA/CIMA-AICPA | 7.10 |
| 14 | Due Diligence / Txn Advisory | CFA Institute | 8.80 | AICPA CPA+ABV | 7.85 |
| 15 | Process / Ops Consulting | ASQ | 8.20 | PMI | 7.55 |
| 16 | Analytics / Quantitative | RSS/CStat | 6.75 | ASA/PStat | 6.55 |

---

*End of scoring output. All 16 clusters scored. 91 total credential body evaluations across all clusters.*
