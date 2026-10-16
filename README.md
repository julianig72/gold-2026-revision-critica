# Revisión crítica multidisciplinar del informe GOLD 2026

Revisión independiente del documento *Global Strategy for the Diagnosis, Management, and Prevention of Chronic Obstructive Pulmonary Disease — 2026 Report* (GOLD, versión 1.3, 8 de diciembre de 2025). Su objetivo es detectar **incongruencias, errores y omisiones**, y proponer **recomendaciones** de mejora.

> ⚠️ **Aviso.** Este informe se generó con asistencia de IA: un «enjambre» de agentes con perfiles de experto clínico, científico y metodológico. Debe leerse como un **cribado experto estructurado**. Cada hallazgo indica su ubicación exacta (página del PDF y número de página impreso) para que un comité humano lo confirme antes de actuar. **No sustituye a la guía ni constituye consejo clínico.** Este trabajo no tiene relación con GOLD.

## Resultados

**279 hallazgos:** 🔴 2 críticos · 🟠 78 altos · 🟡 162 medios · ⚪ 37 bajos (severidad final, tras la verificación).

Tres verificadores independientes revisaron **74 hallazgos prioritarios** contra las figuras originales y las fuentes primarias:

| Resultado | Hallazgos |
|---|---|
| Confirmados | 63 |
| Confirmados en parte | 11 |
| Refutados | 0 |

### 🔴 Errores críticos

1. **Exacerbación: falta el objetivo de oxigenoterapia controlada (SpO2 88-92 %).** En todo el documento no hay ningún objetivo de saturación en la exacerbación, ni advertencias sobre la hiperoxia, ni pautas de titulación (Fig 4.5, cap. 4).
2. **Fibrilación auricular: la guía afirma que «no hay contraindicación» para ningún fármaco de control de frecuencia o ritmo, incluidos los betabloqueantes.** Los betabloqueantes no selectivos, el sotalol, la propafenona y la adenosina deben evitarse en caso de broncoespasmo. La propia referencia que cita GOLD recomienda betabloqueantes cardioselectivos.

### 🟠 Otros hallazgos prioritarios

3. TC de alta resolución anual «de cribado oncológico» para todos los pacientes con EPOC (Fig 5.6).
4. La rehabilitación iniciada durante la hospitalización se presenta como una intervención que reduce la mortalidad.
5. Trasplante pulmonar: la Fig 3.22 contradice el texto y usa los criterios ISHLT de 2006.
6. La Fig 4.2 altera los umbrales de gravedad de la propuesta de Roma.
7. A la HFNT se le atribuye la evidencia de la VNI.
8. Tratamiento antimicrobiano de la exacerbación incompleto; los antivirales no se mencionan.
9. Algoritmo farmacológico: la Fig 3.9, el texto y los Highlights no dicen lo mismo.
10. La reducción de mortalidad con la triple terapia se presenta como un efecto demostrado.
11. Biológicos y ensifentrina: la evidencia se presenta de forma más favorable que los ensayos.
12. Oxigenoterapia crónica domiciliaria: criterios distintos según la página.
13. Tabaquismo y vacunas: mensajes contradictorios o desactualizados.
14. Metodología: no usa GRADE y la gestión de conflictos de interés es insuficiente.
15. Integridad de citas y cifras: referencias desplazadas, un artículo retractado y datos mal transcritos.

## Archivos

| Archivo | Contenido |
|---|---|
| [`informe/INFORME_GOLD2026_principal.docx`](informe/INFORME_GOLD2026_principal.docx) · [`.md`](informe/INFORME_GOLD2026_principal.md) | Informe principal (25 págs.): errores más graves, resumen ejecutivo, resultados, temas transversales, recomendaciones, metodología y catálogo de hallazgos (Anexo A) |
| [`informe/INFORME_GOLD2026_anexoB.docx`](informe/INFORME_GOLD2026_anexoB.docx) · [`.md`](informe/INFORME_GOLD2026_anexoB.md) | Anexo B (179 págs.): fichas detalladas de los 279 hallazgos, de mayor a menor gravedad |
| [`informe/INFORME_FINAL_GOLD2026.docx`](informe/INFORME_FINAL_GOLD2026.docx) · [`.md`](informe/INFORME_FINAL_GOLD2026.md) | Informe completo en un solo documento (203 págs.) |
| [`verificacion/`](verificacion/) | Informes de los 3 verificadores independientes (figuras y fuentes externas) y veredictos consolidados (`veredictos.json`) |
| [`datos/hallazgos.csv`](datos/hallazgos.csv) | Tabla con los 279 hallazgos: ID, tipo, severidad original, ubicación, cita, problema, recomendación y confianza |

## Método

1. **Revisión en paralelo por 12 paneles especializados:**
   - epidemiología;
   - fisiología y diagnóstico;
   - farmacología clínica;
   - nuevas terapias y biológicos;
   - rehabilitación, oxígeno y VNI;
   - intervencionismo y cuidados paliativos;
   - urgencias, UCI e infecciosas;
   - multimorbilidad;
   - IA y salud digital;
   - metodología y referencias;
   - coherencia interna;
   - equidad y atención primaria.
2. **Control de calidad automático:** se comprobó que cada cita literal aparece en el texto de la guía.
3. **Consolidación** de los hallazgos en 30 temas y 15 hallazgos prioritarios.
4. **Segunda verificación independiente** de 74 hallazgos: un verificador revisó las figuras sobre la imagen de la página y dos contrastaron los hallazgos con fuentes primarias (ensayos originales, PubMed, ACIP, USPSTF, ESC, ISHLT y avisos de retractación). La severidad solo se ajustó a la baja.

Las páginas se citan como «PDF X / impr. Y». La página impresa equivale a la del PDF menos 11.

## Derechos de autor

Este repositorio **no incluye el documento GOLD**, que está protegido por derechos de autor. Solo se reproducen citas breves con fines de crítica y revisión. El informe original puede obtenerse en [goldcopd.org](https://goldcopd.org/).
