# Objektumvezérelt rendszerek tervezése
# IMN245g-1

## Általános információk

- http://www.inf.u-szeged.hu/oktatas/kurzusleirasok/I051.xml
- http://www.inf.u-szeged.hu/~beszedes/teaching/oovez/index.html
- http://www.inf.u-szeged.hu/~antal

## Gyakorlat értékelése

A gyakorlaton szerezhető összesen 100p (40p zh + 60p projektmunka).

Jegyek ponthatárai:

- 90-100 jeles
- 75-89 jó
- 60-74 közepes
- 45-59 elégséges

### Zárthelyi dolgozatok (40 pont)
- Két zh, 20-20 perces, gyakorlat és előadás anyag is, 2*20p.
- Maximálisan elérhető: 40 pont.
- Minimális követelmény: a két zh-ból min. 20p (**az egyes zh-kra külön-külön minimum 10-10p**).
- Javítani csak az egész anyagból lehet, maximum 20 pontért.

### Projektek (60 pont)
- A projekteken 3-5 fős csapatok dolgoznak!
- Teljesítendő minimális pontszám: összesen 20, de projektenként min. 40% (P1, P2: 12).
- Projektek javítására nincs lehetőség!

### P0: csapatalakítás, projektválasztás

#### OVRT-P0-csapatnév-csapatalakítás

A gyakorlatvezetőnek küldeni kell egy mailt a megadott tárggyal, ahol fel kell sorolni a csapat tagjait a h-s azonosítókkal együtt, úgy hogy az első helyen a csapatkapitány szerepeljen a következő sémának megfelelően (fontos, hogy feldolgozás miatt semmi más ne szerepeljen a mailben):

```
hxxxxxx;Neptun azonosito;Vezetéknév Keresztnév
```

#### OVRT-P0-csapatnév-projektválasztás

A megadott határidőig küldeni kell egy mailt, ahol prioritási sorrendben meg kell adni 5 projektet. Ez alapján kerülnek a projektek kiosztásra, egy projektet max. 1 csapat kap, ezért ha valaki olyanra jelentkezik, amit korábban valaki lefoglalt akkor a prioritásban következőt kapja, ha az is foglalt, akkor így tovább.

#### P1: UML tervezési projekt, prototípus – 30p

A feladat a választott projekt megtervezése tanult OO tervezési eszközök segítségével és az azt implementáló prototípus készítése.

##### OVRT-P1-csapatnév-projektterv – 3p

P1, P2 feladatok ütemezését tartalmazó projekttervet kell leadni, kiemelve a csapat tagjai közötti feladatok megoszlását.
A megrendelő által elfogadott projekttervet kinyomtatva, a határidőt követő órára be kell hozni.
Az elfogadott projekttervet a gyakorlat oktatója aláírja, a későbbiekben minden leadásnál ezen történik a pontok/költségek menedzselése. 

*A projekttervet nyomtatva és PDF-ben kell leadni. A pdf-nek a Git repo doc/ mappájában kell lennie.*

**Névkonvenció**: `OVRT-P0-csapatnev-projektterv.pdf`

##### OVRT-P1-csapatnév-tervek – 12p


A funkcionalitást megvalósító eszközhöz UML tervek készítése:
Use Case diagram, Class diagram, Package diagram

*A terveket PDF-ben kell leadni. A pdf-nek a Git repo doc/ mappájában kell lennie.(tetszőleges UML szerkesztő használhat, ingyenes PDF nyomtatók segíthetnek, pl. Bullzip)*

**Névkonvenció**: `OVRT-P1-csapatnev-tervek.pdf`

##### OVRT-P1-csapatnév-prototípus – 15p

A gyakorlatvezetővel egyeztetett OO nyelven (preferált: Java, C++, Python, C#) implementált prototípust kell leadni. Nem baj, ha nem teljesíti a teljes funkcionalitást, de kísérő dokumentációban indokolni kell ez miért van így, illetve, hogy mennyire felel meg a terveknek az implementáció.

*A forráskódnak a Git src/ mappájában kell elérhetőnek lennie, a kísérő dokumentációt PDF-ben kell leadni. A pdf-nek a Git repo doc/ mappájában kell lennie.*

**Névkonvenció**: `OVRT-P1-csapatnev-protipus.{pdf}`

#### P2: Tervezési mintákkal újratervezett eszköz – 30p


A feladat a korábban megtervezett és prototípussal leadott program újratervezése, refactoring lehetőségeket és a már tanult tervezési mintákat szem előtt tartva. Az újratervezett eszközhöz végleges implementációt is el kell készíteni.

##### OVRT-P2-csapatnév-tervek – 15p

A korábbi UML tervek átdolgozása, hogy tervezési mintákat is tartalmazzanak (ha alapból nem tartalmaznak).

**Legalább 3 tervezési minta felhasználása kötelező!**

Az eredeti tervekhez plusz: Sequence diagram, Deployment diagram

*A terveket PDF-ben kell leadni. A pdf-nek a Git repo doc/ mappájában kell lennie. (tetszőleges UML szerkesztő használható, ingyenes PDF nyomtatók segíthetnek, pl. Bullzip)*

**Névkonvenció**: `OVRT-P2-csapatnev-tervek.pdf`

##### OVRT-P2-csapatnév-implementáció – 15p

Végleges, az új terveknek megfelelő implementáció a gyakorlatvezetővel egyeztetett OO nyelven (preferált: Java, C++, Python, C#).
Az implementációban felismerhetőnek kell lennie a választott tervezési mintáknak, amiket bemutatón a csapat **bármely** tagjának be kell tudni mutatnia!

*A forráskódnak a Git src/ mappájában kell elérhetőnek lennie, a kísérő dokumentációt PDF-ben kell leadni. A pdf-nek az Git repo doc/ mappájában kell lennie.*

**Névkonvenció**: `OVRT-P2-csapatnev-implementacio.{pdf}`

Megjegyzések

- A megadott elnevezési konvenciókat (email tárgya, fájlok elnevezése) szigorúan be kell tartani; pl. emailnél nem megfelelő tárgy esetén a beküldött anyagot nem értékeljük.
- A projektekről minden óra végén egy rövid megbeszélést kell tartani minden csapatnak a megrendelővel (gyakvezérrel).
- A leadást követő foglalkozáson a megrendelőnek szóban be kell mutatni az átadott részeredményeket.
- Leadás késésekor minden megkezdett új nap esetén (hétvége és ünnepnap is beleszámít) 2p levonásra kerül az aktuális felelősöktől (projektterv alapján).
- Amennyiben valamelyik csapattag kilép és emiatt a többi csapattag hátrányba kerül, akkor lehetőség van a projektterv átütemezésére; ebben az esetben a megrendelővel azonnal egyeztetni kell!
