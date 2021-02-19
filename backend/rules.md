# Регламенты кодирования

## Линтеры

[golangci-lint](https://github.com/golangci/golangci-lint)

## Правила именования переменных


## Правила кодирования

**Структура проекта**

В соответствии со [стандартным разбинием для проектов на Go](https://github.com/golang-standards/project-layout)

```
.
├── internal
│   ├── model         // основные структуры
│   ├── handler       // обработчики запросов
│   │   └── vX        // версия X
│   ├── service       // бизнес-логика
│   └── repository    // взаимодействие с БД
│       └── postgres  // реализация под СУБД PostgreSQL
├── cmd               // точка входа в приложение
├── schema            // SQL файлы с миграциями
└── configs           // файлы конфигурации
```
