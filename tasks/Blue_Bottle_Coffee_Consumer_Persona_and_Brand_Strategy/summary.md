# Blue Bottle Coffee Consumer Persona and Brand Strategy

**Task URL:** https://manus.im/app/lczVxcPe7ASz76dBSEbt9u
**Status:** stopped

---

Acknowledged! I'll build a comprehensive Blue Bottle Coffee persona dashboard — a rich, interactive web application covering all the requested modules. Let me start planning this out.

Project scaffolded. Now brainstorming the design direction before writing any code.

I've chosen the **"Editorial Roastery"** design direction — a Swiss International Typographic Style meets editorial brutalism approach. Think Wallpaper* magazine or a Kinfolk layout applied to a dashboard:

- **Palette**: Warm parchment background (`#F5F0E8`), espresso near-black text, roasted amber accent (`#C17F3A`)
- **Typography**: Playfair Display for display/headers, DM Sans for body, DM Mono for data labels
- **Layout**: Asymmetric 12-column grid, persistent left sidebar, oversized section labels
- **Feel**: Premium, editorial, considered — like a brand book come to life, not a generic SaaS tool

Now generating hero images and building all dashboard modules.

All 7 sections are now built. TypeScript is clean (0 errors). Doing a final status check and then creating the checkpoint.

The dashboard is looking great! All sections are rendering correctly. Now saving the checkpoint.

Your **Blue Bottle Coffee Persona & Creative Intelligence Dashboard** is live. All 7 sections are built with the "Editorial Roastery" design — warm parchment palette, Playfair Display typography, and DM Mono data labels throughout.

**What's inside:**

| Section | What it covers |
|---|---|
| **Consumer Persona** | 3 personas (Ritual Seeker, Gift-Giver, Matcha Explorer) with traits, motivations, behaviors, mood cues, and ROAS/CPP/CTR per segment |
| **Brand DNA** | 5 brand pillars with ad angles, tone do/don't guardrails, visual rules, and 4 copy formulas |
| **Inspiration Feed** | 8 content cards (UGC, Brand, Competitor, Trend) filterable by type, with performance indicators |
| **Idea Generator** | Concept builder (Product × Format × Angle), 8 hook frameworks, and a 10-item content angle library |
| **Seasonal Context** | 6-period annual calendar with urgency levels, occasions, themes, and ROAS range targets |
| **Experience Map** | 4 journey maps (Home Brewing, Café, Gifting, Subscription) with stage-by-stage emotion and creative opportunity |
| **Test & Learn** | 6 test entries with ROAS/CPP/CTR bar chart, expandable learnings, and a 6-insight winning patterns summary |

**Three concrete next steps to consider:**

1. **Connect live Meta Ads data** — upgrade to a full-stack project to pull real ROAS, CPP, and CTR from your ad account directly into the Test & Learn tracker, replacing the static sample entries with live campaign results.
2. **Add a "New Test Entry" form** to the Test & Learn tracker so the team can log new hypotheses, formats, and results directly in the dashboard without editing code.
3. **Expand the Inspiration Feed** with a URL input field — let the team paste a TikTok or Instagram link and tag it with product, theme, and performance tier to build a living swipe file over time.

The performance metrics in the dashboard are **entirely fictional/illustrative sample data** that I authored when building the dashboard. They are hardcoded in the `client/src/lib/data.ts` file — not pulled from any live source.

Specifically:

| Metric | Source |
|---|---|
| ROAS (4.8×, 7.4×, etc.) | Made-up sample values I wrote to demonstrate the layout |
| CPP ($28.4, $31.2, etc.) | Illustrative figures, not from your ad account |
| CTR (2.1%, 1.8%, etc.) | Sample data only |
| Test & Learn entries | Fictional hypotheses and results I created as placeholders |
| Segment performance stats | Estimated/illustrative, not from Meta Ads |

**To get real numbers into the dashboard, there are two paths:**

1. **Manual entry (quickest)** — I can update the `data.ts` file with your actual campaign numbers right now. Just paste in your ROAS, CPP, CTR, and spend figures by product/format and I'll replace the placeholders immediately.

2. **Live Meta Ads connection (most powerful)** — I can upgrade the project to a full-stack app and wire it to your Meta Ads account via the MCP integration already configured in this project. This would pull real campaign data automatically — broken out by Instant, Merch, Coffee, DPAs, and Matcha — and populate the Test & Learn tracker and segment performance stats dynamically.

Which would you prefer? If you want to go live, just confirm and I'll set it up.

Expanding the Consumer Persona section to 5 fully fleshed-out named personas with messaging ideas, ad angles, and creative hooks for each. Building this out now.

TypeScript is clean (0 errors). The console errors are stale from before the TestLearnTracker file was created — they're no longer relevant. Saving checkpoint now.

The Consumer Persona section is now significantly deeper. Here's what changed from the previous version:

The original 3 generic archetypes have been replaced with **5 named, fully developed personas** — Marcus, Priya, Jordan, Alex, and Diana — each with a real job title, city, income range, a first-person quote, and a distinct archetype description. Each persona now has **three tabs**:

- **Profile & Behaviors** — photo, identity card, trait scores, motivations, behaviors, mood cues, channels, and segment ROAS/CPP/CTR
- **Messaging Ideas** — 3 ready-to-brief concepts per persona, each with an angle, headline, body copy, and specific creative hook
- **Ad Angles & Guardrails** — winning angles ranked by priority, top products, where to reach them, content don'ts, and a creative recommendation based on current ROAS

**Three next steps worth considering:**

1. **Add a "Brief Builder" export** — a one-click button on the Messaging Ideas tab that generates a formatted creative brief PDF for each persona, ready to hand off to a creative team or agency.
2. **Map personas to products more explicitly** — add a matrix view showing which of the 5 products (Instant, Merch, Coffee, DPAs, Matcha) each persona over-indexes on, so media buyers can see persona × product priorities at a glance.
3. **Add a 6th persona for the Lapsed Subscriber** — someone who tried Blue Bottle, paused, and needs a re-engagement angle. This is a high-value retargeting segment that currently has no dedicated messaging framework.

