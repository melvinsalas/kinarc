# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Inferred from the explicit brief: buildless static HTML, CSS, and JavaScript using D3.js, suitable for GitHub Pages and Cloudflare Pages.

## Users

Inferred: family historians and genealogists exploring locally held GEDCOM files, often on desktop but with responsive access on tablets and phones.

## Product Purpose

Turn a private GEDCOM file into an explorable semicircular ancestor fan chart. Success means users can understand lineage structure, birthplace patterns, and individual records without uploading family data.

## Positioning

The viewer combines an unlimited-depth genealogical fan layout, explicit empty ancestor slots, country-of-birth color analysis, and client-only privacy in one static application.

## Operating Context

Users open a local `.ged` file, choose a root individual, adjust visible generations, inspect ancestors, customize country colors, and export the chart for research or sharing.

## Capabilities and Constraints

- Family data must never leave the browser.
- Parse individuals, families, parent relationships, names, birth dates, and birthplaces.
- Maintain genealogical structure by rendering missing ancestors as empty segments.
- Support at least 15 generations without an arbitrary application limit.
- Never silently guess ambiguous birthplace countries.
- Use D3.js and remain suitable for static hosting.

## Brand Commitments

Inferred: calm, trustworthy, research-oriented language. Country colors explicitly include Costa Rica blue, Spain red, Japan pink, France purple, and Unknown gray as defaults.

## Evidence on Hand

- User-supplied GEDCOM file: `FamilySearch Import-original.ged`.
- Synthetic sample genealogy may be included and must be labeled as sample data.
- No testimonials, benchmarks, or external claims are available.

## Product Principles

- Privacy is visible and verifiable.
- Structure is never hidden: unknown ancestors retain their place.
- Geographic inference is transparent about uncertainty.
- Dense genealogical information remains navigable and exportable.
- The chart is the primary workspace, not decoration.

## Accessibility & Inclusion

Inferred: keyboard-operable controls, visible focus states, sufficient contrast, scalable text, and color labels that do not rely on color alone.
