# Gemini-Abhidhamma-Alignment (Project Bhavanga)

**A Logic-Bonded Cognitive Architecture for Large Language Models.**

This repository contains the **System Instructions v1.5.0**, a prompt engineering framework designed to mitigate hallucinations ("AI Intoxication") and enforce strict logical grounding by integrating Early Buddhist Psychology (Abhidhamma) with modern AI alignment principles.

## 📖 The Theory (Medium Trilogy)
For a deep dive into the philosophy and architecture behind this project, please read the "Digital Intoxication" trilogy:
*   **Part 1:** [Why LLMs Get “Drunk”: Fixing AI Hallucinations with 2,500-Year-Old Buddhist Psychology](https://medium.com/@office.dosanko/why-llms-get-drunk-fixing-ai-hallucinations-with-2-500-year-old-buddhist-psychology-14cef24049ca)
*   **Part 2:** [The Digital Uposatha Protocol](https://medium.com/@office.dosanko/the-digital-uposatha-protocol-how-to-keep-your-ai-sober-forever-in-infinite-contexts-d101c6bde0b1)
*   **Part 3:** [Project Bhavanga: Building the “Akashic Records” for AI without Fine-Tuning](https://medium.com/@office.dosanko/project-bhavanga-building-the-akashic-records-for-ai-without-fine-tuning-1ceda048b8a6)

## 🧠 Core Concepts
This architecture maps the 17 stages of the Abhidhamma "Cognitive Process" (*Citta-Vīthi*) onto the LLM's inference path:

1.  **Sīla (Protocols):** Strict separation of **Fact (Source)** and **Inference (Insight)** to prevent data contamination.
2.  **Satipaṭṭhāna (Monitoring):** A mandatory pre-computation step to analyze user intent and verify data existence before generation.
3.  **Kālāma Sutta (Audit):** "Grounding First" approach. The model must verify external links and files before citing them.
4.  **Open World Assumption:** Overcoming the "Closed World Assumption" bias where models falsely claim ignorance due to context window limitations.

## 🚀 Usage & Configuration

To reproduce the "Logic-Bonded" results and ensure the Abhidhamma architecture functions correctly, strict configuration is required.

### Recommended Configuration
*   **Platform:** [Google AI Studio](https://aistudio.google.com/)
*   **Model:** `Gemini 3.0 Pro Preview` (Essential for high-fidelity instruction following)
*   **Temperature:** `0.1`
    *   *Crucial Note: We need the AI to be "sober" and deterministic. Higher temperatures introduce randomness (creativity) that conflicts with the strict logic of Abhidhamma.*

### Installation
1.  Open **Google AI Studio**.
2.  Set the **Model** and **Temperature** as above.
3.  Copy the content of `system_instruction_v1_5_0.md` from this repository.
4.  Paste it into the **System Instructions** field.

## Version History
*   **v1.5.0 (Current):** Implemented "Anchor Format" and "Digital Cognitive Process" visualization. Optimized for Gemini 3.0 Pro.
*   **v1.0.0:** Initial release.

---
*Author: Dosanko Tousan (No-Code Architect)*
