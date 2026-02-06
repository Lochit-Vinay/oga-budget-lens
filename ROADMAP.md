### OGA-budget-lens Roadmap

This roadmap describes the evolution of the Budget Lens project as a long-term civic data infrastructure, not a one-off research or student exercise.

Timeframes are indicative. Progress is expected to be incremental and review-driven.

---

### Phase 0: Foundations (Project Initialization)

Focus:
- Establish shared understanding and guardrails

Key outcomes:
- Canonical budget line item schema
- Clear documentation of design assumptions
- Initial repository structure and contribution norms

This phase is expected to overlap with early GSoC work but remains relevant beyond it.m

### Phase 1: Core Parsing Infrastructure

Focus:
- End-to-end processing of a single real-world budget PDF

Key outcomes:
- PDF ingestion and type detection
- OCR integration with raw text retention
- Layout detection with stored metadata
- Provenance-aware intermediate outputs

Success criteria:
- One document processed end-to-end with traceability

### Phase 2: Table Extraction & Hierarchy Modeling

Focus:
- Turning detected tables into structured budget data

Key outcomes:
- Table extraction with bounding box references
- Explicit parent–child hierarchy reconstruction
- Flagging of ambiguous or uncertain structures

Success criteria:
- Hierarchical budget representation without inferred assumptions

### Phase 3: Controlled AI Assistance

Focus:
- Improving data usability without sacrificing trust

Key outcomes:
- LLM-assisted text cleaning with strict safety rules
- Functional classification (e.g. COFOG)
- Full model and prompt provenance

Non-goal:
- Automated “smart guessing” of missing fiscal values

### Phase 4: Human Review & Auditability

Focus:
- Making verification practical and transparent

Key outcomes:
- Review interface for extracted data
- Edit tracking and attribution
- Clear distinction between AI-extracted and human-verified values

### Phase 5: Validation, QA & Metrics

Focus:
- Measuring reliability and surfacing errors

Key outcomes:
- Arithmetic and structural validation
- Semantic anomaly detection
- Defined quality metrics and reporting

### Phase 6: Interoperability & Reuse

Focus:
- Making outputs usable by others

Key outcomes:
- Standardized exports (JSON, CSV, Excel)
- Compatibility with open fiscal data platforms
- Clear data licensing and reuse documentation

### Phase 7: Multi-Country Demonstration

Focus:
- Proving cross-context applicability

Key outcomes:
- Demo datasets from multiple African countries
- Documented country-specific challenges
- Refined failure-mode documentation
