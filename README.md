# Awesome-Custom-Contract-Pricing-Architecture

# Top Custom Contract & Pricing Architecture Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on CPQ Configuration, Dynamic Pricing Rules & Quote-to-Revenue Orchestration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Custom Contract & Pricing Architecture**. These tools help revenue teams model complex pricing structures—tiered, usage-based, ramped, and multi-year contracts—while enforcing approval workflows and translating negotiated terms into accurate quotes, invoices, and revenue schedules.

**Examples** include Salesforce Revenue Cloud, DealHub, Chargebee, Zuora, Conga, Vendavo, Pricefx, PROS, Zilliant, and Experlogix (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted CPQ, open-source quoting tools, and community-driven pricing engines—ideal for organizations seeking transparent, vendor-neutral pricing logic without per-seat enterprise licensing. Note that purpose-built open-source CPQ is genuinely nascent; the practical path is composing billing platforms with custom pricing logic and lightweight quoting tools.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Salesforce Revenue Cloud (CPQ)](https://www.salesforce.com/)** | Enterprise quote-to-cash platform. **CPQ is priced per seat** (base and Plus tiers); **Billing is priced as a percentage of invoiced volume**. CPQ Plus adds advanced approvals, contract amendments, and order management. Most cost overruns stem from over-scoped CPQ seats rather than platform fees . | CPQ Standard: ~$75/user/month (list); CPQ Plus: ~$150/user/month (list); Billing: percentage of invoiced volume . Negotiated rates often 20–30% below list . | No free tier; demo via sales |
| **[DealHub](https://dealhub.io/)** | Agentic quote-to-revenue platform covering CPQ, CLM, and Billing. Supports multi-dimensional pricebooks, usage-based/tiered/hybrid pricing, ramped quotes, co-terminated expansions, and approval-aware pricing. CRM-agnostic with headless API quoting . | Quote-only (modular: CPQ, CLM, Billing). Vendr data: 15–30% off list for multi-year; 10–20% for annual prepayment . | No free tier; demo via sales |
| **[Chargebee](https://www.chargebee.com/)** | Subscription billing platform with **CPQ Lite** (free for first 50 quotes) and paid CPQ tier for high-velocity sales teams. Supports quoting controls, multi-product quotes, multi-year ramped quotes, and rule-based approval workflows. CPQ available natively or via Salesforce/HubSpot add-ons . | CPQ Lite: **free** (first 50 quotes); paid CPQ tier: quote-only; Billing Performance: ~$7,188/year | **CPQ Lite free** for first 50 quotes (existing Chargebee Billing customers) . No free tier for full CPQ |
| **[Zuora](https://www.zuora.com/)** | Subscription order-to-cash platform with **Zuora CPQ** module for complex product catalogs and pricing structures. Separate module pricing; quote-based and varies by transaction volume. Multi-year commitments yield 10–20% lower pricing; module bundling 15–25% better than separate purchases . | Quote-only (module-based). Vendr benchmark: ~$170,000 typical total cost for mid-market . | No free tier; demo via sales |
| **[Conga CPQ](https://www.conga.com/)** | CLM and CPQ platform within the Conga Revenue Lifecycle suite. Frequently positioned for Salesforce-heavy environments. Implementations can be more complex and costly for larger deployments compared to DealHub . | From **$85/month** (Software Advice listing) . | No free tier; demo via sales |
| **[Vendavo](https://www.vendavo.com/)** | Intelligent CPQ and pricing optimization platform. Capterra lists a **Basic tier starting at $65/month**, though enterprise deployments are typically quote-based . | Basic: **$65/month** (Capterra) . | Free trial available per Capterra; no free version . |
| **[Pricefx](https://www.pricefx.com/)** | Pricing optimization and CPQ platform. Public pricing limited to training programs (e.g., practitioner programs at €390/$450 each); platform licensing is quote-based . | Quote-only (platform); training from ~$450 . | No public free tier; training available separately . |
| **[PROS Smart CPQ](https://www.pros.com/)** | AI-powered configure-price-quote for complex B2B sales. Pricing entirely private-offer based via Microsoft Marketplace; no public list rates . | Quote-only (private offers via Microsoft Marketplace) . | No public free tier; demo via sales . |
| **[Zilliant](https://www.zilliant.com/)** | AI-driven pricing optimization and CPQ. SelectHub indicates pricing starts in the **$500–$1,000 range** (likely per month or per user); custom quote required, no free trial . | **$500–$1,000** (SelectHub estimate); custom quote . | **No free trial** . |
| **[Experlogix](https://www.experlogix.com/)** | CPQ solution for Microsoft Dynamics and Salesforce. Third-party benchmarks indicate **$100–$300/user/month**. Additional costs: CPQ configuration $1K–$5K one-time; CRM/ERP integration $1K–$10K; implementation/training $1K–$5K . | **$100–$300/user/month** (third-party estimate) . | No free tier; demo via sales . |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[SwiftCPQ](https://github.com/topics/configure-price-quote)** | — | **The one actively maintained open-source CPQ tool in this list.** Vendor-agnostic proposal tool positioned as an accessible alternative to proprietary solutions like ConnectWise CPQ, Kaseya Quote Manager, and Scalepad Quoter. Vue-based. Listed under GitHub's `configure-price-quote` topic with a recent April 2026 update . Exact repository URL not confirmed in search results—search GitHub for "SwiftCPQ" to locate it. |
| **[Open Mercato (Product Configurator)](https://github.com/open-mercato/open-mercato)** | [![Stars](https://img.shields.io/github/stars/open-mercato/open-mercato?style=social&color=white)](https://github.com/open-mercato/open-mercato/stargazers) | Open-source commerce platform with a **CPQ (Configure-Price-Quote) module**. Versioned JSON product definitions, deterministic evaluation engine for rules/formulas/BOM quantities, and quote line snapshots for reproducible pricing. Net price only; tax and discount handled by the sales module . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Chargebee CPQ Lite](https://www.chargebee.com/pricing/)** | — | **Not open-source, but the most accessible free CPQ entry point.** Free for first 50 quotes for existing Chargebee Billing customers. Covers quote creation for Sales and immediate amendments for existing customers. Paid CPQ tier adds quoting controls, multi-product quotes, multi-year ramped quotes, and rule-based approvals . Useful as a bridge before committing to enterprise CPQ. |
| **[Kill Bill](https://github.com/killbill/killbill)** | [![Stars](https://img.shields.io/github/stars/killbill/killbill?style=social&color=white)](https://github.com/killbill/killbill/stargazers) | Mature open-source subscription billing platform with **catalog and plan structures** that can model complex pricing (tiered, usage-based, add-ons). Not a CPQ UI, but provides the pricing engine and entitlements layer that a custom quoting front-end could sit on top of. |
| **[Lago](https://github.com/getlago/lago)** | [![Stars](https://img.shields.io/github/stars/getlago/lago?style=social&color=white)](https://github.com/getlago/getlago/stargazers) | Open-source usage-based billing API with metering, pricing plans (tiered, package, percentage), and invoicing. Can serve as the pricing calculation backend for a custom CPQ workflow focused on consumption-based models. |

**Frameworks for building custom systems**: The open-source path to custom contract pricing is **compositional**. **SwiftCPQ** provides a proposal/quoting front-end but its maturity is unverified. **Open Mercato** offers a CPQ module within a broader commerce platform. For the pricing engine itself, **Kill Bill** or **Lago** provide catalog and metering logic that can be paired with a custom approval and quote-generation layer. Expect significant engineering effort—no open-source project ships with enterprise-grade CPQ features like multi-dimensional pricebooks, ramped contracts, and approval matrices out of the box.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Custom pricing architectures govern revenue-critical calculations; errors in pricing logic or approval routing can cause financial loss and customer disputes. Validate all pricing rules against contract terms before production deployment.
- **Pricing transparency varies dramatically in this category.** Vendavo ($65/month) and Conga ($85/month) publish entry points; Experlogix and Zilliant have third-party benchmarks. Salesforce CPQ pricing is complex—per-seat for CPQ, percentage-of-volume for Billing—and **Billing fees compound as revenue grows without any new value delivered** . DealHub, Zuora, PROS, and Pricefx are quote-only. **Open-source CPQ is the weakest category in this entire repository.** SwiftCPQ exists but its maturity and feature depth are unverified; no open-source project rivals Salesforce or DealHub for multi-dimensional pricebooks, ramped quotes, and approval matrices. Chargebee's **CPQ Lite (free for 50 quotes)** is the most accessible way to evaluate CPQ functionality without enterprise commitment .

---

**Made for revenue operations teams, deal desk analysts, pricing managers, and developers building quote-to-cash infrastructure.**  
Let's make custom contract pricing more open, transparent, and accurate.
