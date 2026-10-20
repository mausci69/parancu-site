# ParancU Lab website

Static English-language website for ParancU Lab, the project identity for Maurizio Scibilia’s independent work on evidence-oriented document AI.

Website: [parancu.com](https://parancu.com/). Web application: [ParancU Agent Lab](https://lab.parancu.com/).

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Lab identity, applications and collaboration |
| `technology.html` | Retrieval approach and processing boundaries |
| `products.html` | iOS app, Agent Lab and all existing downloads |
| `research.html` | Research projects, methodology, scoped observations and negative findings |
| `pilot.html` | Potential industrial applications and proposed pilot process |
| `contact.html` | Existing author contact |
| `agent-lab.html` | Application workflow, bounded recovery and data handling |
| `support.html` | Existing ParancU iOS support information |
| `privacy.html` | Existing iOS privacy policy, with application scope clarified |

All content pages share `assets/css/site.css`, navigation, footer and keyboard skip link. There is no framework, build dependency, JavaScript navigation, analytics, contact-form backend or externally loaded font/image dependency.

## Products and resources

- [ParancU on the App Store](https://apps.apple.com/it/app/parancu/id6788739843)
- [Agent Lab](https://lab.parancu.com/)
- [White paper](parancu_v1_1_white_paper.pdf)
- [Project overview](parancu_pitch.pdf)
- [Instructions](parancu_instructions.pdf)
- [Demo script and test queries](parancu_demo_script_and_test_queries.pdf)
- [Maurizio Scibilia CV](Maurizio_Scibilia_CV.pdf)

PDF filenames, `agent-lab.html`, `support.html`, `privacy.html`, `CNAME`, `robots.txt` and the Google verification response remain available at their original paths. The sitemap lists all nine content pages. Root and `index.html` are both valid entry points; the root is canonical.

## Local review

Serve a temporary directory containing only public files with any static HTTP server. Exclude dotfiles and internal Markdown from previews. No build is required. Check all nine pages at desktop and mobile widths, keyboard navigation, internal links, PDF responses and the app links before publication.

## Publication and internal material

The existing GitHub Pages publication mechanism is retained. `CNAME` remains `parancu.com`. No deployment is triggered by local edits; pushing or merging to a publishing branch is a separate owner-approved action.

Internal editorial material is deliberately ignored by Git and excluded from the default Jekyll build. This is not access control: do not force-add internal documents to this public repository, bypass the exclusion with a raw-root deployment, or link their source register from the website. Public pages contain neither private filesystem paths nor internal source IDs. Research observations are dated and qualified; code, mock tests and model judgments are not presented as certified reliability.

ParancU Lab is a project identity, not a claim of incorporation, institutional status or staffing. Potential pilot areas and enterprise cloud/API services are explicitly prospective. No customer deployment, partnership or commercial outcome is claimed.

## Deployment review notes

Keep the default GitHub Pages/Jekyll handling of `_config.yml` exclusions. If publishing changes to a custom artifact workflow later, assemble an explicit public-file artifact instead of uploading the repository root. Publication requires owner authorization.

## Implementation verification — 20 October 2026

- Nine content pages checked in Chromium at 1440, 768, 390 and 320 CSS pixels: no document-level horizontal overflow. The research table scrolls within its labeled region on narrow screens.
- All 170 local page, anchor and asset references resolve; navigation and keyboard skip-to-content work.
- Root/index aliases, existing content URLs, sitemap, robots, search verification and all five PDF responses checked over a local public-only HTTP preview.
- All five PDF files, CNAME, robots and Google verification are byte-identical to the fetched site baseline. Existing support/privacy statements are preserved.
- The internal context and Git metadata return 404 in the public-only preview. Git ignores the context and Jekyll explicitly excludes it.
- Source whitespace checks passed during the implementation review, before publication.

## Final branding verification — 20 October 2026

The approved PL artwork supplies the header icon, PNG favicons, multi-size ICO, Apple touch icon and share metadata. The Apple touch icon is opaque RGB at 180×180, with neutral outer padding replaced by deep green; the central monogram is preserved. All nine headers use the same 40-pixel presentation. Icon assets are under `assets/icons/`, with `favicon.ico` and `site.webmanifest` at the root.

Final local validation passed 36 nine-page layout checks at four desktop/mobile widths, keyboard navigation, 224 local references, image dimensions, original PDF/domain-resource integrity and preservation of approved body copy. The temporary icon preview was removed and excluded from both Git and Jekyll output. These checks do not certify rendering on physical iPhone hardware.
