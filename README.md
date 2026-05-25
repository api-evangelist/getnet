# Getnet (getnet)

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
