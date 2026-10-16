# Verificación externa independiente (ronda 2): hallazgos prioritarios sobre GOLD 2026 (v1.3, 8-dic-2025)

**Verificador:** revisión independiente con perspectiva epidemiológica, neumológica y de integridad científica.
**Fecha de consulta de fuentes web:** 16-oct-2026.

**Método:**
- **Texto de la guía:** `gold_full.txt` (páginas PDF; página impresa = PDF − 11). Las figuras que solo existen como imagen se comprobaron en `pages\pNNN.png`.
- **Referencias:** las numeradas de GOLD se contrastaron con la lista de PDF 175-248.
- **Fuentes primarias:** resúmenes y metadatos en Europe PMC/PubMed, y páginas oficiales de CDC/ACIP, FDA, USPSTF y goldcopd.org.
- **Citas de GOLD:** literales y de ≤25 palabras, por copyright.

**Leyenda de veredictos:**
- **CONFIRMADO:** el hallazgo es correcto en lo esencial.
- **CONFIRMADO PARCIAL:** es correcto en parte, o exagera su alcance o su severidad.
- **NO CONFIRMADO:** la fuente o el texto no lo sostienen.

---

## Resumen de veredictos

| Ítem | IDs | Veredicto | Severidad original → sugerida |
|---|---|---|---|
| F1 | MET-04 | CONFIRMADO PARCIAL | ALTA → MEDIA-ALTA |
| F2 | EPI-01 | CONFIRMADO | ALTA → ALTA |
| F3 | EPI-07 / EPI-10 / EPI-11 | CONFIRMADO (los tres) | MEDIA → MEDIA (EPI-07 y EPI-11); MEDIA → BAJA-MEDIA (EPI-10) |
| F4 | EXA-14 / EXA-15 | CONFIRMADO (ambos) | EXA-14 ALTA → ALTA; EXA-15 MEDIA → MEDIA-ALTA |
| F5 | IA-01 | CONFIRMADO PARCIAL | ALTA → MEDIA |
| F6 | REH-06 | CONFIRMADO | ALTA → MEDIA |
| F7 | FARM-01 | CONFIRMADO (con matices) | ALTA → MEDIA |
| F8 | MUL-01 / MUL-10 | MUL-01 CONFIRMADO; MUL-10 CONFIRMADO PARCIAL | MUL-01 CRÍTICA → ALTA; MUL-10 ALTA → MEDIA |
| F9 | EQ-09 / MUL-14 | CONFIRMADO | EQ-09 ALTA / MUL-14 MEDIA → MEDIA-ALTA (unificar) |
| F10 | EXA-09 | CONFIRMADO | ALTA → ALTA |

---

## F1 · Conflictos de interés y financiación (MET-04)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| F1 | MET-04 | **CONFIRMADO PARCIAL** | «*Disclosure forms for GOLD Committees are posted on the GOLD Website, www.goldcopd.org» (PDF 3). Es la única mención: el grep de `conflict\|disclosure\|funding\|sponsor\|competing\|unrestricted\|recus` no encuentra ninguna declaración de financiación ni de política de COI. | **Financiación.** goldcopd.org/about-us (https://goldcopd.org/about-us/): «As of July 1, 2014, GOLD's activities are funded entirely by the sale of its documents and resources».<br><br>**Declaraciones.** goldcopd.org/science-committee (https://goldcopd.org/science-committee/), pestaña «Disclosures»: los miembros declaran sus relaciones con empresas «in December of each year». El único documento enlazado es `BoD-and-SC-Disclosures_Binder_2022.pdf` (Last-Modified: 23-oct-2023), sin versión 2024-2025 localizable.<br><br>**Estándares.** Exigen que la propia guía incluya la financiación y la gestión de COI: Qaseem A et al. (G-I-N), Ann Intern Med 2012;156(7):525-31, PMID 22473437, DOI 10.7326/0003-4819-156-7-201204030-00009; Brouwers MC et al. (AGREE II, dominio 6), CMAJ 2010;182(18):E839-42, PMID 20603348, DOI 10.1503/cmaj.090449. | **Corrección al hallazgo:** el título «no se declaran» es **inexacto**. Las declaraciones existen online y el informe remite a ellas. Lo que sí se confirma:<br>(a) el documento no incluye una declaración de financiación;<br>(b) no describe ninguna política de gestión de COI (umbrales, recusación en las votaciones);<br>(c) las declaraciones públicas enlazadas corresponden a 2022 y no al ciclo de GOLD 2026;<br>(d) el modelo «venta de documentos» no revela quién compra ni en qué volumen.<br><br>**Ejemplo pertinente:** Boers 2025 (ref. 100, PMID 40254152) tiene como coautores a Wedzicha y Ozoh, miembros del comité (PDF 3), y la financia la industria (ResMed). Esto ilustra la necesidad de gestionar el COI, pero no prueba sesgo.<br><br>**Recomendación:** añadir en el propio PDF la financiación, la política de COI y las declaraciones vigentes (2025-26), y precisar cómo se gestionaron. | MEDIA-ALTA |

---

## F2 · Errores de cita en el capítulo 1 (EPI-01): muestra de 5 citas (más extras)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| F2.1 | EPI-01 | **CONFIRMADO** (cita errónea) | «11% of children with asthma had lung function impairment consistent with… COPD by early adulthood.(163-165)» (PDF 25) | Ref. 164 = Silva J et al. *Technological features of smartphone apps for physical activity promotion…* Pulmonology 2025;31(1):2416796, PMID 37394341. Trata de apps y no de asma infantil. Las refs. 163 (McGeachie, NEJM 2016;374:1842-52, PMID 27168434) y 165 (de Marco, AJRCCM 2011, PMID 20935112) sí son pertinentes. | Retirar la 164. La cifra del 11 % procede de McGeachie (163). | ALTA (conjunto) |
| F2.2 | EPI-01 | **CONFIRMADO** | «…patients with HIV… probably due to methylation disruptions in airway epithelium.(164,220,221)» (PDF 26) | La 220 (Hernández Cordero AI, Thorax 2021;76(5):448-55, PMID 33443234) es correcta. Ref. 221 = Lee H et al. *IgG subclass deficiency… mortality in hospitalized COPD*, Respir Res 2022;23:141, PMID 35641962: no trata del VIH ni de la metilación. La 164 = apps. | Dejar solo la 220. | — |
| F2.3 | EPI-01 | **CONFIRMADO** | «Poor air quality from air pollution also increases the risk of exacerbations, hospitalizations and mortality.(48-50)» (PDF 17) | Las 48 (Ross BA, Thorax 2023, PMID 37147124) y 50 (Robichaux CE, AnnalsATS 2025, PMID 40315387) son correctas. Ref. 49 = Regan EA et al. *Early Evidence of COPD Obscured by Race-Specific Prediction Equations*, AJRCCM 2024;209(1):59-69, PMID 37611073: no trata de contaminación. | Sustituir la 49. | — |
| F2.4 | EPI-01 | **CONFIRMADO** | «The WHO publishes mortality statistics for selected causes of death annually for all WHO regions.(91)» (PDF 21) | Ref. 91 = OMS, *Evidence-Informed Policy Network: EVIPNet in Action* (https://www.who.int/initiatives/evidence-informed-policy-network). Es una web de política informada por evidencia, no de estadísticas de mortalidad. | Citar la OMS Global Health Estimates o la WHO Mortality Database. | — |
| F2.5 | EPI-01 | **CONFIRMADO** | «The term dysanapsis refers to an anthropometric mismatch of airway tree caliber relative to lung volume.(132,133)» (PDF 24) | Ref. 132 = Barker DJ et al., BMJ 1991;303:671-5, PMID 1912913 (peso al nacer). Ref. 133 = Todisco T et al., Eur J Pediatr 1993;152:55-8, PMID 8444206 (prematuridad). La definición procede de Green M, Mead J, Turner JM, J Appl Physiol 1974;37:67-74, PMID 4836570 (ref. 119, citada en la frase siguiente). | Citar la ref. 119 y, si se desea, Smith BM, JAMA 2020. | — |
| F2.6 (extra) | EPI-01 | **CONFIRMADO** | «…reduced ventilatory drive (e.g., sedatives and hypnotic drugs), causing hypercapnic respiratory failure and acidosis.(280)» (PDF 29) | Ref. 280 = Elbehairy AF et al., AJRCCM 2015;191(12):1384-94, PMID 25826478: intercambio gaseoso en la EPOC leve. No trata de sedantes. | Sustituir. | — |
| F2.7 (extra) | EPI-01 | **CONFIRMADO** | «…all-cause mortality.(164,190)» (PDF 26) | La 190 (Diaz AA, JAMA 2023;329:1832-9, PMID 37210745) es correcta. La 164 = apps. | Retirar la 164; parece un patrón repetido de la ref. 164 «intrusa». | — |

**Matices de equidad (contra el hallazgo):**
- Dos casos del bloque EPI-01 no son errores de numeración, sino debilidades de la fuente:
  - ref. 239, un documento GINA-GOLD de 2017 que está desactualizado;
  - ref. 295, una «personal communication».
- La ref. 146 (Çolak 2024) para «pre-COPD» es discutible, no errónea: el origen (Han 2021, ref. 147) se cita en la frase siguiente.
- Aun excluyendo estos tres casos, la muestra contiene ≥7 citas inequívocamente erróneas. A ellas se suman:
  - la ref. 92 (PURE), citada para la precisión de la mortalidad;
  - la ref. 215 (PLATINO-TB), citada para los oxidantes en PDF 28;
  - la reutilización de la ref. 289 en PDF 30.
- El patrón sistemático queda **confirmado**.

---

## F3 · Cifras epidemiológicas y económicas (EPI-07 / EPI-10 / EPI-11)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| F3.1 | EPI-07 | **CONFIRMADO** | «…213.39 million cases… prevalence of 2.7% (2.5 age-standardized prevalence per 100,000) a change of −1.46% since 1990.(70)» (PDF 19) | Wang Z et al. *Global, regional, and national burden of COPD… GBD 2021*. Respir Res 2025;26(1):2. PMID 39748260; DOI 10.1186/s12931-024-03051-2. Datos: prevalencia estandarizada de **2.512,86 por 100.000** (IU 95 % 2.293,93-2.748,52); variación de −1,46 % (IU −3,36 a 0,39), **no significativa**. | Escribir «2.513 por 100.000 (≈2,5 %)». Indicar que la variación desde 1990 no es significativa.<br><br>**Matiz:** la guía no habla expresamente de «tendencia», así que esa parte del hallazgo es menor. | MEDIA |
| F3.2 | EPI-10 | **CONFIRMADO** | «…broad category of "COPD and allied conditions" (ICD-10 codes J42-46).» (PDF 21) | OMS, CIE-10 (https://icd.who.int/browse10/2019/en): J45 = asma y J46 = estado asmático. «COPD and allied conditions» es la rúbrica de la **CIE-9 (490-496)**. Según Wang 2025 (PMID 39748260), el GBD 2021 define la EPOC como J41, J42, J43, J44 y J47. | Escribir «CIE-10 J40-J44 (EPOC); CIE-9 490-496 "COPD and allied conditions"».<br><br>**Corrección al hallazgo:** el GBD incluye J47, no solo J41-J44. | BAJA-MEDIA |
| F3.3 | EPI-11 | **CONFIRMADO** | «…exacerbations are estimated to be $15.60 billion (a relative growth of 584% compared with 2025).(100)» (PDF 21) | Boers E, Allen A, Barrett M, et al. *Forecasting the Global Economic and Health Burden of COPD From 2025 Through 2050*. Chest 2025;168(4):880-9. PMID 40254152; DOI 10.1016/j.chest.2025.03.029. La cifra corresponde a **15.600 millones de exacerbaciones** acumuladas 2025-2050 (2.280 millones en 2025, lo que encaja con el +584 %), no a dólares. | Cambiar a «15.600 millones de exacerbaciones acumuladas». Revisar también «trillion»/«billion» en todo el párrafo. Mencionar la financiación del estudio (industria). | MEDIA |

---

## F4 · Reingresos y mortalidad hospitalaria (EXA-14 / EXA-15)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| F4.1 | EXA-14 | **CONFIRMADO** | «Readmissions occur in 30%-50% of patients within 30 days of discharge…» (PDF 119). **No lleva ninguna cita.** | **(1)** Waeijen-Smit K et al. ERJ Open Res 2024;10(1):00838-2023. PMID 38410700; DOI 10.1183/23120541.00838-2023. Metaanálisis con datos individuales (≈66.000 pacientes): reingreso del **7,1 %** a 30 días, 12,6 % a 90 días y 32,1 % a 1 año; mortalidad hospitalaria del 6,2 %.<br>**(2)** Ruan H et al. Respir Med 2023;206:107090. PMID 36528962; DOI 10.1016/j.rmed.2022.107090. Reingreso agrupado del **11 %** a 30 días y del 37 % a 1 año.<br>**(3)** Jencks SF, Williams MV, Coleman EA. N Engl J Med 2009;360(14):1418-28. PMID 19339721; DOI 10.1056/NEJMsa0803563. En Medicare, el reingreso global a 30 días fue del 19,6 % (EPOC ≈ 22-23 %). | Escribir «≈7-20 % a 30 días según el sistema sanitario (hasta ≈1/3 a 1 año)» y citar (1)-(3). El rango del 30-50 % se acerca a las tasas **a 1 año**, no a 30 días. | ALTA (afecta a indicadores de calidad y planificación) |
| F4.2 | EXA-15 | **CONFIRMADO** | «A large study of patients with COPD and acute respiratory failure reported in-hospital mortality of 17% to 49%.(1100)» (PDF 119) | Ref. 1100 = Gunen H et al. *Factors affecting survival of hospitalised patients with COPD*. Eur Respir J 2005;26(2):234-41. PMID 16055870; DOI 10.1183/09031936.05.00024804. Datos: **n = 205** (no es un estudio «grande»); **17 pacientes (8,3 %)** murieron en el hospital; mortalidad del 24 % a 6 meses y del 33 %, 39 % y 49 % a 1, 2 y 3 años. El «17 %» parece salir de confundir «17 pacientes». | Escribir «mortalidad hospitalaria del 8,3 % y mortalidad acumulada del 33-49 % a 1-3 años (n = 205)». Retirar «large». Puede añadirse como referencia pooled la mortalidad hospitalaria del 6,2 % de Waeijen-Smit 2024. | MEDIA-ALTA |

---

## F5 · Revisión Cochrane de telesalud (IA-01, PDF 146)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| F5 | IA-01 | **CONFIRMADO PARCIAL** | «A Cochrane review(1435) on telehealth for remote monitoring and consultations… included three main different models that have been studied in RCTs» (PDF 146) | **Referencia citada (errónea).** Ref. 1435 = Janjua S, Pike KC, Carr R, Coles A, Fortescue R, Batavia M. *Interventions to improve adherence to pharmacological therapy for COPD*. Cochrane 2021;9:CD013381. PMID 34496032. Es la revisión **equivocada**.<br><br>**Revisión correcta:** Janjua S, Carter D, Threapleton CJ, Prigmore S, Disler RT. *Telehealth interventions: remote monitoring and consultations for people with COPD*. Cochrane 2021;7:CD013196. PMID 34693988; DOI 10.1002/14651858.CD013196.pub2. Resultados:<br>- 29 ECA (n = 5654), 5 de ellos síncronos;<br>- no hay evidencia para la comparación de **consultas remotas**;<br>- monitorización + atención habitual: menos reingresos por EPOC (HR 0,42; 1 estudio, n = 106);<br>- intervenciones multicomponente: menos hospitalizaciones (OR 0,50; 3 estudios, n = 344).<br><br>**Revisión anterior:** McLean S et al. Cochrane 2011;CD007718. PMID 21735417; DOI 10.1002/14651858.CD007718.pub2. Hospitalización OR 0,46 y urgencias OR 0,27. Está superada, así que no citarla es correcto. | **Confirmado:**<br>(a) la referencia está equivocada;<br>(b) se da a entender que la teleconsulta se estudió en ECA, cuando la revisión no halló evidencia;<br>(c) se omiten el comparador multicomponente y la señal sobre reingresos.<br><br>**No confirmado / injusto:** criticar la frase «no evidence of harm». GOLD **parafrasea fielmente** las conclusiones de los autores Cochrane, así que es un matiz metodológico (ausencia de evidencia ≠ evidencia de ausencia), no una tergiversación.<br><br>**Corrección:** sustituir la referencia por CD013196 y aclarar que no hay ECA de teleconsulta frente a la atención habitual. | MEDIA |

---

## F6 · Definición de LTOT frente a REDOX (REH-06, PDF 87)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| F6 | REH-06 | **CONFIRMADO** | «The long-term administration of oxygen (> 15 hours per day; LTOT) is indicated…» y, en el mismo apartado: «the recommendation to use oxygen > 15 hours per day is not supported by newer evidence.» (PDF 87) | **REDOX:** Ekström M et al. *Long-Term Oxygen Therapy for 24 or 15 Hours per Day in Severe Hypoxemia*. N Engl J Med 2024;391(11):977-88. PMID 39254466; DOI 10.1056/NEJMoa2402638.<br>- n = 241; 24 h frente a 15 h.<br>- Hospitalización o muerte a 1 año: 124,7 frente a 124,5 eventos por 100 personas-año; HR 0,99 (IC 95 % 0,72-1,36). Fuentes secundarias dan 64,1 % frente a 63,7 % y que el ensayo se detuvo por futilidad.<br>- El propio resumen asume que **≥15 h/día prolonga la supervivencia**.<br><br>**Ensayos clásicos:** NOTT (Ann Intern Med 1980;93:391-8) y MRC (Lancet 1981;1:681-6). En PDF 92, la guía describe el MRC como «≥15 h vs no oxygen». | Definir la LTOT como «**≥15 h/día**». Reescribir así: «24 h/día no aporta beneficio adicional frente a 15 h/día (REDOX)».<br><br>**Matiz:** la incoherencia es real, pero de redacción. La guía mantiene las indicaciones de la LTOT, así que el riesgo de que se lea «la LTOT ya no está indicada» es bajo. Por eso rebajo la severidad. | MEDIA |

---

## F7 · Vacunación frente al VRS: ACIP frente a la guía (FARM-01, PDF 69-70 y 121)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| F7 | FARM-01 | **CONFIRMADO (con matices)** | **Fig 3.6 (imagen, PDF 69):** «RSV vaccination for individuals aged ≥ 50 years and/or with chronic heart or lung disease, as recommended by the CDC (Evidence A)».<br><br>**Texto (PDF 70):** «For adults aged ≥75 years, the vaccination is universally recommended for if they have not been previously vaccinated.» Esta frase contiene una errata. | **CDC, guía clínica de VRS en adultos** (https://www.cdc.gov/rsv/hcp/vaccine-clinical-guidance/adults.html):<br>- todas las personas de ≥75 años;<br>- de 50 a 74 años solo con riesgo aumentado (incluye la EPOC);<br>- **dosis única**, sin revacunación;<br>- **no** se recomienda en 18-49 años.<br><br>La ampliación a 50-59 años la votó ACIP en abril de 2025 y la adoptó el HHS el 25-jun-2025.<br><br>**Recomendación previa:** Britton A et al. MMWR 2024;73(32):696-702. PMID 39146277; DOI 10.15585/mmwr.mm7332e1.<br><br>**Seguridad:**<br>- FDA, 7-ene-2025: advertencia de **síndrome de Guillain-Barré** en la ficha técnica de Abrysvo y Arexvy (≈9 y ≈7 casos en exceso por millón de dosis en 42 días).<br>- Hause AM et al. MMWR 2024;73(21):489-94. PMID 38814851; DOI 10.15585/mmwr.mm7321a3.<br><br>**Ref. 645** (Wodi AP, MMWR 2025;74(2):30-3, PMID 39820474) es el calendario de enero de 2025, todavía con el umbral de 60-74 años. | **Confirmado:**<br>- «and/or with chronic… lung disease» extiende la recomendación a personas de <50 años con EPOC, algo que ACIP no recomienda;<br>- se atribuye a la recomendación de 50-59 años una evidencia «A» que no está justificada;<br>- no se mencionan la dosis única, la no revacunación ni la señal de SGB;<br>- la «European Commission» autoriza la comercialización, no emite recomendaciones de vacunación;<br>- en el cap. 4 (PDF 121) se afirma que la vacuna del VRS reduce exacerbaciones con refs. (635, 1114-1116) que no tratan del VRS.<br><br>**Matiz:** para las personas con EPOC de ≥50 años, el resultado práctico **coincide** con el CDC, y el texto de PDF 70 describe correctamente el esquema ≥75 / 50-74 con riesgo. La discrepancia se limita a <50 años, al nivel de evidencia y a la seguridad.<br><br>**Corrección:** «Dosis única en ≥75 años y en 50-74 años con EPOC (ACIP 2025); <50 años según la normativa nacional o la ficha técnica; advertir del riesgo de SGB». | MEDIA |

---

## F8 · Cribado de cáncer de pulmón con LDCT (MUL-01 / MUL-10; PDF 57, 123, 130-131, 140-141)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| F8.1 | MUL-01 | **CONFIRMADO** | **Fig 5.6 (imagen, PDF 141; título «…in all Patients with COPD – Regular Follow-up»):** «Yearly… Medications check, spirometry, chest HRCT (cancer screening), SpO₂».<br><br>**Fig 5.5 (PDF 140):** «Spirometry, chest X-ray, chest HRCT, lung volumes, DLco, SpO₂» en la evaluación inicial. | **USPSTF:** Krist AH et al. *Screening for Lung Cancer: USPSTF Recommendation Statement*. JAMA 2021;325(10):962-70. PMID 33687470; DOI 10.1001/jama.2021.1117. LDCT anual en personas de 50-80 años con ≥20 paquetes-año, fumadoras activas o que dejaron de fumar hace <15 años. Se deja de cribar si pasan 15 años sin fumar o si la esperanza de vida es limitada.<br><br>**Fuente de la figura:** Celli BR et al. *A person-centred clinical approach to the multimorbid patient with COPD*. Eur J Intern Med 2025. PMID 40803921; DOI 10.1016/j.ejim.2025.07.020. Es un consenso Delphi de miembros de GOLD, no evidencia de cribado. | La figura propone una TC **de alta resolución** anual «de cribado» para **todos** los pacientes. Eso contradice el texto de la propia guía (PDF 123 y 130-131, que excluye a los no fumadores) y los criterios de la USPSTF.<br><br>**Corrección:** «LDCT anual solo si se cumplen los criterios de cribado y el paciente es candidato a tratamiento curativo, tras decisión compartida». En la Fig 5.5: «TC según las indicaciones del cap. 2 (Fig 2.14)».<br><br>**Matiz:** el título dice «Potential Complementary Approach», lo que suaviza el tono, pero la etiqueta «(cancer screening)» es inequívoca. Rebajo de CRÍTICA a ALTA porque no es una recomendación textual con nivel de evidencia. | ALTA |
| F8.2 | MUL-10 | **CONFIRMADO PARCIAL** | **Punto clave (PDF 123):** «An annual LDCT scan is recommended for lung cancer screening in patients with a smoking history, similar to recommendations for the general population.»<br><br>**Fig 5.4 (PDF 130):** «Age > 55 years · Smoking history > 30 pack years… BMI < 25 kg/m²».<br><br>**Cap. 2 (PDF 57):** «American Cancer Society… 50-80 with 20 pack years… regardless of years since quitting». | **USPSTF 2021:** igual que en F8.1. **El texto de PDF 130 la reproduce correctamente.**<br><br>**ACS:** Wolf AMD et al. *Screening for lung cancer: 2023 guideline update from the American Cancer Society*. CA Cancer J Clin 2024;74(1):50-81. PMID 37909877; DOI 10.3322/caac.21811. Criterios: 50-80 años, ≥20 paquetes-año, fumadores o exfumadores, **sin límite de años desde el abandono**. **PDF 57 la atribuye correctamente.** | **Confirmado:**<br>- se citan dos criterios distintos (ACS en el cap. 2, USPSTF en el cap. 5) sin conciliarlos;<br>- la Fig 5.4 mantiene los umbrales del NLST (>55 años, >30 paquetes-año) junto a criterios vigentes más amplios.<br><br>**Exagerado:**<br>- La Fig 5.4 se titula «Common Risk Factors for the Development of Lung Cancer». Es una lista de factores de riesgo, no de criterios de elegibilidad, así que no «contradice» a la USPSTF como norma.<br>- El punto clave remite a las recomendaciones de la población general («similar to…»), por lo que no propone cribar a *cualquier* fumador.<br>- PDF 57 y PDF 130 describen fielmente a la ACS y a la USPSTF.<br><br>**Corrección:** unificar los criterios en el punto clave (USPSTF 2021 / ACS 2023 / programa nacional) y actualizar los umbrales de la Fig 5.4 o retirar los números. | MEDIA |

---

## F9 · Depresión por sexo en la EPOC (EQ-09 / MUL-14, PDF 133)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| F9 | EQ-09, MUL-14 | **CONFIRMADO** | «…(all approximately 34%), whereas depression alone is more common in men than women (61% versus 39%).(88,327,1276,1278)» (PDF 133). Ese «34 %» se aplica a la ansiedad sola y a la ansiedad + depresión. | **Ref. 327:** Hanania NA et al. *Determinants of depression in the ECLIPSE COPD cohort*. AJRCCM 2011;183(5):604-11. PMID 20889909; DOI 10.1164/rccm.201003-0472OC. Depresión en el 26 % de los pacientes con EPOC, con «higher depression prevalence… in females». El **sexo femenino** es un determinante independiente.<br><br>**Ref. 1278:** Yohannes AM, Casaburi R, Dryden S, Hanania NA. Respir Med 2022;197:106850. PMID 35427843; DOI 10.1016/j.rmed.2022.106850. Muestra de rehabilitación (n = 734, 51 % varones): depresión + ansiedad 34 %, **ansiedad sola 20 %**, **depresión sola 5 %**. El resumen no ofrece ningún desglose por sexo de 61/39.<br><br>**Ref. 88:** Chen W et al. Lancet Respir Med 2015;3(8):631-9. PMID 26208998. Trata de comorbilidad **cardiovascular** y es irrelevante aquí.<br><br>**Ref. 1276:** Maurer J et al. Chest 2008;134(4 Suppl):43S-56S. PMID 18842932. Taller narrativo sin el dato 61/39. | **Confirmado:**<br>- la afirmación «more common in men» contradice la ref. 327;<br>- «all approximately 34%» es falso para la ansiedad sola (20 %);<br>- el 61/39 parece la composición por sexo de un subgrupo pequeño (depresión sola ≈5 % de 734, es decir, ≈37 personas), no una prevalencia. No pude verificarlo en el texto completo, que es de pago.<br><br>**Corrección:** «La depresión es más prevalente en mujeres con EPOC (ECLIPSE); ≈1 de cada 3 pacientes en rehabilitación presenta ansiedad y depresión concomitantes». Retirar la ref. 88. | MEDIA-ALTA (unificar EQ-09 y MUL-14; riesgo de infra-cribado en mujeres) |

---

## F10 · Antivirales y etiología viral de las exacerbaciones (EXA-09)

| Ítem | IDs | Veredicto | Qué dice la guía | Qué dice la fuente primaria | Corrección necesaria | Severidad sugerida |
|---|---|---|---|---|---|---|
| F10 | EXA-09 | **CONFIRMADO** | «Exacerbations are mainly triggered by respiratory viral infections…» (PDF 110).<br><br>La Fig 4.2 (imagen, PDF 107) termina en «Determine etiology: viral testing, sputum culture, other».<br><br>**Grep en todo el documento** de `oseltamivir\|antiviral\|anti-viral\|nirmatrelvir\|remdesivir\|Paxlovid\|baloxavir\|zanamivir\|molnupiravir\|neuraminidase\|peramivir`: **0 coincidencias**. La COVID-19 solo aparece en relación con la vacunación (PDF 61 y 70). | **Gripe:** Uyeki TM et al. *Clinical Practice Guidelines by the IDSA: 2018 Update on… Seasonal Influenza*. Clin Infect Dis 2019;68(6):e1-e47. PMID 30566567; DOI 10.1093/cid/ciy866. Recomienda tratamiento antiviral precoz en pacientes hospitalizados con gripe, sea cual sea el tiempo de evolución, y en ambulatorios de alto riesgo, incluidas las enfermedades pulmonares crónicas.<br><br>**COVID-19:** guía IDSA (https://www.idsociety.org/practice-guideline/covid-19-guideline-treatment-and-management/). Recomienda nirmatrelvir/ritonavir o remdesivir en ambulatorios de alto riesgo. | La guía afirma que la etiología es mayoritariamente viral y recomienda hacer pruebas virales, pero no dice qué hacer si salen positivas. Es una omisión clínicamente relevante e incoherente.<br><br>**Corrección:** añadir un apartado breve de tratamiento antiviral, con oseltamivir ante gripe sospechada o confirmada y antivirales frente al SARS-CoV-2 según las guías vigentes, enlazado con la Fig 4.2. | ALTA |

---

## Observaciones finales sobre la calidad de los hallazgos del enjambre

1. **Hallazgos sólidos y verificados contra la fuente primaria:**
   - EPI-01, EPI-07, EPI-10 y EPI-11;
   - EXA-14 y EXA-15;
   - MUL-01;
   - EQ-09/MUL-14;
   - EXA-09.

   Varios errores de GOLD son de transcripción numérica y se corrigen con facilidad: unidades, «17 pacientes» leído como «17 %», «exacerbaciones» leído como «$», y códigos CIE-9 presentados como CIE-10.
2. **Hallazgos que exageran:**
   - **MET-04:** el título «no se declaran» es inexacto, porque las declaraciones existen online, aunque están desactualizadas.
   - **IA-01:** la crítica a «no evidence of harm» es injusta, porque reproduce la conclusión Cochrane.
   - **REH-06 y FARM-01:** la severidad está inflada.
   - **MUL-10:** la Fig 5.4 es una lista de factores de riesgo, y PDF 57 y PDF 130 citan correctamente a la ACS y a la USPSTF.
   - **MUL-01:** marcado como CRÍTICA cuando es ALTA.
3. **Correcciones a los propios hallazgos:**
   - El GBD codifica la EPOC como J41-J44 + J47 (EPI-10).
   - El 64,1 % frente a 63,7 % de REDOX procede de fuentes secundarias, no del resumen (REH-06).
   - Las refs. 239, 295 y 146 de EPI-01 son debilidades de la fuente, no errores de numeración.
