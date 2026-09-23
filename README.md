# Дмитрий Папиш

### Python Backend · FastAPI · PostgreSQL · AI Automation

Разрабатываю backend-системы, API-интеграции и автоматизацию реальных рабочих процессов.

Основной стек:

`Python` `FastAPI` `PostgreSQL` `SQL` `Docker` `Linux` `systemd`  
`Git` `GitHub Actions` `REST API` `OAuth 2.0` `SQLite` `aiogram`

## Проекты

### ArtToSlipAway — Web Platform

Production web-продукт и CRM на FastAPI / PostgreSQL.

В проекте реализованы:

- FastAPI backend;
- PostgreSQL;
- CRM и административная часть;
- клиентский кабинет;
- защищённая работа с файлами;
- REST API;
- интеграции с Telegram и Google API;
- Docker / CI;
- тестирование;
- Linux / Nginx / systemd / HTTPS;
- резервное копирование и эксплуатация production-сервисов.

**Public case study:**  
https://github.com/ArtToSlipAway/arttoslipaway-web-case-study

**Production:**  
https://arttoslipaway.art

### Clippy Assistant

Персональный AI-ассистент на Python / aiogram с интеграциями OpenAI API,
Google Calendar и Google Tasks.

Реализованы:

- Telegram-интерфейс;
- OpenAI API и tool calling;
- Google Calendar / Tasks;
- OAuth и service-account интеграции;
- SQLite memory;
- voice input;
- HTTP gateway;
- автоматизация задач и проектов.

Production-репозиторий приватный.

**Public sanitized demo:**  
https://github.com/ArtToSlipAway/clippy-ai-assistant-demo

### Internal Control Center

Внутренняя web-панель для доступа к служебным инструментам и production-сервисам.

Архитектура доступа:

- приложение не публикуется напрямую в интернет;
- backend слушает только локальный/private интерфейс;
- доступ с Mac, iPhone и iPad идёт через приватный Tailscale tailnet;
- публичный HTTP/HTTPS ingress для панели отключён;
- production endpoint, конфигурация и исходный код панели остаются приватными.

Этот кейс показывает практическую настройку private-access инфраструктуры
для внутренних административных инструментов без публичной экспозиции сервиса.

## Source-code policy

Рабочие production-репозитории, инфраструктурные конфигурации,
credentials и пользовательские данные являются приватными.

Публичные GitHub-репозитории содержат только специально подготовленные
portfolio / sanitized материалы.

## Контакты

- Website: https://arttoslipaway.art
- GitHub: https://github.com/ArtToSlipAway
