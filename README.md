# Tyler Griffin Portfolio

## Accessibility fixes

- I darkened the muted text color to `#5b706e` so it meets WCAG AA on both the paper and white surfaces.
- I changed keyboard focus outlines to the high-contrast ink color and added clear focus indicators to form controls.
- I removed unnecessary link labels that overrode their visible text, keeping accessible names aligned with the labels users see.
- I added a contact form with explicit labels, a fieldset and legend, required fields, and programmatically associated hints.
- I added inline validation messages, `aria-invalid` states, and a live status message so form feedback is available to assistive technology.
- I clarified that the demo form validates input but is not connected to a message service.

## Visual design

- I used proximity to group related form labels, controls, hints, and errors, and to keep the portfolio cards visually grouped.
- I used similarity by repeating the same card surfaces, rounded project tags, and teal-and-rust palette across all three pages.

## Contrast

The shared palette uses ink `#173b3a`, muted text `#5b706e`, rust `#a74d34`, paper `#f7f8f3`, and white `#ffffff`; the lowest text contrast is 4.93:1 for muted text on paper, above the WCAG AA 4.5:1 requirement.

## WAVE testing

I could not run WAVE because these local pages are not deployed to a public URL for the service to scan; run WAVE on all three pages after deployment.
