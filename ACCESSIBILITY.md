# Accessibility :accessibility:

This project exists to help readers explore Goodreads achievements, challenge badges, and reading goals in a clear and useful way. Accessibility matters here because the content is meant to be helpful to everyone, whether someone is browsing on a laptop, a phone, with a keyboard, or with an assistive technology such as a screen reader. We want people to be able to understand the achievement list, find challenge details, and contribute to the project without hitting unnecessary barriers.

This document explains our accessibility priorities, what contributors should expect, how to report problems, and how the project is maintained.

## Priorities

We prioritize the basics that make a reading guide usable for the widest possible audience:

- clear page structure with meaningful headings and readable text
- keyboard access for links, navigation, and content browsing
- descriptive alt text or labels for badge and image-based achievement content
- strong color contrast and visible focus styles for links and interactive elements
- layouts that remain understandable when zoomed or viewed on smaller screens
- content that works with screen readers and does not rely on color alone to communicate meaning

This repository is a static GitHub Pages site built around markdown content, tables, and badge images. Our goal is to keep the experience simple, readable, and resilient across common browsers and devices. This is an aspirational accessibility goal rather than a formal conformance claim or certification.

## Contributor expectations

Contributors are encouraged to make accessibility part of normal project work, not an afterthought. When making a change to the site or its content, please consider the person reading it in context, not only the visual layout.

Examples of good practice include:

- using clear heading hierarchy instead of relying on visual styling alone
- writing descriptive link text such as “Open the 2026 Fall challenge list” instead of vague text like “click here”
- adding or improving alt text for achievement badges and informative images
- avoiding color-only meaning, such as marking status or category by color without text labels
- keeping tables readable and understandable when zoomed or viewed on a narrow screen
- testing keyboard navigation for page elements and confirming that focus is visible
- documenting any accessibility concerns or testing notes in pull requests for user-facing changes

When a contribution changes layout, image use, content structure, or navigation, a brief note about what was checked and what was tested is helpful. This can include browser testing, keyboard checks, and a short description of the outcome.

## Reporting accessibility issues

If you encounter a barrier or need help using this project, please open an issue on the repository:

https://github.com/BenRogersWPG/Goodreads-Achievements/issues

Please include as much of the following as you can:

- the page or section affected
- the URL or file name involved
- what you expected to happen
- what happened instead
- your browser and operating system
- whether you were using a keyboard, screen reader, or other assistive technology
- screenshots or a short recording if helpful

A screenshot or recording is optional. You do not need to disclose a disability or provide personal medical information to report a problem.

### Severity

We use the following severity labels as a general guide during triage:

- Critical: a user cannot access the core reading guide or complete a key task, and there is no reasonable workaround
- Major: a significant barrier makes the project difficult to use, but there is a temporary workaround
- Moderate: the content is usable but confusing, inconsistent, or difficult in some situations
- Minor: a small issue that affects polish or clarity, but does not block core use

These labels are for triage and communication, not a requirement for reporters to assign them themselves.

### How we respond

When an accessibility issue is submitted, we aim to acknowledge it promptly and keep the reporter informed as the issue is reviewed. In practice, that means:

- we will review the report as part of normal repository maintenance
- we will ask for more detail if needed to reproduce or understand the barrier
- we will share a workaround when one is available while a fix is being developed
- we will update the issue with progress when a change is made or deferred

We cannot guarantee an immediate fix for every report, but we do aim to respond in a reasonable timeframe and to treat accessibility issues seriously. If a fix requires more time, we will explain the status and what is being considered.

## Ownership and maintenance

This project is maintained by Ben Rogers, the repository owner. Accessibility is part of ongoing maintenance for the project, including checking content, reviewing issue reports, and helping ensure that documentation and updates remain usable for a broad audience.

Accessibility review is not limited to one-time work. As the project grows, new challenge lists, badge images, and documentation updates are reviewed with the same questions in mind: can someone find this information, understand it, and use it without unnecessary friction?

## Supported environments

This project is designed for the environments where the repository is typically viewed and shared:

- GitHub.com and GitHub Pages hosting for this repository
- current versions of Chrome, Edge, Firefox, and Safari on desktop
- current mobile browsers on iOS and Android
- keyboard-only navigation and common assistive technologies such as screen readers
- browser zoom and text scaling up to at least 200% without losing core functionality

Because this is a static content repository, support is focused on modern browsers and current accessibility best practices. Older or unsupported browsers may render content less reliably, and some visual or layout differences may still appear depending on platform and assistive technology.

## Known limitations

We are still improving the project in places, and we want to be transparent about known limitations instead of implying that no barriers exist.

Current examples include:

- some achievement pages rely on image-heavy badge layouts, so the visual experience is richer than the plain text experience
- content tables for challenge lists may require horizontal scrolling on very narrow screens in some browsers
- some historical or seasonal badge sections may be updated over time and not every asset has the same level of descriptive labeling yet
- all image have alt tags, but can't guarantee that all fully-describe the image contents in a fully accessible way

These issues are being addressed as the project evolves. If there is a specific barrier you are encountering, please use the issue tracker to report it. We will review it and provide a workaround or fix where possible.

## Feedback and improvements

We welcome suggestions for better accessibility in this project. If you have an idea for improving clarity, navigation, contrast, documentation, or image descriptions, please [open an issue](https://github.com/BenRogersWPG/Goodreads-Achievements/issues) or contribute a pull request.

For active barriers or urgent access issues, please use the reporting process above so the problem is tracked and reviewed. This helps us respond in a way that is useful to the person who encountered the issue and to the wider community using the project.
