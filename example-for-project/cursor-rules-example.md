# Пример правил для .cursor/rules

Создай в своём проекте файл `.cursor/rules/onescript-skills.mdc` (или добавь блок в существующий rule-файл) со следующим содержимым. Отредактируй путь к репозиторию, если skills лежат не рядом.

---

При работе с OneScript (.os, packagedef, #Использовать, классы, модули) и фреймворками Autumn, autumn-cli, Winow используй инструкции из skills:

- skills-onescript: склонирован в `../skills-onescript` (или укажи свой путь). Папки skills: `onescript`, `autumn`, `autumn-cli`, `winow`.
- Либо skills уже скопированы в `.cursor/skills/` этого проекта — тогда агент подхватит их по описанию в SKILL.md.

Выбирай skill по контексту: файлы .os и проектная структура → onescript; DI и желуди → autumn; консольные команды → autumn-cli; веб-маршруты и контроллеры → winow.
