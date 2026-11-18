# Microsoft Purview: Data Security Art of the Possible

A practical PDF guide to data security, governance, compliance, and AI readiness with Microsoft Purview. It is written to be read on its own, without a presenter.

## Get the guide

**Landing page:** https://rodneymhungu.github.io/data-security-art-of-the-possible/

**Direct download:** [data-security-art-of-the-possible-purview.pdf](https://rodneymhungu.github.io/data-security-art-of-the-possible/data-security-art-of-the-possible-purview.pdf)

The PDF is committed to this repository and served by the landing page, so the in-page preview works. That committed copy is the canonical, current version. Tagged [Releases](https://github.com/rodneymhungu/data-security-art-of-the-possible/releases) are kept as dated snapshots for version history, not as the primary download, so there is only one file to update.

## How the landing page works

`index.html` is a single page with no build step. A data block at the top of the file holds the deck facts (date, page count, size), the six sections with their page ranges, and a slide index with capability tags. The section cards and the searchable slide index render from that block, and every link opens the PDF at the right page. Slide previews live in `images/`, listed in `images/manifest.json`.

When the PDF is replaced: update `DECK` and `UPDATED` in the data block, check the page numbers in `SECTIONS` and `SLIDES`, and re-render the images listed in the manifest.

## What is inside

Six sections: current data security challenges, Microsoft's approach with Purview, two worked customer scenarios (corporate espionage, and GenAI oversharing through Copilot), the Purview agents, and recommended next steps. The deck has built in navigation, so you can jump straight to the section you need.

## Feedback and contributions

Spotted something out of date, or have a scenario worth adding? Open an issue. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Credits

This deck originates from Microsoft and was produced by its data security product and field teams as part of the Art of the Possible material. Rodney Mhungu maintains this public version. Shared as community reference material with attribution to Microsoft. No ownership or licence is asserted over the Microsoft content. It is not an official Microsoft publication.
