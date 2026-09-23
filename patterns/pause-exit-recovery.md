# Pause, Exit, and Recovery

## Problem

Users reviewing distressing content need the ability to stop without losing work. When there is no clear pause option, or when exiting a workflow means losing progress, users are forced to continue past their capacity. This removes agency and increases distress. A user who fears losing work will not stop when they should.

## Design Guidance

Provide a persistent pause action that saves state without requiring the user to navigate to a settings menu or complete a confirmation flow. The action should be labeled clearly ("Save and exit") and should be accessible from any screen in the review workflow.

Provide a quick-exit option that closes the current view without a multi-step confirmation. The quick exit does not need to save state in the same way as a planned pause; it is for situations where a user needs to stop immediately.

Warn users before session timeout. Give a minimum of two minutes notice, with an option to extend. Do not auto-logout without warning.

Resumption should restore the user to their exact state: the same artifact, the same position in the review queue, with the same filters and annotations intact.

## Do

- Persistent "Save and exit" action visible in the navigation bar on all review screens
- "Your session will expire in 5 minutes. Extend session or save and exit."
- Resume flow: "Welcome back. You left off on item 23 of 47. Continue where you left off?"
- Quick-exit option that does not require confirmation (state is auto-saved)

## Don't

- Full-page takeover modals that block the exit path
- Auto-logout without warning or save
- Resume flows that restart from the beginning of the evidence set
- Requiring users to complete a step before they can exit

## Risk Level

**High** - Failure removes user agency over their exposure to distressing content and can force continuation past capacity.

## Principles

- Safety
- Empowerment, Voice, and Choice

## Sources

SAMHSA TIP 57: Trauma-Informed Care in Behavioral Health Services.
https://library.samhsa.gov/product/tip-57-trauma-informed-care-behavioral-health-services/sma14-4816

National Center for Biotechnology Information, PMC.
https://pmc.ncbi.nlm.nih.gov/articles/PMC12999910/

Inclusive by Design: Use a Trauma-Informed Approach. UXPA Magazine.
https://uxpamagazine.org/inclusive-by-design-use-a-trauma-informed-approach/

Designing for the Wounded: How Trauma-Informed Product Design Creates Digital Sanctuaries. Medium, Kristin Cooke.
https://medium.com/@kristincooke/designing-for-the-wounded-how-trauma-informed-product-design-creates-digital-sanctuaries-edfe3e72885a
