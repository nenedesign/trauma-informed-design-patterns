# Evidence Provenance

## Problem

In forensic contexts, the integrity and chain of custody of evidence is a legal requirement. When acquisition source, handling history, and artifact metadata are not visible in the UI, investigators cannot verify what they are looking at, and reports may be challenged in court. Provenance buried in a separate export is not sufficient; it must be present at the point of review.

## Design Guidance

Display acquisition source, file hash, acquisition method, and handling history persistently for each artifact during review. This information should be visible at the artifact level without requiring a separate lookup or report generation.

Time-stamp all user actions against an artifact: views, edits, annotations, tags, and exports. Store these in an immutable audit log that is accessible from the UI without requiring admin access.

Make provenance information readable by non-technical reviewers. A legal team member or court should be able to understand the acquisition and handling history without requiring an examiner to explain it.

## Do

- Artifact header: "Acquired: 2026-01-14 09:22 UTC | Source: Axiom Image v7.2 | SHA-256: a4f3c1..."
- "Handling history: Acquired by J. Smith, reviewed by M. Okoro, exported to case file 2026-02-01"
- Audit log accessible from a persistent link in the case navigation, not only from admin settings
- Plain-language provenance summary alongside the technical metadata

## Don't

- Provenance only accessible by generating a separate report export
- No timestamp on reviewer actions (viewing, tagging, annotating)
- Hash values displayed without explanation of what they verify
- Chain of custody that resets or becomes incomplete after case handoff

## Risk Level

**High** - Failure creates chain-of-custody gaps that can render evidence inadmissible and undermine investigations.

## Principles

- Trustworthiness and Transparency
- Collaboration and Mutuality

## Sources

SAMHSA TIP 57: Trauma-Informed Care in Behavioral Health Services.
https://library.samhsa.gov/product/tip-57-trauma-informed-care-behavioral-health-services/sma14-4816

The Complete Guide to Digital Forensics Software for Law Enforcement. VeriPic.
https://www.veripic.com/the-complete-guide-to-digital-forensics-software-for-law-enforcement/

Digital Forensic Case Management Software Development. Zealous Systems.
https://zealousys.com/blog/digital-forensic-case-management-software-development/

Designing User-Friendly Interfaces for Legal Software. Lazarev Agency.
https://www.lazarev.agency/articles/legaltech-design
