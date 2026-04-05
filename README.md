# 👋 Привет, я Backend-разработчик

Меня зовут Михаил. Я активно занимаюсь Backend разработкой с использованием Go (Golang) и создаю масштабируемые REST API приложения.

# 🚀 **Currently working on**
## Context Service

![Go Version](https://img.shields.io/badge/go-1.25+-00ADD8?style=for-the-badge&logo=go)![Status](https://img.shields.io/badge/status-active--development-blue?style=for-the-badge)

---
**Context Service** — центральный микросервис-агрегатор, который выступает **единым входным шлюзом** для работы с LLM (через [Ollama](https://ollama.ai) API). 

Сервис обрабатывает HTTP-запросы, управляет пулом воркеров, применяет circuit breaker, rate limiting и собирает метрики в реальном времени.

> **Ключевая идея**: все внешние интеграции проходят через этот сервис, что позволяет централизованно управлять нагрузкой, отказоустойчивостью и observability.
---
**Telegram Module** — клиентский микросервис-шлюз, который обеспечивает взаимодействие пользователей с системой через интерфейс Telegram

Модуль аутентифицирует пользователей, применяет rate limiting на основе подписок, управляет контекстом диалогов и маршрутизирует запросы к Context Service для генерации ответов через LLM.

> **Ключевая идея**: выступает многопоточным адаптером между Telegram API и внутренними сервисами, обеспечивая отказоустойчивую обработку запросов с гибкой системой лимитирования на основе подписок и graceful shutdown для бесшовного обновления.
---
## Контакты для связи
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/mercurytears)[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:m.polyakov04@gmail.com)
## 📈 GitHub статистика
![Stats](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=HeavyMaverick&theme=monokai)
![Top Langs](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=HeavyMaverick&theme=monokai)
