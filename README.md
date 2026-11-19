# Giranak Backend

ASP.NET Core 11 Web API for Giranak, a city-based community and service discovery platform.

## Tech Stack

- ASP.NET Core 11, EF Core, SignalR
- SQL Server, Redis
- Docker, GitHub Actions

## Architecture

Modular Monolith with Clean Architecture. Each module has its own Domain, Application, Infrastructure, and API layers.

## Getting Started

Prerequisites: .NET 11 SDK, Docker Desktop, Git.

1. Clone the repo and switch to `develop`.
2. Copy `.env.example` to `.env` and set values.
3. Run: `docker compose up --build`
4. API: http://localhost:8080

## Project Structure

(to be updated once the solution skeleton exists)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Related Repos

giranak-web, giranak-mobile, giranak-ai, giranak-docs
