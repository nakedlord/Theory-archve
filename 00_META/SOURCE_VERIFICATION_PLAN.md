# Repository Source Verification Plan

Статус: repository-level source verification plan
Дата: 2026-04-25

## Назначение

Этот файл задаёт общий план источниковой проверки всего теоретического архива после структурной миграции.

Главное правило:

```text
verify sources before developing or canon-expanding
```

---

## 1. Verification principles

### 1.1 Source does not prove theory directly

Источник может поддерживать отдельный мост, факт или ограничение.

Он не доказывает всю теорию целиком.

### 1.2 Separate source claim and theory reading

Формат проверки:

```text
source -> what source says -> extracted claim -> theory interpretation -> confidence status
```

### 1.3 Confidence statuses

Использовать статусы:

- supported;
- plausible;
- contested;
- speculative;
- needs source;
- archived.

### 1.4 No canon update during source collection

Пока идёт сбор источников, `CANON.md` не расширять автоматически.

---

## 2. Verification order

Рекомендуемый порядок:

1. R Theory;
2. Culture as Instructions;
3. PNA;
4. MEAT;
5. Boundary Saturation;
6. SynTax source/chat verification.

Причина:

R Theory и Culture являются центральным содержательным ядром архива. PNA и MEAT являются мостами. Boundary требует физической строгости. SynTax требует сверки с исходными чатами, но уже достаточно структурирован.

---

## 3. R Theory verification

Module plan:

- `01_R_THEORY/SOURCE_VERIFICATION_PLAN.md`
- `01_R_THEORY/ARCHAEOLOGY/SOURCE_VERIFICATION_PLAN.md`

### Priority topics

- Acheulean / late Acheulean;
- fire / camp / childhood;
- death / burial / ochre;
- sapiens / neanderthals networks;
- demography and innovation;
- Oldowan;
- Lomekwi;
- brain size steps;
- stress / mismatch;
- scaffolding and causal development.

### Output files to create later

```text
01_R_THEORY/SOURCES/archaeology_core_sources.md
01_R_THEORY/SOURCES/cognitive_development_sources.md
01_R_THEORY/SOURCES/stress_mismatch_sources.md
01_R_THEORY/SOURCES/cultural_transmission_sources.md
01_R_THEORY/SOURCES/brain_size_sources.md
01_R_THEORY/SOURCES/symbol_concept_sources.md
```

---

## 4. Culture verification

Module plan:

- `03_CULTURE_AS_INSTRUCTIONS/SOURCE_VERIFICATION_PLAN.md`

### Priority topics

- cultural transmission;
- distributed cognition / external memory;
- ritual transmission;
- institution formation;
- mythologization;
- social memory;
- oral tradition;
- New Testament / Mark / Passion narrative textual studies.

### Output files to create later

```text
03_CULTURE_AS_INSTRUCTIONS/SOURCES/cultural_transmission_sources.md
03_CULTURE_AS_INSTRUCTIONS/SOURCES/mythologization_sources.md
03_CULTURE_AS_INSTRUCTIONS/SOURCES/ritual_institution_sources.md
03_CULTURE_AS_INSTRUCTIONS/SOURCES/mark_gospel_sources.md
03_CULTURE_AS_INSTRUCTIONS/SOURCES/new_testament_textual_sources.md
```

---

## 5. PNA verification

Module plan:

- `05_PNA/SOURCE_VERIFICATION_PLAN.md`

### Priority topics

- working memory and attention;
- temporal integration / subjective present;
- predictive processing;
- mental simulation;
- speech / narrative / self-regulation;
- sleep and memory consolidation;
- error monitoring and cognitive control;
- neural oscillations / attention sampling only if revisiting heart-like regulation.

### Output files to create later

```text
05_PNA/SOURCES/working_memory_attention_sources.md
05_PNA/SOURCES/temporal_integration_sources.md
05_PNA/SOURCES/predictive_processing_sources.md
05_PNA/SOURCES/mental_simulation_sources.md
05_PNA/SOURCES/speech_narrative_sources.md
05_PNA/SOURCES/error_monitoring_sources.md
```

---

## 6. MEAT verification

### Priority topics

- memetics;
- cultural transmission;
- social memory;
- ritual studies;
- political communication;
- narrative archetypes;
- network theory as analogy;
- concrete case selection.

### Critical unresolved node

```text
MCCR requires source recovery
```

### Output files to create later

```text
04_MEAT/SOURCE_VERIFICATION_PLAN.md
04_MEAT/SOURCES/memetics_sources.md
04_MEAT/SOURCES/ritual_metric_sources.md
04_MEAT/SOURCES/political_slogan_sources.md
04_MEAT/SOURCES/archetype_sources.md
04_MEAT/SOURCES/mccr_recovery_source.md
```

---

## 7. Boundary Saturation verification

### Priority topics

- Schwarzschild radius / compactness;
- GR compatibility;
- black hole thermodynamics;
- holographic principle;
- Page curve;
- information paradox;
- gravitational redshift;
- scrambling;
- dimensional analysis.

### Output files to create later

```text
06_BOUNDARY_SATURATION/SOURCE_VERIFICATION_PLAN.md
06_BOUNDARY_SATURATION/SOURCES/compactness_sources.md
06_BOUNDARY_SATURATION/SOURCES/holography_sources.md
06_BOUNDARY_SATURATION/SOURCES/page_curve_sources.md
06_BOUNDARY_SATURATION/SOURCES/redshift_sources.md
06_BOUNDARY_SATURATION/SOURCES/scrambling_sources.md
```

### Rule

No physical claim upgrade without source and dimensional verification.

---

## 8. SynTax verification

### Priority topics

- original SynTax chat verification;
- patch history v1.9–v4.9;
- early error classes;
- portable Syntax.md;
- Goal Module;
- activation prompt archive.

### Output files to create later

```text
02_SYNTAX/SOURCE_VERIFICATION_PLAN.md
02_SYNTAX/SOURCES/original_chat_reconstruction.md
02_SYNTAX/SOURCES/patch_history_verification.md
```

### Rule

SynTax verification is mostly internal/source-chat verification, not academic literature verification.

---

## 9. Verification workflow

For each module:

```text
1. Create source card
2. List claims
3. Add sources
4. Extract what sources actually say
5. Compare to theory reading
6. Assign confidence status
7. Update module OPEN_GAPS.md
8. Update module MIGRATION_CLOSURE.md if status changes
9. Only then consider canon update
```

---

## 10. What not to do during verification

Do not:

- search randomly without claim list;
- use weak sources for strong claims;
- treat compatibility as proof;
- upgrade migration drafts to canon;
- mix analogy and physical claim;
- collapse textual, historical and theological layers;
- use MCCR before recovery;
- use PNA as proof of R Theory.

---

## 11. Current repository verification status

```text
source verification planned
source verification not started at repository level
module-level plans exist for R Theory, Culture and PNA
MEAT, Boundary and SynTax still need local source verification plans if verification begins there
```

## 12. Recommended next action

Start with:

```text
01_R_THEORY/SOURCES/archaeology_core_sources.md
```

or, if continuing migration closure instead of source verification:

```text
00_META/REPOSITORY_MIGRATION_CLOSURE.md
```
