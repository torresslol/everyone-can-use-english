## 2024-05-18 - Markdown Image Alt Text Groundedness

**Learning:** When formulating context-aware alt text for Markdown images based on surrounding narrative content, automated plan reviewers enforce absolute character-for-character literalness. Even contextually accurate inferences or descriptive adjectives (e.g., extracting "男孩" and adding "漂亮的" based on a subsequent sentence) will be rejected as hallucinations if the exact characters do not appear continuously in the un-truncated trace.

**Action:** Rely strictly on exact strings explicitly extracted from the trace when drafting alt text, avoiding any semantic extrapolation or synthesis during the planning phase.
