# High-Exposure Content Review

## Problem

Investigators, content moderators, and compliance reviewers face repeated exposure to disturbing, graphic, or distressing content as a core part of their role. Secondary traumatic stress, burnout, and decision fatigue are documented occupational risks for this work. The cumulative effect of exposure is not addressed by any single interaction pattern. It is addressed by the design of the review environment as a whole.

This pattern is distinct from Content Gating and Gradual Exposure, which address individual instances of sensitive content. High-Exposure Content Review addresses the design of sustained, high-volume review sessions.

## Design Guidance

Design the review environment to reduce cumulative exposure without reducing review quality. This includes:

**Session controls:** Provide a visible review counter that tracks items reviewed in the current session. Offer optional session limits with a prompt to take a break. Do not enforce limits automatically; surface them as information the user can act on.

**Triage separation:** Separate initial classification from deep review. A triage queue handles first-pass decisions at lower detail. Deep review queues are for items that require full examination. Users should not spend the same cognitive resources on every item.

**Queue separation:** Separate content types where possible. A queue that contains CSAM, financial fraud documents, and routine device backups forces users to context-switch between materials of very different emotional weight. Where separation is not possible, use visual indicators that allow users to anticipate what they are about to review.

**Wellbeing integration:** Embed a "Request support" action in the review interface. Link to wellbeing resources from within the tool. Normalize the response to distressing content in UI copy. These are not replacement resources; they are access points to existing support systems.

## Do

- Session counter: "47 items reviewed this session. Consider taking a break."
- Separate queues: "CSAM Review," "Violence Review," "General Evidence" with distinct visual treatment
- "Request support" in the sidebar, accessible without leaving the review interface
- "It is common to feel unsettled when reviewing this material. Wellbeing resources are available."
- Optional: "Set a session limit. You will be prompted after [X] items."

## Don't

- No session counter or pacing mechanism; unlimited continuous review with no interruption
- All content types in a single undifferentiated review queue
- Wellbeing resources only accessible from a separate HR or company portal
- Mandated session limits that remove user control (inform, do not enforce)
- No acknowledgment in the UI that the work involves distressing content

## Risk Level

**High** - Failure contributes to secondary traumatic stress, burnout, and decision quality degradation over sustained review sessions.

## Principles

- Safety
- Peer Support
- Collaboration and Mutuality
- Empowerment, Voice, and Choice

## Sources

SAMHSA TIP 57: Trauma-Informed Care in Behavioral Health Services.
https://library.samhsa.gov/product/tip-57-trauma-informed-care-behavioral-health-services/sma14-4816

National Center for Biotechnology Information, PMC.
https://pmc.ncbi.nlm.nih.gov/articles/PMC11706808/

National Center for Biotechnology Information, PMC.
https://pmc.ncbi.nlm.nih.gov/articles/PMC12967362/

Designing for Emotional Safety in Digital Health. Frontiers in Digital Health.
https://www.frontiersin.org/journals/digital-health/articles/10.3389/fdgth.2026.1797681/full

Inclusive by Design: Use a Trauma-Informed Approach. UXPA Magazine.
https://uxpamagazine.org/inclusive-by-design-use-a-trauma-informed-approach/
