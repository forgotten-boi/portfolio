\# Clean Architecture Based Porfolio CMS projects



\*\*Purpose:\*\*.NET 9 backend using Clean Architecture, CQRS (commands/queries), event-driven publishing (Kafka), EF Core/Postgres read models, and DevOps-ready 



\## Planned Repo Layout

```

/ (repo root)

├─ src/

│  ├─ Portfolio.sln

│  ├─ Portfolio.Api/                # Minimal API entrypoint

│  ├─ Portfolio.Application/        # Commands, Queries, DTOs, Handlers

│  ├─ Portfolio.Domain/             # Entities, value objects, domain events

│  └─ Portfolio.Infrastructure/     # EF, Kafka, external integrations

├─ tests/

│  └─ Portfolio.Application.Tests/  # xUnit tests (unit + integration)

├─ deploy/

│  ├─ docker-compose.yml

│  └─ helm/                         # Helm chart skeleton

├─ azure-pipelines.yml

├─ README.md

└─ .dockerignore

```



