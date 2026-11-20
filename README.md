# Ekoszt Pro — Systemy Niskoprądowe (Teletechnika)

Kompleksowa aplikacja webowa (SPA) do kosztorysowania instalacji teletechnicznych (nakłady **RMS**, narzuty `Kp`, `Kz`, `Zysk`, `VAT`), zarządzania zleceniami, harmonogramowania (Gantt, Kalendarz), kontroli kosztów realizacji oraz generowania umów i protokołów odbioru.

## Gotowe szablony teletechniczne w aplikacji:
- **SSP** — System Sygnalizacji Pożaru (okablowanie PH90, centrale, czujki, ROP, próby PSP)
- **CCTV IP** — Telewizja dozorowa IP z analityką AI, NVR, PoE
- **KD / SKD** — Kontrola dostępu (kontrolery 4-drzwiowe, czytniki MIFARE DESFire, zwory, integracja SSP)
- **LAN i Światłowody** — Szafy RACK 19", S/FTP kat. 6A, światłowody 12J, spawanie, pomiary Fluke/OTDR
- **SSWiN** — System Sygnalizacji Włamania i Napadu (Grade 3, PIR+MW, kontaktrony)
- **Oddymianie** — Oddymianie grawitacyjne klatek schodowych (centrala 24V, siłowniki, przyciski PO)
- **Wideodomofony IP** — Systemy wielolokalowe PoE, stacje bramowe RFID
- **System LPR / ANPR** — Rozpoznawanie tablic rejestracyjnych na wjeździe, pętla indukcyjna, szlaban

## Jak wdrożyć na GitHub Pages (w 2 minuty):
1. Utwórz nowe repozytorium na [GitHub](https://github.com/new) (np. `ekoszt-teletechnika`).
2. Wgraj pliki z tego archiwum (`index.html` oraz `README.md`) bezpośrednio do głównego katalogu repozytorium (**Add file -> Upload files**).
3. Wejdź w **Settings -> Pages**.
4. W sekcji **Build and deployment -> Source** wybierz **Deploy from a branch**, ustaw gałąź `main` oraz folder `/ (root)` i kliknij **Save**.
5. Po ok. 30 sekundach aplikacja będzie dostępna online pod adresem `https://<twoj-login>.github.io/ekoszt-teletechnika/`.

## Przechowywanie danych
Aplikacja działa w 100% po stronie przeglądarki (bez konieczności utrzymywania płatnego serwera) i automatycznie zapisuje dane w `localStorage`. W lewym dolnym rogu dostępna jest funkcja **Eksport JSON / Import**, pozwalająca przenosić bazę kosztorysów i zleceń między komputerami.
