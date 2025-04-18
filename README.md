# README.md

# Laravel Docker Development Environment

## 🛠 Wymagania
- Docker
- Docker Compose
- Git

## 🚀 Instalacja

1. Klonowanie repozytorium:
```bash
git clone git@github.com:pioi43/laravel-docker-dev.git
cd laravel-docker-dev
```

2. Uruchomienie środowiska:
```bash
docker-compose up -d
```

3. Instalacja zależności:
```bash
docker-compose exec php composer install
```

4. Konfiguracja:
```bash
cp src/.env.example src/.env
docker-compose exec php php artisan key:generate
```

## 📦 Struktura projektu
```
laravel-docker-dev/
├── docker/
│   ├── nginx/
│   │   └── default.conf
│   └── php/
│       └── Dockerfile
├── src/
│   └── (pliki Laravel)
└── docker-compose.yml
```

## 🔧 Komendy
- Start: `docker-compose up -d`
- Stop: `docker-compose down`
- Logi: `docker-compose logs`
- Artisan: `docker-compose exec php php artisan`

## 🔗 Dostęp
- Frontend: http://localhost:8080
- MySQL:
  - Host: localhost
  - Port: 3306
  - Baza: laravel
  - User: laravel
  - Hasło: secret