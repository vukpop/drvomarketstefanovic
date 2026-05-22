# Drvo Market Stefanović

Ovo je statički HTML/CSS/JS sajt za Drvo Market Stefanović iz Obrenovca. Sajt predstavlja bogatu ponudu laminata, lajsni, brodskog poda i prateće opreme vrhunskih proizvođača.

## Struktura sajta
- `index.html` - Početna stranica
- `ponuda.html` - Pregled svih kategorija proizvoda
- `laminati.html`, `egger.html`, `agt.html`, `kastamonu.html`, `kronotex.html` - Specifične stranice za različite brendove laminata
- `lajsne.html`, `lamperija.html`, `garnisne.html` - Prateći asortiman i dodatna oprema
- `o-nama.html` - Informacije o firmi, tradiciji i iskustvu
- `kontakt.html` - Kontakt podaci sa integrisanom mapom lokacije

## Tehnologije
- HTML5
- CSS3 (Vanilla - custom dizajn i responsivnost)
- Vanilla JavaScript (za interaktivne elemente poput menija i galerija)
- Font Awesome ikone

## Optimizacija
Sajt je optimizovan za brzo učitavanje:
- Implementiran je `loading="lazy"` za slike ispod folda (below-the-fold) kako bi se ubrzalo početno učitavanje
- Prve (Hero) slike imaju `fetchpriority="high"` kako bi se osigurao najbrži mogući LCP (Largest Contentful Paint)
