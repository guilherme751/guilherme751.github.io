---
title: Research
---

## Research Focus

My research centers on **generative models applied to network traffic and IoT monitoring data**, with a focus
on three questions: can synthetic data faithfully replace real data (*fidelity*), is it actually useful for
downstream tasks (*utility*), and does it leak information about the individuals or systems it was trained on
(*privacy*). I've worked with **GANs, Transformers, and TimeGAN/RGAN-style architectures**, developed as part of
my work at LPRM (UFES) and during a research stay at Università di Torino (FAPESP-funded).

## Publications

{{< cards cols="1" >}}
  {{< card
    title="FlowMIA: Membership Inference Attack on Generative Network Flow Models"
    subtitle="Guilherme Brotto et al. — IEEE DCOSS-IoT 2026"
    icon="book-open"
  >}}
  {{< card
    title="IoTTraffic: Assessing Generative Models for Internet of Things Attack Data Flows"
    subtitle="Iran Ribeiro, Guilherme Brotto, Giovani Comarela, Rodolfo Villaça, Vinícius Mota — IEEE WF-IoT 2024"
    icon="book-open"
  >}}
  {{< card
    title="Measuring Fidelity and Utility of Time Series Generative Adversarial Networks"
    subtitle="Iran Ribeiro, Guilherme Brotto, Antonio Rocha, Vinícius Mota — IEEE ISCC 2024"
    icon="book-open"
  >}}
{{< /cards >}}

## Undergraduate Thesis

**FlowMIA: Membership Inference Attack on Generative Network Flow Models**

Completed with the highest grade in my cohort. A model-agnostic framework for evaluating privacy leakage in
tabular generative models using Membership Inference Attacks — requiring only synthetic data produced by the
model being audited. Built for network traffic data, but adaptable to any tabular domain.

**Technologies**: PyTorch, GANs, Transformers, Scikit-learn

[View on GitHub →](https://github.com/guilherme751/FlowMIA)
