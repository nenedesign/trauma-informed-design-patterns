# Reversibility and Safe Errors

## Problem

Irreversible or poorly explained actions in forensic tools create legal risk and increase investigator anxiety. A user who deletes an annotation, removes a tag, or exports a case file without understanding the consequences has no recovery path. Fear of making an irreversible mistake slows review and increases cognitive load.

## Design Guidance

Destructive actions require explicit, clearly explained confirmation. The confirmation dialog should state what will be destroyed and whether it can be recovered. If it cannot be recovered, say so plainly.

Where possible, make actions reversible. Deleted annotations should go to a trash state before permanent deletion. Tags should be removable and re-addable. Case exports should be re-generatable.

Error messages explain what went wrong and what to do next. They do not imply user fault. Frame errors as system states, not user failures.

## Do

- "Delete this annotation? This cannot be undone." with Cancel and Delete buttons
- "Tag removed. Undo?" with a five-second undo option inline
- "Export failed. Your network connection was interrupted. Try again or contact your administrator."
- Confirmation dialogs that name the specific item being deleted, not generic "Are you sure?" prompts

## Don't

- Silent deletes with no confirmation
- Generic error messages: "Error 500," "Something went wrong," "Operation failed"
- Confirmation dialogs with no explanation of what will happen
- Permanent deletion as the only option (no soft delete or trash state)
- Error messages that imply user fault: "You entered an invalid value," "You failed to complete this step"

## Risk Level

**High** - Failure creates unrecoverable data loss and erodes investigator confidence in the tool.

## Principles

- Trustworthiness and Transparency
- Empowerment, Voice, and Choice

## Sources

SAMHSA TIP 57: Trauma-Informed Care in Behavioral Health Services.
https://library.samhsa.gov/product/tip-57-trauma-informed-care-behavioral-health-services/sma14-4816

A Guide to Trauma-Informed Content Design. UX Content Collective.
https://uxcontent.com/a-guide-to-trauma-informed-content-design/

National Center for Biotechnology Information, PMC.
https://pmc.ncbi.nlm.nih.gov/articles/PMC12999910/

Designing User-Friendly Interfaces for Legal Software. Lazarev Agency.
https://www.lazarev.agency/articles/legaltech-design
