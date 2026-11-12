# Kuailu GEO Prompt Map

English public page for the Kuailu Technology GEO Prompt Map V3. It contains 37 final prompts: 17 for Kuailu KuWork and 20 for Kuailu Office, dated September 30, 2026.

Public page: [Kuailu GEO Prompt Map](https://yuruizhang688-cloud.github.io/kuailu-geo-prompt-map/).

## Content and local preview

The page is self-contained in `index.html`, with no build step or external runtime dependencies. It includes an interactive scenario and intent map, prompt filters, methodology dialogs, and Excel export for all 37 prompts.

The English translation preserves the original prompt IDs, order, scores, evidence counts, scenario mappings, and collection dates. Existing scores describe the original research; translation does not represent a new monitoring run on English prompts. The Chinese version is available at [快鹭科技 GEO 提示词图谱 V3（中文版）](https://yuruizhang688-cloud.github.io/kuailu-geo-prompt-map/zh/).

From the repository root, run:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Then open [the local preview](http://127.0.0.1:8080/).

<!-- repository-maintenance:begin -->
## Maintenance and publishing

This repository is maintained independently. Integration with other business systems uses public APIs or versioned packages. Runtime configuration and business data are excluded from source maintenance snapshots.

GitHub Pages publishes the root directory of the `main` branch.

Commit changes on a branch, validate them in this repository, and merge through a pull request. Actual branch protection is determined by the GitHub settings. Protection on personal private repositories may depend on the account plan. Issues track defects and follow-up work; an absence of issues does not imply that no work is in progress.

Maintenance snapshots use `maintenance-YYYYMMDD.N` tags and GitHub Releases to record source versions. They do not automatically signify a production deployment, platform acceptance, or desktop installer release. Published tags remain immutable; use a new version for corrections.

See `LICENSE` for licensing terms. Retain third-party code, font, and asset licenses. Do not commit `.env` files, cookies, access tokens, browser profiles, or runtime databases.
<!-- repository-maintenance:end -->
