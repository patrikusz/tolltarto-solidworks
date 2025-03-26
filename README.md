# Asztali Tolltartó Projekt

## Alapötlet
Mivel nemrég költöztünk át Kárpátaljáról Magyarországra, és szükségem volt egy asztali tolltartóra, úgy döntöttem, hogy az egyéni projektem ebből a tárgyból egy ilyen használati tárgy lesz. Különféle ötletek böngészéséből megtaláltam azt, amelyik a legjobban megtetszett (a Thingiverse oldalán), és az alapján elkezdtem a tervezést. A végén továbbfejlesztettem és hozzáadtam olyan elemeket, amelyek vagy tetszenek, vagy még hasznosak lehetnek számomra.

## A Megvalósítás

### Tervezés
A modell elkészítéséhez a SolidWorks 3D modellező szoftvert választottam, mivel ez volt számomra a legkézenfekvőbb és legszimpatikusabb.

1. **Talapzat Tervrajza:**
   - A talapzat tervrajzát jegyzetlap méretéhez igazítottam.
   - A méretek beállításához a Smart Dimension funkciót használtam.
   - Az Offset Entities művelet segítségével alakítottam ki a szegélyt.

2. **Harmadik Dimenzióba Emelés:**
   - A 2D tervet kiemeltem a harmadik dimenzióba, először a falát, majd a talapzatot is.
   - A Chamfer segítségével letörtem az elülső körív szegély belső élét.

3. **Hátsó Támasz Talpak Elkészítése:**
   - Létrehoztam egy párhuzamos síkot a Right Plane-nel, majd megterveztem a támasz formáját, amit extrudáltam.
   - Egy Sketch segítségével négyszöget rajzoltam, majd ennek oldalára egy újabb háromszöget emeltem.
   - A Linear Pattern művelettel duplikáltam a támaszt, figyelembe véve a megfelelő távolságokat.

4. **Mintázat Létrehozása:**
   - Újabb síkot hoztam létre, amelyre a megfelelő dőlésszög kiszámítását követően rajzoltam meg a mintázatot.
   - Az anyaghasználat csökkentése és a nyomtatási stabilitás érdekében a szöget úgy állítottam be, hogy támasztékok nélkül is nyomtatható legyen.

5. **Alapmodell Kidolgozása:**
   - Lekerekítettem az éleket.
   - Extruded Cut művelettel elhelyeztem a nevemet a tárgyon.
   - Kialakítottam két USB 3.0 tárolót, figyelembe véve az adott csatlakozók méreteit.
   - Dizájnelemként két USB feliratot is elhelyeztem a rekeszek előtt.

### Nyomtatás
1. **STL Fájl Létrehozása:**
   - A modell mentése STL formátumban.

2. **Szeletelés Prusa Slicerrel:**
   - A modellt a megfelelő síkra helyezve szeleteltem.
   - A szoftver jelezte, hogy instabil lehet a modell, de támasztékok használata nélkül is sikerült stabil szeletelést elérni.

3. **Nyomtatási Idő:**
   - A részletes tervezés miatt a nyomtatási idő viszonylag hosszú: 8 óra 16 perc.

4. **G-kód Exportálása:**
   - A G-kódot közvetlenül a nyomtatónak adtam át a nyomtatási folyamat elindításához.

## Összegzés
Az elkészült modell egy stabil, praktikus és esztétikus asztali tolltartó, amely az egyéni igényeimet maximálisan kielégíti. A tervezés és a nyomtatás során szerzett tapasztalatokkal tovább fejleszthetem a jövőbeli projektjeimet is.
