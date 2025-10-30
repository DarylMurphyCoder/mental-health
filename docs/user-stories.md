# User Stories for MindfulHealth

## User Story: Quick Self-Check & Immediate Support

Title: Quick Self-Check and Easy Access to Help

As a visitor to the MindfulHealth site,
I want to complete a short self-check and see clear next steps,
so that I can quickly understand whether I may need immediate support and how to access it.

Background / Context
- The site provides a hero CTA, a resources section (hotlines, therapy, self-help), a short self-check form, and a visible emergency hotline.
- Users may visit the site from mobile or laptop and need accessible, readable controls.

Acceptance Criteria
- The self-check form is reachable from the hero section (link anchors work and content isn't hidden under the fixed navbar).
- The self-check form contains two questions with selects and a Reflect (submit) button.
- When the user submits the form, a short, non-diagnostic feedback message appears in the page, with three tiers (green/yellow/red) based on the score.
- The Reflect button uses the site primary action color (same as navbar/footer) and is visually prominent and keyboard-focusable.
- The emergency hotline is clearly visible in the contact section and in the footer; `Get Help Now` links anchor to it.
- Form controls are readable: select options are black on white, labels align across screen sizes, and the layout does not break on laptop screens.

Notes / Implementation Details
- Ensure `#selfCheckForm` selects have explicit color/contrast rules to override broad global text styling.
- Use responsive CSS so long labels do not push select inputs out of alignment on larger screens.
- Provide clear, accessible ARIA attributes where needed (aria-live on the result container for screen readers).

Estimate: 1–2 story points (small UI + accessibility polish)

Owner: @frontend

---

.