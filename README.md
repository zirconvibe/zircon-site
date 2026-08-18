# ZircOnVibe – Fogtechnikai portfólió

A ZircOnVibe egy egyszerű, egylapos fogtechnikai portfólióweboldal.

Az oldal célja a fogtechnikai tanulmányok és gyakorlati munkák bemutatása képeken, rövid leírásokon és dokumentációkon keresztül.

A projekt folyamatos fejlesztés alatt áll. A tartalom idővel változik, cserélődik és bővül az új munkák elkészülésével.


## Projekt célja

A weboldal egy folyamatosan épülő szakmai portfólió és dokumentációs felület.

Főbb céljai:

- fogtechnikai munkák képes bemutatása
- munkafolyamatok és részfolyamatok dokumentálása
- elkészült fogpótlások és modellek bemutatása
- digitális és manuális munkák bemutatása
- tanulmányi és elméleti munkák dokumentálása
- új munkák és tartalmi kategóriák későbbi hozzáadása

A weboldal nem klasszikus reklám- vagy szolgáltatói oldalnak készült. A cél egy egyszerű, áttekinthető szakmai portfólió kialakítása, amely a későbbiekben is folyamatosan bővíthető.


## Technikai felépítés

A jelenlegi verzió egy statikus weboldal, amelynek alapját HTML5, CSS3, Tailwind CSS és JavaScript adja.

Használt technológiák és szolgáltatások:

- HTML5 – az oldal szerkezete és tartalma
- CSS3 – egyedi megjelenés és reszponzív szabályok
- Tailwind CSS – elrendezés és utility alapú stílusok
- JavaScript – interaktív elemek működése
- Google Fonts – webes betűtípus
- Git – verziókövetés
- GitHub – repository és projektkezelés
- GitHub Pages – weboldal publikálása

Backend és adatbázis jelenleg nincs, mivel a projekt jelenlegi formájában nincs szükség szerveroldali adatkezelésre.


## HTML és oldalstruktúra

Az oldal fő szerkezete az index.html fájlban található.

A dokumentum többek között az alábbi részeket tartalmazza:

- navigáció
- nyitó / hero szekció
- munkafolyamatok
- kész munkák
- elméleti munkák
- képes dokumentációk
- képnézegető elemek
- további tartalmi blokkok

A jelenlegi projektméretnél az egyetlen HTML fájl használata egyszerűbbé teszi a szerkesztést és a tartalom bővítését.

Nagyobb projektméret esetén a HTML, CSS és JavaScript később külön fájlokra, illetve strukturáltabb komponensekre bontható.


## CSS és Tailwind CSS

A megjelenítéshez Tailwind CSS és saját CSS szabályok is használatban vannak.

A Tailwind elsősorban az alábbiakhoz használható:

- elrendezés
- méretezés
- térközök
- tipográfiai beállítások
- reszponzív megjelenítés
- alapvető vizuális elemek

Az egyedi CSS kezeli többek között:

- a háttér megjelenését
- a glass / áttetsző felületeket
- blur effekteket
- egyedi animációkat
- görgetési viselkedést
- képnézegető elemeket
- egyes desktop és mobil eltéréseket

A Tailwind jelenleg CDN-en keresztül működik. Ez a projekt jelenlegi méreténél egyszerű megoldás, mivel nincs szükség külön build folyamatra.

Később, ha a projekt jelentősen nagyobb lesz, áttérhet build alapú Tailwind használatra.


## Reszponzív megjelenítés

Az oldalt desktop és mobil kijelzőkre is kialakítottam.

A CSS media query-k segítségével az oldal bizonyos elemei a képernyő méretéhez igazodnak.

Elsősorban az alábbi elemek változhatnak:

- címsorok mérete
- képek mérete
- margók és térközök
- tartalmi blokkok elrendezése
- navigáció
- egyes vizuális elemek pozíciója

A desktop és mobil megjelenítést külön is ellenőriztem, mert ugyanaz az elrendezés nem minden kijelzőméreten működik megfelelően.


## Képek és média

A portfólió legfontosabb tartalmi elemei a saját készítésű képek és dokumentációk.

A képek külön assets könyvtárban találhatók, így új munkák hozzáadása egyszerűen megoldható.

A bemutatott tartalmak között szerepelhetnek:

- elkészült fogpótlások
- modellek
- munkafolyamatok
- részfolyamatok
- digitális tervezési munkák
- laboratóriumi munkák
- tanulmányi feladatok
- egyéb dokumentációk

A képek és médiafájlok optimalizálása külön fejlesztési terület. Ennek célja:

- gyorsabb oldalbetöltés
- kisebb adatforgalom
- jobb mobilos használhatóság
- kisebb tárhelyigény

Később többek között WebP vagy AVIF formátum, lazy loading és optimalizált képbetöltési stratégia is alkalmazható.


## Képnézegető

A nagyobb képek megtekintéséhez egyszerű képnézegető funkció készült.

Ennek célja:

- a képek részletesebb megtekintése
- az oldal elhagyása nélküli nagyítás
- a képes dokumentáció könnyebb használata

A funkció működésében CSS és JavaScript is részt vesz.


## PDF dokumentáció

A részletesebb dokumentációk külön könyvtárban találhatók.

A PDF-ek többek között az alábbi tartalmakat tartalmazhatják:

- elméleti munkák
- tanulmányi dokumentációk
- részletes munkafolyamatok
- egyéb kapcsolódó anyagok

A rövid bemutatás az oldalon jelenhet meg, míg a részletes dokumentáció külön fájlként maradhat elérhető.


## SEO és keresőmotorok

Az oldalhoz alapvető keresőoptimalizálási beállítások is készültek.

Ezek célja, hogy a keresőmotorok megfelelően tudják értelmezni és feltérképezni az oldalt.

A jelenlegi beállítások:

- megfelelő oldal title
- meta description
- canonical URL
- robots.txt
- sitemap.xml
- magyar nyelvű HTML dokumentum

A canonical URL azért fontos, hogy egyértelmű legyen a keresőmotorok számára, melyik URL az oldal elsődleges változata.

A robots.txt a keresőrobotok számára ad alapvető feltérképezési szabályokat, és megadja a sitemap helyét.

A sitemap.xml az oldal fontos URL-jeit tartalmazza, ezzel segítve azok felfedezését és feltérképezését.

A robots.txt és sitemap.xml nem távolítja el automatikusan a korábban indexelt Google-találatokat. Ezek az oldal keresőmotorokkal való kommunikációját és feltérképezését segítő technikai elemek.


## Git és verziókezelés

A projekt GitHub repositoryban található és Git segítségével verziókövetetten készül.

A commitok segítségével követhetők a fejlesztés fontosabb lépései, például:

- HTML módosítások
- CSS javítások
- új tartalmak
- új képek
- SEO módosítások
- reszponzív javítások
- technikai hibajavítások

A verziókövetés lehetőséget ad a korábbi állapotok visszakeresésére és szükség esetén visszaállítására.


## GitHub Pages és domain

A weboldal GitHub Pages segítségével kerül publikálásra.

A saját domain:

https://zirconvibe.com/

A domain a GitHub Pages projekthez kapcsolódik.

Ez a megoldás jelenleg elegendő egy statikus portfólióweboldal kiszolgálására, külön szerver vagy adatbázis fenntartása nélkül.


## Repository felépítése

A projekt jelenlegi főbb elemei:

- assets/ – képek és egyéb vizuális anyagok
- work_pdfs/ – PDF dokumentációk
- index.html – a weboldal fő fájlja
- CNAME – saját domain kapcsolata
- robots.txt – keresőrobotok számára szükséges beállítások
- sitemap.xml – keresőmotorok számára készített oldaltérkép
- README.md – projekt dokumentáció


## Projekt állapota és további fejlesztés

A weboldal jelenleg működő, de folyamatosan fejlesztett projekt.

A tartalom nem végleges.

Az új munkák elkészülésével:

- új képek kerülnek fel
- korábbi képek cserélhetők
- új munkafolyamatok kerülnek dokumentálásra
- új PDF-ek kerülhetnek be
- új kategóriák alakíthatók ki
- a meglévő technikai megoldások továbbfejleszthetők

Lehetséges későbbi technikai fejlesztések:

- képek további optimalizálása
- WebP / AVIF formátum
- lazy loading
- gyorsabb képbetöltés
- nagyobb médiafájlok optimalizálása
- képnézegető továbbfejlesztése
- accessibility javítások
- CSS és JavaScript külön fájlokra szervezése
- strukturáltabb projektfelépítés
- build rendszer bevezetése nagyobb projektméretnél


## Tartalom és felhasználási feltételek

A weboldalon és a repositoryban található képek, fotók, dokumentumok és egyéb vizuális anyagok saját készítésű tartalmak.

Ezek a bemutatott fogtechnikai munkákat, munkafolyamatokat és tanulmányi anyagokat dokumentálják.

A tartalmak felhasználása előzetes engedélyhez kötött.

Engedély nélkül nem használhatók fel:

- más weboldalon
- közösségi médiában
- kiadványban
- reklámanyagban
- kereskedelmi célra
- módosított vagy újraközölt formában

A GitHub repository nyilvános elérhetősége nem jelent automatikus felhasználási engedélyt a képekre és dokumentumokra.

## Összegzés

A ZircOnVibe egy saját fejlesztésű, folyamatosan bővülő fogtechnikai portfólió.

A projekt jelenlegi célja egy egyszerű, átlátható és könnyen karbantartható weboldal kialakítása, amely később további tartalmakkal és technikai megoldásokkal is bővíthető.

Az oldal tartalma és technikai felépítése a projekt fejlődésével együtt változik.
