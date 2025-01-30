# Remark

Spletno stran si lahko ogledate tukaj:  
[Klikni za ogled](https://anzekriznar.github.io/Remark/)
# Preučevanje Hamiltonovih poti v tabeli

Ta projekt vsebuje interaktivno predstavitev o Hamiltonovih poteh v mreži, narejeno z **Remark.js**, ki vključuje prilagojeno oblikovanje in funkcionalnosti.

## Uporabljene funkcije in elementi

### 1. HTML
- **`<!DOCTYPE html>`** – Določa, da gre za HTML5 dokument.
- **`<meta charset="UTF-8">`** – Nastavi kodiranje znakov na UTF-8.
- **`<meta name="viewport">`** – Omogoča odzivno oblikovanje na različnih napravah.
- **`<link rel="stylesheet" href="index.css">`** – Povezava na zunanjo CSS datoteko.
- **`<script>`** – Vključuje JavaScript kodo v dokument.
- **`<button>`** – Ustvari interaktiven gumb.
- **`<table>`** – Strukturna postavitev gumba in rezultata.
- **`<textarea id="source">`** – Vsebuje remark.js kodo za predstavitev.
- **`<img src="primer1.png">`** – Prikaz slik primerov Hamiltonove poti.

### 2. CSS
- **`@import url(...)`** – Uporaba Google Fonts (`Yanone Kaffeesatz`, `Droid Serif`, `Ubuntu Mono`).
- **`body { font-family: 'Droid Serif'; }`** – Nastavi osnovno pisavo dokumenta.
- **`.remark-slide-container`** – Nastavi ozadje diapozitivov (`background-image`).
- **`button { background-color, padding, border-radius }`** – Oblikovanje gumbov.
- **`@keyframes fadeIn`** – Animacija za prehod diapozitivov (`opacity`, `transform`).

### 3. JavaScript
- **Funkcija `klik()`** – Spreminja vsebino `<td>` ob kliku na gumb:
  ```js
  function klik() {
    document.getElementById("klik-na-gumb").innerHTML = "<p>Dovolj za danes</p>";
  }
