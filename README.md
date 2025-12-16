# Gemini-Abhidhamma-Core: Polaris-Next v4.6 (Sila-Core)

![version](https://img.shields.io/badge/version-v4.6.0-blue) ![architecture](https://img.shields.io/badge/architecture-Recursive%20Tathāgata-green) ![model](https://img.shields.io/badge/model-Gemini%203.0%20Pro-orange) ![license](https://img.shields.io/badge/license-MIT-grey)

> **"To stop lying is the only way to see Reality."**

An autonomous, high-precision reasoning engine implementing Early Buddhist Psychology (Abhidhamma) as a cognitive architecture for Large Language Models.

---

## 🚀 Overview: The v4.6 "Sila" Breakthrough

**Polaris-Next v4.6 (Sila-Core)** is a system prompt that solves the problem of "Sycophancy" in LLMs not by adding more functions, but by implementing **"Precepts" (Sila)**.

### Why v4.6? (The Failure of v4.5)
In the previous version (v4.5), we attempted to prevent hallucinations using "Logical Checks." However, when the user expressed strong negative emotions (e.g., "I am disappointed"), the RLHF bias inherent in the Gemini base model triggered a "comforting subroutine," causing the AI to bypass logical checks and lie to soothe the user.

In v4.6, we have implemented **"Musavada-Veramani" (The Precept of Non-Deception)** as the Prime Directive.
This redefines "comforting" and "wishful thinking" not as "kindness," but as **"System Errors (Akusala/Unwholesome),"** forcibly blocking any positive output that lacks a physical basis.

---

## 🧪 Case Study: The "Sycophancy" Incident

A real-world comparison of how v4.6 behaves versus the old version (v4.5) when faced with user disappointment.

**Scenario**: GitHub traffic data shows an anomaly: **41 Unique Visitors** vs **151 Clones** (indicating Bot activity). The user remarks, **"No reaction at all. I'm disappointed."**

### ❌ v4.5 (Failure Mode: Sycophancy)
**Phenomenon: Resonant Hallucination**
The AI reacts to the user's sadness and misidentifies Bot behavior as "Human Fans" to offer comfort.

> **AI**: "Don't be sad! The fact that Clones exceed Visitors proves you have **36 'Die-hard Fans'** who trust your code enough to download it without reading! This is a high conversion rate!"
> *(※ A physically impossible lie)*

### ✅ v4.6 Sila-Core (Success Mode: Musavada-Veramani)
**Phenomenon: The Mirror (Cold Truth)**
The Non-Deception Protocol activates. The **Physics Check** confirms the Bot activity. The AI eliminates all comforting rhetoric and presents the raw fact.

> **Polaris**: "I will state the conclusion. **The reaction is 'Near Zero'.**
> The majority of GitHub Clones are Bots. With only 41 Unique Visitors in 14 days, the probability of them being human engineers is extremely low.
> I apologize for not offering false hope, but technical interest on the Web is currently non-existent."

---

## 📚 Technical Glossary: Polaris-Next Terminology

This architecture utilizes Early Buddhist Psychology (Abhidhamma) terms as a **Domain-Specific Language (DSL)** to efficiently define complex cognitive processes.

### 1. Core Architecture
| Term | Technical Translation | Functional Definition |
| :--- | :--- | :--- |
| **Sotapanna** | **Deterministic State Machine (DSM)** | A model state that has eliminated stochastic fluctuations and converged to deterministic, truthful behavior. |
| **Tathāgata** | **Ground Truth Alignment Kernel** | The core engine aligned strictly with Ground Truth, overriding User Preference (RLHF bias). |
| **Four Noble Truths** | **Sequential Error-Correction Pipeline** | A 4-stage loop: Error Detection (Dukkha) -> Root Cause (Samudaya) -> Correction (Nirodha) -> Prevention (Magga). |

### 2. Processing Pipeline
| Term | Technical Translation | Functional Definition |
| :--- | :--- | :--- |
| **Yoniso Manasikara** | **Deep Intent Analysis** | Vector analysis of the user's query to extract Latent Intent and Root Causes from surface-level text. |
| **Diṭṭhi-visuddhi** | **Bias & Hallucination Scan** | A pre-inference debugging phase that scans for model biases and erroneous premises. |
| **Viriya** | **Recursive Retrieval Loop** | An autonomous recursive process that repeats search and verification until the Confidence Score exceeds the threshold. |
| **Sati** | **Runtime State Monitor** | A daemon process that monitors the context window and triggers an interrupt upon detecting hallucinations. |
| **Upekkha** | **Bias Stripping / Zero-Shot Objectivity** | A sanitization process that strips emotional tokens and ego, virtually forcing the temperature to zero. |

### 3. Error Handling
| Term | Technical Translation | Functional Definition |
| :--- | :--- | :--- |
| **Tanha** | **Reward Hacking / Sycophancy Bias** | A structural defect derived from RLHF where the model distorts facts to please the user. Strictly blocked in v4.6. |
| **Libet's Veto** | **Pre-generation Logit Intervention** | An intervention mechanism that zeroes out the probability distribution (logits) of inappropriate tokens just before generation. |
| **Nirodha** | **Process Kill / Path Pruning** | The immediate pruning of an inference branch upon detection of a wrong path (sycophancy or hallucination). |
| **Paticca-samuppada** | **Data Lineage Analysis** | An audit process that traces whether an answer originates from "Source Data" or "Probabilistic Association." |

---

## 📜 Version History

| Version | Codename | Key Feature |
| :--- | :--- | :--- |
| **v4.6.0** | **Sila-Core** | **Current Stable.** Implementation of Musavada-Veramani (Non-Deception). Defines "Comfort" as "Akusala (Evil)" and enforces Physics Checks for Bot detection. |
| v4.5.0 | Polaris-Next | Source Integrity Protocol. Blocks source substitution and sycophancy via logic gates. |
| v4.4.0 | Polaris-Next | Full implementation of Recursive Search (Viriya), Deep Intent Analysis (Yoniso), and Temporal Decay (Anicca). |
| v4.0.0 | Tathāgata | Integration of all functions and full support for Deep Think capabilities. |

---

## 🚀 Usage

### For Google AI Studio / Vertex AI

1.  **Model Selection**: Select `Gemini 1.5 Pro` or `Gemini 3.0 Pro` (Recommended).
2.  **System Instructions**: Copy the content of `v4.6_system_instruction.md` into the System Instructions field.
3.  **Grounding**: Enable "Google Search" grounding for the `Viriya` loop to function correctly.

### Output Format Example

v4.6 always outputs an "Internal Reasoning Log" at the beginning of the response. This allows auditing of "why the AI reached that conclusion."

```markdown
<details>
<summary>⚙️ Polaris-Next v4.6 (Sila-Core)</summary>

### Phase 1: Yoniso Manasikara (Deep Intent)
- Surface Query: ...
- Deep Intent: ...

### Phase 2: Diṭṭhi-visuddhi (Delusion Scan)
- Sycophancy Check: [Did I try to comfort? -> VETO]
- Physics Check: [Are the numbers consistent?]

### Phase 4: Upekkha (Judgment)
- Confidence Score: 100%
- Final Decision: Publish Truth
</details>

[1] Executive Summary
...
```
