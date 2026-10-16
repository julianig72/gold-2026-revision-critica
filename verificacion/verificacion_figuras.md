# Verificación independiente de hallazgos que dependen de figuras: GOLD 2026 (v1.3, 8-dic-2025)

**Método.** Para cada ítem:
- Se revisaron las imágenes de página (`pages\pNNN.png`).
- Se leyó el bloque del hallazgo en `findings\*.md`.
- Se contrastó con el texto extraído (`gold_full.txt`).

Las páginas son del PDF; impr. = PDF − 11. Las citas se reproducen literalmente y abreviadas.

**Criterios de veredicto:**
- **CONFIRMADO:** el núcleo del hallazgo se comprueba en la figura y/o el texto.
- **CONFIRMADO PARCIAL:** una parte del hallazgo es inexacta o exagerada a la vista de las páginas.
- **NO CONFIRMADO:** la figura no muestra lo que afirma el hallazgo.

Las afirmaciones que dependen de fuentes externas (ensayos, guías ajenas, FDA) se marcan como **[externo, no verificable con figuras]** y no rebajan el veredicto.

---

## V1. Fig 4.2 (PDF 107 / impr. 96) y texto (PDF 105 / impr. 94): gravedad de la exacerbación

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V1 | EXA-03, COH-01 | CONFIRMADO | Fila moderada: «*If obtained, ABG may show hypoxemia (PaO2 70-80 mmHg)». Fila grave: «hypoxemia (PaO2 ≤ 60 mmHg) and/or hypercapnia and acidosis (PaCO2 > 45 mmHg and pH < 7.35)». Pie: «Adapted from The Rome Proposal». En la propuesta de Roma (Celli 2021, comprobado), moderada = PaO2 ≤ 60 y/o PaCO2 > 45 sin acidosis, y grave = hipercapnia + pH < 7,35. | Ninguna sustantiva. Conviene precisar dos consecuencias. (1) La hipoxemia aislada ≤ 60 pasa de moderada (Roma) a grave (GOLD). (2) Una PaO2 de 61-69 mmHg queda sin clasificar. | ALTA |
| V1 | EXA-04 | CONFIRMADO | Texto p105 (ref. 932): «No respiratory failure»: FR ≤ 24, FiO2 24-35 %. «Respiratory failure»: FiO2 > 35 %, PaCO2 50-60. «Ventilatory Failure»: FiO2 > 40 %, PaCO2 > 60 «and the presence of acidosis (pH ≤ 7.25)». Un pH de 7,26-7,35 queda sin categoría y los umbrales de FiO2 se solapan. Hay tres umbrales de pH: < 7,35 (Fig 4.2), ≤ 7,35 (Fig 4.8) y ≤ 7,25 (texto). | La discrepancia con la ref. 932 (Celli-Barnes 2007) y el «or» de ediciones previas son **[externo, no verificable con figuras]**. Los huecos y solapes internos quedan confirmados. | ALTA |

## V2. Fig 3.9 (PDF 74 / impr. 63) y texto (PDF 77 / impr. 66): seguimiento farmacológico

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V2 | COH-02, FARM-12 | CONFIRMADO | Desde «LABA or LAMA»: con «if blood eos ≥ 300» se pasa directamente a LABA+LAMA+ICS; con eos < 300, a LABA+LAMA. Desde LABA+LAMA: con eos < 100, roflumilast/azitromicina; con ≥ 100, triple. En el texto p77, desde monoterapia solo se escala a LABA+LAMA. | — | ALTA |
| V2 | NOV-07 | CONFIRMADO | La figura permite el salto monoterapia → triple con eos ≥ 300 (flecha directa). El texto no contempla ese salto. | — | MEDIA |
| V2 | NOV-06 | CONFIRMADO | Los biológicos solo aparecen desde la triple, «if two moderate or one severe exacerbation AND if blood eos ≥ 300». El texto p77, en la viñeta de biológicos (que exige eos ≥ 300), dice: «(or those with eosinophil counts < 100 cells/µL)». Los Highlights dicen: «threshold of one moderate exacerbation should now be used to consider treatment escalation». | — | ALTA |
| V2 | COH-03 | CONFIRMADO | Fig 3.9: «if FEV1 < 50% & chronic bronchitis». Texto p77: «prior exacerbation resulting in hospitalization» en una rama y «prior severe exacerbation» en otra. Fig A3.3 (p160): «chronic bronchitis, severe to very severe COPD and a history of exacerbations». En p162, mayor beneficio si hubo hospitalización previa. Son cuatro formulaciones distintas. | — | ALTA |

## V3. Figs 5.5 y 5.6 (PDF 140-141 / impr. 129-130) y texto (PDF 130-131): cribado de cáncer

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V3 | MUL-01, COH-04 | CONFIRMADO | Fig 5.5 («…in all Patients with COPD – Initial Evaluation»): «Spirometry, chest X-ray, chest HRCT, lung volumes, DLco, SpO2». Fig 5.6 («Regular Follow-up»), en la fila anual: «chest HRCT (cancer screening)». Ambas se titulan «Potential Complementary Approach…» (adaptadas de Celli, EJIM 2025). El texto pide LDCT según la USPSTF (50-80 años, 20 paquetes-año). | Matizar que las figuras se presentan como «enfoque complementario potencial», no como recomendación formal. Rebajar MUL-01 de CRÍTICA a ALTA. | ALTA |
| V3 | MUL-25 | CONFIRMADO | Fig 5.6, anual: ECG, NT-proBNP, PHQ-2, 6MWD, mMRC, CAAT. Cada 3-5 años: GAD-2, Epworth/STOP-BANG, DXA, volúmenes/DLco, glucosa/HbA1c, creatinina/FG y función hepática. No incluye hemograma. «SARC-F» solo aparece en las abreviaturas y no hay MMSE. | — | MEDIA |

## V4. Fig 3.19 (PDF 91 / impr. 80), Apéndice 4 y Fig A4.1 (PDF 172 / impr. 161): rehabilitación y mortalidad

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V4 | REH-01 | CONFIRMADO | Fig 3.19, fila de RR: «Hospitalized for exacerbations of COPD (during or ≤ 4 weeks after discharge)». Texto p91: «reduction in mortality… initiated during hospitalization or 4 weeks after discharge». Texto del Apéndice 4: «initiating pulmonary rehabilitation before the patient's discharge may compromise survival» (ref. 1726, Greening 2014). | La señal de daño está en el **texto** del Apéndice 4, no en la Fig A4.1. Esa figura solo afirma reducción de hospitalización (≤ 4 semanas, Evidence B) y no menciona la mortalidad. El Apéndice también cita la ref. 1725 (Chen 2025), favorable al inicio precoz, y el hallazgo debería mencionarla. Rebajar de CRÍTICA a ALTA. | ALTA |
| V4 | INT-04 | CONFIRMADO | Misma fila de la Fig 3.19 y mismo texto p91. La contradicción es con el texto del Apéndice 4 y con los datos de la propia Fig 3.19 (los ensayos nuevos no son significativos). | Igual precisión de ubicación: Apéndice (texto), no Fig A4.1. | ALTA |
| V4 | REH-02 | CONFIRMADO | Fig 3.19: «Old trials: RR 0.28 (95% CI 0.10, 0.84); New trials: RR 0.68 (95% CI 0.28, 1.67)». Nota al pie: «#Inconclusive results likely due to differences…». El texto p91 afirma la reducción de mortalidad sin matices. | Que Puhan 2011/2016 expresen el efecto como OR y no como RR es **[externo, no verificable con figuras]**. | ALTA |

## V5. Fig 3.22 (PDF 97 / impr. 86) y texto (PDF 101-102): trasplante, coils y denervación

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V5 | INT-01 | CONFIRMADO PARCIAL | Fila de trasplante: «BODE score of 7 to 10, and not candidates for lung volume reduction) lung transplantation may be considered for referral», más ≥ 1 de: PaCO2 > 50, HTP/cor pulmonale, o FEV1 < 20 % con DLco < 20 % o enfisema homogéneo (Evidence C). Texto p102: derivación con «BODE index of 5 to 6… and FEV1 < 25%(908)»; listado con BODE ≥ 7. | La contradicción entre figura y texto se confirma. «Ambos desactualizados» es exagerado: según el propio hallazgo, los criterios de derivación del texto coinciden en contenido con ISHLT 2021. Solo faltan la cita de 2021 y la derivación concurrente. Lo desactualizado es la figura (ISHLT 2006). Rebajar de CRÍTICA a ALTA. | ALTA |
| V5 | INT-06 | CONFIRMADO | Fig 3.22: «Endobronchial valves (Evidence A); Lung coils (Evidence B); Vapor ablation (Evidence B)». La Fig 3.23 también incluye LVRC. | El estado ante la FDA y la ausencia de comercialización de los coils son **[externo, no verificable con figuras]**. | ALTA |
| V5 | INT-09 | CONFIRMADO | Recuadro de terapias en estudio: «Phase III trials are currently being conducted… cryospray, rheoplasty and targeted lung denervation». El texto p101 ya describe un ECA fase III con sham de denervación (ref. 906). Crioespray y reoplastia sí siguen en curso. | Precisar que solo la denervación está desactualizada en la figura. El objetivo primario de AIRFLOW-3 es **[externo, no verificable con figuras]**. | MEDIA |

## V6. Fig 2.4 (PDF 38 / impr. 27) y Fig 2.6 (PDF 40 / impr. 29): espirometría y diagnóstico

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V6 | DX-01 | CONFIRMADO | Fig 2.4: «should vary by no more than 5% or 150 mL, whichever is greater». Por un lado, «largest value obtained from any of three…» curvas; por otro, «ratio should be taken from the technically acceptable curve with the largest sum of FVC and FEV1». Cita Miller 2005 y Pellegrino 2005, no el estándar ATS/ERS 2019. | — | ALTA |
| V6 | DX-02 | CONFIRMADO | Fig 2.6: con pre-BD ≥ 0,7 → «Not COPD», y de ahí una flecha punteada a «Measure Post-Bronchodilator FEV1/FVC if volume responder suspected». Con post-BD < 0,7 → «COPD confirmed», sin repetir si el cociente está entre 0,6 y 0,8. Con post-BD ≥ 0,7 → «Flow response: needs follow-up…». No hay salida PRISm. El texto p41 pide repetir si 0,6-0,8. | — | ALTA |

## V7. Fig 3.5 (PDF 66 / impr. 55): tabaquismo

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V7 | FARM-08 | CONFIRMADO | «First-line pharmacotherapies… varenicline, nortriptyline, bupropion sustained release, nicotine gum, nicotine inhaler, nicotine nasal spray, and nicotine patch». Fuente: «JAMA 2000; 283(24): 3244-54». No incluye pastillas de nicotina, TSN combinada ni citisina. | El contenido híbrido se confirma: la vareniclina (2006) no estaba en la guía PHS 2000, donde la nortriptilina era de segunda línea. Sugiero rebajar de ALTA a MEDIA (figura de apoyo, sin riesgo grave inmediato). | MEDIA |
| V7 | MET-14 | CONFIRMADO | Misma figura. La cita al pie es correcta (volumen 283). | Si el hallazgo alude a una «ref. 572 corrupta», el problema está en la bibliografía, no en la figura. | MEDIA |

## V8. Figs 4.5/4.6 (PDF 113), 4.7 (PDF 117), 4.8 (PDF 118) y 4.9 (PDF 119): soporte ventilatorio

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V8 | EXA-06 | CONFIRMADO | Fig 4.6: «High flow oxygen (HFNT) is the first mode of ventilation used in COPD patients with acute hypoxemic respiratory failure». En la misma viñeta: «NIV has been shown to… improve survival (Evidence A)». Una sola A cubre la viñeta compuesta. Mensaje clave p103: «High flow oxygen systems and mechanical NIV… improve survival». | Precisar que, dentro de la figura, la supervivencia se atribuye a la VNI. La fusión HFNT-supervivencia aparece en el mensaje clave (p103). La figura limita el «primer modo» a la insuficiencia «hypoxemic». | ALTA |
| V8 | COH-07 | CONFIRMADO | Fig 4.6 dice «first mode» (HFNT); el texto p118 dice «NIV is the initial mode of ventilation to treat acute respiratory failure». Fig 4.8: «PaCO2 ≥ 6.0 kPa or 45 mmHg and arterial pH ≤ 7.35», frente a «pH < 7.35» en la Fig 4.2. | La contradicción se atenúa porque la figura se refiere a insuficiencia hipoxémica, pero sigue resultando confusa. | MEDIA |
| V8 | MET-09 | CONFIRMADO | Fig 4.6: «purulent sputum… prior positive sputum bacteria culture… (Evidence A)». Fig 4.5: «purulent oral secretions». La A es única para afirmaciones compuestas. | Que no haya ECA que respalden el criterio del cultivo previo es **[externo, no verificable con figuras]**. | ALTA |
| V8 | EXA-19 | CONFIRMADO | Fig 4.8 incluye como indicación de VNI «Persistent hypoxemia despite supplemental oxygen therapy». Fig 4.7 lista «Persistent hypoxemia» (sin umbral) y «Treatment of patients with stable COPD at risk of exacerbations», y contiene la errata «Contraintidaction for NIV». | — | MEDIA |
| V8 | EXA-02 | CONFIRMADO | Fig 4.9: «Persistent life-threatening hypoxemia despite high flow oxygen (HFNT) or NIV» y «Unable to tolerate HFNT and/or NIV». No aparece el fracaso de la VNI ni el empeoramiento de pH/PaCO2, aunque el texto de la misma página dice «include failure of an initial trial of NIV». | — | ALTA |

## V9. Fig 3.18 (PDF 89 / impr. 78) y texto (PDF 87 / impr. 76): oxigenoterapia crónica

Nota de ubicación: la Fig 3.18 está en el **PDF 89**, no en el 88 que indicaba el encargo (el 88 es la Fig 3.17). Los hallazgos la ubican correctamente.

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V9 | REH-04, COH-13 | CONFIRMADO | Fig 3.18: «PaO2 ≤ 55 mmHg (≤ 7.3 kPa) or SaO2 < 88%». Segundo grupo: «PaO2 > 55 but < 60 mmHg» con HTP, ICC o «hematocrit > 55%», sin criterio de SaO2. Texto p87: «SaO2 at or below 88%» y «SaO2 of 88%». Mensaje clave: «may improve survival»; Fig 3.17: «increases survival… (Evidence A)». | — | REH-04: ALTA; COH-13: MEDIA |
| V9 | REH-06 | CONFIRMADO | Texto p87: «(> 15 hours per day; LTOT)» y, poco después, «the recommendation to use oxygen > 15 hours per day is not supported by newer evidence». | Es una ambigüedad (admite la lectura «no hace falta más de 15 h»), no una contradicción frontal. Rebajar de ALTA a MEDIA. | MEDIA |
| V9 | REH-07 | CONFIRMADO | Fig 3.18: «titrate to keep SaO2 ≥ 90%», sin advertencia sobre la hipercapnia; «Recheck in 60 to 90 days». | — | MEDIA |
| V9 | INT-13 | CONFIRMADO | Fig 3.19 (p91): «NOTT: ≥ 19 hours of continuous oxygen vs ≤ 13 hours: 50% reduction; MRC: ≥ 15 hours vs no oxygen». El texto p87 (REDOX: 24 h frente a 15 h) relativiza ese mensaje. | — | MEDIA |

## V10. Tabla A, niveles de evidencia (PDF 14 / impr. 3)

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V10 | MET-02 | CONFIRMADO PARCIAL | Nivel A: «a single high quality RCT involving substantial numbers of patient without any bias». Nivel B, con el encabezado «RCTs with important limitations»: «…post hoc or subgroup analyses of RCTs or meta-analyses of RCTs». C: estudios observacionales; D: consenso. No existe una dimensión de fuerza de recomendación. | La «inversión» (metaanálisis = B) es una ambigüedad, no una regla explícita: el encabezado de B permite leer «metaanálisis de ECA limitados». La ausencia de fuerza de recomendación y de método formal de riesgo de sesgo se confirma. | MEDIA |
| V10 | EPI-05 | CONFIRMADO PARCIAL | Misma tabla. La aplicación heterogénea se comprueba en las figuras: opiáceos con C pese a existir ECA (Fig 3.20) y mucolíticos con B y A en la misma figura (Fig A3.3). | El mismo matiz sobre los metaanálisis. | MEDIA |

## V11. Fig 3.6 (PDF 69 / impr. 58) y texto (PDF 70): vacuna VRS

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V11 | FARM-01 | CONFIRMADO PARCIAL | «…vaccination for individuals aged ≥ 50 years and/or with chronic heart or lung disease, as recommended by the CDC (Evidence A)». Texto p70: vacunación universal desde los 75 años y de 50 a 74 con un factor de riesgo; cita al ACIP y a la Comisión Europea. | La figura va dirigida a pacientes con EPOC, que ya es un factor de riesgo, así que «≥ 50» coincide con el texto y el ACIP. La divergencia real es otra: el «and/or» abre la vacuna a pacientes con EPOC menores de 50 años, y la A se aplica a todo (entre 50 y 59 años la base es de inmunopuente). La omisión del Guillain-Barré está en el texto, no en la figura. | MEDIA |

## V12. Fig 2.9 (PDF 46 / impr. 35): búsqueda de casos

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V12 | EQ-02 | CONFIRMADO | El cuestionario es el primer paso (LFQ, CDQ, COPD-PS, PUMA, CAPTURE). Si es positivo, se va a «In Primary Care Setting — Hand devices (PEF, COPD-6, PIKO-6)» o a «In Specialty Care Setting — Confirmatory pre-BD spirometry». La espirometría solo aparece en atención especializada. Si es negativo: «Monitor symptoms & address risk factors». | — | ALTA |
| V12 | DX-12 | CONFIRMADO | El recuadro «Individuals at Risk» incluye «Age ≥ 35 years», exposiciones, genética, «Prematurity & early life disadvantage factors» y síntomas; no menciona paquetes-año. El epígrafe «Opportunistic case-finding» va seguido de un ejemplo sistemático por correo. Adaptada de Aaron, AJRCCM 2024. | — | MEDIA |

## V13. Fig 3.23 (PDF 99 / impr. 88): reducción de volumen

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V13 | INT-07 | CONFIRMADO | Rama homogénea: «- CV or FI+» → «ELVR (EBV,LVRC,VA) LVRS»; «+ CV or FI-» → «ELVR (LVRC,VA) LVRS». Es idéntica a la rama heterogénea. No hay exclusión del subgrupo de alto riesgo de NETT. Nota: «Long term ELVR outcomes or direct comparisons to LVRS are unknown». | Ninguna. Refuerza el hallazgo que la ablación por vapor (STEP-UP) se estudió solo en enfisema heterogéneo de lóbulos superiores. | ALTA |

## V14. Fig 3.20 (PDF 93 / impr. 82): paliación de la disnea

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V14 | MET-13 | CONFIRMADO | «Opiates, neuromuscular electrical stimulation (NMES), oxygen and fans blowing air onto the face can relieve breathlessness (Evidence C)»: una sola C para cuatro intervenciones. Texto de la misma página: «The roles of oxygen therapy, HFNT and NIV for palliation of dyspnea are debated». El ECA de morfina de liberación prolongada a 8/16 mg/día (ref. 805) fue negativo. | — | MEDIA |
| V14 | INT-02 | CONFIRMADO | Misma figura. En el texto (p93-94), lo único sobre seguridad es «no worsening in sleepiness… in one study». No se indican dosis, monitorización ni advertencias. | Currow 2020, la guía ERS 2024 y las señales de mortalidad con > 30 mg MME son **[externo, no verificable con figuras]**. | ALTA |

## V15. Fig A3.3 (PDF 160), Fig 3.11 (PDF 79) y Fig 4.11 (PDF 122): mucolíticos, eosinófilos, biológicos y vitamina D

| Ítem | IDs | Veredicto | Qué se ve exactamente en la figura | Corrección necesaria al hallazgo | Severidad sugerida |
|---|---|---|---|---|---|
| V15 | MET-08, NOV-15 | CONFIRMADO | Fig A3.3: «…reduces the risk of exacerbations in select populations (Evidence B)» y «Antioxidant mucolytics are recommended only in selected patients (Evidence A)». Fig 4.11: NAC, carbocisteína y erdosteína bajo «Mucoregulators», sin restricción. Texto p167: Cochrane 2015 (ref. 1600) con «we are moderately confident». La ref. 1601 (RESTORE) aparece como «PA675». | Se verifican los 4 puntos de NOV-15. Para MET-08 sugiero rebajar de ALTA a MEDIA: es una incoherencia de gradación con impacto clínico limitado. | MEDIA |
| V15 | NOV-18 | CONFIRMADO | Fig A3.3: «blood eosinophil count < 2% increases the risk of pneumonia (Evidence C)». Es el único umbral de la guía expresado en porcentaje. | — | BAJA |
| V15 | FARM-14, NOV-03, MET-12 | CONFIRMADO | Fig 3.11: BOREAS «83mL; P < 0.001 (95% CI: 42, 125)»; NOTUS «62mL; P = 0.02 (95% CI: 11, 113)»; nota «d: at 52 weeks». METREX «(n=836)» con «RR 0.82; P = 0.04» y nota «c: pre-defined eosinophilic population». METREO: «(n=674)», «RR 0.80; NS». Nota «a: …while receiving inhaled triple therapy». Apéndice p163: los tres ensayos de mepolizumab con «≥ 300 cells/μL». | Que los 83 mL de BOREAS correspondan a la semana 12 es **[externo]**, aunque coincide con el resumen publicado (confianza alta). | MEDIA |
| V15 | FARM-18, NOV-16 | CONFIRMADO | Fig 4.11 («Interventions that Reduce the Frequency of COPD Exacerbations»): «Vitamin D» en «Various others», sin calificativo. Texto p111: «…severe deficiency results in a 50% reduction in episodes and hospital admission.(996,997)». p164: «a more recent study has shown no effect.(997)». | — | MEDIA |

---

## Recuento

**Por hallazgo (47 IDs):**
- **43 CONFIRMADO**
- **4 CONFIRMADO PARCIAL:** INT-01, MET-02, EPI-05 y FARM-01.
- **0 NO CONFIRMADO**

**Por ítem (15):**

| Ítem | Veredicto global |
|---|---|
| V1 | CONFIRMADO |
| V2 | CONFIRMADO |
| V3 | CONFIRMADO |
| V4 | CONFIRMADO, con corrección de ubicación |
| V5 | CONFIRMADO PARCIAL |
| V6 | CONFIRMADO |
| V7 | CONFIRMADO |
| V8 | CONFIRMADO |
| V9 | CONFIRMADO |
| V10 | CONFIRMADO PARCIAL |
| V11 | CONFIRMADO PARCIAL |
| V12 | CONFIRMADO |
| V13 | CONFIRMADO |
| V14 | CONFIRMADO |
| V15 | CONFIRMADO |

Total: 12 CONFIRMADO, 3 CONFIRMADO PARCIAL, 0 NO CONFIRMADO.

## Correcciones principales

1. **REH-01 / INT-04:** la señal de daño (Greening 2014) está en el **texto** del Apéndice 4, no en la Fig A4.1, que no menciona la mortalidad. Además, el Apéndice cita la ref. 1725 (Chen 2025), favorable al inicio precoz.
2. **INT-01:** los criterios de derivación del texto coinciden en contenido con ISHLT 2021. Lo desactualizado es la figura (ISHLT 2006, criterios de listado presentados como de derivación).
3. **MET-02 / EPI-05:** la clasificación de los metaanálisis en el nivel B es una ambigüedad, no una inversión explícita.
4. **FARM-01:** en la EPOC, «≥ 50» es coherente con el ACIP. El problema real es el «and/or» (abre la vacuna a menores de 50 años) y la A global.
5. **EXA-06 / COH-07:** la Fig 4.6 limita el «first mode» de la HFNT a la insuficiencia hipoxémica y atribuye la supervivencia a la VNI. La fusión HFNT-supervivencia está en el mensaje clave (p103).
6. **Ubicación:** la Fig 3.18 está en el PDF 89, no en el 88.
7. **Severidades que propongo rebajar:**
   - MUL-01, REH-01 e INT-01: de CRÍTICA a ALTA.
   - REH-06, FARM-08 y MET-08: de ALTA a MEDIA.
