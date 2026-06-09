# Schema Deployment Playbook

## Rules

1. Use JSON-LD.
2. Use stable `@id` values.
3. Keep schema consistent with visible page content.
4. Validate with Google's Rich Results Test and Schema.org validator.
5. Avoid duplicate FAQPage schema from plugins, blocks, and custom code.
6. Do not mark up claims that are not visible to users.
7. Prefer complete, accurate recommended properties over bloated or inaccurate markup.

## Suggested schema types

- `Organization`
- `LocalBusiness`
- `RoofingContractor`
- `WebSite`
- `WebPage`
- `SoftwareApplication`
- `WebApplication`
- `Service`
- `DefinedTermSet`
- `DefinedTerm`
- `Article`
- `TechArticle`
- `Report`
- `BreadcrumbList`
- `VideoObject`
- `ImageObject`

## Stable ID pattern

```text
https://inspector-roofing.com/#organization
https://inspector-roofing.com/#website
https://inspector-roofing.com/ai-homeowner-tool-belt/#toolbelt
https://inspector-roofing.com/scopereader/#software
https://inspector-roofing.com/roofmatch/#software
https://inspector-roofing.com/inspector-ai-roof-plan-assistant/#software
https://inspector-roofing.com/instant-roof-quote-generator/#software
https://inspector-roofing.com/inspector-agreementflow/#software
```

## Deployment order

1. Organization + WebSite across site.
2. WebPage + SoftwareApplication on each tool page.
3. DefinedTermSet for knowledge gaps and roofing terms.
4. Article/Report schema on the white paper page.
5. VideoObject on demos with transcripts.
