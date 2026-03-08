# CasIA: Breaking the Self-Validation Ceiling

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC_BY--NC--ND_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

This repository contains the working paper and supplementary materials for the **CasIA (Cesar Adah Sophia IA)** framework — a structural solution to the monolithic self-validation problem in Large Language Models.

**Author:** César Lacruz  
**Latest version:** v12 (March 2026)  
**Paper:** [CasIA_Paper_v12_2026.pdf](./CasIA_Paper_v2.5_2026.pdf)

---

## 📄 Abstract

Current LLMs face a fundamental information-theoretic limit: any self-validation mechanism operating within the same representational space cannot reliably detect its own systematic errors. This ceiling persists under stochastic sampling and extends to all self-interactive protocols, including self-consistency and multi-agent debate within a single model (Theorem 3.1).

We introduce **CasIA**, a principled architecture that structurally separates generation, metacognitive validation, and normative regulation into independent parameter spaces — applying the principle of **privilege separation** to AI safety. Success is measured by **synergy** via Partial Information Decomposition (PID): information about correctness that exists only in the combination of components, never in any one alone.

We provide a complete experimental protocol — with matched-compute baselines, poisoned-context stress tests, and pre-registered PID robustness criteria — to quantify the "complementarity gap" of today's frontier models.

---

## 🔑 Key Contributions

1. **Formal proof** that any self-interactive protocol on a single model is bounded by its own representational space (Theorem 3.1).
2. **Detectability bound** via Fano's inequality, converting information theory into operational error limits (Lemma 3.1).
3. **CasIA Architecture**: three-component system with independent parameters for generation (𝒢), validation (𝒱), and regulation (𝒩).
4. **PID Synergy Criterion**: a measurable definition of when multi-model systems produce genuinely new information.
5. **Complete Experimental Protocol** with robustness analysis and matched-compute baselines.

---

## 📁 Repository Structure

