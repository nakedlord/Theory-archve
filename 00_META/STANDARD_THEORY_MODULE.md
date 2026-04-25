# Standard Theory Module

Каждая теория в архиве ведётся как отдельный проект.

## Минимальный состав

```text
THEORY_NAME/
  CANON.md
  STATUS.md
  VERSIONS/
  PATCHES/
  HYPOTHESES/
  CASES/
  FALSIFICATION/
  SOURCES/
  SYNC_LOG.md
```

## Назначение файлов

- `CANON.md` — текущая признанная версия.
- `STATUS.md` — зрелость, роль, риски, следующий шаг.
- `VERSIONS/` — зафиксированные версии канона.
- `PATCHES/` — изменения канона.
- `HYPOTHESES/` — рабочие идеи до принятия.
- `CASES/` — проверки на материале.
- `FALSIFICATION/` — условия ослабления.
- `SOURCES/` — источники и данные.
- `SYNC_LOG.md` — история изменений.

## Правило

Если теория не имеет `FALSIFICATION/` и `CASES/`, она считается недостаточно проверенной, даже если её канон выглядит сильным.
