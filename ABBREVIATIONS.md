# Part B — Abbreviations List

Extracted from `Abstract.docx`, `Introduction.docx`, `Methods.docx`, `Discussion.docx` and the Results text. Expansions are taken from your own documents wherever you defined them; items marked ⚠️ are used in the text but never expanded, and need your decision or verification.

**Placement:** after Keywords, before Introduction — per 4D Lab SOP section order, item 6. Front matter, not an appendix. This also addresses Meeting 5 common dissertation error #11 ("too many abbreviations/acronyms, without an appropriate abbreviations list").

---

## The list — 32 entries

| Abbreviation | Expansion | Source |
|---|---|---|
| 4D-flow CMR | four-dimensional flow cardiovascular magnetic resonance | your text — Abstract |
| AF | atrial fibrillation | your text — Methods |
| AR | aortic regurgitation | your text — Methods |
| AS | aortic stenosis | your text — Abstract |
| AVA | aortic valve area | your text — Introduction |
| BMI | body mass index | your text — Methods |
| CI | confidence interval | ⚠️ see note 3 |
| CMR | cardiovascular magnetic resonance | your text — Methods |
| COPD | chronic obstructive pulmonary disease | your text — Methods |
| ECG | electrocardiographic | ⚠️ never expanded |
| EDV | end-diastolic volume | your text — Abstract |
| ESV | end-systolic volume | your text — Methods |
| FOV | field of view | your text — Methods |
| FullRR | full cardiac cycle | your text — Abstract |
| GRAPPA | generalised autocalibrating partially parallel acquisition | ⚠️ never expanded — verify against source |
| IHD | ischaemic heart disease | your text — Methods |
| IQR | interquartile range | your text — Methods |
| KE | kinetic energy | your text — Methods |
| LV | left ventricular | your text — Abstract |
| LVEF | left ventricular ejection fraction | your text — Abstract |
| LVOT | left ventricular outflow tract | ⚠️ never expanded |
| NNUH | Norfolk and Norwich University Hospital | your text — Methods |
| NYHA | New York Heart Association | your text — Methods |
| PV | pressure–volume | your text — Introduction |
| PVA | pressure–volume area | your text — Methods |
| REC | Research Ethics Committee | ⚠️ see note 2 |
| R–R | R-wave to R-wave interval | ⚠️ never expanded |
| SD | standard deviation | your text — Methods |
| TE | echo time | ⚠️ never expanded — verify against source |
| TR | repetition time | ⚠️ never expanded — verify against source |
| TTE | transthoracic echocardiography | your text — Introduction |
| VENC | velocity encoding | your text — Methods |

---

## Notes requiring your action

**1. Six used but never expanded: ECG, GRAPPA, LVOT, R–R, TE, TR.**

GRAPPA, TE, TR and FOV each appear only once, in the Methods 2.3 acquisition parameters, and derive from the published PREFER-CMR protocol you cite. **Verify those four expansions against that paper** rather than accepting the standard renderings above. Two valid options for them: expand at first use in Methods 2.3, or list them here — not both.

**2. REC — inconsistent as written.** Methods currently reads *"the National Research Ethics Service under REC reference 21/NE/0149."* NRES and REC are different bodies; REC is the Research Ethics Committee. Confirm which is correct for reference 21/NE/0149 before finalising this entry.

**3. CI — defined after first use.** Methods defines *"confidence intervals (CIs)"*, but the singular **CI** appears in the Abstract, Results and Discussion, and the Abstract use precedes the Methods definition. List as **CI**.

---

## Three entries deliberately excluded — not abbreviations

| Term | Why | What it needs instead |
|---|---|---|
| **MASS** | Analysis software | Identification at first use — developer and version. It currently appears in the Abstract with no indication that it is software. |
| **SPSS** | Product name | Already correct as written: "IBM SPSS Statistics version 32" |
| **PREFER-CMR** | Study/registry acronym | Full registry name at first use, or a statement that it is a registry. It currently appears in the Abstract cold. |

---

## Confirmed not required

- **SV** — "stroke volume" is written in full throughout. Do not add.
- **MRI** — never used; CMR is used consistently.
- **TKE** — appears only inside a bracketed editorial note in the Discussion reference list. Unused once that note is deleted (see below).

---

## Two defects found during extraction

**1. `Results.docx` is absent from this repository.** Abstract, Introduction, Methods and Discussion are present; Results is not. The only copy on disk is in the `Desertation-` repository and it is stale — Table 1 there carries **`[Pending]` placeholders in the control column**:

> `28.5 ± 4.1* [Pending] · Heart rate, bpm 67.4 ± 7.9 [Pending] · Systolic BP, mmHg 144.4 ± 20.5 [Pending] · Diastolic BP, mmHg 70.8 ± 7.3 [Pending]`

Check whichever Results file you are assembling from for those placeholders, and add the current version to this repository alongside the other sections.

**2. `Discussion.docx` contains an editorial note in its reference list:**

> `...the master list if the specific Dyverfeldt paper used for the aortic TKE/pressure-loss statement is separate from reference 10.]`

Delete this when rebuilding the Discussion reference list. It is currently sitting in a submission document.
