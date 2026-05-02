# Documentation-Derived Clinical Intelligence

**VitaSignal LLC** | Clinical AI Research Platform

A validated, documentation-derived clinical AI platform combining three predictive modules — IDI, DBS, and SEDR — to transform routine EHR documentation patterns into actionable clinical risk signals across ICU populations.

---

## Platform Overview

This repository supports the integrated platform paper:

> *Documentation-Derived Clinical Intelligence: Validating IDI, DBS, and SEDR Across ICU Populations*
> Pacific Symposium on Biocomputing (PSB) 2027

The platform unifies three independently validated modules into a cohesive documentation-derived clinical intelligence system.

---

## Modules

### 1. Intensive Documentation Index (IDI)
Quantifies the rhythm, density, and completeness of ICU nursing documentation as a predictive signal for mortality and clinical deterioration.

- Validated across MIMIC-IV and HiRID multicohort ICU populations
- Outperforms APACHE IV on documentation-dense patient subgroups
- Temporal validation published: *medRxiv*, February 2026

### 2. Documentation Burden Score (DBS)
Measures documentation workload as a structural signal for nurse-sensitive outcomes (NSOs), burnout risk, and staffing strain.

- Feature set: entry frequency, shift-level volume, cross-shift carryover, note complexity
- Validated on N=1,878 heart failure ICU stays (MIMIC-IV)
- AUROC 0.739 vs. 0.571 baseline (+0.168, p=0.001)

### 3. Shift-End Deterioration Risk (SEDR)
Predicts end-of-shift patient deterioration using documentation pattern features captured during the shift, enabling proactive handoff risk stratification.

- Period-level AUROC validated across temporal cohorts
- Submitted: *npj Digital Medicine*, 2026

---

## Related Repositories

- [Intensive-Documentation-Index](https://github.com/colla00/Intensive-Documentation-Index)
- [VitaSignal-SEDR](https://github.com/colla00/VitaSignal-SEDR) *(if applicable)*

---

## Citation

If you use this work, please cite:

```
Collier, A.M. (2026). Documentation-Derived Clinical Intelligence: Validating IDI, DBS,
and SEDR Across ICU Populations. Pacific Symposium on Biocomputing 2027.
```

---

## About VitaSignal

VitaSignal LLC develops fairness-preserving clinical decision support tools backed by NIH funding. Our mission is to improve patient outcomes through equitable, documentation-derived clinical AI.

- Website: [vitasignal.ai](https://vitasignal.ai)
- NIH AIM-AHEAD CLINAQ Fellow | Award No. 1OT2OD032581
- Principal Investigator: Alexis M. Collier, DHA

---

## License

© 2026 VitaSignal LLC. All rights reserved. Patent applications pending.
