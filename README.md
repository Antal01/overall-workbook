# overall-workbook  

## Mi a git?  
  Nyílt forrású verziókezelő rendszer, szoftverforráskód kezelő rendszer.  
## Mi a github?
  A github egy kódtárhely verziókezeléshez és fejlesztők munkájának együttműködéséhez.  
## Mi a remote repository?  
  A project olyan verziói amik valahol az interneten vagy halózaton találhatóak.  
## Miért fordul elő merge conflict?  
  Amikor pull-olunk egy git repositoryt van hogy a helyi és a távoli verzióban is ugyanazokon a helyeken történt változtatás, és ilyenkor a rendszer nem képes összefésülni a két változatot.  
## Milyen előnyei vannak a verziókezelő rendszer használatának?  
-	A forráskód kezelése és védelme  
-	A kódon végrehajtott módosítások nyomon követése  
-	A kód összehasonlítása korábbi verziókkal  
-	Támogatja és megkönnyíti a fejlesztők munkáját, együttműködését.  
## Mi a hoisting?  
  A javascript a változó deklarációját az adott függvény vagy blokk elejére helyezi.    
## A különbség egy array és egy object között?  
- Az array egy lista ami elemekből áll, az elemeket az index számaikkal tudjuk elérni.  
- Az objectek kulcs-érték párokat tartalmaznak. Object.key-el tudjuk elérni az értéket vagy a key neve szögletes zárójelben.  
## Hogy lehet elérni egy lista első és utolsó elemét. 
- Egy lista elemét mindig a [0]-el kapjuk meg. Az utolsot pedig [l.length-1].  
## Primitív adattípusok javascriptben.  
- string
- number
- boolean
- null
- undefined
- bigint
- symbol  
## Értékadási műveletek  
- =, +=, -=, *=, /=, %=;  **=  
## Aritmatikai műveletek  
- összeadás, kivonás, szorzás, osztás, maradékos osztás, hatványozás  
## Összehasonlító műveletek  
- == === < > <= >=  
## Logikai műveletek  
- && || ! és, vagy, negáció  
## Különbség a for for of for in között.  
- A sima for 3 részböl áll, első egy kezdeti értékadás, a második egy feltétel ami ha igaz addig futtatjuk a ciklus magot és lefuttatjuk a 3. részt.
- Gyakran arra használjuk hogy végig menjunk egy lista elemein de nem annyira kötött mint a többi for ciklus, más lehetőségeink is vanak itt.
- A for of végig literál a listán, az elemeket egy változóba teszi, és futtatja a kód blokkot.
- A for in egy objecten literál végig és key-eket egy változóba teszi majd futtatja a kód blokkot.  
## Hogy adod meg egy lista számok átlagát ha nem használhatsz beépített függvényt?  
- összeadom a számokat a listában és elosztom az array.lenght-el.  
## Mik egy függvény fő részei?  
- function kulcsszó
- Egy opcionális név(lehet anonymus is)
- Paraméter(ek) zárójelben.
- Az állítások kapcsos zárójelben.(függyvény törzs)  
## Mi a különbség paraméter és argument között?  
- A paraméterek nevek azoknak az adatoknak amik a függvénynek  lesznek átadva.
- Az argumentumok pedig a valós adatok.  
## Mi a különbség a function expression(kifejezés) és a function statement(állítás) között?  
- A függvénykifejezés értéket társít egy változóhoz és csak akkor tölt be ha az értelmező eléri a függvény definicióját.
- A függvényállítás betöltődik a kód végrehajtása előtt, tudjuk használni a függvény definiálása előtt.  
## Mi a method?  
A method egy object tulajdonság aminek függvény értéke van.  
## Nevezz meg 3 beépített függvényt (vagy metódust) ami a stringre vonatkozik  
- split()
- CharAt()
- parseInt()
## Nevezz meg 3 beépített függvényt ami arrayre vonatkozik  
- push()
- sort()
- slice()  
## Nevezz meg 3 beépített függvényt ami számokra vonatkozik.  
- math.floor()
- math.random()
- toString()  
## Mi a callback function?  
- A callback függyvényeket egy másik függvény argumentumába adjuk át.
- Az aminek átadtuk majd meghivja ezt a függyvényt.(set.timeOut)  
## Mi a különgbség a for ciklus és a forEach között?  
- A sima for ciklus egy tömb elemein literál végig meghatározott alkalommal.Ez egy beépített nyelvi elem.
- A forEach egy metódus.eEgy tömbön vagy objectumon megy végig, de callback functiont használ a tömb minden egyes eleménél.  
## A különbség a javascript és a json adatszerkezet között?  
- A json támogatva van 50 programozási nyelv által. Adat szerkezete tartalmaz stringet, numberst, booleant, nullt objectumot, listát.
- A javascript objectumok teljes mértékben a javascriptöl függnek. Nem működnek semmilyes más programozási nyelvvel. Adat szerekezete tartalmazza ugyanezt mint a json-nek de még kiegészül undefineddal, függvényekkel.  
## Hogy csinálunk javascript adatszerkezetet json adatszerkezetböl?  
Json.parse() metódussal  
## Mi a különgbség a javascript adatszerkezet és a dom adatszerkezet között?  
A dom egy fa szerkezet amit a böngésző arra használ hogy megjelenítsen egy weboldalt. A fa nódjait elemeknek hívjuk.
Az elemeknek attribútumaik vannak. Minden attributumnak van egy string kulcsa és egy string értéke. A dom tartalmaz szöveget is az elemek között.
Javscript adat szerkezetet akkor hasznaljuk ha futtatjuk a javascript kódot.
Ez lehet a böngészőben is szerverben is. Ez a szerkezet listákat objectumokat, stringeket számokat tartalmaz.  
## Mik a lépések egy html elem tartalmának kicserélésére?  
Először a getElementbyId vagy querySelectorral meg kell keresni az elemet, aztán pedig az : innerHTML vagy insertAdjacentHTML kell használni.  
## Mi az event listener?  
- Az event listener olyan függvény ami egy esemény bekövetkezésére vár. pl amikor a felhasználó a webhelyen lévő gombra kattint. Az addEvenelistener függyvénnyel tudjuk az event listener függyvényünket hozzárendelni az eseményhez. Amikor az esemény megtörténik az event listener meghívódik.  
## Mik a lépései egy html elem tartalmának kicserélésére ha az elemre kattintunk?  
Először az addEventlistnert használjuk hogy hozzárendeljük az eseményhez az event listener  függyvényünket.  
A böngésző meghívja az event listenerünket mikor rákattintanak a gombra. Utána hívunk egy függvényt ami kicseréli a htmlt.  
## A click event listeneren belül hogy tudjuk elérni azt az elemet amire kattintottak?  
Az event listener függvény kiolvassa a változobol az elemet amire kattintottak.(event.target)
## Mi a különgség a display:block és a display inline között?  
A display block a képernyő teljes szélességét használja. Az inline nem, ott más elemek is lehetnek mellette.  
## Mi a különbség a position: relative és a position: absolute között?  
Ha egy elemnél a position:relative-t használjuk, akkor a böngésző az elem helyét az eredeti pozíció és a relatív pozíció alapján számítja ki.  
Ha a position: abszolút értéket használjuk, akkor a böngésző az általunk megadott koordináták szerint helyezi el az elemet.  
## Mi a box model? Milyen css tulajdonságok tartoznak hozzá?  
A tartalom mindig a doboz közepén van, és körülötte van 3 további doboz: padding, border, margin. Tudjuk állítani a dobozok vastagságát.  
## Milyen css tulajdonságok befolyásolják a betűtípust és a szöveg megjelenését?  
betű: font families ,font-size, font style, font weight  
szöveg: text transform, text decoration, text shadow, line height,  text alignment, color  
## Mik a lépései egy html class hozzáadásának eltávolításának?  
Először meg kell keresnünk az elemet a getElementById-val vagy querySelectorral.  
Utánna pedig a setAttribute() tudjuk hozzáadni vagy a removeAttributtal eltávolítani.  
## Mikor használjuk a var-t, let-et és a const-ot?  
A var az egy függvény hatókörű változó. Ha egy függvényben definiáljuk akkor a függvény lefutása közben elérhetjük.  
A let változó csak blokk hatókörű. Az adott blokkon kívül nem érhető el. A var és a let egyaránt használható globális változóként.  
A const változónak minden tulajdonsága megegyezik a let változóval, csak a felhasználó nem tudja frissíteni.  
