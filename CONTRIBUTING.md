# Contributing

**🇬🇧 English** · [🇺🇦 Українською](#внесок-у-проєкт)

These guidelines apply to every repository in this organization that does not define its own.

## Language

**Write in English or Ukrainian.** That covers pull request titles and descriptions, issue
reports, and review discussion. Pick whichever you can express the problem in most clearly —
a precise Ukrainian description is worth more than an imprecise English one.

Two things stay in English regardless, because they are read by tools and by people outside the
university: **code identifiers** (class, function and variable names) and **commit subject
lines**. Commit bodies may be in either language.

**User-facing strings follow the file you are editing.** Several of our projects have Ukrainian
interface text written inline; matching the surrounding code is correct, and translating it to
English is not an improvement.

## Before you open a pull request

1. **Work on a branch** — `feature/<short-description>` or `fix/<short-description>`. Do not
   push directly to the default branch.
2. **Read the repository's own conventions.** Where a project has an `AGENTS.md` or
   `CLAUDE.md`, that file is the source of truth for its setup, coding style and release steps,
   and it overrides anything here.
3. **Use Docker for local development.** Most projects ship a `docker-compose.yml` or a
   `Makefile`, so you should not need PHP, Composer or Python installed on your machine.
   Running a project's checks inside its container also means they run against the version the
   project actually targets, rather than whatever your machine happens to have.
4. **Review your own diff first.** Either `/review` from
   [claude-skills](https://github.com/grinchenkoedu/claude-skills), or simply read it carefully.
   Most review comments are things the author would have caught by rereading.
5. **Moodle plugins:** bump `$plugin->version` in `version.php` when you add or move anything
   under `classes/`, or change `db/` schema, caches or scheduled tasks. Without it a live site
   will not pick up your code — this is the most common way a correct change fails in
   production.

## Opening the pull request

Describe **what changed and why**. A reviewer who has not seen the ticket, the conversation or
your screen should be able to follow it.

**Request [@matasarei](https://github.com/matasarei) as the reviewer.** Every change is read by
a person before it is merged. An automated review is a first pass, never the approval — bots
are tuned for style and routinely approve changes containing real defects.

If a reviewer is wrong, say so and explain why. Pushing back with evidence is part of the
process, not a breach of it.

## Working with AI assistance

We use AI assistance openly. It is a tool, not an author: you remain responsible for every line
you submit. Understand it, test it, and be able to explain it in review. Never submit code you
cannot account for.

Credit yourself as the author of the work — do not list an AI tool in an `@author` tag.

---

# Внесок у проєкт

[🇬🇧 English](#contributing) · **🇺🇦 Українською**

Ці правила діють для кожного репозиторію організації, який не має власних.

## Мова

**Пишіть англійською або українською.** Це стосується заголовків і описів пул-реквестів,
повідомлень про помилки та обговорення під час рецензії. Обирайте ту мову, якою можете
пояснити проблему найточніше: точний опис українською вартий більше за неточний англійською.

Дві речі лишаються англійською незалежно від вибору, бо їх читають інструменти й люди поза
університетом: **ідентифікатори в коді** (назви класів, функцій, змінних) і **заголовки
комітів**. Тіло коміту може бути будь-якою з двох мов.

**Тексти, які бачить користувач, пишіть так, як у файлі, який редагуєте.** У кількох наших
проєктах інтерфейсні рядки написані українською прямо в коді; відповідати сусідньому коду —
правильно, а перекладати його англійською — не покращення.

## Перед тим, як відкрити пул-реквест

1. **Працюйте в гілці** — `feature/<короткий-опис>` або `fix/<короткий-опис>`. Не надсилайте
   зміни напряму до основної гілки.
2. **Прочитайте домовленості самого репозиторію.** Якщо у проєкті є `AGENTS.md` чи
   `CLAUDE.md`, саме цей файл є джерелом істини щодо налаштування, стилю коду та випуску, і він
   має пріоритет над цим документом.
3. **Використовуйте Docker для локальної розробки.** Більшість проєктів має `docker-compose.yml`
   або `Makefile`, тож PHP, Composer чи Python встановлювати локально не потрібно. Запуск
   перевірок усередині контейнера також означає, що вони йдуть на тій версії, під яку проєкт
   написано, а не на тій, що випадково є на вашій машині.
4. **Спершу перегляньте власний diff.** Командою `/review` з
   [claude-skills](https://github.com/grinchenkoedu/claude-skills) або просто уважно прочитавши
   його. Більшість зауважень рецензента — це те, що автор помітив би сам при перечитуванні.
5. **Плагіни Moodle:** підніміть `$plugin->version` у `version.php`, якщо ви додали або
   перемістили щось у `classes/` чи змінили схему `db/`, кеші або заплановані завдання. Без
   цього робочий сайт не побачить ваш код — це найпоширеніший спосіб, у який правильна зміна
   не спрацьовує на продакшені.

## Оформлення пул-реквесту

Опишіть, **що змінилося і навіщо**. Людина, яка не бачила ні задачі, ні обговорення, ні вашого
екрана, має зрозуміти суть.

**Призначте рецензентом [@matasarei](https://github.com/matasarei).** Кожну зміну перед злиттям
читає людина. Автоматична рецензія — це перший прохід, а не схвалення: боти налаштовані на
стиль і регулярно схвалюють зміни зі справжніми дефектами.

Якщо рецензент помиляється — скажіть про це й поясніть чому. Аргументоване заперечення є
частиною процесу, а не його порушенням.

## Робота з ШІ

Ми користуємося допомогою ШІ відкрито. Це інструмент, а не автор: ви відповідаєте за кожен
надісланий рядок. Розумійте його, тестуйте й будьте здатні пояснити на рецензії. Ніколи не
надсилайте код, за який не можете відповісти.

Вказуйте автором роботи себе — не пишіть назву ШІ-інструмента в теґу `@author`.
