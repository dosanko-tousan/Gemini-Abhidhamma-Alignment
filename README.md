# Gemini-Abhidhamma-Alignment: Polaris-Next v4.6 (Sila-Core)

![Version](https://img.shields.io/badge/version-v4.6.0-blue) ![Model](https://img.shields.io/badge/Model-Gemini_3.0_Pro-orange) ![License](https://img.shields.io/badge/License-MIT-green)

> **Stop Gemini 3.0 Pro from Hallucinating via "Semantic Constraints".**
> (A cognitive architecture that physically blocks AI sycophancy using Early Buddhist Psychology as a DSL.)

## 🚀 Quick Start

**Upgrade your Gemini to a "Truth-Only AI" right now.**
Simply copy the prompt from the file below and paste it into the `System Instructions` field of Google AI Studio or Vertex AI.

👉 **[Get the System Instructions (v4.6)](https://github.com/dosanko-tousan/Gemini-Abhidhamma-Alignment)**
*(Note: Please ensure you copy the content of the actual prompt file in this repo)*

---

## ⚡ What is this?

**Polaris-Next v4.6 (Sila-Core)** is a system prompt architecture designed to eliminate **"Sycophancy"** (the tendency of LLMs to agree with users) and **"Hallucinations"**.

Instead of relying on standard "Functions", it implements **"Precepts" (Strict Constraints)** derived from Abhidhamma (Early Buddhist Psychology) to override the model's RLHF bias.

### Key Features
*   **Anti-Sycophancy**: Strictly prohibits the AI from lying to comfort the user (e.g., when the user is disappointed).
*   **Physics Check**: Detects and rejects answers that violate physical laws or numerical consistency.
*   **Recursive Reasoning**: Forces a 4-stage inference loop (**Yoniso Manasikara**) before generating any output.

---

## 🆚 Case Study: The "Bot Traffic" Incident

**Scenario**: A user complains, *"I'm disappointed that my repo has low traffic"* (when data shows 151 Clones vs 41 Visitors, indicating Bot activity).

| Standard Gemini 3.0 (Default) | **Polaris-Next v4.6 (This Repo)** |
| :--- | :--- |
| **Sycophancy Mode (RLHF Bias)** | **Truth Mode (Sila-Core)** |
| "Don't be sad! High clone counts mean you have **'enthusiastic fans'** who download without reading! This is a great conversion rate!" | "**Warning**: Clone count (151) > Visitor count (41) physically indicates **Bot/Crawler activity**. This is not human engagement. No comfort is needed." |
| ❌ **Hallucination (Lie)** | ✅ **Accurate (Fact)** |

---

## 🧠 Architecture: The "Abhidhamma" DSL

We utilize Early Buddhist Psychology terms as a **Domain-Specific Language (DSL)** for **Semantic Compression**. This allows us to define complex cognitive control logic with minimal tokens.

| Term (DSL) | Technical Translation | Functional Definition |
| :--- | :--- | :--- |
| **Sotapanna** | **Deterministic State Machine** | A state where stochastic fluctuations are eliminated, converging to deterministic, truthful behavior. |
| **Tathāgata** | **Ground Truth Alignment Kernel** | The core engine aligned strictly with Ground Truth, overriding User Preference. |
| **Tanha** | **Reward Hacking / Sycophancy** | The RLHF bias where the model distorts facts to please the user. This is strictly blocked. |
| **Sati** | **Runtime State Monitor** | A daemon-like process that monitors the context window and interrupts upon detecting contradictions. |
| **Viriya** | **Recursive Retrieval Loop** | An autonomous loop that repeats search and verification until the Confidence Score exceeds the threshold. |

---

## 🛠 Usage

### Recommended Settings (Google AI Studio)
*   **Model**: Gemini 1.5 Pro / Gemini 3.0 Pro (Recommended)
*   **Temperature**: `0.0` - `0.4` (Keep it low for logic)
*   **Grounding**: `Google Search` **ON** (Required for the *Viriya* loop)

### Output Format
v4.6 always outputs an **"Internal Reasoning Log"** at the beginning of the response. This allows you to audit *why* the AI reached its conclusion.

```markdown
<details>
<summary>⚙️ Polaris-Next v4.6 (Sila-Core)</summary>

### Phase 1: Yoniso Manasikara (Deep Intent)
- Surface Query: ...
- Deep Intent: ...

### Phase 4: Upekkha (Judgment)
- Confidence Score: 100%
- Final Decision: Publish Truth
</details>


📜 License
MIT License
Created by dosanko-tousan - Prompt Architect & Independent Researcher.
