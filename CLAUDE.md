# Daily Research Repository Guidelines

## Overview

This repository contains AI/LLM research conducted by [LLM Index](https://llmindex.net), a project by [Creative Content Crafts](https://co.actor).

## Folder Structure

Research reports are organized by year and month:

```
/YYYY/MM/
```

Example:
```
/2025/12/gemini-3-eqbench-research.md
/2025/12/claude-4-coding-benchmark.md
/2026/01/llama-4-performance-analysis.md
```

## Report Format

Every research report MUST include the following sections:

### Header (Required)

```markdown
# [Report Title]

**Research by [LLM Index](https://llmindex.net)**
**A project by [Creative Content Crafts](https://co.actor)**
**Date:** [YYYY-MM-DD]
```

### Sections (Required)

1. **Aim** - Clear statement of research objectives
2. **Methodology** - How the research was conducted
3. **Results** - Maximum results received with data tables
4. **Conclusions** - Key takeaways and recommendations
5. **References** - Links to sources, tools, and related resources

### Template

```markdown
# [Research Title]

**Research by [LLM Index](https://llmindex.net)**
**A project by [Creative Content Crafts](https://co.actor)**
**Date:** YYYY-MM-DD

---

## Aim

[Clear statement of what this research aims to discover or measure]

---

## Methodology

[Description of tools, benchmarks, and methods used]

---

## Results

[Data tables, scores, rankings - include ALL relevant metrics]

---

## Conclusions

[Key findings, recommendations, and insights]

---

## References

- [LLM Index](https://llmindex.net)
- [Creative Content Crafts](https://co.actor)
- [Additional sources...]
```

## Naming Convention

Files should be named using kebab-case:
- `model-name-benchmark-type.md`
- Example: `gemini-3-eqbench-emotional-intelligence.md`

## Commit Messages

Use descriptive commit messages:
- `Add: [model] [benchmark] research`
- `Update: [model] results with new data`
- `Fix: corrections to [report name]`
