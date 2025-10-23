Last Updated: 2025-10-23
Status: Актуально на 23 октября 2025

# CONTRIBUTING

Базовый процесс вклада:
- Fork → feature-ветка → PR в `main` → ревью владельца (@VadimDSL) → merge.

Правила:
- Прямые push в `main` запрещены (ветка защищена). Все изменения через PR.
- Ревью владельца обязательно (см. `.github/CODEOWNERS`).
- Формат веток: `feat|fix|docs/<scope>-<short>`.
- Сообщения коммитов: `type(scope): summary` (scopes: `roles/*`, `shared-skills`, `crowd-git`).

Качество и документация:
- Обновляйте README соответствующих папок при изменении структуры [REF: crowd-git/plan.md].
- Поддерживайте [CANONICAL] источники; вторичные упоминания — через [REF:].

CI проверки:
- Markdown lint и проверка ссылок выполняются в GitHub Actions (`.github/workflows/validate.yml`).

