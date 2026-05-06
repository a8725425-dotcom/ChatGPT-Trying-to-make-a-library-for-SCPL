# SCPL Math Library (`mathlib`)

Локальная математическая библиотека для SCPL.

## Что внутри
- `pi()`
- `square(x)`
- `cube(x)`
- `avg(a, b)`
- `clamp(value, min, max)`
- `percent(part, whole)`
- `distance2d(x1, y1, x2, y2)`
- `circle-area(r)`
- `circle-length(r)`

## Пример использования
```scpl
Initialize-console
import: mathlib
Console-print: (call square 5)
Console-print: (call cube 3)
Console-print: (call avg 10 14)
Console-print: (call percent 25 200)
Console-print: (call distance2d 0 0 3 4)
Console-print: (call circle-area 2)
Close-console
```

