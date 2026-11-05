# Trasa kuriera

Aplikacja webowa (PWA) dla kuriera: odczyt adresów ze zdjęć etykiet, kolejność postojów z uwzględnieniem korków, odcinki piesze dla paczek bliżej niż 100 m, odhaczanie doręczeń i odbiorów.

- Otwórz stronę w Safari na iPhonie → Udostępnij → **Do ekranu początkowego**.
- Trasa i klucze są zapisane wyłącznie w telefonie (localStorage), nic nie trafia do tego repozytorium.
- Opcjonalne klucze (Ustawienia trasy w aplikacji):
  - **TomTom** – korki na żywo i dokładne adresy (darmowy klucz z developer.tomtom.com),
  - **Claude API** – lepszy odczyt etykiet (płatny, console.anthropic.com).
- Bez kluczy: tekst etykiety rozpoznaje telefon (Tesseract.js), adresy z OpenStreetMap (Nominatim), mapa OpenStreetMap.
