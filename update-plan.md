# Website Support & Policy Update Plan

## Objectives
- Enrich the support landing page and its child resources with clear remote-support guidance for macOS and Windows.
- Provide visitors an easy preview and download for the business card asset.
- Ensure the Manuals landing page routes users to the correct manuals hub.
- Draft and publish a comprehensive company policy page tailored to System Solve Solutions.

## Scope Breakdown

### 1. Support Hub Enhancements (`support/index.html`)
- Introduce a concise overview describing available support channels (phone, email, remote assistance).
- Add prominent call-to-action tiles linking to:
  - Remote Support instructions (new/updated `support/remote-support.html`).
  - Manuals hub (`support/manuals.html` or main `manuals.html`).
  - Policy page (`support/policy.html`).
- Confirm footer/navigation remains consistent with the global template.

### 2. Remote Support Guide (`support/remote-support.html`)
- Organize guide into parallel macOS and Windows sections using accessible headings.
- Recommend cost-effective, easy-to-use tools:
  - **Windows:** Microsoft Quick Assist (pre-installed), fallback TeamViewer QuickSupport.
  - **macOS:** Built-in Screen Sharing (Messages) and AnyDesk Free for commercial use review.
- Include step-by-step walkthroughs, prerequisites, screenshots placeholders, and escalating-contact instructions.
- Provide troubleshooting tips (network permissions, security prompts) and a fallback phone contact.

### 3. Business Card Preview (`support/business-card.html` or new page)
- Embed a scaled-down `<img>` preview of existing business-card PNG (assume asset path `support/business-card.png`).
- Provide dual download links:
  - Direct PNG download button.
  - Existing PDF link for print-ready version.
- Note recommended print specs (dimensions, bleed) in caption.

### 4. Manuals Landing Page (`manuals.html` and `support/manuals.html`)
- Replace any outdated or circular links with direct navigation to each manual under `manuals/` directory.
- Add short descriptions per manual category for clarity.
- Maintain consistent layout/footers with primary site.

### 5. Policy Page Refresh (`support/policy.html`)
- Draft tailored policy covering:
  - Service scope and response times.
  - Remote support terms & customer responsibilities.
  - Privacy/data handling and liability limitations.
  - Payment, cancellations, and warranty clauses.
  - Contact and escalation paths.
- Format with clear headings, list structures, and callouts for critical clauses.

## Content & Asset Requirements
- Confirm location/name of business card PNG; copy into `support/` if not already present.
- Gather company-specific policy details (operating hours, legal name, FL coverage).
- Optional: capture annotated screenshots for remote-support steps.

## Implementation Checklist
1. Update support landing page content blocks and navigation.
2. Rewrite remote-support guide with macOS/Windows flows and affordable tool recommendations.
3. Enhance business card page with PNG preview and download CTA.
4. Correct manuals landing navigation to point to actual manuals.
5. Draft and format new policy document.
6. Cross-verify all internal links and footers.
7. Perform accessibility review (heading order, alt text) and mobile responsiveness check.
8. Conduct final QA sweep: link validation, spell-check, and visual consistency.

## Out-of-Scope (for now)
- Creating new graphic assets beyond resizing/embedding existing PNG.
- Implementing backend ticketing or authentication systems.
- Adding paid remote-support platform integrations.

## Timeline & Ownership
- **Day 1:** Gather content, finalize remote-support copy, update support hub structure.
- **Day 2:** Implement business card preview/download, manuals navigation corrections, draft policy page.
- **Day 3:** QA pass, stakeholder review, revisions, and deploy.

## Success Metrics
- Support page clearly communicates remote assistance options with <3 clicks to actionable steps.
- Business card asset is previewable and downloadable in both PNG and PDF formats.
- Manuals landing page correctly routes to all manuals without dead links.
- Policy page reflects company practices and is easy to scan.
