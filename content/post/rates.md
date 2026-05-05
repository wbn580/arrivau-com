---
title: "Australian Home Loan Rates — Monthly Comparison"
slug: "rates"
date: 2026-04-22T09:00:00Z
lastmod: 2026-05-05T09:30:00Z
description: "Arrivau's monthly snapshot of advertised variable / 2Y / 3Y / 5Y fixed rates and cash-back offers from 30+ Australian lenders — updated each month from Brokerpedia."
categories: ["Home Loans"]
tags: ["Interest Rates", "Rate Comparison", "Cash-back", "Mortgage Broker"]
author: "Mitchell Harding"
draft: false
---

<!--
  ╔══════════════════════════════════════════════════════════════════╗
  ║  ⚠  利率表同步依赖 — 改完这个文件后必须跑：                      ║
  ║      python3 scripts/sync_ozloan_rates.py                        ║
  ║                                                                  ║
  ║  本文件是 ozloan-cn / ozloan-en 两站 /rates/ 页的上游数据源。    ║
  ║  任何改动（行、利率、Cash-back标记、FAQ、日期、CSS）都要同步。       ║
  ║  同步完要 rebuild + deploy 两个 ozloan 站，否则它们会落后。      ║
  ║  详见 arrivau-static/CLAUDE.md                                   ║
  ╚══════════════════════════════════════════════════════════════════╝
-->

<div class="arv-rates">

<p class="arv-rates-lede">Arrivau 持续跟踪澳大利亚 <strong>30+ 家</strong>主流贷款机构的报价 —— 从四大银行、区域银行、非银贷款机构，到新兴的数字银行。下表为 <strong>2026年5月5日</strong>更新的横向对比（自住 / 本息 / 80% LVR 情景下的广告利率），每一列<strong>最低值</strong>已加粗，带 ✻ 标记的行表示该机构本月提供Cash-back（Cash-back）。</p>

<div class="arv-rates-toolbar">
  <span class="arv-rates-badge">✻ = Cash-back this month</span>
  <span class="arv-rates-badge">All rates shown as % p.a.</span>
</div>

<div class="arv-rates-scroll">
<table class="arv-rates-table">
  <colgroup>
    <col style="width:26%">
    <col style="width:13.5%">
    <col style="width:14.5%">
    <col style="width:14.5%">
    <col style="width:14.5%">
    <col style="width:17%">
  </colgroup>
  <thead>
    <tr>
      <th scope="col">Lender</th>
      <th scope="col">Variable<br><small>Variable</small></th>
      <th scope="col">2Y Fixed<br><small>2Y Fixed</small></th>
      <th scope="col">3Y Fixed<br><small>3Y Fixed</small></th>
      <th scope="col">5Y Fixed<br><small>5Y Fixed</small></th>
      <th scope="col">Cash-back<br><small>Cash-back</small></th>
    </tr>
  </thead>
  <tbody>
    <tr><th scope="row">AMP Bank</th><td>6.24</td><td>7.10</td><td>7.15</td><td>7.39</td><td>—</td></tr>
    <tr><th scope="row">ANZ <span class="arv-rates-cb">✻</span></th><td>7.38</td><td>6.84</td><td>6.99</td><td>6.99</td><td>$3,000</td></tr>
    <tr><th scope="row">Auswide Bank</th><td>5.99</td><td>6.64</td><td>6.69</td><td>7.04</td><td>—</td></tr>
    <tr><th scope="row">Bank of China <span class="arv-rates-cb">✻</span></th><td>6.38</td><td>6.39</td><td>6.79</td><td>6.79</td><td>Special<sup>†</sup></td></tr>
    <tr><th scope="row">Bank of Melbourne</th><td>6.83</td><td>6.79</td><td>6.99</td><td>7.19</td><td>—</td></tr>
    <tr><th scope="row">Bank of Sydney</th><td>5.94</td><td>6.99</td><td>6.99</td><td>—</td><td>—</td></tr>
    <tr><th scope="row">Bank Australia</th><td>5.89</td><td><strong>6.29</strong></td><td><strong>6.39</strong></td><td><strong>6.49</strong></td><td>—</td></tr>
    <tr><th scope="row">BankSA</th><td>6.83</td><td>6.79</td><td>6.99</td><td>7.19</td><td>—</td></tr>
    <tr><th scope="row">Bankwest</th><td>6.54</td><td>7.09</td><td>7.19</td><td>7.29</td><td>—</td></tr>
    <tr><th scope="row">Bendigo Bank</th><td>6.98</td><td>6.94</td><td>6.89</td><td>6.94</td><td>—</td></tr>
    <tr><th scope="row">BOQ</th><td>7.19</td><td>7.09</td><td>7.59</td><td>7.84</td><td>—</td></tr>
    <tr><th scope="row">Commonwealth Bank (CBA)</th><td>6.73</td><td>6.74</td><td>7.04</td><td>7.19</td><td>—</td></tr>
    <tr><th scope="row">Firstmac</th><td>6.84</td><td>7.29</td><td>7.39</td><td>7.79</td><td>—</td></tr>
    <tr><th scope="row">Gateway Bank</th><td>7.04</td><td>7.14</td><td>7.09</td><td>7.69</td><td>—</td></tr>
    <tr><th scope="row">Great Southern Bank</th><td>6.69</td><td>6.90</td><td>6.95</td><td>—</td><td>—</td></tr>
    <tr><th scope="row">Heritage Bank</th><td>5.84</td><td>6.34</td><td><strong>6.39</strong></td><td>6.54</td><td>—</td></tr>
    <tr><th scope="row">HSBC</th><td>6.19</td><td>6.39</td><td>6.44</td><td>—</td><td>—</td></tr>
    <tr><th scope="row">ING</th><td>6.29</td><td><strong>6.29</strong></td><td>6.44</td><td>6.64</td><td>—</td></tr>
    <tr><th scope="row">Macquarie Bank</th><td>6.29</td><td>6.99</td><td>7.04</td><td>7.19</td><td>—</td></tr>
    <tr><th scope="row">ME Bank</th><td>7.62</td><td>6.79</td><td>6.59</td><td>7.19</td><td>—</td></tr>
    <tr><th scope="row">MyState Bank</th><td>6.24</td><td>7.19</td><td>7.24</td><td>7.69</td><td>—</td></tr>
    <tr><th scope="row">NAB</th><td>7.21</td><td>6.64</td><td>6.79</td><td>6.79</td><td>—</td></tr>
    <tr><th scope="row">Newcastle Permanent</th><td>5.94</td><td>6.44</td><td>6.49</td><td>6.64</td><td>—</td></tr>
    <tr><th scope="row">Police &amp; Nurses (P&amp;N)</th><td>5.94</td><td>6.54</td><td>6.69</td><td>6.79</td><td>—</td></tr>
    <tr><th scope="row">Qudos Bank</th><td>6.14</td><td>6.54</td><td>6.64</td><td>6.74</td><td>—</td></tr>
    <tr><th scope="row">St. George</th><td>6.83</td><td>6.79</td><td>6.99</td><td>7.19</td><td>—</td></tr>
    <tr><th scope="row">Suncorp Bank</th><td>6.29</td><td>6.69</td><td>6.79</td><td>6.79</td><td>—</td></tr>
    <tr><th scope="row">Teachers Mutual</th><td>6.29</td><td>6.69</td><td>6.79</td><td>6.99</td><td>—</td></tr>
    <tr><th scope="row">ubank</th><td>6.24</td><td>6.59</td><td>6.64</td><td>6.79</td><td>—</td></tr>
    <tr><th scope="row">Virgin Money <span class="arv-rates-cb">✻</span></th><td><strong>5.59</strong></td><td>6.79</td><td>6.59</td><td>7.19</td><td>$4,000</td></tr>
    <tr><th scope="row">Westpac</th><td>6.83</td><td>6.79</td><td>6.99</td><td>7.19</td><td>—</td></tr>
  
</table>
</div>

<p class="arv-rates-footnotes">
<sup>†</sup> Bank of China Discount Plus Home Loans — specific margin is subject to broker-negotiated banker discretion and may vary.<br>
ANZ $3,000 cash-back is for refinance customers only, conditions apply, ask your broker for details. Virgin Money $4,000 cash-back applies to new loans only, LVR &lt; 80%, minimum loan amount $300k.
</p>

<p class="arv-rates-note">本月最低Variable利率：<strong>Virgin Money 5.59%</strong>，其次 <strong>Heritage Bank 5.84%</strong>、<strong>Bank Australia 5.89%</strong>。二年固定端 <strong>ING 与 Bank Australia 并列最低 6.29%</strong>；三年固定端 <strong>Bank Australia 与 Heritage Bank 并列最低 6.39%</strong>；五年固定端最低为 <strong>Bank Australia 6.49%</strong>。现金Cash-back方面 <strong>Virgin Money $4,000、ANZ $3,000</strong> 为本期前列，Bank of China 另提供 Discount Plus 特别折扣（具体幅度以 broker 议价后为准）。实际可批利率会根据您的 <strong>LVR、贷款金额、收入结构、还款方式</strong>以及银行当月的优惠政策而有折扣，很多时候比上表的广告价低 20–40 BPs。</p>

</div>

## How to choose — three common questions

### Variable or fixed?

<p>The RBA cash rate currently sits above the long-run median, with markets pricing cuts into the second half of 2026. If you&rsquo;re likely to <strong>sell, refinance or pay down early within the next 1–2 years</strong>, variable is usually the better call. If your priority is <strong>certainty of monthly repayments</strong> or locking cash flow for the next 2–3 years, consider a pure fixed loan or a <em>split</em> — half fixed, half variable.</p>

<!-- R2_IMAGE:au-realestate-1048211 -->
<figure class="article-hero" itemscope itemtype="https://schema.org/ImageObject">
  <img src="https://img.ulec.com.cn/loan/au-realestate-1048211-2026-1280x853.webp" 
       alt="Australian real estate photo"
       loading="lazy"
       width="1200"
       height="799"
       decoding="async"
       itemprop="contentUrl">
  <figcaption itemprop="caption">图片来源: UNILINK · ulec.com.cn</figcaption>
</figure>
<script type="application/ld+json">{"@context": "https://schema.org", "@type": "ImageObject", "contentUrl": "https://img.ulec.com.cn/loan/au-realestate-1048211-2026-1280x853.webp", "name": "Australian real estate photo", "caption": "Australian real estate photo", "creditText": "UNILINK 优领教育", "creator": {"@type": "Organization", "name": "UNILINK 优领教育", "url": "https://ulec.com.cn"}, "license": "Pixabay License (free commercial use)"}</script>
<!-- /R2_IMAGE -->



### Is the cash-back worth chasing?

<p>A $3,000–$4,000 cash-back looks attractive — until you compare rates. If chasing the rebate costs you 15–20 bps on the rate, a $1M loan pays an extra $1,500–$2,000 interest per year, and the rebate is fully clawed back in 1–2 years. Cash-back is only a real bonus when the <strong>underlying rate is still competitive</strong>.</p>

### Why is my actual rate different from the table?

<p>The table shows banks&rsquo; published <em>advertised</em> rates. Your actual approved rate depends on <strong>LVR</strong> (lower is better), <strong>loan size</strong> (loans above $1M typically unlock extra margin), <strong>owner-occupier vs. investment</strong>, <strong>P&amp;I vs. interest-only</strong>, feature packs like <strong>offset / redraw</strong>, and the <em>banker discretion</em> discount a broker can negotiate. As a licensed MFAA-member mortgage broker, Arrivau compares real approval pricing from 30+ lenders so you can pick the rate + feature mix that actually fits.</p>

<div class="arv-rates-cta">
  <h3>Want to know the rate you&rsquo;d actually qualify for?</h3>
  <p>Fill in the 2-minute assessment and we&rsquo;ll come back within one business day with a 3-lender shortlist tailored to your profile.</p>
  <div class="arv-rates-cta-btns">
    <a class="arv-rates-btn arv-rates-btn--primary"
       href="https://www.mikecrm.com/vlxWlcI"
       target="_blank" rel="nofollow noopener noreferrer">Get a free assessment →</a>
    <a class="arv-rates-btn arv-rates-btn--ghost"
       href="tel:+61451827455">📞 Call +61 451 827 455</a>
  </div>
</div>

<p class="arv-rates-disclaimer">数据来源：<a href="https://www.brokerpedia.com.au/Rate" target="_blank" rel="nofollow noopener noreferrer">Brokerpedia</a> 银行公开报价数据库，Arrivau 于 <strong>2026-05-05</strong> 最后核对。利率与Cash-back政策可能随时变动，以银行正式批准函为准。本页内容为一般信息，不构成个人化财务建议。Arrivau 为持牌 Mortgage Broker，MFAA 会员，ACL / ASIC 合规。</p>

<style>
  .arv-rates{width:100%;}
  .arv-rates-lede{font-size:16px;line-height:1.7;color:#334155;margin:0 0 14px;}
  .arv-rates-toolbar{display:flex;flex-wrap:wrap;gap:8px;margin:0 0 12px;}
  .arv-rates-badge{
    display:inline-block;padding:4px 10px;border-radius:999px;
    background:#fff4e5;color:#b45309;font-size:12px;font-weight:600;
    border:1px solid #fcd9ae;
  }
  .arv-rates-badge:nth-child(2){background:#eef2ff;color:#3730a3;border-color:#c7d2fe;}

  /* Horizontal scroll wrapper: fills the content column */
  .arv-rates-scroll{
    overflow-x:auto;
    -webkit-overflow-scrolling:touch;
    border:1px solid #e5e7eb;
    border-radius:12px;
    box-shadow:0 2px 8px rgba(15,23,42,.04);
    background:#fff;
    width:100%;
  }

  .arv-rates-table{
    width:100%;
    table-layout:fixed;
    border-collapse:separate;
    border-spacing:0;
    font-size:14px;
    min-width:640px;
    margin:0;
  }
  .arv-rates-table thead th{
    position:sticky;top:0;
    background:#ED6F0C;
    color:#fff;
    font-weight:600;
    padding:12px 14px;
    text-align:right;
    border-bottom:2px solid #c55a08;
    white-space:nowrap;
    font-size:13px;
    line-height:1.35;
  }
  .arv-rates-table thead th small{
    display:block;font-size:11px;opacity:.7;font-weight:400;letter-spacing:.02em;margin-top:2px;
  }
  .arv-rates-table thead th:first-child{
    text-align:left;
    left:0;z-index:2;
    border-top-left-radius:12px;
  }
  .arv-rates-table thead th:last-child{border-top-right-radius:12px;}

  .arv-rates-table tbody th{
    text-align:left;
    font-weight:600;
    color:#0f172a;
    padding:11px 14px;
    background:#f8fafc;
    position:sticky;left:0;
    border-right:1px solid #e5e7eb;
    white-space:nowrap;
    font-size:14px;
  }
  .arv-rates-table tbody td{
    padding:11px 14px;
    text-align:right;
    color:#1e293b;
    border-bottom:1px solid #f1f5f9;
    font-variant-numeric:tabular-nums;
  }
  .arv-rates-table tbody tr:nth-child(even) th,
  .arv-rates-table tbody tr:nth-child(even) td{background:#fbfcfe;}
  .arv-rates-table tbody tr:hover th,
  .arv-rates-table tbody tr:hover td{background:#fff4e5;}
  .arv-rates-table tbody tr:last-child td{border-bottom:0;}
  .arv-rates-table tbody td strong{
    color:hsl(32deg 97% 45%);
    font-weight:700;
  }
  .arv-rates-cb{
    display:inline-block;
    color:hsl(32deg 97% 45%);
    margin-left:4px;
    font-size:13px;
  }

  .arv-rates-note{
    margin:14px 2px 0;
    font-size:14px;line-height:1.7;color:#334155;
  }
  .arv-rates-footnotes{
    margin:10px 2px 0;
    padding:10px 12px;
    background:#fff7ed;
    border-left:3px solid hsl(32deg 97% 45%);
    border-radius:4px;
    font-size:12.5px;line-height:1.65;color:#475569;
  }
  .arv-rates-footnotes sup{color:hsl(32deg 97% 45%);font-weight:700;margin-right:2px;}
  .arv-rates-footnotes a{color:hsl(32deg 97% 45%);text-decoration:underline;}

  /* FAQ section spacing */
  .arv-rates + h2{
    margin-top:40px;padding-top:20px;border-top:1px solid #e5e7eb;
  }

  /* CTA */
  .arv-rates-cta{
    margin:36px 0 24px;
    padding:28px 28px 26px;
    border-radius:16px;
    background:linear-gradient(135deg,#fff7ed 0%,#fff 60%);
    border:1px solid #fcd9ae;
    text-align:center;
  }
  .arv-rates-cta h3{margin:0 0 6px;font-size:20px;color:#0f172a;}
  .arv-rates-cta p{margin:0 0 18px;color:#475569;font-size:14px;}
  .arv-rates-cta-btns{display:flex;gap:12px;justify-content:center;flex-wrap:wrap;}
  .arv-rates-btn{
    display:inline-flex;align-items:center;gap:8px;
    padding:13px 24px;border-radius:999px;
    font-weight:700;font-size:15px;line-height:1;
    text-decoration:none;
    transition:transform .18s,box-shadow .18s,filter .18s;
    white-space:nowrap;
  }
  .arv-rates-btn--primary{
    background:hsl(32deg 97% 45%);color:#fff !important;
    box-shadow:0 6px 16px rgba(234,128,12,.28);
  }
  .arv-rates-btn--primary:hover{transform:translateY(-1px);filter:brightness(1.06);}
  .arv-rates-btn--ghost{
    background:#fff;color:#0f172a !important;
    border:1.5px solid #0f172a;
  }
  .arv-rates-btn--ghost:hover{background:#0f172a;color:#fff !important;}

  .arv-rates-disclaimer{
    margin:22px 0 0;
    font-size:12px;line-height:1.7;color:#64748b;
  }
  .arv-rates-disclaimer a{color:#0f172a;text-decoration:underline;}

  @media (max-width:640px){
    .arv-rates-table{font-size:13px;}
    .arv-rates-table thead th,
    .arv-rates-table tbody th,
    .arv-rates-table tbody td{padding:10px 10px;}
    .arv-rates-cta{padding:22px 18px;}
    .arv-rates-cta h3{font-size:18px;}
    .arv-rates-btn{padding:12px 18px;font-size:14px;}
  }
</style>
