# Redshift-like Boundary Degradation — Boundary Saturation Migration Draft

Статус: speculative analogy / needs formalization

## Назначение

Этот файл переносит старую идею о деградации пропускной способности границы при росте compactness / density / correlation load.

Важно: это пока аналогия, а не доказанный физический механизм.

---

## 1. Исходная идея

В ранней формулировке Boundary Saturation была запись:

```text
c_e = c0 * g(rho_Z)
```

где:

```text
g'(rho_Z) < 0
```

Смысл: при росте плотности внутренних корреляций пропускная способность граничного канала снижается.

---

## 2. Связь с redshift-like behavior

Эта деградация может напоминать redshift-like эффект:

```text
рост compactness -> снижение внешней доступности внутренних процессов
```

Но корректный статус:

```text
redshift-like analogy
```

а не:

```text
derived gravitational redshift
```

---

## 3. Что нужно различать

### Physical redshift

Физический эффект в общей теории относительности.

### Boundary degradation

Спекулятивная запись снижения доступности выхода через границу.

### Analogy layer

Попытка описать похожий мотив языком насыщения границы.

Эти три слоя нельзя смешивать.

---

## 4. Возможная рабочая формула

```text
C_b = sum(c_e)
```

```text
c_e = c0 * g(lambda)
```

где `lambda` — пока неопределённая boundary load / compactness-related variable.

Условие:

```text
g'(lambda) < 0
```

---

## 5. Что нужно формализовать

1. Что такое `lambda`?
2. Связана ли она с compactness `chi`?
3. Что именно измеряет `c_e`?
4. В каких единицах задана `C_b`?
5. Можно ли связать `g(lambda)` с известным redshift factor?
6. Не дублирует ли модель уже известное описание ОТО без нового содержания?

---

## 6. Что модель пока не утверждает

Модель пока не утверждает:

- что redshift выведен из Boundary Saturation;
- что `g(lambda)` физически известна;
- что внутренняя корреляционная плотность является стандартной физической величиной;
- что эта модель заменяет метрику Шварцшильда.

---

## 7. Безопасная формулировка

```text
Boundary Saturation may use a redshift-like degradation analogy to describe decreasing external accessibility near the compactness threshold.
```

---

## 8. Статус

```text
speculative analogy / needs dimension and GR compatibility check
```

Связанные файлы:

- `threshold_E_over_R.md`
- `compatibility_with_GR.md`
- `predictions_and_non_predictions.md`
