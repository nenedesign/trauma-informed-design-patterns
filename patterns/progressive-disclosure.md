# Progressive Disclosure

## Problem

Displaying all technical detail for every artifact at once overwhelms investigators and surfaces information before it is relevant. A full hex dump alongside a human-readable file preview, or a complete metadata record displayed by default, forces users to filter signal from noise before they can begin their actual task. In high-volume environments, this compounds fatigue.

## Design Guidance

Start with high-level summaries. Surface technical detail on demand. Use expand/collapse controls for sensitive or detailed sections. The depth of information shown should match the stage of the workflow and the role of the user.

Progressive disclosure is not the same as hiding information. Everything is accessible; the default display is calibrated to the most common task at each stage.

Triage views should show only what is needed to make an initial classification decision. Analysis views reveal full technical metadata and processing details. Reporting views surface output fields, not source metadata.

## Do

- Default artifact view: filename, type, acquisition date, summary flag. "Show technical metadata" expands the full record.
- "View full transcript" below a text summary of a communications artifact
- Role-based default depth: examiner sees more by default than a legal reviewer
- Expand/collapse on all metadata sections; state persists across sessions

## Don't

- Full hex dump displayed alongside the human-readable evidence preview by default
- All metadata fields expanded for every artifact in a list view
- Requiring users to hide or close fields they did not ask for
- Different disclosure levels in different parts of the product with no consistent logic

## Risk Level

**Medium** - Failure increases cognitive load and decision fatigue; does not directly cause harm but degrades review quality over time.

## Principles

- Empowerment, Voice, and Choice
- Safety

## Sources

SAMHSA TIP 57: Trauma-Informed Care in Behavioral Health Services.
https://library.samhsa.gov/product/tip-57-trauma-informed-care-behavioral-health-services/sma14-4816

Digital Forensic Tools: Why Ease of Use Is Essential. Magnet Forensics.
https://www.magnetforensics.com/blog/digital-forensic-tools-why-ease-of-use-is-essential/

Designing User-Friendly Interfaces for Legal Software. Lazarev Agency.
https://www.lazarev.agency/articles/legaltech-design

National Center for Biotechnology Information, PMC.
https://pmc.ncbi.nlm.nih.gov/articles/PMC12999910/
