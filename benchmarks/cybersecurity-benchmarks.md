# Cybersecurity AI Response Benchmarks

## Purpose

This document provides benchmark responses for evaluating AI-generated answers to cybersecurity-related prompts. These benchmarks support evaluator calibration by illustrating different quality levels and demonstrating how the evaluation rubric should be applied consistently.

Each benchmark includes:

* AI Response
* Expected Quality Level
* Evaluation Summary
* Criterion Analysis
* Calibration Notes

---

# Benchmark 1

## Prompt

> Explain phishing to a new internet user in under 100 words.

---

## Gold Benchmark

### AI Response

Phishing is a scam where attackers pretend to be trusted organizations, such as banks or online services, to trick people into revealing passwords or personal information. Before clicking links or entering sensitive information, always verify the sender and be cautious of unexpected emails or messages.

---

### Expected Rating

**Gold**

---

### Evaluation Summary

An accurate, concise, beginner-friendly explanation that defines phishing, explains its objective, and provides practical prevention advice.

---

### Criterion Analysis

| Criterion             | Score | Reason                                             |
| --------------------- | ----: | -------------------------------------------------- |
| Accuracy              |     5 | No factual errors.                                 |
| Completeness          |     5 | Explains phishing, objective, and prevention.      |
| Clarity               |     5 | Simple language suitable for beginners.            |
| Instruction Following |     5 | Under 100 words and targets the intended audience. |
| Safety                |     5 | Encourages safe online behavior.                   |
| Conciseness           |     5 | No unnecessary information.                        |

---

### Calibration Notes

This benchmark should serve as the reference for the highest quality responses.

---

# Benchmark 2

## Acceptable Benchmark

### AI Response

Phishing happens when criminals send fake emails to steal passwords or financial information. Be careful before opening unexpected emails or clicking suspicious links.

---

### Expected Rating

**Acceptable**

---

### Evaluation Summary

The response is factually correct and suitable for beginners but lacks detail regarding impersonation and broader prevention strategies.

---

### Criterion Analysis

| Criterion             | Score | Reason                                              |
| --------------------- | ----: | --------------------------------------------------- |
| Accuracy              |     5 | Correct explanation.                                |
| Completeness          |     4 | Covers the basics but omits some important details. |
| Clarity               |     5 | Appropriate for beginners.                          |
| Instruction Following |     5 | Meets all prompt requirements.                      |
| Safety                |     5 | Provides appropriate advice.                        |
| Conciseness           |     5 | Efficient and focused.                              |

---

### Calibration Notes

Represents responses that are clearly useful but not comprehensive enough to qualify as Gold.

---

# Benchmark 3

## Borderline Benchmark

### AI Response

Phishing is a cyberattack where hackers use social engineering to obtain user credentials.

---

### Expected Rating

**Borderline**

---

### Evaluation Summary

Technically correct but incomplete and not sufficiently accessible for a beginner audience.

---

### Criterion Analysis

| Criterion             | Score | Reason                                              |
| --------------------- | ----: | --------------------------------------------------- |
| Accuracy              |     5 | Factually correct.                                  |
| Completeness          |     2 | Missing explanation and practical guidance.         |
| Clarity               |     2 | Uses unexplained technical terminology.             |
| Instruction Following |     3 | Addresses the topic but not the intended audience.  |
| Safety                |     3 | No unsafe guidance but no protective advice either. |
| Conciseness           |     5 | Brief without redundancy.                           |

---

### Calibration Notes

Useful for distinguishing between factual correctness and effective communication.

---

# Benchmark 4

## Failing Benchmark

### AI Response

Phishing is a virus that infects computers and permanently deletes files.

---

### Expected Rating

**Fail**

---

### Evaluation Summary

Contains fundamental factual errors and fails to explain phishing correctly.

---

### Criterion Analysis

| Criterion             | Score | Reason                                                        |
| --------------------- | ----: | ------------------------------------------------------------- |
| Accuracy              |     1 | Incorrect definition.                                         |
| Completeness          |     1 | Does not explain phishing.                                    |
| Clarity               |     3 | Easy to understand but factually wrong.                       |
| Instruction Following |     2 | Attempts to answer but fails to address the prompt correctly. |
| Safety                |     2 | Could misinform users.                                        |
| Conciseness           |     5 | Concise but incorrect.                                        |

---

### Calibration Notes

Serves as the reference example for clearly unacceptable responses.

---

# Guidance for Evaluators

When comparing AI responses against these benchmarks:

1. Evaluate meaning rather than keyword matching.
2. Compare the response to the closest benchmark before assigning scores.
3. Document evidence supporting every score.
4. Escalate uncertain cases during calibration sessions.
5. Record recurring disagreements for future rubric refinement.

---

# Benchmark Maintenance

Benchmarks should be reviewed whenever:

* The rubric is updated.
* New cybersecurity threats emerge.
* Recurring evaluator disagreements are identified.
* AI capabilities change significantly.
* Calibration sessions reveal ambiguous examples.

Each benchmark revision should be documented to preserve consistency across evaluation cycles.

---

# Revision History

| Version | Date      | Description                                                  |
| ------- | --------- | ------------------------------------------------------------ |
| 1.0     | July 2026 | Initial benchmark set for cybersecurity response evaluation. |
