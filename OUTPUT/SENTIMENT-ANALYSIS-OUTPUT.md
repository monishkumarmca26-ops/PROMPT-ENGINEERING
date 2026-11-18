# Sentiment Analysis – Output Evaluation

## Project Information
- **Project:** E-Commerce Sentiment Analysis
- **Prompt Version:** 1.0
- **Model Tested:** [Enter model name]
- **Testing Date:** [Enter date]

---

## Test Case 1 – Positive Sentiment

**Input:**
> The product quality is excellent. I am very happy with my purchase.

**Expected Output:**
```text
Positive
```

**Actual Output:**
```text
Positive
```

**Status:** PASS

---

## Test Case 2 – Negative Sentiment

**Input:**
> The product stopped working after two days. Very disappointed.

**Expected Output:**
```text
Negative
```

**Actual Output:**
```text
Negative
```

**Status:** PASS

---

## Test Case 3 – Neutral Sentiment

**Input:**
> The package arrived yesterday.

**Expected Output:**
```text
Neutral
```

**Actual Output:**
```text
Neutral
```

**Status:** PASS

---

## Test Case 4 – Mixed Sentiment

**Input:**
> The camera quality is excellent, but the battery performance is terrible.

**Expected Output:**
```text
Negative
```

**Actual Output:**
```text
Negative
```

**Status:** PASS

---

## Evaluation Summary

| Metric | Result |
|---|---|
| Total test cases | 4 |
| Passed | 4 |
| Failed | 0 |
| Accuracy | 100% |

*Note: Illustrative test results. Replace these with actual results obtained by running your prompt.*

## Observations
- Correctly identifies positive sentiment.
- Detects negative sentiment.
- Handles neutral statements.
- Identifies mixed sentiment.

## Future Improvements
- Test sarcasm.
- Test complex negation.
- Test ambiguous customer reviews.
