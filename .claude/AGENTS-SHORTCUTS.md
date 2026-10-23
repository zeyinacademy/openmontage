# Агенты: шпаргалка (OpenMontage)

Активные агенты лежат в `.claude/agents/` и видны в каждой сессии. Их немного, чтобы не тратить токены.
Остальные лежат в `.claude/agents-library/`: в контекст не попадают, токены не тратят.

## Задача → агент

| Задача | Агент |
|---|---|
| Монтаж коротких видео | Short-Video Editing Coach |
| YouTube: удержание, превью, главы | Video Optimization Specialist |
| Сценарии и тексты | Content Creator |
| TikTok | TikTok Strategist |
| Instagram Reels | Instagram Curator |
| Видео для рекламы | Ad Creative Strategist |

Мелкую задачу проще попросить напрямую, без агента. Агент нужен, когда работа большая: план, аудит, серия текстов.

## Как вызвать

Напишите в чате: «Используй агента Instagram Curator и сделай контент-план на неделю».

## Как включить агента из библиотеки

Найдите файл в `.claude/agents-library/` и попросите Claude: «Перенеси agents-library/<файл>.md в agents». Выключить — обратно.
Источник: https://github.com/msitarzewski/agency-agents (MIT).
