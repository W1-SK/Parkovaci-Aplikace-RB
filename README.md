# Parkovací aplikace

Tento repozitář obsahuje návrh a funkční prototyp (MVP) interní aplikace pro správu parkovacích míst. Projekt vzniká v rámci praxe a pokrývá fázi projektového řízení i samotný vývoj.

## Cíle projektu
- Nahradit manuální sledování obsazenosti parkoviště.
- Umožnit zaměstnancům ověřit si kapacitu a rezervovat místo předem.
- Poskytnout přehled o stavu parkovacích míst v reálném čase.

## Struktura repozitáře
- `/docs` - Projektová dokumentace k jednotlivým fázím (SMART cíle, Business case, WBS, analýza rizik).
- `/frontend` - Klientská část napsaná v Reactu (Vite + Tailwind CSS).
- `/backend` - API vrstva v .NET a databáze SQLite pro správu dat.

## Lokální spuštění

Pro spuštění je nutné mít nainstalované prostředí Node.js a .NET SDK.

### 1. Spuštění API (Backend)
V terminálu přejděte do složky backendu a spusťte:
```bash
cd backend
dotnet restore
dotnet run
```
API standardně naslouchá na http://localhost:5000 nebo https://localhost:5001.

### 2. Spuštění Webové aplikace (Frontend)
V novém okně terminálu přejděte do složky frontendu:
```bash
cd frontend
npm install
npm run dev
```
Aplikace bude po spuštění dostupná na adrese http://localhost:5173.