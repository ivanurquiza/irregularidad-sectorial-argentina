# Irregularidad crediticia y actividad sectorial en Argentina

¿El aumento de la mora responde a la caída de actividad por sector, o al cambio en la composición de cartera tras el boom de crédito?

Panel de 12 sectores CLANAE, frecuencia trimestral (Q2 2021 – Q4 2025). Regresión con quiebre estructural entre períodos de baja y alta inclusión financiera. Datos de BCRA (préstamos por actividad, serie 26, CER) e INDEC (EMAE, PIB corriente).

El resultado central es que la actividad sectorial no explica el aumento de mora: el coeficiente de EMAE no es significativo en ninguna especificación. Lo que sí cambia entre períodos es el intercepto — sube casi 1 pp (p=0.04) cuando se pasa al período de alta inclusión (crédito/PIB >10%). Eso es consistente con un efecto composición: la entrada masiva de nuevos tomadores deteriora la calidad promedio de cartera independientemente de lo que pase con la actividad económica. Con efectos fijos de tiempo, la pendiente además cambia de signo entre períodos, reforzando que la relación mora-actividad se rompe cuando cambia la composición del crédito.

Todo el análisis está en `analisis_mora_sector.ipynb`. Los datos fuente van en `datos/` y las figuras generadas en `figuras/`.
