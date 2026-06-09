# GitHub upload instructions

This package already includes the corrected Zenodo DOI: `10.5281/zenodo.20585267`.

## Upload path

1. Open the GitHub repository: https://github.com/RichNass87/inspector-roofing-ai-homeowner-tool-belt
2. Choose **Add file -> Upload files**.
3. Upload the contents of this folder, not the ZIP file itself.
4. Use this commit message:

```text
Add DOI-updated public documentation package
```

## Release notes

Use `release/GITHUB_RELEASE_NOTES_v0.1.0.md` for the release text.

## Important

This ZIP intentionally does **not** include a root `.zenodo.json` file. The DOI has already been assigned manually, and avoiding root Zenodo metadata helps prevent GitHub-to-Zenodo metadata parsing errors.

Do not upload customer documents, private prompts, API keys, webhook URLs, production source code, signed agreements, or private homeowner files.
