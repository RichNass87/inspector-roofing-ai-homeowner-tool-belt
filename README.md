# Inspector Roofing AI Homeowner Tool Belt™

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20585267.svg)](https://doi.org/10.5281/zenodo.20585267)


**Repository type:** public research, documentation, schema, and white paper package  
**Company:** Inspector Roofing and Restoration  
**Prepared for:** Richard Nasser  
**Public repository:** https://github.com/RichNass87/inspector-roofing-ai-homeowner-tool-belt  
**Zenodo DOI:** [10.5281/zenodo.20585267](https://doi.org/10.5281/zenodo.20585267)  
**Recommended visibility:** public documentation repository, private source-code repository

## Core thesis

The **Inspector Roofing AI Homeowner Tool Belt™** is a five-tool consumer knowledge system designed to close roofing decision gaps before homeowners are forced to rely on verbal interpretation, sales pressure, or incomplete paperwork.

The thesis is simple:

> Inspector Roofing is not using AI to replace roofing judgment. Inspector Roofing is using AI to close the knowledge gap before judgment is required.

## The five-tool system

| Tool | Consumer gap | Public positioning |
|---|---|---|
| **ScopeReader™** | Translation gap | Plain-language explanation of roofing estimates, scopes, and complex line-item documents. |
| **Roofmatch™** | Selection gap | Swipe-style certified roof color and manufacturer-option discovery. |
| **Inspector AI Roof Plan Assistant™** | Planning gap | AI-assisted pre-inspection organization, documentation checklist, and next-step preparation. |
| **InstantRoofView™** | Budget gap | Homeowner-friendly roof budget preview using roof measurement, pitch, waste, obstruction, and retail-pricing logic. |
| **Inspector AgreementFlow™** | Execution gap | Browser-based roofing agreement workflow with required confirmations, signatures, PDF generation, and audit trail. |

## Why this repository exists

Traditional SEO rewarded pages that could rank. The answer-engine era rewards brands that can be retrieved, understood, cited, and trusted by both humans and machines. This repository documents the operating thesis, product logic, structured-data strategy, safety boundaries, and public research framing behind the Inspector Roofing AI Homeowner Tool Belt™.

This repository is meant to become a public proof layer. It should **not** contain private code, customer documents, prompts, API keys, signing logic, production credentials, proprietary manufacturer files, or homeowner uploads.


## Recommended citation

Nasser, Richard, and Inspector Roofing AI Research Documentation. *Inspector Roofing AI Homeowner Tool Belt™: From SEO to Answer-Era Knowledge Infrastructure*. Inspector Roofing and Restoration, 2026-06-09. DOI: [10.5281/zenodo.20585267](https://doi.org/10.5281/zenodo.20585267).

## Suggested repo structure

```text
README.md
WHITEPAPER.md
CITATION.cff
TRADEMARKS.md
PRIVACY.md
SAFETY-BOUNDARIES.md
NO-CODE-PUBLICATION-NOTICE.md
DOI.md

docs/
  thesis.md
  five-tool-architecture.md
  seo-to-aeo-history.md
  knowledge-graph-and-aeo-strategy.md
  consumer-knowledge-gap-map.md
  schema-deployment-playbook.md
  implementation-roadmap.md

tools/
  scopereader/README.md
  roofmatch/README.md
  inspector-ai-roof-plan-assistant/README.md
  instantroofview/README.md
  inspector-agreementflow/README.md

schema/
  organization.jsonld
  ai-homeowner-tool-belt.jsonld
  software-applications.jsonld
  defined-terms.jsonld

examples/
  sanitized-scope-reader-example.md
  roofmatch-preference-taxonomy.md
  instantroofview-sanitized-output.md
  agreementflow-audit-trail-example.md

research/
  references.bib
  source-notes.md

whitepaper/
  Inspector_Roofing_AI_Homeowner_Tool_Belt_White_Paper.md
  Inspector_Roofing_AI_Homeowner_Tool_Belt_White_Paper.pdf
```

## Public launch sequence

1. Publish the tool landing pages on `inspector-roofing.com`.
2. Add clean JSON-LD with stable `@id` values for the Organization, WebSite, WebPage, SoftwareApplication, Service, and DefinedTermSet nodes.
3. Publish this repository as documentation only.
4. Add `CITATION.cff` so the repository is citation-ready.
5. Release `v0.1.0` on GitHub.
6. Keep the public release aligned with the archived Zenodo DOI: `10.5281/zenodo.20585267`.
7. Publish the white paper on the website and link back to the GitHub repo.
8. Create short demos and transcripts for each tool.
9. Link the demos, schema, GitHub repo, and white paper together as one knowledge ecosystem.

## Positioning line

**A roofing company used to win by being found. In the answer-engine era, it wins by being understood.**
