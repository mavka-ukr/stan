# Стан

Модуль стану для Мавки.

## Використання

```мавка
взяти "хмарний.пак.укр/стан/0.0.3"

стан = Стан((рахунок=1))

стан.слухати((): друк("стан змінено"))

дія збільшити()
  стан["рахунок"] += 1
кінець

збільшити()
збільшити()
збільшити()

друк(стан)
```
