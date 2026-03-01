# Skills for OneScript

Набор **Cursor Agent Skills** для языка [OneScript](https://oscript.io/learn/) и экосистемы фреймворков [Autumn](https://autumn-library.github.io/). Skills дают агенту Cursor инструкции по синтаксису, структуре проектов и типичным паттернам при работе с кодом на OneScript.

## Навыки (skills)

| Skill          | Описание                                                                                                                                                                     |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **onescript**  | Язык OneScript: структура модуля (.os), типы, конструкции, проекты (packagedef, src/Классы, src/Модули), библиотеки (#Использовать), opm.                                    |
| **autumn**     | Фреймворк Autumn (ОСень): DI, компоненты («желуди»), Осень.НайтиЖелудь(), аннотации &Желудь, &Дуб, &Верховный, &Завязь, точка входа Поделка.                                 |
| **autumn-cli** | Консольные приложения: команды и подкоманды (&КомандаПриложения, &ПодкомандаПриложения), аргументы и опции (&Аргумент, &Опция), &ВыполнениеКоманды, типы и осень-properties. |
| **winow**      | Веб-сервер на OneScript и Autumn: &Контроллер, &ТочкаМаршрута, Запрос/Ответ, параметры, ограничения (без HTTPS).                                                             |

## Как использовать

1. **Скопировать в проект**  
   Скопируйте нужную папку из `skills/` в `.cursor/skills/` вашего проекта:
   - `skills/onescript` → `.cursor/skills/onescript`
   - `skills/autumn` → `.cursor/skills/autumn`
   - и т.д.

2. **Или указать путь к репозиторию**  
   Если в Cursor/агент настроен на чтение skills из внешнего каталога, укажите путь к этому репозиторию или к папке `skills` в нём.

После подключения агент будет применять соответствующий skill при работе с файлами .os, Autumn, autumn-cli или Winow (по описанию в `description` каждого SKILL.md).

1. **Подключение в своём проекте (AGENTS.md / .cursor/rules)**  
   Чтобы явно указать агенту на эти skills, в корне своего OneScript-проекта можно добавить:
   - **AGENTS.md** — пример в [example-for-project/AGENTS.md.example](example-for-project/AGENTS.md.example): скопировать в проект как `AGENTS.md` и при необходимости поправить пути.
   - **.cursor/rules** — пример текста для rule-файла в [example-for-project/cursor-rules-example.md](example-for-project/cursor-rules-example.md): создать `.cursor/rules/onescript-skills.mdc` или вставить блок в существующее правило.

## Источники

- [OneScript — изучение](https://oscript.io/learn/)
- [Autumn Docs](https://autumn-library.github.io/)

## Лицензия

MIT — см. [LICENSE](LICENSE).
