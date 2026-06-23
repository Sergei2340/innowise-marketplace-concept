# Innowise Marketplace — Concept

A presentation-ready vision for a new **Marketplace** section on [innowise.com](https://innowise.com): a storefront where clients **buy and ship ready-made solutions** instead of commissioning custom development from scratch.

**▶ Live prototype:** https://sergei2340.github.io/innowise-marketplace-concept/

> This is an interactive concept prototype (a single self-contained web page), not a production system. It exists to make the idea tangible and to align stakeholders.

---

## The idea in one line

Turn the engineering work Innowise already does for clients into **productized, licensable solutions** — templates, modules and SDKs sold through a normal e-commerce flow — and use that storefront as a **new top-of-funnel for the services business**.

## Why it matters

Today Innowise sells **custom development**: every engagement starts as a bespoke project and a sales conversation. That's high-value but slow to enter and hard to scale.

The Marketplace adds a second, complementary motion:

- **Self-serve revenue** — buyers purchase a license, download the source, and go live in days. No SOW, no kickoff.
- **A wider funnel** — a €1.5k template puts Innowise's brand and code inside a prospect's product *before* any sales call.
- **A bridge back to services** — every product nudges the buyer toward Innowise engineers for integration, customization and white-labeling. Productized sales feed the core consulting pipeline rather than competing with it.

That bridge is the strategic core of the concept — see **Consultation hooks** below.

## What it is

- A new **Marketplace** entry in the site header, opening a storefront of **120+ ready-to-deploy products** across Innowise's real domains: **AI & ML, Healthcare, FinTech, Data, Web, VR / AR, IoT, Security**.
- Each product is a **battle-tested solution you license and ship** — sold with a standard catalog → cart → checkout → confirmation flow.
- Royalty-free licensing model: **one-time payment, unlimited commercial use, instant download, 12 months of updates** — no per-seat or royalty fees.

## Consultation hooks (the services bridge)

At three points in the journey the storefront offers to connect the buyer with the Innowise team:

1. **Product page** — an "integration help available" band.
2. **Cart** — an optional *free integration consultation* upsell.
3. **Checkout** — an **Integration support** tier step: *Self-serve (free) · Guided (€490) · Full white-label (custom quote)*.

This converts a one-off product purchase into a potential services engagement.

## The flagship example — VR Meditation App Template

The prototype builds out one product end-to-end to show the intended depth: a **white-label Unity VR meditation template** for Meta Quest 3/2/Pro and Pico 4 (€1,499). Its product page demonstrates the full template: overview, features, how-it-works, tech specs, what's included, integration help, and FAQ — plus a multi-image environment slider and the cart/checkout flow.

The other 11 catalog cards (ShopForge, FleetTrace, MediSync, LedgerHawk, and more) illustrate the breadth of the storefront.

## Design

Built to look like a real Innowise page, not a generic template:

- Authentic brand tokens — **Sora** (display) / **Karla** (body) fonts, brand red `#C63031`, and the site's **fully-sharp (0px) corners**.
- Case-study-style cinematic product imagery, matched to the look of [innowise.com/cases](https://innowise.com/cases/).
- Layout, header and type scale mirror the live site.

## How it's built

- A **single, fully self-contained HTML page** — all fonts and images are inlined (base64), with **no external dependencies, no backend, and no build step**. It runs from any static host or even a downloaded file.
- A lightweight hash-router drives the views (`#/marketplace`, `#/product`, `#/checkout`, `#/confirmation`).
- Hosted here on **GitHub Pages**; also available as a Claude artifact for internal review.

---

*Concept prototype — for discussion and alignment. Not a shipping product.*
