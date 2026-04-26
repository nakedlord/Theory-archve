# SynTax Activation Prompt Archive

Статус: archived / sensitive prompt not reproduced

## Назначение

Этот файл фиксирует, что в старых обсуждениях существовала идея короткого activation prompt для SynTax.

Промпт должен был быть непонятен случайным людям, но распознаваем моделью как команда активации архитектуры.

---

## Почему prompt не воспроизводится здесь

Этот файл не хранит сам скрытый activation prompt.

Причины:

- активация не должна зависеть от магической фразы;
- архитектура должна быть понятна через portable specification;
- скрытые фразы хуже аудируются;
- переносимый SynTax должен работать через явные правила.

---

## Правильная замена

Вместо скрытого activation prompt использовать:

- `portable_syntax_md.md`;
- `GOAL_MODULE.md`;
- `runtime_pipeline_full.md`;
- `validation_layer_full.md`;
- `MIGRATION_MODE.md`.

---

## Статус

```text
archived / activation idea preserved / prompt not stored
```

Если нужно восстановить точный prompt, требуется исходный чат.
