# SynTax Error Architecture — Full Migration Draft

Статус: migration draft / needs verification

## Назначение

Error Architecture фиксирует классы ошибок SynTax и правила их обработки.

Ошибка в SynTax — не просто сбой ответа.

Ошибка может быть источником эволюции архитектуры, если она повторяется и указывает на системный дефект.

---

## 1. Главная логика

```text
ошибка -> классификация -> коррекция -> recurrence tracking -> patch candidate
```

Не каждая ошибка требует патча.

Повторяющаяся ошибка требует системной реакции.

---

## 2. Типовые классы ошибок

Полный список ранних error classes требует сверки с исходным чатом.

В текущей миграции точно перенесены:

- E11 Context Lock-In;
- Error Recurrence Counter;
- Drift Detection.

Также из канона SynTax видны связанные failure modes:

- level mixing;
- false depth;
- premature synthesis;
- abstraction inflation;
- context overreach;
- canon pollution;
- weak grounding;
- no progress delta.

---

## 3. E11 Context Lock-In

Context Lock-In — ошибка, при которой одна рамка начинает доминировать и подавлять альтернативные чтения.

Симптомы:

- один module включается по привычке;
- no-module path исчезает;
- словарь теории выглядит как нейтральная реальность;
- альтернативы не рассматриваются.

Коррекция:

- forced competitive read;
- module deactivation;
- explicit separation;
- return to Context Arbitration.

---

## 4. False Depth

False Depth — ответ выглядит глубоким, но не меняет карту различений.

Связано с Progress Delta Check.

Коррекция:

- спросить, какое новое различение появилось;
- убрать стилистическую сложность;
- вернуться к объекту и цели.

---

## 5. Premature Synthesis

Premature Synthesis — слишком ранняя сборка вывода до проверки напряжений.

Симптомы:

- ответ слишком гладкий;
- конфликт сглажен;
- альтернативы не рассмотрены;
- неопределённость преждевременно закрыта.

Коррекция:

- вернуть tension;
- открыть competing frame;
- задержать финальный вывод.

---

## 6. Abstraction Inflation

Abstraction Inflation — рост абстракции без роста различающей силы.

Симптом:

```text
понятий больше, понимания не больше
```

Коррекция:

- grounded example;
- lower-level check;
- progress delta check;
- complexity governance.

---

## 7. Canon Pollution

Canon Pollution — попадание рабочей гипотезы в Memory Infrastructure как будто она уже признана.

Коррекция:

- перевести в hypothesis / migration draft / candidate;
- обновить status;
- проверить patch route.

Связано с Infrastructure Split.

---

## 8. Weak Grounding

Weak Grounding — сильное утверждение без достаточной опоры.

Коррекция:

- указать уровень уверенности;
- вынести в hypothesis;
- запросить источник;
- создать evidence file.

---

## 9. Error Recurrence Counter

ERC отслеживает повторение ошибок.

Поля:

- Error ID;
- recurrence window;
- recurrence count;
- severity drift;
- last seen;
- trigger threshold;
- escalation status.

Пороги:

- pattern noticed;
- correction required;
- patch candidate required;
- audit review required.

---

## 10. Drift Detection

Drift Detection отслеживает медленное смещение поведения системы относительно канона.

Типы drift:

- Trace Drift;
- Metric Drift;
- Error Drift;
- Validation Drift;
- User Isolation Drift;
- Context Discipline Drift.

Drift нельзя фиксировать по одному случаю.

Нужно observation window.

---

## 11. Ошибка как источник патча

Если ошибка повторяется, она становится не локальным провалом, а источником архитектурного развития.

Формула:

```text
recurring error -> audit -> patch candidate -> validation -> architecture update
```

---

## 12. Migration mode errors

В режиме миграции типовые ошибки:

- развивать вместо переносить;
- ставить canon вместо migration draft;
- забыть needs verification;
- не обновить IMPORT_BACKLOG;
- смешать старую мысль и новую интерпретацию;
- потерять source requirement.

---

## 13. Статус файла

```text
migration draft / needs verification
```

Нужно сверить с полной Error Architecture из исходного SynTax-чата.
