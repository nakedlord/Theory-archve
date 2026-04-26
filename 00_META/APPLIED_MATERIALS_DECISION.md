# Applied Materials Decision

Статус: active repository decision
Дата: 2026-04-25

## Решение

Рабочие и бизнес-материалы не переносить в `Theory-archive` по умолчанию.

Для рабочих материалов создан отдельный репозиторий:

```text
nakedlord/GYMKIDS-
```

## Почему отдельно

`Theory-archive` хранит теории, каноны, патчи, кейсы, evidence и source verification.

Рабочие материалы имеют другую природу: регламенты, методологии, инструкции, скрипты, маркетинг, аналитика, таблицы, ТЗ, чек-листы и операционные процессы.

Если хранить всё вместе, возникнет смешение:

```text
theory canon != business knowledge base
```

## Что относится к рабочему репозиторию

- FLY ZONE methodology;
- GYMKiDs marketing and audience research;
- trainer scripts;
- trial lesson OS;
- injury regulations;
- UTM and Yandex cards;
- subscription analytics;
- retention / family day analysis;
- RSYa quiz;
- creative tasks;
- operational checklists.

## Что может попадать в Theory-archive

Рабочий материал можно переносить в `Theory-archive` только если он используется как явный кейс для теории: R Theory learning/scaffolding, Culture as Instructions, SynTax as work architecture, pedagogy as instruction transfer.

## Следующий шаг

Инициализировать `nakedlord/GYMKIDS-` как рабочую базу знаний.
