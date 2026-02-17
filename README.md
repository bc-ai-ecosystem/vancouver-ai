# Vancouver AI Community Meetups Archive

**A community-maintained open data resource for AI practitioners, researchers, and tinkerers.**

Welcome to the public archive of the [Vancouver AI Community](https://vancouver.bcai.net) monthly meetups. This repository contains verbatim transcripts, analytical recaps, and machine-readable indexes from 20+ monthly gatherings of Vancouver's AI community.

## What's Inside

| Content | Description |
|---------|-------------|
| `transcripts/` | Full transcripts of meetup presentations, panels, and discussions |
| `recaps/` | Analytical summaries with key themes, quotes, and takeaways |
| `index/events.json` | Per-event metadata: date, venue, speakers, attendance |
| `index/speakers.json` | Speaker index with meetup appearances |
| `index/documents.json` | Per-document metadata for all files |

## Quick Stats

- **20** events indexed (2024, 2025, 2026)
- **37** documents (20 transcripts, 17 recaps)
- **45** speakers referenced
- **~250k words** of community discourse

## Use Cases

This archive is designed for community hacking. Here are some ideas:

### RAG & Search Applications
Build semantic search over meetup history using the JSON indexes and markdown content. Create a "What did Vancouver AI discuss about X?" tool.

### Network Visualization
Use `speakers.json` to map the community graph. Who speaks most? Who appears together? Visualize the social network of Vancouver AI.

### NLP & Topic Modeling
Train topic models on the transcript corpus. Track how AI discourse evolved. Detect emerging themes before they go mainstream.

### Quote Mining
Extract quotable moments for social media, newsletters, or presentations. The recaps already highlight key quotes—programmatically extract more.

### Training Data
Use the transcripts as training data for fine-tuning models on AI domain vocabulary, Vancouver tech context, or conversational AI.

### Community Bots
Build Discord/Slack bots that can answer questions about past meetups, recommend relevant sessions, or surface historical context.

## Data Format

All markdown files include **YAML frontmatter** with structured metadata:

```yaml
---
title: "Vancouver AI Community Meetup #22 - Full Transcript"
date: 2025-10-29
meetup_number: 22
type: transcript
venue: "HR MacMillan Space Centre (Planetarium), Vancouver, BC"
speakers: ["Kris Krüg", "Kevin Friel", "Matthew Schwartzman", ...]
attendance: 250
tags: ["meetup", "transcript", "vancouver-ai"]
---
```

CSV versions of all indexes are also available.

## Cultural Protocols

This archive documents a community that begins each gathering with indigenous ceremony. When working with this content:

1. **Respect**: Indigenous ceremony content should be treated with cultural sensitivity
2. **Attribution**: Credit indigenous speakers by name and nation when referencing their words
3. **Context**: Don't extract ceremonial content out of its original context
4. **Consultation**: For substantial use of indigenous content, consider reaching out to the community

These are community norms reflecting our values—not legal requirements.

## Getting Started

```bash
# Clone the archive
git clone https://github.com/bc-ai-ecosystem/vancouver-ai.git
cd vancouver-ai

# Explore the data
ls transcripts/
cat index/events.json | jq '.'
cat index/speakers.json | jq '.[0:5]'

# Find all mentions of a topic
grep -r "Claude" transcripts/
grep -r "open source" recaps/
```

## Attribution

This content is licensed under [CC-BY-4.0](LICENSE). When using, please attribute:

> Vancouver AI Community Meetup Archive
> https://github.com/bc-ai-ecosystem/vancouver-ai
> Licensed under CC-BY-4.0

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for details on:
- Reporting errors in transcripts
- Suggesting improvements to the archive
- Cultural protocols for indigenous content

**Note**: This is a read-only archive. Content is published from the BC + AI Ecosystem knowledge base after each monthly meetup.

## Community Links

- **Community Portal**: [vancouver.bcai.net](https://vancouver.bcai.net)
- **BC + AI Ecosystem**: [bcai.net](https://bcai.net)
- **Monthly Meetups**: Last Tuesday of each month at the Planetarium

## Maintainer Info

This archive is auto-generated from the BC + AI Ecosystem knowledge base.

```bash
# From the kk-ai-ecosystem repo
python3 scripts/content-scripts/publish-meetup-archive.py \
  --target-repo "/path/to/vancouver-ai" \
  --push
```

---

*Generated: 2026-02-17*

**Built with love by the Vancouver AI community. Hack freely.**
