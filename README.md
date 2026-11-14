# Encyklopedie burgundských válek

Osobnosti, bitvy, události, místa a písně burgundských válek (1468–1477) podle dobových kronik, s českým překladem. Projekt vzniká pro české reenactory burgundských válek.

**Web:** `index.html`, na GitHub Pages zobrazený jako stránka projektu.

## Prameny a překlady
| Kronika | Rukopis | Edice, ze které se překládá | Překlad |
|---|---|---|---|
| Diebold Schilling st., *Grosse Burgunderchronik* („Zürcher Schilling“) | Zürich, Zentralbibliothek, Ms A 5 | G. Tobler, Bern 1897–1901 | `preklady/Schilling_Zurich/kap/` (429 kapitol) |
| Diebold Schilling st., *Amtliche Berner Chronik*, sv. 3 | Bern, Burgerbibliothek, Mss.h.h.I.3 (iluminace i ze sv. 1–2) | vlastní přepis rukopisu ze skenů e-codices | `preklady/Schilling_Bern3/kap/` (předmluva a 421 kapitol) |
| Gerold Edlibach, *Zürcher- und Schweizerchronik* | Zürich, Zentralbibliothek, Ms A 75 | J. M. Usteri, Zürich 1847 | `preklady/Edlibach_Zurich/kap/` (53 kapitol, úsek 1468–1477) |
| Peter von Molsheim, *Freiburger Chronik der Burgunderkriege* | Fribourg, BCU, Ms. L 2030 | A. Büchi, Bern 1914 | `preklady/Molsheim_Fribourg/kap/` (159 kapitol) |
| Johannes Knebel, *Diarium* (latinsky) | Basel, Universitätsbibliothek | W. Vischer a H. Boos, *Basler Chroniken* II–III, 1880–1887 | zatím jen jako pramen, bez překladu |

Překlady vytvořila AI (Claude) z tištěných edic, Bern 3 z vlastního přepisu rukopisu. Prošly první korekturou, **proti rukopisům zatím ověřené nejsou**. Nejistá místa jsou označena `[?]`. Závazné odborné termíny jsou v `TERMINY.md`.

Iluminace se načítají přímo z digitálních knihoven [e-codices](https://www.e-codices.ch) a [e-manuscripta](https://www.e-manuscripta.ch).

## Jak pomoci
Termíny a opravy překladu se sbírají ve sdílené tabulce správce projektu. Pokud chcete pomoci s korekturou, ozvěte se správci.

## Formát souborů překladu
Každá kapitola je JSON soubor: `odstavce` = seznam dvojic `text` (originál z edice) a `preklad` (čeština), `poznamky` = poznámky překladatele.
