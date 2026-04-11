# Spec-Driven Development (SDD)

> Связи: [[04-context-engineering]] [[10-vibe-coding]] [[03-claude-anthropic]] [[11-frontier-unrealized]]

## Что это

**Spec-Driven Development** — методология разработки ПО через спецификации.
Вместо "напиши код" → "опиши что должна делать система" → ИИ пишет код по спецификации.

Нарратив канала: SDD = следующий шаг после Vibe Coding. Vibe Coding умирает → приходит SDD.

---

## Серия видео (7 частей)

| # | Видео | Ссылка | Продолж. |
|---|-------|--------|----------|
| 0 | Эпоха ИИ: переход к разработке на основе спецификаций | youtu.be/7TB-PdgdUM0 | 13:58 |
| 1 | SDD: От промптов к спецификациям. Конец Vibe Coding | youtu.be/TlH8uOdKiIY | 15:19 |
| 2 | SDD: Четыре фазы SDD | youtu.be/m_qK4djDfu4 | 15:37 |
| 3 | SDD: Триумф или иллюзия? | youtu.be/x3-yf60205A | 17:24 |
| 4 | SDD: План реализации | youtu.be/yk1jJxsG0qU | 17:25 |
| 5 | SDD: Design OS — Product × AI Frontend | youtu.be/x9j2kvW2O64 | 15:11 |
| + | Spec-Driven Development в Amazon Kiro: введение | youtu.be/EANDHtAHHMY | 16:18 |
| + | Spec-Driven Development: агентная разработка на уровне FAANGC | youtu.be/mQwHSNHbTZ0 | ? |

---

## Четыре фазы SDD

1. **Requirements Spec** — описание требований на естественном языке
2. **Design Spec** — архитектурный дизайн (ИИ предлагает, человек утверждает)
3. **Implementation Plan** — пошаговый план с чекпоинтами
4. **Code Generation** — ИИ генерирует код по спецификации

---

## Amazon Kiro

Первый коммерческий IDE, построенный на принципах SDD (2025).
Видео: youtu.be/EANDHtAHHMY

Amazon встраивает SDD в корпоративный workflow.
Это первый крупный инструмент — но массового принятия нет.

---

## Почему Vibe Coding недостаточно

Из серии видео:
- Vibe coding = "попроси ИИ написать код без понимания"
- Проблемы: отладка невозможна, нет ответственности, нет архитектуры
- Context Engineering заканчивает эпоху vibe coding (youtu.be/C5Q-E7ao1ZE)
- SDD = структура + ИИ + человеческое понимание

---

## Связь с Context Engineering

SDD требует качественного context engineering:
- Спецификация = контекст для ИИ
- Чем точнее спецификация → тем точнее код
- [[04-context-engineering]] описывает как управлять этим контекстом

---

## Статус ⚠️

Сформулировано: ✓
Инструменты: Amazon Kiro (частично)
Массовое принятие: ✗ (99% делает vibe coding)
Корпоративный стандарт: ✗
Образование: ✗
