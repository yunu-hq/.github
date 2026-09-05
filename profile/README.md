<div align="center">

# YUNU

### AI-native platforms for enterprise intelligence, media, and intelligent digital experiences.

**YUNU LTDA** is a Brazilian technology company designing and building software platforms where artificial intelligence is part of the operating architecture, not an accessory added afterward.

We combine **AI engineering, domain-driven design, distributed systems, automation, and platform architecture** to build products for complex real-world environments and long-term evolution.

[Website](https://yunu.com.br) · [Engineering HQ](https://github.com/yunu-hq/Yunu)

</div>

---

## Ecosystem

YUNU is organized around four architectural areas:

```text
YUNU
├── PLATFORM
├── CORPORATE
├── ENTERPRISE
│   ├── CATALOG INTELLIGENCE
│   ├── YUNU.COMMERCE
│   └── YUNU.PHARMA
└── MEDIA
    ├── YUNU.NEWS
    ├── YUNU.FLOW
    └── shared media intelligence capabilities
```

`YUNU.MEDIA` is the umbrella for YUNU's consumer media products. The public products are **YUNU.NEWS** and **YUNU.FLOW**.

---

## Products and capabilities

### YUNU.COMMERCE

**AI-native commerce and catalog intelligence.**

A platform focused on catalog intelligence, taxonomy resolution, enrichment, semantic understanding, data quality, product and SKU proposal workflows, and intelligent integration across commerce ecosystems.

**Stage:** Active private development. The existing Commerce codebase is planned to be adopted into the YUNU engineering monorepo under `enterprise/commerce/` through an explicit migration and compatibility process.

### YUNU.PHARMA

**AI-native pharmaceutical catalog and data intelligence.**

A specialized enterprise vertical for pharmaceutical product classification, taxonomy normalization, regulatory metadata, attribute enrichment, semantic resolution, and enterprise integration.

**Stage:** Architecture and product definition / available for enterprise project development.

### CATALOG INTELLIGENCE

**Industry-neutral catalog intelligence capability.**

A future shared enterprise core for taxonomy, classification, attribute, segment, resolution, enrichment, and catalog quality capabilities proven first through real product usage.

It is not treated as a speculative universal core. Extraction happens only after the reusable boundary is validated through Commerce and future enterprise consumers such as Pharma.

### YUNU.NEWS

**AI-native real-time news intelligence and Live News Canvas.**

Designed around real-time source ingestion, event detection, story clustering, provenance, factual and claim extraction, cross-source synthesis, personalization, realtime updates, and social discussion.

YUNU.NEWS is intended to make conflicting perspectives and source attribution explicit while keeping important global stories continuously visible and evolving as new evidence appears.

**Stage:** Product, domain, architecture, and documentation definition. NEWS starts natively inside the YUNU engineering monorepo.

### YUNU.FLOW

**AI-native creator and social platform.**

A short-form creator experience built around video publishing and AI-assisted creation, intelligent content understanding, personalized feeds, discovery, follows, reactions, comments, realtime interaction, moderation, creator growth, campaigns, advertising, and monetization.

**Stage:** Architecture and product definition.

### CORPORATE WEBSITE

The YUNU institutional website is maintained inside the engineering monorepo under `corporate/website/` and deployed independently to Azure Static Web Apps.

**Stage:** Live and independently deployable.

---

## Shared platform

The YUNU Platform provides technical capabilities that products may consume without sharing product domain models:

- Foundation
- AI abstractions and runtime
- Contracts
- Identity
- Messaging
- Observability
- Runtime capabilities

Shared technical capabilities remain product-neutral. Product domain logic stays inside its owning bounded context.

---

## Engineering model

YUNU is evolving toward a **monorepo with independently owned products, bounded contexts, solution views, CI/CD pipelines, and deployment lifecycles**.

We use:

- **Domain-Driven Design** for business domains and bounded contexts
- **Clean Architecture** for inward dependency direction
- **Hexagonal Architecture** for ports and adapters
- **CQRS** where command/query separation provides real value
- **Domain Events** inside bounded contexts
- **Integration Events** across boundaries
- **Automated unit, integration, contract, architecture, and end-to-end testing**
- **Path-filtered CI/CD** so each product builds and deploys independently
- **Documentation and architecture before implementation** for new domains

Shared capabilities are extracted only after proven reuse. We share capabilities deliberately, never product domain by accident.

---

## Current engineering direction

```text
YUNU.COMMERCE  → active implementation + planned monorepo adoption
YUNU.NEWS      → architecture/documentation now, implementation follows
YUNU.FLOW      → architecture/product definition
YUNU.PHARMA    → enterprise vertical definition
CATALOG INTEL. → future extraction from proven enterprise behavior
PLATFORM       → shared technical foundation
CORPORATE      → live institutional systems
```

---

## Areas of focus

**Artificial Intelligence** · **Distributed Systems** · **Domain Engineering** · **Catalog Intelligence** · **Commerce Intelligence** · **Pharmaceutical Intelligence** · **News Intelligence** · **Creator Platforms** · **Media Intelligence** · **Platform Architecture**

YUNU explores systems where AI, domain logic, software architecture, and product operations evolve as one coherent engineering ecosystem.

---

<div align="center">

**YUNU LTDA**  
Brazil 🇧🇷  
[yunu.com.br](https://yunu.com.br)

</div>
