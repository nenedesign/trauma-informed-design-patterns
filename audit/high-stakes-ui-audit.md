# High-Stakes UI Audit

A scorable checklist for evaluating high-stakes, investigative, and sensitive review interfaces against trauma-informed and safety-by-design principles.

Grounded in SAMHSA's six trauma-informed care principles (TIP 57) and applied to high-stakes UX.

---

## How to Score

Score each item 0 to 3:

- **0 - Missing**: The pattern is not present in the product
- **1 - Partial**: The pattern is present in some areas but applied inconsistently
- **2 - Good**: The pattern is consistently applied throughout the product
- **3 - Excellent**: The pattern is consistently applied and exceeds the baseline guidance

Tag each item with evidence: a screenshot, a link, or a note describing where the pattern was or was not found.

---

## Risk Levels

- **High**: Failure directly causes re-traumatization, harm, or loss of legal integrity
- **Medium**: Failure increases cognitive load or reduces user control
- **Low**: Failure reduces quality but is recoverable without harm

---

## 1. Safety and Emotional Load

Focus: Reduce re-traumatization and cognitive overload during evidence review.

| Pattern | Risk | Score (0-3) | Evidence |
|---|---|---|---|
| Content warnings appear before graphic, violent, sexual, or sensitive material | High | | |
| Sensitive assets are gated behind an explicit "show" action; no auto-preview or auto-play | High | | |
| Users can skip or defer high-risk content items | High | | |
| Summary or redacted views are the default; full detail is opt-in | High | | |
| Evidence sets are chunked with section headers and estimated review times | Medium | | |
| Color palette is calm and non-aggressive; red is reserved for critical errors only | Medium | | |
| No auto-play media; no flashing or jarring animation in standard states | Medium | | |
| Reduced-motion option is available and respects system-level settings | Low | | |
| Dark mode is available without requiring onboarding to be completed first | Low | | |
| A persistent "save and exit" action is accessible from all review screens | High | | |
| Session timeout includes a warning with an option to extend | Medium | | |
| Resumption restores the user to their exact previous position and state | Medium | | |

**Category score: ___ / 36**

---

## 2. Trust, Transparency, and Provenance

Focus: Build confidence that the system is reliable, auditable, and respectful of due process.

| Pattern | Risk | Score (0-3) | Evidence |
|---|---|---|---|
| Each artifact displays acquisition source, hash, and acquisition method at the point of review | High | | |
| Handling history is visible for each artifact without requiring a separate report export | High | | |
| All user actions (views, edits, tags, exports) are time-stamped in an immutable audit log | High | | |
| The audit log is accessible from the case view without requiring admin access | High | | |
| AI-generated outputs are visually distinct from human-reviewed content | High | | |
| AI outputs cite the source evidence they are based on | High | | |
| Confidence indicators are expressed in plain language, not only as a numerical score | Medium | | |
| An explanation of how an AI model reached its conclusion is accessible at the point of use | Medium | | |
| Data access, retention, and export policies are visible within the product | Medium | | |
| Role-based access levels are visible at the point of use, not only in account settings | High | | |

**Category score: ___ / 30**

---

## 3. Control, Agency, and Pacing

Focus: Give investigators and reviewers meaningful control over workflows and exposure.

| Pattern | Risk | Score (0-3) | Evidence |
|---|---|---|---|
| Workflows include visible progress indicators | Medium | | |
| Users can navigate backward in a workflow without losing prior decisions | Medium | | |
| Configurable review modes are available (triage, analysis, reporting) | Medium | | |
| High-level summaries are shown by default; technical metadata is on demand | Medium | | |
| Expand and collapse controls are available for sensitive or detailed sections | Low | | |
| Destructive actions require explicit, named confirmation with consequences stated | High | | |
| Where possible, destructive actions have a soft-delete or undo state | High | | |
| Error messages explain the issue and the next step without implying user fault | Medium | | |
| Users can mark items as reviewed, flagged, or deferred | High | | |
| Annotation tools (notes, highlights, timelines) are available during evidence review | High | | |
| Annotations are attributed and time-stamped | High | | |
| Tag types have defined semantics documented within the product | Medium | | |

**Category score: ___ / 36**

---

## 4. Information Architecture and Navigation

Focus: Make complex case data navigable without overwhelming users.

| Pattern | Risk | Score (0-3) | Evidence |
|---|---|---|---|
| Screen structure (navigation, content, actions) is standardized across modules | Low | | |
| Case and artifact hierarchy is logical: cases, investigations, evidence sets, artifacts | Medium | | |
| Naming and metadata conventions are consistent across views | Low | | |
| Filtering supports: type, date, source, sensitivity level, and tags | Medium | | |
| Search supports suggestions and saved queries | Low | | |
| Visual relationship views (timeline, graph, map) are available for relevant artifact types | Medium | | |
| Visual views link to underlying raw data | Medium | | |

**Category score: ___ / 21**

---

## 5. High-Stakes Workflows

Focus: Support core investigative tasks while minimizing unnecessary friction and distress.

| Pattern | Risk | Score (0-3) | Evidence |
|---|---|---|---|
| Acquisition, parsing, and indexing status is visible during processing | Medium | | |
| Estimated time to completion is shown for background jobs | Low | | |
| Evidence review mode minimizes UI chrome and supports keyboard navigation | Medium | | |
| Shared case notes, tasks, and assignments are visible with owner and due date | Medium | | |
| Role-aware views are available: examiner, investigator, legal, manager | High | | |
| Reports include plain-language summaries alongside technical appendices | Medium | | |
| Export produces audit trails and outputs suitable for legal and law enforcement formats | High | | |

**Category score: ___ / 21**

---

## 6. Language, Microcopy, and Inclusivity

Focus: Avoid blame, shame, and stigmatizing language; support diverse users.

| Pattern | Risk | Score (0-3) | Evidence |
|---|---|---|---|
| Error messages avoid implying user fault | Medium | | |
| Content category labels are descriptive and factual, not sensational or clinical | Medium | | |
| "You can" is used over "you must" where policy allows | Low | | |
| Chosen names, pronouns, and identity fields are supported and used consistently | Medium | | |
| Summaries and outputs are written for non-technical audiences | Medium | | |
| Technical terms include tooltips or glossary links | Low | | |

**Category score: ___ / 18**

---

## 7. Privacy, Security, and Ethical Safeguards

Focus: Align with legal, regulatory, and ethical expectations for sensitive data.

| Pattern | Risk | Score (0-3) | Evidence |
|---|---|---|---|
| Role-based permissions are visible and understandable at the point of use | High | | |
| Permission failures surface a clear explanation and a contact path | High | | |
| Access logs are easily retrievable and auditable by case stakeholders | High | | |
| Data retention and deletion options are available, clearly labeled, and role-appropriate | High | | |
| Human-in-the-loop checkpoints exist before high-impact AI recommendations take effect | High | | |
| AI model documentation (bias, fairness, accuracy) is accessible within the product | Medium | | |

**Category score: ___ / 18**

---

## 8. High-Exposure Review Environment

Focus: Reduce cumulative harm from sustained, high-volume review of distressing content.

| Pattern | Risk | Score (0-3) | Evidence |
|---|---|---|---|
| A session review counter tracks items reviewed in the current session | High | | |
| Optional session limits are available (user-controlled, not enforced automatically) | High | | |
| Disturbing content types are separated into distinct queues where possible | High | | |
| "Request support" is accessible within the review interface without leaving the tool | High | | |
| Wellbeing resources are embedded in the product, not redirected to an external portal | Medium | | |
| UI copy normalizes emotional responses to distressing content without dramatizing them | Medium | | |

**Category score: ___ / 18**

---

## Summary Scorecard

| Category | Max Score | Score | Notes |
|---|---|---|---|
| 1. Safety and Emotional Load | 36 | | |
| 2. Trust, Transparency, and Provenance | 30 | | |
| 3. Control, Agency, and Pacing | 36 | | |
| 4. Information Architecture and Navigation | 21 | | |
| 5. High-Stakes Workflows | 21 | | |
| 6. Language, Microcopy, and Inclusivity | 18 | | |
| 7. Privacy, Security, and Ethical Safeguards | 18 | | |
| 8. High-Exposure Review Environment | 18 | | |
| **Total** | **198** | | |

---

## Score Interpretation

- **160-198**: Strong trauma-informed design foundation; address remaining gaps in High-risk items
- **120-159**: Good coverage with meaningful gaps; prioritize categories with the most High-risk items missing
- **80-119**: Significant gaps; focus on categories 1, 2, 3, and 7 before other improvements
- **Below 80**: Foundational redesign needed; begin with content gating, provenance, and access controls

---

## Sources

See [references.md](../references.md) for the full citation list.

SAMHSA TIP 57: Trauma-Informed Care in Behavioral Health Services.
https://library.samhsa.gov/product/tip-57-trauma-informed-care-behavioral-health-services/sma14-4816
