---
layout: page
title: Market sentiment and inhomogeneous information flow
description: Transfer Entropy - RMT - Market order books - Market sentiment
img: assets/img/RMTclustering.png
importance: 1
category: school
---

<a href="https://github.com/jpradov/Financial-big-data" style="display:inline-block;">
  <img src="/assets/img/github-mark.png" alt="GitHub Repository" width="30" height="30" style="filter: invert(0);">
</a>
<a href="/assets/pdf/FinBigData_PradoAffolter.pdf" style="display:inline-block;">
  <img src="/assets/img/pdf-icon.png" alt="Report PDF" width="30" height="30" style="filter: invert(0);">
</a>

<script>
  // Detect if night mode is active and switch icons to white version if true
  (function() {
    const nightMode = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;
    if (nightMode) {
      document.querySelectorAll('img[alt="GitHub Repository"]').forEach(img => {
        img.src = '/assets/img/github-mark-white.png';
      });
      document.querySelectorAll('img[alt="Report PDF"]').forEach(img => {
        img.src = '/assets/img/pdf-icon.png';
      });
    }
  })();
</script>

This work was jointly written with Joanne Affolter as part of the class "Financial Big Data", given by Damien Challet (CentraleSupelec, Paris).

# Abstract

Cryptocurrency markets are highly dynamic and volatile. They are characterized not only by rapid price fluctuations, but also by their sensitivity to market sentiment shifts relating jointly to the underlying assets and to the exchange platforms where these assets are traded.

This study examines how market sentiment fluctuations influence changes in currency quotes across different cryptocurrency exchanges, focusing on Bitcoin. We collect tick-by-tick trade data and second-resolution market order book data from Binance and Bitstamp throughout Jan 2021 - Dec 2021 and employ Google Trends search indexes for crypto keywords as proxies. The analysis unfolds in three stages: (i) validating our chosen proxy as an explanatory variable for cryptocurrency price changes using transfer entropy as a measure of information flow, (ii) checking the validity of traditional stylized facts in the crypto case and their variations across both exchanges, and (iii) scrutinizing the time-evolution of the induced lead-lag correlation throughout the studied period.

