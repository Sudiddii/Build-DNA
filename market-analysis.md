# Market Analysis Frameworks

Load when building Section 2 (Market Analysis) of the Build Brief.

---

## TAM / SAM / SOM — Bottom-Up Method

Never use top-down TAM ("the global fitness market is $100B") — it's meaningless for early-stage decisions. Use bottom-up instead.

**Bottom-up formula:**
```
TAM = [# of people with this problem] × [average annual spend on this problem]
SAM = TAM × [% reachable given your geography, language, distribution]
SOM = SAM × [% you can realistically capture in year 1–2]
```

**Example (meal planning app for shift workers):**
```
TAM: 50M shift workers in US/UK/AU × $120/year on meal planning = $6B [estimate]
SAM: English-speaking, smartphone-owning shift workers with disposable income ≈ 8M × $120 = $960M [estimate]
SOM: Realistic year 1 target = 5,000 paying users × $8/month = $480K ARR [estimate]
```

Always flag estimates. Never present a number as fact unless you have a source.

---

## Why Now — Three Forces Framework

Every good "Why Now" has at least two of these three forces:

**1. Behavioral shift**
Something changed in how people live, work, or spend. Examples:
- Remote work normalized async communication (→ async tools market)
- TikTok trained a generation to expect short-form video (→ short-form content tools)
- COVID made people comfortable ordering groceries online (→ delivery infrastructure)

**2. Technology shift**
Something became newly possible, newly cheap, or newly accessible. Examples:
- LLMs made text generation cheap (→ AI writing tools)
- Shopify made e-commerce setup trivial (→ niche product stores)
- Stripe made payment processing accessible to solo developers (→ micro-SaaS)

**3. Market shift**
An incumbent failed, a regulation changed, or a demographic shifted. Examples:
- Netflix raised prices → opening for cheaper alternatives
- GDPR created compliance obligations → compliance tooling market
- Millennials hitting home-buying age → first-time homebuyer tools

---

## Market Sizing by Business Type

### SaaS / Software
- Find industry reports (Statista, IBISWorld, G2 market reports)
- Count competitors' customer counts if public
- Search LinkedIn for job titles in the target persona — proxy for market size
- Check App Store/Play Store download estimates for comparable apps

### Physical Products / E-commerce
- Check Amazon Best Sellers rank — use tools like Jungle Scout or manual estimation
- Search Etsy for similar products, count reviews × estimated conversion rate
- Look at import/export data (US Census, Alibaba trade data)
- Check Google Trends for search volume as demand proxy

### Services / Consulting
- Count the number of businesses in the target category (Google Maps, LinkedIn, industry associations)
- Estimate average spend per client × number of reachable clients

### Creator / Content
- Count subscribers/followers of comparable creators
- Check Patreon/Substack for comparable paid membership numbers
- Look at course marketplace (Udemy, Gumroad) sales estimates for comparable topics

---

## Competitive Analysis Depth Guide

**Direct competitors:** Same product, same customer, same job to be done.
**Indirect competitors:** Different product, same customer, same job to be done.
**Substitute competitors:** Different product, different approach, same outcome.

Always include at least one substitute — it reveals what the customer does *today* without your product.

**Where to find competitors:**
- Google: "[problem] tool / app / service / alternative"
- ProductHunt: search the category
- G2 / Capterra: software categories
- Etsy / Amazon: physical products
- Substack / Gumroad: content products
- App Store search

**What to capture for each competitor:**
- Price point
- Target customer (who do they serve best?)
- Core strength (what do they do better than anyone?)
- Core weakness (what do reviewers complain about most?)
- Distribution (how do they acquire customers?)
- Funding / size (are they well-resourced or scrappy?)
