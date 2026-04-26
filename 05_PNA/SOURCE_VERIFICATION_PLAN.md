# PNA Source Verification Plan

Статус: active source verification plan
Дата: 2026-04-25

## Назначение

Этот файл задаёт план источниковой проверки PNA.

Цель — отделить:

- исследовательские факты;
- интерпретацию через PNA;
- связь с ΔT;
- связь с R1/R2/R3;
- speculative extensions.

Главное правило:

```text
source can support a bridge, but not prove PNA as a full model
```

---

## 1. Verification structure

Для каждого claim нужно фиксировать:

```text
claim -> source -> what source says -> PNA interpretation -> confidence status
```

Нельзя использовать источник по working memory или predictive processing как прямое доказательство PNA.

---

## 2. Confidence statuses

### supported bridge

Источник хорошо поддерживает отдельный мост.

### plausible bridge

Источник совместим с PNA-интерпретацией, но не доказывает её.

### contested bridge

В литературе есть спор или несколько конкурирующих трактовок.

### speculative

Идея пока является внутренней гипотезой.

### needs source

Нужен источник до использования в сильном выводе.

---

## 3. Working memory and attention

### Related files

- `EMPIRICAL_LINKS/working_memory_attention.md`
- `VERSIONS/working_memory_child_development.md`

### Claims to verify

- рабочая память временно удерживает информацию для текущей задачи;
- внимание выбирает и ограничивает доступные элементы;
- working memory + attention могут поддерживать temporary cognitive availability;
- развитие рабочей памяти связано с детским переходом к более сложным цепочкам действия и объяснения.

### Needed sources

- working memory reviews;
- attention and working memory relation;
- executive function;
- developmental working memory;
- attention control in children.

### Current status

```text
supported bridge / developmental extension needs source verification
```

---

## 4. Temporal integration / subjective present

### Related files

- `EMPIRICAL_LINKS/temporal_integration_window.md`
- `VERSIONS/consciousness_flicker.md`

### Claims to verify

- сознательный опыт может иметь temporal integration windows;
- есть исследования субъективного настоящего порядка нескольких секунд;
- окно 2–5 секунд является рабочей гипотезой, а не универсальным законом;
- PNA flicker can be interpreted as temporary situation window only cautiously.

### Needed sources

- temporal integration;
- subjective present;
- perception windows;
- attention sampling;
- conscious access cycles.

### Current status

```text
source-supported but contested bridge / 2-5 sec range speculative
```

---

## 5. Predictive processing

### Related files

- `EMPIRICAL_LINKS/predictive_processing.md`
- `VERSIONS/attention_switching_error_monitoring.md`

### Claims to verify

- мозг можно описывать через предсказание, ошибку и коррекцию;
- mismatch / prediction error может быть мостом к R3.1/R3.2;
- error monitoring и attention switching могут поддерживать переход от действия к анализу ошибки.

### Needed sources

- predictive processing;
- prediction error;
- error monitoring;
- conflict monitoring;
- cognitive control;
- attention switching.

### Current status

```text
conceptual bridge with strong literature base / R3 mapping remains interpretive
```

---

## 6. Mental simulation

### Related file

- `VERSIONS/mental_simulation.md`

### Claims to verify

- mental simulation allows internal rehearsal of possible actions;
- episodic future thinking supports planning;
- counterfactual thinking supports learning without direct action;
- mental simulation may extend ΔT by allowing comparison of trajectories.

### Needed sources

- mental simulation;
- episodic future thinking;
- counterfactual reasoning;
- model-based decision making;
- planning and working memory.

### Current status

```text
plausible bridge / needs sources
```

---

## 7. Speech, narrative and R3

### Related file

- `VERSIONS/speech_narrative_r3.md`

### Claims to verify

- speech supports self-regulation;
- narrative helps structure sequences and causal relations;
- language can scaffold working memory and rule maintenance;
- stories can transmit causal and moral instructions.

### Needed sources

- private speech;
- narrative cognition;
- language and executive function;
- causal explanation development;
- cultural transmission through stories.

### Current status

```text
plausible bridge / needs developmental and cognitive sources
```

---

## 8. Sleep / imagination / reflection

### Related file

- `VERSIONS/sleep_imagination_reflection.md`

### Claims to verify

- sleep supports memory consolidation and offline processing;
- imagination supports possible future trajectories;
- reflection supports second-order learning and rule revision;
- these can be read as ways to reduce the cost of real-world error.

### Needed sources

- sleep and memory consolidation;
- imagination and simulation;
- metacognition;
- reflective reasoning;
- learning and error correction.

### Current status

```text
important R-theory bridge / source verification needed
```

---

## 9. R3 modes

### Related file

- `VERSIONS/r3_modes_pna.md`

### Claims to verify

- online predictive control;
- local error explanation;
- offline retrospective rewrite;
- relation to error monitoring, metacognition and retrospective reasoning.

### Needed sources

- cognitive control;
- error monitoring;
- performance monitoring;
- metacognition;
- retrospective reasoning;
- rumination vs constructive reflection.

### Current status

```text
interpretive hypothesis / needs verification
```

---

## 10. Heart-like regulation

### Related file

- `VERSIONS/heart_like_regulation_archive.md`

### Claims to verify

- possible rhythmic structure of activation windows;
- possible relation to neural oscillations or attention sampling;
- possible relation to arousal/autonomic regulation.

### Needed sources

- neural oscillations;
- attention sampling;
- conscious access rhythms;
- arousal regulation;
- autonomic-cognitive coupling.

### Current status

```text
archived speculative note / do not reactivate without sources
```

---

## 11. PNA and R Theory boundary

### Rule

PNA can support R Theory only as a possible cognitive bridge.

It cannot be used as proof of:

- R0/R1/R2/R3;
- ΔT;
- symbolic rupture;
- R3 modes.

### Correct formulation

```text
PNA may provide a cognitive interpretation of how ΔT could be supported.
```

### Incorrect formulation

```text
PNA proves ΔT.
```

---

## 12. Future source cards

Potential source files:

```text
SOURCES/working_memory_attention_sources.md
SOURCES/temporal_integration_sources.md
SOURCES/predictive_processing_sources.md
SOURCES/mental_simulation_sources.md
SOURCES/speech_narrative_sources.md
SOURCES/sleep_reflection_sources.md
SOURCES/error_monitoring_sources.md
SOURCES/neural_oscillation_attention_sampling_sources.md
```

---

## 13. Current status

```text
source verification plan created / sources partially listed / source cards not created
```

## Next step

Create `MIGRATION_CLOSURE.md`.
