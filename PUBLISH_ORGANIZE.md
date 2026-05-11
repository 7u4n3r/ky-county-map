# PUBLISH_ORGANIZE.md

## Purpose

This file defines the publish/organize posture for `ky-county-map`.

This repository is an ABLE-KY-aligned Kentucky county navigation tool.

It exists to support county-level resource routing, civic access, legal-access orientation, and rights-restoration pathways.

## Current public role

KY County Map is a standalone navigation surface for:

- Kentucky county-level resource routing
- ABLE-KY-aligned civic/legal-access navigation
- clickable county map interaction
- public orientation by region
- low-friction county lookup

## Publish-safe description

KY County Map is an ABLE-KY-aligned interactive Kentucky county navigation tool for routing people toward county-level civic, legal-access, and rights-restoration resources.

## What this is

This repo may hold:

- Kentucky county map interface files
- county-level navigation links
- ABLE-KY-facing resource routing
- static HTML/CSS/JS map code
- accessibility improvements
- mobile usability improvements
- embed instructions

## What this is not

This repo is not:

- Perspection governance
- Faceless Reclaimation story material
- Trinity Framework final site
- System Analysis Reference
- a raw legal evidence archive
- a public accusation page
- a catch-all ecosystem homepage

## Entry posture

The public posture should be:

- simple
- civic
- navigational
- accessible
- county-specific
- practical
- low-friction

## Public entry draft

Working headline:

# Kentucky County Map

Working subheadline:

ABLE-KY-aligned county navigation for civic and legal-access resources.

Working entry copy:

This interactive Kentucky county map helps route visitors toward county-level resources and regional access points.

It is built as a lightweight navigation surface that can be embedded, adapted, or connected to ABLE-KY resource pages.

## Publish checklist

Before publishing, confirm:

- [ ] map loads on mobile
- [ ] county labels or hover states are readable
- [ ] click targets route correctly
- [ ] resource URLs are current
- [ ] inactive counties are visually clear
- [ ] the page does not imply legal advice
- [ ] ABLE-KY framing is accurate and approved before public organizational use
- [ ] related projects are not merged into this map identity

## Route/click behavior

County click behavior should remain explicit and easy to edit.

Current expected example pattern:

```javascript
function handleCountyClick(county) {
    const url = `https://able-ky.org/county/${county.toLowerCase()}`;
    window.location.href = url;
}
```

If the final destination URLs differ, update the click handler and document the new routing pattern in `README.md`.

## Related but separate

- Perspection holds governance and observation infrastructure.
- Faceless Reclaimation holds public story/artifact/Reclaimation material.
- Trinity Framework holds structural method and movement logic.
- Trinity Tools holds sandbox experiments and preserved drafts.
- System Analysis Reference holds neutral templates and evidence structures.

## Operating rule

This repository is a navigation tool.

It helps people find the right county-level direction.
It does not absorb the full ecosystem.
It does not become governance, testimony, or analysis by default.
