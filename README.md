# info15 — База знаний и вики по каналу @yersham

Репозиторий содержит русскоязычную базу знаний (LLM-wiki) по материалам YouTube-канала `@yersham` (`UCXu7rUYYfUmbe6jBS0bSeMQ`, Казахстан), посвящённого технологиям искусственного интеллекта, агентным системам, разработке ПО, математике и биологии/медицине. По состоянию на момент формирования вики в ней зафиксированы данные канала: 4 710 подписчиков, 2 661 видео, 485 030 просмотров (основная видимая выборка — ~188 уникальных видео в тематических каталогах).

## Структура репозитория

```text
.
├── LICENSE             # Лицензия GNU AGPL v3.0
├── README.md           # Этот файл
├── yersham_wiki/       # Основная база знаний (28 Markdown-файлов)
│   ├── README.md       # Навигация по всем разделам и хронология канала (2009–2026)
│   ├── CLAUDE.md       # Правила ведения wiki (принципы Karpathy LLM Knowledge Bases)
│   ├── 00-channel-overview.md ... 14-knowledge-systems.md
│   ├── 16-biology-medicine.md ... 19-deep-dives-2025.md
│   ├── 20-innovations-2026.md
│   └── 20-catalog-agi-future.md ... 25-catalog-platforms-infra.md
└── yersham_wiki_v2/    # Расширенная практическая версия wiki (8 Markdown-файлов)
    ├── README.md       # Карта разделов v2 и отличия от первой версии
    ├── 00-v2-overview.md
    ├── 01-v2-agentic-methods.md
    ├── 02-v2-neural-innovation-radar.md
    ├── 03-v2-implementation-playbooks.md
    ├── 04-v2-risk-governance.md
    ├── 05-v2-tools-stack-2026.md
    └── 06-v2-new-video-evidence.md
```

### Основные разделы

- **[`yersham_wiki/README.md`](yersham_wiki/README.md)** — базовая вики:
  - обзоры канала и персон (`00-channel-overview.md`, `12-key-figures.md`);
  - темы по ИИ: AGI (`01`), архитектура агентов (`02`), Claude и Anthropic (`03`), Context Engineering (`04`), Spec-Driven Development (`05`), открытые модели (`06`), сознание и когнитивные эффекты (`07`), экономика и общество (`08`), математические основы (`09`), Vibe Coding (`10`), нереализованные идеи (`11`), системы знаний (`14`), биология и медицина (`16`), платформы и инструменты (`17`), нарратив и разборы видео 2025–2026 (`13`, `18`, `19`, `20-innovations-2026.md`);
  - 6 тематических каталогов видео со ссылками и описаниями (`20-catalog-agi-future.md` — `25-catalog-platforms-infra.md`);
  - правила редактирования для LLM-агентов ([`yersham_wiki/CLAUDE.md`](yersham_wiki/CLAUDE.md)).
- **[`yersham_wiki_v2/README.md`](yersham_wiki_v2/README.md)** — практическое дополнение: операционные модели (`Planner→Executor→Verifier`, dual-loop), пошаговые планы внедрения (30/60/90 дней), оценка рисков и governance, стек инструментов 2026 года и разборы новых видео.

## Технологический стек и использование

Репозиторий состоит исключительно из текстовых документов в формате Markdown; исполняемого кода, зависимостей, сборочных скриптов и автоматических тестов в репозитории нет.

Внутри статей используются перекрёстные вики-ссылки вида `[[имя-файла]]`, поэтому базу удобно просматривать:
- напрямую в веб-интерфейсе GitHub, начиная с [`yersham_wiki/README.md`](yersham_wiki/README.md) и [`yersham_wiki_v2/README.md`](yersham_wiki_v2/README.md);
- локально как хранилище Obsidian (файлы связаны относительными вики-ссылками).

## Ветки репозитория

- `main` — основная ветка, содержит актуальное состояние обеих директорий (`yersham_wiki/` и `yersham_wiki_v2/`).
- `claude/research-ai-innovations-Oo3xP` — ветка разработки основной вики (влита в `main` через PR [#1](https://github.com/svend4/info15/pull/1), [#2](https://github.com/svend4/info15/pull/2) и [#5](https://github.com/svend4/info15/pull/5)).
- `codex/analyze-youtube-channel-for-ai-innovations` — ветка первичной структуры `yersham_wiki_v2/` (влита в `main` через PR [#3](https://github.com/svend4/info15/pull/3)).
- `codex/analyze-youtube-channel-for-ai-innovations-eue9hx` — ветка доработки `yersham_wiki_v2/` (влита в `main` через PR [#4](https://github.com/svend4/info15/pull/4)).
- `codex/readme-overview-20261118` — открытый черновик PR [#6](https://github.com/svend4/info15/pull/6) с кратким обзором репозитория для корневого `README.md`.

## Лицензия

Проект распространяется под лицензией **GNU Affero General Public License v3.0 (AGPL-3.0)** — см. файл [`LICENSE`](LICENSE).
