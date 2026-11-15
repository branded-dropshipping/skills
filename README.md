# Branded Dropshipping Skills

Turn your agent into your ecommerce operator.

15 skills for branded dropshipping, from winning-product research and PDP teardowns to UGC, post-purchase upsells and Meta scaling. Give your agent a competitor store, a product you're considering, raw footage or campaign numbers, and put it to work on the next move.

Find products you can actually source and demonstrate. Pull apart the offer behind an ad. Rebuild a storefront, brief creators, and work through the unit economics before raising spend. The same pack covers what happens after the sale: fulfillment, customer support, payout holds and representment.

[Research](#find-the-product-and-the-angle) · [Store & offers](#build-the-store-and-the-offer) · [Creative & scaling](#make-creative-and-scale-meta) · [Operations](#fulfill-orders-and-keep-the-money-moving) · [Try it](#put-the-skills-to-work)

<br>

## Install

Copy this to your agent:

```text
Install branded dropshipping skills globally for this agent using `npx skills`.
https://github.com/branded-dropshipping/skills
```

<br>

## Find the product and the angle

### [winning-product-research](skills/winning-product-research/SKILL.md)

Hunt through Meta Ad Library, burner feeds, marketplace neighbors and supplier catalogs. Filter for a repeatable demo, an exact supplier match and enough landed margin to test.

```sh
npx skills add branded-dropshipping/skills --skill winning-product-research -g
```

### [reverse-engineer-any-store](skills/reverse-engineer-any-store/SKILL.md)

Follow the ad through the advertorial, PDP and cart. Break down the angle, proof, bundle ladder and subscription defaults, then find what your own offer can do differently.

```sh
npx skills add branded-dropshipping/skills --skill reverse-engineer-any-store -g
```

### [reddit-customer-research](skills/reddit-customer-research/SKILL.md)

Mine Reddit for voice of customer: switching triggers, objections, failed alternatives and repeat purchases. Follow the updates; the first complaint often leaves out the ending.

```sh
npx skills add branded-dropshipping/skills --skill reddit-customer-research -g
```

<br>

## Build the store and the offer

### [clone-any-store](skills/clone-any-store/SKILL.md)

Inspect the DOM, CSS, loaded fonts and public bundles behind a reference store. Rebuild the design system as an editable site ready to deploy, with your catalog.

```sh
npx skills add branded-dropshipping/skills --skill clone-any-store -g
```

### [increase-average-order-value](skills/increase-average-order-value/SKILL.md)

Choose bundles, upsells and downsells that make the main purchase better, faster or easier to use. Compare take rate and contribution per visitor. A higher AOV can still leave less money.

```sh
npx skills add branded-dropshipping/skills --skill increase-average-order-value -g
```

### [checkout-debug](skills/checkout-debug/SKILL.md)

Trace cart-line identity, variant selection, discount stacking, shipping rates and mobile wallets. Reproduce the route from the actual ad-click URL through to the order record.

```sh
npx skills add branded-dropshipping/skills --skill checkout-debug -g
```

### [abandoned-cart-recovery](skills/abandoned-cart-recovery/SKILL.md)

Build email/SMS flows around the objection holding up the order. Work through timing, product blocks, buyer suppression and whether the flow adds sales beyond those already coming back.

```sh
npx skills add branded-dropshipping/skills --skill abandoned-cart-recovery -g
```

<br>

## Make creative and scale Meta

### [ai-ad-factory](skills/ai-ad-factory/SKILL.md)

Turn an angle into a complete static or video ad: buying reason, product demo, proof beats, offer and CTA. Make each proof beat answer the doubt that would stop the sale.

```sh
npx skills add branded-dropshipping/skills --skill ai-ad-factory -g
```

### [ai-ugc-factory](skills/ai-ugc-factory/SKILL.md)

Brief human, AI or hybrid creators with A-roll, B-roll, opening takes and product-handling direction. Fix the delivery, voice or missing demo before spending another round on the edit.

```sh
npx skills add branded-dropshipping/skills --skill ai-ugc-factory -g
```

### [viral-hook-formats](skills/viral-hook-formats/SKILL.md)

Adapt organic hooks into filmable openings. Line up the first frame, spoken line and overlay, then carry the promised payoff into the body.

```sh
npx skills add branded-dropshipping/skills --skill viral-hook-formats -g
```

### [ad-campaign-scaling](skills/ad-campaign-scaling/SKILL.md)

Work through Meta budget raises, cost controls, underdelivery and rollback. Judge the extra spend against the extra contribution while considering conversion lag and cash runway.

```sh
npx skills add branded-dropshipping/skills --skill ad-campaign-scaling -g
```

<br>

## Fulfill orders and keep the money moving

### [sourcing-and-fulfillment](skills/sourcing-and-fulfillment/SKILL.md)

Go from exact-product sourcing and RFQs to sample checks, per-order fulfillment and tracking exceptions. Match the supplier SKU and quantity since a tracking number alone does not show carrier movement.

```sh
npx skills add branded-dropshipping/skills --skill sourcing-and-fulfillment -g
```

### [support-automation](skills/support-automation/SKILL.md)

Build WISMO replies, macros, refund routing and human handoffs around the store’s actual policies. Keep self-service promises aligned with what the warehouse can still change.

```sh
npx skills add branded-dropshipping/skills --skill support-automation -g
```

### [chargeback-fighter](skills/chargeback-fighter/SKILL.md)

Build a representment around the disputed claim, the decisive record and the payment timeline. Reconcile refunds and dispute credits before the same order gets paid back twice.

```sh
npx skills add branded-dropshipping/skills --skill chargeback-fighter -g
```

### [payment-network](skills/payment-network/SKILL.md)

Set up payments or troubleshoot an existing payment stack. Compare effective fees, reserves, settlement timing and eligible Whop Card spending against the cash the store needs next.

```sh
npx skills add branded-dropshipping/skills --skill payment-network -g
```

<br>

## Put the skills to work

### Turn a competitor teardown into your own offer

> Use reverse-engineer-any-store on this competitor URL. Follow the ad into the PDP and cart, break down the bundle ladder and proof, and find an objection they've left unanswered. Then use increase-average-order-value to work out an offer for my product using my landed costs.

You get a teardown tied to an offer decision: what to borrow, what to change, and whether the extra order value leaves enough contribution.

### Turn raw footage into a creative test

> Use ai-ugc-factory to review these clips and identify the missing shots. Use viral-hook-formats to write three openings against one body, then ai-ad-factory to build the selling argument and edit plan. Work with the product claims and footage I've supplied.

You get opening variations, a body with a reason to buy, and a pickup list the creator can film. The comparison tests the opening while keeping the rest of the ad consistent.

### Find where the next dollar should go

> My Meta spend is up but store orders are flat. Use ad-campaign-scaling to compare the extra spend with extra contribution, allowing for conversion lag. If checkout completion has dropped, use checkout-debug to trace the actual buyer route. Tell me what to change first and what would make you reverse the decision.

You get a decision about the next spend level, the fault to investigate if there is one, and a rollback condition grounded in the store's numbers.
