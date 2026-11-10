# Internal Link Architect

New posts are rooms without doors. This adds the doors.

A free Claude skill from the [AI Ranking community](https://skool.com/ai-ranking-free).

## What it does

1. Builds an inventory of the pages on your site.
2. Picks the exact pages each new post should link to and from, with the anchor text.
3. Outputs a link plan you can apply in minutes.

## Install

**Claude desktop app or claude.ai:** download [internal-link-architect.zip](https://github.com/NicoSKOOL/internal-link-architect/releases/latest/download/internal-link-architect.zip) (don't unzip it), then go to Settings > Capabilities > Skills > Upload skill. Also turn on Code execution and file creation.

**Claude Code:**

```bash
git clone https://github.com/NicoSKOOL/internal-link-architect ~/.claude/skills/internal-link-architect
```

## Data

- **Needs:** the [DataForSEO](https://app.dataforseo.com/?aff=182182) connector for the page inventory.
- For a whole-site pass, see [jev-internal-links](https://github.com/NicoSKOOL/jev-internal-links).

## Use

> Plan internal links for my new post at https://example.com/blog/new-post/

## Where it fits

Step 5 of the AI Ranking SEO loop: site-brief-builder, keyword-fanout-map, seo-content-writer, onpage-optimizer, internal-link-architect, ai-visibility-checker, ai-citation-finder, then back to keywords. Next: [ai-visibility-checker](https://github.com/NicoSKOOL/ai-visibility-checker).

## License

MIT
---

## Part of AI Ranking

This is one of the free tools from **AI Ranking**, the community where we learn how to get businesses found on Google and recommended by AI (ChatGPT, Google AI Overviews, Perplexity).

**Free community:** [skool.com/ai-ranking-free](https://skool.com/ai-ranking-free)  
Every free skill in one place, with setup guides.

**Premium:** [skool.com/ai-ranking](https://skool.com/ai-ranking)  
For when you want help, not just tools:
- Support when a skill or a site gets stuck
- 1-1 sessions
- Live Q&A calls
- The full training on how to rank in AI search

Built by [Nico Gorrono](https://airankingskool.com/about/)
