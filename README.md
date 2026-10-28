# New SAP Exam Format 2026: Scenario-Based and System-Based Guide

A single, self-contained web page explaining SAP's new performance-based certification
exam format: scenario-based assessments (SBA) and system-based assessments (SyBA).

The page covers every exam code in the 2026 new-format portfolio, an old-versus-new
comparison, a step-by-step preparation guide, official SAP resources only, and FAQs
people actually search for.

## Files in this repository

| File | Purpose |
| --- | --- |
| `index.html` | The complete web page. Self-contained: embedded CSS, inline SVG graphics only, no build step, no dependencies. |
| `README.md` | This file. |
| `robots.txt` | Crawl rules that allow all crawlers and reference the sitemap. |
| `sitemap.xml` | Sitemap entry so search engines can index the page. |

There are no image files in this repository. All imagery is inline SVG embedded in the
HTML, so nothing can break and nothing needs to be downloaded at runtime.

## Publishing to GitHub

1. Create a new repository, for example `sap-new-exam-format`.
2. Copy these four files into the repository root.
3. Push the files.
4. Enable GitHub Pages for the repository.
5. Replace the placeholder URLs before publishing:
   - In `index.html`: replace `https://yourname.github.io/sap-new-exam-format/` in the
     canonical link and the Open Graph URL with your real GitHub Pages URL.
   - In `sitemap.xml`: replace the placeholder `<loc>` URL with your real GitHub Pages URL.
6. After enabling Pages, visit your live URL and confirm the page loads, the table of
   contents anchors work, and no console errors appear.

## Customizing

- Update the last-updated date in the footer of `index.html`.
- Re-verify all external links before publishing. SAP changes exam pages and product URLs
  frequently. Start from the SAP Certification hub: https://learning.sap.com/get-certified
- Exam codes, cut scores, and durations change with each new exam version. Always confirm
  current details on SAP's official certification pages before you book.

## SEO and accessibility notes

- Single H1, semantic HTML5 landmarks, descriptive heading hierarchy.
- JSON-LD structured data: TechArticle and FAQPage.
- All links are plain, crawlable `<a href>` links with descriptive anchor text.
- Every inline SVG carries `role="img"`, `aria-label`, and a `<title>`.
- Keyboard-friendly navigation, skip-to-content link, dark mode and print styles included.

## Disclaimer

This guide is independent and is not affiliated with, endorsed by, or sponsored by SAP SE.
SAP, SAP S/4HANA, SAP BTP, SuccessFactors, Ariba, Concur, Fieldglass, Signavio, LeanIX,
Analytics Cloud, Business Data Cloud, Joule, SAP Activate, and all SAP product names are
trademarks of SAP SE.

Last updated: October 28, 2026.
