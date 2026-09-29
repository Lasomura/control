
# GitHub Project

## О проекте

Это учебный проект для изучения Git и GitHub.

## Полезные ссылки

- [GitHub](https://github.com/)
- [Документация Git](https://git-scm.com/doc)
- [Документация GitHub](https://docs.github.com/)

## Изображение

![GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

## Таблица

| Команда | Назначение |
|---|---|
| `git init` | Создание Git-репозитория |
| `git add .` | Добавление файлов |
| `git commit` | Создание коммита |
| `git push` | Отправка файлов на GitHub |

## Диаграмма

```mermaid
graph LR
    A[Изменение файлов] --> B[git add]
    B --> C[git commit]
    C --> D[git push]
    D --> E[GitHub]