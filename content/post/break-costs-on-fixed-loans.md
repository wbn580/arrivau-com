---
title: "How break costs on a fixed loan are actually calculated"
slug: "break-costs-on-fixed-loans"
date: 2026-04-12T18:37:35+10:00
description: "The formula lenders use is publicly disclosed but rarely explained. We walk through a $600k, 3-year example step by step."
categories: ["Home Loans"]
tags: ["fixed rate", "break cost"]
author: "Mitchell Harding"
featured_image: "https://images.unsplash.com/photo-1560520653-9e0e4c89eb11?w=1400&q=80&auto=format&fit=crop"
draft: false
---

<!-- R2_IMAGE: break-costs-fixed-loan -->
<figure class="article-image">
  <img
    src="https://img.ulec.com.cn/edu/break-costs-fixed-loan-1777885613.webp"
    alt="How break costs on a fixed loan are actually calculated"
    width="940"
    height="551"
    loading="lazy"
    decoding="async"
    sizes="(max-width: 768px) 100vw, 750px"
  />
</figure>
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ImageObject",
  "contentUrl": "https://img.ulec.com.cn/edu/break-costs-fixed-loan-1777885613.webp",
  "name": "How break costs on a fixed loan are actually calculated",
  "description": "How break costs on a fixed loan are actually calculated — 配图来源：R2自有图库",
  "width": "940",
  "height": "551",
  "license": "https://creativecommons.org/licenses/publicdomain/",
  "acquireLicensePage": "https://img.ulec.com.cn/about"
}
</script>
When you repay or refinance a fixed-rate loan before the fixed period ends, the lender charges a break cost. The calculation method is publicly disclosed in every fixed-rate contract, but most borrowers never read it.

## The underlying principle

When you fixed your rate, the lender went to the wholesale market and fixed its own funding at the same term. If you break early and rates have fallen, the lender has to sell its swap position at a loss. The break cost recovers that loss.

Crucially, if rates have risen since you fixed, the break cost can be zero or even negative - the lender's swap position is in profit. In practice lenders rarely rebate positive break costs; they just waive them.

## A worked example

Suppose you fixed $600,000 for 3 years at 5.50% on 1 July 2024. Two years in, on 1 July 2026, you want to refinance. Remaining fixed term: 1 year. Current 1-year bank bill swap rate (BBSW): 3.80%.

The break cost formula is:

**Break cost = Loan balance × (Original swap rate - Current swap rate) × Remaining term**

Rough numbers:

- Loan balance: ~$575,000 (reduced over 2 years of P&I repayments)
- Original 3-year swap when you fixed: ~4.00%
- Current 1-year swap: 3.80%
- Remaining term: 1 year

Break cost ≈ $575,000 × (4.00% - 3.80%) × 1 = **$1,150**

If rates had fallen further, say the current 1-year swap was 2.80%:

Break cost ≈ $575,000 × (4.00% - 2.80%) × 1 = **$6,900**

And in a dramatic drop, 1.80%:

Break cost ≈ $575,000 × (4.00% - 1.80%) × 1 = **$12,650**

The asymmetry is real: small rate moves cost hundreds; large moves cost thousands.

## Refinements the actual formula includes

Real lender formulas refine this with:

- **NPV discounting** - each year's lost margin is discounted to present value
- **Lender's margin, not swap rate** - some lenders use their internal cost of funds
- **Administration fee** - a flat $250-$400 on top of the calculation

Most lenders will give you a break-cost quote on request. It's valid for 48 hours.

## When breaking still makes sense

Three cases:

1. **The savings from refinancing outweigh the break cost.** Rare - usually only true if the break cost is under $2,000 and the new rate is 100+ bps sharper for a long term.
2. **You need to sell.** Selling a fixed-rate property with 2 years to go - you pay the break cost because you have to.
3. **You're converting owner-occupier to investment.** Sometimes the tax deductibility of a higher-rate investment loan outweighs the break cost on the lower-rate owner-occupier fixed.

## What never makes sense

Breaking a fixed loan that has less than 6 months remaining, or breaking to fix at a longer term when swap rates have fallen further than the new fixed offering reflects.
