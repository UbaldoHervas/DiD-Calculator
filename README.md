# Advanced Diff-in-Diff-Calculator
DiD calculator with DoubleML library

# Warnings:
1. Heurísticos
Lo implementado es en base a heurísticos. Si algo no te enacja, considera añadir covariables o ajustar.
2. Modelos ML y tuning
Se usan Random Forest y Logistic Regression con hiperparámetros fijos para simplificar. Valora hyper‑parameter tuning si necesitas algo más avanzado.
3. Otras amenazas
Revisa el contexto de tu aplicación antes de interpretar causalmente.

# La calculadora contiene:
1. Instalación
2. Carga del CSV + formato
3. Transformación ΔY
4. DoubleMLData
5. Estimación Diff-in-diff
6. Diagnóstico y resultado

Os recomiendo seguir la documentación de DoubleML: https://docs.doubleml.org/stable/index.html
También seguir mi newsletter en la que hablo de análisis causal: https://leanalytics.substack.com/
