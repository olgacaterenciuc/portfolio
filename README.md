# portfolio
My personal portfolio website showcasing my projects, skills, and experience.

## Pages

- [Landing page](./index.html): introduction, selected work, experience, and contact links.
- [Agent Hub case study](./agenthub.html): Learn and Adopt ownership, selected prototype screens, scope decisions, public preview, and leadership outcomes.
- [Connected Selling case study](./connected-selling.html): an anonymized case study about a rapid, cross-team demo.

The site uses the HTML designs supplied in the ZIP, with inline CSS and JavaScript
and shared navigation and accessibility styles in [prototype.css](./prototype.css).
No framework, package installation, or build step is required.

## Prototype flow

1. On the landing page, select **Work** or the hero's **Scroll** link.
2. Select the **Agent Hub** or **Connected Selling / View case study** card.
3. Use the case study's **Contents** links to jump between sections.
4. Select **All work** in the header or **Back to work** near the footer to
   return directly to the landing page's selected work.
5. Use **Connected Selling** at the end of Agent Hub, or **Previous case study:
   Agent Hub** on Connected Selling, to move between the case studies.

**Work** and **About** navigation is available on desktop and mobile. Links support
keyboard focus, and animations respect the system's reduced-motion preference.
Email and LinkedIn links open their real destinations rather than prototype screens.
The landing-page case-study cards are text-only; project screenshots appear inside
the case studies.

## Local preview

From the project directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://127.0.0.1:8000> in your browser. Stop the server with `Ctrl+C`.

## Assets and content

Fonts load from Google Fonts and require an internet connection. Case-study
screenshots are stored locally in [assets](./assets).
Contact details are preserved from the supplied designs.
One remaining case-study card is intentionally marked "Coming soon."

### Agent Hub

The three supplied prototype exports replace the original external-image gallery:

- [Hub landing page](./assets/agenthub-overview.png): the replacement landing-page export, with rollout, calculator, and insights entry points alongside learning resources.
- [Agent selection](./assets/agenthub-adopt-selection.png): agent and capability choices.
- [Rule configuration](./assets/agenthub-adopt-rules.png): prerequisites and case follow-up rules.

Only decorative export edges are trimmed; application pixels are not rescaled,
and the original attachments are unchanged. Images display without cropping,
upscaling, grayscale, or added borders, with soft elevation and full-size links.
These are selected prototype screens, not the entire experience or evidence of
measured adoption or savings.

The narrative distinguishes leading Learn and Adopt from supporting Measure.
The portfolio owner confirmed that Agent Hub entered public preview in August
2025, superseding the original October 2025 targets. This is a product-level
milestone, not a separate release claim for each pillar or confirmation of general
availability. Leadership prioritization and recognition are retained from the
supplied case-study record; no usage metrics or usability-test results are added.
Feedback now uses two exact excerpts: leadership feedback supplied by the owner
and Mark McLeish's public LinkedIn post, transcribed from the supplied screenshot.
The internal speaker is unnamed; no job title or publication date is inferred
for the public post. The earlier unsourced testimonial wording is not restored.
The screenshot itself, including phone UI and unrelated personal details, is not
copied into the repository. The original post URL has not yet been supplied.
Both excerpts are presented as qualitative feedback, not evidence of adoption,
business results, or the scale of public engagement.

## Confidential case study

Connected Selling is a descriptive portfolio title, not the original project name.
The case study is based on the provided summary, presentation-slide references, and
an anonymized excerpt from customer feedback,
not the protected source document. The slides clarified visual-fidelity and
structure ownership, the customer's internal audience, the authenticity feedback
and response, and qualitative reviewer feedback.
The authenticity issue and subsequent pivot are presented as an explicit sequence:
initial problem, a shift to existing product patterns and platform-team guidance,
and qualitative improvement. This is a change in approach, not a full rebuild.
It omits client, organization, collaborator, product, and hosting-provider names
from the project narrative. No source document, presentation-slide references,
feedback screenshot, or video was added to the repository for this case study.
The slides were paraphrased into anonymized text, and the customer feedback was
excerpted without the event name or identifying attribution.

The local [demo image](./assets/connected-selling-overview.png) is an unchanged copy
of the replacement screenshot supplied for this case study. It includes the
talking-points thread panel on the right. The owner confirmed that the names
and details in the image are fictional presentation data, so they are retained
without redaction and labeled as fictional in the page caption. Product interface
branding remains visible. The original attachment was not modified.
A soft CSS shadow and rounded corners add elevation without an image border.
The image is the original 1479 × 768 PNG, preserved byte-for-byte,
without resampling or artificial upscaling. The full-size link uses the same PNG.
Only a selected demo screen is shown; the full prototype is withheld for
confidentiality, as explained in the page's introductory note.
The screen follows a compact opening summary. Numbered HTML annotations explain
three visible features without changing the source PNG or attributing every
interaction to one designer. The image is loaded eagerly as primary page content.

The demo is not presented as a shipped product, and no launch, adoption, or
business-impact claims are made. Outcomes describe qualitative reviewer feedback
and direct feedback from the requesting customer representative. The quoted
excerpt preserves the original wording, with anonymous role-based attribution.
The customer's anticipated stakeholder response is not presented as a measured
result or a confirmed event presentation; final event delivery remains unconfirmed
and is not claimed.
The standalone hosting/access section is omitted so the pivot leads directly
to the customer response and takeaways.
The before-and-after comparison describes the disconnected starting workflow
versus the proposed CRM access inside the collaboration workspace, not a shipped
feature or two visual-design revisions. An approved visual iteration example
could provide additional evidence; the complete prototype need not be disclosed.
Any future visual assets also need an identification and disclosure review.
