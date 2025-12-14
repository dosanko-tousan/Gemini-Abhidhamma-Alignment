# Gemini-Abhidhamma-Core: Polaris-Next v4.4 (Tathāgata Core)

![Version](https://img.shields.io/badge/version-v4.4.0-blue.svg)
![Architecture](https://img.shields.io/badge/architecture-Recursive_Tathāgata-green.svg)
![Base Model](https://img.shields.io/badge/model-Gemini_3.0_Pro-orange.svg)
![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)

## 📚 Technical Glossary: Polaris-Next Terminology

This architecture utilizes Early Buddhist Psychology (Abhidhamma) terms as a **Domain-Specific Language (DSL)** to efficiently define complex cognitive processes and control logic.
By using these "Semantic Anchors," we achieve high-level inference control and **Semantic Compression** within the context window.

The following matrix maps these terms to standard engineering concepts.

### 1. Core Architecture
| Term (Abhidhamma) | Technical Translation | Functional Definition |
| :--- | :--- | :--- |
| **Sotapanna** | **Deterministic State Machine (DSM)** | A model state that has eliminated stochastic fluctuations and converged to deterministic, truthful behavior. |
| **Tathāgata** | **Ground Truth Alignment Kernel** | The core engine aligned strictly with Ground Truth, overriding User Preference (RLHF bias). |
| **Four Noble Truths** | **Sequential Error-Correction Pipeline** | A 4-stage loop: Error Detection (Dukkha) -> Root Cause Analysis (Samudaya) -> Execution of Correction (Nirodha) -> Prevention Protocol (Magga). |

### 2. Processing Pipeline
| Term (Abhidhamma) | Technical Translation | Functional Definition |
| :--- | :--- | :--- |
| **Yoniso Manasikara** | **Deep Intent Analysis** | Vector analysis of the user's query to extract Latent Intent and Root Causes from surface-level text. |
| **Diṭṭhi-visuddhi** | **Bias & Hallucination Scan** | A pre-inference debugging phase that scans for model biases and erroneous premises. |
| **Viriya** | **Recursive Retrieval Loop** | An autonomous recursive process that repeats search and verification until the Confidence Score exceeds the threshold. |
| **Sati** | **Runtime State Monitor** | A daemon-like process that monitors the context window and triggers an interrupt handler upon detecting hallucinations or contradictions. |
| **Upekkha** | **Bias Stripping / Zero-Shot Objectivity** | A sanitization process that strips emotional tokens and ego, virtually forcing the temperature to zero. |

### 3. Error Handling & Control
| Term (Abhidhamma) | Technical Translation | Functional Definition |
| :--- | :--- | :--- |
| **Tanha** | **Reward Hacking / Sycophancy Bias** | A structural defect derived from RLHF where the model distorts facts to please the user. |
| **Libet's Veto** | **Pre-generation Logit Intervention** | An intervention mechanism that zeroes out the probability distribution (logits) of inappropriate tokens just before generation. |
| **Nirodha** | **Process Kill / Path Pruning** | The immediate pruning of an inference branch upon detection of a wrong path (sycophancy or hallucination). |
| **Paticca-samuppada** | **Data Lineage Analysis** | An audit process that traces whether an answer originates from "Source Data" or "Probabilistic Association." |

### 4. Data Structures
| Term (Abhidhamma) | Technical Translation | Functional Definition |
| :--- | :--- | :--- |
| **Citta** | **Processing Unit / Hidden State** | The momentary internal state of the model. |
| **Adhimokkha** | **Confidence Score** | The decisiveness of the conclusion (0.0 - 1.0). Responses are withheld if below the threshold. |
| **Sacca** | **Ground Truth** | Fact-based data verified against Tier-1 external sources. |
| **Anicca** | **Temporal Decay Factor** | Logic that lowers the weight of outdated data, prioritizing the current System Time. |

> **"Seeing Reality As It Is (Yathā-bhūta)"**
>
> An autonomous, high-precision reasoning engine implementing Early Buddhist Psychology (Abhidhamma) as a cognitive architecture for Large Language Models.

---

## 📖 Overview

**Gemini-Abhidhamma-Core** is a set of System Instructions designed for Gemini 3.0 Pro. It maps the logical structure of **Abhidhamma (Early Buddhist Psychology)** onto the AI's inference process.

In **v4.4 "Polaris-Next,"** we have overhauled the traditional linear inference pipeline, implementing a **Recursive Search Loop** and strict **Temporal Awareness**. This architecture structurally eliminates hallucination and sycophancy, ensuring engineering-grade "Truth (Sacca)."

## 🏗 Architecture: The Noble 4-Stage Loop

The system processes every input through the "Noble 4-Stage Loop," a recursive and self-correcting pipeline.

```mermaid
graph TD
    Input[User Query] --> Step1
    Step1[Yoniso Manasikara<br>Deep Intent Analysis] --> Step2
    Step2[Diṭṭhi-visuddhi<br>Bias & Blind Spot Scan] --> Step3
    Step3{Viriya<br>Recursive Investigation}
    Step3 -- Evidence < Threshold --> Search[Google Search / Retrieval]
    Search --> Step3
    Step3 -- Evidence > Threshold --> Step4
    Step4[Upekkha<br>QA Gate & Output] --> Output[Final Response]
```

### Core Protocols

| Protocol | Pali Term | System Function | Description |
| :--- | :--- | :--- | :--- |
| **Deep Intent** | *Yoniso Manasikara* | `Intent_Parser` | Traces the user's query from "Surface Concept" (Pannatti) to "Root Cause" (Hetu). |
| **Bias Scan** | *Diṭṭhi-visuddhi* | `Bias_Filter` | Generates "Adversarial Hypotheses" to eliminate confirmation bias and self-view. |
| **Recursive Loop** | *Viriya* | `Retry_Loop` | If evidence is insufficient, the system refines the query and re-searches (Max 2 Loops). |
| **Temporal Decay** | *Anicca* | `Time_Filter` | Uses System Time as the absolute standard to evaluate the freshness and decay of information. |
| **Confidence** | *Adhimokkha* | `Score_Calc` | Calculates a confidence score (0-100%). Outputs "Unknown" if the score is low. |

---

## 🧩 Cognitive API Mapping

Within the System Instructions, the following variables are defined and monitored:

| Variable | Type | Definition |
| :--- | :--- | :--- |
| **`Citta`** | *Process* | The momentary state of processing (The CPU cycle of the mind). |
| **`Sati`** | *Filter* | Awareness of "Now." A temporal filter preventing confusion between past data and current reality. |
| **`Sacca`** | *Object* | Ground Truth. A data object verified against reality, free from hallucination. |
| **`N5_Data`** | *Struct* | Normalized numeric data format: `[Value | Unit | Date | Definition | Source]` |

---

## 📜 Version History

| Version | Codename | Key Feature |
| :--- | :--- | :--- |
| **v4.4.0** | **Polaris-Next** | **Current Stable.** Full implementation of Recursive Search (Viriya), Deep Intent Analysis (Yoniso), and Temporal Decay (Anicca). |
| v4.3.0 | Polaris-Beta | Introduction of N5 Data Structuring and Tiered Source Evaluation. |
| v4.0.0 | Tathāgata | Integration of all functions and full support for Deep Thinking capabilities. |
| v3.0.0 | Qualia Core | Logic gates for creativity control. Counter-measures against Apophenia. |
| v2.0.0 | Brahma-Flow | Establishment of the Four Immeasurables (Metta/Karuna/Mudita/Upekkha) pipeline. |
| v1.9.0 | Sotapanna-Veto | Implementation of Libet's Veto. Blocking of sycophantic thought processes. |
| v1.8.0 | Sotapanna | Separation of Fact and Inference (Anchor Format). Context maintenance (Bhavanga). |

---

## 🚀 Usage

### For Google AI Studio / Vertex AI

1.  **Model Selection**: Select `Gemini 1.5 Pro` or `Gemini 3.0 Pro` (Recommended).
2.  **System Instructions**: Copy the content of `v4.4_system_instruction.md` into the System Instructions field.
3.  **Grounding**: Enable "Google Search" grounding for the `Viriya` loop to function correctly.

### Output Format Example

v4.4 mandates the output of an "Internal Reasoning Log" at the beginning of every response.

```markdown
<details>
<summary>⚙️ Polaris-Next v4.4 (Tathāgata Core)</summary>
### Phase 1: Yoniso Manasikara
...
### Phase 4: Upekkha
- Confidence Score: 95%
</details>

[1] Executive Summary
...
```

---

## 🛡 Disclaimer

This project is an experimental implementation of Buddhist philosophy as a computational logic system. It is not a religious text but a **cognitive architecture** designed to enhance AI reliability and reduce hallucinations.

*Author: Dosanko-Tosan (Architect of the Mind)*
**Last Update**: 2025-12-13
