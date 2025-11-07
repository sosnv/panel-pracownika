# Panel Pracownika - Harry Burger

Aplikacja panelu pracownika dla restauracji Harry Burger. System zarządzania zamówieniami, magazynem i kontrolą dnia pracy.

## 🚀 Funkcjonalności

- **Dashboard** - Przegląd dziennych statystyk i podsumowań
- **Zamówienia** - Zarządzanie aktywnymi zamówieniami i przegląd historii
- **Nowe zamówienie** - Tworzenie i konfiguracja zamówień (burgery, napoje, dodatki)
- **Magazyn** - Zarządzanie stanem magazynowym produktów
- **Kontrola dnia** - Zarządzanie sesją dnia pracy
- **Ustawienia dnia** - Konfiguracja parametrów dnia
- **Zużycie własne** - Rejestracja zużycia produktów przez pracowników

## 🛠️ Technologie

- **React** 18.3.1
- **Firebase** (Firestore, Hosting)
- **React Router** - nawigacja
- **Tailwind CSS** - stylowanie
- **Framer Motion** - animacje
- **React Hot Toast** - powiadomienia
- **jsPDF** - generowanie PDF

## 📋 Wymagania

- Node.js (wersja 14 lub wyższa)
- npm lub yarn
- Konto Firebase z projektem

## 🔧 Instalacja

1. Sklonuj repozytorium:
```bash
git clone https://github.com/sosnv/panel-pracownika.git
cd panel-pracownika
```

2. Zainstaluj zależności:
```bash
npm install
```

3. Skonfiguruj Firebase:
   - Utwórz plik `src/firebaseClientConfig.js` z konfiguracją Firebase
   - Skonfiguruj `firebase.json` i `.firebaserc` dla swojego projektu

## 🚀 Uruchomienie

### Tryb deweloperski:
```bash
npm start
```
Aplikacja będzie dostępna pod adresem [http://localhost:3000](http://localhost:3000)

### Build produkcyjny:
```bash
npm run build
```

### Wdrożenie na Firebase:
```bash
firebase deploy
```

## 📁 Struktura projektu

```
src/
├── components/          # Komponenty React
│   ├── Sidebar.js
│   ├── WarehouseSnapshotModal.js
│   └── WarehouseStockTile.js
├── contexts/           # Context API
│   ├── DaySessionContext.js
│   └── UserContext.js
├── data/              # Dane produktów
│   ├── burgers.js
│   ├── drinks.js
│   ├── extras.js
│   ├── ufo-burgers.js
│   └── warehouseProducts.js
├── pages/             # Strony aplikacji
│   ├── Dashboard.js
│   ├── Orders.js
│   ├── History.js
│   ├── NewOrder.js
│   ├── Warehouse.js
│   ├── DayControlDashboard.js
│   ├── DaySettings.js
│   └── EmployeeConsumption.js
├── firebase.js
├── firebaseClientConfig.js
└── App.js
```

## 🔐 Konfiguracja Firebase

Aplikacja wymaga skonfigurowania Firebase:
- Firestore Database
- Firebase Hosting
- Authentication (opcjonalnie)

## 📝 Skrypty dostępne

- `npm start` - Uruchamia aplikację w trybie deweloperskim
- `npm run build` - Buduje aplikację do produkcji
- `npm test` - Uruchamia testy
- `firebase deploy` - Wdraża aplikację na Firebase Hosting

## 🌐 Wdrożenie

Aplikacja jest wdrożona na Firebase Hosting:
**https://restauracjapracownik.web.app**

## 📄 Licencja

Projekt prywatny - Harry Burger

## 👤 Autor

sosnv
