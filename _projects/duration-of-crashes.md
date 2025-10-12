---
layout: page
title: Duration of Stock Market Crashes
description: We study how long it takes the U.S. market (CRSP) to recover from 10% drawdowns since 1926, why recovery times vary, and how to use that information.
img: /assets/projects/duration-of-crashes/crashes.png
pdf: /assets/projects/duration-of-crashes/duration-of-crashes.pdf
importance: 2
category: work
# related_publications: 
---

We study how long it takes the U.S. stock market to recover from a crash, defined as a 10% drop from a recent peak after the prior crash has recovered. Using the CRSP market index (daily data, 1926–2024), we identify **36** crash episodes. Recovery times are highly heterogeneous—**mean 387 days**, **median 127 days**, with a range from **30** to **4,544** days. On average, prices fall **28%** further before bottoming (time-to-trough: **13–1,039** days).

We show that the distribution of recovery times is too heavy-tailed to be explained by i.i.d. returns. Crashes associated with **bubbles** and **recessions** persist significantly longer, whereas liquidity-driven corrections tend to resolve quickly. We develop a **conditional duration model** (Inverse Gaussian with state-dependent mean and volatility) and provide reduced-form and MLE evidence that observable conditions at crash onset—valuation (CAPE), recession state, bubble indicators (PSY), and crash speed—help explain recovery times. Finally, we construct simple timing rules conditioned on these states that deliver **higher Sharpe ratios** than buy-and-hold.

- **Data:** CRSP market index (daily), 1926–2024  
- **Signals:** CAPE, NBER recessions, PSY bubble episodes, crash speed  
- **Takeaway:** Bubble/recession crashes last longer and have lower post-crash Sharpe; fast crashes recover faster
---