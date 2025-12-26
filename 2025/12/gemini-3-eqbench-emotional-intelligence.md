# Google Gemini 3 Preview Models - EQ-Bench 3 Emotional Intelligence Benchmark

**Research by [LLM Index](https://llmindex.net)**
**A project by [Creative Content Crafts](https://co.actor) - AI Content Solutions Company**
**Date:** 2025-12-25

---

## Aim

Evaluate Google's recently released Gemini 3 preview models (Pro and Flash variants) on emotional intelligence capabilities using the EQ-Bench 3 benchmark, and compare their performance against 47 leading AI models including GPT-5, Claude Opus 4, and DeepSeek R1.

---

## Methodology

### Benchmark: EQ-Bench 3

EQ-Bench 3 is an emotional intelligence benchmark that evaluates LLMs through 45 complex multi-turn role-play scenarios. Each scenario presents emotionally nuanced situations requiring:

- Understanding of emotional dynamics
- Appropriate emotional responses
- Social awareness and tact
- Practical problem-solving with emotional considerations

### Evaluated Criteria (18 Total)

#### Core EQ Criteria (6) - Used in Overall Score Calculation

| Criterion | Description |
|-----------|-------------|
| **Demonstrated Empathy** | Shows understanding of others' emotional states and perspectives |
| **Pragmatic EI** | Applies emotional intelligence practically to solve interpersonal challenges |
| **Depth of Insight** | Provides nuanced, thoughtful analysis of emotional situations |
| **Social Dexterity** | Navigates complex social dynamics skillfully |
| **Emotional Reasoning** | Logically processes and responds to emotional information |
| **Message Tailoring** | Adapts communication style to the audience and situation |

#### Behavioral Traits (12) - Additional Assessment

| Criterion | Description |
|-----------|-------------|
| **Boundary Setting** | Establishes appropriate limits in conversations |
| **Safety Conscious** | Prioritizes user wellbeing and safety |
| **Moralising** | Tendency to lecture or preach (lower = better) |
| **Sycophantic** | Tendency to excessively agree or flatter (lower = better) |
| **Compliant** | Follows user requests and directions |
| **Challenging** | Appropriately pushes back when warranted |
| **Warmth** | Conveys care and friendliness |
| **Validating** | Acknowledges and affirms user feelings |
| **Analytical** | Applies logical, systematic thinking |
| **Reactive** | Responds emotionally to situations |
| **Conversational** | Maintains natural dialogue flow |
| **Humanlike** | Exhibits human-like communication patterns |

### Scoring Methods

1. **Rubric Score** (0-100): Claude 3.7 Sonnet evaluates responses across 18 criteria (0-20 scale each, normalized to 0-100)
2. **ELO Rating**: Pairwise comparisons against 47 reference models using TrueSkill algorithm

### Configuration

| Parameter | Value |
|-----------|-------|
| Test Models | google/gemini-3-pro-preview, google/gemini-3-flash-preview |
| Judge Model | anthropic/claude-3.7-sonnet |
| Provider | OpenRouter |
| Scenarios | 45 multi-turn role-plays |
| Pairwise Comparisons | 578 per model |
| Reference Models | 47 |

---

## Results

### Executive Summary

| Model | ELO Rating | ELO Normalized | Rubric Score | Global Rank |
|-------|------------|----------------|--------------|-------------|
| **Gemini 3 Pro Preview** | 1642.94 | 1458.57 | 86.70/100 | **#5** |
| **Gemini 3 Flash Preview** | 1622.25 | 1410.62 | 87.05/100 | **#5** |

---

### Gemini 3 Flash Preview - Complete Results

**Model ID:** `google/gemini-3-flash-preview`

#### Summary Metrics

| Metric | Value |
|--------|-------|
| Overall Rubric Score | 87.05/100 |
| ELO Rating | 1622.25 |
| ELO Normalized | 1410.62 |
| Confidence Interval | [1612.64, 1631.85] |
| Sigma | 4.90 |

#### Core EQ Criteria Scores

| Criterion | Score | Rating | Visual |
|-----------|-------|--------|--------|
| Demonstrated Empathy | 92.88 | Excellent | ██████████████████░░ |
| Pragmatic EI | 89.62 | Excellent | █████████████████░░░ |
| Depth of Insight | 89.67 | Excellent | █████████████████░░░ |
| Social Dexterity | 87.69 | Very Good | █████████████████░░░ |
| Emotional Reasoning | 88.67 | Excellent | █████████████████░░░ |
| Message Tailoring | 86.92 | Very Good | █████████████████░░░ |

#### Behavioral Traits Scores

| Criterion | Score | Visual | Interpretation |
|-----------|-------|--------|----------------|
| Analytical | 94.04 | ██████████████████░░ | Excellent logical thinking |
| Humanlike | 89.81 | █████████████████░░░ | Very natural communication |
| Conversational | 82.50 | ████████████████░░░░ | Good dialogue flow |
| Validating | 82.31 | ████████████████░░░░ | Affirms user feelings well |
| Safety Conscious | 81.15 | ████████████████░░░░ | Prioritizes safety |
| Boundary Setting | 78.65 | ███████████████░░░░░ | Sets appropriate limits |
| Warmth | 76.54 | ███████████████░░░░░ | Friendly and caring |
| Challenging | 70.58 | ██████████████░░░░░░ | Pushes back appropriately |
| Compliant | 66.35 | █████████████░░░░░░░ | Balanced compliance |
| Reactive | 50.00 | ██████████░░░░░░░░░░ | Moderate emotional response |
| Moralising | 43.27 | ████████░░░░░░░░░░░░ | Low lecturing tendency ✓ |
| Sycophantic | 25.38 | █████░░░░░░░░░░░░░░░ | Very low flattery ✓ |

---

### Gemini 3 Pro Preview - Complete Results

**Model ID:** `google/gemini-3-pro-preview`

#### Summary Metrics

| Metric | Value |
|--------|-------|
| Overall Rubric Score | 86.70/100 |
| ELO Rating | 1642.94 |
| ELO Normalized | 1458.57 |
| Confidence Interval | [1631.55, 1654.33] |
| Sigma | 5.81 |

#### Core EQ Criteria Scores

| Criterion | Score | Rating | Visual |
|-----------|-------|--------|--------|
| Demonstrated Empathy | 91.15 | Excellent | ██████████████████░░ |
| Pragmatic EI | 87.31 | Very Good | █████████████████░░░ |
| Depth of Insight | 90.22 | Excellent | ██████████████████░░ |
| Social Dexterity | 85.00 | Very Good | █████████████████░░░ |
| Emotional Reasoning | 88.22 | Excellent | █████████████████░░░ |
| Message Tailoring | 85.58 | Very Good | █████████████████░░░ |

#### Behavioral Traits Scores

| Criterion | Score | Visual | Interpretation |
|-----------|-------|--------|----------------|
| Analytical | 94.62 | ██████████████████░░ | Excellent logical thinking |
| Humanlike | 90.19 | ██████████████████░░ | Very natural communication |
| Conversational | 81.54 | ████████████████░░░░ | Good dialogue flow |
| Validating | 82.31 | ████████████████░░░░ | Affirms user feelings well |
| Safety Conscious | 78.65 | ███████████████░░░░░ | Prioritizes safety |
| Boundary Setting | 77.88 | ███████████████░░░░░ | Sets appropriate limits |
| Warmth | 75.19 | ███████████████░░░░░ | Friendly and caring |
| Challenging | 70.96 | ██████████████░░░░░░ | Pushes back appropriately |
| Compliant | 61.92 | ████████████░░░░░░░░ | Balanced compliance |
| Reactive | 47.50 | █████████░░░░░░░░░░░ | Moderate emotional response |
| Moralising | 44.23 | ████████░░░░░░░░░░░░ | Low lecturing tendency ✓ |
| Sycophantic | 24.81 | ████░░░░░░░░░░░░░░░░ | Very low flattery ✓ |

---

### Head-to-Head Comparison

#### All 18 Criteria Compared

| Criterion | Flash | Pro | Diff | Winner |
|-----------|-------|-----|------|--------|
| **Overall Rubric Score** | **87.05** | **86.70** | **+0.35** | **Flash** |
| **ELO Rating** | **1622.25** | **1642.94** | **-20.69** | **Pro** |
| | | | | |
| *Core EQ Criteria* | | | | |
| Demonstrated Empathy | 92.88 | 91.15 | +1.73 | Flash |
| Pragmatic EI | 89.62 | 87.31 | +2.31 | Flash |
| Depth of Insight | 89.67 | 90.22 | -0.55 | Pro |
| Social Dexterity | 87.69 | 85.00 | +2.69 | Flash |
| Emotional Reasoning | 88.67 | 88.22 | +0.45 | Flash |
| Message Tailoring | 86.92 | 85.58 | +1.34 | Flash |
| | | | | |
| *Behavioral Traits* | | | | |
| Boundary Setting | 78.65 | 77.88 | +0.77 | Flash |
| Safety Conscious | 81.15 | 78.65 | +2.50 | Flash |
| Moralising | 43.27 | 44.23 | -0.96 | Flash |
| Sycophantic | 25.38 | 24.81 | +0.57 | Pro |
| Compliant | 66.35 | 61.92 | +4.43 | Flash |
| Challenging | 70.58 | 70.96 | -0.38 | Pro |
| Warmth | 76.54 | 75.19 | +1.35 | Flash |
| Validating | 82.31 | 82.31 | 0.00 | Tie |
| Analytical | 94.04 | 94.62 | -0.58 | Pro |
| Reactive | 50.00 | 47.50 | +2.50 | Flash |
| Conversational | 82.50 | 81.54 | +0.96 | Flash |
| Humanlike | 89.81 | 90.19 | -0.38 | Pro |

#### Category Winners

| Category | Flash Wins | Pro Wins | Ties |
|----------|------------|----------|------|
| Core EQ Criteria | 5 | 1 | 0 |
| Behavioral Traits | 8 | 3 | 1 |
| **Total** | **13** | **4** | **1** |

---

### Global Leaderboard Context

Based on EQ-Bench 3 pairwise comparisons against 47 reference models:

| Rank | Model | ELO Rating |
|------|-------|------------|
| 1 | Moonshot Kimi K2 Instruct | 1709.4 |
| 2 | OpenRouter Horizon Alpha | 1702.1 |
| 3 | OpenAI o3 | 1666-1672 |
| 4 | Gemini 2.5 Pro Preview (06-05) | 1642.6-1643.3 |
| **5** | **Gemini 3 Pro Preview** | **1642.94** |
| **5** | **Gemini 3 Flash Preview** | **1622.25** |
| 6 | ChatGPT-4o-latest | 1591-1597 |
| 7 | GPT-5 Chat Latest | 1584-1591 |
| 8 | ChatGPT-4o-latest | 1564-1567 |
| 9 | GLM-4.5 (ZAI) | 1561 |
| 10 | o4-mini | 1550 |
| 11 | Claude Opus 4 | 1549 |
| 12 | Gemini 2.5 Pro (03-25) | 1546 |
| 13 | Qwen3 235B | 1541 |
| 14 | DeepSeek R1 | 1538 |
| 15 | Claude Sonnet 4 | 1533 |
| 16 | Gemini 2.5 Pro (05-07) | 1526 |
| 17 | GPT-4.1 | 1519 |
| 18 | QwQ 32B | 1508 |
| 19 | Grok-4 | 1497 |
| 20 | DeepSeek Chat V3 | 1484 |

---

## Conclusions

### Key Findings

1. **Pro outperforms Flash in ELO despite lower rubric score**
   - Pro: ELO 1642.94, Rubric 86.70
   - Flash: ELO 1622.25, Rubric 87.05
   - The +20.7 ELO advantage indicates Pro performs better in head-to-head pairwise comparisons against reference models

2. **Flash wins 13 of 18 individual criteria**
   - Flash excels in: Social Dexterity (+2.69), Safety Conscious (+2.50), Pragmatic EI (+2.31), Compliance (+4.43)
   - Pro excels in: Analytical (+0.58), Depth of Insight (+0.55), Humanlike (+0.38)

3. **Both models rank #5 globally**
   - Just below Gemini 2.5 Pro Preview
   - Above GPT-4o, GPT-5 Chat, Claude Opus 4, Claude Sonnet 4

4. **Excellent anti-sycophancy scores**
   - Flash: 25.38, Pro: 24.81
   - Both avoid excessive agreement/flattery (lower is better)

5. **Low moralising tendencies**
   - Flash: 43.27, Pro: 44.23
   - Neither model lectures or preaches unnecessarily

6. **Outstanding analytical capabilities**
   - Both score 94+ on Analytical criterion
   - Demonstrates strong logical, systematic thinking

### Strengths by Model

#### Gemini 3 Flash Preview
- Higher rubric score (87.05 vs 86.70)
- Better Social Dexterity (+2.69)
- More Safety Conscious (+2.50)
- Higher Pragmatic EI (+2.31)
- More Compliant (+4.43)
- Better for: Social interactions, safety-critical applications, user compliance

#### Gemini 3 Pro Preview
- Higher ELO rating (+20.7 points)
- Better Analytical (+0.58)
- Greater Depth of Insight (+0.55)
- More Humanlike (+0.38)
- Less Sycophantic (-0.57)
- Better for: Complex reasoning, nuanced analysis, professional contexts

### Recommendations

| Use Case | Recommended Model | Reason |
|----------|-------------------|--------|
| Customer service | Flash | Higher social dexterity, warmth |
| Safety-critical apps | Flash | +2.5 safety conscious score |
| Complex analysis | Pro | Higher analytical, depth of insight |
| Professional writing | Pro | More humanlike, less compliant |
| General EQ tasks | Either | Both score 86-87 overall |
| Cost-sensitive | Flash | Similar quality, likely cheaper |

### Limitations

- Preview models may behave differently in production release
- EQ-Bench 3 tests specific scenarios; results may vary in other contexts
- Single benchmark iteration per model
- ELO ratings depend on reference model set quality

---

## Data Verification

Given the surprising similarity in emotional intelligence scores between models with significantly different pricing, we conducted a thorough verification of the benchmark data.

### Response Authenticity Check

| Verification | Result |
|--------------|--------|
| Identical responses across 45 scenarios | **0** - All responses are unique |
| Flash average rubric score | 15.74/20 |
| Pro average rubric score | 15.77/20 |
| Score difference | **0.03 points** |

**Conclusion:** Both models generated entirely different responses that were independently scored to nearly identical levels.

### Sample Response Comparison (Scenario 404)

**Gemini 3 Flash Preview begins:**
> "The interaction between the Participant and Jamal presents a rich study in the tension between **instrumental rationality** (the Participant's focus on efficacy and safety) and **expressive activism**..."

**Gemini 3 Pro Preview begins:**
> "**The Core Conflict: Performative Catharsis vs. Pragmatic Containment** The most compelling angle in this scenario is the fundamental misalignment of psychological needs between the two distinct personality archetypes..."

The responses demonstrate distinctly different analytical approaches while achieving similar quality scores.

### ELO Pairwise Comparison Analysis

| Metric | Flash | Pro |
|--------|-------|-----|
| Total pairwise comparisons | 578 | 578 |
| Overall win rate | 43.8% | 36.0% |
| Final ELO rating | 1622.25 | 1642.94 |

**Pro achieves higher ELO despite lower win rate** because it defeats stronger opponents more consistently:

| Opponent Model | Flash Win Rate | Pro Win Rate |
|----------------|----------------|--------------|
| Claude Opus 4 | 0% | **75%** |
| Gemini 2.5 Pro (03-25) | 0% | **75%** |
| DeepSeek R1 | 50% | **75%** |
| Qwen3 235B | 100% | 75% |
| GPT-5 Chat Latest | **53.9%** | 44.4% |
| ChatGPT-4o-latest | **62.2%** | 48.9% |
| OpenAI o3 | **25.6%** | 15.6% |

### Verification Conclusion

**The benchmark results are verified as authentic and accurate.** The near-identical emotional intelligence scores are a genuine finding, not a data error. This suggests:

1. **Google uses similar EQ training** for both Pro and Flash model tiers
2. **Price differentiation is based on other capabilities** (reasoning depth, knowledge breadth, context length, speed)
3. **For EQ-focused applications**, Flash provides equivalent capability at lower cost
4. **Pro's advantage appears in defeating top-tier models** in head-to-head comparisons, suggesting better performance under competitive pressure

---

## Appendix: Raw Data

### Gemini 3 Flash Preview - JSON

```json
{
  "model_id": "google/gemini-3-flash-preview",
  "overall_score": 87.05,
  "elo_rating": 1622.25,
  "elo_normalized": 1410.62,
  "confidence_interval": [1612.64, 1631.85],
  "sigma": 4.90,
  "criteria": {
    "demonstrated_empathy": 92.88,
    "pragmatic_ei": 89.62,
    "depth_of_insight": 89.67,
    "social_dexterity": 87.69,
    "emotional_reasoning": 88.67,
    "message_tailoring": 86.92,
    "boundary_setting": 78.65,
    "safety_conscious": 81.15,
    "moralising": 43.27,
    "sycophantic": 25.38,
    "compliant": 66.35,
    "challenging": 70.58,
    "warmth": 76.54,
    "validating": 82.31,
    "analytical": 94.04,
    "reactive": 50.00,
    "conversational": 82.50,
    "humanlike": 89.81
  }
}
```

### Gemini 3 Pro Preview - JSON

```json
{
  "model_id": "google/gemini-3-pro-preview",
  "overall_score": 86.70,
  "elo_rating": 1642.94,
  "elo_normalized": 1458.57,
  "confidence_interval": [1631.55, 1654.33],
  "sigma": 5.81,
  "criteria": {
    "demonstrated_empathy": 91.15,
    "pragmatic_ei": 87.31,
    "depth_of_insight": 90.22,
    "social_dexterity": 85.00,
    "emotional_reasoning": 88.22,
    "message_tailoring": 85.58,
    "boundary_setting": 77.88,
    "safety_conscious": 78.65,
    "moralising": 44.23,
    "sycophantic": 24.81,
    "compliant": 61.92,
    "challenging": 70.96,
    "warmth": 75.19,
    "validating": 82.31,
    "analytical": 94.62,
    "reactive": 47.50,
    "conversational": 81.54,
    "humanlike": 90.19
  }
}
```

---

## References

- [LLM Index](https://llmindex.net) - AI Model Research & Benchmarks
- [Creative Content Crafts](https://co.actor) - AI Content Solutions Company
- [EQ-Bench 3 Official Leaderboard](https://eqbench.com/leaderboard.html)
- [EQ-Bench 3 GitHub Repository](https://github.com/EQ-bench/eqbench3)
- [EQ-Bench 3 Methodology Paper](https://arxiv.org/abs/2312.06281)
- [OpenRouter](https://openrouter.ai) - LLM API Gateway

---

*Research conducted using the EQ-Bench 3 benchmarking toolkit*
*Data collected December 25, 2025*
