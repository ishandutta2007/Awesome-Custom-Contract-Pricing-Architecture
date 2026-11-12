# Awesome Custom Contract & Pricing Architecture [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of SaaS platforms, enterprise CPQ solutions, open-source pricing engines, and quote-to-cash (Q2C) developer frameworks for complex contract modeling, usage-based billing, and revenue orchestration.

---

## Sector Overview & Market Dynamics

The global **Configure, Price, Quote (CPQ) and Revenue Lifecycle Management** software market is valued at approximately **$3.8 billion to $4.1 billion** (growing at a CAGR of ~16% toward an estimated $12+ billion by the early 2030s). Market concentration is **moderately concentrated at the high-end enterprise layer**—anchored by dominant ecosystem leaders like Salesforce, SAP, Oracle, and Conga—yet remains **fragmented across mid-market, vertical manufacturing, and consumption-billing segments** where dozens of agile SaaS point-solutions and emerging developer tools compete.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [Enterprise & SaaS Platforms](#enterprisessaas-platforms)
- [Open-Source Projects & Pricing Engines](#open-source-projects--pricing-engines)
- [Architectural Patterns: Composing Modern Pricing Engines](#architectural-patterns-composing-modern-pricing-engines)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Enterprise & SaaS Platforms

The table below catalogs premier SaaS CPQ, contract pricing, and quote-to-revenue platforms. The table is sorted descending by **Company Scale** (Valuation / Market Capitalization / Annual Revenue).

| Product | Company Scale (Valuation / Revenue) | Description | Starting Pricing | Free Tier / Trial Limits |
|:---|:---|:---|:---|:---|
| **[Salesforce Revenue Cloud (CPQ)](https://www.salesforce.com/products/cpq/)** | **~$300B+ MCap** (~$38B ARR) | Enterprise quote-to-cash engine built natively on Salesforce CRM. Supports product bundling, multi-level approvals, contract amendments, and volume pricing. | **$75 /user/month** (CPQ Standard list; CPQ Plus at $150 /user/month) | **No direct public free tier**; 30-to-90-day sandbox via developer edition & Salesforce Trailhead environments |
| **[Chargebee](https://www.chargebee.com/)** | **~$3.5B Valuation** (~$200M–$300M ARR) | Subscription management and billing system with dedicated CPQ capabilities for SaaS deal terms, multi-year ramped agreements, and sales quotes. | **$599 /month** (Performance plan billed annually; Starter tier at 0% take-rate on first $250k) | **14-day full feature free trial**; CPQ Lite is free forever for the first 50 quotes for billing customers |
| **[Zuora](https://www.zuora.com/)** | **~$1.7B Valuation** (~$450M ARR) | Enterprise order-to-cash and subscription monetization platform featuring Zuora CPQ and multi-attribute rating engines for recurring and consumption contracts. | **~$6,250 /month** (Entry enterprise packages start at ~$75,000/year) | **No self-serve free trial**; private sandbox / PoC scoped exclusively via guided sales consultation |
| **[PROS Smart CPQ](https://www.pros.com/)** | **~$1.4B Valuation** (~$350M ARR) | AI-powered dynamic pricing and CPQ platform designed for high-scale B2B omnichannel distribution and complex bill-of-materials (BOM) configurations. | **$60 /user/month** (Starting Essentials tier via partner app marketplaces; enterprise custom-quoted) | **No self-serve free trial**; guided product demonstration required |
| **[Conga CPQ](https://www.conga.com/)** | **~$1.25B Valuation** (~$250M–$380M ARR) | Comprehensive contract lifecycle management (CLM) and enterprise CPQ platform (incorporating Apttus technology) tailored for large Salesforce ecosystems. | **$85 /user/month** (Software Advice verified starting benchmark) | **30-day free trial** available for select Conga Composer add-on tools; core CPQ requires sales demo |
| **[DealHub](https://dealhub.io/)** | **~$600M–$800M Valuation** (~$60M+ ARR) | Agentic quote-to-revenue suite unifying CPQ, CLM, subscription management, and digital sales rooms with headless quoting API support. | **$19–$65 /user/month** (Starting benchmark for modular components; full CPQ suite custom-quoted) | **No self-serve free trial**; personalized demo and live proof-of-concept upon sales engagement |
| **[Vendavo](https://www.vendavo.com/)** | **~$400M–$500M Est. Value** (~$90M–$95M ARR) | Commercial excellence and B2B pricing optimization platform offering CPQ, dynamic deal guidance, and profit-margin guardrails. | **$65 /user/month** (Basic starting tier benchmark per Capterra directory) | **No self-serve free trial**; interactive sandbox and sandbox walk-through via vendor sales team |
| **[Pricefx](https://www.pricefx.com/)** | **~$350M–$450M Est. Value** (~$60M–$90M ARR) | Cloud-native pricing software covering price setting, price optimization, rebate management, and CPQ calculation engines. | **~$4,166 /month** (~$50,000/year minimum platform contract baseline; practitioner certifications from $450) | **No self-serve free trial**; custom enterprise PoC and evaluation scoped with solutions architects |
| **[Zilliant](https://www.zilliant.com/)** | **~$250M–$350M Est. Value** (~$35M–$40M ARR) | AI-driven pricing intelligence, price optimization, and CPQ software engineered for wholesale distribution and manufacturing enterprises. | **$500 /month** (Minimum entry license threshold; typical implementations scale upward) | **No free trial**; live custom demo with historical data benchmark modeling available on request |
| **[Experlogix](https://www.experlogix.com/)** | **~$100M–$150M Est. Value** (~$20M–$30M ARR) | Visual and rule-based CPQ platform deeply integrated into Microsoft Dynamics 365, NetSuite, and Salesforce environments. | **$100 /user/month** (Third-party implementation baseline benchmark) | **30-day free trial** (available for Experlogix Document Automation; core CPQ engine requires guided demo) |

---

## Open-Source Projects & Pricing Engines

For organizations building modular, developer-first, or vendor-neutral quote-to-cash infrastructure, the following open-source projects provide quotation interfaces, consumption metering backends, billing engines, and product-configuration rules. 

The table is sorted descending by **GitHub Stars**.

| Repository / Project | Stars | Focus Area | Description |
|:---|:---|:---|:---|
| **[getlago/lago](https://github.com/getlago/lago)** | [![Stars](https://img.shields.io/github/stars/getlago/lago?style=social&color=white)](https://github.com/getlago/lago/stargazers) | Metering & Usage-Based Pricing Engine | Open-source metering and consumption-based billing API. Handles complex hybrid pricing, progressive tiers, allowances, and custom enterprise contract metrics. |
| **[invoiceninja/invoiceninja](https://github.com/invoiceninja/invoiceninja)** | [![Stars](https://img.shields.io/github/stars/invoiceninja/invoiceninja?style=social&color=white)](https://github.com/invoiceninja/invoiceninja/stargazers) | Invoicing & Quote Generation | Full-featured open-source invoicing and quotation platform supporting custom quotes, payment gateways, multi-currency pricing, and client approval portals. |
| **[polarsource/polar](https://github.com/polarsource/polar)** | [![Stars](https://img.shields.io/github/stars/polarsource/polar?style=social&color=white)](https://github.com/polarsource/polar/stargazers) | Developer Monetization & Subscriptions | Open-source monetization and billing platform tailored for developer ecosystems, usage entitlements, dynamic pricing, and digital checkout flows. |
| **[killbill/killbill](https://github.com/killbill/killbill)** | [![Stars](https://img.shields.io/github/stars/killbill/killbill?style=social&color=white)](https://github.com/killbill/killbill/stargazers) | Subscription Billing & Catalog Engine | Battle-tested, enterprise open-source subscription billing platform with sophisticated catalog definition, recurring billing logic, and contract entitlement plugins. |
| **[open-mercato/open-mercato](https://github.com/open-mercato/open-mercato)** | [![Stars](https://img.shields.io/github/stars/open-mercato/open-mercato?style=social&color=white)](https://github.com/open-mercato/open-mercato/stargazers) | B2B Commerce & CPQ Engine | Modular open-source commerce platform featuring a native CPQ module with JSON product definitions, deterministic formula evaluation, and BOM configuration. |
| **[pledra/odoo-product-configurator](https://github.com/pledra/odoo-product-configurator)** | [![Stars](https://img.shields.io/github/stars/pledra/odoo-product-configurator?style=social&color=white)](https://github.com/pledra/odoo-product-configurator/stargazers) | Dynamic Product Configuration | Open-source module suite for Odoo providing multi-attribute dynamic product configuration, price rule computations, and quote generation. |
| **[webXcerpt/openCPQ](https://github.com/webXcerpt/openCPQ)** | [![Stars](https://img.shields.io/github/stars/webXcerpt/openCPQ?style=social&color=white)](https://github.com/webXcerpt/openCPQ/stargazers) | In-Browser CPQ & Configurator | MIT-licensed browser-based product-configuration library using JavaScript/React to compute pricing models and configuration logic client-side. |

---

## Architectural Patterns: Composing Modern Pricing Engines

Purpose-built open-source CPQ suites are rare; modern engineering teams increasingly compose custom contract pricing architectures using decoupled layers:

```
┌────────────────────────────────────────────────────────────────────────┐
│                      1. Quoting & Deal Desk UI                        │
│   (SwiftCPQ / Invoice Ninja / OpenCPQ / Custom Next.js + React Apps)   │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                   2. Pricing & Rule Evaluation Engine                  │
│       (Open Mercato / JSON Logic / Cel / Custom Microservices)         │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│               3. Metering, Catalog & Subscription Layer                │
│             (Lago / Kill Bill / Polar / Stripe / Chargebee)            │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│             4. Enterprise ERP, General Ledger & Billing Sync           │
│                    (NetSuite / SAP / QuickBooks / Xero)                │
└────────────────────────────────────────────────────────────────────────┘
```

1. **Quoting Front-End**: Handles quote line item editing, visual approval thresholds, proposal document rendering (PDF), and digital e-signatures.
2. **Pricing Engine Microservice**: Evaluates multi-dimensional price books, customer-specific negotiated discount matrices, minimum spend commitments, and co-termination terms.
3. **Metering & Billing Backend**: Ingests high-frequency consumption events, meters API calls/compute, and binds usage to contract schedules.
4. **General Ledger & ERP Integration**: Pushes recognized revenue, tax computations, and accounts receivable entries into financial ledgers.

---

## How to Contribute

Contributions, corrections, and additions are welcome! Please follow these guidelines:

1. Fork this repository.
2. Ensure new SaaS listings provide **exact starting prices**, **free tier/trial details**, and **valuation/revenue estimates**.
3. For open-source repositories, ensure they are actively maintained, include a social badge linking to `/stargazers`, and fit the CPQ/Pricing domain.
4. Open a Pull Request with a concise summary of changes.

---

## Disclaimer

- This repository is a community-curated research resource and does not constitute financial, legal, or procurement advice.
- Vendor list pricing, enterprise minimums, and acquisition valuations are compiled from public regulatory filings, SaaS intelligence indexes (Vendr, Latka, Tracxn), and marketplace listings. Always verify terms directly with vendor sales representatives prior to procurement.
