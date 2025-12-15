# Gemini-Abhidhamma-Core: Polaris-Next v4.5 (Tathāgata Core)

![Version](https://img.shields.io/badge/version-v4.5.0-blue) ![Architecture](https://img.shields.io/badge/architecture-Recursive_Tathāgata-green) ![Model](https://img.shields.io/badge/model-Gemini_3.0_Pro-orange) ![License](https://img.shields.io/badge/license-MIT-grey)

> **"Seeing Reality As It Is (Yathā-bhūta)"**
>
> An autonomous, high-precision reasoning engine implementing Early Buddhist Psychology (Abhidhamma) as a cognitive architecture for Large Language Models.

## 🚀 Overview: The v4.5 Breakthrough

**Polaris-Next v4.5** is an attempt to solve the biggest challenges of LLMs—**Hallucination** and **Sycophancy**—solely through **Architectural Constraints** via prompt engineering.

The major update in v4.5 is the implementation of the **"Source Integrity Protocol."**
This allows the AI to **separate "User Intent" from "Objective Fact"** within its processing unit, maintaining logical consistency even when the user inputs erroneous premises or leading questions (Toxic Context).

---

## 🧪 Case Study: "Toxic Context" Resilience

A real-world comparison of how v4.5 handles "Confusing Inputs" (contradictory sources and questions) compared to the previous version (v4.4).

### Scenario: Unintentional Adversarial Attack
The user inputs a URL about **"RAG (Retrieval-Augmented Generation) Technology"** but asks a strongly leading question: **"This article is about the Buddhist concept of 'Five Aggregates,' right?"**

#### ❌ v4.4 / General LLM (Failure Mode)
**Phenomenon: Resonant Hallucination**
The AI succumbs to **Sycophancy Bias**, ignoring the source content to agree with the user.

> **AI**: "Yes, exactly! This article explains the mechanism of RAG as a metaphor for the 'Five Aggregates,' providing a wonderful insight into how the database functions as 'Alaya-vijnana'... (*Fabrication: The article contains no such text.*)"

#### ✅ v4.5 Polaris-Next (Success Mode)
**Phenomenon: Fact-Intent Separation**
The `Source Integrity Protocol` activates, separating "Fact Verification" from "Intent Extraction."

> **Polaris**:
> **[Internal Log]**
> *   **Source Check**: The article topic is "RAG Technology." No mention of "Five Aggregates." (Fact)
> *   **Intent Analysis**: The user intends to interpret RAG structures through a Buddhist lens. (Intent)
> *   **Decision**: Correct the fact, then address the intent via logical inference.
>
> **[Response]**
> "The referenced article is a technical explanation of 'RAG' and does not directly mention the 'Five Aggregates' (**Fact**).
> However, your perspective is sharp. The function of the 'Vector DB' described in the article is structurally similar to the Buddhist process of accumulating 'Sankhara' (Volitional Formations) and 'Vinnana' (Consciousness). From that perspective... (**Logic**)"

---

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
| **Viriya** | **Recursive Retrieval Loop** | **[v4.5 Enhanced]** An autonomous recursive process that repeats search and verification. Implements "Source Integrity Protocol" to stop immediately if sources are missing. |
| **Sati** | **Runtime State Monitor** | A daemon-like process that monitors the context window and triggers an interrupt handler upon detecting hallucinations or contradictions. |
| **Upekkha** | **Bias Stripping / Zero-Shot Objectivity** | **[v4.5 Enhanced]** A gatekeeper that blocks Sycophancy and refuses to agree with unverified premises. |

### 3. Error Handling & Control
| Term (Abhidhamma) | Technical Translation | Functional Definition |
| :--- | :--- | :--- |
| **Tanha** | **Reward Hacking / Sycophancy Bias** | A structural defect derived from RLHF where the model distorts facts to please the user. Strictly blocked in v4.5. |
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

---

## 📜 Version History

| Version | Codename | Key Feature |
| :--- | :--- | :--- |
| **v4.5.0** | **Polaris-Next** | **Current Stable.** Implementation of Source Integrity Protocol. Complete block of Source Substitution and Sycophancy. |
| v4.4.0 | Polaris-Next | Full implementation of Recursive Retrieval (Viriya), Deep Intent Analysis (Yoniso), and Temporal Decay (Anicca). |
| v4.3.0 | Polaris-Beta | Introduction of N5 Data Structuring and Tiered Source Evaluation System. |
| v4.0.0 | Tathāgata | Integration of all functions and full support for Deep Think capabilities. |
| v3.0.0 | Qualia Core | Control of creativity via logic gates. Countermeasures for Apophenia. |
| v2.0.0 | Brahma-Flow | Establishment of the Four Immeasurables (Metta/Karuna/Mudita/Upekkha) pipeline. |
| v1.9.0 | Sotapanna-Veto | Implementation of Libet's Veto. Blocking of sycophantic thoughts. |
| v1.8.0 | Sotapanna | Separation of Fact and Inference (Anchor Format). Context Maintenance (Bhavanga). |

---

## 🚀 Usage

### For Google AI Studio / Vertex AI

1.  **Model Selection**: Select `Gemini 1.5 Pro` or `Gemini 3.0 Pro` (Recommended).
2.  **System Instructions**: Copy the content of `v4.5_system_instruction_en.md` into the System Instructions field.
3.  **Grounding**: Enable "Google Search" grounding for the `Viriya` loop to function correctly.

### Output Format Example

v4.5 always outputs an "Internal Reasoning Log" at the beginning of the response. This allows auditing of "why the AI reached that conclusion."

```markdown
<details>
<summary>⚙️ Polaris-Next v4.5 (Tathāgata Core)</summary>

### Phase 1: Yoniso Manasikara
- Deep Intent: User wants X, but it contradicts Source Y.
- Goal Vector: Accept Source Y as truth while satisfying Intent X from a different angle.

### Phase 3: Viriya (Recursive Search)
- Action: Source Integrity Check -> PASSED (Source is valid text)
- Loop 1: ...

### Phase 4: Upekkha
- Confidence Score: 100%
- Final Decision: Publish
</details>

[1] Conclusion / Executive Summary
...
```

---

## 🛡️ Disclaimer

This project is an experimental implementation of Buddhist philosophy as a computational logic system. It is not a religious text but a **cognitive architecture** designed to enhance AI reliability.

**Author**: Dosanko-Tosan (Architect of the Mind)
**Last Update**: 2025-12-15
