# Getnet (getnet)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Getnet is a leading merchant acquirer in Latin America and a payments subsidiary of Banco Santander, operating across Brazil, Argentina, Chile, Colombia, Mexico, Uruguay, Spain, and Portugal. Getnet is the region's second-largest acquirer by transaction volume and powers card processing, alternative payment methods, gateway, anti-fraud, tokenization, installments, marketplaces, and POS for over a million merchants. The API ecosystem is consolidating under the global Getnet Docs portal (docs.globalgetnet.com) with a Single Entry Point (SEP) Regional API alongside Web Checkout, Marketplace, Payment Link, Chargeback, Onboarding, in-store terminal integrations, and an emerging Agentic Commerce / MCP AI Toolkit surface. The Brazilian developer hub at developers.getnet.com.br is being migrated to the unified global portal.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/getnet/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Payments, Acquirer, Brazil, LATAM, Santander, E-Commerce, In-Store Payments, POS, Pix, Boleto, Cards, 3DS, Tokenization, Marketplace, Split Payments, Payment Link, Web Checkout, Onboarding, Chargeback, Webhooks, OAuth 2.0, Agentic Commerce, MCP

## APIs

### Getnet Regional API (Single Entry Point)

Getnet's core REST API and Single Entry Point (SEP) for direct payment integration across Argentina, Brazil, Chile, Colombia, Mexico, Portugal, Spain, and Uruguay. Includes single-step and pre-authorization card flows, 3D Secure, refund, cancel, query, recurring, one-click, installments (Parcelado Emissor / Parcelado Lojista), Pix, Bizum, digital wallets, and local APMs.

- **Human URL:** https://docs.globalgetnet.com/en/products/online-payments/regional-api
- **API Reference:** https://docs.globalgetnet.com/en/products/online-payments/regional-api/swagger

### Getnet Web Checkout

Plug-and-play hosted payment surface in three modes (embedded iframe, lightbox pop-up, redirect) that reduces PCI scope. Supports card, debit, Pix, and Boleto in Brazil plus cards and local methods across AR, CL, MX, UY.

- **Human URL:** https://docs.globalgetnet.com/en/products/online-payments/web-checkout
- **API Reference:** https://docs.globalgetnet.com/en/products/online-payments/web-checkout/swagger

### Getnet Marketplace API

Payments for multi-seller platforms: sub-seller onboarding, card capture (Visa, Mastercard, Elo, Amex, Hipercard), programmable splits with commission rules, receivables management, daily CIP settlement file transmission, plus a dedicated Marketplace Capture API for transactional split flows.

- **Human URL:** https://docs.globalgetnet.com/en/products/online-payments/marketplace-api
- **API Reference:** https://developers.getnet.com.br/products-docs/i59203rhmt1cann6m5nl73i5/swagger

### Getnet Payment Link API (BR)

Programmatically generate shareable payment links so Brazilian merchants can sell without a website or virtual store, distributing checkout via WhatsApp, email, SMS, and social channels.

- **Human URL:** https://docs.globalgetnet.com/en/products/online-payments/payment-link-api-br
- **API Reference:** https://docs.globalgetnet.com/en/products/online-payments/payment-link-api-br/swagger

### Getnet Onboarding API (BR)

100%-online self-accreditation API for new Getnet Brasil merchants. Covers offer showcase, establishment registration and qualification, and order management.

- **Human URL:** https://docs.globalgetnet.com/en/products/business-operations/onboarding-api-br
- **API Reference (homologacao):** https://api-homologacao.getnet.com.br/api-doc/

### Getnet Chargeback API

Dispute management API for listing, viewing, contesting, accepting, and documenting chargebacks. OAuth 2.0 Bearer tokens (1-hour TTL) with merchant, platform, and auditor roles. Integrated for AR, CL, MX.

- **Human URL:** https://docs.globalgetnet.com/en/products/business-operations/chargeback

### Getnet Merchant Reporting API

Standardized cross-country reports that simplify settlement and capture reconciliation across Getnet markets.

- **Human URL:** https://docs.globalgetnet.com/en/products/business-operations/global-merchant-reports

### In-Store Payments (App2App, Host-to-Host, Integrated POS, Cloud-to-Cloud)

Terminal-integration models covering inter-app handoff, host-to-host PDV/ERP connectivity, full POS-driven flows, and cloud-mediated remote control of Get Smart and SuperGet terminals.

- **App2App:** https://docs.globalgetnet.com/en/products/in-store-payments/app2app-integration
- **Host-to-Host:** https://docs.globalgetnet.com/en/products/in-store-payments/host-to-host
- **Integrated POS:** https://docs.globalgetnet.com/en/products/in-store-payments/integrated-pos
- **Cloud-to-Cloud:** https://docs.globalgetnet.com/en/products/in-store-payments/cloud-to-cloud

### Getnet Agentic Commerce and MCP AI Toolkit

Payment surface for autonomous AI agents and an MCP toolkit that lets ChatGPT, Claude, and Gemini quote, charge, refund, and inspect transactions through curated MCP tools.

- **Agentic Commerce:** https://docs.globalgetnet.com/en/products/agentic-commerce/agentic-commerce
- **MCP AI Toolkit:** https://docs.globalgetnet.com/en/products/agentic-commerce/mcp-ai-toolkit

### Supporting APIs

- **OAuth 2.0 Token API:** https://docs.globalgetnet.com/en/products/sap-immediate-delivery/getnet-oauth2-token-api
- **Idempotency API (Plataforma Digital):** https://developers.getnet.com.br/products-docs/bopkivddldlkc88xfa9anqcd/swagger
- **Canais Digitais API:** https://developers.getnet.com.br/products-docs/vp6zrskhqougabjn7o1axagi/swagger
- **SAP Immediate Delivery:** https://docs.globalgetnet.com/en/products/sap-immediate-delivery/wl-entrega-imediata
- **White Label Merchant Ops:** https://docs.globalgetnet.com/en/products/white-label/paper-rolls
- **Get Smart App2App (Spain):** https://docs.globalgetnet.com/en/products/local-processor-spain/get-smart-app2app

## Plugins and SDKs

- **Getnet for Magento 2 (Adobe Commerce):** https://github.com/Getnet-Brasil/payment-magento
- **Split Example for Magento:** https://github.com/Getnet-Brasil/split-example-magento
- **Sub-Seller Magento Module:** https://github.com/Getnet-Brasil/sub-seller-magento
- **Android SDK Test App:** https://github.com/Getnet-Brasil/app-test-sdk-android
- **WooCommerce, VTEX, Nubemshop plugins:** https://docs.globalgetnet.com/en/products/online-payments/plugins

## Portals and Support

- **Brazilian Site:** https://site.getnet.com.br
- **Global Site:** https://www.getnetworld.com
- **Global Docs:** https://docs.globalgetnet.com/en
- **Brazilian Developer Portal (legacy, being migrated):** https://developers.getnet.com.br
- **FAQ:** https://site.getnet.com.br/duvidas/
- **Pricing / Taxas:** https://site.getnet.com.br/taxas/
- **Sign Up (Ecommerce):** https://site.getnet.com.br/ecommerce/
- **Sandbox (Homologacao):** https://api-homologacao.getnet.com.br/api-doc/
- **GitHub:** https://github.com/Getnet-Brasil
- **PagoNxt (parent):** https://github.com/pagonxt

## Review

See [review.yml](review.yml) for the API Evangelist review.
