# matla.zaplatform.com

The landing page of **مطلع (Matla)**, the free Arabic prayer-times app for iPhone and Apple Watch.
Served by GitHub Pages from `main` at the repo root, custom domain `matla.zaplatform.com` (`CNAME`).

**Don't edit these files by hand.** They are generated from the design folder
`design-thoughts/matla-landing/` (the source of truth), where the README explains every file:

    cd design-thoughts/matla-landing
    python3 tools/gen-faq.py          # FAQ JSON-LD from the visible FAQ
    python3 tools/build-docs.py       # privacy + terms pages from markdown
    python3 tools/build-site.py <this repo>
    # then commit and push here

Stable URLs (the app and App Store Connect point at them): `/privacy/`, `/terms/`, `/#support`,
and their English twins under `/en/`.
