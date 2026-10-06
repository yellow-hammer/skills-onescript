# Skills for OneScript

Навыки и правила для [OneScript](https://oscript.io/learn/) и фреймворков [Autumn](https://autumn-library.github.io/). Навыки учат агента собирать пакет. Правила задают стиль и грабли платформы в проекте, куда их скопировали.

## Навыки

| Skill | Когда |
| --- | --- |
| **onescript** | Пакет: `packagedef`, `src/Модули`, `src/Классы`, `internal`, opm, `#Использовать`. |
| **onescript-tests** | Тесты OneUnit (`&Тест`, фикстуры, `opm run test`). Если в манифесте `1testrunner`, навык его не подменяет. |
| **autumn** | DI, желуди, `&Деталька`, `&Рогатка`. Основной текст — Autumn 5. |
| **autumn-cli** | Команды, аргументы, опции. Пакет 1.3.0 работает на Autumn 5. |
| **winow** | HTTP-контроллеры, маршруты, каталог `app`. С 0.14 нужен Autumn 5. |

Подробные грабли платформы лежат в `skills/onescript/pitfalls.md`.

## Правила

Каталог `rules/` ставится вместе с навыками в папки выбранного агента:

| Агент | Навыки | Правила |
| --- | --- | --- |
| Cursor | `.cursor/skills/` | `.cursor/rules/*.mdc` |
| GitHub Copilot | `.github/skills/` | `.github/instructions/*.instructions.md` |
| Claude Code | `.claude/skills/` | `.claude/rules/*.md` |

| Файл | К чему применяется |
| --- | --- |
| `os-code-style` | `**/*.os` |
| `os-package` | `packagedef` |
| `os-tests` | `tests/**/*.os` |
| `os-pitfalls` | `**/*.os` |

## Как подключить

1. Скопируй нужные папки из `skills/` в папку навыков выбранного агента.
2. Правила положи в его каталог правил.

Пример `AGENTS.md` и текста правила: [example-for-project](example-for-project/).

## Опора

- [OneScript](https://oscript.io/learn/)
- [Autumn](https://autumn-library.github.io/)

## Лицензия

MIT, см. [LICENSE](LICENSE).
