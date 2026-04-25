# SynTax Validation Layer — Full Migration Draft

Статус: migration draft / needs verification

## Назначение

Validation Layer проверяет, можно ли доверять результату работы SynTax.

Он не создаёт идеи, а проверяет:

- уровень утверждения;
- статус материала;
- связность;
- grounding;
- риски натяжки;
- context lock-in;
- progress delta.

---

## 1. Главная функция

Validation Layer защищает систему от красивых, но ненадёжных выводов.

Формула:

```text
transformation -> validation -> accept / revise / defer / reject
```

---

## 2. Level Separation

Нужно различать:

- факт;
- интерпретацию;
- гипотезу;
- аналогию;
- каноническое утверждение;
- migration draft;
- evidence;
- speculative claim.

Смешение уровней — базовая ошибка.

---

## 3. Grounding Check

Grounding Check спрашивает:

- на чём основан вывод;
- есть ли источник;
- это память, документ, рассуждение или гипотеза;
- насколько сильна опора;
- можно ли проверить утверждение.

---

## 4. Status Check

Каждый файл или идея должен иметь статус.

Примеры статусов:

- active canon;
- candidate;
- migration draft;
- recovery draft;
- evidence layer;
- source-based bridge;
- speculative draft;
- archived;
- needs source.

Если статус неясен, ставить:

```text
migration draft / needs verification
```

---

## 5. Context Discipline Check

Проверяет, не захватила ли вывод одна рамка.

Связан с:

- Context Arbitration;
- E11 Context Lock-In;
- Module Independence.

Вопросы:

- есть ли конкурирующая рамка;
- не используется ли теория как универсальное объяснение;
- нужен ли no-module path;
- отделена ли теория от материала.

---

## 6. Progress Delta Check

Проверяет, дал ли результат новое различение.

Progress Delta есть, если появилось:

- уточнение;
- разделение уровней;
- новый критерий;
- новый статус;
- новая проверка;
- новая карта связей;
- исправление ошибки.

Нет Progress Delta, если есть только красивый пересказ.

---

## 7. Complexity Check

Проверяет, не добавляет ли система лишний слой.

Вопрос:

```text
можно ли получить тот же результат уточнением уже существующего элемента?
```

Если да, новый слой не нужен.

---

## 8. Migration Validation

Для режима миграции Validation Layer проверяет:

- не развиваем ли мы новую идею вместо переноса;
- правильно ли выбран статус;
- не попал ли migration draft в canon;
- внесён ли файл в IMPORT_BACKLOG;
- нужна ли пометка needs verification;
- не нужно ли обновить sync log.

---

## 9. Canon Update Validation

Перед обновлением канона нужна проверка:

- есть ли patch;
- есть ли case;
- есть ли limitation;
- есть ли risk;
- есть ли cross-link;
- не раздувается ли canon;
- можно ли обновить canon коротко.

Связанный файл:

- `00_META/CANDIDATE_TO_CANON_CHECKLIST.md`

---

## 10. Evidence Validation

Evidence не равен доказательству.

Evidence должен показывать:

- что поддерживает;
- что ослабляет;
- где спорно;
- где нужен источник;
- где есть альтернативное объяснение.

---

## 11. Speculative Model Validation

Для спекулятивных моделей нужно отделять:

- физическое утверждение;
- формальную аналогию;
- интуицию;
- candidate prediction;
- non-prediction.

Пример:

- Boundary Saturation.

---

## 12. Выходы Validation Layer

Возможные решения:

- accept;
- revise;
- keep as candidate;
- keep as migration draft;
- needs source;
- archive;
- reject;
- update canon;
- update backlog.

---

## 13. Статус файла

```text
migration draft / needs verification
```

Нужно сверить с исходной SynTax validation specification при возможности.
