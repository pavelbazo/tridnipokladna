# Složka pro videonávody

Sem nahrávej hotová videa (formát .mp4 doporučený, funguje ve všech prohlížečích).

## Jak přidat video na web

1. Nahraj sem soubor, např. `01-zalozeni-tridy.mp4`
2. Otevři `index.html`, najdi sekci s komentářem "NÁVOD PRO PAVLA" (je to v sekci Videonávody)
3. U příslušné karty smaž blok `<div class="video-placeholder">...</div>`
4. Odkomentuj tag `<video>` pod ním (odeber komentářové značky kolem něj)
5. Uprav `src="videos/nazev-souboru.mp4"` na skutečný název tvého souboru

## Doporučení pro videa
- Ideální poměr stran: 16:9
- Délka: klidně 1–3 minuty, krátká a konkrétní videa fungují nejlíp
- Velikost souboru: pro rychlé načítání ideálně do cca 20–30 MB na video
  (pokud bude video větší, zvaž kompresi nebo přesun na YouTube a vložení odkazu místo přímého souboru)

## Volitelně: náhledový obrázek (poster)
Pokud chceš, aby se před přehráním videa zobrazoval hezký náhled místo černé
plochy, přidej do assets/ obrázek (např. `thumbnail-1.jpg`) a doplň ho do
tagu `<video poster="assets/thumbnail-1.jpg">`.
