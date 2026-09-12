# Nicholas Hernandez

I build things that let AI systems do real work: MCP servers, agent workflows, and
production software with an LLM somewhere in the loop that has to be right.

Founder of **Civic-Chain**, a govtech company working on municipal financial
transparency. Most of what is public here came out of that, or out of trying to
automate a part of it.

## AI tooling

**[geo-inspector-mcp](https://github.com/Bigsupe55/geo-inspector-mcp)** · TypeScript
An MCP server that inspects a website's AI-search readiness. Four tools, every parser a
pure function with fixture tests, all HTTP through one capped and redirect-limited
helper. Published on npm and listed in the official
[MCP Registry](https://registry.modelcontextprotocol.io).

**[ai-visibility-audit](https://github.com/Bigsupe55/ai-visibility-audit)** · Claude Code plugin
The workflow layer over those tools: a skill that orchestrates them into a scored,
client-ready report. The scoring is a bundled zero-dependency script, so the same site
state always produces the same number. Claude writes the words and never invents the
math. That split is the whole design.

**[procurement-forecast-bot](https://github.com/Bigsupe55/procurement-forecast-bot)** · TypeScript
Finds planned federal procurement before any RFP exists, scores it 0-100, and emails a
ranked digest. Four public agency sources, three of them undocumented and
reverse-engineered off the agencies' own front ends. An optional LLM pass judges fit
against a cached capability profile, with a hard per-run item cap as a cost ceiling. It
ships switched off, because a model judging against an unreviewed profile is worse than
no model at all.

## Other public work

**[maine-political-map](https://github.com/Bigsupe55/maine-political-map)** · JavaScript + Leaflet
Every Maine political district and 529 town polygons, with 207 officials joined to the
districts they hold. Vanilla JS, no build step. Towns are shaded by median household
income across classes cut at the data's own quantiles, because even intervals put 80% of
Maine in one bucket.

**[The Response Ledger](https://github.com/Bigsupe55/Representative-Response-Board)** · JavaScript + Supabase
A public record of outreach to government offices and how long each takes to respond.
One static page, a free database, and a scheduled job that doubles as its own keepalive.
Built entirely on free tiers, which is what drove every architectural decision in it.

## Before this

Seven years in compliance and operations: violation investigations across 1,000+
residential units, vendor negotiation, and staff training on Florida statute. Six Sigma
Yellow Belt, Scrum Fundamentals, and a Florida LCAM license. Bilingual English/Spanish.

That background is why the software I build tends to be about process, records, and
money that someone has to account for.

---

Open to work on AI agent systems and AI product. Reach me at
[nghernandez55@gmail.com](mailto:nghernandez55@gmail.com).
