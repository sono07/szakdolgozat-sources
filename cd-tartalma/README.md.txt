# CD-melléklet tartalma

A szakdolgozat LaTeX segítségével készült. A dolgozat forrásfájljai a "report/sources" mappában találhatóak.
A dolgozat PDF-re fordított változata pedig a "report/pdf" mappában található meg "report.pdf" néven.

A dolgozat során elkészült játék forrásfájljai a "game/sources" mappába kerültek elhelyezésre.
A program fordításához a Node.js-re, NPM csomagkezelőre, illetve internetkapcsolatra van szükség.

A "game/sources" mappában egy konzolt szükséges először nyitni, itt az "npm install" parancsot kell futtatni, a szükséges függőségek telepítéséhez (ehhez internetkapcsolat szükséges).
Ezután, ha a teszteket szeretnénk futtatni, akkor azt az "npm test" parancs segítségével tehetjük meg.
Az alkalmazás fejlesztői módban való elindításához az "npm start" parancsot kell futtatnunk, ami a fordítás után egy webszervert fog elindítani a gépünkön a 8080-as porton. Ezután böngészőnkben a "localhost:8080" -as oldalra navigálva elérhetjük az alkalmazást.
A program optimalizáltan és kiadható formában fordított változatát az "npm run build" parancs futtatásával lehet elkészíteni. Ez az aktuális mappán belüli "dist" mappába fogja elhelyezni a fordított fájlokat. Ezt követően a kész fájlokat egy webszerverre másolva lehet használni. A kipróbálhatóság érdekében az "npm run serve-build" paranccsal tudunk futtatni ideiglenesen egy minimális funkciókkal bíró webszervert. Ez a parancs elméletileg az alapértelmezett böngészőnkben meg is nyitja az alkalmazást mely a "http://127.0.0.1:4949/dist/" címen érhető el.

Az előre lefordított alkalmazás a "game/dist" mappában található, ennek használatához előzőekben említetthez hasonlóan szükségünk van egy webszerverre.

A játék használatáról részletesebben a dolgozatban a Használat fejezetben található útmutatás.