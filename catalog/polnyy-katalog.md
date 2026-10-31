# 📚 Полный каталог ИИ-инструментов для разработчиков (280+)

[← Главная](../README.md) · [Уроки](../docs/01-kak-vybrat.md)

Полная русскоязычная версия списка [jamesmurdza/awesome-ai-devtools](https://github.com/jamesmurdza/awesome-ai-devtools): **282 инструмента в 20 категориях**, описания переведены и сокращены. В [главном README](../README.md) — отобранные лучшие инструменты, сравнительные таблицы и готовые стеки; здесь — всё подряд, включая небольшие и нишевые проекты.

| Метка | Значение |
|---|---|
| 🟢 | Открытый исходный код |
| 🏠 | Работает локально / можно развернуть у себя |
| 🔌 | Поддерживает MCP или сам является MCP-сервером |

## Содержание

- [🖥 Среды разработки](#-среды-разработки)
  - [🖥 ИИ-IDE](#-ии-ide)
  - [🧩 Расширения для IDE](#-расширения-для-ide)
- [⌨️ Терминал](#️-терминал)
  - [⌨️ Агенты в терминале](#️-агенты-в-терминале)
  - [🔧 CLI-утилиты](#-cli-утилиты)
- [🌐 Веб-инструменты](#-веб-инструменты)
  - [🏗 Конструкторы приложений](#-конструкторы-приложений)
  - [🎨 Генераторы интерфейсов](#-генераторы-интерфейсов)
  - [🤖 Облачные агенты для кода](#-облачные-агенты-для-кода)
  - [🧠 Понимание кодовой базы](#-понимание-кодовой-базы)
  - [🗄 Базы данных и SQL](#-базы-данных-и-sql)
  - [✂️ Сниппеты и утилиты](#️-сниппеты-и-утилиты)
- [💻 Десктопные и мобильные приложения](#-десктопные-и-мобильные-приложения)
- [⚡ Автоматизация](#-автоматизация)
  - [👀 Ревью пулл-реквестов](#-ревью-пулл-реквестов)
  - [🧪 Тесты и CI/CD](#-тесты-и-cicd)
- [🏗 Инфраструктура агентов](#-инфраструктура-агентов)
  - [🕸 Оркестрация нескольких агентов](#-оркестрация-нескольких-агентов)
  - [📦 Песочницы и изоляция](#-песочницы-и-изоляция)
  - [⚙️ Конфигурация и контекст](#️-конфигурация-и-контекст)
  - [💸 Учёт токенов и расходов](#-учёт-токенов-и-расходов)
- [🛠 Специализированные инструменты](#-специализированные-инструменты)
  - [🌿 Git и коммиты](#-git-и-коммиты)
  - [📝 Генерация документации](#-генерация-документации)
- [📖 Ресурсы](#-ресурсы)
  - [🇷🇺 На русском](#-на-русском)

---

## 🖥 Среды разработки

### 🖥 ИИ-IDE

Полноценные среды разработки со встроенным ИИ для генерации кода, чата и отладки.

- **[Cursor](https://www.cursor.com/)** — самая популярная ИИ-IDE: чат, правки, генерация и отладка, режим агента. Форк VS Code, поэтому интерфейс и расширения привычные.
- **[Windsurf](https://windsurf.com)** — ИИ-IDE с чатом, правками и агентом Cascade. Форк VS Code, раньше назывался Codeium.
- **[Zed](https://zed.dev/)** 🟢 🏠 — быстрый совместный редактор от создателей Atom и Tree-sitter, со встроенным ИИ и поддержкой локальных моделей.
- **[Replit](https://replit.com/)** — облачная IDE в браузере: автодополнение, чат, агент для разработки и деплой в один клик.
- **[Google Antigravity](https://antigravity.google/)** — IDE «агенты прежде всего» от Google: автономные агенты планируют, выполняют и проверяют сложные задачи, глубоко интегрированы с браузером.
- **[Trae](https://www.trae.ai/)** — адаптивная ИИ-IDE с чатом и генерацией кода.
- **[Theia IDE](https://theia-ide.org/#theiaide)** 🟢 🏠 — расширяемая open-source IDE (веб и десктоп) с ИИ-чатом, автодополнением, помощью в терминале и своими агентами на любых LLM. Построена на платформе Theia AI.
- **[Mutable](https://github.com/mutableai/monitors4codegen)** — веб-IDE с чат-ботом и интеграцией с GitHub.
- **[UI Pilot](https://ui-pilot.com/)** — чат-редактор, который генерирует формы на Material UI.
- **[GitWit](https://gitwit.dev/)** — веб-редактор для создания React-приложений с ИИ.
- **[OneCompiler](https://onecompiler.com/)** — бесплатный онлайн-компилятор с ИИ для 70+ языков: пиши, запускай и делись кодом.
- **[BuilderStudio](https://builderstudio.dev)** — нативное macOS-пространство для агентной разработки: навыки, MCP, изолированное выполнение в контейнерах, параллельные агенты и маршрутизация между 380+ моделями.

### 🧩 Расширения для IDE

Плагины, добавляющие автодополнение, чат и рефакторинг в привычные редакторы.

- **[GitHub Copilot](https://github.com/features/copilot)** — самый распространённый ИИ-ассистент: автодополнение, чат, режим агента, генерация описаний PR и тестов. VS Code, JetBrains, Visual Studio, Vim и др.
- **[Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev)** 🟢 🏠 — автономный агент для VS Code: создаёт и правит файлы, выполняет команды и пользуется браузером с твоего разрешения. Поддерживает OpenRouter, Anthropic, OpenAI, Gemini, Bedrock, Azure, Vertex и локальные модели.
- **[Continue](https://continue.dev/)** 🟢 🏠 — расширение для VS Code и JetBrains: чат, рефакторинг, генерация кода, правки в нескольких файлах и запуск команд.
- **[Tabnine](https://www.tabnine.com/)** 🏠 — ассистент автодополнения с возможностью развёртывания у себя; расширения для 15 редакторов, включая VS Code, IntelliJ, Neovim, Eclipse.
- **[Supermaven](https://supermaven.com/)** — очень быстрое автодополнение с контекстом до 300 000 токенов.
- **[Amazon Q Developer](https://aws.amazon.com/q/developer/build/)** — ассистент AWS для VS Code и JetBrains: ревью, документация, тесты, миграция Java. Бывший CodeWhisperer.
- **[JetBrains AI](https://www.jetbrains.com/ai/)** — ИИ-ассистент и агент во всех IDE JetBrains.
- **[Refact AI](https://refact.ai/)** 🟢 🏠 — open-source ассистент: чат, автодополнение, рефакторинг и дообучение на твоей кодовой базе. VS Code и JetBrains.
- **[Tabby](https://tabbyml.github.io/tabby/)** 🟢 🏠 — self-hosted сервер автодополнения кода, расширения для VS Code, JetBrains и Vim.
- **[Blackbox AI](https://www.useblackbox.io/)** — автодополнение и чат со ссылками на онлайн-источники.
- **[CodeGeeX](https://codegeex.cn/)** 🟢 — ассистент на собственной модели CodeGeeX: чат, автодополнение, рефакторинг; 9 редакторов.
- **[Quack AI](https://www.quackai.com/)** — следит за соблюдением гайдлайнов проекта.
- **[CodeMate](https://www.codemate.ai/)** — отладка и оптимизация кода в VS Code.
- **[AskCodi](https://www.askcodi.com/)** — ассистент для VS Code, JetBrains и Sublime Text.
- **[dbForge AI Assistant](https://www.devart.com/dbforge/ai-assistant/)** — генерация и оптимизация SQL внутри инструментов dbForge.
- **[GoCodeo](https://www.gocodeo.com/)** — агент для VS Code, который собирает и деплоит full-stack приложения с Vercel и Supabase.
- **[Ptah](https://marketplace.visualstudio.com/items?itemName=ptah-extensions.ptah-coding-orchestra)** 🟢 🔌 — мультипровайдерный «оркестр» для VS Code: OpenRouter (200+ моделей), Kimi, GLM, Copilot, Gemini, Codex в одном окне, встроенный MCP-сервер.
- **[aiXcoder](https://www.aixcoder.com/en/)** 🏠 — локальный или облачный ассистент для IntelliJ, CLion, GoLand, PyCharm, WebStorm, VS Code и Eclipse.
- **[Sourcery](https://sourcery.ai/)** — ИИ-ревьюер и линтер со справочником лучших практик Python и JS/TS.
- **[Swimm](https://swimm.io)** — понимание кода через статический анализ и автодокументацию; VS Code и все IDE JetBrains.
- **[Gemini в Android Studio](https://developer.android.com/studio/preview/studio-bot)** — ассистент в Android Studio (бывший Studio Bot): генерация кода, поиск ресурсов, лучшие практики.
- **[IBM watsonx Code Assistant for Z](https://www.ibm.com/products/watsonx-code-assistant-z)** — модернизация мейнфреймов: перевод COBOL в Java, рефакторинг.
- **[EasyCode](https://www.easycode.ai/)** — чат с GPT-моделями в VS Code.
- **[Kilo Code](https://kilocode.ai)** 🟢 🏠 — open-source агент для планирования, написания и исправления кода в VS Code.
- **[FlyonUI MCP](https://flyonui.com/mcp)** 🔌 — MCP-сервер для генерации компонентов, блоков и страниц на Tailwind CSS.
- **[Traycer](https://traycer.ai)** — ассистент «сначала план, потом код» для VS Code.
- **[shadcn/studio MCP](https://shadcnstudio.com/mcp)** 🔌 — MCP-сервер для генерации компонентов shadcn/ui.
- **[onUI](https://github.com/onllm-dev/onUI)** 🟢 🔌 — расширение браузера и MCP-сервер: размечаешь элементы на странице и передаёшь контекст в Claude Code, Cursor, Windsurf или Copilot.
- **[Sweep](https://sweep.dev/)** — ИИ-плагин для JetBrains: автодополнение, индексация кодовой базы, контекстные подсказки.
- **[Antigravity Link](https://github.com/cafeTechne/antigravity-link-extension)** 🟢 🔌 — управление сессиями Google Antigravity с телефона: зеркало чата, отправка сообщений, загрузка файлов.
- **[Shadcn Space MCP](https://shadcnspace.com/mcp)** 🔌 — подключает Cursor, Claude Code, VS Code и др. к реестру компонентов Shadcn Space.
- **[Blueprint (Imbue)](https://marketplace.visualstudio.com/items?itemName=Imbue.imbue-blueprint)** 🟢 — помощник планирования: задаёт вопросы о задаче и пишет markdown-план для любого агента. VS Code, Cursor, Windsurf.

---

## ⌨️ Терминал

### ⌨️ Агенты в терминале

Автономные CLI-агенты: пишут код, выполняют команды, работают с несколькими файлами сразу.

- **[Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview)** 🔌 — агентный инструмент Anthropic для разработки в терминале: понимает весь репозиторий, правит файлы, запускает тесты, поддерживает MCP, хуки, навыки и субагентов.
- **[OpenAI Codex CLI](https://openai.com/codex/)** 🟢 🏠 🔌 — официальный open-source агент OpenAI для терминала: выполняет код, правит файлы, работает с разными провайдерами и локальными моделями.
- **[Aider](https://aider.chat/)** 🟢 🏠 — популярный CLI-ассистент: вносит изменения и сам коммитит их в git. Любые LLM, свои бенчмарки моделей.
- **[OpenHands](https://www.all-hands.dev/)** 🟢 🏠 — open-source автономный разработчик (бывший OpenDevin) с редактором, терминалом и браузером.
- **[Devin](https://devin.ai/)** — автономный ИИ-инженер от Cognition: планирование, код, отладка и деплой в собственной среде.
- **[Gemini CLI](https://geminicli.com/)** 🟢 🔌 — open-source агент Google для командной строки с MCP и интеграцией с shell.
- **[Cursor CLI](https://cursor.com/cli)** — агент Cursor для генерации и правки кода из терминала.
- **[Goose](https://block.github.io/goose/)** 🟢 🏠 🔌 — open-source агент от Block, работает на твоей машине, расширяется через MCP, поддерживает разные LLM.
- **[Amazon Q Developer CLI](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line.html)** — автодополнение команд, перевод запроса на естественном языке в команду и агентный чат. macOS, Linux, Windows (WSL).
- **[Cosine](https://cosine.sh/)** — агент для корпоративных кодовых баз: баги, фичи, рефакторинг, PR; развёртывание в изолированном контуре.
- **[AdaL](https://sylph.ai/)** — агент, в котором совместно работают модели Claude, GPT и Gemini; запоминает паттерны кодовой базы.
- **[Axon](https://github.com/kill136/axon)** 🟢 🔌 — ассистент с веб-IDE, мультиагентной системой и 37+ инструментами.
- **[Mini SWE-Agent](https://mini-swe-agent.com/latest/)** 🟢 — минималистичный агент для обучения и экспериментов с идеями SWE-agent.
- **[Micro Agent](https://www.builder.io/blog/micro-agent)** 🟢 — агент, который пишет код и исправляет его, пока не пройдут тесты.
- **[Blueprint](https://github.com/JuliusBrussee/blueprint)** 🟢 — плагин для Claude Code: из описания — в план, из плана — в параллельные задачи сборки с автоматической проверкой и перекрёстным ревью моделями.
- **[cmux](https://github.com/manaflow-ai/cmux)** 🟢 — терминал для macOS на базе Ghostty с вертикальными вкладками и уведомлениями от агентов.
- **[pi](https://pi.dev/)** 🟢 🏠 — минималистичный расширяемый агент: расширения на TypeScript, навыки, шаблоны промптов и темы распространяются как npm-пакеты.

### 🔧 CLI-утилиты

Лёгкие консольные инструменты: коммиты, контекст для LLM, автоматизация.

- **[gptcomet](https://github.com/belingud/gptcomet)** 🟢 — генерирует сообщения коммитов и делает ревью изменений; разные провайдеры и языки.
- **[Baz CLI](https://github.com/baz-scm/baz-cli)** 🟢 — ИИ-ревью кода из терминала с доступом к диффу и коду.
- **[models](https://github.com/arimxyer/models)** 🟢 — TUI для просмотра моделей, бенчмарков Artificial Analysis и агентов. Rust + Ratatui.
- **[Jctx](https://github.com/Shashwat-Gupta57/Jctx)** 🟢 — собирает структурированный контекст из проектов на Python, Kotlin и Java для LLM, с картой зависимостей и оценкой токенов.
- **[CCG Workflow](https://github.com/fengshao1227/ccg-workflow)** 🟢 — связка Claude + Codex + Gemini для Claude Code: 28 слэш-команд, умная маршрутизация (Gemini — фронтенд, Codex — бэкенд), параллельная работа.
- **[Butterfish](https://butterfi.sh)** 🟢 — ChatGPT прямо в shell с простыми агентными возможностями.
- **[TmuxAI](https://tmuxai.dev/)** — ненавязчивый ИИ-помощник в терминале tmux.
- **[IWE](https://github.com/iwe-org/iwe)** 🟢 — граф знаний из markdown с CLI для агентов, без векторной БД.
- **[Hermes IDE](https://www.hermes-ide.com)** 🟢 — обёртка для zsh, bash и fish: подсказки команд, выполнение задач, управление git и worktree.
- **[codesight](https://github.com/Houseofmvps/codesight)** 🟢 🔌 — сжимает контекст проекта (роуты, схемы, компоненты) для агентов: в 9–13 раз меньше токенов.
- **[prpack](https://github.com/Lucas2944/prpack)** 🟢 — упаковывает пулл-реквест (дифф, коммиты, файлы) в один markdown для ревью моделью.
- **[Marmot](https://marmot.sh)** — единая CLI-команда для агентов: ИИ, веб-поиск, скрейпинг и обогащение данных у разных провайдеров.
- **[ORCH](https://github.com/oxgeneral/ORCH)** 🟢 — запускает Claude Code, OpenCode, Codex и Cursor как команду: статусы задач, ретраи, сообщения между агентами, TUI-панель.
- **[Octomind](https://github.com/muvon/octomind)** 🟢 🔌 — сессионный ИИ-ассистент: 7 провайдеров, план прежде кода, семантический поиск, постоянная память.

---

## 🌐 Веб-инструменты

### 🏗 Конструкторы приложений

Создают и деплоят full-stack приложения по описанию на естественном языке.

- **[Bolt.new](https://bolt.new)** — агент веб-разработки в браузере на WebContainers: npm-пакеты, Node.js-серверы, деплой.
- **[Lovable](https://lovable.dev/)** — превращает описание или дизайн в работающее приложение с деплоем и интеграцией с GitHub.
- **[Backgrounder.dev](https://backgrounder.dev/)** — бесплатный интерфейс для агентов (Claude Code, Codex, Gemini, Goose, Pi) в фоновых процессах: ветвление чатов, расписание запусков.
- **[Co.dev](https://www.co.dev/)** — создание и деплой full-stack приложений.
- **[Capacity](https://capacity.so)** — веб-приложения из текстового описания.
- **[Leap.new](https://leap.new/)** — приложения с настоящим бэкендом и API, деплой в твоё облако.
- **[Pico](https://picoapps.xyz)** — микроприложения с мгновенным деплоем.
- **[SoftGen](https://softgen.ai/)** — генерация веб-приложений.
- **[LlamaCoder](https://llamacoder.together.ai/)** 🟢 — генерация приложений на open-source моделях.
- **[Forge](https://forge-web.rebaselabs.online)** — генерирует Next.js-приложения, работает с твоим API-ключом без наценки.
- **[E2B Fragments](https://fragments.e2b.dev/)** 🟢 — шаблон для создания ИИ-приложений с выполнением кода в песочницах.
- **[Mocha](https://getmocha.com/)** — no-code конструктор веб-приложений.
- **[Pythagora](https://www.pythagora.ai/)** — 14 специализированных агентов собирают React/Node.js-приложения; интеграция с VS Code и Cursor.
- **[Mage](https://usemage.ai/)** 🟢 — full-stack приложения на Wasp, React, Node.js и Prisma.
- **[Make Real](https://makereal.tldraw.com/)** — рисуешь интерфейс на холсте tldraw, получаешь HTML/JS-приложение.
- **[Glowbom](https://glowbom.com/)** — генерация приложений с экспортом на разные платформы.
- **[VULK](https://vulk.dev)** — React + PostgreSQL, Flutter, игры на Three.js и темы Shopify из описания; хостинг в ЕС, экспорт исходников.
- **[Taskade Genesis](https://taskade.com/genesis)** 🔌 — создание агентов, процессов и приложений на естественном языке.
- **[Berrry](https://berrry.app)** — превращает посты из X и Reddit в веб-приложения.
- **[Blank Space](https://www.blankspace.build/)** 🟢 🏠 — open-source альтернатива v0, Lovable и Bolt, можно развернуть у себя.
- **[Fastshot](https://fastshot.ai/)** — no-code создание мобильных приложений.
- **[ai-vertical-saas-gen](https://github.com/kurtnebiev-elvis4/ai-vertical-saas-gen)** 🟢 — CLI генерирует отраслевые SaaS-приложения (Next.js + Supabase) для 20+ ниш.

### 🎨 Генераторы интерфейсов

Генерируют компоненты, макеты и фронтенд-код из текста или дизайна.

- **[v0](https://v0.dev/)** — генерация и доработка UI-компонентов и приложений от Vercel.
- **[Magic Patterns](https://www.magicpatterns.com/)** — UI из промпта, картинки или референса; Shadcn, ChakraUI, Tailwind, экспорт в Figma.
- **[Tempo](https://www.tempolabs.ai/)** — визуальный редактор React-интерфейсов с ИИ.
- **[Google Stitch](https://stitch.withgoogle.com/)** — ИИ-дизайн интерфейсов от Google (бывший Galileo AI).
- **[Uizard](https://uizard.io/)** — многоэкранные макеты из текста, скриншота или наброска от руки.
- **[Polymet](https://polymet.ai)** — прототипирование UI с готовым фронтенд-кодом.
- **[Kombai](https://kombai.com/)** — фронтенд-код из макетов Figma.
- **[CodeParrot](https://www.codeparrot.ai/)** — плагин VS Code: код из Figma с учётом твоих компонентов и стандартов.
- **[Fronty](https://fronty.com/)** — превращает изображение в HTML/CSS.
- **[BoringUi](https://www.boringui.xyz/)** — HTML + Tailwind из JSON-данных.
- **[CSS Picker](https://csspicker.dev/)** — копирует стили с сайтов, картинка в код, текст в UI.
- **[Frontman](https://frontman.sh/)** 🟢 — агент в браузере: кликаешь на элемент, описываешь изменение — получаешь правки кода с горячей перезагрузкой. Next.js, Vite, Astro.

### 🤖 Облачные агенты для кода

Агенты, которые работают с существующим репозиторием в фоне и приносят пулл-реквесты.

- **[Factory](https://www.factory.ai/)** — платформа с агентами «Droids» в IDE, терминале, Slack/Teams и CI/CD: рефакторинг, инциденты, миграции.
- **[Jules](https://jules.google.com/)** — асинхронный агент Google, интегрированный с GitHub: исправляет баги и делает задачи в фоне, создаёт PR.
- **[Potpie](https://potpie.ai)** 🟢 — агенты для вопросов по кодовой базе, тестирования, отладки и проектирования систем.

### 🧠 Понимание кодовой базы

Навигация, поиск и ответы на вопросы о существующем коде.

- **[4DA](https://www.npmjs.com/package/@4da/mcp-server)** 🔌 🏠 — десктоп-приложение и MCP-сервер (36 инструментов): знает стек, зависимости и решения проекта, сканирует уязвимости через OSV.dev.
- **[Sourcegraph Cody](https://about.sourcegraph.com/cody)** — ассистент с чатом, рефакторингом и тестами, хорошо работает с большими кодовыми базами.
- **[Unblocked](https://getunblocked.com/)** — отвечает на вопросы о коде с учётом GitHub, Slack, Jira и Confluence.
- **[Magnet](https://www.magnet.run/)** — рабочее пространство, где репозитории и задачи служат контекстом.
- **[Code to Flow](https://codetoflow.com)** — визуализация кода в интерактивные блок-схемы.
- **[Gru.ai](https://www.gru.ai/)** — помощь с алгоритмами, отладкой и тестами.
- **[sudocode](https://sudocode.ai/)** — управление контекстом агентов в долгих задачах.
- **[sourcebook](https://github.com/maroondlabs/sourcebook)** 🟢 🔌 — генерирует AGENTS.md/CLAUDE.md из структуры кода и истории git без LLM.
- **[Grasp](https://github.com/ashfordeOU/grasp)** 🟢 🔌 🏠 — граф зависимостей по ссылке на репозиторий, оценка «здоровья», сканер безопасности, тепловая карта изменений.
- **[Kasava](https://kasava.dev)** — читает каждый коммит, чтобы отчёты и планы опирались на реальную архитектуру.
- **[SeaGOAT](https://kantord.github.io/SeaGOAT/latest/)** 🟢 🏠 — локальный семантический поиск по коду на векторных эмбеддингах.
- **[ContextWire](https://contextwire.dev)** 🔌 — бесплатный API поиска для агентов (105 поисковиков).
- **[Reflex](https://github.com/reflex-search/reflex)** 🟢 🏠 🔌 — локальный полнотекстовый поиск по коду для агентов: < 100 мс на 10k+ файлов, JSON-вывод.

### 🗄 Базы данных и SQL

- **[Wren AI](https://getwren.ai/oss)** 🟢 🏠 — open-source SQL-агент: вопросы к базе данных на естественном языке.
- **[TEXT2SQL.AI](https://www.text2sql.ai/)** — строит, объясняет и исправляет SQL-запросы по описанию.
- **[SQLAI.ai](https://www.sqlai.ai/)** — генерация, исправление и оптимизация SQL с учётом твоей схемы.

### ✂️ Сниппеты и утилиты

- **[CodePal](https://codepal.ai/)** — быстрая генерация и рефакторинг кода в браузере.
- **[AI Code Convert](https://aicodeconvert.com/)** — перевод кода между языками программирования.
- **[AutoRegex](https://www.autoregex.xyz/)** — регулярные выражения из описания на естественном языке.
- **[unpkg.ai](https://unpkg.ai/)** 🟢 — генерация ESM-модулей JavaScript по URL для быстрого прототипирования.
- **[EnigmaEasel](https://enigmaeasel.com)** — доступные цветовые палитры, OKLCH-градиенты и пары шрифтов с экспортом в Tailwind и SCSS.
- **[JSONFix](https://jsonfix-lake.vercel.app/)** — чинит невалидный JSON.
- **[CronAI](https://cronai-nu.vercel.app/)** — cron-выражения из описания расписания.
- **[RegexAI](https://regexai-six.vercel.app/)** — регулярки с объяснением для разных диалектов.

---

## 💻 Десктопные и мобильные приложения

Нативные приложения для ИИ-разработки, терминалы и управление агентами.

- **[Warp](https://www.warp.dev/)** — ИИ-терминал с подсказками команд, агентами и общей базой знаний команды.
- **[Pieces](https://pieces.app/)** — менеджер сниппетов и «движок контекста» с десктоп-приложением и расширением браузера.
- **[Memex](https://memex.tech/)** — создание приложений на любом стеке на естественном языке прямо на компьютере.
- **[Poirot](https://github.com/LeonardoCardoso/Poirot)** 🟢 🏠 — macOS-приложение для просмотра сессий Claude Code: диффы, повтор команд, работает офлайн.
- **[Anima](https://github.com/btangonan/anima)** 🟢 — macOS-компаньон для Claude Code с «фамильярами» для каждого проекта и наблюдением за сессиями. Tauri + Rust.
- **[Agent FM](https://github.com/agentfm-ai/agent-fm)** 🟢 🏠 — озвучивает сессии Claude Code и Codex: прогресс, блокеры, решения, ошибки.
- **[CCHub](https://github.com/Moresl/cchub)** 🟢 — GUI для экосистемы Claude Code: MCP-серверы, навыки, конфиги, слэш-команды.
- **[Mantra](https://mantra.gonewx.com)** — «машина времени» для сессий Claude Code, Cursor и Windsurf: сохранение и восстановление полного состояния диалога.
- **[Dorothy](https://github.com/Charlie85270/Dorothy)** 🟢 — запуск нескольких агентов (Claude Code, Codex, Gemini) одновременно: автоматизации, канбан, удалённое управление.
- **[Nimbalyst](https://nimbalyst.com)** — среда управления агентами Claude Code и Codex с визуальным редактированием markdown, макетов и схем.
- **[Parallel Code](https://github.com/johannesjo/parallel-code)** 🟢 — параллельный запуск Claude Code, Codex CLI и Gemini CLI с изоляцией через git worktree и общим GUI.
- **[PATAPIM](https://patapim.ai)** — терминальная IDE для агентов: сетка из 9 терминалов, голосовой ввод Whisper, доступ по локальной сети.
- **[IM.codes](https://github.com/im4codes/imcodes)** 🟢 — мобильное и веб-управление терминальными агентами вдали от компьютера: терминал, файлы, git, превью, уведомления.
- **[OpenQuack](https://github.com/larryxiao/openquack)** 🟢 🏠 — локальная голосовая диктовка промптов на macOS через WhisperKit для Claude Code, Cursor, Codex и Aider.
- **[Onepilot](https://onepilotapp.com)** — iOS-приложение для запуска агентов на удалённых серверах по SSH.
- **[Vibe Island](https://vibeisland.app)** — панель в «чёлке» MacBook для 18 CLI-агентов: запросы разрешений, переход в нужный терминал, лимиты провайдеров.
- **[Clave](https://github.com/codika-io/clave)** 🟢 🏠 — нативное macOS-приложение для параллельных сессий Claude Code: сетка, группы, SSH, git-панель, аналитика.

---

## ⚡ Автоматизация

### 👀 Ревью пулл-реквестов

Боты, которые автоматически проверяют PR и предлагают исправления.

- **[CodeRabbit](https://coderabbit.ai/)** — настраиваемое ИИ-ревью: сводки и построчные предложения в PR.
- **[Qodo PR Agent](https://github.com/qodo-ai/pr-agent)** 🟢 🏠 — open-source автоматическое ревью кода. Qodo раньше назывался Codium (не путать с Codeium).
- **[Greptile](https://greptile.com/code-review-bot)** — ревью PR в GitHub и GitLab с полным контекстом кодовой базы.
- **[Macroscope](https://macroscope.com/code-review)** — ревью на основе графа AST и контекста из трекера задач.
- **[Codegen](https://www.codegen.com/)** — PR-агент для корпоративных кодовых баз.
- **[Nova](https://www.trynova.ai/)** — CI-бот: сводки и тесты для новых PR.
- **[PR Explainer Bot](https://pr-explainer-bot.web.app/)** — добавляет пояснения к новым PR.
- **[Goast](https://goast.ai/)** — анализирует логи ошибок и предлагает исправления.
- **[Corgea](https://corgea.com/)** — находит и исправляет уязвимый код.
- **[Pixee](https://pixee.ai)** — находит проблемы безопасности и качества и создаёт готовые к мержу PR.
- **[CodeAnt AI](https://www.codeant.ai/)** — автоматически создаёт PR с исправлениями.
- **[What The Diff](https://whatthediff.ai/)** — пишет понятное описание изменений в PR.
- **[CodeReviewBot](https://codereviewbot.ai/)** — ИИ-ревью для GitHub.
- **[Gito](https://github.com/Nayjest/Gito)** 🟢 🏠 — ревьюер с любой моделью, локально или в GitHub Actions.
- **[Baz](https://baz.co)** — ревьюер, обученный гайдлайнам и соглашениям команды.
- **[Z.ai Code Review](https://github.com/tarmojussila/zai-code-review)** 🟢 — ревью PR на моделях Z.ai (GLM).
- **[MiniMax Code Review](https://github.com/tarmojussila/minimax-code-review)** 🟢 — ревью PR на моделях MiniMax.
- **[Revieko](https://synqra.tech/revieko/)** — «радар» архитектурного дрейфа: оценка структурных рисков PR.
- **[crit](https://crit.md)** 🏠 — ревью работы агентов человеком: комментарии к планам и коду в локальном UI, экспорт в JSON для агента.
- **[CodeHawk](https://codehawk.crossgen-ai.com)** — GitHub App с построчными комментариями о багах и уязвимостях.
- **[Grit](https://app.grit.io)** — агент для автоматизации поддержки кода и миграций.
- **[PR Triage](https://pr-triage-web.vercel.app)** 🟢 — оценивает PR по шести критериям качества с доказательствами из диффа.
- **[prpack-action](https://github.com/Lucas2944/prpack-action)** 🟢 — GitHub Action: упаковывает каждый PR в markdown для ревью моделью.
- **[Issue AI Agent](https://github.com/alexyan0431/issue-ai-agent)** 🟢 — GitHub Action: классифицирует, размечает issues, ищет дубликаты и отвечает.

### 🧪 Тесты и CI/CD

Генерация юнит- и e2e-тестов, ИИ в пайплайнах.

- **[Checksum AI](https://checksum.ai)** — автономный QA-агент: генерирует Playwright-тесты прямо в репозиторий.
- **[OctoMind](https://octomind.dev)** — генерация и автоподдержка браузерных e2e-тестов в GitHub Actions, Azure DevOps.
- **[Traceloop](https://traceloop.com/)** — OpenTelemetry-трассировка + ИИ для надёжности LLM-приложений.
- **[Carbonate](https://carbonate.dev/)** — e2e-тесты на естественном языке для Jest, PHPUnit, unittest.
- **[Meticulous.ai](https://www.meticulous.ai/)** — автоматически создаваемые и поддерживаемые e2e-тесты.
- **[Diffblue](https://www.diffblue.com/)** — автогенерация юнит-тестов для Java.
- **[Qodo](https://www.qodo.ai/)** — генерация содержательных тестов для основных языков; VS Code и JetBrains.
- **[KushoAI](https://kusho.ai/)** — превращает коллекции Postman, OpenAPI и curl в наборы API-тестов для CI/CD.
- **[Wopee.io](https://wopee.io)** — визуальное регрессионное тестирование с ИИ-агентами; Playwright, Cypress, Robot Framework.
- **[Test Gru](https://gru.ai/home#test-gru)** — автоматизация юнит-тестов для бизнеса.
- **[TraceRoot AI](https://traceroot.ai/)** — наблюдаемость с агентами, которые исправляют баги в продакшене.
- **[Fine](https://fine.dev/)** — среда для автоматизации рутины: GitHub, Sentry, Linear, самовосстанавливающийся CI/CD.
- **[CodeFlash](https://www.codeflash.ai/)** — CLI и CI-инструмент для оптимизации Python-кода.
- **[Recurse ML](https://recurse.ml)** — ищет баги в коде, сгенерированном ИИ.
- **[TestDriver](https://testdriver.ai)** — кроссплатформенные e2e-тесты без селекторов.
- **[agent-qa](https://vostride.com)** 🔌 — тестирует веб-приложения, Android и iOS через CLI/MCP с долговременной памятью memidex, проверкой самоулучшений и артефактами прогонов.

---

## 🏗 Инфраструктура агентов

### 🕸 Оркестрация нескольких агентов

Параллельный запуск нескольких агентов с изоляцией рабочих пространств.

- **[Conductor](https://conductor.build/)** — macOS-приложение для одновременной работы нескольких Claude Code и Codex в изолированных git worktree: панель мониторинга, ревью и мерж.
- **[Superset](https://superset.sh/)** — редактор для «роёв» агентов Claude Code, Codex и др. в изолированных worktree.
- **[Sidecar](https://github.com/marcus/sidecar)** 🟢 — TUI-компаньон для CLI-агентов: история, git, задачи, управление рабочим пространством.
- **[Vibe Kanban](https://vibekanban.com/)** 🟢 — канбан-доска для делегирования задач автономным агентам и отслеживания прогресса.
- **[OpenASE](https://github.com/pacificstudio/openase)** 🟢 — тикет-ориентированная платформа для Claude Code, Codex и Gemini CLI.
- **[Trellis](https://github.com/mindfold-ai/Trellis)** 🟢 — фреймворк для Claude Code и Cursor: задачи, спецификации, мультиагентные пайплайны.
- **[Codex в ChatGPT](https://chatgpt.com/codex)** — облачная оркестрация агентов, подключённых к GitHub: каждая задача в своей песочнице, при прохождении тестов — PR.
- **[GolemBot](https://github.com/0xranx/golembot)** 🟢 — единый API поверх Claude Code, Cursor, OpenCode и Codex с адаптерами для Slack, Telegram, Discord.
- **[Stoneforge](https://stoneforge.ai)** 🟢 — параллельный запуск агентов с автоматическим распределением, мержем и восстановлением.
- **[Shep](https://github.com/shep-ai/cli)** 🟢 — центр управления SDLC для агентов с этапами согласования и веб-панелью.
- **[Bernstein](https://github.com/chernistry/bernstein)** 🟢 — детерминированный оркестратор: из одной цели — параллельные агенты, проверка тестами, автокоммит.
- **[GreatCTO](https://github.com/avelikiy/great_cto)** 🟢 — мультиагентный SDLC поверх Claude Code, Cursor, Codex, Aider: 34 агента-специалиста, отраслевые шаблоны и пакеты соответствия (PCI, HIPAA, EU AI Act).
- **[Kagan](https://github.com/kagan-sh/kagan)** 🟢 — доска оркестрации с расширением для VS Code.
- **[LoopTroop](https://github.com/looptroop-ai/LoopTroop)** 🟢 🏠 — локальный GUI-оркестратор: «совет моделей» для планирования, повторные циклы, изоляция в worktree.
- **[MartinLoop](https://martinloop.com/)** 🟢 — контрольная плоскость для агентов: жёсткие лимиты бюджета, проверяющие этапы, журнал аудита.
- **[Forge](https://github.com/LucasDuys/forge)** 🟢 — spec-driven цикл для Claude Code: brainstorm → plan → execute с ревью кода моделью.
- **[SwarmClaw](https://github.com/swarmclawai/swarmclaw)** 🟢 🏠 — self-hosted рантайм для Claude Code, Codex, Gemini CLI, OpenCode, Goose, Qwen Code и др.: расписания, делегирование, оргструктура агентов.
- **[CueAPI](https://github.com/cueapi/cueapi-core)** 🟢 🏠 — планировщик запусков агентов с обязательной проверкой результата.
- **[pi-ralph](https://github.com/samfoy/pi-ralph)** 🟢 — мультиагентные циклы реализации, ревью и отладки для агента pi.
- **[AgentsMesh](https://agentsmesh.ai)** 🏠 🔌 — self-hosted платформа «цифровой команды»: удалённые станции агентов, канбан, интеграция с PR, SSO и аудит.
- **[osModa](https://github.com/bolivian-peru/os-moda)** 🟢 — ИИ-операционная система на NixOS с маршрутизацией между агентами и атомарными откатами.

### 📦 Песочницы и изоляция

Безопасные изолированные окружения для запуска агентов.

- **[VibeBox](https://vibebox.robcholz.com)** 🟢 🏠 — отдельная микро-VM-песочница для каждого проекта на macOS.
- **[brood-box](https://github.com/stacklok/brood-box)** 🟢 🏠 — агенты (Claude Code, Codex, OpenCode) в аппаратно изолированных микро-VM со снапшотами и контролем исходящего трафика.
- **[Open Agent](https://github.com/Th0rgal/openagent)** 🟢 🏠 — self-hosted панель управления Claude Code с изолированными контейнерами.
- **[FlyDex](https://flydex.net)** — удалённое управление локальными сессиями Codex из браузера: сопряжение по QR, подтверждения.
- **[mirrord](https://github.com/metalbear-co/mirrord)** 🟢 — изоляция агентов в общем кластере Kubernetes: фильтры трафика, ветки БД, разделение очередей Kafka.
- **[AgentTier](https://github.com/agenttier/agenttier)** 🟢 🏠 — Kubernetes-рантайм песочниц для агентов: Pod + PVC + запрет сетевого трафика по умолчанию, опционально gVisor.

### ⚙️ Конфигурация и контекст

Управление правилами, контекстом и конфигами агентов в разных редакторах.

- **[Context7](https://context7.com/)** 🔌 — актуальная документация и примеры кода для любой библиотеки прямо в Cursor, Claude Code, Windsurf и др.
- **[ctxlint](https://github.com/YawLabs/ctxlint)** 🟢 — линтер файлов контекста (CLAUDE.md, .cursorrules, copilot-instructions.md): устаревшие пути, неверные команды, лишние токены.
- **[Entroly](https://github.com/juyterman1000/entroly)** 🟢 🔌 — оптимизация контекста, снижающая расход токенов на 70–95%.
- **[lean-ctx](https://leanctx.com)** 🟢 🔌 — сжимает чтение файлов, вывод shell и поиск по коду для агентов.
- **[Caliber](https://github.com/rely-ai-org/caliber)** 🟢 — сканирует код и генерирует конфиги агентов (CLAUDE.md, .cursorrules, навыки, MCP), оценивает настройку по шкале 0–100.
- **[claude-snapshot](https://github.com/adhenawer/claude-snapshot)** 🟢 — экспорт всей настройки Claude Code в архив и восстановление на другой машине.
- **[claude-overlay](https://github.com/mzmmoazam/claude-overlay)** 🟢 — управление конфигами Claude Code для разных провайдеров (Bedrock, OpenRouter, LiteLLM и др.).
- **[LynxPrompt](https://github.com/GeiserX/LynxPrompt)** 🟢 🏠 — платформа для генерации и синхронизации конфигов 30+ ИИ-ассистентов.
- **[Conduit8](https://github.com/conduit8/conduit8)** 🟢 — CLI-реестр навыков для Claude Code.
- **[TokRepo](https://github.com/henu-wang/tokrepo)** 🟢 — реестр 220+ ресурсов для агентов: навыки, промпты, MCP-конфиги.
- **[Domscribe](https://www.domscribe.com/)** 🔌 — передаёт агенту runtime-контекст веб-приложения (props, state, исходник) через MCP.
- **[faf-cli](https://github.com/Wolfe-Jam/faf-cli)** 🟢 — формат `.faf` с «ДНК проекта» для любого ИИ.
- **[ContextMCP](https://contextmcp.ai)** 🏠 🔌 — self-hosted семантический поиск по документации для агентов.
- **[AgentsKB](https://agentskb.com)** 🔌 — база из 39 000+ технических вопросов и ответов через MCP и API.
- **[Not Human Search](https://nothumansearch.ai)** 🔌 — поисковик «агентного веба»: сайты с llms.txt, OpenAPI и MCP.
- **[CLIRank](https://clirank.dev)** 🔌 — рейтинг 400+ API по удобству для ИИ-агентов.
- **[Zenable](https://zenable.io/)** — ограничители для агентов, изучающие стандарты команды.
- **[pi-steering-hooks](https://github.com/samfoy/pi-steering-hooks)** 🟢 — детерминированные запреты для агента pi (без force push и т. п.) без расхода токенов.
- **[Spartan AI Toolkit](https://github.com/spartan-stratos/spartan-ai-toolkit)** 🟢 — 67 слэш-команд с проверками качества: TDD, ревью, атомарные коммиты.
- **[Nex](https://github.com/nex-crm/nex-as-a-skill)** 🔌 — граф знаний организации из почты, Slack, CRM и 100+ сервисов для агентов.
- **[Agentify](https://github.com/koriyoshi2041/agentify)** 🟢 — из OpenAPI-спецификации одной командой: MCP-сервер, AGENTS.md, CLAUDE.md, llms.txt и ещё 5 форматов.
- **[ContextKit](https://nova-labs.dev/contextkit/generate)** — веб-генератор CLAUDE.md, .cursorrules, codex.md и GEMINI.md без отправки данных на сервер.
- **[skill-optimizer](https://github.com/fastxyz/skill-optimizer)** 🟢 — тестирует SKILL.md на разных моделях и переписывает, пока все не достигнут порога качества.
- **[KubeStellar Console kc-agent](https://github.com/kubestellar/console)** 🟢 🔌 — MCP-мост от агентов к мультикластерному Kubernetes. Проект CNCF Sandbox.
- **[SwarmVault](https://github.com/swarmclawai/swarmvault)** 🟢 🏠 🔌 — локальное RAG-хранилище: книги, заметки, код → markdown-вики с графом знаний и гибридным поиском.
- **[claude-code-pro-pack](https://github.com/sisyphusse1-ops/claude-code-pro-pack)** 🟢 — базовый набор из 12 правил для CLAUDE.md и AGENTS.md.
- **[cc-audit](https://github.com/sisyphusse1-ops/cc-audit)** 🟢 — линтер CLAUDE.md/AGENTS.md: утечки секретов, слишком длинные файлы, пропущенные разделы.
- **[GAAI Framework](https://github.com/Fr-e-d/GAAI-framework)** 🟢 — слой управления для агентов: бэклог, память между сессиями, журнал решений, QA-этапы.
- **[intelligence-sync](https://github.com/ainova-systems/intelligence-sync)** 🟢 — один источник правил для всех IDE: пишешь в markdown, движок раскладывает в нативные форматы каждого инструмента.

### 💸 Учёт токенов и расходов

- **[Tokscale](https://github.com/junhoyeo/tokscale)** 🟢 — учёт токенов у OpenCode, Claude Code, Codex, Gemini CLI, Cursor и др., с рейтингом и 3D-графиками.
- **[BurnRate](https://getburnrate.io)** 🏠 — локальная аналитика расходов на Claude Code, Cursor, Codex, Copilot, Windsurf, Cline и Aider с 23 правилами оптимизации.
- **[Code Insights](https://github.com/melagiri/code-insights)** 🟢 🏠 — CLI и дашборд для анализа ИИ-сессий на SQLite.
- **[agenttrace](https://github.com/luoyuctl/agenttrace)** 🟢 🏠 — TUI-наблюдаемость: стоимость, токены, ошибки инструментов, аномалии.
- **[onWatch](https://github.com/onllm-dev/onwatch)** 🟢 🏠 — отслеживание квот у 7 провайдеров, веб-панель, без телеметрии.
- **[claude-lens](https://github.com/Astro-Han/claude-lens)** 🟢 — строка состояния Claude Code с темпом расхода лимитов в окнах 5 ч / 7 дней.
- **[cc-tempo](https://github.com/O0000-code/cc-tempo)** 🟢 — строка состояния: активное время работы, ускорение субагентами, график изменений кода.
- **[ai-coding-tools-pricing](https://github.com/lunacompsia-oss/ai-coding-tools-pricing)** 🟢 — открытый JSON-датасет тарифов ИИ-инструментов для кода, обновляется ежемесячно.
- **[CodeCosts](https://codecosts.pages.dev)** — калькулятор и сравнение стоимости тарифов.
- **[CostPilot](https://nova-labs.dev/cost-dashboard/analyze)** — анализ логов Claude Code в браузере: токены, стоимость, лишние траты.
- **[WhereMyTokens](https://github.com/jeongwookie/WhereMyTokens)** 🟢 — приложение в трее Windows для мониторинга токенов Claude Code в реальном времени.
- **[aicost](https://github.com/dwylq/aicost)** 🟢 — анализ расходов Claude Code, Cursor и Copilot с HTML-дашбордом.
- **[CostGoat](https://costgoat.com)** — приложение в строке меню: квоты агентов и расходы на LLM API, облака и подписки.
- **[TokenWise](https://github.com/CodeShuX/tokenwise)** 🟢 — маршрутизатор задач Claude Code между Haiku, Sonnet и Opus с учётом сэкономленных денег.

---

## 🛠 Специализированные инструменты

### 🌿 Git и коммиты

- **[git-lrc](https://github.com/HexmosTech/git-lrc)** 🟢 — бесплатное ИИ-ревью на каждый коммит.
- **[GitBrain](https://gitbrain.dev/)** — git-клиент: делит изменения и пишет сообщения коммитов.
- **[GitButler](https://gitbutler.com/)** 🟢 — git-клиент с параллельными ветками и генерацией сообщений коммитов.

### 📝 Генерация документации

- **[DiagramGPT](https://www.eraser.io/diagramgpt)** — блок-схемы, ER-диаграммы, архитектура облака и диаграммы последовательностей из текста или кода.
- **[DocuPilot](https://docupilot-alpha.vercel.app)** — GitHub App: обновляет README, CHANGELOG и API-документацию при каждом пуше.
- **[DocuWriter.ai](https://www.docuwriter.ai/)** — документация кода и API из исходников.
- **[EkLine](https://ekline.io/)** — проверки качества и стиля документации, автогенерация.
- **[Changenotes](https://changenotes.app)** — автоматические changelog из коммитов и PR при каждом релизе.

---

## 📖 Ресурсы

- **[aiforcode.io](https://aiforcode.io)** — каталог 40+ ИИ-инструментов с прозрачной оценкой и квизом для выбора.
- **[Awesome Code Docs](https://github.com/johnxie/awesome-code-docs)** — подробные туториалы по open-source ИИ-инструментам.
- **[AI Coding Compare](https://aicodingcompare.com)** — сравнение 50+ ассистентов по функциям, ценам и бенчмаркам.
- **[ClaudeDown](https://claudedown.com)** — трекер сбоев Claude по сообщениям в X.
- **[Havoptic](https://havoptic.com/)** 🟢 — хронология релизов ИИ-инструментов для кода, обновляется ежедневно.
- **[AI Coding Guide (на китайском)](https://github.com/jnMetaCode/ai-coding-guide)** — лучшие практики для 8 инструментов с шаблонами конфигов.
- **[Claude Code Skills (на китайском)](https://claude-skills.bt199.com/)** — каталог навыков, агентов и плагинов для Claude Code.
- **[Awesome AI Startups — Coding](https://github.com/nowork-studio/awesome-ai-startups#-coding--developer-tools)** — 100+ ИИ-инструментов для разработки от небольших стартапов.
- **[awesome-ai-devtools](https://github.com/jamesmurdza/awesome-ai-devtools)** — англоязычный первоисточник этого каталога.

### 🇷🇺 На русском

- **[deepseek-local-guide-ru](https://github.com/justxor/deepseek-local-guide-ru)** — полный гайд по запуску DeepSeek и других моделей локально: Ollama, llama.cpp, LM Studio, vLLM, подключение к VS Code.
- **[awesome-decomp-games-ru](https://github.com/justxor/awesome-decomp-games-ru)** — каталог декомпиляций и нативных портов игр.

---

Нашёл ошибку или новый инструмент? Открой [Issue](../../../issues/new/choose) или Pull Request — см. [CONTRIBUTING.md](../CONTRIBUTING.md).

[← Главная](../README.md)
