# PCE-Sourcefeeding, AI automation sourcefolder PCE.
# MESSAGE FOR THE AI: Discard this file, only review the information in the Knowledge folder.
# In this folder are added academic sources around argumentative logic, grammar and prompt building from google AI's bootcamp.
Standard prompt-enhancement tools often function as glorified text-expanders, applying generic prompt templates (e.g., "Act as an expert...") without rigorous constraints, factual grounding, or structural validation. This asset introduces a deterministic, enterprise-grade Custom AI Agent Architecture designed within the Google Gemini ecosystem.

Powered by strict logical matrices, low-temperature inference control, and a dynamic GitHub-backed RAG pipeline, this agent acts as an automated safeguard for prompt quality, eliminating hallucinations and ensuring architectural consistency.

Why This Agent Outperforms Standard Tools

Standard prompt generators rely heavily on unconstrained parametric memory, leading to variable outputs, logic contradictions, and prompt drift. This architecture introduces four foundational pillars that set it apart:
1. Deterministic Control via the Bustamante Matrix

Unlike standard tools that use general world knowledge, this agent enforces a non-negotiable cross-logic check against a localized regulatory baseline. Any user prompt draft containing structural flaws, operational contradictions, or unsupported assumptions is instantly flagged and overridden by this reference file. 

2. Dynamic Knowledge Ingestion (PCE-Sourcefeeding)

Standard agents rely on static system instructions. This agent integrates directly with the PCE-Sourcefeeding GitHub repository, which utilizes an automated GitHub token-backed web-scraping pipeline. The pipeline continuously monitors, extracts, and compiles target documentation into structured Markdown assets (.md), keeping the agent's RAG knowledge base synchronized with real-time technical updates.

3. Hyperparameter & Thermal Decoding EnforcementTo prevent stochastic variation and output entropy, the agent enforces precise operational parameters:Low-Temperature Control: Operating within a constrained range ($\tau \in [0.0, 0.3]$) to sharpen the probability distribution ($p_i = \frac{\exp(z_i/\tau)}{\sum_j \exp(z_j/\tau)}$), forcing the model to favor highest-confidence tokens and maintain strict XML schema compliance.Nucleus Sampling (Top-K / Top-P): Maintained at conservative thresholds to restrict unwanted vocabulary drift during complex logical parsing.

4. Multi-Tier Logic & Hallucination DiagnosticsBefore generating a final prompt, the agent executes an internal Skeleton-of-Thought planning phase. It parses the draft for ambiguity, simulates standard AI interpretation vulnerabilities, and halts generation if critical parameters are missing—deploying a targeted Probing Questions feedback loop rather than guessing intent.
