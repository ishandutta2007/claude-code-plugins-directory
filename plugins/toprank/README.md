# Toprank

Toprank is an open-source Claude Code plugin for SEO and Google Ads workflows. It connects Claude Code to Google Search Console and Google Ads data, surfaces issues that hurt traffic or waste spend, and can apply fixes directly in the repository when the agent has code access.

Repository: https://github.com/nowork-studio/toprank

## Why it is useful

- Runs SEO audits with Google Search Console data instead of static checklists
- Finds and fixes metadata, heading, schema, and content issues directly in code
- Supports Google Ads audits, keyword cleanup, negative keyword suggestions, and copy generation
- Includes repo-aware Claude Code skills such as `/toprank:seo-analysis`, `/toprank:meta-tags-optimizer`, and `/toprank:ads-audit`

## Install

Run these commands in Claude Code:

```text
/plugin marketplace add nowork-studio/toprank
/plugin install toprank@nowork-studio
```

## Notes

- Open source and MIT licensed
- Current GitHub repository: 129 stars
- Plugin metadata and skills live in the upstream repository under `.claude-plugin/` plus the `seo/`, `google-ads/`, and `gemini/` directories
