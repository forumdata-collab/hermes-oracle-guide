# Changelog

All notable changes will be documented in this file.
Format based on [Keep a Changelog](https://keepachangelog.com/).

## [1.2.0] - 2026-09-17
### Added
- §16 Free-tier monitoring + daily billing push (OCI Usage API) — all four languages.
- `sitemap.xml` (4 locales with `xhtml:link` hreflang annotations) and `robots.txt`.
- `canonical` + `hreflang` (zh-Hant / en / zh-CN / ar / x-default) + Open Graph
  (`og:locale`, `og:locale:alternate`, `og:url`, `og:title`, `og:description`) on every language.

### Changed
- Table of contents grouped into three collapsible stages (Getting started / Deploy /
  Advanced & ops) and now includes the appendix.
- Sub-heading numbering unified: `▎15.1`–`▎15.6` (§15) and `▎A.1`–`▎A.3` (appendix).
- Hero copy, the "free forever" feature card and the disclaimer now state both tiers
  (Always Free 2 OCPU/12GB vs PAYG 4 OCPU/24GB, see §15) and are dated as continuously updated.
- TOC labels in the English and Arabic editions rewritten (previously machine-translated,
  e.g. "12 Trampling Collection" → "12 Pitfalls").
- Ko-fi call-to-action localised per language (was Traditional Chinese on every edition).
- Related-links block: all four editions now carry the same 8 links; the Quark/Drive row that
  sat outside `.link-block` in the Traditional Chinese edition was moved inside it.
- zh-CN edition: 39 lines of Cantonese (嘅／唔使／睇／咗／冇／喺) rewritten as written Mandarin.

### Fixed
- Arabic edition: shell commands inside 38 code blocks had been machine-translated
  (`sudo` → `سودو`, `curl` → `حليقة`, `Environment=` → `البيئة=`) and were unusable —
  code blocks are now canonical, with only comments translated.
- Arabic edition: code blocks forced to `direction: ltr` so RTL layout no longer scrambles
  quotes, paths and flags.
- English edition: garbled heading "枞DeepSeek API Key"; broken `DEEPSEEK_API_KEY` placeholder.

## [1.0.0] - 2026-08-23
### Added
- Initial release.
