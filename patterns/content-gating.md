# Content Gating

## Problem

Auto-loading graphic or sensitive content exposes users to material they have not consented to view. In forensic and investigative contexts, this causes re-traumatization and erodes trust in the tool. Users who cannot predict when distressing content will appear lose confidence in their ability to manage their own exposure.

## Design Guidance

Gate potentially distressing content behind an explicit user action. Never auto-preview. Provide a clear content warning before the "show" action that describes what the user will see without reproducing the content itself. Allow users to skip or defer high-risk items.

Content types that require gating include: graphic imagery, violent or sexual content, content involving minors, and any material the user has flagged as distressing in a previous session.

The gate should be a deliberate action, not a dismissible banner. A toggle or button labeled with the content type and a description of what it contains gives users the information they need to make a decision.

## Do

- "This item contains graphic imagery of a violent crime scene. Select 'View' to open it."
- "This artifact has been flagged as high-sensitivity. Review before opening."
- Allow users to defer: "Skip for now" with a way to return to deferred items

## Don't

- Auto-load thumbnail previews of evidence assets
- Auto-play video evidence on hover or page load
- Use a dismissible banner as the only gate before graphic content
- Show the content in a preview pane without an explicit open action

## Risk Level

**High** - Failure causes unexpected exposure to distressing content and can re-traumatize users.

## Principles

- Safety
- Empowerment, Voice, and Choice

## Sources

SAMHSA TIP 57: Trauma-Informed Care in Behavioral Health Services.
https://library.samhsa.gov/product/tip-57-trauma-informed-care-behavioral-health-services/sma14-4816

A Guide to Trauma-Informed Content Design. UX Content Collective.
https://uxcontent.com/a-guide-to-trauma-informed-content-design/

National Center for Biotechnology Information, PMC.
https://pmc.ncbi.nlm.nih.gov/articles/PMC12999910/

Designing for the Wounded: How Trauma-Informed Product Design Creates Digital Sanctuaries. Medium, Kristin Cooke.
https://medium.com/@kristincooke/designing-for-the-wounded-how-trauma-informed-product-design-creates-digital-sanctuaries-edfe3e72885a
