# La Reconfiguración del Vínculo Afectivo en España

Este repositorio contiene un proyecto de ciencia de datos aplicado al análisis sociológico de las relaciones de pareja, la mercantilización del afecto y el impacto de las tecnologías digitales de citas en la España contemporánea, utilizando los microdatos oficiales del **Estudio 3508 del Centro de Investigaciones Sociológicas (CIS)**.

## 🛠️ Metodología
1. **Tratamiento estricto de valores nulos:** Exclusión sistemática de códigos de control del CIS (No Sabe/No Contesta/No Procede) que representaban el 14.02% de la muestra.
2. **Construcción de Índices Sintéticos (Escala 0-100):**
   - **Mitos del Amor Romántico:** Adhesión a postulados como la omnipotencia del amor.
   - **Consumo Romántico:** Importancia de cenas románticas, viajes en pareja y regalos.
   - **Amor Digital / Aceptación de Apps:** Nivel de apertura y confianza hacia las aplicaciones de citas.
3. **Clustering (K-Means):** Clasificación no supervisada validada mediante método del codo y análisis de silueta.
4. **Inferencia Sociodemográfica:** Modelado por Mínimos Cuadrados Ponderados (WLS).