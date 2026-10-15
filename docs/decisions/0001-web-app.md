# 0001: Forma aplikacji: web app

- **Status:** przyjęta
- **Data:** 2026-10-15
- **Issue:** #12

## Kontekst

Kill the Busywork to gra na telefon dla uczestników konferencji Strategy World 2027 (luty 2027).
Uczestnicy trafiają do gry przez kody QR rozmieszczone na konferencji. Kody przygotowuje konferencja.

Rozważane opcje:
1. **Web app** w przeglądarce telefonu, hostowana na Vercel.
2. **Natywna aplikacja** (Expo) w App Store i Google Play.

## Decyzja

Gra jest **web appem**.

## Uzasadnienie

- Kod QR otwiera link w przeglądarce, więc gracz zaczyna grać od razu, bez pobierania aplikacji ze sklepu.
- Nie ma przeglądu w App Store i Google Play, więc zmiany można wdrażać do ostatniej chwili przed konferencją.
- Prototyp (https://kill-the-busywork.vercel.app/) już działa jako web app, więc nie trzeba go przepisywać.

## Konsekwencje

- Zadania dotyczą przeglądarek mobilnych: iOS Safari i Android Chrome (#2).
- Trzeba zadbać o działanie przy słabym Wi-Fi na konferencji (#3).
- Funkcje PWA (ikona na ekranie głównym, splash screen) są dodatkiem, a nie warunkiem działania gry (#8).
