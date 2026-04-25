# Complexity Passport / Complexity Governance — Full Migration Draft

Статус: migration draft / needs verification

## Назначение

Complexity Governance защищает SynTax от архитектурного раздувания.

Новый слой, оператор, метрика или протокол должен давать прирост различающей силы, а не просто увеличивать сложность.

---

## 1. Главная проблема

Архитектура может расти слишком быстро.

Каждый новый элемент может казаться полезным локально, но вместе они создают:

- bloat;
- дублирование;
- трудность исполнения;
- слабую воспроизводимость;
- перегрузку validation;
- путаницу статусов.

---

## 2. Главное правило

```text
new complexity must justify itself by distinguishing gain
```

Если тот же результат можно получить уточнением старого элемента, новый элемент не нужен.

---

## 3. Complexity Passport

Для каждого complexity-increasing patch нужен паспорт.

Поля:

- Complexity ID;
- Added Construct;
- Complexity Cost;
- Claimed Distinguishing Gain;
- Runtime Overhead;
- Audit Overhead;
- Simplification Alternatives Considered;
- Acceptance Threshold.

---

## 4. Complexity Cost

Стоимость сложности может включать:

- новый обязательный слой;
- новую runtime-stage;
- новую метрику;
- новый error class;
- новый audit-файл;
- новый статус;
- новый оператор;
- рост нагрузки на пользователя или систему.

---

## 5. Distinguishing Gain

Прирост различающей силы может быть:

- новое различение;
- устранение recurring error;
- снижение ambiguity;
- повышение auditability;
- улучшение routing;
- защита от canon pollution;
- улучшение migration discipline;
- предотвращение theory overreach.

---

## 6. Simplification Alternatives

Перед добавлением нового элемента нужно спросить:

```text
можно ли решить это уточнением существующего слоя?
```

Примеры:

- не нужен новый оператор, если можно расширить старый;
- не нужен новый статус, если хватает migration draft / candidate / archive;
- не нужен новый модуль, если это case внутри существующего модуля.

---

## 7. Acceptance Threshold

Новый construct можно принять, если:

```text
distinguishing gain > complexity cost
```

И если нет более простого решения.

---

## 8. Rejection is valid

Mutation candidate можно отклонить не потому, что он ложный, а потому что он слишком дорогой.

Формула:

```text
good idea ≠ good architecture patch
```

---

## 9. Связь с Operator Registry

Operator Registry требует overlap check.

Complexity Governance требует cost/gain check.

Вместе они предотвращают operator explosion.

---

## 10. Связь с Migration Mode

В Migration Mode нельзя создавать новый слой для каждого старого фрагмента.

Сначала нужно классифицировать материал в существующих категориях:

- canon;
- version;
- patch;
- case;
- evidence;
- source bridge;
- migration draft;
- recovery draft;
- archive.

---

## 11. Статус файла

```text
migration draft / needs verification
```

Нужно сверить с исходным Complexity Governance Rule v4.6 при возможности.
