# Dimension Check: Cb and Idot — Boundary Saturation

Статус: migration draft / model hygiene / needs formal work

## Назначение

Этот файл переносит и дисциплинирует проблему размерностей в Boundary Saturation.

В ранних записях использовалось условие:

```text
I_dot >= C_b
```

Но это условие осмысленно только если `I_dot` и `C_b` имеют одинаковую размерность.

---

## 1. Переменные

```text
C_b   boundary capacity / пропускная способность границы
I_dot internal production or actualization rate / внутренняя скорость актуализации
```

Проблема:

пока не ясно, что именно течёт через границу.

Варианты:

- энергия;
- информация;
- корреляции;
- entropy rate;
- causal influence;
- другая величина.

---

## 2. Нельзя сравнивать разные величины

Если `C_b` — поток энергии, то `I_dot` тоже должен быть потоком энергии.

Если `C_b` — информационная пропускная способность, то `I_dot` должен быть скоростью производства или актуализации информации.

Если `C_b` — поток корреляций, нужно определить единицу корреляции.

---

## 3. Минимальное требование

Перед любым выводом нужно задать:

```text
[C_b] = ?
[I_dot] = ?
```

И проверить:

```text
[C_b] == [I_dot]
```

Если размерности не совпадают, условие насыщения некорректно.

---

## 4. Возможные варианты нормировки

### Energy-flow reading

```text
C_b = maximum energy flux across boundary
I_dot = internal energy processing rate
```

Риск: это может просто дублировать известную физику без нового содержания.

### Information-flow reading

```text
C_b = information capacity of boundary
I_dot = internal information generation / scrambling rate
```

Риск: нужно определить информацию и связь с физическими величинами.

### Correlation-flow reading

```text
C_b = accessible correlation flux
I_dot = internal correlation actualization rate
```

Риск: корреляция пока не имеет строгой единицы.

---

## 5. Связь с compactness

Текущий безопасный параметр:

```text
chi = 2GE / (c^4 R)
```

Boundary Saturation может пытаться связать `C_b` и `I_dot` с `chi`, но не должна заменять compactness criterion без вывода.

---

## 6. Redshift-like degradation

Если вводится функция деградации:

```text
c_e = c0 * g(lambda)
```

нужно определить:

- что такое `lambda`;
- безразмерна ли она;
- связана ли она с `chi`;
- как проверять `g(lambda)`.

---

## 7. Что нельзя делать

Нельзя писать:

```text
I_dot >= C_b
```

как физический критерий, пока не определены размерности.

Нельзя использовать `correlation` как свободную метафору, если из неё выводится физический порог.

---

## 8. Минимальный следующий шаг

Выбрать одну интерпретацию для первого formal pass:

1. information-flow;
2. energy-flow;
3. correlation-flow.

Затем явно задать единицы и проверить совместимость с compactness threshold.

---

## 9. Статус

```text
migration draft / dimension hygiene / not a physical derivation
```

Связанные файлы:

- `threshold_E_over_R.md`
- `compatibility_with_GR.md`
- `redshift_like_boundary_degradation.md`
- `predictions_and_non_predictions.md`
