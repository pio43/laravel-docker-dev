# README.md

# Laravel Docker Development Environment

Ten projekt ma na celu stworzenie środowiska deweloperskiego dla aplikacji Laravel przy użyciu Dockera. Poniżej znajdują się instrukcje dotyczące uruchamiania i konfigurowania środowiska.

## Wymagania

- Docker
- Docker Compose

## Struktura projektu

```
laravel-docker-dev
├── docker
│   ├── nginx
│   │   └── default.conf
│   └── php
│       └── Dockerfile
├── src
│   └── .gitkeep
├── .env.example
├── .gitignore
├── docker-compose.yml
├── composer.json
└── README.md
```

## Uruchamianie projektu

1. Skopiuj plik `.env.example` do `.env` i dostosuj zmienne środowiskowe według potrzeb.
2. Uruchom polecenie:

   ```bash
   docker-compose up -d
   ```

3. Otwórz przeglądarkę i przejdź do `http://localhost`.

## Edytowanie plików

Pliki źródłowe aplikacji Laravel znajdują się w katalogu `src`. Możesz edytować je lokalnie, a zmiany będą automatycznie odzwierciedlane w kontenerze.

## Zakończenie

Aby zatrzymać kontenery, użyj polecenia:

```bash
docker-compose down
```

Dzięki temu środowisko deweloperskie Laravel będzie łatwe do uruchomienia i zarządzania przy użyciu Dockera.