# Graph Report - .  (2026-06-11)

## Corpus Check
- Corpus is ~4,093 words - fits in a single context window. You may not need a graph.

## Summary
- 8 nodes · 5 edges · 3 communities (1 shown, 2 thin omitted)
- Extraction: 80% EXTRACTED · 20% INFERRED · 0% AMBIGUOUS · INFERRED: 1 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Package Manifest|Package Manifest]]
- [[_COMMUNITY_Landing Page Entry and CI|Landing Page Entry and CI]]
- [[_COMMUNITY_Vercel Routing Config|Vercel Routing Config]]

## God Nodes (most connected - your core abstractions)
1. `private` - 1 edges
2. `rewrites` - 1 edges
3. `Truest Sites Web Development Service` - 1 edges
4. `CI Check Workflow` - 1 edges

## Surprising Connections (you probably didn't know these)
- `CI Check Workflow` --references--> `Truest Sites Web Development Service`  [INFERRED]
  .github/workflows/ci.yml → public/index.html

## Import Cycles
- None detected.

## Communities (3 total, 2 thin omitted)

### Community 0 - "Package Manifest"
Cohesion: 0.50
Nodes (3): name, private, version

## Knowledge Gaps
- **6 isolated node(s):** `name`, `version`, `private`, `rewrites`, `Truest Sites Web Development Service` (+1 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `name`, `version`, `private` to the rest of the system?**
  _6 weakly-connected nodes found - possible documentation gaps or missing edges._