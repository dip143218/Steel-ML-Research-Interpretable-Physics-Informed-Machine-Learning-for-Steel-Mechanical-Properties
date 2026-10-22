STEEL MECHANICAL-PROPERTY SHAP ANALYSIS
=======================================

Targets: yield strength, tensile strength, elongation
Method: model-agnostic permutation SHAP
No cross-validation was run in this cell.

Selected feature sets:
- Yield strength: Raw 13 features
- Tensile strength: Raw 13 features
- Elongation: Raw 13 + 3 proxy descriptors

IMPORTANT LIMITATIONS:
1. Models were fitted on all usable rows for interpretation.
2. SHAP explanations are not independent validation.
3. Mean absolute SHAP measures attribution magnitude, not causality.
4. Positive mean SHAP is not proof that a feature always increases the target; use beeswarm and dependence plots to inspect direction.
5. Proxy descriptors are composition-based estimates, not direct measurements of physical properties.
6. Results can depend on the selected background sample.
