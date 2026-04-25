# Operator Registry Protocol — Full Migration Draft

Статус: migration draft / needs verification

## Назначение

Этот файл переносит полный смысл Operator Registry Protocol.

Operator Registry нужен, чтобы операторы SynTax не существовали как неявные привычки, не дублировались и не раздували архитектуру.

---

## 1. Главная проблема

Без реестра операторов система может использовать разные названия для одного и того же действия или, наоборот, одним словом называть разные операции.

Это создаёт:

- operator duplication;
- hidden overlap;
- weak auditability;
- architecture bloat;
- неясные preconditions;
- слабую validation.

---

## 2. Что такое оператор

Оператор — это повторяемое преобразование мышления или материала.

Примеры:

- разделить уровни;
- выделить скрытую предпосылку;
- создать patch;
- свернуть формулу в canon;
- построить case;
- вынести cross-link;
- определить статус материала;
- провести migration classification.

---

## 3. Registry Passport

Каждый стабильный оператор должен иметь паспорт.

Поля:

- Operator ID;
- Operator Name;
- Function;
- Target Object;
- Preconditions;
- Transformation Rule;
- Expected Output;
- Compatible Navigation Commands;
- Preferred Context Couplings;
- Validation Hooks;
- Failure Modes;
- Overlap Risks;
- Status.

---

## 4. Статусы операторов

### Core Operator

Базовый оператор, без которого SynTax не работает.

### Auxiliary Operator

Вспомогательный оператор, усиливающий конкретные режимы.

### Experimental Operator

Рабочая проба, ещё не принятая в стабильный слой.

### Deprecated Operator

Оператор, заменённый более точной конструкцией.

### Archived Operator

Исторически важный, но неактивный оператор.

---

## 5. Правило добавления оператора

Новый оператор можно добавить только если его distinguishing gain превышает overlap с существующими операторами.

Вопрос:

```text
что этот оператор различает такого, чего раньше нельзя было различить?
```

Если ответ слабый, оператор не нужен.

---

## 6. Overlap Check

Перед добавлением оператора нужно проверить:

- не делает ли это уже существующий оператор;
- можно ли уточнить старый оператор вместо нового;
- не создаёт ли новый оператор путаницу;
- есть ли validation hook;
- понятно ли, когда оператор применять.

---

## 7. Validation Hooks

У каждого оператора должен быть способ проверки результата.

Примеры:

- Level Separation проверяется отсутствием смешения факт/гипотеза/интерпретация.
- Canon Compression проверяется краткостью и стабильностью формулировки.
- Migration Classification проверяется статусом файла.
- Cross-link Creation проверяется наличием двух связанных модулей и явной причины связи.

---

## 8. Failure Modes

Типовые сбои операторов:

- применён не к тому объекту;
- применён слишком рано;
- создаёт ложную глубину;
- дублирует другой оператор;
- скрыто включает любимую теорию;
- не имеет output criterion;
- не проходит validation.

---

## 9. Связь с Complexity Governance

Operator Registry защищает от operator explosion.

Complexity Governance задаёт вопрос:

```text
стоимость нового оператора меньше, чем его различающая сила?
```

Если нет, оператор не добавляется.

---

## 10. Связь с текущей миграцией

В Migration Mode особенно важны операторы:

- Migration Classification;
- Status Assignment;
- Canon vs Draft Separation;
- Source Requirement Detection;
- Backlog Update;
- Coverage Audit Update.

---

## 11. Статус файла

```text
migration draft / needs verification
```

Нужно сверить с исходным Operator Registry Protocol v4.9 при возможности.
