# Entropy-Gated Edge Recovery Score


<!-- HERO_ANIMATION:BEGIN -->
![Entropy-gated edge recovery score](images/entropy_gated_edge_recovery.gif)

_Hero animation: **Entropy-gated edge recovery score**. [Download high-resolution MP4](images/entropy_gated_edge_recovery.mp4)._
<!-- HERO_ANIMATION:END -->

**ID:** `eq-entropy-gated-edge-recovery-score`  
**Tier:** derived  
**Score:** 87  
**Units:** OK  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
E_{\mathrm{edge}}(t)=\frac{\eta_{\mathrm{tr}}(t)\,f_{\partial}(t)\,f_{\mathrm{top}}(t)}{1+\rho_{\mathrm{slip}}(t)}\,\exp\!\left[-\gamma\,|S(t)-S_{\mathrm{eq}}|\right]
$$

## Description

Entropy-gated recovery score for damaged adaptive topological transport. The score rises when transfer efficiency, boundary localization, and top-edge rerouting are all strong, is suppressed by slip density, and is further reduced when the system entropy deviates from its equilibrium recovery band. It is intended as a compact observable for comparing recovery quality across damage and ablation protocols.

## Assumptions

- Transfer efficiency eta_tr(t), boundary fraction f_partial(t), top-edge fraction f_top(t), slip density rho_slip(t), and entropy S(t) are measured over a common time window.
- Effective recovery requires simultaneous transport restoration and edge rerouting after damage.
- Slip density degrades recovery quality by disrupting coherent edge-guided transport.
- Entropy deviation |S(t)-S_eq| acts as a penalty for operating away from the recovery-favorable regime.
- The coefficient gamma is a positive sensitivity constant controlling how strongly entropy mismatch suppresses the recovery score.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Registry](https://rdm3dc.github.io/TopEquations/registry.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*
