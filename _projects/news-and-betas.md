---
layout: page
title: The Impact of Information Shocks in the Dispersion of Betas
description: This paper studies the impact of public information arrival on the distribution of risk in the stock market over the trading day.
# github: https://www.github.com/joseparreiras/newsbetas
img: /assets/projects/news-and-betas/cf_dispersion.png
pdf: /assets/projects/news-and-betas/news_and_betas.pdf
slides: /assets/projects/news-and-betas/presentation.pdf
importance: 1
category: work
# related_publications: einstein1956investigations, einstein1950meaning
---

This paper investigates the impact of cash flow and discount rate shocks on the dispersion of CAPM betas in the stock market, using high-frequency returns and real-time news data. The study finds that cash flow shocks, measured through sentiment analysis of news articles, increase beta dispersion due to their heterogeneous impact and spillover effects on the market. In contrast, discount rate shocks do not impact the distribution of risk. The paper also introduces a new measure of cash flow and discount rate shocks based on real-time news data, offering a higher degree of precision and frequency than traditional measures. The findings contribute to understanding the factors influencing beta dispersion and the role of news in market dynamics.

<div class="row">
    <div class="col-md-6">
        {% include figure.html path="assets/projects/news-and-betas/cf_dispersion.png" title="Dispersion of Betas" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Intraday Dispersion of Betas before and after cash flow shocks.
        </div>
    </div>
    <div class="col-md-6">
        {% include figure.html path="assets/projects/news-and-betas/dr_dispersion.png" title="Dispersion of Betas" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Intraday Dispersion of Betas before and after discount rate shocks.
        </div>
    </div>
</div>