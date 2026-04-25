# Drift Detection Protocol — Full Migration Draft

Статус: migration draft / needs verification

## Назначение

Drift Detection Protocol нужен для выявления медленного отклонения SynTax от активного канона.

Drift — это не разовая ошибка, а устойчивое смещение поведения системы.

---

## 1. Главная проблема

Система может формально продолжать работать, но постепенно менять:

- reasoning path;
- validation discipline;
- response behavior;
- context usage;
- error pattern;
- user isolation;
- canon discipline.

Без drift detection это изменение можно заметить слишком поздно.

---

## 2. Определение drift

Drift — устойчивое статистическое или структурное смещение поведения относительно baseline.

Формула:

```text
baseline behavior -> observation window -> repeated deviation -> drift candidate
```

---

## 3. Почему нельзя фиксировать drift по одному случаю

Один случай может быть шумом, адаптацией или особенностью задачи.

Drift требует:

- observation window;
- baseline comparison;
- repeated indicators;
- severity estimate.

---

## 4. Типы drift

### Trace Drift

Меняется типичный runtime path.

Например, система начинает пропускать validation или sync.

### Metric Drift

Меняются runtime metrics: падает grounding, progress delta или validation reliability.

### Error Drift

Увеличивается частота или тяжесть конкретных error classes.

### Validation Drift

Validation Layer начинает слабеть: пропускает level mixing, weak grounding или premature synthesis.

### User Isolation Drift

User preferences начинают влиять на truth-sensitive reasoning сильнее, чем должны.

### Context Discipline Drift

Растёт Context Lock-In, theory overreach или исчезает no-module path.

---

## 5. Drift Passport

Для каждого drift candidate нужен паспорт:

- Drift ID;
- Drift Type;
- Observation Window;
- Baseline Version;
- Current Pattern;
- Indicators;
- Severity Level;
- Correction Recommendation;
- Patch Review Trigger.

---

## 6. Severity levels

### D1 Weak Drift

Слабое отклонение, нужен мониторинг.

### D2 Functional Drift

Отклонение влияет на качество работы, нужен targeted audit.

### D3 Canon Threat

Отклонение угрожает активному канону или архитектурной дисциплине, нужен patch review или rollback review.

---

## 7. Источники сигналов

- Execution Trace;
- Runtime Metrics;
- Error Recurrence Counter;
- Audit Protocol;
- Version Comparison;
- Coverage Audit;
- User correction patterns.

---

## 8. Связь с Error Recurrence Counter

ERC считает повторяющиеся ошибки.

Drift Detection смотрит шире: не только повтор ошибки, но и смещение поведения всей системы.

Формула:

```text
recurrent errors may indicate drift
```

---

## 9. Связь с Migration Mode

В Migration Mode возможен drift:

- система начинает развивать идеи вместо переноса;
- migration drafts начинают выглядеть как canon;
- backlog не обновляется;
- статус материала теряется;
- source requirement игнорируется.

---

## 10. Коррекция drift

Возможные меры:

- targeted audit;
- return to runtime protocol;
- status correction;
- patch review;
- context module deactivation;
- complexity reduction;
- rollback to previous version;
- update checklist.

---

## 11. Статус файла

```text
migration draft / needs verification
```

Нужно сверить с исходным Drift Detection Protocol v4.3 при возможности.
