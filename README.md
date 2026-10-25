# TaskTracker

## Описание
Небольшая программа для хранения задач. Позволяет их создавать, удалять и изменять.
Будет удобно использовать при планировании своего распорядка.

## Используемые технологии
- C#
- .NET 8
- Git

## Требования
Для компиляции и запуска программы требуется .NET 8 SDK

## Структура проекта
TaskTracker_AuditProject
│   CHANGELOG.md
│   TaskTracker.sln
│   notes_local.txt
│   project-info.txt
│   README.md
│
├───temp
│       debug_notes.txt
│
├───src
│   └───TaskTracker
│       │   TaskTracker.csproj
│       │   Program.cs
│       │
│       │
│       ├───Models
│       │       TaskItem.cs
│       │
│       ├───Services
│       │       TaskService.cs
│       │
│       └───Utils
│               FileHelper.cs
│
├───config
│       appsettings.example.json
│
├───docs
│       USER_GUIDE.md
│       INSTALL_OLD.txt
│
├───test
│       test.txt
│
├───scripts
│       run.bat
│
├───data
│       tasks.json
│
└───notes
        notes.txt

## Запуск
1. Откройте папку `src/TaskTracker`.
2. Выполните `dotnet build`
2. Выполните `dotnet run`.

## Основные особенности
Данная программа позволяет составить список задач.
Их можно добавлять и удалять.
Также можно их изменять. Например, изменить имя или статус.

Версия: 1.3

Контакт для вопросов: отсутствует

## Планы развития

В дальнейшем рассматривается возможность разработки веб-версии TaskTracker.

Базовые требования к браузерной среде привелены в:
docs/WEB_REQUIREMENT.md