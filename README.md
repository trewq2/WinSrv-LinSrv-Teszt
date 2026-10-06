# Windows szerver, Linux szerver összefoglalás

GitHub Pages-re kész statikus tudásmérő oldal 13. évfolyam számára.

## Funkciók
- 30 Rocky Linux kérdés + 30 Windows Server kérdés
- kevert kérdés- és válaszsorrend
- egyszerre egy kérdés, visszalépés nélkül
- 1 pont helyes válaszért, hibás válasz 0 pont
- 30 perces alapértelmezett időkorlát
- név és osztály rögzítése
- lap-/ablakváltás számlálása
- százalékos és témakörönkénti kiértékelés
- részletes PDF: saját válasz + helyes válasz + 0/1 pont

## GitHub Pages
1. Hozz létre egy repositoryt, pl. `windows-linux-szerver-osszefoglalas`.
2. Töltsd fel a négy fájlt a repository gyökerébe.
3. **Settings → Pages → Deploy from a branch**.
4. Branch: `main`, mappa: `/(root)`.

## Idő módosítása
Az `app.js` elején a `minutes:30` érték írható át.

## Csalás elleni korlát
A megoldás GitHub Pages miatt teljesen kliensoldali. A keverés, a visszalépés tiltása, a teljes képernyő, a fókuszvesztés-számlálás és a hash-alapú válaszellenőrzés csökkenti az egyszerű csalás lehetőségét, de fejlesztői eszközökkel egy statikus oldal nem tehető teljesen vizsgabiztossá. Szigorú vizsgához Moodle vagy más szerveroldali rendszer szükséges.
