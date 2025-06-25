# Go WebSocket Чат

[![English](https://img.shields.io/badge/Language-English-blue)](README.md)
[![Русский](https://img.shields.io/badge/Язык-Русский-red)](README.ru.md)

![Go](https://img.shields.io/badge/Go-1.21+-00ADD8?logo=go)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16+-4169E1?logo=postgresql)
![WebSocket](https://img.shields.io/badge/WebSocket-RealTime-FF6600?logo=websocket)

## Используемые технологии

| Компонент       | Технология |
|-----------------|------------|
| Серверная часть | Go 1.24.4   |
| WebSocket       | Gorilla/websocket |
| База данных     | PostgreSQL 17 |
| Контейнеризация | Docker |
| Клиентская часть| HTML5 |

## Описание проекта

Это простое чат-приложение на **Go**, демонстрирующее:
- Обмен сообщениями через WebSocket
- Интеграцию с PostgreSQL
- Параллельную обработку сообщений
- Базовую клиент-серверную архитектуру

> **Примечание**: Это мой проект для **изучения** возможностей Go в разработке систем реального времени, разрабатывался для лучшего освоения Go

## Основные возможности

- Обмен сообщениями в реальном времени
- Поддержка множества клиентов
- Сохранение истории сообщений
- Простая аутентификация (по имени пользователя)
- Кроссплатформенные клиенты

## Быстрый старт

### Необходимые компоненты
- Go 1.24.4
- Docker
- PostgreSQL (или используйте Docker)

### Установка
```bash
# Клонируем репозиторий
git clone https://github.com/yourusername/go-websocket-chat.git
cd go-websocket-chat

# Запускаем PostgreSQL
docker-compose up -d

# Запускаем сервер
go run main.go