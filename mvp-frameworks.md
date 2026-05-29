# MVP Frameworks

Load when building Section 8 (MVP Build Plan) of the Build Brief.

---

## The Three MVP Types

### 1. Fake Door MVP (validate before building)
Build nothing. Create a landing page that describes the product as if it exists. Drive traffic. Measure signups, pre-orders, or clicks on a "Buy Now" button that leads to a waitlist.

**When to use:** You're not sure if people want this at all.
**Success signal:** 50+ email signups or 10+ pre-orders in 2 weeks without paid ads.
**Tools:** Carrd, Framer, Notion + Tally form, Gumroad pre-order.

### 2. Concierge MVP (do it manually first)
Deliver the value by hand — no software, no automation. You are the product. This reveals what customers actually need before you build anything.

**When to use:** You have customers but aren't sure what to build for them.
**Example:** Before building a scheduling app, manually schedule meetings for 5 clients via email/DM.
**Success signal:** Customers pay for the manual service. If they won't pay for the manual version, they won't pay for the automated version.

### 3. Vertical Slice MVP (build the thinnest working version)
Build one complete user journey end-to-end — not all features, but one job done fully. One user, one use case, all the way through.

**When to use:** You've validated demand and need to build something shippable.
**Rule:** If a feature doesn't serve the core use case, it doesn't exist in v1.
**Anti-pattern:** Building 10 features at 20% completion instead of 1 feature at 100%.

---

## No-Code Stack by Product Type

### SaaS / Web App
| Component | Recommended | Alternative |
|---|---|---|
| Frontend | Webflow | Framer, Carrd (landing only) |
| Backend / Logic | Airtable + Zapier | Make (Integromat), n8n |
| Database | Airtable | Notion, Supabase |
| Auth | Memberstack | Outseta |
| Payments | Stripe | Gumroad, Lemon Squeezy |
| Hosting | Webflow | Netlify, Vercel |

### E-commerce / Physical Products
| Component | Recommended | Alternative |
|---|---|---|
| Store | Shopify | WooCommerce, Gumroad |
| Payments | Shopify Payments / Stripe | PayPal |
| Inventory | Shopify | Airtable |
| Shipping | ShipBob | Printful (print-on-demand) |
| Email | Klaviyo | Mailchimp |

### Content / Creator Business
| Component | Recommended | Alternative |
|---|---|---|
| Newsletter | Beehiiv | Substack, ConvertKit |
| Course | Gumroad | Teachable, Podia |
| Community | Circle | Discord, Slack |
| Paid content | Patreon | Substack |

### Service / Consulting
| Component | Recommended | Alternative |
|---|---|---|
| Booking | Calendly | Cal.com |
| Proposals | Notion | Google Docs |
| Contracts | Docusign | HelloSign |
| Invoicing | Stripe | Wave (free) |
| CRM | Notion | HubSpot (free tier) |

---

## Vibe-Coding Stack (AI-assisted development)

For founders who can code a little or are learning:

| Component | Recommended | Why |
|---|---|---|
| IDE | Cursor | Best AI-assisted coding experience |
| Prototyping | Replit | Deploy instantly, no setup |
| Frontend | Next.js + Tailwind | Claude knows it extremely well |
| Backend | Supabase | Auth + database + storage in one |
| Payments | Stripe | Best docs, Claude can implement it |
| Deployment | Vercel | One command deploy |

**Prompt to get started in Cursor:**
> "Build a [product description] for [target user]. Start with the most important feature: [core use case]. Use Next.js, Tailwind, and Supabase. Keep it simple — no feature beyond what's needed for this one use case."

---

## Kill Criteria by Phase

Every phase needs a pre-set kill threshold. Set it before hope distorts judgment.

| Phase | Question | Kill if... |
|---|---|---|
| Fake Door | Do people want this? | <50 signups in 2 weeks (organic) |
| Concierge | Will they pay for it? | <3 paying customers in 4 weeks |
| MVP | Do they come back? | <30% week-2 retention |
| v1 | Does it grow? | No organic referrals after 50 customers |

---

## MVP Scope Decision Framework

For each proposed feature, ask:
1. Does this serve the core use case? → If no, cut it.
2. Would a customer pay without this feature? → If yes, cut it.
3. Can this be done manually instead of built? → If yes, do it manually first.
4. Will this take more than 1 week to build? → If yes, simplify or cut it.

The goal of v1 is to prove ONE thing: that people will pay for the core value. Everything else is distraction.
