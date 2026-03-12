# SME Sourcing & Delivery: Ideation Working Document
## For Anthropic Workflow Review Services Proposal

*Working draft — March 2026*

---

## Part 1: Orienting to the Problem

### What Anthropic Has Today
Anthropic uses individual SME contractors at ~$250/hr to review and evaluate Claude's performance on domain-specific workflows. These SMEs prioritize, annotate, and validate AI outputs across finance, consulting, and other verticals. The workflow spreadsheets reviewed here contain **229 finance workflows** and **50 consulting workflows**, each rated P0/P1/P2 by panels of 5-6 expert reviewers.

### What the Workflow Data Reveals About the Work

The workflows cluster into **distinct skill families** that map to different credential pools. This isn't one homogeneous need — it's a portfolio of needs with very different talent supply characteristics.

**Finance breaks into roughly 10 sub-domains:**

| Cluster | # Workflows | Key Skill Markers | Credential Signals |
|---------|------------|-------------------|-------------------|
| **Investment Banking / Valuation** | ~62 (IB-tagged) | DCF, LBO, M&A modeling, pitchbooks, CIMs, fairness opinions | MBA/MSF + IB experience, CFA |
| **Asset Management / Portfolio** | ~30 (AM-tagged) | Portfolio attribution, rebalancing, investment thesis, RFP responses | CFA, CAIA, portfolio mgmt experience |
| **Private Equity / VC** | ~34 (VC/PE-tagged) | IC memos, cap tables, term sheets, 100-day plans, LP reporting | PE/VC deal experience, MBA |
| **Hedge Fund / Public Markets** | ~24 (HF-tagged) | Stock pitch memos, variant perception, catalyst tracking, channel checks | Buy-side research, CFA |
| **Commercial Banking / Lending** | ~15 (CB-tagged) | Credit memos, loan underwriting, covenant monitoring, CRE analysis | Credit analyst experience, banking certs |
| **FP&A / Corporate Finance** | ~25 | AOP, variance analysis, rolling forecasts, board decks, scenario planning | Corporate finance / FP&A experience |
| **Accounting / Audit** | ~14 | Month-end close, SOX testing, audit workpapers, revenue recognition | CPA or equivalent, audit experience |
| **Insurance** | ~14 | Underwriting, claims adjudication, actuarial reserves, cat modeling, NAIC reporting | ACAS/FCAS, CPCU — **US-specific** |
| **Risk Management** | ~15 | VaR, credit risk, CECL, stress testing (CCAR/DFAST), RCSA | FRM, PRM, quant finance |
| **Compliance / Regulatory** | ~15 | SAR filing, KYC, OFAC screening, HMDA, Fair Lending | CAMS, compliance experience — **partially US-specific** |
| **Treasury** | ~14 | Cash forecasting, FX hedging, liquidity stress testing, debt covenants | CTP, treasury mgmt |
| **Tax** | ~3 | Tax returns, audit examination, structured products | CPA/EA — **US-specific** |

**Consulting breaks into ~6 sub-domains:**

| Cluster | # Workflows | Key Skill Markers |
|---------|------------|-------------------|
| **Strategy / Management Consulting** | ~12 | Client findings decks, business cases, competitive intel, benchmarking, frameworks |
| **Due Diligence / Transaction Advisory** | ~5 | Commercial/operational/financial DD, valuation |
| **Compliance / Regulatory Consulting** | ~15 | AML/KYC, SOX, regulatory gap assessments, mock exams, SARs |
| **Process / Operations** | ~8 | Process mapping, implementation roadmaps, SOPs, change management |
| **Analytics / Quantitative** | ~6 | Statistical modeling, survey design, KPI dashboards, predictive analytics |
| **Organizational / Stakeholder** | ~4 | Org design, stakeholder analysis, risk matrices |

### The Critical Observation

Not all workflows are equally hard to staff. The difficulty gradient runs roughly like this:

**Easier to source globally** (transferable skills, international standards):
- DCF / LBO / valuation modeling (IFRS or GAAP — math is math)
- Financial statement analysis and three-statement modeling
- Portfolio analytics and attribution
- Statistical / quantitative analysis
- Strategy frameworks and competitive intelligence
- Process mapping and operational analysis

**Harder to source globally** (US-specific regulation, licensing, or market knowledge):
- US insurance (state-level regulation, NAIC, admitted vs. surplus lines)
- US tax (IRC, Form 1040, state conformity)
- US compliance/regulatory (HMDA, Fair Lending, CCAR/DFAST, Dodd-Frank specifics)
- SAR/BSA/AML (FinCEN-specific procedures)

**In between** (international standards exist but US nuance matters):
- Commercial lending (Basel standards exist, but US bank exam cycle is specific)
- Risk management (VaR and CECL concepts are global, but Fed stress testing is US)
- SOX compliance (PCAOB standards, but Big 4 operates globally)

---

## Part 2: Sourcing Pools by Workflow Cluster

The question: **Where do "clumps" of people exist who could do 1-6 month sprint review work?**

### Sourcing Pool Type Taxonomy

Before mapping sources to domains, here are the **types of pools** worth considering:

1. **University faculty & advanced PhD students** — Deep domain knowledge, often available for project-based consulting, publication-motivated
2. **Professional exam candidates / recent passers** — CFA L3 candidates, FRM candidates, actuarial exam students — actively studying the exact material, highly motivated, often underemployed relative to their knowledge
3. **Big 4 / consulting alumni in lower-cost markets** — People who did 3-5 years at Deloitte/PwC/EY/KPMG in Nairobi, Lagos, Johannesburg, Cairo — trained on the methodology, often now in middle-management or independent consulting
4. **Diaspora professionals** — African-born, US/UK-trained finance professionals who've returned or work remotely from home countries
5. **Professional association members** — CFA Society chapters, ACCA members, actuarial society members in African countries
6. **Freelance/gig platforms with verified credentials** — Toptal, Braintrust, Andela alumni (for the quant/analytics workflows)

### Source Map by Workflow Cluster

#### 1. Investment Banking / Valuation (~62 workflows)

| Source | Why | Availability for Sprints | Vetting Signal |
|--------|-----|-------------------------|----------------|
| **CFA Institute exam candidates (L2/L3) in Africa** — Kenya, South Africa, Nigeria, Egypt have 5,000+ candidates/year | Actively studying valuation, financial analysis, corporate finance | **High** — exam prep is seasonal, between windows they're available | CFA exam pass/progress, employer history |
| **MBA finance concentrations at UCT GSB, Lagos Business School, Strathmore** | Trained in case-based valuation, M&A analysis | **High** — MBA students have project slots, recent grads seeking work | School selectivity, course grades, capstone projects |
| **IB analyst/associate alumni from African bulge-bracket offices** (Citi, JPM, Goldman presence in Joburg, Lagos) | 2-4 years of actual deal execution, pitchbook/model experience | **Medium** — these people have jobs, but moonlighting or between-roles windows exist | LinkedIn deal history, employer verification |
| **Chartered Financial Analyst Society local chapters** (CFA Society South Africa, CFA Society East Africa) | Ready-made professional networks with verified credentials | **High** — societies actively facilitate project-based work | CFA charterholder status, society membership |
| **ACCA / CIMA qualified professionals** in East/West Africa | UK-standard accounting/finance qualification, strong analytical base | **High** — ACCA has 250,000+ members in Africa | ACCA/CIMA membership number verification |

#### 2. Asset Management / Portfolio (~30 workflows)

| Source | Why | Availability | Vetting Signal |
|--------|-----|-------------|----------------|
| **CFA charterholders in South Africa, Kenya, Nigeria** | Direct credential match for portfolio analysis work | High | Charterholder verification through CFA Institute |
| **Portfolio managers / analysts at African asset managers** (Allan Gray, Coronation, Old Mutual, Sanlam) | Real portfolio management experience with global standard methodologies | Medium — employed, but willing to consult | Employer + AUM track record |
| **University of Cape Town — Masters in Financial Management / MPhil Finance** | Quantitative finance training, portfolio theory | High | Academic record, research output |
| **Actuarial science students** (UCT, Stellenbosch, Wits) — cross-trained | Strong quantitative skills, understand risk-return frameworks | High — actuarial pipeline is long, students available for project work | Exam progress, university standing |

#### 3. Commercial Banking / Lending (~15 workflows)

| Source | Why | Availability | Vetting Signal |
|--------|-----|-------------|----------------|
| **Credit analysts at major African banks** (Standard Bank, FirstRand, Ecobank, Access Bank, Zenith Bank) | Daily credit memo writing, loan analysis, covenant monitoring | Medium | Employment verification, credit certification |
| **Banking academy graduates** (e.g., Kenya School of Monetary Studies, FITC Nigeria) | Trained specifically in commercial banking workflows | High | Certification records |
| **University of Pretoria / Wits — Banking & Finance programs** | Structured banking curriculum | High | Academic record |
| **Microfinance / DFI professionals** (AfDB, IFC local staff) | Credit analysis in development context, often over-qualified | Medium | Institutional affiliation |

#### 4. Insurance (~14 workflows) — **US Partnership Required**

| Source | Why | Availability | Vetting Signal |
|--------|-----|-------------|----------------|
| **US actuarial exam candidates (ASA track)** at Temple, Illinois, UConn, Wisconsin | Actively studying the exact loss reserving, pricing, cat modeling material | **High** — exam-season availability | Exam progress (SOA/CAS records) |
| **Risk management & insurance programs** — St. John's Tobin, Georgia State Robinson, Temple Fox | Dedicated insurance curriculum with P&C, underwriting, claims | High — students available | Program enrollment, internship history |
| **South African actuaries (ASSA fellows)** — for transferable skills | SA has one of the strongest actuarial professions outside US/UK; ASSA exams are rigorous | High | ASSA membership — but needs US regulatory overlay |
| **CPCU candidates / recent designees** via The Institutes | Studying commercial lines underwriting, claims, reinsurance | High | CPCU exam progress |
| **Former US insurance carrier analysts** on career breaks or freelancing | Direct US P&C experience | Medium | CPCU, ARM, AU designations + employer history |

#### 5. Risk Management (~15 workflows)

| Source | Why | Availability | Vetting Signal |
|--------|-----|-------------|----------------|
| **FRM (Financial Risk Manager) candidates** — GARP has growing African enrollment | Studying VaR, credit risk, CECL, stress testing | High | FRM exam progress via GARP |
| **Quantitative finance programs** — UCT MPhil Quant Finance, Wits MSc Mathematical Finance | Advanced quant risk modeling, derivatives pricing | High | Academic record, thesis topic |
| **Risk professionals at SA banks** (SA banks are Basel III compliant, sophisticated risk frameworks) | Real-world ICAAP, stress testing, RCSA experience | Medium | Employer + professional cert |
| **University of Nairobi — MSc Financial Engineering** | Quant methods, risk analytics | High | Academic record |

#### 6. Compliance / Regulatory (~15 workflows) — **Partially US-Specific**

| Source | Why | Availability | Vetting Signal |
|--------|-----|-------------|----------------|
| **CAMS (Certified Anti-Money Laundering Specialist) holders in Africa** — ACAMS has chapters in South Africa, Nigeria, Kenya | AML/KYC/SAR methodology is increasingly global (FATF standards) | High | CAMS certification |
| **Big 4 regulatory advisory alumni in Africa** (Deloitte, PwC, EY, KPMG all have compliance practices in Joburg, Lagos, Nairobi) | Trained on US/UK regulatory frameworks serving multinational clients | Medium-High | Big 4 employment verification |
| **US compliance officers** on Upwork/Toptal for the specifically US pieces (HMDA, Fair Lending) | Direct US regulatory experience | Medium | CRCM, CAMS, employer history |
| **Law faculty at African universities** with financial regulation specialization | Deep regulatory knowledge, often consulting-available | Medium | Publication record, bar/qualification status |

#### 7. FP&A / Corporate Finance (~25 workflows)

| Source | Why | Availability | Vetting Signal |
|--------|-----|-------------|----------------|
| **ACCA / CIMA professionals in East/West/Southern Africa** | Core competency in management accounting, budgeting, variance analysis | High | Professional membership |
| **FP&A professionals at multinational Africa HQs** (Unilever, Nestlé, MTN, Safaricom) | Run the exact AOP, forecast, variance, board deck workflows | Medium | Employer verification |
| **University accounting/finance lecturers** | Deep technical knowledge, flexible scheduling | High | Academic position, publication record |

#### 8. Strategy Consulting (~12 consulting workflows)

| Source | Why | Availability | Vetting Signal |
|--------|-----|-------------|----------------|
| **MBB alumni in Africa** (McKinsey Joburg/Lagos/Nairobi, BCG, Bain) | Trained on the exact frameworks, slide-making, client deliverables | Medium — employed, but moonlighting/between-roles | LinkedIn, firm verification |
| **MBA students at top African business schools** (UCT GSB, Strathmore, LBS) | Case-method trained, consulting-oriented | High | School admission selectivity |
| **African Development Bank / World Bank consultants** | Policy and strategy analysis at scale | Medium | Institutional affiliation |
| **Ashesi, ALU graduates** (entrepreneurship/business focus) | Analytical training, English-fluent, young/available | High | University verification |

#### 9. Analytics / Quantitative (~6 consulting + cross-cutting)

| Source | Why | Availability | Vetting Signal |
|--------|-----|-------------|----------------|
| **Data science / statistics programs** at African universities (UCT, Makerere, Addis Ababa) | Statistical modeling, survey design, predictive analytics | High | Academic record, GitHub/Kaggle |
| **Andela alumni / African tech talent platforms** | Trained in structured analytical work, familiar with remote sprint models | High | Platform track record |
| **AIMS (African Institute for Mathematical Sciences) graduates** — Rwanda, South Africa, Cameroon, Ghana, Senegal, Tanzania | World-class quantitative training, specifically designed to develop African mathematical talent | **Very High** — AIMS explicitly produces people looking for applied work | AIMS degree + thesis |

---

## Part 3: The Value Proposition — Reframed

### Two Models for Improving a Workflow

There are fundamentally two ways to figure out how a workflow should work:

**Model A — Top-Down Expert:** Ask one brilliant expert how it *should* work. Build a reference standard from their mental model. The problem: you get one person's opinionated framework. Implementation risk is massive because the end product has to fit back into the hands of the hundreds of mid-level practitioners who actually do this work every day. Few experts = lots of single-point-of-failure risk. You're unlikely to hit genius, especially across 229+ diverse workflows. And the expert's model may be elegant but disconnected from how the work actually gets done in the wild.

**Model B — Bottom-Up Practitioner Census:** Ask 100-200 mid-level practitioners how they *experience* the workflow today. From that diversity of real-world practice, abstract a model. Use AI to iterate on and improve the core operations. Return a solution that fits the actual population of users — because those users are the ones who will either adopt the results or be made useless by an ivory-tower abstraction. This approach is statistically robust: the signal from 200 diverse, qualified practitioners is fundamentally more reliable than from 5 brilliant ones for the purpose of training an AI that needs to serve the *distribution* of real users, not the 99th-percentile expert.

**This is the core insight for the proposal.** Anthropic doesn't need Claude to perform like one Goldman MD's mental model of a DCF. They need Claude to perform in a way that's useful to the *distribution* of people who actually build DCFs — the VP at a middle-market bank, the associate at a regional PE shop, the FP&A analyst at a SaaS company. The workflow review data already shows this: Avery's commentary explicitly notes that priority depends entirely on which seat you're evaluating from (IB MD vs. AM MD vs. Risk MD vs. VC partner). One expert's view is one data point. Two hundred practitioners' views *are* the ground truth.

### What Anthropic Actually Needs (And What Their Current Model Can't Deliver)

Anthropic is in a global AI race. Cutting corners on model training would be profoundly stupid. The value proposition is **not** "we're cheaper." Leading with price in this context sounds like lower quality, and any procurement person at Anthropic would rightfully be suspicious.

**The actual bottleneck is sourcing speed and cohort scale.**

Anthropic's current model: recruit individual $250/hr contractors one at a time. This gets them ~20 people for a workflow review sprint. That's peanuts when you're trying to evaluate Claude's performance across 279 workflows spanning 16 sub-domains. Their internal team knows what they need but is too busy running model training cycles to build out the sourcing and operational infrastructure for finding, vetting, and deploying hundreds of qualified reviewers.

**The win for Anthropic is:**
- Getting 10x the qualified reviewers in half the deployment time
- Broader coverage across the full workflow landscape (not 20 people stretched thin across 279 workflows, but focused cohorts mapped to specific sub-domains)
- Statistically meaningful sample sizes for evaluation (not 1-2 opinions per workflow, but 10-20)
- A repeatable process that doesn't depend on their team doing the sourcing legwork every sprint cycle

**The pitch, cleanly:**

> *"You need 200 qualified reviewers deployed across your workflow domains in 2 weeks, not 20 over 2 months. I can build the sourcing and operational infrastructure to make that happen. Global talent pools mean I can do it at a price point that lets you buy 10x the coverage — which gives you fundamentally better training signal. The savings aren't the point. The coverage, speed, and statistical depth are the point. The savings are what make the coverage and speed economically viable."*

### Why "Sourcing" Is the Real Service

The product isn't labor. The product is the **sourcing infrastructure**: the ability to identify, vet, activate, and quality-control domain-specific cohorts on demand. This is an operational problem, not a staffing problem. It requires:

1. **Pre-mapped talent pools** — knowing exactly which professional communities, university programs, and credential pipelines feed each workflow cluster
2. **Rapid vetting at scale** — credential verification, domain competency testing, and calibration sprints that can process 200 candidates in a week, not 20 in a month
3. **Sprint deployment ops** — onboarding, briefing, quality monitoring, and cohort management for short-burn (1-3 month) engagements
4. **Quality signal generation** — not just "pass/fail" review, but structured evaluation data with inter-rater reliability, disagreement flagging, and systematic error categorization

The lower cost per reviewer is real and it matters — but it matters because it's what makes 200 reviewers economically viable instead of 20. It's the lever that unlocks scale, not the value proposition itself.

### The Operational Background as Differentiator

This isn't a staffing pitch. It's an operational pitch. The question for Anthropic isn't "can we find cheaper SMEs?" — it's "who can build us the infrastructure to source and deploy qualified reviewer cohorts at 10x our current scale, across multiple domains, on a sprint cadence?" That's a logistics and operations problem. The person who solves it needs to understand both the domain requirements (what makes someone qualified to review a DCF workflow vs. a SAR investigation workflow) and the operational mechanics (how to find 200 of those people, vet them in a week, deploy them for a month, and rotate to the next domain).

---

## Part 4: Operational Delivery Model

### Why One Model, Not Five

Mixed staffing models are exponentially harder to deliver. Managing multiple tiers with different compensation, different vetting processes, different quality calibration systems, and handoff points between them — that's not a lean operation, that's a staffing agency. The coordination overhead eats the margin and recreates exactly the complexity that makes the current $250/hr model slow. Keep it flat.

### The Model: Pop-Up Sprint Cohorts (Single Tier, High Utilization)

**How it works:** For each domain sprint Anthropic needs, recruit, vet, and deploy a cohort of 30-50 qualified practitioners at a single competency tier. Full-time commitment for a defined sprint (preference: 1 month, up to 3 months, never longer than 6). High utilization, short burn. When the sprint ends, the cohort disbands. Rinse and repeat for the next domain.

**The talent profile is consistent across sprints:** Mid-career practitioners with 3-8 years of domain experience and a relevant professional credential (CFA, ACCA, FRM, CAMS, etc.) or advanced degree. Not students. Not senior executives. The people who actually *do* the work every day. These are the people whose collective experience *is* the ground truth for how a workflow should function.

**Why this profile specifically:**
- They know the workflow from doing it, not from teaching it or supervising it
- They're the population Claude actually needs to serve
- 50 of them at $30-60/hr gives you more coverage than 5 at $250/hr, with statistically meaningful sample sizes
- They're available for sprint commitments in ways that senior people aren't

**Sprint economics (illustrative):**
- 40 practitioners × 160 hrs/month × $45/hr avg cost = $288K/month raw labor
- + 30-40% markup for ops/QA/management = ~$375-400K/month delivered to Anthropic
- Compare: 20 US contractors × 40 hrs/month × $250/hr = $200K/month for *half* the coverage
- Anthropic pays ~2x for ~4x the reviewer-hours and ~10x the statistical depth
- OR: Anthropic pays the same $200K and gets 25 practitioners at 80 hrs/month — still 2-3x the coverage of their current model

**The key operational constraint: high utilization, short burn.**

This means the sourcing infrastructure has to be able to spin up cohorts fast. The vetting can't take 6 weeks. The preference for cost of vetting, training, and QC is to maximize hours-per-person rather than spreading thin across many people working few hours. A practitioner doing 160 hours in a month is far more efficient to onboard, calibrate, and quality-monitor than one doing 20 hours over 3 months.

**Sourcing channels for sprint cohorts (by activation speed):**

*Fast activation (1-2 weeks):*
- Professional association job boards and member networks (CFA societies, ACCA, ACAMS chapters)
- University career services at target programs (direct relationship required)
- Alumni networks from Big 4 African offices
- Existing freelancer platforms with credential filters (Toptal, Braintrust)

*Medium activation (2-4 weeks):*
- Direct outreach to practitioners at target employers (LinkedIn recruiter-style)
- Exam prep community partnerships (CFA, FRM study groups)
- Conference and professional event recruiting

*Pipeline building (ongoing):*
- University partnership agreements for recurring access to graduating cohorts
- Professional association sponsorships that include recruiting access
- Referral networks from successful sprint alumni

### What Needs to Be True for This to Work

1. **Pre-built sourcing relationships** in 3-5 key talent markets before the first sprint
2. **A vetting process that takes days, not weeks** — credential verification + a 2-hour domain competency assessment + a paid 5-hour calibration trial
3. **A sprint playbook** that's reusable across domains — onboarding, briefing, daily QA, output collection, cohort management
4. **Clear scope agreements with Anthropic** — which workflows, how many reviewers, what output format, what quality metrics
5. **Payment infrastructure** that works in target markets (this is non-trivial in some African countries — mobile money, international transfers, tax withholding)

---

## Part 5: Highest-Leverage Starting Points

If we had to pick **2-3 domain clusters** to pilot that maximize the chance of demonstrating value to Anthropic:

### Pilot Candidate 1: Investment Banking / Valuation
- **Why:** Largest cluster (62 workflows), highest economic value to Anthropic's customers, deeply technical, globally-standardized methodology
- **Sourcing:** CFA candidates/charterholders in South Africa + Kenya + Nigeria; MBA finance students at UCT/LBS/Strathmore
- **Advantage:** Math doesn't have a nationality. A DCF is a DCF. IFRS vs. GAAP differences are documentable and learnable.
- **Risk:** IB-specific jargon and deal conventions may require calibration

### Pilot Candidate 2: Risk Management
- **Why:** Highly quantitative, growing regulatory importance, FRM/PRM certification is global, South African banks run sophisticated Basel III programs
- **Sourcing:** FRM candidates, UCT/Wits quant finance programs, AIMS graduates, SA bank risk departments
- **Advantage:** Quant skills are the hardest for Anthropic to find cheaply. Most scarce = most valuable.
- **Risk:** US stress testing specifics (CCAR/DFAST) need US supplementation

### Pilot Candidate 3: Strategy / Management Consulting
- **Why:** High-value Anthropic use case, framework-based (teachable/rubric-able), large pool of MBA-trained talent globally
- **Sourcing:** MBB alumni in African offices, top MBA programs, development bank consultants
- **Advantage:** Consulting deliverables are structurally similar (deck + analysis + recommendation) — amenable to rubric-based evaluation
- **Risk:** "Quality of thinking" is harder to rubric-ize than "accuracy of a DCF"

### The One I'd Actually Lead With:
**Investment Banking / Valuation.** It's the largest cluster, the skills are most globally transferable, the CFA pipeline in Africa is massive and growing, and the output quality is objectively measurable (a model either ties out or it doesn't). If you can demonstrate that 5 CFA charterholders in Nairobi can evaluate Claude's DCF output as well as a $250/hr contractor in New York, you've proven the entire business model.

---

## Part 6: Vetting Architecture (Sketch)

The micro-targeting differentiation you described — vetting on credentials, publications, social media, custom evals — is the moat. Here's a rough framework:

### Stage 1: Credential Screen (Automated)
- Professional certification status (CFA, ACCA, FRM, CAMS, etc.) — verified against issuing body
- Academic degree and institution — verified against university records
- Minimum years of relevant experience — self-reported, cross-referenced with LinkedIn

### Stage 2: Domain Competency Test (Semi-Automated)
- Custom-built assessment per workflow cluster (30-60 min)
- Example: For IB/Valuation — given a set of company financials, build a simple DCF, identify 5 errors in a provided model, write a 1-paragraph investment thesis
- Scored against rubric by Tier 3 experts
- Establishes baseline competency AND creates calibration data

### Stage 3: Publication / Thought Leadership Screen (Manual)
- Google Scholar publication record in relevant domain
- Conference presentations, working papers
- Professional blog/newsletter writing
- Social media presence indicating domain engagement (Finance Twitter, LinkedIn thought leadership)
- NOT required, but weighted positively — indicates someone who thinks about the domain, not just executes

### Stage 4: Calibration Sprint (Paid Trial)
- 5-10 hours of actual review work on pre-scored gold-standard outputs
- Measure agreement with established expert ratings
- Inter-rater reliability score becomes part of reviewer profile
- This is the real filter — and it doubles as training

### Stage 5: Ongoing Quality Monitoring
- Periodic gold-standard items seeded into production review queues
- Drift detection: reviewers whose scores diverge from consensus get flagged
- Quality-adjusted pay: higher reliability = higher rate (your sliding scale concept)

---

## Key Strategic Insights (Conversation Log)

### 1. The "100 Practitioners" Method Is the Actual IP

The bottom-up methodology — aggregate how 100-200 mid-level practitioners actually experience a workflow, abstract a model from that, iterate with AI, return a solution — isn't just an operational approach. It's a *proprietary evaluation methodology* that should be named, documented, and pitched as such. It's the intellectual core of the proposal.

Why it works specifically for AI training: Anthropic doesn't need Claude to match one expert's mental model. They need Claude to be useful to the *distribution* of real practitioners. The workflow review data already proves the current model's limitation — Avery's commentary explicitly notes that the "right" prioritization depends entirely on which seat you're in (IB MD vs. AM MD vs. Risk MD vs. VC partner). Five experts give you five opinions. Two hundred practitioners give you the actual ground truth of how the work gets done.

This reframes the entire engagement from "staffing service" to "evaluation methodology provider that happens to also supply the practitioners."

### 2. The Pricing Trap — Don't Lead with Cost

Leading with "we're cheaper" in the context of AI model training for a company in a global AI race is actively counterproductive. It signals lower quality. Any procurement person at Anthropic would rightfully be suspicious.

The right framing: Anthropic can pay ~2x their current spend and get ~4x the reviewer-hours and ~10x the statistical depth. OR they can pay the same amount and get 2-3x coverage. Either way, the value is in the *coverage and speed*, not the unit cost. The global talent pool is what makes that math work — it's the enabler, not the headline.

The pitch should never mention "cost savings" upfront. It should say: "You need 200 qualified reviewers in 2 weeks, not 20 over 2 months. Here's how we do that." The economics follow naturally in the conversation.

### 3. One Staffing Model, Not Five — Complexity Is the Enemy

Mixed tiers (students → professionals → senior experts) sounds elegant but creates exponential operational complexity: three compensation structures, three vetting processes, three calibration systems, handoff failure modes between tiers. That's a staffing agency, not a lean operation. The coordination overhead eats the margin and recreates the sluggishness of the current $250/hr model.

The right model: One talent profile (mid-career practitioners, 3-8 years experience, relevant credential), one vetting process, one deployment cadence. Keep it flat. The moat is in the sourcing infrastructure and the methodology, not in organizational complexity.

### 4. The Competitive Moat vs. Scale AI / Appen / Surge AI

These companies all have Africa operations. Their model: volume labor for general annotation. General-purpose annotators following rubrics. The differentiation here is fundamentally different — *domain-specific practitioner cohorts*. People who actually write credit memos, build DCFs, file SARs, and run covenant tests for a living. That's a completely different talent pool that Scale/Appen can't easily access because their entire recruiting infrastructure is built for the other model.

This distinction has to be razor-sharp in any pitch: "We're not competing with Scale AI. They provide annotators. We provide practitioners."

### 5. The "Sprint" Model Preference: High Utilization, Short Burn

The preference for cost of vetting, training, and QC is to maximize hours-per-person. A practitioner doing 160 hours in one month is far more efficient to onboard, calibrate, and quality-monitor than one doing 20 hours over 3 months. This pushes toward full-time-for-one-month as the ideal engagement pattern, with up to 3 months for complex domains, hard cap at 6 months.

This has implications for the talent pool: you need people who can commit full-time for short periods. That favors between-jobs professionals, exam candidates between windows, academics during breaks, and freelancers — not people in full-time corporate roles.

### 6. Avery's Commentary Validates the Whole Thesis

Avery's extended commentary in the Finance workflow review is a gift. She explicitly articulates the problem the "100 practitioners" model solves: *"The challenge here is that there are a number of ways to think about this, and a great deal of these workflows would be prioritized differently based on the lens of the person prioritizing them."* She walks through how a Goldman MD in IB, vs. AM, vs. risk, vs. VC would each prioritize completely differently.

This is Anthropic's own data proving that their current 5-reviewer model is structurally insufficient. Quote this in the pitch (with permission). It's the strongest possible setup for the "you need 200 diverse practitioners, not 5 brilliant ones" argument.

### 7. Jeff's "Don't Have Enough Info" Data Point

Jeff marked 115 of 229 finance workflows (50%!) as "Don't have enough info." This isn't a knock on Jeff — it's proof that even qualified SMEs don't span the full domain. No single expert covers it all. The current model's coverage gap is built into the data. The proposal should frame this not as a criticism but as an observation: *"Your own review data shows that individual experts, no matter how qualified, have natural coverage limits. Our model addresses this structurally by deploying sub-domain-specific cohorts that ensure every workflow cluster has reviewers who know it from direct daily experience."*

---

## What's Still Open / Next Steps

1. **Anthropic's actual sprint cadence and domain roadmap** — Which domains are they ramping next? This determines where to build sourcing relationships first.
2. **Positioning validation** — The pitch is "faster cohorts at scale, not cheaper labor." Does this land with the right people at Anthropic? Who is the buyer — the ML team lead who needs reviewers, or procurement?
3. **Proof of concept design** — What does a credible pilot look like? Probably: pick one workflow cluster (IB/Valuation), source 30-40 practitioners in 2 weeks, run a 1-month sprint, deliver structured evaluation data, and benchmark quality against Anthropic's existing contractor output on the same workflows.
4. **Sourcing relationship groundwork** — Which 3-5 markets and which specific institutions/associations to build relationships with first? This is pre-work that has to happen before any pilot can launch.
5. **Data security and compliance** — Anthropic's requirements for where review work happens. This could be a dealbreaker if they require on-premises or US-only data handling.
6. **Legal structure** — Entity jurisdiction, contractor classification per country, IP assignment, NDA framework.
7. **Competitive differentiation** — Scale AI, Surge AI, Appen, Remotasks all have Africa operations. Their model is volume labor for general annotation. The differentiation here is *domain-specific practitioner cohorts* — people who actually do credit memos and DCFs for a living, not general-purpose annotators who follow rubrics. That's a fundamentally different talent pool and a fundamentally different value proposition. But it needs to be articulated sharply.
8. **The "100 practitioners" methodology as IP** — The bottom-up approach (aggregate practitioner experience → abstract model → iterate with AI → return solution) could itself be a publishable, proprietary methodology. Worth developing as a named framework that becomes part of the pitch.

---

*This is an ideation document, v2. The core thesis has shifted from "cheaper SMEs" to "faster, broader, statistically deeper evaluation cohorts deployed through purpose-built sourcing infrastructure." The Africa talent pools are the enabler. The operational capability to source and deploy domain-specific practitioner cohorts at 10x current scale, on a sprint cadence, is the product.*
