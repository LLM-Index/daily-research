# Google Gemini 3 Preview Models - EQ-Bench 3 Emotional Intelligence Benchmark

**Research by [LLM Index](https://llmindex.net)**
**A project by [Creative Content Crafts](https://co.actor)**
**Date:** 2025-12-25

---

## Aim

Evaluate Google's newly released Gemini 3 preview models (Pro and Flash variants) on emotional intelligence capabilities using the EQ-Bench 3 benchmark, and compare their performance against 47 leading AI models including GPT-5, Claude Opus 4, and DeepSeek R1.

---

## Methodology

### Benchmark: EQ-Bench 3

EQ-Bench 3 evaluates LLMs through 45 complex multi-turn role-play scenarios testing:

- **Demonstrated Empathy** - Understanding others' emotional states
- **Pragmatic EI** - Practical application of emotional intelligence
- **Depth of Insight** - Nuanced analysis of emotional situations
- **Social Dexterity** - Navigation of complex social dynamics
- **Emotional Reasoning** - Logical processing of emotional information
- **Message Tailoring** - Adapting communication style appropriately

### Scoring Methods

1. **Rubric Score** (0-20): Claude 3.7 Sonnet evaluates responses across 18 criteria
2. **ELO Rating**: Pairwise comparisons against 47 reference models using TrueSkill algorithm

### Configuration

| Parameter | Value |
|-----------|-------|
| Test Models | google/gemini-3-pro-preview, google/gemini-3-flash-preview |
| Judge Model | anthropic/claude-3.7-sonnet |
| Provider | OpenRouter |
| Pairwise Comparisons | 578 per model |
| Reference Models | 47 |

---

## Results

### Summary

| Model | ELO Rating | ELO Normalized | Rubric Score | Global Rank |
|-------|------------|----------------|--------------|-------------|
| **Gemini 3 Pro Preview** | 1642.94 | 1458.57 | 17.27/20 (86.35%) | **#5** |
| **Gemini 3 Flash Preview** | 1622.25 | 1410.62 | 17.33/20 (86.65%) | **#5** |

### Detailed Metrics

#### Gemini 3 Pro Preview

| Metric | Value |
|--------|-------|
| Model ID | google/gemini-3-pro-preview |
| ELO Rating | 1642.94 |
| ELO Normalized | 1458.57 |
| Confidence Interval | [1631.55, 1654.33] |
| Sigma | 5.81 |
| Rubric Score | 17.27/20 (86.35%) |

#### Gemini 3 Flash Preview

| Metric | Value |
|--------|-------|
| Model ID | google/gemini-3-flash-preview |
| ELO Rating | 1622.25 |
| ELO Normalized | 1410.62 |
| Confidence Interval | [1612.64, 1631.85] |
| Sigma | 4.90 |
| Rubric Score | 17.33/20 (86.65%) |

### Global Leaderboard Context

Based on EQ-Bench 3 pairwise comparisons against 47 reference models:

| Rank | Model | ELO Rating |
|------|-------|------------|
| 1 | Moonshot Kimi K2 Instruct | 1709 |
| 2 | OpenRouter Horizon Alpha | 1702 |
| 3 | OpenAI o3 | 1666-1672 |
| 4 | Gemini 2.5 Pro Preview | 1643 |
| **5** | **Gemini 3 Pro Preview** | **1643** |
| **5** | **Gemini 3 Flash Preview** | **1622** |
| 6 | ChatGPT-4o-latest | 1591-1597 |
| 7 | GPT-5 Chat Latest | 1584-1591 |
| 8 | ChatGPT-4o-latest | 1564-1567 |
| 9 | GLM-4.5 | 1561 |
| 10 | o4-mini | 1550 |
| 11 | Claude Opus 4 | 1549 |
| 12 | Gemini 2.5 Pro (03-25) | 1546 |
| 13 | Qwen3 235B | 1541 |
| 14 | DeepSeek R1 | 1538 |
| 15 | Claude Sonnet 4 | 1533 |

---

## Conclusions

### Key Findings

1. **Pro outperforms Flash in ELO (+20.7 points)** - Despite Flash having a marginally higher rubric score (17.33 vs 17.27), Pro achieves a significantly higher ELO rating, indicating stronger performance in head-to-head comparisons against reference models.

2. **Both models rank #5 globally** - Placing just below Gemini 2.5 Pro and above GPT-4o, ChatGPT-4o-latest, and Claude Opus 4.

3. **Competitive with flagship models** - Both Gemini 3 previews outperform GPT-5 Chat, Claude Sonnet 4, and DeepSeek R1 in emotional intelligence.

4. **Gemini 2.5 Pro remains slightly ahead** - The 2.5 Pro still edges out 3 Pro by a small margin (~0.4 ELO points).

### Recommendations

| Use Case | Recommended Model |
|----------|-------------------|
| EQ-sensitive applications | Gemini 3 Pro Preview |
| Cost-effective EQ tasks | Gemini 3 Flash Preview |
| Maximum EQ performance | Moonshot Kimi K2 or OpenRouter Horizon Alpha |

### Limitations

- Preview models may have different behavior in production release
- EQ-Bench 3 tests specific emotional intelligence scenarios; results may vary in other contexts
- Single benchmark iteration; recommend multiple runs for production decisions

---

## References

- [LLM Index](https://llmindex.net) - AI Model Research & Benchmarks
- [Creative Content Crafts](https://co.actor) - AI Solutions Company
- [EQ-Bench 3 Official Leaderboard](https://eqbench.com/leaderboard.html)
- [EQ-Bench 3 GitHub Repository](https://github.com/EQ-bench/eqbench3)
- [OpenRouter](https://openrouter.ai) - LLM API Gateway

---

*Research conducted using the EQ-Bench 3 benchmarking toolkit*
*Data collected December 25, 2025*
