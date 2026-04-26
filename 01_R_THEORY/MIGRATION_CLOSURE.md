# R Theory Migration Closure

Статус: migration closure / source verification still required
Дата: 2026-04-25

## Назначение

Этот файл фиксирует временное закрытие миграции R-теории на текущем этапе.

Закрытие миграции не означает, что теория полностью проверена источниками.

Оно означает, что текущие известные наработки по R-теории перенесены в GitHub, разложены по статусам и получили карту дальнейшей проверки.

---

## 1. Migration result

```text
R Theory migration: broadly transferred
```

Перенесены основные слои:

- active canon;
- версии;
- патчи;
- кейсы;
- археология;
- evidence;
- фальсификация;
- cross-links;
- source verification plan;
- coverage / gaps / canon review.

---

## 2. Canon transferred

### Статус

```text
yes / active canon exists
```

### Файлы

- `CANON.md`
- `STATUS.md`
- `VERSIONS/v3.2.md`

### Текущий canon

```text
R Theory v3.2
```

Ключевое различение:

```text
символ фиксирует значимость
понятие фиксирует переносимое различение
понятие = сжатая инструкция различения
```

### Ограничение

`CANON.md` пока не расширялся после review.

Решение:

```text
CANON.md remains unchanged until source verification and canon compression decision
```

---

## 3. Versions transferred

### Статус

```text
yes / partial verification required
```

### Файлы

- `VERSIONS/v3.1_full.md`
- `VERSIONS/v3.2.md`
- `VERSIONS/VERSION_COMPARISON_v3.1_v3.2.md`

### Решение

```text
v3.2 = active canon snapshot
v3.1_full = migration draft / needs verification
```

---

## 4. Patches transferred

### Статус

```text
yes / indexed
```

### Файлы

- `PATCHES/2026-04-25_symbol_to_concept.md`
- `PATCHES/2026-04-25_shadows_of_R3.md`
- `PATCHES/q_r3_system.md`
- `PATCHES/recursive_choice_decoherence.md`
- `PATCHES/PATCH_INDEX.md`

### Решение

```text
symbol_to_concept -> accepted into v3.2
shadows_of_R3 -> candidate
q_r3_system -> migration draft / needs verification
recursive_choice_decoherence -> migration draft / needs verification
```

---

## 5. Cases transferred

### Статус

```text
yes / draft cases / indexed
```

### Файлы

- `CASES/ochre_symbol_to_concept.md`
- `CASES/fire_symbol_to_concept.md`
- `CASES/burial_symbol_to_concept.md`
- `CASES/shadows_of_R3_burial_case.md`
- `CASES/shadows_of_R3_taboo_luck_case.md`
- `CASES/ARCHAEOLOGY_MAP.md`
- `CASES/CASE_INDEX.md`

### Решение

Кейсы поддерживают:

- `symbol_to_concept`;
- `shadows_of_R3` candidate;
- осторожное археологическое чтение R-уровней.

Они не являются доказательством теории.

---

## 6. Archaeology transferred

### Статус

```text
broadly transferred / source verification required
```

### Файлы

- `ARCHAEOLOGY/README.md`
- `ARCHAEOLOGY/ARCHAEOLOGY_INDEX.md`
- `ARCHAEOLOGY/SOURCE_VERIFICATION_PLAN.md`
- `ARCHAEOLOGY/lomekwi.md`
- `ARCHAEOLOGY/oldowan.md`
- `ARCHAEOLOGY/acheulean.md`
- `ARCHAEOLOGY/late_acheulean_transfer.md`
- `ARCHAEOLOGY/cultural_pulsation.md`
- `ARCHAEOLOGY/brain_size_steps.md`
- `ARCHAEOLOGY/independent_inventions.md`
- `ARCHAEOLOGY/migration_cold_pressure.md`
- `ARCHAEOLOGY/death_symbolism.md`
- `ARCHAEOLOGY/demography_innovation_stabilization.md`
- `ARCHAEOLOGY/archaeology_falsification_map.md`
- `ARCHAEOLOGY/fire_camp_childhood.md`
- `ARCHAEOLOGY/sapiens_neanderthals_networks.md`

### Решение

Археологический блок можно считать миграционно перенесённым, но не источниково закрытым.

---

## 7. Evidence transferred

### Статус

```text
yes / indexed / source verification required
```

### Файлы

- `EVIDENCE/2026-04-23_empirical_verification.md`
- `EVIDENCE/brain_size_cultural_scaffolding.md`
- `EVIDENCE/stress_metabolic_mismatch.md`
- `EVIDENCE/scaffolding_causal_development.md`
- `EVIDENCE/network_stabilization_innovation.md`
- `EVIDENCE/EVIDENCE_INDEX.md`

### Решение

Evidence layer полезен, но не равен доказательству R-теории.

---

## 8. Source verification status

### Статус

```text
required / not completed
```

### Файлы

- `SOURCE_VERIFICATION_PLAN.md`
- `ARCHAEOLOGY/SOURCE_VERIFICATION_PLAN.md`

### Что ещё нужно

- собрать source cards;
- добавить реальные библиографические ссылки;
- проверить contested claims;
- снизить статус speculative claims, если источники не подтвердят их;
- сверить migration drafts с исходными чатами.

---

## 9. Cross-links transferred

### Статус

```text
yes / active cross-link map exists
```

### Файл

- `CROSS_LINKS.md`

### Основные связи

- R Theory ↔ Culture as Instructions;
- R Theory ↔ PNA;
- R Theory ↔ MEAT;
- R Theory ↔ SynTax;
- Boundary Saturation explicitly separated.

### Решение

Связи сохранены, но границы теорий разведены.

---

## 10. Coverage and gap tracking

### Файлы

- `COVERAGE.md`
- `OPEN_GAPS.md`
- `CANON_REVIEW.md`
- `MIGRATION_PLAN.md`

### Статус

```text
yes / active tracking exists
```

---

## 11. What remains open

Открыто:

1. Source verification.
2. Сверка migration drafts с исходными чатами.
3. Возможная canon compression после проверки.
4. Решение по `shadows_of_R3` candidate.
5. Сверка Q-R3.
6. Сверка recursive choice / decoherence.
7. Подбор источников по археологии.
8. Подбор источников по evidence claims.

---

## 12. What should not be done yet

Пока не делать:

- не расширять `CANON.md`;
- не принимать `shadows_of_R3` в канон;
- не превращать PNA в доказательство R Theory;
- не использовать archaeology drafts как доказанные claims;
- не смешивать Boundary Saturation с R Theory;
- не развивать новые R-гипотезы до source verification pass.

---

## 13. Ready to move to next theory?

### Migration perspective

```text
yes, R Theory is migrated enough to move to next module
```

### Verification perspective

```text
no, R Theory still requires source verification
```

Итоговое решение:

```text
R Theory migration can be paused as structurally closed.
Next module migration may begin.
Source verification remains a future pass.
```

---

## 14. Recommended next module

Следующий модуль для такой же процедуры:

```text
02_SYNTAX
```

Порядок для SynTax:

1. `02_SYNTAX/COVERAGE.md`
2. `02_SYNTAX/OPEN_GAPS.md`
3. `02_SYNTAX/CANON_REVIEW.md`
4. `02_SYNTAX/PATCHES/PATCH_INDEX.md`
5. `02_SYNTAX/MIGRATION_CLOSURE.md`

---

## Final status

```text
R Theory migration: structurally closed for now
Source verification: open
Development: paused
Next action: move to SynTax migration closure or run R source verification later
```
