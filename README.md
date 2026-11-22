# Burgundské války v dobových pramenech

Dobové kroniky, deníky, sněmovní záznamy a depeše k burgundským válkám (1468–1477) v českém překladu vedle originálu, s rejstříkem osobností, událostí, míst, zbraní a písní. Projekt vzniká pro české reenactory burgundských válek.

**Web:** `index.html`, na GitHub Pages zobrazený jako stránka projektu.

## Prameny a překlady
| Kronika | Rukopis | Edice, ze které se překládá | Překlad |
|---|---|---|---|
| Diebold Schilling st., *Grosse Burgunderchronik* („Zürcher Schilling“) | Zürich, Zentralbibliothek, Ms A 5 | G. Tobler, Bern 1897–1901 | `preklady/Schilling_Zurich/kap/` (429 kapitol) |
| Diebold Schilling st., *Amtliche Berner Chronik*, sv. 3 | Bern, Burgerbibliothek, Mss.h.h.I.3 (iluminace i ze sv. 1–2) | vlastní přepis rukopisu ze skenů e-codices | `preklady/Schilling_Bern3/kap/` (předmluva a 421 kapitol) |
| Gerold Edlibach, *Zürcher- und Schweizerchronik* | Zürich, Zentralbibliothek, Ms A 75 | J. M. Usteri, Zürich 1847 | `preklady/Edlibach_Zurich/kap/` (53 kapitol, úsek 1468–1477) |
| Peter von Molsheim, *Freiburger Chronik der Burgunderkriege* | Fribourg, BCU, Ms. L 2030 | A. Büchi, Bern 1914 | `preklady/Molsheim_Fribourg/kap/` (159 kapitol) |
| Diebold Schilling ml., *Eidgenössische Chronik* („Luzerner Schilling“) | Luzern, Korporation Luzern, S 23 fol. | vlastní přepis rukopisu ze skenů e-codices (s. 140–281) | `preklady/Luzerner_Schilling/kap/` (95 kapitol, úsek 1468–1480) |
| Johannes Knebel, *Diarium* (latinsky) | Basel, Universitätsbibliothek | W. Vischer a H. Boos, *Basler Chroniken* II–III, 1880–1887 | `preklady/Knebel_Diarium/kap/` (227 kapitol, 1473–1479) a `basne/` (7 básní) |
| Conrad Pfettisheim, *Reimchronik über die Burgunderkriege* (veršovaná) | prvotisk, Štrasburk asi 1477 | G. Tobler, Bern 1917 | `preklady/Pfettisheim_Reimchronik/kap/` (19 oddílů) |
| *Eidgenössische Abschiede* (sněmovní výnosy Spříseženců) | úřední záznamy sněmů | A. Ph. Segesser, *Amtliche Sammlung der ältern Eidgenössischen Abschiede* II (1863) a III/1 (1858) | `preklady/Abschiede/kap/` (506 stran, přeloženo 252: 1474 – červenec 1478) |
| Philippe de Commynes, *Mémoires* (francouzsky) | | É. Dupont, Paris 1840–1847 | `preklady/Commynes_Memoires/kap/` (50 kapitol, burgundský úsek) |
| Olivier de La Marche, *Mémoires* (francouzsky) | | H. Beaune a J. d'Arbaumont, Paris 1883–1888 | `preklady/LaMarche_Memoires/kap/` (11 kapitol) |
| Jean Molinet, *Chroniques* (francouzsky) | | J.-A. Buchon, Paris 1827 | `preklady/Molinet_Chroniques/kap/` (39 kapitol) |
| Depeše milánských vyslanců (Panigarola, Appiano, Petrasanta…; italsky) | Milán, Archivio di Stato | F. de Gingins-La Sarra, Paris–Genève 1858 | `preklady/Gingins_Depese_milanske/kap/` (287 depeší 1473–1477, čísla podle edice) |

Překlady vytvořila AI (Claude) z tištěných edic, Bern 3 a Luzerner Schilling z vlastního přepisu rukopisu. Prošly první korekturou, **proti rukopisům zatím ověřené nejsou**. Nejistá místa jsou označena `[?]`. Závazné odborné termíny jsou v `TERMINY.md`.

Iluminace se načítají přímo z digitálních knihoven [e-codices](https://www.e-codices.ch) a [e-manuscripta](https://www.e-manuscripta.ch).

## Jak pomoci
Termíny a opravy překladu se sbírají ve sdílené tabulce správce projektu. Pokud chcete pomoci s korekturou, ozvěte se správci.

## Formát souborů překladu
Každá kapitola je JSON soubor: `odstavce` = seznam dvojic `text` (originál z edice) a `preklad` (čeština), `poznamky` = poznámky překladatele.
