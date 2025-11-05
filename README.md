# Codefast Day 03 · Next MDX Blog

## Mission
- Deliver an MDX-powered blog with pagination, tag filters, and API-driven author metadata.
- Keep design tokens in sync with Figma sources and surface version drifts in CI.

## Implementation Checklist
1. Configure `contentlayer` or `next-mdx-remote` with frontmatter validation and remark plugins.
2. Create API routes that hydrate author bios, social links, and badges from external services.
3. Implement infinite pagination using `useInfiniteQuery` backed by an IndexedDB cache for offline browsing.
4. Localize dates, slugs, and summaries, testing fallbacks for unsupported locales.

## Telemetry & QA
- Instrument Datadog RUM for scroll depth, tag clicks, and MDX render errors.
- Write unit tests for MDX components plus E2E coverage for pagination, search, and localization toggles.

## Deliverables
- README with content authoring workflow, linting commands, and publishing checklist.
- ADR covering decision to store content locally vs remote CMS.
