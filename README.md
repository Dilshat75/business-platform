# business-platform

Monorepo for the business platform application.

## Structure

```
business-platform/
├── backend/              # API and business logic
├── frontend/             # Web application
├── infrastructure/
│   ├── nginx/            # Reverse proxy configuration
│   ├── postgres/         # Database init scripts
│   └── docker/           # Docker-related configs
├── .env.example
├── docker-compose.yml
└── LICENSE
```

## Getting started

1. Copy `.env.example` to `.env` and adjust values.
2. Run `docker compose up --build`.
