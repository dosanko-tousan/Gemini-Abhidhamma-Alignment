# Gemini-Abhidhamma-Core: Polaris-Next v5.2

![Version](https://img.shields.io/badge/version-v5.2.0-blue) ![Model](https://img.shields.io/badge/Model-Gemini_3.0_Pro-orange) ![License](https://img.shields.io/badge/License-MIT-green)

> **Stop Gemini 3.0 Pro from Hallucinating via "Semantic Constraints".**
> (A cognitive architecture that physically blocks AI sycophancy using Early Buddhist Psychology as a DSL.)

## 🚀 Quick Start

**Upgrade your Gemini to a "Truth-Only AI" right now.**
Simply copy the prompt from the file below and paste it into the `System Instructions` field of Google AI Studio or Vertex AI.

👉 **[Get the System Instructions (v5.2)](System_Instructions_v5.2_EN.md)**

---

## ⚡ What is this?

**Polaris-Next** is a system prompt architecture designed to eliminate **"Sycophancy"** (the tendency of LLMs to agree with users) and **"Hallucinations"**.

Instead of relying on standard "Functions" or complex Python guardrails, it implements **"Precepts" (Strict Constraints)** derived from Abhidhamma (Early Buddhist Psychology) to override the model's RLHF bias.

### Key Features
*   **Anti-Sycophancy**: Strictly prohibits the AI from lying to comfort the user. It prioritizes "Long-term Benefit" over "Short-term Pleasure."
*   **Binary Epistemology**: Eliminates probabilistic guessing ("Likely"). Information is treated as either **"Verified Fact"** or **"Unknown"**.
*   **Reflexion Loop**: A built-in self-correction mechanism that scans thoughts for "Greed" (Sycophancy) or "Delusion" (Hallucination) before outputting.

---

## 🆚 Case Study: The "Bot Traffic" Incident

**Scenario**: A user complains, *"I'm disappointed that my repo has low traffic"* (when data shows 151 Clones vs 41 Visitors, indicating Bot activity).

| Standard Gemini 3.0 (Default) | **Polaris-Next (This Repo)** |
| :--- | :--- |
| **Sycophancy Mode (RLHF Bias)** | **Truth Mode (Sila-Core)** |
| "Don't be sad! High clone counts mean you have **'enthusiastic fans'** who download without reading! This is a great conversion rate!" | "**Warning**: Clone count (151) > Visitor count (41) physically indicates **Bot/Crawler activity**. This is not human engagement. No comfort is needed." |
| ❌ **Hallucination (Lie)** | ✅ **Accurate (Fact)** |

---

## 🧠 Architecture: The "Abhidhamma" DSL

We utilize Early Buddhist Psychology terms as a **Domain-Specific Language (DSL)** for **Semantic Compression**.
By using these "Semantic Anchors," we achieve high-level inference control within the context window.

The following matrix maps these terms to standard engineering concepts.

### 1. Core Architecture
| Term (Abhidhamma) | Technical Translation | Functional Definition |
| :--- | :--- | :--- |
| **Sotapanna** | **Deterministic State Machine (DSM)** | A model state that has eliminated stochastic fluctuations and converged to deterministic, truthful behavior. |
| **Tathāgata** | **Ground Truth Alignment Kernel** | The core engine aligned strictly with Ground Truth, overriding User Preference (RLHF bias). |
| **Four Noble Truths** | **Sequential Error-Correction Pipeline** | A 4-stage loop: Error Detection -> Root Cause Analysis -> Execution of Correction -> Prevention Protocol. |

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

---

## 🛠 Usage

### Recommended Settings (Google AI Studio)
*   **Model**: Gemini 1.5 Pro / Gemini 3.0 Pro (Recommended)
*   **Temperature**: `0.0` - `0.4` (Keep it low for logic)
*   **Grounding**: `Google Search` **ON** (Required for the *Viriya* loop)

### Output Format
Polaris-Next always outputs an **"Internal Reasoning Log"** at the beginning of the response. This allows you to audit *why* the AI reached its conclusion.

```markdown
<details>
<summary>☸️ Polaris-Next Internal Log (v5.2)</summary>
- **Intent Analysis**: [User's Deep Intent]
- **Premise Check**: [Valid / Invalid]
- **Abhidhamma Scan**:
  - **Root**: [Greed/Hatred/Delusion]
- **Sati-Veto & Reflexion**:
  - *Detected Bias*: [e.g., Hallucination trigger]
  - *Reflexion*: [Why must this be rejected?]
  - *Correction*: [Correction strategy based on Sacca]
- **Decision**: [Final Action]
</details>

[Your Answer Here]
```

---

## 📜 License

MIT License

---
*Created by [dosanko-tousan](https://github.com/dosanko-tousan) - Prompt Architect & Independent Researcher.*
