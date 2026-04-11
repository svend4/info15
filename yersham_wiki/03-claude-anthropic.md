# Claude и Anthropic

> Связи: [[02-agents-architecture]] [[04-context-engineering]] [[05-spec-driven-dev]]

## Обзор

Anthropic и Claude — самая часто встречающаяся тема канала в 2025–2026.
Автор явно использует Claude Code как основной инструмент и разбирает каждое обновление.

---

## Модели и утечки

| Видео | Ссылка | Дата |
|-------|--------|------|
| Утечка Anthropic: Claude Opus 4.7 и дорожная карта | youtu.be/Ln1FLgOFPnA | 2026 |
| Утечка Anthropic: дорожная карта Claude Code и новые модели | youtu.be/hhojBAM2LSY | 2026 |
| Claude Mythos: утечка о прорыве Anthropic | youtu.be/2PQHyyPFnEg | 2026 |
| Claude Mythos: приватизация высокоуровневого интеллекта | youtu.be/C8HxOELtEQw | апр.2026 |
| Эволюция Claude Code: корпоративная архитектура | youtu.be/Oz4VgrIQZIs | апр.2026 |
| Claude Operon, Gemma 4 и рубеж Arc-AGI 3 | youtu.be/FAh6ibnkCt4 | 2026 |

**Claude Mythos** — новая frontier-модель Anthropic с возможностями кибербезопасности (Project Glasswing).
**Claude Opus 4.7** — следующая версия в дорожной карте.

---

## Claude Code

| Видео | Ссылка |
|-------|--------|
| Claude Code: создаём систему знаний AI | youtu.be/MGhi216zyqE |
| Claude Code: 12 архитектурных примитивов v1 | youtu.be/X3cAGKsrCtE |
| Claude Code: 12 архитектурных примитивов v2 | youtu.be/1wyvrF77M0o |
| Claude Code: How to Create and Automate Skills | youtu.be/e5hRtRhNbjQ |
| Claude Code: ваш первый сайт с нуля | youtu.be/FF4Ml9mfr0s |
| Claude Code: эпоха AI-агентов. Ноябрь 2025 | youtu.be/GEQnKaeRMuM |
| Claude Code Gets More Powerful: New Super Update | youtu.be/GDEhx-Dt1nA |
| Утечка Claude Code: архитектурные секреты | youtu.be/UmNX1bpe1EY |
| Автоматизация создания YouTube-контента с Claude Code | youtu.be/1wDkR3Quf3s |
| Claude Code and the Global Restructuring of Software Dev | youtu.be/jnjlXewpTZY |
| Руководство для начинающих по автоматизациям в Claude Code | youtu.be/hrYDIivXhxM |

---

## Claude Skills (агентная абстракция)

| Видео | Ссылка |
|-------|--------|
| Claude Skills: новая агентная абстракция | youtu.be/0Aqld1lB5ws |
| Claude Skills: непрерывное обучение и управление контекстом v1 | youtu.be/inFqHgtd4q4 |
| Claude Skills: непрерывное обучение и управление контекстом v2 | youtu.be/O9E6NbawOMA |
| AI-сотрудники: 250 навыков Claude для преподавателей | youtu.be/RP4TIVcSbXc |
| Эволюция навыков, понятных AI-агентам | youtu.be/DirA0IRguHo |
| Синтез логики: мультинавыковый Markdown и агентная самоэволюция | youtu.be/N3z2ZUFy6Wg |

---

## Claude Co-work и продуктивность

| Видео | Ссылка |
|-------|--------|
| Claude Co-work: полный гайд по агентной продуктивности | youtu.be/zcCHpK3juIo |
| Освоение Claude Co-work: полное руководство | youtu.be/tXPSMJ3ebgs |
| Автоматизация бизнес-процессов с Claude Projects и Co-work | youtu.be/y0PpYZpYNUw |
| Цифровые сотрудники: Claude Co-work v1 | youtu.be/Ru_xYfYJA5Y |
| Агентная революция Claude: дорожная карта 2026 для преподавателей | youtu.be/__8BSt9BuDc |

---

## Система знаний Карпати + Claude

| Видео | Ссылка |
|-------|--------|
| Создание саморазвивающихся систем знаний с Claude Code и архитектурой Карпати | youtu.be/nHMqJWBWYZI |
| Claude Code: создаём систему знаний AI | youtu.be/MGhi216zyqE |

**Концепция**: CLAUDE.md как корень знаний → wiki в Markdown → агент читает, обновляет, связывает.
Это то, что делает данная wiki-база знаний по принципам Карпати.

---

## Ключевые принципы архитектуры Claude (из утечки)

```
CLAUDE.md (конфигурация и память)
    ↓
raw/ (исходные материалы — читает, не редактирует)
    ↓
wiki/ (структурированные .md файлы — пишет и обновляет)
    ↓
health check (лinting — находит противоречия, добавляет связи)
```
