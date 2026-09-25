# Trauma-Informed Design Patterns

Design patterns for digital products that handle sensitive content, evidence, or high-stakes investigations. Grounded in SAMHSA's six trauma-informed care principles and applied to interaction design.

These patterns are for designers, researchers, and product teams building tools in high-stakes investigation, content moderation, abuse reporting, healthcare, and crisis services.

---

## Foundation

This repository applies the six principles from SAMHSA's Trauma-Informed Care framework (TIP 57) to digital product design:

1. **Safety** - Users feel physically and psychologically safe using the product
2. **Trustworthiness and Transparency** - Actions and system behavior are clear and predictable
3. **Peer Support** - Users are not isolated; support resources are accessible when needed
4. **Collaboration and Mutuality** - The product works with users, not at them
5. **Empowerment, Voice, and Choice** - Users have meaningful control over their experience
6. **Cultural, Historical, and Gender Issues** - The product respects diverse identities and contexts

See [/principles](./principles/) for how each maps to digital design.

---

## Patterns

| Pattern | Category | Risk |
|---|---|---|
| [Content Gating](./patterns/content-gating.md) | Safety and Emotional Load | High |
| [Gradual Exposure](./patterns/gradual-exposure.md) | Safety and Emotional Load | High |
| [Calm Visual Tone](./patterns/calm-visual-tone.md) | Safety and Emotional Load | Medium |
| [Pause, Exit, and Recovery](./patterns/pause-exit-recovery.md) | Safety and Emotional Load | High |
| [Evidence Provenance](./patterns/evidence-provenance.md) | Trust, Transparency, and Provenance | High |
| [Explainable AI Output](./patterns/explainable-ai-output.md) | Trust, Transparency, and Provenance | High |
| [Self-Paced Workflows](./patterns/self-paced-workflows.md) | Control, Agency, and Pacing | Medium |
| [Progressive Disclosure](./patterns/progressive-disclosure.md) | Control, Agency, and Pacing | Medium |
| [Annotation and Distance](./patterns/annotation-and-distance.md) | Control, Agency, and Pacing | High |
| [Reversibility and Safe Errors](./patterns/reversibility-safe-errors.md) | Control, Agency, and Pacing | High |
| [Neutral Microcopy](./patterns/neutral-microcopy.md) | Language, Microcopy, and Inclusivity | Medium |
| [Least-Privilege Access](./patterns/least-privilege-access.md) | Privacy, Security, and Ethical Safeguards | High |
| [High-Exposure Content Review](./patterns/high-exposure-content-review.md) | Investigator Wellness | High |

---

## Repository Structure

```
/principles    SAMHSA principles applied to digital product design
/patterns      Individual design patterns with guidance and research grounding
/audit         Scorable checklist for high-stakes and investigative UI review
references.md  Full citation list
```

---

## How to Use

**Principles** establish the framework. Read these first to understand the why behind the patterns.

**Patterns** are the implementation layer. Each pattern addresses a specific problem, provides design guidance, and is tagged by risk level.

**Audit** is a structured checklist for evaluating an existing product against these patterns. Use it in design reviews, heuristic evaluations, or research planning.

---

## Risk Levels

Each pattern is tagged:

- **High** - Failure directly causes re-traumatization, harm, or loss of legal integrity
- **Medium** - Failure increases cognitive load or reduces user control
- **Low** - Failure reduces quality but is recoverable without harm

---

## Pattern Template

Each pattern follows this structure:

- **Problem** - What goes wrong without this pattern
- **Design guidance** - What to do
- **Do / Don't** - Concrete implementation examples
- **Risk level** - High / Medium / Low
- **Principles** - Which SAMHSA principles this pattern serves
- **Sources** - Research citations

---

## Sources

See [references.md](./references.md) for the full citation list.

---

## Related

- [ai-accountability-design-patterns](https://github.com/nenedesign/ai-accountability-design-patterns): 12 accountability concepts for AI-assisted products: traceability, chain of custody, explainability, integrity, and more. The Evidence Provenance and Explainable AI Output patterns here map directly to Provenance, Explainability, and Chain of Custody there.
- [conversational-ai-patterns](https://github.com/nenedesign/conversational-ai-patterns): interaction design patterns for conversational AI, including HITL handoff design, auditable AI output, and scale triage for regulated evidence review.
