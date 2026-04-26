# R Theory Migration Plan

Статус: active migration plan
Дата: 2026-04-25

## Главная цель

Максимально полно перенести текущие наработки по R-теории в GitHub, не развивая новые идеи до завершения миграции.

План строится по принципу:

```text
сначала закрыть один модуль -> потом переходить к следующему
```

Текущий фокус:

```text
01_R_THEORY
```

Пока R Theory не получит `COVERAGE.md`, `OPEN_GAPS.md` и `SOURCE_VERIFICATION_PLAN.md`, не переходить к глубокой миграции других теорий.

---

## 1. Что считается R-теорией

В R-блок входят все материалы, где центральным объектом являются:

- R0/R1/R2/R3;
- ΔT;
- рекурсивный выбор;
- символический разрыв;
- переход функция -> значимость -> символ -> понятие;
- обучение через вынесение ошибок из реальности;
- сон / воображение / рефлексия / осознанность как режимы обучения;
- R3 modes;
- Q-R3;
- decoherence choice;
- археологические маркеры R-уровней;
- антропогенез;
- история артефактов;
- огонь, лагерь, детство;
- охра, погребение, смерть;
- культурная пульсация;
- демография и стабилизация инноваций;
- sapiens / neanderthals;
- evidence по проверке предсказаний R-теории.

Материалы PNA, MEAT и Culture относятся к R-теории только как cross-links, если R-уровни являются центральным объектом анализа.

---

## 2. Текущая структура R Theory

Уже есть:

```text
01_R_THEORY/
  CANON.md
  STATUS.md
  SYNC_LOG.md
  MIGRATION_PLAN.md
  VERSIONS/
  PATCHES/
  CASES/
  EVIDENCE/
  SOURCES/
  ARCHAEOLOGY/
  FALSIFICATION/
```

Ключевые уже созданные файлы:

```text
VERSIONS/v3.1_full.md
VERSIONS/v3.2.md
PATCHES/2026-04-25_symbol_to_concept.md
PATCHES/2026-04-25_shadows_of_R3.md
PATCHES/q_r3_system.md
PATCHES/recursive_choice_decoherence.md
CASES/ARCHAEOLOGY_MAP.md
ARCHAEOLOGY/lomekwi.md
ARCHAEOLOGY/oldowan.md
ARCHAEOLOGY/acheulean.md
ARCHAEOLOGY/late_acheulean_transfer.md
ARCHAEOLOGY/cultural_pulsation.md
ARCHAEOLOGY/brain_size_steps.md
ARCHAEOLOGY/independent_inventions.md
ARCHAEOLOGY/migration_cold_pressure.md
ARCHAEOLOGY/death_symbolism.md
ARCHAEOLOGY/demography_innovation_stabilization.md
ARCHAEOLOGY/archaeology_falsification_map.md
ARCHAEOLOGY/fire_camp_childhood.md
ARCHAEOLOGY/sapiens_neanderthals_networks.md
EVIDENCE/2026-04-23_empirical_verification.md
```

---

## 3. Статусы внутри R Theory

### active canon

Только текущий `CANON.md` и актуальные принятые версии.

Сейчас:

```text
R Theory v3.2
```

### migration draft

Восстановлено из памяти или прошлых разговоров, требует сверки.

Примеры:

```text
VERSIONS/v3.1_full.md
ARCHAEOLOGY/*.md
PATCHES/q_r3_system.md
PATCHES/recursive_choice_decoherence.md
```

### candidate

Оформлено как кандидат на канон, но ещё не принято.

Пример:

```text
PATCHES/2026-04-25_shadows_of_R3.md
```

### evidence layer

Сопоставление с исследованиями, источниками или данными.

Пример:

```text
EVIDENCE/*.md
```

### needs source

Содержание перенесено, но требуется исходный чат, документ или внешние источники.

Большая часть археологической ветки пока имеет этот статус.

---

## 4. Этапы миграции R Theory

# Этап 1. Инвентаризация

## Цель

Создать карту того, что уже перенесено и чего не хватает.

## Файлы

```text
01_R_THEORY/COVERAGE.md
01_R_THEORY/OPEN_GAPS.md
```

## Что должно попасть в COVERAGE

- текущий canon;
- версии;
- патчи;
- кейсы;
- evidence;
- archaeology;
- cross-links;
- что перенесено полностью;
- что частично;
- что требует источника.

## Критерий завершения

Можно открыть один файл `COVERAGE.md` и понять состояние всей R-теории.

---

# Этап 2. Стабилизация канона

## Цель

Понять, что сейчас действительно является каноном R-теории, а что только migration draft.

## Файлы

```text
01_R_THEORY/CANON.md
01_R_THEORY/STATUS.md
01_R_THEORY/VERSIONS/v3.2.md
01_R_THEORY/VERSIONS/v3.1_full.md
```

## Проверить

- R0/R1/R2/R3;
- ΔT;
- R как уровни вынесенного обучения;
- символический разрыв;
- символ vs понятие;
- понятие как сжатая инструкция различения;
- связь с культурой как инструкциями.

## Выход

Не обязательно обновлять canon сразу.

Сначала создать файл:

```text
01_R_THEORY/CANON_REVIEW.md
```

## Критерий завершения

Понятно, какие формулировки оставить в `CANON.md`, а какие держать в версиях и патчах.

---

# Этап 3. Полная версия R v3.1 / v3.2

## Цель

Сравнить `v3.1_full.md` и текущий `v3.2.md`.

## Файл

```text
01_R_THEORY/VERSIONS/VERSION_COMPARISON_v3.1_v3.2.md
```

## Проверить

- что добавило v3.2;
- не потерялось ли что-то из v3.1;
- какие части v3.1 являются активными;
- какие части v3.1 являются историческими;
- какие части требуют источника.

## Критерий завершения

Понятно, что именно означает R Theory v3.2 относительно v3.1.

---

# Этап 4. Патчи R-теории

## Цель

Разобрать все R-патчи и поставить им статусы.

## Уже есть

```text
PATCHES/2026-04-25_symbol_to_concept.md
PATCHES/2026-04-25_shadows_of_R3.md
PATCHES/q_r3_system.md
PATCHES/recursive_choice_decoherence.md
```

## Нужно создать

```text
01_R_THEORY/PATCHES/PATCH_INDEX.md
```

## Для каждого патча указать

- статус;
- source;
- связанную версию;
- связанные cases;
- принят ли в canon;
- что ещё нужно проверить.

## Предварительные статусы

```text
symbol_to_concept -> accepted into v3.2
shadows_of_R3 -> candidate
q_r3_system -> migration draft / needs verification
recursive_choice_decoherence -> migration draft / needs verification
```

---

# Этап 5. Археологический блок

## Цель

Закрыть подробную карту археологических маркеров.

## Уже есть

```text
ARCHAEOLOGY/lomekwi.md
ARCHAEOLOGY/oldowan.md
ARCHAEOLOGY/acheulean.md
ARCHAEOLOGY/late_acheulean_transfer.md
ARCHAEOLOGY/cultural_pulsation.md
ARCHAEOLOGY/brain_size_steps.md
ARCHAEOLOGY/independent_inventions.md
ARCHAEOLOGY/migration_cold_pressure.md
ARCHAEOLOGY/death_symbolism.md
ARCHAEOLOGY/demography_innovation_stabilization.md
ARCHAEOLOGY/archaeology_falsification_map.md
ARCHAEOLOGY/fire_camp_childhood.md
ARCHAEOLOGY/sapiens_neanderthals_networks.md
```

## Нужно создать

```text
ARCHAEOLOGY/SOURCE_VERIFICATION_PLAN.md
ARCHAEOLOGY/ARCHAEOLOGY_INDEX.md
```

## Проверить по каждому файлу

- это факт, интерпретация или гипотеза;
- какие источники нужны;
- какой R-уровень предполагается;
- что ослабляет интерпретацию;
- какие cross-links есть.

## Критерий завершения

Археологический блок можно читать как карту гипотез и проверок, а не как набор свободных рассуждений.

---

# Этап 6. Evidence block

## Цель

Разложить и проверить evidence по предсказаниям R-теории.

## Уже есть

```text
EVIDENCE/2026-04-23_empirical_verification.md
EVIDENCE/brain_size_cultural_scaffolding.md
EVIDENCE/stress_metabolic_mismatch.md
EVIDENCE/scaffolding_causal_development.md
EVIDENCE/network_stabilization_innovation.md
```

## Нужно создать

```text
EVIDENCE/EVIDENCE_INDEX.md
EVIDENCE/SOURCE_STATUS.md
```

## Проверить

- какие claims поддержаны источниками;
- какие contested;
- какие только plausible;
- какие требуют web/source verification;
- какие claims нельзя использовать как доказанные.

---

# Этап 7. Cases block

## Цель

Собрать все кейсы R-теории и проверить их статус.

## Уже есть

```text
CASES/ochre_symbol_to_concept.md
CASES/fire_symbol_to_concept.md
CASES/burial_symbol_to_concept.md
CASES/shadows_of_R3_burial_case.md
CASES/shadows_of_R3_taboo_luck_case.md
CASES/ARCHAEOLOGY_MAP.md
```

## Нужно создать

```text
CASES/CASE_INDEX.md
```

## Проверить

- какой патч проверяет кейс;
- какой статус кейса;
- что он усиливает;
- что он не доказывает;
- нужен ли источник.

---

# Этап 8. Cross-links

## Цель

Отделить R-теорию от соседних теорий, но сохранить связи.

## Проверить связи

```text
R Theory ↔ Culture as Instructions
R Theory ↔ PNA
R Theory ↔ MEAT
R Theory ↔ SynTax
R Theory ↔ Boundary Saturation only if analogy is explicit
```

## Нужно создать

```text
01_R_THEORY/CROSS_LINKS.md
```

или обновить `90_CROSS_LINKS/`.

## Критерий завершения

Понятно, где R-теория заканчивается и где начинается соседний модуль.

---

# Этап 9. Source verification

## Цель

Создать список того, что нужно проверить по источникам.

## Файл

```text
01_R_THEORY/SOURCE_VERIFICATION_PLAN.md
```

## Группы источников

- archaeology;
- cognitive development;
- working memory and attention;
- stress and metabolism;
- cultural transmission;
- demography and innovation;
- sapiens/neanderthals;
- brain size evolution;
- burial and ochre;
- fire and camp.

## Критерий завершения

Есть список источников и проверяемых claims.

---

# Этап 10. Final R Theory migration closure

## Цель

Зафиксировать, что R-теория перенесена достаточно полно для текущего этапа.

## Файлы

```text
01_R_THEORY/COVERAGE.md
01_R_THEORY/OPEN_GAPS.md
01_R_THEORY/SOURCE_VERIFICATION_PLAN.md
01_R_THEORY/MIGRATION_CLOSURE.md
```

## Статусы на выходе

В `MIGRATION_CLOSURE.md` указать:

```text
canon transferred: yes/no
versions transferred: yes/no
patches transferred: yes/no
archaeology transferred: partial/full
cases transferred: partial/full
evidence transferred: partial/full
source verification required: yes
ready to move to next theory: yes/no
```

---

## 5. Приоритет выполнения

Выполнять строго по порядку:

1. `COVERAGE.md`
2. `OPEN_GAPS.md`
3. `CANON_REVIEW.md`
4. `PATCHES/PATCH_INDEX.md`
5. `ARCHAEOLOGY/ARCHAEOLOGY_INDEX.md`
6. `ARCHAEOLOGY/SOURCE_VERIFICATION_PLAN.md`
7. `EVIDENCE/EVIDENCE_INDEX.md`
8. `CASES/CASE_INDEX.md`
9. `SOURCE_VERIFICATION_PLAN.md`
10. `MIGRATION_CLOSURE.md`

---

## 6. Что нельзя делать до закрытия R Theory

Не переходить глубоко к другим теориям, кроме технических cross-links.

Не развивать новые R-гипотезы.

Не принимать candidate-патчи в canon без checklist.

Не искать новые источники бессистемно до создания `SOURCE_VERIFICATION_PLAN.md`.

Не смешивать migration drafts и canon.

---

## 7. Definition of done

R Theory migration можно считать закрытой на текущем этапе, если:

- есть `COVERAGE.md`;
- есть `OPEN_GAPS.md`;
- есть `SOURCE_VERIFICATION_PLAN.md`;
- все существующие файлы имеют статус;
- ясно, что canon, что migration draft, что candidate;
- археологический блок имеет индекс;
- evidence block имеет индекс;
- cases block имеет индекс;
- создан `MIGRATION_CLOSURE.md`.
