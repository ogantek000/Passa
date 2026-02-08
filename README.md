Keepy – Keep Going

A minimalist web app for building habits and tracking streaks.
Runs 100% client-side (LocalStorage), optimized for mobile (iOS/Android), and installable as a PWA.

✨ Features
🧠 Habit (streak) management

Add, delete, and rename habits

Categories (sport, health, work, learning, hobby, other + custom)

Emoji personalization per habit

Current streak counter

📅 History calendar

Monthly view per habit

Day states:

✅ completed

❄️ freeze

❌ missed

Editing limited to 7 days back (anti-cheating safeguard)

Smooth month navigation without full reloads

🔥 Statistics

Total completed days

Longest streak

Daily average

Activity heatmap (last 28 days)

Per-category stats

🎨 Interface

Themes: dark / light / ocean

Animations (streak, bounce, ice effect)

Toasts with undo

Skeleton loading

Responsive, mobile-first layout

📱 Mobile & PWA

Full iOS (Safari) support

Drag & drop works on phones

No scroll “bounce” during drag

Add to Home Screen

Offline-ready (LocalStorage)

💬 Motivational quotes

Built-in quotes (PL / EN / ES)

One quote per day

Live language switching

Custom user quotes

🗂 Project structure
/
├── index.html        # Entire app (HTML + CSS + JS)
├── icon.png          # App icon (PWA / favicon)
├── manifest.json     # PWA manifest
└── README.md         # This file


⚠️ Note: the mascot file bro must include a proper extension, e.g. bro.jpg.

🚀 Getting started

Copy index.html

Place it in any folder

Open it in a browser (Chrome / Safari)

(Optional) deploy to static hosting (GitHub Pages, Netlify, Vercel)

No requirements:

backend

npm

frameworks

💾 Data & privacy

All data is stored in localStorage

No server communication

No cookies

Data stays on the user’s device

LocalStorage keys:

keepy – habits and history

theme – selected theme

quoteLang – quote language

quoteDate, quoteIndex – daily quote

🧩 Tech stack

Vanilla JavaScript (ES6)

HTML5

CSS3 (custom properties, animations)

LocalStorage

PWA (manifest + mobile meta tags)

No external dependencies.

⚠️ Known limitations (intentional)

No cross-device sync

No user accounts

No data export (can be added)

One app instance per device

🛠 Possible extensions (next steps)

Data export/import (JSON)

Sync (Firebase / Supabase)

Push notifications

Weekly/monthly charts

iOS / Android widgets

📄 License

Private / personal project.



Keepy – Keep Going

Minimalistyczna aplikacja webowa do budowania nawyków i śledzenia pass (streaków).
Działa w 100% po stronie przeglądarki (LocalStorage), jest zoptymalizowana pod mobile (iOS/Android) i może być zainstalowana jako PWA.

✨ Funkcje
🧠 Zarządzanie nawykami (passami)

Dodawanie, usuwanie i zmiana nazw pass

Kategorie (sport, zdrowie, praca, nauka, hobby, inne + własne)

Personalizacja emoji passy

Licznik aktualnej passy (streak)

📅 Kalendarz historii

Widok miesięczny per passa

Oznaczanie dni:

✅ wykonane

❄️ freeze

❌ opuszczone

Edycja tylko do 7 dni wstecz (zabezpieczenie przed oszukiwaniem)

Nawigacja miesiącami bez przeładowania całej strony

🔥 Statystyki

Łączna liczba wykonanych dni

Najdłuższa passa

Średnia dzienna

Heatmapa aktywności (ostatnie 28 dni)

Statystyki per kategoria

🎨 Interfejs

Motywy: dark / light / ocean

Animacje (streak, bounce, ice effect)

Toasty z możliwością cofnięcia usunięcia

Skeleton loading

Responsywny layout (mobile-first)

📱 Mobile & PWA

Pełne wsparcie iOS (Safari)

Drag & drop działa na telefonach

Brak „bounce” scrolla przy przeciąganiu

Możliwość dodania do ekranu głównego

Offline-ready (LocalStorage)

💬 Cytaty motywacyjne

Wbudowane cytaty (PL / EN / ES)

Jeden cytat dziennie

Zmiana języka w locie

Własne cytaty użytkownika

🗂 Struktura projektu
/
├── index.html        # Cała aplikacja (HTML + CSS + JS)
├── icon.png          # Ikona aplikacji (PWA / favicon)
├── manifest.json     # Manifest PWA
└── README.md         # Ten plik


⚠️ Uwaga: plik bro (maskotka) powinien mieć poprawne rozszerzenie, np. bro.jpg.

🚀 Uruchomienie

Skopiuj plik index.html

Umieść go w dowolnym folderze

Otwórz w przeglądarce (Chrome / Safari)

(Opcjonalnie) wrzuć na hosting statyczny (GitHub Pages, Netlify, Vercel)

Nie jest wymagany:

backend

npm

frameworki

💾 Dane i prywatność

Wszystkie dane są zapisywane w localStorage

Brak wysyłania danych do serwera

Brak cookies

Dane pozostają na urządzeniu użytkownika

Klucze LocalStorage:

keepy – passy i historia

theme – motyw

quoteLang – język cytatów

quoteDate, quoteIndex – cytat dnia

🧩 Technologie

Vanilla JavaScript (ES6)

HTML5

CSS3 (custom properties, animations)

LocalStorage

PWA (manifest + mobile meta tags)

Brak zależności zewnętrznych.

⚠️ Znane ograniczenia (świadome decyzje)

Brak synchronizacji między urządzeniami

Brak kont użytkowników

Brak eksportu danych (można dodać)

Jedna aplikacja = jedno urządzenie

🛠 Możliwe rozszerzenia (kolejne kroki)

Eksport / import danych (JSON)

Synchronizacja (Firebase / Supabase)

Notyfikacje push

Wykresy tygodniowe/miesięczne

Widget iOS / Android

📄 Licencja

Projekt prywatny / personalny.
