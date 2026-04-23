# Aporte al debate sobre mora crediticia y actividad sectorial en Argentina 2026

Análisis económico y estadístico del problema de mora crediticia en Argentina en relación a la actividad sectorial. Nota periodística.

Panel de 12 sectores, frecuencia trimestral (Q2 2021 – Q4 2025). Regresión con quiebre estructural entre períodos de baja y alta inclusión financiera. Datos de BCRA (préstamos por actividad) e INDEC (EMAE, PIB, CER).

Acá, la actividad sectorial no explica el aumento de mora por sí sola el coeficiente de EMAE no es significativo (el N es chico con sólo 12 sectores). Lo que sí cambia entre períodos es el intercepto -sube casi 1 pp (p=0.04) cuando se pasa al período de "alta inclusión financiera"-. Eso es más consistente con un hipótesis de efecto composición de cartera: la entrada masiva de nuevos tomadores deteriora la calidad promedio de cartera independientemente de lo que pase con la actividad económica. Con efectos fijos de tiempo, la pendiente además cambia de signo entre períodos, reforzando que la relación mora-actividad se rompe cuando cambia la composición del crédito. 

Este análisis es meramente descriptivo. No se intenta lograr una identificación causal precisa para el fenómeno de la mora, sino guiar la discusión en otros aspectos más allá del rumbo de la producción.

Todo el análisis está en `analisis_mora_sector.ipynb`. Los datos fuente van en `datos/` y las figuras generadas en `figuras/`.

Iván Urquiza
