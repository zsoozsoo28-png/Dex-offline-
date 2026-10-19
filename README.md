# DEX telefonos felület – GitHub Pages

## Feltöltés
A mappa fájljait közvetlenül a `dex-offline` tárhely gyökérkönyvtárába töltsd fel. Az `index.html`, `sw.js` és `manifest.webmanifest` fájlok közvetlenül ott legyenek.

GitHub mobiloldalon: a tárhely főoldalán görgess a Quick setup részhez, válaszd az `uploading an existing file` hivatkozást, tallózd ki a kibontott csomag fájljait, majd válaszd a Commit changes lehetőséget.

Ezután Settings → Pages → Build and deployment résznél válaszd a Deploy from a branch beállítást, `main` ágat és `/(root)` mappát, majd Save. A megjelenő Pages-címet Chrome-ban nyisd meg egyszer internetkapcsolattal, és add hozzá a kezdőképernyőhöz.

## Mi működik, és mihez kell kapcsolat?
- Ez a csomag a telefonos DEX webes felületét és a böngésző gyorsítótárát tartalmazza.
- A korábban betöltött felület internet nélkül is megnyitható. A DEX beszélgetésmemóriája a böngésző helyi tárhelyére ment.
- A szabad, természetes nyelvű AI-válaszhoz és a WORK szerveres szerkesztéséhez továbbra is elérhető AI/WDEA szerver kell. Ebben a csomagban nincs helyi AI-modell vagy teljes WORK-rendszer.
- A beszédstílus-profil a hálózati AI-nak adott utasításban szerepel. Nem tanít önálló modellt, és nem garantál minden diktálási hiba automatikus javítását.
- A kamera és a mikrofon működése böngésző-, engedély- és eszközfüggő; valódi telefonon kell ellenőrizni.

## Nyilvánosság és kulcsok
A GitHub Pageshez használt nyilvános tárhely fájljait bárki megnézheti. Ne tölts fel jelszót, API-kulcsot, személyes adatot vagy szerver titkot. A DEX beállításaiban megadott kulcsokat se oszd meg, és később helyezd át szerveroldali védelem mögé.
