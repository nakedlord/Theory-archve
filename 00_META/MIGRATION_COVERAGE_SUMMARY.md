# Migration Coverage Summary

Статус: repository-level migration summary
Дата: 2026-04-25

## Назначение

Этот файл фиксирует общий статус миграции теоретического архива в GitHub.

Он не заменяет module-level `COVERAGE.md` и `MIGRATION_CLOSURE.md`, а собирает общую картину по всем основным модулям.

Главное правило:

```text
structurally migrated ≠ source verified ≠ canonized
```

---

## 1. Общий результат

Основные модули перенесены структурно:

```text
01_R_THEORY
02_SYNTAX
03_CULTURE_AS_INSTRUCTIONS
04_MEAT
05_PNA
06_BOUNDARY_SATURATION
```

Для каждого модуля создана карта покрытия и closure-файл.

Статус всего архива:

```text
core theory archive structurally migrated
source verification remains open
```

---

## 2. R Theory

### Статус

```text
structurally closed for migration / source verification open
```

### Ключевые файлы

- `01_R_THEORY/COVERAGE.md`
- `01_R_THEORY/OPEN_GAPS.md`
- `01_R_THEORY/CANON_REVIEW.md`
- `01_R_THEORY/PATCHES/PATCH_INDEX.md`
- `01_R_THEORY/VERSIONS/VERSION_COMPARISON_v3.1_v3.2.md`
- `01_R_THEORY/ARCHAEOLOGY/ARCHAEOLOGY_INDEX.md`
- `01_R_THEORY/ARCHAEOLOGY/SOURCE_VERIFICATION_PLAN.md`
- `01_R_THEORY/EVIDENCE/EVIDENCE_INDEX.md`
- `01_R_THEORY/CASES/CASE_INDEX.md`
- `01_R_THEORY/SOURCE_VERIFICATION_PLAN.md`
- `01_R_THEORY/CROSS_LINKS.md`
- `01_R_THEORY/MIGRATION_CLOSURE.md`

### Canon status

```text
R Theory v3.2 = active canon
```

### Open status

Source verification is required, especially for archaeology, brain size, sapiens/neanderthals, stress/mismatch and developmental claims.

---

## 3. SynTax

### Статус

```text
structurally closed for migration / source verification open
```

### Ключевые файлы

- `02_SYNTAX/COVERAGE.md`
- `02_SYNTAX/OPEN_GAPS.md`
- `02_SYNTAX/CANON_REVIEW.md`
- `02_SYNTAX/PATCHES/PATCH_INDEX.md`
- `02_SYNTAX/MIGRATION_CLOSURE.md`

### Canon status

```text
SynTax = active infrastructure
```

### Open status

Needs source verification against original SynTax chats. Early error classes and portable Syntax.md may need source-level correction.

---

## 4. Culture as Externalized Instructions

### Статус

```text
structurally closed for migration / source and textual verification open
```

### Ключевые файлы

- `03_CULTURE_AS_INSTRUCTIONS/COVERAGE.md`
- `03_CULTURE_AS_INSTRUCTIONS/OPEN_GAPS.md`
- `03_CULTURE_AS_INSTRUCTIONS/CANON_REVIEW.md`
- `03_CULTURE_AS_INSTRUCTIONS/CASES/CASE_INDEX.md`
- `03_CULTURE_AS_INSTRUCTIONS/SOURCE_VERIFICATION_PLAN.md`
- `03_CULTURE_AS_INSTRUCTIONS/MIGRATION_CLOSURE.md`

### Canon status

```text
Culture as Externalized Instructions v1.1 = active canon
```

### Open status

Textual verification is required for New Testament / Mark / Passion narrative files. Source verification is required for mythologization, ritual, institution and social memory claims.

---

## 5. MEAT

### Статус

```text
structurally closed for migration / source and concrete case verification open
```

### Ключевые файлы

- `04_MEAT/COVERAGE.md`
- `04_MEAT/OPEN_GAPS.md`
- `04_MEAT/CANON_REVIEW.md`
- `04_MEAT/CASES/CASE_INDEX.md`
- `04_MEAT/MIGRATION_CLOSURE.md`

### Model status

```text
MEAT v0.2 = active qualitative model
```

### Open status

MCCR remains recovery draft / needs source. MEAT metrics are qualitative, not numerical. Concrete cases are still needed.

---

## 6. PNA

### Статус

```text
structurally closed for migration / source verification and operationalization open
```

### Ключевые файлы

- `05_PNA/COVERAGE.md`
- `05_PNA/OPEN_GAPS.md`
- `05_PNA/CANON_REVIEW.md`
- `05_PNA/SOURCE_VERIFICATION_PLAN.md`
- `05_PNA/MIGRATION_CLOSURE.md`

### Hypothesis status

```text
PNA = draft hypothesis with source route
```

### Open status

PNA is not canon. Operational definition, amplitude, coherence, 2–5 second window, R3 modes and heart-like regulation all require caution and sources.

---

## 7. Boundary Saturation

### Статус

```text
structurally closed for migration / physics verification open
```

### Ключевые файлы

- `06_BOUNDARY_SATURATION/COVERAGE.md`
- `06_BOUNDARY_SATURATION/OPEN_GAPS.md`
- `06_BOUNDARY_SATURATION/CANON_REVIEW.md`
- `06_BOUNDARY_SATURATION/MIGRATION_CLOSURE.md`

### Model status

```text
Boundary Saturation = speculative formal model
```

### Open status

Not established physics. Needs dimension definitions, GR compatibility checks, source verification and clear separation of analogy and physical claim.

---

## 8. Archive and unresolved nodes

### EAT

Статус:

```text
archived / isolated speculative node
```

Файл:

- `99_ARCHIVE/EAT_entanglement_axis_theory.md`

### MCCR

Статус:

```text
recovery draft / needs source
```

Файл:

- `04_MEAT/VERSIONS/mccr_recovery_draft.md`

---

## 9. Repository-level operational files

Основные управляющие файлы:

- `00_META/MIGRATION_MODE.md`
- `00_META/MIGRATION_STATUS_RULES.md`
- `00_META/IMPORT_BACKLOG.md`
- `00_META/CANDIDATE_TO_CANON_CHECKLIST.md`
- `00_META/FIELD_MAP.md`
- `00_META/COVERAGE_AUDIT_2026-04-25.md`
- `00_META/DEVELOPMENT_PLAN.md`

Нужно добавить / создано в этом этапе:

- `00_META/MIGRATION_COVERAGE_SUMMARY.md`
- `00_META/OPEN_GAPS.md`
- `00_META/SOURCE_VERIFICATION_PLAN.md`

---

## 10. Overall status table

| Module | Migration | Canon / Model status | Verification |
|---|---|---|---|
| R Theory | structurally closed | active canon v3.2 | source verification open |
| SynTax | structurally closed | active infrastructure | source verification open |
| Culture | structurally closed | active canon v1.1 | source/text verification open |
| MEAT | structurally closed | active qualitative model v0.2 | concrete cases/source open |
| PNA | structurally closed | draft hypothesis | source/operationalization open |
| Boundary Saturation | structurally closed | speculative formal model | physics verification open |
| EAT | archived | not active | needs source if reactivated |
| MCCR | recovery draft | not active | needs source |

---

## 11. Repository-level conclusion

```text
Core migration is structurally complete enough to stop module-hopping migration.
Next phase should be source verification, not theory development.
```

Recommended next phase:

```text
source verification pass, module by module
```

Suggested order:

1. R Theory sources;
2. Culture textual/source verification;
3. PNA cognitive sources;
4. MEAT concrete cases;
5. Boundary physics verification;
6. SynTax source/chats verification.
