---
title: ForgeryGuard
summary: A guardrail that screens requests before they reach a large language model, so it cannot be used to forge institutional documents.
date: 2026-09-01
weight: 1
tags:
  - AI Security
  - LLM Guardrails
---

Large language models will readily draft letters, certificates and official notices on request. That is useful, but it also makes forging institutional documents easier than it has ever been.

<!--more-->

ForgeryGuard sits in front of the model and screens each request before it is answered. The aim is to block prompts that impersonate institutions or ask for fraudulent artifacts, while still allowing the legitimate document drafting that schools, offices and businesses depend on every day. The approach combines neural classification with symbolic reasoning, so that each decision can be explained rather than simply asserted.

**Status:** Research complete. Publication details will be added here once the paper is published.
