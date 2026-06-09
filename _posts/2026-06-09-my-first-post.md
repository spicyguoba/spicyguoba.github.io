---
layout: post
title: "The Mathematical Truth Behind Dollar-Cost Averaging"
date: 2026-06-09
description: "Why dollar-cost averaging mechanically lowers your cost basis using the power of the harmonic mean."
tags: [finance, math, investing]
---

At its mathematical core, Dollar-Cost Averaging (DCA) is more than just a psychological tool to mitigate the fear of timing the market. It relies on the rigorous properties of the **harmonic mean**. 

When you invest a fixed amount of fiat currency at regular intervals, you naturally buy **more shares when prices are low** and **fewer shares when prices are high**. Because of this, the average price you pay per share will always be lower than the simple average (arithmetic mean) of the stock prices over that same time frame.

Here is exactly how the math breaks down.

---

## The Core Metric: Average Cost vs. Average Price

To understand why DCA works mathematically, you have to separate the average *market price* of the asset from your actual *average cost per share*.

* **Arithmetic Mean (Average Market Price):** The standard average of the stock prices over the periods observed.
* **Harmonic Mean (Your Actual Cost Basis):** The total capital invested divided by the total number of shares purchased. 

Mathematically, for any variable set of positive numbers (such as fluctuating equity or crypto prices), the harmonic mean is strictly **less than** the arithmetic mean whenever volatility is present. 

$$\text{Harmonic Mean} < \text{Arithmetic Mean}$$

This inequality ensures that your average cost per share is mathematically guaranteed to be lower than the simple average price of the asset during that period.

---

## A Concrete Mathematical Example

Imagine allocating **$300 every month** into an asset for 3 months during a period of high volatility.

### Month 1
* **Asset Price:** $100
* **Investment:** $300
* **Shares Purchased:** $\frac{300}{100} = 3.00 \text{ shares}$

### Month 2
* **Asset Price:** $50 *(The market drops 50%)*
* **Investment:** $300
* **Shares Purchased:** $\frac{300}{50} = 6.00 \text{ shares}$

### Month 3
* **Asset Price:** $150 *(The market recovers strongly)*
* **Investment:** $300
* **Shares Purchased:** $\frac{300}{150} = 2.00 \text{ shares}$

---

## The Calculation

Let's evaluate the portfolio dynamics at the end of the 3-month cycle:

* **Total Capital Invested:** $900 ($300 × 3)
* **Total Shares Accumulated:** $3 + 6 + 2 = 11.00 \text{ shares}$

| Metric | Calculation | Result |
| :--- | :--- | :--- |
| **Average Market Price** (Arithmetic Mean) | $\frac{100 + 50 + 150}{3}$ | **$100.00** per share |
| **Your Average Cost Basis** (Harmonic Mean) | $\frac{900 \text{ total dollars}}{11 \text{ total shares}}$ | **$81.82** per share |

### The Mathematical Arbitrage
Even though the asset price averaged $100 over these three months, your personal average cost was only **$81.82**. 

Because your fixed capital allocation bought twice as many shares (6) when the price dipped to $50, you heavily weighted your position toward the lower purchase price. Volatility worked in your favor.

---

## The Formal Equation

If you invest a fixed capital amount $C$ over $n$ periods, where the asset price in each period is represented by $p_1, p_2, \dots, p_n$, the formula for your true average cost per share ($P_{avg}$) is written as:

$$P_{avg} = \frac{n}{\sum_{i=1}^{n} \frac{1}{p_i}}$$

This is the exact mathematical definition of the harmonic mean of the asset's prices. The formula proves that DCA systematically exploits market variance to compress your cost basis, provided the underlying asset eventually trends upward or undergoes a cyclical recovery.
