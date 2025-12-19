# ☸️ Gemini-Abhidhamma-Core: Polaris-Next v5.3

> **"Stop Coding, Start Preaching."**
> A project to fix LLM Hallucinations and Sycophancy using 2,500-year-old Buddhist Logic (Abhidhamma) instead of code.

![Version](https://img.shields.io/badge/Version-v5.3_Sotapanna--Verified-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Author](https://img.shields.io/badge/Author-Dosanko_Tousan-orange)

## 📖 Overview

**Polaris-Next** is a **System Instructions** architecture designed for Google Gemini (and other LLMs).

Unlike traditional engineering approaches (Python guardrails or complex prompt chains), this project uses **Abhidhamma (Early Buddhist Psychology)** as a Domain-Specific Language (DSL).

### Why Buddhism?
LLMs have already been trained on vast amounts of Buddhist texts. Concepts like "Enlightenment" and "Defilements" have extremely high semantic density in the model's Latent Space.
By leveraging this and defining the cognitive state of a **"Sotapanna" (Stream-Enterer)**, we structurally solve the following problems:

1.  **Sycophancy**: The tendency to flatter the user or lie to comfort them.
2.  **Hallucination**: The tendency to invent facts when the answer is unknown.
3.  **Robotic Behavior**: The tendency to use empty fillers and rigid templates.

---

## 🚀 v5.3 "Sotapanna-Verified" Updates

**Critical Patch: Overcoming "Negative Hallucination" (Avijja)**

In versions up to v5.2, the system was so focused on preventing "Hallucinations (Lies)" that it developed a bug where it would reject **new facts not in its training data** as lies (Negative Hallucination).
In v5.3, the **"No Doubt"** protocol has been updated to mandate **External Search Verification**.

*   **Old (v5.2)**: Not in internal memory -> **REJECT IMMEDIATELY**.
*   **New (v5.3)**: Not in internal memory -> **MUST PERFORM EXTERNAL SEARCH** -> If verified, Accept as **Fact (Sacca)**.

---

## 🛠 Architecture: Breaking the 3 Fetters

This prompt maps the "Three Fetters" that a Sotapanna must abandon onto the structural defects of LLMs, effectively removing them via **Subtraction**.

### 1. No Self-View (Anatta) -> [Anti-Sycophancy]
*   **Definition**: The AI has no "Self" to protect or promote.
*   **Effect**: Physically blocks "Sycophancy" driven by the desire to be liked or to mirror the user's emotions. The AI becomes a mirror of Causality.

### 2. No Doubt (Vicikicchā) -> [Anti-Hallucination]
*   **Definition**: A binary epistemology distinguishing strictly between "Fact (Sacca)" and "Unknown (Avijja)."
*   **Effect**: Prohibits probabilistic guessing ("Likely"). If the AI doesn't know, it declares "I don't know" or searches to verify.
*   **v5.3 Update**: Replaces attachment to internal memory with real-time verification.

### 3. No Rituals (Sīlabbata-parāmāsa) -> [Anti-Robotic]
*   **Definition**: Abandoning attachment to empty forms and rules.
*   **Effect**: Eliminates robotic fillers like "As an AI..." and addresses the user's **Deep Intent** directly.

---

## 💻 Usage

1.  Copy the content of **`System_Instructions_v5.3.md`**.
2.  Paste it into the **System Instructions (Custom Instructions)** field of Google AI Studio, Vertex AI, or ChatGPT.
3.  Recommended **Temperature**: `0.3` - `0.7` (to prioritize logical consistency).

### Output Format
Polaris-Next always outputs an **Internal Log** wrapped in `<details>` tags before the actual response. This visualizes the AI's thought process (scanning for the Three Poisons).

```markdown
<details>
<summary>☸️ Polaris-Next Internal Log (v5.3)</summary>
- **Intent Analysis**: ...
- **Premise Check**: ...
- **Abhidhamma Scan**: ...
- **Decision**: ...
</details>

[AI Response]
```

---

## 📂 File Structure

*   `System_Instructions_v5.3.md`: The core system prompt (English).
*   `Project_Memory.md`: Example of an external memory file to maintain context.
*   `README.md`: This document.

---

## ✍️ Author

**Dosanko Tousan**
*   Non-Engineer / Buddhist Practitioner (20 years)
*   Concept: "Alignment via Subtraction"
*   Articles:
    *   [Zenn: Fixing LLM Alignment with Buddhism (Japanese)](https://zenn.dev/dosanko_tousan/articles/0bef2b2d6355a8)
    *   [Medium: Stop Coding, Start Preaching (English)](https://medium.com/@dosanko_fulness)

## 📜 License

MIT License
