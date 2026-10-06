# Куда копировать навыки и правила

Скопируй навыки и правила по таблице.

| Агент | Навыки | Правила |
| --- | --- | --- |
| Cursor | `.cursor/skills/` | `.cursor/rules/*.mdc` |
| GitHub Copilot | `.github/skills/` | `.github/instructions/*.instructions.md` |
| Claude Code | `.claude/skills/` | `.claude/rules/*.md` |

Исходники правил в этом репозитории — `.mdc` с полем `globs`. В Copilot то же правило пишется с `applyTo`, в Claude Code — с `paths`. В свою папку клади `.mdc` в соседний каталог `rules`.

Навыки: `onescript`, `onescript-tests`, `autumn`, `autumn-cli`, `winow`.

Правила: `os-code-style`, `os-package`, `os-tests`, `os-pitfalls`.
