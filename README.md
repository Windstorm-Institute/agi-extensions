# Paper 7: The Throughput Basin Origin

**Four Orthogonal Experiments on Whether Serial Decoding Convergence Is Architectural, Thermodynamic, or Data-Driven**

**Status:** Complete. Formal draft published with internal adversarial review attached. Paper 7.1 follow-up experiments scoped.

---

## ⚠ Read this first

This paper is published together with its full **internal adversarial review**, which identifies four blocking issues that constrain how strongly the present results can be read. The defensible claim is narrower than the original headline.

> **Defensible claim:** *At 92M parameters, on Markov synthetic data with corpus-specific BPE tokenizers, training-data token entropy is the dominant predictor of achieved BPT, and we find no positive evidence of a transformer-specific ~4-bit ceiling in this regime.*

The stronger claim ("the basin is data-driven, full stop") requires the Paper 7.1 re-runs.

## Canonical repository

All code, data, results, the manuscript, and the unredacted adversarial review live at:

**→ [github.com/sneakyfree/agi-extensions](https://github.com/sneakyfree/agi-extensions)**

This Windstorm-Institute repository exists as a stable institutional pointer. The active work happens in the canonical repo above.

## Key links

- **Formal manuscript (v1.2 PDF):** [`Paper7-Throughput-Basin-Origin-v1.2.pdf`](https://github.com/sneakyfree/agi-extensions/blob/main/paper/Paper7-Throughput-Basin-Origin-v1.2.pdf)
- **Internal adversarial review:** [`review/adversarial_review.md`](https://github.com/sneakyfree/agi-extensions/blob/main/review/adversarial_review.md)
- **Paper 7.1 tracking issue:** [sneakyfree/agi-extensions#1](https://github.com/sneakyfree/agi-extensions/issues/1)
- **Long-form companion article:** [The Mirror, Not the Wall](https://windstorminstitute.org/articles/throughput-basin-origin.html)

## In context

- **Papers 1–6** (the Windstorm research arc through the Inherited Constraint hypothesis): [`Windstorm-Institute/fons-constraint`](https://github.com/Windstorm-Institute/fons-constraint)
- **Experiment code mirror:** [`Windstorm-Labs/agi-extensions`](https://github.com/Windstorm-Labs/agi-extensions)
- **Website:** [windstorminstitute.org](https://windstorminstitute.org)
