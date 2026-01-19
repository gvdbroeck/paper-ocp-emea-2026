# OCP EMEA Summit 2026 - DC Short-Circuit Protection Methodology Paper

## Conference Requirements Summary

**Event:** OCP EMEA Summit Future Technologies Symposium  
**Date:** April 29, 2026 | Barcelona, Spain  
**Submission Deadline:** February 9, 2026 (11:59 PM PT)

**Format Requirements:**
- **2-page IEEE two-column conference format**
- Must report on innovative engineering/scientific results
- Technology projected 2-5 years out
- **Must not be commercial** or contain confidential information
- Categories: AI/HPC, Data Center Sustainability, Future Tech

**Judging Criteria ($10,000 prize):**
1. **Innovation** - Uniqueness vs. current state-of-the-art
2. **Impact to OCP Community** - Market coverage potential
3. **Timeline to Impact** - Years to market prevalence

---

## Proposed Paper Title

**"A Systematic Methodology for DC Short-Circuit Protection Evaluation in High-Power Data Center Microgrids"**

---

## Academic Paper Outline (IEEE 2-Page Format)

### I. ABSTRACT (150-200 words)
- Challenge: DC power distribution in data centers faces critical protection gaps
- Problem: Lack of standardized methodologies for evaluating DC short-circuit protection requirements
- Contribution: Novel simulation-based methodology combining transient analysis with protection device coordination
- Results: Validation using laboratory testing with solid-state circuit breakers
- Impact: Enables systematic protection design for emerging DC data center architectures

### II. INTRODUCTION (0.4 pages)
**A. Motivation**
- Growth of DC power distribution in hyperscale data centers (380V, 400V, 800V systems)
- AI/HPC workloads driving higher power densities
- Absence of mature DC protection standards (vs. AC systems with IEC 60909, IEEE 1584)

**B. Technical Challenges**
- Rapid fault current rise in DC systems (exponential vs. sinusoidal)
- Limited breaking capacity of conventional DC breakers
- Coordination complexity with multiple sources (batteries, converters, utility)
- Lack of natural current zero crossing

**C. Research Gap**
- Existing methods: simplified analytical approaches inadequate for complex topologies
- Need: Comprehensive methodology considering transient behavior, source contributions, protection device characteristics

**D. Paper Contribution**
- Systematic simulation-based methodology for DC fault analysis
- Integration of protection device models and coordination schemes
- Experimental validation framework using SCCB prototypes

### III. METHODOLOGY (0.8 pages)

**A. System Modeling Framework**
1. **Component-Level Models**
   - Battery systems: dynamic impedance and discharge characteristics
   - Power converters: control response during faults
   - Cable networks: distributed parameter models
   - Protection devices: trip characteristics and breaking capacity

2. **Fault Scenario Generation**
   - Bolted faults at critical nodes
   - High-impedance faults
   - Arc fault considerations
   - Worst-case loading conditions

**B. Transient Simulation Approach**
1. **Multi-Physics Modeling**
   - Electrical transients (microsecond to millisecond scale)
   - Thermal effects on conductor and device ratings
   - Control system interactions

2. **Source Contribution Analysis**
   - Individual source fault current contributions
   - Time-domain superposition for multiple sources
   - Peak current and energy calculations (I²t)

**C. Protection Coordination Strategy**
1. **Selectivity Analysis**
   - Time-current coordination curves
   - Zone-based protection schemes
   - Backup protection requirements

2. **Device Selection Criteria**
   - Breaking capacity vs. prospective fault current
   - Operating time vs. equipment withstand capability
   - Coordination margins between protection zones

**D. Validation Framework**
- Laboratory test setup requirements
- Measurement protocols
- Comparison metrics (peak current, clearing time, energy dissipation)

### IV. CASE STUDY: 800V DC MICROGRID (0.5 pages)

**A. System Architecture**
- Multi-source topology: 2MW battery system, 1MW solar, 500kW utility connection
- Load distribution: 15 zones with mixed critical/non-critical loads
- Protection hierarchy: 3-level coordination scheme

**B. Simulation Results**
1. **Fault Current Analysis**
   - Peak fault currents: 15-45 kA depending on location
   - Source contributions breakdown
   - Critical fault locations identified

2. **Protection Device Evaluation**
   - SCCB response times: 2-5ms
   - Energy let-through comparison
   - Coordination verification

**C. Laboratory Validation**
- Test configuration with SCCB prototypes
- Measured vs. simulated fault currents (±8% agreement)
- Trip time validation (±0.5ms)
- Thermal stress verification

**D. Key Findings**
- Methodology accurately predicts protection requirements
- SCCB technology enables selective coordination
- Design guidelines for 2-5 year deployment timeline

### V. DISCUSSION (0.2 pages)

**A. Implications for Data Center Design**
- Standardized protection evaluation process
- Reduced over-specification and costs
- Enhanced safety and reliability

**B. Technology Readiness**
- SCCB maturity: TRL 7-8 (prototype demonstration)
- Integration challenges: control systems, monitoring
- Path to commercialization: 2-3 years

**C. Standardization Needs**
- Proposed test protocols
- Coordination study requirements
- Documentation standards

### VI. CONCLUSION (0.1 pages)
- Summary of methodology contributions
- Validation results demonstrate feasibility
- Call for industry collaboration on standardization
- Future work: AI-based protection optimization, hybrid AC/DC systems

### REFERENCES (8-10 key citations)
- IEEE standards (1547, 1709)
- Recent SCCB research papers
- DC microgrid protection surveys
- Data center power distribution studies

---

## ABB Meeting Strategy (Friday)

### Meeting Objectives
1. **Secure SCCB prototype access** for laboratory validation
2. **Establish co-authorship** (ABB researcher as co-author adds credibility)
3. **Define test protocols** for validation phase
4. **Discuss joint presentation** at OCP (separate from paper)

### Key Discussion Points

**1. Academic Collaboration Framework**
- Position: "We have unique simulation capabilities for evaluating protection requirements in complex DC systems"
- Ask: "Your SCCB prototypes would provide the validation data needed for academic publication"
- Benefit to ABB: Early validation of products in realistic scenarios, academic credibility, OCP visibility

**2. Laboratory Testing Scope**
- Propose specific test scenarios from case study
- Define measurement requirements
- Timeline: Tests needed by mid-March for paper finalization
- Location: Your lab facility (mention this as differentiator)

**3. Intellectual Property Boundaries**
- Paper focuses on **methodology**, not product promotion
- ABB SCCB referenced as "commercially available solid-state circuit breaker technology"
- No proprietary specifications disclosed
- Results demonstrate technology class, not specific product

**4. Presentation Strategy (Separate from Paper)**
- Paper: Academic, methodology-focused, neutral
- Presentation: Can showcase specific results, mention products
- Demo opportunity: Live simulation + hardware demonstration
- ABB branding acceptable in presentation (not paper)

**5. Co-Authorship Proposal**
- Lead author: Your team (methodology development)
- Co-author: ABB researcher (experimental validation, SCCB expertise)
- Affiliation: "Independent research collaboration"
- Strengthens paper credibility significantly

### Unique Value Propositions

**What You Bring:**
- Advanced simulation platform for DC system analysis
- Laboratory facilities for controlled testing
- Neutral academic positioning (not competitor)
- OCP platform for technology dissemination

**What ABB Brings:**
- State-of-the-art SCCB prototypes
- Protection engineering expertise
- Industry credibility
- Potential for follow-on commercial engagement

### Risk Mitigation
- **Concern:** ABB may want promotional content
  - **Response:** "Academic paper must be neutral, but presentation can highlight specific products"
  
- **Concern:** Proprietary information disclosure
  - **Response:** "We only need performance characteristics, not design details"
  
- **Concern:** Timeline pressure
  - **Response:** "Testing can be completed in 4-6 weeks, paper draft by mid-March"

### Follow-Up Actions
- Draft collaboration agreement (if positive response)
- Schedule laboratory visit for SCCB testing
- Establish communication channel for paper development
- Plan joint presentation outline

---

## Timeline to Submission

- **Now - Jan 17:** Finalize ABB collaboration, secure SCCB access
- **Jan 20 - Feb 7:** Laboratory testing and data collection
- **Feb 10 - Feb 23:** Paper drafting and internal review
- **Feb 24 - Mar 2:** ABB co-author review and revisions
- **Mar 3 - Mar 9:** Final polishing and submission preparation
- **Feb 9 deadline:** Submit to OCP FTS

---

## Key Success Factors

This outline positions your work as **academic research** while leveraging your unique simulation capabilities and laboratory facilities. The ABB collaboration adds validation credibility without compromising the non-commercial requirement. 

**Why This Will Win:**
- **Innovation (High):** Novel methodology addressing critical gap in DC protection
- **OCP Impact (High):** Directly addresses data center power distribution challenges
- **Timeline (Realistic):** 2-3 years to widespread adoption aligns with OCP focus

**Differentiation:**
- Combines simulation with experimental validation
- Addresses real-world complexity (multi-source systems)
- Provides actionable design guidelines
- Neutral academic perspective with industry validation

---

## Notes for Paper Development

### Technical Content to Emphasize
- Transient behavior modeling (unique to DC systems)
- Multi-source fault contribution analysis
- Protection coordination in absence of standards
- Experimental validation methodology

### Content to Avoid
- Product specifications or comparisons
- Commercial claims or market analysis
- Proprietary information
- Promotional language

### Writing Style
- Objective, scientific tone
- Focus on methodology and results
- Clear problem-solution-validation structure
- Emphasize reproducibility and standardization potential
