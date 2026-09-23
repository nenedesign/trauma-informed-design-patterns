# Least-Privilege Access

## Problem

When access controls are invisible or inconsistent in the UI, investigators cannot verify who has access to case data. Reviewers may access material outside their authorized scope without realizing it. Audit trails become unreliable. In a legal context, unauthorized access to evidence can compromise an investigation or invalidate findings.

## Design Guidance

Display the current user's role and access level explicitly within the workspace. Role-based access controls should be visible at the point of use, not only in admin settings or account management screens.

When a user encounters an action they are not permitted to take, explain why and who to contact. Silent permission failures leave users without recourse.

Access logs must be auditable and accessible to the user who generated them, not only to administrators. Data retention, deletion, and redaction controls should be clearly labeled and matched to the user's role.

## Do

- Role indicator in the workspace header: "M. Okoro | Examiner | Case 2024-0041 (Read-only for archived cases)"
- When a user attempts a restricted action: "You do not have permission to export this case. Contact your case manager."
- Access log accessible from the case view: "View access history for this case"
- Retention and deletion options that match the user's role and are labeled in plain language

## Don't

- Silent failures when a user attempts a restricted action (no error message, action simply does not work)
- Role permissions only visible in account settings, not at the point of use
- Access logs only accessible to administrators
- Retention and deletion options visible to roles that cannot use them, with no explanation

## Risk Level

**High** - Failure creates unauthorized access to sensitive evidence and audit trail gaps that can compromise legal proceedings.

## Principles

- Trustworthiness and Transparency
- Safety

## Sources

SAMHSA TIP 57: Trauma-Informed Care in Behavioral Health Services.
https://library.samhsa.gov/product/tip-57-trauma-informed-care-behavioral-health-services/sma14-4816

National Center for Biotechnology Information, PMC.
https://pmc.ncbi.nlm.nih.gov/articles/PMC12999910/

The Complete Guide to Digital Forensics Software for Law Enforcement. VeriPic.
https://www.veripic.com/the-complete-guide-to-digital-forensics-software-for-law-enforcement/

Designing User-Friendly Interfaces for Legal Software. Lazarev Agency.
https://www.lazarev.agency/articles/legaltech-design
