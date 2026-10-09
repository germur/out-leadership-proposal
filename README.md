# Out Leadership — Digital Platform Proposal

An interactive English proposal for Todd Sears and Manny Gallegus, focused on Return on Equality, independent publishing and a connected digital ecosystem.

## Run locally

No dependency installation or build is required. From this repository:

```sh
python -m http.server 4173 --directory dist --bind 127.0.0.1
```

Open http://127.0.0.1:4173. Stop the server with Ctrl+C. You can also open `dist/index.html` directly; keep the complete `dist` directory together.

## Included experiences

- Three-step guided walkthrough and editable featured-leader example.
- Page builder with approved blocks, responsive preview, undo, local draft storage and standalone HTML export.
- Public research journey, illustrative member access, connected microsites and sample HubSpot enquiry.
- Interactive architecture with technology logos and official documentation.
- Twelve-week delivery proposal: desktop workstream board and mobile phase cards, with SEO throughout.
- Frontend/backend handoffs, expandable scope decisions and local discussion checklist.

## Scope and boundaries

This repository implements the proposal and its browser-only simulations. It does not implement the proposed production Astro website, Storyblok CMS, Django backend, authentication or CRM integration. Storyblok remains a candidate subject to an editor trial. The twelve-week target assumes discovery, agreed scope and backend alignment; no cost or fixed backend estimate is included.

No form submissions, member authentication or CRM requests are sent. Builder drafts stay in browser localStorage; other examples are temporary page state. The proposal includes `noindex,nofollow`; this controls indexing, not access. Hosting visibility is configured separately.

## Hosting

Serve the entire `dist` directory on a static host. Asset references are relative and support hosting under a repository path. The existing private proposal is at https://out-leadership-digital-proposal.germur.chatgpt.site/.

## Assets and checks

Technology icons are sourced from Simple Icons and identify their respective products; they are not endorsements. Other illustrations are SVG/CSS. See `VERIFICATION.md` for checks and limitations. Original emails, diagnostic PDFs and hosting credentials are not part of this repository.
