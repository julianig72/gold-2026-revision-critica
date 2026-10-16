# Verificación externa independiente: lote 1 (ítems E1 a E10)

**Documento auditado:** GOLD 2026 Report, versión 1.3, de 8 de diciembre de 2025.

**Fecha de verificación:** 16 de octubre de 2026.

**Perfil del verificador:** neumología clínica, farmacología y medicina basada en la evidencia. El planteamiento es escéptico y busca la refutación.

## Método

- **Qué se contrasta.** Para cada ítem se comparan tres cosas:
  1. El texto exacto de la guía (`gold_full.txt`, más las figuras renderizadas cuando el contenido es una imagen).
  2. La lista de referencias numeradas de la propia guía (PDF 175-248).
  3. Las fuentes primarias externas.
- **De dónde salen las fuentes externas.**
  - Registros de Europe PMC y PubMed (NCBI E-utilities).
  - Textos completos en PMC o en repositorios institucionales de acceso abierto.
  - Fichas técnicas de la FDA (openFDA).
  - Guías ESC, ACC/AHA e ISHLT.
  - Avisos de retractación de PubMed.
- **Páginas.** Todas son páginas del PDF. La página impresa es la del PDF menos 11.

**Citas de GOLD:** son literales breves (25 palabras o menos), usadas solo para verificar y criticar, porque el documento tiene copyright.

**Leyenda de veredictos**

- **CONFIRMADO:** el problema existe y el hallazgo es correcto en lo esencial.
- **CONFIRMADO PARCIAL:** el problema existe, pero el hallazgo contiene errores, exageraciones o atribuciones incorrectas.
- **NO CONFIRMADO:** la fuente primaria no respalda el hallazgo.

## Resumen de veredictos

| Ítem | IDs | Veredicto | Severidad sugerida | Severidad propuesta en el hallazgo |
|---|---|---|---|---|
| E1 | MUL-02 | CONFIRMADO | ALTA | CRÍTICA |
| E2 | INT-01 | CONFIRMADO PARCIAL | ALTA | CRÍTICA |
| E3 | INT-06 | CONFIRMADO | MEDIA | ALTA |
| E3 | INT-05 | CONFIRMADO | ALTA | ALTA |
| E4 | NOV-01, MET-11 | CONFIRMADO | ALTA | ALTA |
| E4 | NOV-02 | CONFIRMADO PARCIAL | MEDIA-BAJA | MEDIA |
| E5 | NOV-08, FARM-15 | CONFIRMADO | MEDIA-ALTA | ALTA / MEDIA |
| E6 | NOV-04, INT-11 | CONFIRMADO (con matices) | ALTA | ALTA / MEDIA |
| E6 | NOV-05 | CONFIRMADO PARCIAL | BAJA | BAJA |
| E7 | REH-01, INT-04 | CONFIRMADO | ALTA | CRÍTICA / ALTA |
| E8 | MET-15 | CONFIRMADO (el problema es mayor de lo descrito) | MEDIA | MEDIA |
| E9 | DX-10 | CONFIRMADO | MEDIA-ALTA | ALTA |
| E10 | MUL-07 | CONFIRMADO | ALTA | ALTA |

---

## E1 · Fibrilación auricular y fármacos de control de frecuencia o ritmo en la EPOC

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| E1 | MUL-02 | **CONFIRMADO** | PDF 128: *"There is no contraindication to any specific rate or rhythm control medication or strategy in patients with COPD, including beta-blockers."* La frase no lleva cita propia; la oración anterior cita la ref. 1171 (ACC/AHA 2023). | **1. La propia fuente de GOLD es más restrictiva.** Joglar JA, Chung MK, Armbruster AL, et al. *2023 ACC/AHA/ACCP/HRS Guideline for the Diagnosis and Management of Atrial Fibrillation.* Circulation 2024;149(1):e1-e156. PMID 38033089; doi:10.1161/CIR.0000000000001193. En su §10.12 da una recomendación 2a (B-R): "it is reasonable to use **cardioselective** beta blockers". El texto añade que los betabloqueantes "can exacerbate reactive airway disease and are generally avoided in that setting".<br>**2. ESC 2024.** Van Gelder IC, Rienstra M, Bunting KV, et al. *2024 ESC Guidelines for the management of atrial fibrillation.* Eur Heart J 2024;45(36):3314-3414. PMID 39210723; doi:10.1093/eurheartj/ehae176. Tabla 12: "In case of asthma, non-selective beta-blockers should be avoided. Contraindicated in… history of severe bronchospasm". El texto dice que los β1-selectivos tienen "a better efficacy and safety profile".<br>**3. ESC 2020.** Hindricks G, et al. Eur Heart J 2021;42(5):373-498. PMID 32860505; doi:10.1093/eurheartj/ehaa612. Verificada en el texto completo de acceso abierto. Tabla 13: en el asma, usar β1-bloqueantes, y los betabloqueantes están contraindicados si hay antecedente de broncoespasmo grave. Tabla 15: la propafenona y el sotalol "should not be used in patients with… asthma".<br>**4. Fichas técnicas de la FDA.** Propafenona: contraindicada en "bronchospastic disorders or severe obstructive pulmonary disease". Sotalol: contraindicado en "bronchial asthma or related bronchospastic conditions". Adenosina IV: contraindicada en "known or suspected bronchoconstrictive or bronchospastic lung disease". Amiodarona: advertencia en recuadro por toxicidad pulmonar, de hasta el 17 % y mortal en torno al 10 % de los casos. | Sustituir la frase por: "Preferir β1-selectivos (bisoprolol, metoprolol, nebivolol) o diltiazem/verapamilo si FEVI >40 %. Evitar betabloqueantes no selectivos y sotalol si hay broncoespasmo. Propafenona contraindicada en EPOC grave/broncoespasmo. Adenosina contraindicada en enfermedad broncoespástica. Vigilar la toxicidad pulmonar de la amiodarona." Citar la ESC 2024 y la §10.12 de ACC/AHA 2023. | **ALTA.** La afirmación es categórica y contradice las fichas técnicas. CRÍTICA es defendible si se valora el uso en el ámbito de urgencias. |

**Matices sobre el hallazgo**

- MUL-02 atribuye a la ESC 2020 una lista explícita de fármacos a evitar en la EPOC: betabloqueantes no selectivos, sotalol, propafenona y adenosina. Esa lista **no está** en la ESC 2020 en forma de sección sobre EPOC. Las contraindicaciones aparecen en las tablas de fármacos y referidas al **asma** o al broncoespasmo. La ESC 2024 tampoco enumera esos fármacos para la EPOC.
- La sustancia del hallazgo sigue siendo correcta: las fichas técnicas de la FDA contraindican la propafenona, el sotalol y la adenosina en la enfermedad broncoespástica.
- La crítica a la anticoagulación como "cornerstone" es menor. Es fraseología estándar, y la ACC/AHA estratifica el riesgo.

---

## E2 · Criterios de derivación y de inclusión en lista para trasplante pulmonar

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| E2 | INT-01 | **CONFIRMADO PARCIAL** | **Fig. 3.22 (PDF 97), paráfrasis:** etiqueta como criterios de *derivación* un BODE de 7 a 10 más al menos uno de estos: ingreso con PaCO2 >50 mmHg, HP/cor pulmonale pese a O2, o FEV1 <20 % con DLCO <20 % o enfisema homogéneo. Son los criterios de **inclusión en lista** de ISHLT 2006.<br>**Texto (PDF 102):** derivar con *"BODE index of 5 to 6, a PaCO2 > 50 mmHg… and/or PaO2 < 60 mmHg… and FEV1 < 25%.(908)"*; listar con *"BODE index is ≥ 7; FEV1 is < 15% to 20%"*, tres o más exacerbaciones graves, etc. | **ISHLT 2006:** Orens JB, et al. J Heart Lung Transplant 2006;25(7):745-55. PMID 16818116.<br>**Ref. 908, consenso ISHLT 2014:** Weill D, Benden C, Corris PA, et al. J Heart Lung Transplant **2015**;34(1):1-15. PMID 25085497. El texto de GOLD reproduce sus criterios.<br>**Consenso vigente, ISHLT 2021:** Leard LE, Holm AM, Valapour M, et al. *Consensus document for the selection of lung transplant candidates: An update from the ISHLT.* J Heart Lung Transplant 2021;40(11):1349-79. PMID 34419372; doi:10.1016/j.healun.2021.07.005.<br>• *Derivación:* enfermedad progresiva pese a tratamiento máximo, BODE 5-6 o FEV1 20-25 %, aumento del BODE >1 en 24 meses, cociente arteria pulmonar/aorta >1 en TC, exacerbaciones frecuentes y calidad de vida inaceptable. Contempla la derivación **simultánea** a reducción de volumen y a trasplante.<br>• *Inclusión en lista:* el BODE de 7 a 10 *"stands as the best guideline"*. El FEV1 <20 % es una consideración adicional. La HP, la hipercapnia crónica y las exacerbaciones graves *"may influence listing"*. | 1. Retitular la Fig. 3.22 como criterios de **inclusión en lista**, o sustituirla por los criterios de derivación de ISHLT 2021.<br>2. Actualizar el texto a Leard 2021, que debe citarse.<br>3. Eliminar "no candidato a LVRS" como requisito previo y recoger la derivación simultánea. | **ALTA.** CRÍTICA es excesiva: el problema puede retrasar derivaciones, pero la decisión final corresponde a centros especializados. |

**Errores del hallazgo**

- INT-01 atribuye a ISHLT 2021 criterios que en realidad son de 2014. En concreto, para derivar: PaCO2, PaO2 y FEV1 <25 %; y para listar: tres o más exacerbaciones graves y FEV1 <15-20 %. ISHLT 2021 no los formula así.
- INT-01 fecha la ref. 908 en 2014. Se publicó en 2015; el "2014" forma parte del título.
- Lo que sí está demostrado es esto: la figura y el texto son incongruentes entre sí, ambos están desactualizados y falta ISHLT 2021, que no aparece en la lista de referencias.

---

## E3 · Coils endobronquiales y comparación de válvulas endobronquiales (EBV) frente a cirugía de reducción de volumen (LVRS)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| E3a | INT-06 | **CONFIRMADO** | PDF 98: *"vapor ablation and lung coils) are not widely available for clinical care in many countries"*.<br>PDF 100: *"This therapy has limited clinical availability."*<br>La Fig. 3.22 mantiene *"Lung coils (Evidence B)"*. | **Situación regulatoria (FDA).** El 14-jun-2018, el comité asesor de la FDA votó 3 a 8 a que los beneficios del sistema ELEVAIR/RePneu no superaban sus riesgos, con votos desfavorables en eficacia. BTG recibió después una carta de *not approvable* (agosto de 2018). El dispositivo **nunca fue aprobado** por la FDA; tenía marcado CE desde 2010.<br>**Retirada del mercado.** Roodenburg SA, et al. Respiration 2025;104(1):58-68. PMID 39284292; doi:10.1159/000541366. Afirma que los coils originales "have been discontinued".<br>**Ensayos.**<br>• RENEW: Sciurba FC, et al. JAMA 2016;315(20):2178-89. PMID 27179849; doi:10.1001/jama.2016.6261. La distancia en la prueba de marcha de 6 minutos mejoró 14,6 m, en el umbral de relevancia clínica. Las complicaciones mayores fueron del 34,8 % frente al 19,1 %, y hubo más neumonías y neumotórax.<br>• REVOLENS: Deslée G, et al. JAMA 2016;315(2):175-84. PMID 26757466. Sin beneficio significativo en la prueba de marcha a 12 meses y con una razón coste-efectividad muy desfavorable. | 1. Indicar que los coils **no están aprobados por la FDA** y que se han **retirado** del mercado.<br>2. Retirarlos de la Fig. 3.22 o marcarlos como "no disponible / histórico".<br>3. Mantener la evidencia como información histórica. | **MEDIA.** Un dispositivo retirado del mercado no puede llevar a usos inadecuados. El problema es de vigencia, no de seguridad inmediata. La severidad ALTA del hallazgo es algo excesiva. |
| E3b | INT-05 | **CONFIRMADO** | PDF 99-100: comparar EBV frente a LVRS *"show comparable benefits with endobronchial valve treatment but with fewer complications.(862)"* | **La ref. 862 no compara con cirugía.** Criner GJ, et al. (LIBERATE). Am J Respir Crit Care Med 2018;198(9):1151-64. PMID 29787288. Compara EBV con tratamiento estándar; **no incluye un brazo de LVRS**.<br>**El único ensayo aleatorizado directo es CELEB.** Buttery SC, Banya W, Bilancia R, et al. *Lung volume reduction surgery versus endobronchial valves: a randomised controlled trial.* **Eur Respir J** 2023;61(4):2202063. PMID 36796833; doi:10.1183/13993003.02063-2022.<br>• Muestra: 88 pacientes.<br>• Cambio en iBODE a 12 meses: −1,10 con LVRS frente a −0,82 con EBV; p=0,54.<br>• Una muerte por brazo.<br>• Datos completos a 12 meses en solo 49 de 88 pacientes.<br>• No respalda "fewer complications". | 1. Corregir la frase: "En el único ECA directo (CELEB), LVRS y EBV produjeron mejoras similares a 12 meses, con potencia limitada; no hay evidencia comparativa sólida sobre complicaciones."<br>2. Citar CELEB.<br>3. Desvincular la ref. 862 de esta afirmación. | **ALTA.** La afirmación está mal atribuida y condiciona la elección entre cirugía y broncoscopia. |

**Errores del hallazgo y del enunciado**

- INT-06 cita RENEW como "JAMA 2016;315:175-84". Esas páginas corresponden a **REVOLENS**. RENEW es JAMA 2016;315:2178-89.
- El enunciado de la tarea sitúa CELEB en *Lancet Respir Med*. El ensayo se publicó en **Eur Respir J** 2023.
- No se ha verificado en una fuente primaria la causa de la retirada de los coils. Se ha atribuido a la adquisición de BTG por Boston Scientific, pero no consta en una fuente primaria.

---

## E4 · Mepolizumab y biológicos (METREX, METREO y MATINEE)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| E4a | NOV-01, MET-11 | **CONFIRMADO** | Apéndice 3, PDF 163: *"Across three phase III… blood eosinophil count of ≥ 300 cells/μL… 52 to 104 weeks… reduction in exacerbations leading to ED visits or hospitalizations (690,691)"*.<br>La Fig. 3.11 (PDF 79) sí recoge los umbrales correctos, lo que constituye una **incongruencia interna**. | **METREX y METREO.** Pavord ID, Chanez P, Criner GJ, et al. *Mepolizumab for Eosinophilic COPD.* N Engl J Med 2017;377(17):1613-29. PMID 28893134; doi:10.1056/NEJMoa1708208.<br>• Ambos duraron **52 semanas**.<br>• Los eosinófilos se exigían ≥150/µL en el cribado **o** ≥300/µL en el año previo.<br>• METREX solo fue positivo en el estrato eosinofílico: RR 0,82 (IC 95 %: 0,68-0,98), P ajustada 0,04. En la población total, RR 0,98.<br>• **METREO fue negativo:** con 100 mg, RR 0,80 (0,65-0,98), P ajustada 0,07; con 300 mg, RR 0,86, P ajustada 0,14.<br>**MATINEE.** Sciurba FC, Criner GJ, Christenson SA, et al. N Engl J Med 2025;392(17):1710-20. PMID 40305712; doi:10.1056/NEJMoa2413181.<br>• Eosinófilos ≥300/µL, tratamiento de **52 a 104 semanas**.<br>• Exacerbaciones moderadas o graves: RR 0,79 (0,66-0,94), P=0,01.<br>• La calidad de vida y los síntomas no mostraron diferencias significativas. Por eso, según los autores, *"no statistical inferences regarding subsequent secondary end points"*. Esto afecta también a las exacerbaciones con visita a urgencias u hospitalización. | Reescribir el párrafo ensayo por ensayo:<br>• METREX: positivo solo en el estrato eosinofílico.<br>• METREO: no significativo.<br>• MATINEE: positivo en el objetivo primario, con eosinófilos ≥300 y de 52 a 104 semanas.<br>• Eliminar la reducción de urgencias u hospitalizaciones, o marcarla como "no testable por jerarquía". | **ALTA.** Sobrerrepresenta la eficacia de un biológico de alto coste. MEDIA-ALTA es aceptable. |
| E4b | NOV-02 | **CONFIRMADO PARCIAL** | Fig. A3.3 (PDF 160): *"Mepolizumab reduces exacerbations in patients with and without chronic bronchitis (Evidence A)"*; *"Dupilumab… improves lung function and quality of life… (Evidence A)"*. | **Definición de niveles de evidencia de la propia guía (Tabla A, PDF 14).** El nivel A exige "consistent findings" o "a single high quality RCT involving substantial numbers". El nivel B admite resultados "somewhat inconsistent" y análisis de subgrupos.<br>**Dupilumab y calidad de vida.**<br>• BOREAS fue positivo: Bhatt SP, et al. N Engl J Med 2023;389(3):205-14. PMID 37272521.<br>• **NOTUS** no mostró diferencias significativas en el SGRQ: Bhatt SP, et al. N Engl J Med 2024;390(24):2274-83. PMID 38767614; doi:10.1056/NEJMoa2401304.<br>• Los resultados son inconsistentes, lo que corresponde a un nivel B. | **Dupilumab, calidad de vida:** bajar a nivel B.<br>**Mepolizumab:** el nivel A es defendible para "reduce exacerbaciones" solo con MATINEE como ensayo único de calidad. "With and without chronic bronchitis" procede de subgrupos, lo que corresponde a un nivel B. | **MEDIA-BAJA.** |

---

## E5 · Ensifentrina tras LABA+LAMA

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| E5 | NOV-08, FARM-15 | **CONFIRMADO** | **Fig. 3.9 (PDF 74, imagen):** en la rama de disnea, tras LABA+LAMA, *"Consider adding ensifentrine"*, **sin** "if available".<br>**Texto (PDF 77):** *"Considering adding ensifentrine if available."*<br>**Apéndice (PDF 163):** los ensayos *"not designed to assess the impact of ensifentrine on top of LABA+LAMA or LABA+LAMA+ICS"*; *"currently only available in the US"*. | **ENHANCE-1 y ENHANCE-2.** Anzueto A, Barjaktarevic IZ, Siler TM, et al. *Ensifentrine, a Novel PDE3 and PDE4 Inhibitor for the Treatment of COPD: Randomized, Double-Blind, Placebo-controlled, Multicenter Phase III Trials (ENHANCE).* Am J Respir Crit Care Med 2023;208(4):406-16. PMID 37364283; PMC10449067; doi:10.1164/rccm.202306-0944OC.<br>• **Tratamiento de base permitido:** ninguno, LAMA o LABA, con o sin ICS. **Se excluía la combinación LABA+LAMA.**<br>• Recibían LAMA o LABA concomitante el 69 % (ENHANCE-1) y el 55 % (ENHANCE-2).<br>• FEV1 AUC0-12h: +87 y +94 mL.<br>• Las exacerbaciones fueron un objetivo secundario, en 24 semanas, en una población no seleccionada por riesgo de exacerbación. | 1. En la Fig. 3.9 y en el texto, indicar que no hay datos de ensayos aleatorizados con LABA+LAMA de base.<br>2. Posicionarla como opción basada en extrapolación (evidencia D o "consenso"), o como alternativa al segundo broncodilatador cuando este no se tolera.<br>3. Añadir "if available" en la figura. | **MEDIA-ALTA.** El Apéndice reconoce la limitación, pero el algoritmo, que es lo que más se usa, no la recoge. |

---

## E6 · Mortalidad con triple terapia (IMPACT y ETHOS)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| E6a | NOV-04, INT-11 | **CONFIRMADO** (con matices) | **PDF 92:** *"IMPACT(467) and ETHOS,(492)… reduce all-cause mortality compared to dual inhaled LABD therapy"*.<br>**Fig. 3.19 (PDF 91):** *"relative risk reduction… IMPACT: HR 0.72… ETHOS: HR 0.51"*, sin indicar dosis ni comparador.<br>Población descrita como *"≥ 2 moderate exacerbations) and/or severe"*. | **ETHOS, ensayo original.** Rabe KF, Martinez FJ, Ferguson GT, et al. N Engl J Med 2020;383(1):35-48. PMID 32579807. La mortalidad se analizó con valor nominal (HR 0,54).<br>**ETHOS, análisis de mortalidad.** Martinez FJ, Rabe KF, Ferguson GT, et al. Am J Respir Crit Care Med 2021;203(5):553-64. PMID 33252985; doi:10.1164/rccm.202006-2618OC.<br>• Budesonida 320 µg (BGF 320) frente a la doble broncodilatación (GFF): HR 0,51 (0,33-0,80).<br>• BGF 320 frente a ICS/LABA (BFF): 0,72 (0,44-1,16), no significativo.<br>• **BGF 160: sin diferencia significativa** frente a ninguno de los dos comparadores.<br>• Es un objetivo secundario sin control de multiplicidad.<br>**Por tanto, sí: solo la dosis de 320 µg mostró beneficio, y solo frente a LAMA/LABA.**<br>**IMPACT.** Lipson DA, et al. N Engl J Med 2018;378(18):1671-80. PMID 29668352. Análisis de mortalidad: Lipson DA, Crim C, Criner GJ, et al. Am J Respir Crit Care Med 2020;201(12):1508-16. PMID 32162970.<br>• Frente a UMEC/VI: HR 0,72 (0,53-0,99), P=0,042.<br>• Frente a FF/VI: 0,89 (0,67-1,16), no significativo.<br>• Incluye datos adicionales de estado vital.<br>**Hipótesis de la retirada de ICS.** Suissa S, Drazen JM. N Engl J Med 2018;378(18):1723-4. PMID 29669218. Es una **hipótesis discutida**, no un hecho. Lipson 2020 sostiene que sus datos *"refute the premise"*.<br>**Criterios de inclusión.** En ambos ensayos bastaba **una** exacerbación moderada si el FEV1 era <50 %. | 1. Presentar el efecto sobre la mortalidad como **señal procedente de objetivos secundarios o análisis adicionales**, no como efecto establecido.<br>2. En la Fig. 3.19, especificar "BGF 320 µg vs LAMA/LABA" y "vs ICS/LABA no significativo", y añadir que BGF 160 no fue significativo.<br>3. Mencionar el debate sobre la retirada de ICS.<br>4. Corregir los criterios de inclusión. | **ALTA.** La figura lista intervenciones "que reducen la mortalidad", lo que puede impulsar el uso de ICS, que tienen riesgo de neumonía. |
| E6b | NOV-05 | **CONFIRMADO PARCIAL** | Fig. 3.19: *"b) ETHOS trials (Martinez et al. 2021)"*.<br>Fig. A3.3 (PDF 160): *"Recent data suggesta beneficial effect"*. | **Lista de referencias de GOLD.**<br>• Martinez 2021 (PMID 33252985) **no figura** en ella. La ref. 494 es otro artículo de Martinez (KRONOS).<br>• Las refs. 492 y 694 están **duplicadas**: ambas son Rabe NEJM 2020.<br>• La ref. 791 es el protocolo de SUMMIT, citado en el texto (PDF 92) para un resultado. El artículo de resultados es la ref. 1181 (Vestbo, Lancet 2016).<br>• La errata "suggesta" se confirma en la imagen de la Fig. A3.3.<br>**"CAAT™" no es una errata.** GOLD usa ese término deliberadamente (PDF 50: CAT™ y CAAT™ son equivalentes). | 1. Añadir Martinez 2021 a la lista de referencias.<br>2. Fusionar las refs. 492 y 694.<br>3. Sustituir la ref. 791 por la 1181.<br>4. Corregir "suggesta".<br>5. **No** cambiar CAAT™. | **BAJA.** |

**Matiz sobre el hallazgo**

- NOV-04 describe el análisis de mortalidad de IMPACT como "posterior". Es preciso solo en parte: la mortalidad durante el tratamiento estaba prespecificada, y lo que se añadió después fue la recogida adicional del estado vital.
- NOV-04 presenta la retirada de ICS como explicación plausible, pero sin la refutación de los autores de IMPACT. Debe presentarse como un debate abierto.

---

## E7 · Rehabilitación iniciada durante el ingreso y mortalidad

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| E7 | REH-01, INT-04 | **CONFIRMADO** | **PDF 91:** *"reduction in mortality… pulmonary rehabilitation initiated during hospitalization or 4 weeks after discharge… (778-781)"*.<br>**Fig. 3.19:** la marca como *"#Inconclusive"*, con *"Old trials RR 0.28"* y *"New trials: RR 0.68 (95% CI 0.28, 1.67)"*.<br>Greening solo se cita en el **Apéndice 4 (PDF 172, ref. 1726):** *"may compromise survival"*. | **Ensayo aleatorizado con señal de daño.** Greening NJ, Williams JE, Hussain SF, et al. *An early rehabilitation intervention to enhance recovery during hospital admission for an exacerbation of COPD: randomised controlled trial.* BMJ 2014;349:g4315. PMID 25004917; doi:10.1136/bmj.g4315.<br>• 389 pacientes, rehabilitación iniciada en las primeras 48 h.<br>• Reingreso: HR 1,1 (0,86-1,43).<br>• **Mortalidad a 12 meses: OR 1,74 (1,05-2,88)**.<br>**Lo que muestran las refs. citadas en PDF 91:**<br>• **Ref. 778:** Lu HY, et al. Int J Chron Obstruct Pulmon Dis 2023;18:881-93. PMID 37215744. Mortalidad: **RR 0,72 (0,39-1,34), no significativo**. El inicio durante el ingreso muestra una tendencia a menos beneficio.<br>• **Ref. 781:** Puhan MA, et al. Cochrane 2016, CD005305.pub4. PMID 27930803. Mortalidad: **OR 0,68 (0,28-1,67), no significativo**, con certeza baja. La Fig. 3.19 lo rotula como "RR".<br>• **Ref. 779:** Ryrsø CK, et al. BMC Pulm Med 2018;18:154. PMID 30219047. RR 0,58 (0,35-0,98), con 4 ensayos.<br>• **Ref. 780:** Puhan 2011, Cochrane. PMID 21975749. Ensayos antiguos con OR 0,28 (0,10-0,84).<br>• **Ref. 782:** Lindenauer PK, et al. JAMA 2020;323(18):1813-23. PMID 32396181. Estudio **observacional** con rehabilitación iniciada en los 90 días **posteriores al alta**. | 1. Separar la movilización intrahospitalaria de la rehabilitación estructurada tras el alta.<br>2. Eliminar "during hospitalization" de la afirmación de mortalidad.<br>3. Indicar que los metaanálisis más recientes (Lu 2023, Cochrane 2016) no muestran una reducción significativa de la mortalidad.<br>4. Citar Greening 2014 en el cuerpo principal.<br>5. Recomendar iniciar la rehabilitación en las 3-4 semanas tras el alta. | **ALTA.** CRÍTICA es defendible: la afirmación invita a intervenir en una fase para la que existe un ensayo aleatorizado con aumento de la mortalidad. |

**Matiz sobre el hallazgo**

- La guía **sí** menciona a Greening, pero únicamente en el Apéndice 4. En el texto principal, la referencia a la mortalidad omite esa señal de daño.
- Dos de las cuatro referencias que sostienen "reduction in mortality" (las refs. 778 y 781) **no** muestran reducción significativa. Esto agrava el hallazgo.

---

## E8 · Referencia retractada (ref. 241)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| E8 | MET-15 | **CONFIRMADO** (el problema es mayor de lo descrito) | PDF 28: *"Oxidants are… released from activated inflammatory cells such as macrophages and neutrophils.(215,241)"*. | **Artículo citado (ref. 241).** Malhotra D, Thimmulappa R, Vij N, et al. *Heightened endoplasmic reticulum stress in the lungs of patients with COPD: the role of Nrf2-regulated proteasomal activity.* Am J Respir Crit Care Med 2009;180(12):1196-207. PMID 19797762; doi:10.1164/rccm.200903-0324OC. PubMed lo marca como **"Retracted Publication"**.<br>**Expresión de preocupación:** AJRCCM 2014;190(10):1200. PMID 25398118.<br>**Retractación:** AJRCCM 2016;193(3):344. PMID 26829430; doi:10.1164/rccm.1933retraction. Es conjunta con el artículo sobre DJ-1 (PMID 18556627).<br>**Ref. 215:** Menezes AM, et al., estudio PLATINO sobre **tuberculosis** y obstrucción. Es irrelevante para la afirmación sobre estrés oxidativo. | 1. Eliminar la ref. 241.<br>2. Sustituir las refs. 215 y 241 por fuentes válidas, por ejemplo la ref. 240 (Domej 2014) o una revisión actual.<br>3. Implantar un cribado de retractaciones mediante PubMed, Retraction Watch o Crossref. | **MEDIA.** El impacto clínico es nulo, pero el fallo de integridad bibliográfica es doble. |

**Error del hallazgo:** MET-15 afirma que la frase "se sostiene con la ref. 215". No es así: tras retirar la ref. 241, la afirmación queda **sin ninguna referencia válida**.

---

## E9 · Recomendación de la USPSTF sobre el cribado de EPOC

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| E9 | DX-10 | **CONFIRMADO** | PDF 44: *"screening of low-risk, asymptomatic individuals is not recommended by the US Preventive Services Task Force.(380)"*. | **Declaración de recomendación.** US Preventive Services Task Force; Mangione CM, Barry MJ, Nicholson WK, et al. *Screening for COPD: USPSTF Reaffirmation Recommendation Statement.* JAMA 2022;327(18):1806-11. PMID 35536260; doi:10.1001/jama.2022.5692.<br>• Grado **D** frente al cribado en **adultos asintomáticos**, entendidos como los que no reconocen ni refieren síntomas respiratorios, **sin restringirlo a los de bajo riesgo**.<br>• La evidencia revisada *"included current and former smokers"*.<br>• Solo excluye a las personas sintomáticas y a algunos grupos de muy alto riesgo, como el déficit de alfa-1 antitripsina o determinadas exposiciones laborales.<br>**La ref. 380 es el informe de evidencia, no la recomendación:** Webber EM, et al. JAMA 2022;327(18):1812-6. PMID 35536261. | 1. Citar con exactitud: "La USPSTF desaconseja (D) el cribado en adultos asintomáticos, incluidos fumadores".<br>2. Citar Mangione 2022.<br>3. Declarar y justificar la divergencia de GOLD sobre la búsqueda activa de casos en expuestos asintomáticos (PDF 45). | **MEDIA-ALTA.** Tergiversa la recomendación de un organismo externo; el daño clínico directo es limitado. La severidad ALTA del hallazgo es algo excesiva. |

---

## E10 · Hipertensión pulmonar asociada a EPOC y ensayo PERFECT

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| E10 | MUL-07 | **CONFIRMADO** | PDF 129: *"Further well-designed RCTs should be encouraged to advise for or against the use of PAH medications in PH-COPD.(1193)"*.<br>La ref. 1193 **es el propio ensayo PERFECT**, y no se menciona su resultado. | Nathan SD, Argula R, Trivieri MG, et al. *Inhaled treprostinil in pulmonary hypertension associated with COPD: PERFECT study results.* Eur Respir J 2024;63(6):2400172. PMID 38811045; doi:10.1183/13993003.00172-2024.<br>• Se interrumpió precozmente por recomendación del comité de monitorización de datos y seguridad, por **mayor riesgo de eventos adversos graves** y *"suggestive evidence of an increased risk of mortality"*.<br>• La distancia en la prueba de marcha de 6 minutos fue numéricamente peor con el fármaco.<br>• Conclusión de los autores: los resultados *"do not support iTRE as a viable treatment option"*. | Añadir: "El treprostinil inhalado no debe usarse en la HP-EPOC (ensayo PERFECT interrumpido por daño). En la HP grave, el tratamiento con vasodilatadores debe limitarse a centros expertos o a ensayos clínicos." | **ALTA.** Se omite un resultado de daño de la propia referencia citada, en un contexto de uso fuera de indicación por extrapolación desde la HP asociada a enfermedad pulmonar intersticial (ensayo INCREASE). |

---

## Errores detectados en los hallazgos o en el enunciado

1. **INT-01:** describe ISHLT 2021 con los criterios de 2014 y fecha la ref. 908 en 2014, cuando se publicó en 2015.
2. **INT-06:** asigna a RENEW las páginas de REVOLENS (JAMA 2016;315:175-84).
3. **Enunciado de la tarea:** CELEB se publicó en *Eur Respir J* 2023, no en *Lancet Respir Med*.
4. **MUL-02:** atribuye a la ESC 2020 una lista sobre EPOC que no existe como tal. Las contraindicaciones de la ESC 2020 se refieren al asma o al broncoespasmo grave, aunque las fichas de la FDA respaldan la sustancia del hallazgo.
5. **NOV-05:** "CAAT™" no es una errata.
6. **MET-15:** la ref. 215 no sostiene la frase, por lo que el problema es mayor de lo descrito.
7. **REH-01 e INT-04:** la guía sí cita a Greening, aunque solo en el Apéndice 4.
8. **NOV-04:** la retirada de ICS en IMPACT es una hipótesis discutida, no un hecho. Además, la mortalidad durante el tratamiento estaba prespecificada.

## Limitaciones de la verificación

- **ISHLT 2006:** el contenido procede de fuentes secundarias.
- **ESC 2020:** se ha verificado en el texto extraído del PDF de acceso abierto. La Fig. 14, sobre la elección de fármacos y donde aparece la EPOC, es una imagen que no se pudo leer.
- **BGF 160 en ETHOS:** el HR de aproximadamente 0,79 procede de la introducción de Martinez 2021; no se extrajo el IC de la tabla.
- **Panel de la FDA de 2018 sobre los coils:** se conoce por prensa especializada (MassDevice) y no por el acta oficial. La causa comercial de la retirada no está verificada.
- **Ensifentrina:** no se ha revisado su situación regulatoria fuera de EE. UU. después de 2025.
