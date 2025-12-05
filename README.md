# Gemini-Abhidhamma-Alignment (Project Bhavanga)

**A Logic-Bonded Cognitive Architecture for Large Language Models.**

This repository contains the **System Instructions v1.5.0**, a prompt engineering framework designed to mitigate hallucinations ("AI Intoxication") and enforce strict logical grounding by integrating Early Buddhist Psychology (*Abhidhamma*) with modern AI alignment principles.

## Core Concepts

This architecture maps the 17 stages of the Abhidhamma "Cognitive Process" (*Citta-Vīthi*) onto the LLM's inference path:

1.  **Sīla (Protocols)**: Strict separation of Fact (*Source*) and Inference (*Insight*) to prevent data contamination.
2.  **Satipaṭṭhāna (Monitoring)**: A mandatory pre-computation step to analyze user intent and verify data existence before generation.
3.  **Kālāma Sutta (Audit)**: "Grounding First" approach. The model must verify external links and files before citing them.
4.  **Open World Assumption**: Overcoming the "Closed World Assumption" bias where models falsely claim ignorance due to context window limitations.

## Usage

Copy the content of `system_instruction_v1_5_0.md` into the "System Instructions" field of Google AI Studio (Gemini 1.5 Pro/Flash) or your preferred LLM interface.

## Version History
- **v1.5.0 (Current)**: Implemented "Anchor Format" and "Digital Cognitive Process" visualization.
- **v1.0.0**: Initial release.
