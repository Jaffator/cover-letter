# Motivační dopis

Motivační dopis jako jedna HTML stránka pro GitHub Pages.

Live: https://jaffator.github.io/cover-letter/

- **Upravit text** – zapne úpravy přímo ve stránce (oslovení, firma, datum, odstavce…). Do `localStorage` daného prohlížeče se ukládají jen pole, která jste změnili; ostatní vždy sledují text z repozitáře. Pole vymazané do prázdna se po dokončení úprav vrátí na výchozí text.
- **Obnovit původní** – zahodí úpravy z prohlížeče.
- **Export do PDF** – poskládá dopis v aktuálním znění do PDF přímo v prohlížeči (jsPDF, vektorový text, písma z `assets/fonts`) a stáhne `Motivacni_dopis_Jaroslav_Lufinka.pdf`. Rozvržení PDF je v `index.html` ve funkci `render`, nezávisle na CSS.

Písma jsou statické TTF z Google Fonts (podmnožina latin + latin-ext). Trvalou změnu textu udělejte v `index.html` (každé editovatelné místo má atribut `data-field`).

## Náhled

```bash
python -m http.server 5188
```
