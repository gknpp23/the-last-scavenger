# The Last Scavenger

**Intelligent Deal Monitoring and Price Intelligence Platform**

The Last Scavenger is a personal price intelligence project designed to monitor promotional channels, identify relevant deals, track products and detect unusual pricing opportunities.

The platform combines Telegram data collection, workflow automation, persistent storage and local AI processing.

## Core Features

- Telegram channel monitoring.
- Automated deal extraction.
- Product wishlist and target price tracking.
- Coupon identification.
- Price history.
- Suspicious price anomaly detection.
- Automated Telegram notifications.
- AI-assisted deal classification.

## Technology Stack

| Component | Technology |
|---|---|
| Backend | Python |
| Telegram Integration | Telethon / Telegram Bot API |
| Workflow Automation | n8n |
| Database | PostgreSQL |
| AI Inference | Ollama |
| Database Management | Beekeeper Studio |
| Infrastructure | Docker |
| Version Control | Git / GitHub |

## Architecture

The initial architecture consists of:

1. Telegram channels as data sources.
2. A Python collector using Telethon.
3. n8n for workflow orchestration.
4. PostgreSQL for persistent storage.
5. Ollama for optional AI-assisted classification.
6. A Telegram bot for user interaction and notifications.

## Project Status

**Development: Environment Setup**

The infrastructure and development environment are being prepared. Core application features are planned for subsequent milestones.

## Goals

- Build a functional deal monitoring system.
- Explore event-driven automation.
- Apply local LLMs to structured information extraction.
- Develop a reproducible, containerized architecture.
- Document engineering decisions and implementation.

---

*The Last Scavenger is an independent software project developed for learning, experimentation and practical automation.*
