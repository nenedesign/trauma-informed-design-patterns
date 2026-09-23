# Gradual Exposure

## Problem

Presenting full, unfiltered evidence sets by default forces users to process all material at once. In high-volume review environments, this increases cognitive load, accelerates fatigue, and raises the risk of re-traumatization. Users have no way to calibrate how much they engage with before they are ready.

## Design Guidance

Show summary or redacted views by default. Users opt into full detail. Break long evidence sets into manageable chunks with section headers and estimated review times. Provide text summaries or low-resolution previews first; full images, video, and transcripts are available on request.

Chunking should be meaningful. Divide evidence by artifact type, date range, or case relevance rather than arbitrary page size. Give users an estimate of what is in each chunk before they open it.

## Do

- "Showing text summary. Select 'View full transcript' to open the complete record."
- "This set contains 47 items. Estimated review time: 12 minutes. Items are grouped by date."
- "Page 1 of 6. Each section contains approximately 8 artifacts."
- Low-resolution image placeholder with dimensions and a "View full resolution" button

## Don't

- Load all evidence assets into a single infinite scrolling feed
- Show full image resolution or auto-play video by default
- Present evidence counts without any structure or grouping
- Remove the summary view once a user has opened full detail (allow toggling back)

## Risk Level

**High** - Failure forces uncontrolled exposure to high volumes of distressing content.

## Principles

- Safety
- Empowerment, Voice, and Choice
- Collaboration and Mutuality

## Sources

SAMHSA TIP 57: Trauma-Informed Care in Behavioral Health Services.
https://library.samhsa.gov/product/tip-57-trauma-informed-care-behavioral-health-services/sma14-4816

National Center for Biotechnology Information, PMC.
https://pmc.ncbi.nlm.nih.gov/articles/PMC12999910/

Designing for the Wounded: How Trauma-Informed Product Design Creates Digital Sanctuaries. Medium, Kristin Cooke.
https://medium.com/@kristincooke/designing-for-the-wounded-how-trauma-informed-product-design-creates-digital-sanctuaries-edfe3e72885a

Digital Forensic Tools: Why Ease of Use Is Essential. Magnet Forensics.
https://www.magnetforensics.com/blog/digital-forensic-tools-why-ease-of-use-is-essential/
