# Consolidated Test Plan

## Test environment
- A desktop or mobile web browser.
- Internet access is needed for the illustrative placeholder images hosted externally.
- Open each case study's `index.html` file.

## General checks
| ID | Check | Expected result |
|---|---|---|
| GEN01 | Open each index.html | Corresponding webpage opens without requiring a server-side application |
| GEN02 | Inspect headings and paragraphs | Content hierarchy is readable |
| GEN03 | Inspect images | Placeholder image appears; alternative text is available if image cannot load |
| GEN04 | Use navigation hyperlinks | Browser moves to the matching section in the same document |
| GEN05 | Inspect ordered and unordered lists | List items appear in the correct order and grouping |
| GEN06 | Inspect CSS stylesheet | Colours, font properties, borders, width, height, margins and padding are applied |
| GEN07 | Inspect source files | No JavaScript, framework, backend or database code is present |

Detailed case-specific tests are stored in each case-study folder's `TEST-CASES.md`.

## Limitations
- These are static front-end webpages.
- Contact email links open the user's default email application; no message is submitted to a server.
- Placeholder content and sample contact details must be replaced before final academic submission.
- External placeholder images require internet access.
