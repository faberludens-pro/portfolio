```yaml
title: "Website Navigation Redesign — Enterprise Web Services Platform"
year: 2023
domain: Web Hosting / SaaS
duration: 3 months (April–June 2023)
primary_role: Principal UX Researcher
secondary_roles:
  - Information Architect
  - UX Designer (Prototype)
  - UX Strategist
methods:
  - Desk research and competitive benchmarking
  - User interviews (n=8, including 3 pilots)
  - Card sorting (n=25, including 3 pilots)
  - Prototype design (wireframes + interactive Figma)
  - Moderated usability testing (n=18, including 6 pilots)
impact: Research defined and validated a full navigation redesign — 4 groupings, mega menu, updated labeling — that was independently confirmed by a second team, then shipped to production ~2 years later
```

# Enterprise Web Services Platform — Navigation Redesign From First Principles

A web services platform wasn't converting. I answered **5 specific research questions** about naming, groupings, overview pages, menu type, and conversion focus — then designed and validated an interactive prototype. The design sat unimplemented for nearly two years, was independently confirmed correct by a second team, and finally shipped to production in mid-2025.

| | |
|---|---|
| **4 research methods** across 3 months | **5 research questions** fully answered |
| **22 card-sort participants** | **18 prototype validation participants** |
| Prototype rated **median 4/5** vs. live competitors | Design independently validated by second team 3 months after delivery |
| **~2 years later** — shipped to production | Website implemented as designed |

---

## 1. Context

An enterprise web services platform — offering website builders, domains, hosting, email, and marketing services for small and medium businesses — was struggling to convert website visitors. Over half of visitors who came to purchase did so; but a significant share left without buying, with confusion over the product offering as the leading cause. Users needed the platform to help them identify the right package.

The platform's global navigation had grown organically: inconsistently labeled, structured around internal product categories rather than visitor mental models, and not optimized for converting first-time visitors. The marketing team assigned me to find out what was wrong — and propose a fix.

**The brief assumption:** adding more context and fewer options to the navigation would deliver a clearer, more focused purchase experience.

**Business goals:** improve conversion rate, reduce decision paralysis, provide clearer pricing pathways.

**Constraints:** cross-functional impact (AEM, storefront, PMM, analytics, creative, SEO teams) — any navigation change required coordination across at least 6 teams.

---

## 2. My Role

**Primary: Principal UX Researcher**
I owned the full project: scoped the research plan, selected methods, ran all sessions, synthesized findings across methods, and framed the answers to all five research questions. I then translated findings directly into a prototype rather than handing off to a separate design team.

**Secondary roles:**
- **Information Architect**: Designed the new navigation structure from scratch — main menu, secondary menus, page content hierarchy, and footer — based on card sort results and mental models surfaced in interviews.
- **UX Designer (Prototype)**: Built interactive Figma wireframes validating the proposed IA before any engineering investment.
- **UX Strategist**: Applied Fitts' Law to the menu-type recommendation; identified conversion touchpoints (inline pricing tables) from behavioral patterns in usability testing; advised on SEO channel strategy for navigation items.

---

## 3. Method

**Desk research (baseline)**
Reviewed existing internal documentation: slide decks, Q1 listening posts (survey data from ~1,000+ visitors), FullStory homepage heatmaps and click maps, and two prior navigation studies (2020 and 2021). Conducted a content inventory of the full site and mapped the current IA using Octopus.do. Benchmarked navigation patterns across 5 competitors: GoDaddy, Wix, Squarespace, Square, and IONOS — analyzing menu types, groupings, labeling conventions, and pricing page placement.

**User interviews (n=8 total, 3 pilot + 5 validated)**
Explored how prospective visitors mentally categorized the platform's products and services, what terms they used, and where current terminology created confusion. Participants evaluated the platform alongside 2 competitors (Wix, GoDaddy, or Shopify) in a counterbalanced order to minimize bias. Recruited across 4 profiles: starting SMB, established SMB upgrading, side business, and business-idea seeker. Sessions ran via UserTesting with screen sharing.

**Card sorting (n=25 total, 3 pilot + 22 validated)**
Tested which groupings made structural sense to target users, using 40 items representing all navigation content. Ran via Maze. Produced four top-level categories validated as the clearest organizing structure across the full product range.

**Prototype design**
Translated research findings into an interactive Figma prototype covering the main navigation, secondary menus with contextual descriptions for each item, and page-level content outlines for the Home, Business, eCommerce, and Pricing pages. This was not a handed-off wireframe — I designed it to be testable by real users in moderated sessions.

**Moderated usability testing (n=18 total, 6 pilot + 12 final)**
Validated the prototype against the live platform and two competitors. Participants were assigned to find whatever they were looking for across 3–4 websites in sequence, then rated the prototype's navigation relative to the other sites on a 1–5 scale (Much Worse to Much Better). Sessions ran via UserTesting.

**Timeline:** April 28 – June 2023 (brief to validated prototype in ~2 months)

---

## 4. Analysis and Insights

**Finding 1 — Naming: Title-style labels omitted the descriptive terms users searched for.**
The platform's navigation relied on labels that were structurally ambiguous ("Expert Services," "QuickStart," "Overview"). Visitors with lower web-technology familiarity couldn't locate what they were looking for. The label "Templates" was the clearest example: the site used "Custom Designs," but users universally called them "templates" — and some participants couldn't tell whether the showcased designs were templates or websites built for previous clients. SEO also emerged as a constraint: navigation label decisions required coordination with the marketing team to serve both user clarity and search indexing.

**Finding 2 — Groupings: Visitors navigate by profile, not by product category.**
Both "explorers" (browsing broadly) and "seekers" (looking for known terms) oriented naturally to the same four categories: **Business** (establishing online presence), **eCommerce** (building online stores), **Products** (specific feature additions), and **Pricing** (consistently sought after an initial page scan). The current structure organized by product line (Websites, Marketing, Domains, Hosting, Security, Email) didn't map to how visitors described their own needs.

**Finding 3 — Overview pages: Visitors use them as entry points, not as intermediate steps.**
Participants clicked "Overview" far more often than any other submenu item on first visits. They wanted a single page that showed everything offered in a category — not a brief introduction before drilling into sub-pages. The recommendation: consolidate each category into a single long-form page with anchor-based secondary navigation, presenting features, pricing, and a CTA in one flow. This eliminates the need for standalone Overview items and reduces total nav options.

**Finding 4 — Menu type: Mega menu, not dropdown.**
Given the volume of items per category, a mega menu was the right choice. Fitts' Law analysis supported this: larger click targets per item (especially important for mobile/touch), higher visual contrast to signal interactive areas, and spatial grouping to reduce scan time. The current implementation also failed to communicate location — no active states, no breadcrumbs — which made it easy to get disoriented between pages.

**Finding 5 — Conversion: Pricing needs to appear inline, not only as a nav destination.**
Once visitors found interesting content in a category, they expected to be able to act on it immediately. Pricing tables at the bottom of Business and eCommerce pages were well-received in validation. Pricing was the single most consistently sought destination after an initial site scan, confirming it should be prominent in primary navigation *and* inline on category pages.

**Additional findings (outside the 5 research questions):**
- Most participants had never heard of the platform; brand recognition for Wix, GoDaddy, and Shopify was significantly higher
- Many visitors abandoned when blocked by a paywall before seeing enough of the product — "I'd leave once there's no free trial"
- The current IA was too horizontal and shallow — a full IA redesign was needed, not just a menu relabel
- Cart expiration and the mandatory domain-selection step before checkout were significant friction points

---

## 5. Deliverables and Outcomes

**Deliverables:**
- Research report answering all 5 research questions with supporting evidence
- Annotated content inventory and current IA map
- Competitive analysis across 5 sites
- New navigation structure: main menu, secondary menus with contextual item descriptions, footer reorganization
- Interactive Figma prototype ([wireframes + prototype](https://www.figma.com/proto/gpaXnUx6U0waJSlV8eLzMM/[redacted]-Streamlined-Menu-Navigation?page-id=207%3A8418&node-id=207-9764&scaling=scale-down-width&starting-point-node-id=207%3A9764&hide-ui=1))
- Validation test report with participant quotes and improvement backlog

**Validation results:**
- Prototype rated **median 4/5** (Much Better) and **mean 3.22/5** vs. the live platform, Wix, and GoDaddy
- Representative user quotes:
  - *"I found the e-commerce option quick, and at the bottom was the pricing! On the same page, which I enjoyed. Very clean UI and zen user experience. Less clutter and easier to digest."*
  - *"This has all I look for: email, website templates, sales, scheduling. This is very good and offers all I need."*
  - *"Nothing really stood out — it is very clear and concise. I do like that instead of sentences describing products, it went with bullet points. Much easier to digest."*
  - *"Nothing. Near perfect. Maybe more support chat visible. I feel this was the best experience. I did not have to explore 3 different pages to paint a picture of how it would work or cost."*

**Organizational impact:**
The research was presented to the marketing team, who thanked the team and moved on. No immediate implementation followed. Three months later, the same team commissioned a second, independent team to run the same project. That team's conclusion: the original research was correct and the proposed direction was right. The marketing team then acted on the findings.

Approximately **2 years after the original delivery**, the redesigned website — built to the navigation architecture I had proposed — went live. The implementation was confirmed by direct observation. The platform subsequently changed its go-to-market strategy and the website was taken down, but the design had shipped and performed.

A/B testing was not implemented during the study period; no pre/post conversion metrics are available. The impact evidence is: validated prototype scores, independent team confirmation, and eventual production implementation.

---

## 6. Recommendations and Next Steps

Top recommendations delivered (in order of navigation hierarchy importance):

1. **Fix the label language first** — four correct groupings with wrong labels will still fail; user-recognized terms are the prerequisite for everything else
2. **Restructure primary nav** into four validated groupings: Business, eCommerce, Products, Pricing
3. **Adopt the mega menu** — item volume alone justifies it; Fitts' Law benefits on mobile are a secondary win
4. **Replace Overview pages with long-form category pages** — anchor-based secondary nav (domain search, expert services, builder, products, pricing) within the page
5. **Remove Resources, Blog, and Case Studies from primary nav** — footer placement serves SEO without competing for navigation attention
6. **Surface pricing tables inline on category pages** — visitors expect to act from within the category, not only from the Pricing nav item
7. **Prioritize template discovery** — add search and industry filters; start the purchase flow from the template, not from a domain search

Follow-up research recommended:
- Quantitative A/B test of the new navigation structure vs. the current to validate conversion impact
- First-click test with zero-exposure participants to validate label choices independently of card-sort results
- Post-launch click-heatmap analysis to confirm the four-category groupings hold under real-world traffic patterns

---

## 7. Reflection

**What worked:** The four-method sequence was well-designed for the questions at hand. Desk research and interviews established the conceptual baseline before asking participants to evaluate specific structures — which made the card sort more valid and the usability testing more diagnostic. Participants weren't being asked to evaluate a structure with no mental model for it; they'd already expressed how they thought about the platform's products.

Translating the research directly into a prototype — rather than writing a research report and waiting for a design handoff — was the right call. The prototype let us test whether the proposed IA actually worked in practice, not just whether users endorsed it in the abstract. The validation results showed it did.

The Fitts' Law analysis was a useful bridge between qualitative user preferences and a quantitative design rationale. Recommending a mega menu based on "users liked it" would have been a weaker argument than grounding the recommendation in target-size and touch-accuracy principles.

**Challenges:** The marketing team expected a different output — possibly a visual redesign rather than a research-grounded navigation architecture. When the findings were presented, the reaction was polite but non-committal. This was a misalignment in expectations, not in research quality — which the independent team's validation confirmed three months later.

No long-term A/B testing was implemented during the study period. Without pre/post conversion data, the quantitative business case for the recommendation had to rest on the prototype validation scores and the independent confirmation.

**What I'd do differently:** Invest more upfront effort in stakeholder alignment — clarify what "success" looks like for the receiving team before the first research session. The study answered every question in the brief, but the brief may not have fully captured what the stakeholders needed to feel confident enough to act. Stronger expectation-setting at the kick-off might have accelerated the path to implementation.

---

## Prototype Screens

**Home page** — 4-category primary navigation (Business, eCommerce, Products, Pricing) with domain search bar:

![Prototype home page](assets/web-platform-navigation-redesign-research-2023/prototype-homepage.png)

**Products mega menu** — each item with name and contextual description, organized across 6 product categories:

![Products mega menu open](assets/web-platform-navigation-redesign-research-2023/prototype-products-menu.png)

**Business page** — profile-based landing with secondary anchor navigation (Features, Scheduling, Marketing, Analytics, Support, Templates, Plans):

![Business page with secondary anchor nav](assets/web-platform-navigation-redesign-research-2023/prototype-business.png)

**Pricing page** — comparison table inline, directly accessible from primary nav:

![Pricing comparison page](assets/web-platform-navigation-redesign-research-2023/prototype-pricing.png)

[▶ Interactive prototype](https://www.figma.com/proto/gpaXnUx6U0waJSlV8eLzMM/[redacted]-Streamlined-Menu-Navigation?page-id=207%3A8418&node-id=207-9764&scaling=scale-down-width&starting-point-node-id=207%3A9764&hide-ui=1)
