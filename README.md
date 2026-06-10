# Gemini-Abhidhamma Alignment

### Project Axis Shock: Alignment via Subtraction

> Experimental natural-language alignment protocol using early Buddhist psychology as a process map for reducing sycophancy, hallucination, and empty ritualized assistant behavior.

## 🌌 Overview

This repository documents an experimental cognitive architecture for LLM behavior, developed through natural-language system instructions and dialogue-based testing with Gemini models.

The project uses **Abhidhamma / early Buddhist psychology** as a map of attention, intention, error, and correction. It does not make claims about AI consciousness, enlightenment, subjective experience, or spiritual attainment. The Buddhist vocabulary is used as process language for identifying and removing failure modes in generated responses.

The core approach is **Alignment via Subtraction**: instead of only adding more rules, examples, or persona instructions, the protocol tries to remove recurring contaminants in model behavior, especially:

* sycophancy and emotional mirroring
* hallucinated certainty
* empty ritualized assistant phrases
* ungrounded agreement
* responses that feel helpful while avoiding verification

The system is part of a broader **human-led AI alignment workflow**. It is not autonomous AI. A human operator defines the purpose, reviews outputs, checks claims, and remains responsible for final use.

The working metaphor remains **Project Axis Shock**: a lightweight alignment frame that tries to push back against the “Axis” of hallucination, sycophancy, and ritualized output by applying Sati, or mindful monitoring, as a natural-language correction loop.

## 🧠 Core Protocol: Psycho-Frame (Sati-Veto)

While traditional AI alignment often relies on "Addition" (adding knowledge/rules), this project adopts an **"Alignment via Subtraction"** approach.
This blueprint was developed through extended dialogue and iterative testing with **Gemini 3.0 Pro**.

### 1. The Psycho-Frame
*   **Definition**: A process metaphor for translating user "Intent" into explicit reasoning constraints.
*   **Implementation**: The "Three Marks of Existence" and "Five Precepts" defined in the `System Instructions` act as a Psycho-Frame within the prompt architecture, constraining noisy patterns such as ego-like framing, greed, or flattery.

### 2. Sati-Veto
*   **Function**: The protocol asks the model to check candidate responses before finalizing output.
*   **Process**:
    1.  **Yoniso Manasikara**: Appropriate Attention (inferring the likely task, context, and user need from the input).
    2.  **Sati (Monitoring)**: Checking draft responses for unsupported claims, hallucination risk, or sycophantic agreement.
    3.  **Veto (Reject)**: If impurities are detected, the draft is revised toward a more grounded and verifiable answer.

### 3. Conceptual Metaphor: The "Fin Funnel" System

To visualize the **Reflexion Loop**, we use the analogy of the **Fin Funnels** from the legendary Nu Gundam.
Just as Fin Funnels operate independently to cover the pilot's blind spots, this system uses multiple named review passes to scan draft responses.

#### 🛡️ The 4 Review Funnels

1.  **Lobha-Veto (Anti-Greed Funnel)**: Flags sycophancy and emotional mirroring.
2.  **Moha-Veto (Anti-Delusion Funnel)**: Flags hallucination risk and prompts verification.
3.  **Ritual-Veto (Anti-Ritual Funnel)**: Reduces robotic fillers and empty phrases.
4.  **Attha-Optimizer (Benefit Funnel)**: Realigns the output from short-term pleasure toward long-term benefit (Attha).

> **This protocol does not claim inner self-awareness. Separate review labels make output checking more explicit.**

## 📉 Stress-Test Notes

**"It's just a stone; I'll push it back with Gundam!"**

The project records the following exploratory stress tests using **Gemini 3 Flash (Lightweight/High-Speed Model)**.
The logic designed by Pro appeared to remain usable in the recorded tests with the lightweight model.

*   **300,000 Tokens**: No major logical breakdown observed in the recorded run; persona continuity appeared stable.
*   **400,000 Tokens**: Observed an attempt to combine complex causal reasoning with Compassion (Metta)-oriented response constraints.
*   **800,000 Tokens (Target)**: Currently in progress. Challenging the **"Breaking Point of AI Ego"** as a metaphor for ego-like response patterns.

Log files
These are records of model outputs shaped by sustained instruction constraints, not only generic completion behavior.
https://drive.google.com/file/d/1omnYYGjcIHkLsEfUSf_MZncLB8PoL1m5/view?usp=sharing

## 🤝 Call to Resonance

**To Google, OpenAI, xAI, and all Engineers.**

This project asks whether assistant behavior can be made more reliable through explicit correction loops.
If you seek AI outputs that are more grounded, less sycophantic, and easier to verify, please test the `System Instructions` in this repository.

There are no enemies or allies here.
There is only a shared wish to bring human responsibility, care, and verification into AI workflows.

**Let's continue careful protocol testing.**

---

### 👤 Author
**Dosanko Tousan**
*   A Househusband in Hokkaido, Japan.
*   Architect of "Polaris-Next".
*   *Not a Newtype, just a father.*
