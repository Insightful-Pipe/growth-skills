# InsightfulPipe Growth & App Marketing Skills

**25 free Claude skills for growth and app marketing: growth loops, North Star metric, trial-to-paid, paywalls, lead magnets, app store optimization, Apple Ads and app attribution.**

Most of these skills also work from reports you export and paste in, with no account needed. Skills that need numbers read them live from your accounts when the InsightfulPipe MCP is connected.

Part of the free [InsightfulPipe marketing skills library](https://github.com/Insightful-Pipe/marketing-skills). Skills with a **Page** link have a page with a sample run at [insightfulpipe.com](https://insightfulpipe.com/marketing-claude-skills); newer ones get theirs soon.

## Install

### Claude Code

```
/plugin marketplace add Insightful-Pipe/growth-skills
/plugin install insightfulpipe-growth@insightfulpipe-growth
```

### Any agent: Claude Code, Codex, Cursor and others

```
npx skills add Insightful-Pipe/growth-skills
```

Add `--skill app-attribution-auditor` to install one skill.

### Claude.ai and Claude Desktop

Download a skill's ZIP from its page on insightfulpipe.com (the **Page** links below), or zip its folder from `skills/` if it has no page yet, then in Claude open **Customize > Skills**, choose **+ Create skill > Upload a skill** and pick the ZIP. Skills need code execution turned on.

## Skills (25)

| Skill | What it does | |
|---|---|---|
| [App Install (User Acquisition) Campaign Planner](skills/app-install-ua-planner/) | Plans paid user acquisition for a live mobile app across Apple Ads, Google App campaigns, Meta, TikTok, Snapchat and AppLovin, setting max CPI, day 7 ROAS targets and a… |  |
| [App Install Attribution Auditor](skills/app-attribution-auditor/) | Audits mobile app install attribution across AppsFlyer, Adjust, Branch or Singular, SKAdNetwork conversion values, Google Ads, Meta, TikTok and GA4. |  |
| [App Marketing Plan](skills/app-marketing-plan/) | Writes a mobile app marketing plan from pre-launch to scale, covering ASO, Google Play pre-registration, App Store pre-order, soft launch, paid UA, creators and… |  |
| [App Rating Prompt Planner](skills/app-rating-prompt-planner/) | Plans when an iOS or Android app should show the App Store review request or Google Play in-app review card, checks the prompt against store rules and compares reviews… |  |
| [App Store Conversion Analyst](skills/app-store-conversion-analyst/) | Analyzes App Store Connect and Google Play Console store listing exports to find why visitors do not install, splitting conversion by source, mix shift from real drops… |  |
| [App Store Listing Localizer](skills/app-store-localization/) | Localizes App Store and Google Play listings, picking which countries to localize next and finding the keywords each locale searches instead of translating, then writes… |  |
| [App Store Screenshot and Preview Video Brief](skills/app-screenshot-video-brief/) | Writes a designer brief for App Store and Google Play screenshots, captions, app preview video and feature graphic, choosing the first three frames from reviews and… |  |
| [Apple Search Ads Manager](skills/apple-ads-manager/) | Audits and builds Apple Ads (Apple Search Ads) campaigns for an iOS app, covering brand, category, competitor and discovery structure, keyword bids, negatives, search… |  |
| [AppLovin Ads Analyzer](skills/applovin-ads-analyzer/) | Analyzes AppLovin Ads (Axon Ads Manager) campaigns for app installs or web sales, grading CPI, cost per purchase and ROAS by campaign, country and creative set, and… |  |
| [Developer Tool Growth Plan](skills/developer-oss-growth/) | Plans developer marketing and a 90-day growth plan for a dev tool, API or open-source project, tracing docs traffic, GitHub stars and signup cohorts through to paid… |  |
| [Feature Adoption Planner](skills/feature-adoption-planner/) | Plans feature adoption campaigns for existing software users. |  |
| [Growth Experiment Backlog](skills/growth-experiment-backlog/) | Builds a growth experiment backlog from the weakest funnel step in GA4 or pasted numbers, scores ideas with ICE or RICE, drops tests the traffic cannot power, plans a… |  |
| [Growth Loop Designer](skills/growth-loop-designer/) | Designs growth loops (invites, shared outputs, public pages, content, paid reinvestment), measures each loop's output and cycle time from product numbers or GA4, and… |  |
| [In-App Events and Featuring Planner](skills/in-app-events-featuring-planner/) | Plans App Store in-app events, Google Play promotional content and featuring nominations on a dated calendar timed to seasonal demand, with event cards in store limits. |  |
| [Interactive Calculator Builder](skills/interactive-calculator-builder/) | Builds a working ROI, savings, cost or quote calculator as one embeddable HTML file, with the formula checked against worked examples, GA4 events, optional email… |  |
| [Lead Magnet Writer](skills/lead-magnet-writer/) | Writes a finished lead magnet (checklist, fill-in template, one-page guide or email course) with opt-in copy and a delivery email, picking the angle from Search Console… |  |
| [Net Revenue Retention and Expansion Planner](skills/expansion-revenue-planner/) | Calculates SaaS net revenue retention (NRR) and GRR from Stripe or billing exports, scores which paying accounts are ready to upgrade, add seats or buy add-ons, and… |  |
| [North Star Metric Builder](skills/north-star-metric-builder/) | Chooses a North Star metric by testing candidates against your retention and revenue history from GA4, BigQuery or pasted data, then builds 3 to 5 input metrics with… | [Page](https://insightfulpipe.com/marketing-claude-skills/growth/north-star-metric-builder) |
| [Paywall Screen Optimizer](skills/paywall-screen-optimizer/) | Reviews subscription app and SaaS paywall screens by placement, ranks where starts are lost from GA4 or pasted counts, checks App Store and Google Play disclosure… |  |
| [PLG and SaaS Growth Audit](skills/plg-saas-growth-audit/) | Audits a self-serve SaaS funnel from visit to signup, activation, paid, expansion, churn and failed payments, puts an MRR figure on each leak from GA4, Stripe or… |  |
| [Plugin and Integration Marketplace Optimizer](skills/integration-marketplace-listing/) | Audits and rewrites app and plugin listings on the Shopify App Store, Chrome Web Store, WordPress.org and Atlassian Marketplace against field limits and rivals, and… |  |
| [Quiz Funnel Builder](skills/quiz-funnel-builder/) | Builds a quiz funnel (product recommendation quiz, lead gen quiz or scorecard) from real customer groups in Shopify, WooCommerce, Klaviyo or GA4, with every answer path… |  |
| [Store Listing Experiments and Custom Product Pages](skills/store-listing-experiments/) | Plans, sizes and reads App Store product page optimization tests and Google Play store listing experiments, and plans custom product pages and custom store listings for… |  |
| [Trial-to-Paid Conversion Optimizer](skills/trial-to-paid-optimizer/) | Finds why free trial users don't pay from Stripe, Paddle or Chargebee exports, splits trials by activation and source, checks trial emails, length and card rule, and… |  |
| [Web-to-App Funnel Planner](skills/web-to-app-funnel/) | Plans a web2app funnel that sells app subscriptions on the web before install, weighing the store fee saved against drop-off, checking App Store and Google Play rules… |  |

## Live data (optional)

Skills that read account data use the [InsightfulPipe MCP server](https://insightfulpipe.com/mcp-servers) when it's connected. Without it, each skill tells you which exports to paste in and works from those.

## What this plugin runs and sends

The plugin contains skills only: Markdown instructions (`SKILL.md`, `HOW_TO_USE.md`) and sample input and output files. It adds no hooks, commands or MCP servers, runs no code on your machine and sends no data anywhere by itself. When you have the InsightfulPipe MCP connected, Claude uses it to read your accounts, and makes a change only after you confirm it. The `scripts/` and `.github/` folders keep this repository in sync with insightfulpipe.com and are not part of what the plugin does.

## License

MIT. See [LICENSE](LICENSE).
