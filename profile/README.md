<p align="center">
  <img src="logo.png" alt="Borys Grinchenko Kyiv University Logo" width="200" />
</p>

<h1 align="center">Borys Grinchenko Kyiv University</h1>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Moodle-F98012?style=for-the-badge&logo=moodle&logoColor=white" alt="Moodle" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress" />
</p>

<p align="center">
  <strong>Open Source Software and Educational Technology</strong><br>
  <strong>Програмне забезпечення з відкритим вихідним кодом та освітні технології</strong>
</p>

---

## 🏛 About Us / Про нас

**[EN]**<br>
Welcome to the official GitHub organization of **Borys Grinchenko Kyiv University**.
Our mission is to foster open-source development, collaborate on educational technology, and provide tools that empower students, educators, and the broader academic community in Ukraine and worldwide.

Our development primarily focuses on:
*   🎓 **E-Learning Enhancements:** Plugins and optimizations for Learning Management Systems like Moodle.
*   🏫 **University Information Systems:** Deans' office workflows, registries, e-portfolios and admission campaigns.
*   🔌 **API Integrations:** Seamless connections with essential services (e.g., Diia, StrikePlagiarism, Scopus, LDAP).
*   💻 **Student & Research Projects:** Collaborative academic software engineering.
*   🤖 **AI & Agentic Development:** Embracing AI-driven software engineering and agentic workflows in strict compliance with academic integrity, copyright laws, and ethical standards.

<br>

**[UA]**<br>
Ласкаво просимо до офіційної GitHub організації **Київського столичного університету імені Бориса Грінченка**.
Наша місія полягає у сприянні розробці програмного забезпечення з відкритим вихідним кодом, співпраці у сфері освітніх технологій та створенні інструментів, що допомагають студентам, викладачам та ширшій академічній спільноті в Україні та світі.

Наша розробка насамперед зосереджена на:
*   🎓 **Покращення електронного навчання:** Плагіни та оптимізації для систем управління навчанням, таких як Moodle.
*   🏫 **Інформаційні системи університету:** Робочі процеси деканатів, реєстри, е-портфоліо та вступні кампанії.
*   🔌 **API Інтеграції:** Безшовне підключення до ключових сервісів (наприклад, Дія, StrikePlagiarism, Scopus, LDAP).
*   💻 **Студентські та дослідницькі проєкти:** Спільна академічна розробка програмного забезпечення.
*   🤖 **ШІ та агентна розробка:** Впровадження підходів до розробки програмного забезпечення на базі штучного інтелекту з суворим дотриманням академічної доброчесності, авторського права та етичних стандартів.

---

## 🌟 Featured Projects / Популярні проєкти

*   **[claude-skills](https://github.com/grinchenkoedu/claude-skills):**
    *   *(EN)* Our shared toolkit of [Claude Code](https://claude.com/claude-code) skills for everyday development — planning, implementing, reviewing and verifying. Repository-agnostic, documented in English and Ukrainian. See below.
    *   *(UA)* Наш спільний набір навичок [Claude Code](https://claude.com/claude-code) для щоденної розробки — планування, реалізація, рецензування та перевірка. Не прив'язаний до конкретного репозиторію, документація англійською та українською. Див. нижче.
*   **[local_cleanup](https://github.com/grinchenkoedu/local_cleanup):**
    *   *(EN)* A robust Moodle plugin designed to optimize storage and database performance by identifying and removing unnecessary orphaned files, old submissions, and logs.
    *   *(UA)* Надійний плагін Moodle, призначений для оптимізації продуктивності сховища та баз даних шляхом пошуку та видалення непотрібних файлів-сиріт, старих робіт і логів.
*   **[diia-php](https://github.com/grinchenkoedu/diia-php):**
    *   *(EN)* A PHP client for interacting with the Diia (Дія) API, facilitating digital state services integration.
    *   *(UA)* PHP-клієнт для взаємодії з API Дія, що сприяє інтеграції з державними цифровими сервісами.
*   **[strike-plagiarism-php](https://github.com/grinchenkoedu/strike-plagiarism-php):**
    *   *(EN)* A PHP client wrapper for the StrikePlagiarism API v2, helping maintain academic integrity.
    *   *(UA)* Обгортка PHP-клієнта для API StrikePlagiarism v2, що допомагає підтримувати академічну доброчесність.
---

## 🤖 AI-Assisted Development / Розробка за допомогою ШІ

**[EN]**<br>
We develop with AI assistance openly and deliberately. Our shared toolkit lives in
**[claude-skills](https://github.com/grinchenkoedu/claude-skills)** — six
[Claude Code](https://claude.com/claude-code) skills covering an ordinary development day.
Install them with two commands:

```
/plugin marketplace add grinchenkoedu/claude-skills
/plugin install toolkit@grinchenkoedu
```

| Command | What it does |
|---|---|
| `/plan` | Turns a request or a written brief into a plan, checked against the real code |
| `/implement` | Builds it step by step, resuming where it stopped if interrupted |
| `/review` | Checks your own changes before you push them |
| `/pr-review` | Reviews someone else's pull request in an isolated worktree |
| `/pr-resolve` | Works through review comments — verdict first, never blind fixes |
| `/verify` | Runs the tests and drives the real thing to prove it works |

They are repository-agnostic, run a project's commands **inside its Docker container** so checks
use the version the project actually targets, and are written to be economical enough for a basic
Claude subscription. Full documentation, including a beginner's walkthrough, is available in
[English](https://github.com/grinchenkoedu/claude-skills/blob/main/README.md) and
[Ukrainian](https://github.com/grinchenkoedu/claude-skills/blob/main/README.uk.md).

> **Academic integrity:** AI assistance is a tool, not an author. You remain responsible for
> every line you submit — understand it, test it, and be able to explain it. Never submit code
> you cannot account for.

<br>

**[UA]**<br>
Ми розробляємо із залученням ШІ відкрито й усвідомлено. Наш спільний набір інструментів —
**[claude-skills](https://github.com/grinchenkoedu/claude-skills)**: шість навичок
[Claude Code](https://claude.com/claude-code), що покривають звичайний робочий день розробника.
Встановлення — дві команди:

```
/plugin marketplace add grinchenkoedu/claude-skills
/plugin install toolkit@grinchenkoedu
```

| Команда | Що робить |
|---|---|
| `/plan` | Перетворює запит або письмовий опис на план, звірений із реальним кодом |
| `/implement` | Виконує його крок за кроком, продовжуючи з місця зупинки після перерви |
| `/review` | Перевіряє ваші власні зміни перед відправкою |
| `/pr-review` | Рецензує чужий пул-реквест в ізольованому робочому дереві |
| `/pr-resolve` | Опрацьовує коментарі рецензентів — спершу вердикт, жодних сліпих виправлень |
| `/verify` | Запускає тести й перевіряє, що воно справді працює |

Вони не прив'язані до конкретного репозиторію, виконують команди проєкту **всередині його
Docker-контейнера** — тож перевірки йдуть на тій версії, під яку проєкт написано, — і достатньо
ощадливі для базової підписки Claude. Повна документація, разом із покроковим прикладом для
початківців, доступна [англійською](https://github.com/grinchenkoedu/claude-skills/blob/main/README.md)
та [українською](https://github.com/grinchenkoedu/claude-skills/blob/main/README.uk.md).

> **Академічна доброчесність:** ШІ — це інструмент, а не автор. Ви відповідаєте за кожен
> надісланий рядок: розумійте його, тестуйте й будьте здатні пояснити. Ніколи не надсилайте код,
> за який не можете відповісти.

---

## 🤝 How to Contribute / Як долучитися

**[EN]**<br>
We welcome contributions from our students, faculty, and the global open-source community!

1. **Work on a branch** — `feature/<short-description>` or `fix/<short-description>`. Please do
   not push directly to the default branch.
2. **Read the repository's own conventions first.** Where a project has an `AGENTS.md` or
   `CLAUDE.md`, that file is the source of truth for its setup, coding style and release steps.
3. **Use Docker for local development.** Most of our projects ship a `docker-compose.yml` or a
   `Makefile`, so you should not need PHP, Composer or Python installed on your machine.
4. **Check your own work before asking for review** — `/review` from our toolkit, or simply read
   your own diff carefully.
5. **Open a Pull Request and request [@matasarei](https://github.com/matasarei) as the reviewer.**
   Every change is reviewed by a person before it is merged; an automated review is a first pass,
   never the approval.
6. **Moodle plugins:** remember to bump `$plugin->version` in `version.php` when you add or move
   anything under `classes/`, or change `db/` schema, caches or scheduled tasks — otherwise a live
   site will not pick up your code.

<br>

**[UA]**<br>
Ми вітаємо внески від наших студентів, викладачів та світової спільноти open-source!

1. **Працюйте в гілці** — `feature/<короткий-опис>` або `fix/<короткий-опис>`. Будь ласка, не
   надсилайте зміни напряму до основної гілки.
2. **Спершу прочитайте домовленості самого репозиторію.** Якщо у проєкті є `AGENTS.md` чи
   `CLAUDE.md`, саме цей файл є джерелом істини щодо налаштування, стилю коду та випуску.
3. **Використовуйте Docker для локальної розробки.** Більшість наших проєктів має
   `docker-compose.yml` або `Makefile`, тож PHP, Composer чи Python встановлювати локально не
   потрібно.
4. **Перевірте власну роботу перед тим, як просити рецензію** — командою `/review` з нашого
   набору або просто уважно прочитавши власний diff.
5. **Відкрийте Pull Request і призначте рецензентом [@matasarei](https://github.com/matasarei).**
   Кожна зміна перед злиттям переглядається людиною; автоматична рецензія — це перший прохід, а не
   схвалення.
6. **Плагіни Moodle:** не забудьте підняти `$plugin->version` у `version.php`, якщо ви додали або
   перемістили щось у `classes/` чи змінили схему `db/`, кеші або заплановані завдання — інакше
   робочий сайт не побачить ваш код.

---

## 📬 Contact & Links / Контакти та посилання
*   🌐 **Website / Вебсайт:** [kubg.edu.ua](https://kubg.edu.ua/)
*   👤 **Code review / Код-рев'ю:** [@matasarei](https://github.com/matasarei)
*   📍 **Location / Розташування:** Kyiv, Ukraine / Київ, Україна

---
<p align="center">
  <i>"Education is the most powerful weapon which you can use to change the world."</i><br>
  <i>"Освіта – це найпотужніша зброя, яку ви можете використати, щоб змінити світ."</i>
</p>
