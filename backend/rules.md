# Регламенты кодирования Backend

## Линтеры

[golangci-lint](https://github.com/golangci/golangci-lint)

## Рекомендации по написанию кода

[Uber Go Style Guide](https://github.com/uber-go/guide/blob/master/style.md)

## Структура проекта

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
