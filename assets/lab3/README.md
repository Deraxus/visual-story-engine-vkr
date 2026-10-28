# Диаграммы ЛР 3

| Модель | Файлы |
|---|---|
| М1 — компоненты движка | `01-components.puml`, `01-components.png` |
| М2 — данные сценария | `02-scenario-data.puml`, `02-scenario-data.png` |
| М3 — состояние прохождения | `03-session-state.puml`, `03-session-state.png` |
| М4 — принятие выбора | `04-choice-sequence.puml`, `04-choice-sequence.png` |
| М5 — выдача следующего кадра | `05-execution-activity.puml`, `05-execution-activity.png` |
| М6 — AS-IS | `06-as-is.puml`, `06-as-is.png` |
| М7 — TO-BE | `07-to-be.puml`, `07-to-be.png` |

Исходники имеют кодировку UTF-8. Изображения подготовлены в [PlantUML 1.2026.9](https://github.com/plantuml/plantuml/releases/tag/v1.2026.9).

Для повторного построения из этой папки:

```text
java -jar <путь-к-plantuml.jar> -charset UTF-8 -tpng -nometadata *.puml
```

[Описание параметров командной строки](https://plantuml.com/command-line).
