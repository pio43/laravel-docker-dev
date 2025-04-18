# README.md

# 🔥 WEB/DEV Studio F33 - Laravel Developer Portfolio

## 🎯 Wizja Projektu
Cyfrowy manifest web/deva, który:
- Myśli kodem
- Oddycha deploymentem
- Śni w artisanach

## 🛠 Stack Technologiczny
- **Backend:** Laravel 11 (modularny)
- **Frontend:** 
  - Livewire 3.0
  - Alpine.js
  - Tailwind CSS
  - Framer Motion
- **Admin Panel:** Filament
- **Database:** MySQL 8.0
- **Development:** Docker + Laravel Sail

## 🎨 Główne Funkcjonalności

### 🧠 Myśli z Konsoli
```php
feat(life): dodano wreszcie sen po deployu
fix(brain): przestań myśleć o bugach o 3 w nocy
```

### 💻 Stack Rzeźnika
- Interaktywna mapa technologii
- Dokumentacja w stylu Matrix
- Easter eggi dla prawdziwych devów

### ⏱ Dev-Time Machine
- Historia projektów w stylu git
- Breakdown techniczny
- Lekcje z przeszłości

## 🚀 Instalacja

1. Klonowanie repozytorium:
```bash
git clone git@github.com:pio43/laravel-docker-dev.git
cd laravel-docker-dev
```

2. Uruchomienie środowiska:
```bash
docker-compose up -d
```

3. Instalacja zależności:
```bash
docker-compose exec php composer install
yarn install
```

4. Konfiguracja:
```bash
cp src/.env.example src/.env
docker-compose exec php php artisan key:generate
```

## 📦 Struktura Projektu
```
laravel-docker-dev/
├── docker/
│   ├── nginx/
│   │   └── default.conf
│   └── php/
│       └── Dockerfile
├── src/
│   ├── app/
│   │   ├── Http/
│   │   └── Console/
│   ├── resources/
│   │   ├── js/
│   │   └── views/
│   └── routes/
└── docker-compose.yml
```

## ⚡ Komendy Developerskie
- Start: `docker-compose up -d`
- Stop: `docker-compose down`
- Logi: `docker-compose logs`
- Artisan: `docker-compose exec php php artisan`
- Asset Build: `yarn dev`

## 🔗 Dostęp
- Frontend: http://localhost:8080
- Admin Panel: http://localhost:8080/admin
- MySQL:
  - Host: localhost
  - Port: 3306
  - Database: laravel
  - Username: laravel
  - Password: secret

## 🎨 Design Guidelines
- Dark mode jako domyślny
- JetBrains Mono dla nagłówków
- Animacje mikrointerakcji (60fps)
- Cyberpunkowe gradienty i efekty glitch
- Terminal-style UI elements

## 🧪 Easter Eggs
- Konami Code → Tryb terminala
- Dev Quiz
- Random PHP Artisan Jokes