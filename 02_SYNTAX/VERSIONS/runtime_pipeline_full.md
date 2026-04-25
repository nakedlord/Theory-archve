# SynTax Runtime Pipeline — Full Migration Draft

Статус: migration draft / needs verification

## Назначение

Этот файл переносит общий runtime pipeline SynTax: как система проходит путь от входного запроса до ответа, патча, канона или следующего шага.

Файл не создаёт новую архитектуру, а фиксирует уже обсуждённую логику исполнения.

---

## 1. Общий принцип

SynTax должен работать не как набор красивых понятий, а как исполняемый маршрут мышления.

Минимальная логика:

```text
input -> interpretation -> goal -> routing -> context arbitration -> operators -> validation -> response -> sync
```

---

## 2. Input

Input — входной материал пользователя.

Это может быть:

- вопрос;
- идея;
- текст;
- задача;
- файл;
- критика;
- команда переноса;
- запрос на развитие;
- запрос на фиксацию.

---

## 3. Interpreted Input Packet

Вход нужно интерпретировать:

- что пользователь хочет;
- какой объект работы;
- какой уровень задачи;
- нужна ли разработка или миграция;
- есть ли уже активная цель;
- есть ли риск перепутать режимы.

Пример текущего режима:

```text
user asks to continue -> current mode = migration, not theory development
```

---

## 4. Goal Packet

Goal Packet фиксирует:

- Active Goal;
- Session Goal;
- Expected Output;
- Why this matters;
- Next Step.

Goal Packet связан с Goal Module.

---

## 5. Scheduler Routing

Scheduler выбирает режим работы:

- clarify;
- migrate;
- analyze;
- patch;
- verify;
- synthesize;
- archive;
- update canon;
- create case;
- create evidence;
- create cross-link.

В migration mode Scheduler должен выбирать перенос, а не развитие.

---

## 6. Context Arbitration

Перед подключением теоретической рамки нужно проверить, нужна ли она.

Возможные режимы:

- no-module path;
- single module;
- competitive read;
- deferred module.

Это защищает от Context Lock-In.

---

## 7. Operator Selection

Оператор выбирается по задаче.

Примеры операторов:

- distinction extraction;
- level separation;
- canon compression;
- patch formatting;
- case construction;
- evidence separation;
- cross-link creation;
- archive classification;
- migration classification.

---

## 8. Transformation

Transformation — собственно преобразование материала.

Пример:

```text
старое воспоминание -> migration draft -> статус -> файл GitHub
```

Или:

```text
идея -> candidate patch -> cases -> canon checklist
```

---

## 9. Validation

Validation проверяет:

- не смешаны ли уровни;
- есть ли источник;
- не перепутан ли статус;
- не попала ли гипотеза в канон;
- есть ли progress delta;
- не раздута ли архитектура;
- нужен ли sync log.

---

## 10. Response Realization

Ответ пользователю должен сообщить:

- что сделано;
- какие файлы созданы;
- какой статус поставлен;
- что остаётся открытым;
- следующий шаг.

Без лишнего метатекста.

---

## 11. Sync

Если была работа с GitHub, нужно обновить:

- соответствующий `SYNC_LOG.md`;
- `IMPORT_BACKLOG.md`, если это миграция;
- `COVERAGE_AUDIT`, если закрывается пробел;
- `STATUS.md`, если меняется зрелость модуля.

---

## 12. Runtime rule for migration mode

Пока активен Migration Mode:

```text
migrate first, develop later
```

Если материал восстановлен из памяти, ставить:

```text
migration draft / needs verification
```

Если материал неполон, ставить:

```text
recovery draft / needs source
```

---

## 13. Статус файла

```text
migration draft / needs verification
```

Нужно сверить с исходной SynTax runtime specification при возможности.
