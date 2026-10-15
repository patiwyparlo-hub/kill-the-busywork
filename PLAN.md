# Kill the Busywork: plan

Aplikacja na telefon (web app / PWA) dla uczestników konferencji **Strategy World 2027** (luty 2027).
Uczestnik skanuje kod QR i gra w przeglądarce. Tylko po angielsku.

- Prototyp: https://kill-the-busywork.vercel.app/
- Kontekst produktu: https://software.strategy.com/ssis
- Design System: https://claude.ai/code/artifact/227b1180-5043-4c1a-a367-091e0dd80fd2

## Ustalenia (15.10.2026)

- Forma: web app, bez publikacji w sklepach ([decyzja 0001](docs/decisions/0001-web-app.md)).
- Ekran wyniku: dwa przyciski, „Play again” i „See all Strategy SI apps” (→ https://software.strategy.com/ssis).
- Bez licznika czasu. „A 60-second game” to tylko orientacyjny czas gry.
- Kody QR przygotowuje konferencja, nie ten projekt.

## Kolejność zadań (od najważniejszego)

| # | Issue | Zadanie | Status |
|---|---|---|---|
| 1 | [#12](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/12) | Forma aplikacji: web app | zdecydowane |
| 2 | [#1](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/1) | Link „See all Strategy SI apps” do software.strategy.com/ssis | zrobione (link działał od początku, otwiera się w nowej karcie) |
| 3 | [#2](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/2) | Dopracowanie na prawdziwych telefonach (iOS, Android) | do zrobienia |
| 4 | [#3](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/3) | Gotowość na słabe Wi-Fi i ruch na konferencji | do zrobienia |
| 5 | [#4](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/4) | Analityka gry | do zrobienia |
| 6 | [#5](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/5) | Treści pod uczestników World 2027 | do zrobienia |
| 7 | [#6](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/6) | Zgodność z SSIS Design System | do zrobienia |
| 8 | [#7](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/7) | Dostępność | do zrobienia |
| 9 | [#8](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/8) | PWA: manifest, ikony, splash screen | do zrobienia |
| 10 | [#9](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/9) | Porządek w repo i automatyczny deploy | do zrobienia |
| 11 | [#10](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/10) | Harmonogram do World 2027 | do zrobienia |
| – | [#11](https://github.com/patiwyparlo-hub/kill-the-busywork/issues/11) | Przycisk Share przy personie | opcjonalne |

## Terminy

- Koniec stycznia 2027: wersja gotowa do testów.
- Tydzień przed World 2027: zamrożenie zmian.
