# Objektumvezérelt rendszerek tervezése

## Kötelező programok 2017-2018-1

Az alább található néhány kötelező program ötlet, de ezeken kívül egyedi ötleteket is meg lehet valósítani, azonban ezt a gyakorlatvezetővel egyeztetni kell.

A kötelező programok megvalósítása előre egyeztetett nyelven történhet, külső függvénykönyvtárak is használhatóak, azonban az órán tanultakat a beadott programnak tükröznie kell. Mind webes, mind asztali alkalmazás készíthető.

### South Park figurarajzoló alkalmazás

#### Feladatkiírás
A feladat egy South Park figurarajzoló alkalmazás elkészítése, amelyben a felhasználó South Park figurákat rakhat össze egyszerűen.

#### Főbb funkciók
- a felhasználó kézzel összepakolhatja a figurát már előre elkészített részfigurákból (pl. egy kész fej) vagy pedig primitív elemek (szem, száj, sapka, stb.) segítségével.
- minden elemnek van egy vagánysági pontja (pl. a piros sál pontja 10, a fekete sapkáé 5)
- az összetett elemek vagánysági pontja az őt felépítő elemek pontjának összege.
- különböző statisztikák a figurákról (pl. legvagányabb elem, legkevésbé vagány elem, átlagos vagányság, stb.)
- elkészült figurák mentése és betöltése
- elkészült figurák mentése képként
- különböző hátterek (színterek)

#### Extra funkció ötletek (ezeken kívül természetesen bármilyen egyedi ötlettel kiegészíthető)
- nyomtatás (pl. minden elemet külön-külön helyez a nyomtatandó dokumentumra, hogy stop motion animációt készíthessünk belőle)
- rajzolás funkció (pl.: háttéren módosíthassunk)
- random figura generálása
- elkészült figurák mentése (akár online) katalógusba

### Bemutató készítő alkalmazás

#### Feladatkiírás
A feladat egy Google Slides/Microsoft PowerPoint alkalmazáshoz hasonló bemutató készítő alkalmazás fejlesztése, leegyszerűsített funkcionalitással. Az alkalmazás lehet általános célú is, de lehet specializálni is, akkor az adott témakörhöz kapcsolódó funkciókat kell készíteni.

#### Főbb funkciók
- diák hozzáadása, törlése, módosítása
- kész bemutatók mentése, betöltése
- diavetítés
- szerkezeti sablonok (legalább 2 darab, pl.: fejléces, 1 hasábos diasablon; fejléc nélküli, 2 hasábos sablon)
- kinézeti sablonok (legalább 2 darab)
- különböző dobozok behelyezése (pl. sima szövegdoboz, kódrészlet doboz (benne lévő kód syntax highlightot kap), képdoboz)
- statisztika megjelenítése a felhasználó számára (pl. hány diát készített, hány szó van átlagosan egy dián, stb.)

#### Extra funkció ötletek (ezeken kívül természetesen bármilyen egyedi ötlettel kiegészíthető)
- bemutató mentése JPG, PDF formátumba
- behelyezett dobozok automatikus rendezése úgy, hogy ergonomikus legyen
- animáció (áttűnések, szöveg beúszás, stb.)

### D&D pálya szerkesztő

#### Feladatkiírás
A feladat egy D&D pálya szerkesztő alkalmazás fejlesztése. A programmal össze lehessen állítani egy alaprajzot és tárgyakat lehessen elhelyezni jelmagyarázattal. Példák: https://www.google.hu/search?q=dungeons+and+dragons+map&source=lnms&tbm=isch&sa=X&ved=0ahUKEwi3y5Cq7v7VAhXjKJoKHWsNDaAQ_AUICigB&biw=1920&bih=1085#imgrc=Y305XWXCC4Q1ZM:

#### Főbb funkciók:
- négyzetrácsra épülő alaprajz összeállítása az alapoktól
- négyzetrácsra épülő alaprajz véletlenszerű generálása 
- kész pálya mentése és betöltése
- program által nyújtott tárgyal elhelyezése (ajtó, ágy, asztal, szék, stb.)
- feliratok elhelyezése
- különböző statisztikák készítése (melyik tárgyból mennyi van lerakva, átlagosan hány tárgy van egy szobában)
- nehézség megállapítása a pálya méretéből és a lehelyezett tárgyakból

#### Extra funkció ötletek (ezeken kívül természetesen bármilyen egyedi ötlettel kiegészíthető)
- szabadkézi pálya rajzolás
- nyomtatás
- fog of war
- karakterek elhelyezése a térképre, játék során mozgatása
- szörnyek lehelyezése, eltávolítása
- az elkészült térképek automatikus feltöltése webre
- pályák vizuális dekorálása

### Sport-nyomonkövető alkalmazás

#### Feladatkiírás
A feladat egy sportolást nyilvántartó és segítő alkalmazás készítése. Az alkalmazás több sportolási lehetőséget támogat, dokumentálja a felhasználó teljesítményét és statisztikai adatokat jelenít meg. A felhasználók felvehetik egymást ismerősként és összehasonlíthatják eredményeiket barátaikkal, ezzel további motivációt szerezve.

Példa: https://www.endomondo.com/

#### Főbb funkciók:
- sportágak elkülönítése, egyedi elemek figyelembevétele
- cardio típusú sportágak (futás, úszás, kerékpározás, gyaloglás,...)
- megtett távolság és idő megadása
- felhasználók elkülönítése
- lehetőség más felhasználók ismerősként való felvételére
- statisztikai adatok számítása és megjelenítése az elvégzett tevékenységekről (heti jelentés, diagramok, elégetett kalória)
- az eredmények ismerősökkel való összehasonlítása, riport készítése

#### Extra funkció ötletek (ezeken kívül természetesen bármilyen egyedi ötlet elkészíthető)
- statisztikák, riportok, diagramok mentése PDF formába
- erőnléti edzés támogatása (mit, mekkora súllyal, hányszor és hány ismétléssel hajt végre, pl. kitörés, 10 kg, 20-szor, 5 ismétléssel)
- a felhasználó kihívásokat adhat meg magának (például heti 3 futás egy hónapig), ezeket a rendszer ellenőrzi, és ha sikerült a kihívás, akkor értesítse a felhasználót
- kihívások küldése ismerősöknek, a kihívások elfogadhatók vagy visszautasíthatók
- baráti csoportok, közös kihívásokkal (pl. 5 barát alakít egy csoportot, majd létrehoznak egy "csoport kihívást", mondjuk 40 km futás. Ilyenkor folyamatosan figyelni kell a csoport tagjainak egyéni teljesítményét, és értesíteni a tagokat, ha elérték a kihívás teljesítéhez szükséges teljesítményt)
- pontrendszer, valamilyen céllal

### Kreatív írást segítő alkalmazás

#### Feladatkiírás
A feladat egy írást segítő alkalmazás készítése, amelyben a felhasználó elvégezheti magát az írást, a különböző jelenetek és fejezetek elkülönítését, és mindmap funkciókkal rendszerezheti ötleteit.

Példák: https://www.literatureandlatte.com/scrivener.php, https://play.google.com/store/apps/details?id=com.cryptobees.mimind&hl=hu

#### Főbb funkciók:
- szöveg létrehozása, alapszintű formázása (legalább 3 az alábbiakból: méret, betűtípus, színezés, aláhúzás, félkövér, dőlt)
- projektek, fejezetek elkülönítése, jelenetek létrehozása
- idővonal megvalósítása és megjelenítése a jelenetek között tetszőlegesen megadott időpontokkal
- mindmap készítési lehetőségek: szöveg tárolására és módosítására alkalmas elemek létrehozása, szabad mozgatása, tetszőleges összekapcsolása, színezése

#### Extra funkció ötletek (ezeken kívül természetesen bármilyen egyedi ötlet elkészíthető)
- sablonok létrehozása, új szöveg sablonból való kezdése, alap sablonok (karakter leírás sablon, helyszín leírás sablon, stb.)
- több helyszín esetén lehetőség párhuzamos idővonalakra
- mindmap-en képek hozzáadása, illetve különböző alakú elemek
- mindmap-en különböző kapcsolatok megadása (színek, szaggatott vonalak...)
- mindmap-en elemek csoportjainak létrehozása a háttér színével elkülönítve
