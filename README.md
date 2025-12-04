# Go WebSocket Chat Application

[![English](https://img.shields.io/badge/Language-English-blue)](README.md)
[![Russian](https://img.shields.io/badge/Язык-Русский-red)](README.ru.md)

![Go](https://img.shields.io/badge/Go-1.21+-00ADD8?logo=go)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16+-4169E1?logo=postgresql)
![WebSocket](https://img.shields.io/badge/WebSocket-RealTime-FF6600?logo=websocket)

## Overview

This is my project to **learn** Go's capabilities in real-time systems development, designed to learn Go. A real-time chat application built with **Go** to demonstrate:
- WebSocket communication
- PostgreSQL integration
- Concurrent message handling
- Basic client-server architecture

## Features

- Real-time messaging
- Multiple client support
- Message history storage
- Simple authentication (username-based)
- Cross-platform clients

## Technologies

| Component       | Technology |
|-----------------|------------|
| Backend         | Go 1.24.4   |
| WebSocket       | Gorilla/websocket |
| Database        | PostgreSQL 17 |
| Containerization| Docker |
| Frontend        | HTML5 |

## Quick Start

### Prerequisites
- Go 1.24.4
- Docker
- PostgreSQL (or use Docker)

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/go-websocket-chat.git
cd go-websocket-chat

# Start PostgreSQL
docker-compose up -d

# Run server
go run main.go
