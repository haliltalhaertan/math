<a name="matematiksel-araştırmalar"></a>
# Mathematical Research

This is a **research notebook**, not a class notebook.

<a name="nasıl-çalışıyoruz"></a>
## How We Work

We don't memorize formulas here. Instead:

1. **Find a question** whose rule fits in one sentence but whose answer isn't clear.
2. **Experiment** by having a computer calculate thousands or millions of examples.
3. **Look closely** for patterns or anything unusual in the numbers.
4. **Write it down**, noting what we saw and what we still don't understand.

Mathematicians work much the same way, except that after step four
they also try to write a *proof*. Before we get there, we'll learn what to look for.

<a name="kural"></a>
## The Rule

**Don't skip anything you don't understand.** "What does this mean?" is the
most valuable question in this notebook. You can't investigate something
you don't understand. There are no stupid questions.

<a name="araştırmalar"></a>
## Investigations

| # | Topic | Status |
|---|-------|--------|
| [01](01-collatz/) | The Collatz conjecture: how numbers reach 1 | Introduction / open question |
| [02](02-cp20-task6-bagimsiz-dogrulama/) | CP20 Task 6 theorem candidate: numerical verification and literature | Numerical components and novelty checked |
| [03](03-cp17-zemin-kontrolu/) | CP17 foundational theorem: carry identities and the K17 constant | Externally verifiable claims check out |
| [04](04-cp20-task6-denetim/) | CP20 Task 6: independent zero-trust audit | `PROOF VALID WITH WORDING REPAIR` |
| [05](05-cp20-task7-denetim/) | CP20 Task 7: B=4 pressure theorem audit | `PROOF VALID WITH WORDING REPAIR` (scope) |
| [06](06-task6-guclendirme/) | Strengthening the B=3 result for Task 6 | Unaudited candidate: κ ≥ 1.585 → κ ≥ 3.028 |
| [07](07-geriye-donuk-tarama/) | Retrospective review: applying a new method to earlier results | Frontier κ ≥ 1.053 → κ ≥ 2.784; sparse-critical extension (draft) |
| [08](08-literatur-taramasi/) | Detailed literature review using primary sources | No equivalent theorem found |
| [09](09-literaturden-baglantilar/) | Approaches from the literature: applying new tools to an open problem | 5 connections; priority: Hensel digit density |
| [11](11-surekli-kesir-denetim/) | Self-audit of the continued-fraction finding | `[VALID AS OBSERVATION — ONE LEMMA MISSING]` |
| [12](12-d0-denetim/) | Independent audit of CP20 Task 8B2 D0 | `[PROOF VALID WITH WORDING REPAIR]` |
| [13](13-d1-denetim/) | Independent audit of CP20 Task 8B2 D1 | `[PROOF VALID WITH WORDING REPAIR]` + Finding D |

<a name="güncel-durum"></a>
## Current Status

**[DURUM.md](DURUM.md)** covers the theorems frozen in Drive, this
repository's contribution, and three mistakes the independent audit helped me correct.

<a name="iki-katman"></a>
## Two Levels

This notebook has two distinct levels:

- **01**: A beginner's introduction. What Collatz is, why it's hard, and examples you can work through by hand.
- **02**: An independent check of the active research frontier in the CP01–CP20 Google Drive archive. This level is technical and follows the archive's audit standards.

The audit of CP20 Task 6 is complete (04). The main theorem is valid; the
controller's bounded-tracking lemma needs a wording correction.

<a name="deneyleri-çalıştırmak"></a>
## Running the Experiments

```bash
python3 01-collatz/deney.py
```

No additional software is needed beyond Python.
