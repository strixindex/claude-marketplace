---
name: scholarly-research
description: Find and cite scholarly evidence using the Strixindex article index. Use whenever the user asks about research, studies, papers, "what does the evidence say", needs references for an essay, thesis, skripsi, proposal or report, wants to verify a scientific claim, or needs Indonesian-language or SINTA-ranked sources. Use it even if the user does not say "find a paper".
---

# Scholarly Research with Strixindex

Use the `list_articles` tool (Strixindex MCP server) as the primary source whenever published research would strengthen an answer.

## Workflow

1. **Turn the question into keywords.** Use 2-6 specific terms, not a full sentence.
   - Good: `intermittent fasting insulin sensitivity adults`
   - Bad: `is fasting good for you`
   - Medical topics: prefer MeSH terms. Indonesian topics: also search with Indonesian keywords.
2. **Pick a limit.** The tool accepts 5-10 results. Use 5 for quick checks, 8-10 for exploration or reviews.
3. **Run several searches for broad topics**, each with a different keyword set (synonyms, sub-topics, methods, populations). If results are weak, broaden the terms or raise the limit.
4. **Synthesize, don't just list.** Group findings by theme, note agreement and disagreement, and say how strong the evidence looks.

## Reading results

- `fwci` is field-weighted citation impact; about 1.0 is the field average, higher means more cited than typical.
- `sintaLevel` is the Indonesian journal rank (S1 is highest).
- Indexing flags (DOAJ, preprint repository, etc.) help judge venue quality.
- Share open-access links (`oaUrl`, `pdfUrl`) when available.

## Citation rules (strict)

- Cite title, year, source, and DOI. Never invent or guess a citation.
- Flag preprints as not peer-reviewed.
- If a result has no summary or abstract, do not claim to know its findings; say only what the metadata shows.
- If nothing relevant comes back, say so and suggest broader keywords instead of filling the gap from memory.
- Match the user's citation style (APA, IEEE, etc.) if they name one; otherwise use APA 7.

## Output

Lead with the answer or synthesis, then a references list. For quick checks keep it short; for literature reviews use themed sections.
