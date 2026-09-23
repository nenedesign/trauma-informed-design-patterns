# Self-Paced Workflows

## Problem

Linear, timed, or progress-forced workflows deny investigators control over the sequence and pace of evidence review. This is both a cognitive load issue and a due process concern. An investigator who must complete step 3 before returning to step 2, or who is auto-advanced on a timer, is not in control of their own work. The workflow is making investigative decisions the human should be making.

## Design Guidance

Step-by-step workflows should include visible progress indicators and allow backward navigation without losing work. Users can move forward and back freely. No step should auto-advance.

Offer configurable review modes that change the density and sequence of information: triage mode for initial classification, deep analysis mode for detailed examination, and reporting mode for output preparation. The mode selector should be accessible from the workspace, not buried in settings.

Progress should be persistent. A user who leaves a workflow and returns should resume at their last position, with their prior decisions intact.

## Do

- Step indicator: "Step 3 of 7. You can return to any previous step at any time."
- Mode selector in the workspace header: "Triage | Analysis | Reporting"
- "Your progress has been saved. Resume from step 3?"
- Allow users to jump to any step from the step indicator

## Don't

- "You must complete this step before proceeding."
- Auto-advance after a timed action (e.g., auto-mark as reviewed after 30 seconds)
- Workflows that lose user decisions when navigating backward
- No indication of how many steps remain or where the user is in the process

## Risk Level

**Medium** - Failure removes user control over pace and sequence, increasing cognitive load and decision fatigue.

## Principles

- Empowerment, Voice, and Choice
- Collaboration and Mutuality

## Sources

SAMHSA TIP 57: Trauma-Informed Care in Behavioral Health Services.
https://library.samhsa.gov/product/tip-57-trauma-informed-care-behavioral-health-services/sma14-4816

National Center for Biotechnology Information, PMC.
https://pmc.ncbi.nlm.nih.gov/articles/PMC12999910/

Digital Forensic Tools: Why Ease of Use Is Essential. Magnet Forensics.
https://www.magnetforensics.com/blog/digital-forensic-tools-why-ease-of-use-is-essential/

Inclusive by Design: Use a Trauma-Informed Approach. UXPA Magazine.
https://uxpamagazine.org/inclusive-by-design-use-a-trauma-informed-approach/
