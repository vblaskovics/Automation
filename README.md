# Automata teszteléshez példa feladatok

[Ez az oldal](https://vblaskovics.github.io/GroupamaAutomation) oktatási céllal készült.

Olyan demo felületeket tartalmaz, amelyek segítségével gyakorolni lehet webes automatizált tesztelési kereteket - pl. Selenium IDE-t, és Selenium WebDriver-t.

## Dummy felületek
- [Hello World](https://vblaskovics.github.io/Automation/pages/01_hello_world.html)
- [Webshop](https://vblaskovics.github.io/Automation/pages/02_webshop.html)
- [Űrlap](https://vblaskovics.github.io/Automation/pages/03_form.html)
- [Időjárás](https://vblaskovics.github.io/Automation/pages/04_forecast.html)
- [Kő, papír, olló](https://vblaskovics.github.io/Automation/pages/05_kopapirollo.html)


## Feladatok

### 1. Elem kiválasztása
A [Hello World oldalból](https://vblaskovics.github.io/Automation/pages/01_hello_world.html) indulj ki!
1. Ellenőrizd, hogy a böngészőlap címe: "Hello World"! 
2. Keresd meg a "Hello Selenium!" elemet az oldalon, és ellenőrizd, hogy a szöveg tartalma valóban "Hello Selenium!" - id alapján!
3. Keresd meg az alcímet, és ellenőrizd, hogy a felírata: "Ez egy alcím" - class alapján!
4. Ellenőrizd, hogy az azonosító: "HW/001"!
5. Ellenőrizd, hogy az email: test@example.com!
6. Ellenőrizd, hogy a dátum 2022.01.03!
7. Indítsd úgy a tesztet, hogy az elején rákattintassz az Elront gombra
    - Ellenőrizd, hogy a tesztek hibát jeleznek-e!
    - Keresd meg a hibáról készült log-ot!
8. Vegyél fel egy új ellenőrzést a legelső ellenőrzés elé, amiben szintén a HW/001 mező értékét ellenőrzöd! Most is úgy indítsd a tesztet, hogy először az Elront gombra kattintassz, viszont most úgy csináld meg az ellenőrzést, hogy ennél a pontnál ne álljon meg a teszt!
9. Comment-eld ki az Elront gombra való kattintást!

### 2. Várakozás

A [Webshop oldalból](https://vblaskovics.github.io/Automation/pages/02_webshop.html) indulj ki!
1. Add hozzá az első terméket a kosárhoz, és ellenőrizd, hogy sikerült-e hozzáadni!
2. Ellenőrizd, hogy tudod-e növelni és csökkenteni a termékek számát!
3. Nyomd meg a második termék Részletek gombját, és ellenőrizd, hogy megjelennek-e a részletek!
    - Mikor Xpath és mikor css?
    - Várakozni kell
4. Add hozzá a harmadik terméket is a kosárhoz, és ellenőrizd, hogy sikerült-e hozzáadni! (Figyeld a selector-t!)


### 3. Formok
Az [Űrlap oldalból](https://vblaskovics.github.io/Automation/pages/03_form.html) indulj ki!
1. Írj be a name mezőbe egy nevet, és ellenőrizd, hogy sikerült-e!
2. Ellenőrizd, hogy az email mezőnek van-e placeholder szövege!
3. Ellenőrizd, hogy a Name label össze van-e rendelve az input mezővel!
4. Ellenőrizd, hogy hibaüzenetet kapunk-e, ha @ karakter nélküli emailcímet adunk meg!
5. Ellenőrizd, hogy nem kapunk hibaüzenetet, ha @ karakterrel adunk meg email címet!
6. Ellenőrizd, hogy ha az Email-t rosszul töltjük ki, de az Email megerősítése mezőt jól, akkor csak az első esetben kapunk hibaüzenetet!
7. Ellenőrizd, hogy működik a Submit gomb, ha legalább a *-os mezők ki lettek töltve!
8. Ellenőrizd, hogy nem működik a Submit gomb, ha van *-os mező, ami nincs kitöltve!

### 4. If, variable, loop
Az [Időjárás oldalból](https://vblaskovics.github.io/Automation/pages/04_forecast.html) indulj ki!
1. Ellenőrizd, hogy megjelenik-e hőmérséklet adat!
2. Ellenőrizd, hogy ha - a hőmérséklet, akkor megjelenik egy fagyás ikon!
3. Ellenőrizd, hogy ha + a hőmérséklet, akkor nem jelenik meg fagyás ikon!
4. Addig frissítsd az oldalt, ameddig nem jelenik meg a fagyás ikon!

### 5. Kő-papír-olló
Az [Kő-papír-olló](https://vblaskovics.github.io/Automation/pages/05_forecast.html) indulj ki!
1. Teszteld le, hogy a program mindig szabályosan értékeli ki a lépéseket!
