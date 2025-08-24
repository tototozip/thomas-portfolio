---
layout: inner
position: left
title: "Reasoning LLM-Based Stock Pricing"
date: 2025-06-04 18:00:00
categories: research finance
tags: [LLM, Stock-Pricing, Chain-of-Thought]
featured_image: "/thomas-portfolio/img/posts/05_llm-stock-pricing.png"
project_link: "thomasmolinier/thomas-portfolio/papers/ThesisMerged-7.pdf"
button_text: "Read the Paper"
button_icon: "file-pdf-o"
lead_text: "Exploratory project using chain-of-thought–enabled large language models to derive fair values for equities from fundamental disclosures and macro signals."
---

Exploratory project using **chain-of-thought–enabled large language models** to derive fair values for equities from fundamental disclosures and macro signals.

* LLMs: Qwen-2.5 7B + GRPO fine-tuning  
* Inputs: 10-K text embeddings, FRED macro time-series, analyst consensus  
* Outputs: conditional price distributions & risk-adjusted target returns  
* Early validation: Sharpe up to 1.4 on 2015–24 walk-forward (paper forthcoming)

Stay tuned for a full technical report and open-sourced notebooks.