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

  
## Mi a különgség a let és a var között?  
- A var függvény hatókörű változó, ha függvényben definiáljuk, akkor hozzáférhetünk miközben a funkció fut.
- A let változó csak blokk hatókörű. Az adott blokkon kívül nem érhető el. A var és a let egyaránt használható globális változók meghatározására.  
## Praktukus példa a reduce function használatára  
- megkapni az az összegét egy listánnyi számnak
  
        const array1 = [1, 2, 3, 4];
        // 0 + 1 + 2 + 3 + 4
        const initialValue = 0;
        const sumWithInitial = array1.reduce(
          (accumulator, currentValue) => accumulator + currentValue,
          initialValue
        );
        console.log(sumWithInitial);
        // Expected output: 10  

## Példa filter function használatára  
- például magkapni a 20-nál kisebb számait egy listának  

        const numbers = [32, 33, 16, 40];
        const numbersBelow20 = numbers.filter(number => number < 20)  

## Mi a webserver?  
- Hardver oldalon a webszerver egy olyan számítógép, amely webszerver szoftvert és egy webhely componens fájljait tárolja.
- A webszerver csatlakozik az internethez, és támogatja az adatcserét más, az internethez csatlakoztatott eszközökkel.  
## Magyarázd el a cliens-server architechtúrát  
- A szerver az, aki a kért szolgáltatásokat nyújtja.
- Az ügyfelek azok, akik szolgáltatást igényelnek.
- A szerver tárolja, szállítja és kezeli az ügyfél által kért erőforrások és szolgáltatások nagy részét.  
  
- Az ügyfél jellemzői:  
  - A kérés feladója ügyfélként ismert
  - Kéréseket kezdeményez
  - Várja és fogadja a válaszokat
  - Általában kevés szerverhez csatlakozik egyszerre
  - Jellemzően közvetlenül kommunikál a végfelhasználókkal egy grafikus felhasználói felület segítségével  
      
- A szerver jellemzői:  
  - A kliens által küldött kérés fogadóját szervernek nevezik
  - Passzív (szolga)
  - Várja az ügyfelek kérését
  - A kérések beérkezése után feldolgozza azokat, majd kiszolgálja a válaszokat
  - Általában nagyszámú ügyféltől fogad kapcsolatokat
  - Általában nem lép kapcsolatba közvetlenül a végfelhasználókkal  
## Mi a különbség a szinkron és az aszinkron végrehajtás között?  
- A szinkron feladatok sorrendben történnek – az első feladatot be kell fejeznie, mielőtt a következőre lépne.
- Az aszinkron feladatok tetszőleges sorrendben, vagy akár egyszerre is végrehajthatók.  
## Mi az "npm"? Miért hasznos?  
- Node Package Manager a javascript platformhoz. Modulokat helyez el, hogy a node megtalálhassa őket, és kezeli a függőségi konfliktusokat.
- Node programok közzétételére, felfedezésére, telepítésére és fejlesztésére szolgál.  
## Mi a különbség a "depdendencies" és a "devDependencies" között a "package.json" fájlban?  
- A dependency egy olyan objektum, amely tartalmazza a könyvtárat, amelyre a projektnek szüksége van a termelési környezetekhez és a hatékony működéshez. (Modulok, amelyek futás közben is szükségesek)
- A devDependencies a package.json fájl azon csomagjai, amelyekre csak projektfejlesztési céloknál van szüksége. (Modulok, amelyekre csak a fejlesztés során van szükség.)  
## Mi lenne a javascript "fetch" hatása, ha nem lenne aszinkron?  
- Ha a lekérés nem aszinkron, az azt jelenti, hogy a kód végrehajtása blokkolva lesz, amíg a kérés be nem fejeződik.
- A hálózati válaszra várva a felhasználói felület nem reagál, ami rossz felhasználói élményt eredményezne.
- Ez hatással lenne a teljes alkalmazás teljesítményére, mivel a böngésző nem tudna más JavaScript-kódot végrehajtani, amíg a lekérési kérés befejezésére vár.  
## Miért járna előnyökkel a fejlesztőnek a "Postman" alkalmazás használatával?  
- Könnyű API-tesztelés: lehetővé teszi a fejlesztők számára, hogy kéréseket küldjenek, megtekintsék a válaszokat, és gyorsan és egyszerűen végezzenek hibakeresést
- már a fejlesztési folyamat korai szakaszában felismerni a problémákat
- valós időben figyeli az API-kat, és értesítéseket kap, ha valami elromlik  
## Sorolja fel az URL részeit: 
1. Séma: A séma meghatározza az erőforrás eléréséhez használt protokollt. A gyakori sémák közé tartozik a HTTP, HTTPS  
2. Subdomain  
3. Host: A host adja meg annak a kiszolgálónak a tartománynevét vagy IP-címét, ahol az erőforrás található.  
4. Port: A port a kiszolgálón lévő erőforrás eléréséhez használt hálózati port számát adja meg. Ez nem kötelező, és általában kimarad, ha a séma alapértelmezett portszámát használja.  
5. Path Az elérési út az erőforrás helyét határozza meg a szerveren. Általában könyvtárak és fájlnevek sorozatából áll, amelyeket perjelek választanak el.  
6. Query string: A query string lehetővé teszi további paraméterek átadását a szervernek az erőforrás kérésekor. Kérdőjel választja el az útvonaltól, és egy vagy több kulcs-érték párból áll, amelyeket „és” jel választ el.  
7. Fragment: A fragment az erőforrás egy meghatározott részét határozza meg, amelyet meg kell jeleníteni. Ezt egy hash szimbólum választja el az URL többi részétől, és általában HTML-dokumentumokhoz használják az oldal egy adott részéhez való görgetéshez.  
## Mik a query paraméterek?
- A query paraméterek egy url végéhez csatolt paraméterek meghatározott halmaza.
- Ezek az URL kiterjesztései, amelyek az átadott adatok alapján meghatározott tartalmak vagy műveletek meghatározására szolgálnak.  
## Milyen HTTP állapotkódokat ismer?  
- Tájékoztató válaszok (100-199)
- Sikeres válaszok (200-299)
- 200 OK : A kérés sikeres volt
- 201 Létrehozva : A kérés sikeres volt, és ennek eredményeként új erőforrás jött létre. Ez általában a POST kérések vagy néhány PUT kérés után küldött válasz.
- Átirányítási üzenetek (300–399)
- Ügyfél hibaválaszai (400–499)
- 400 Hibás kérés: A szerver nem tudja feldolgozni a kérést ügyfélhiba miatt
- 401 Jogosulatlan: Bár a HTTP-szabvány meghatározza az "illetéktelen" kifejezést, szemantikailag ez a válasz azt jelenti, hogy "nem hitelesített". Vagyis az ügyfélnek hitelesítenie kell magát, hogy megkapja a kért választ.
- 404 Nem található: A szerver nem találja a kért erőforrást, az URL-t nem ismeri fel.
- 429 Túl sok kérés : A felhasználó túl sok kérést küldött egy adott időn belül ("sebességkorlátozás").
- Szerverhiba-válaszok (500-599)
- 500 Belső szerverhiba : a szerver váratlan feltétellel találkozott, amely megakadályozta a kérés teljesítésében.  
## Hogyan néz ki egy HTTP-kérés? Melyek a legrelevánsabb HTTP header fieldek
- A HTTP-kérés egy ügyfél (például egy webböngésző) által a webszervernek küldött üzenet, amely egy adott művelet végrehajtását kéri a szerveren.
- A HTTP (Hypertext Transfer Protocol) a kliensek és szerverek közötti kommunikációra használt protokoll a világhálón.
- A HTTP-kérések a webfejlesztés alapvető részét képezik, és számos feladathoz használják őket, például weboldalak lekérésére, űrlapadatok elküldésére és webes API-kal való interakcióra.
- A HTTP-kérés három részből áll: a kérés sorából, a kérés fejlécéből és az üzenet törzséből
- A leggyakrabban használt HTTP-módszerek a POST, GET, PUT, PATCH és DELETE.
- fetch()
- beépített JavaScript metódus, amely aszinkron hálózati kérések (HTTP kérések) küldésére szolgál webszerverekhez vagy API-khoz.
- A fetch() metódus promisokat ad vissza, amely lehetővé teszi a fejlesztők számára, hogy a válaszadatokat elegánsabban és hatékonyabban kezeljék, mint a hagyományos visszahívási függvények esetén. A promise feloldható egy Response objektummal, amely információkat tartalmaz a válaszról, például az állapotkódot, fejléceket és adatokat.

        fetch('https://api.example.com/data')
        .then(response => response.json())
        .then(data => {
          // Csinálj valamit az adatokkal
        })
        .catch(error => {
          // Az esetleges hibák kezelése
        });

- Ebben a példában a fetch() a „https://api.example.com/data” URL-címre küldött GET kérelmet szolgálja. A választ ezután a json() metódussal JSON-ba konvertálja, amely egy promiset ad vissza, amely az elemzett JSON-adatokkal oldódik meg. Végül az adatok kezelése a második then() metódussal történik, vagy az esetleges hibákat a catch() metódus kezeli.  
## Hogyan néz ki egy HTTP-válasz? Melyek a legrelevánsabb HTTP header fields?  
- A HTTP-válasz egy üzenet, amelyet egy webszerver küld egy ügyfélnek (például egy webböngészőnek) HTTP-kérésre válaszul. A válasz jellemzően a kért tartalmat vagy a kérés állapotára vonatkozó információkat tartalmazza.
- HTTP válasz részei:  
  1. Állapotsor: A válasz első sora, amely tartalmazza a HTTP verziót, a kérés eredményét jelző numerikus állapotkódot, valamint az állapot rövid szöveges leírását.  
  2. Fejlécek: Opcionális kiegészítő információk a válaszról, például a visszaküldött adatok típusa, a válasz hossza vagy a gyorsítótárazási utasítások az ügyfél számára.  
  3. Törzs: A válasz tartalma, például HTML, JSON vagy kép.  

## Miért hagyja figyelmen kívül a `node_modules` mappát a `.gitignore` fájlban?
- A Node.js projektekben a node_modules mappa általában nagyszámú külső féltől származó függőséget és könyvtárat tartalmaz, amelyeket csomagkezelőn (például npm vagy Yarn) keresztül telepítenek. Ez a mappa könnyen meglehetős méretűvé válhat, és általában nem szükséges belefoglalni a verziókezelésbe, mivel a függőségek a semmiből telepíthetők bármelyik gépre az npm install vagy a yarn install futtatásával.
- A node_modules mappa figyelmen kívül hagyása a .gitignore fájlban segíthet csökkenteni a Git tárhely méretét, és elkerülni a nagy bináris fájlok szükségtelen végrehajtását, ami lelassíthatja a Git műveleteket, és növelheti a lerakat teljes méretét.  

## Miért javasolt a fejlesztőknek a `get`, `put`, `delete` http metódusok használata?	
- Ezek a módszerek egyértelmű és szabványosított módot biztosítanak a weben található erőforrásokkal való interakcióhoz.
- GET: Ez a módszer egy erőforrás reprezentációjának lekérésére szolgál, például egy weboldal vagy egy adatrekord. A GET-kéréseknek biztonságosnak és hatékonynak kell lenniük, ami azt jelenti, hogy nem módosíthatják a lekért erőforrást, és nem járhatnak semmilyen mellékhatással.
- PUT: Ez a módszer egy erőforrás frissítésére vagy új reprezentációra való cseréjére szolgál. A PUT kérés törzse általában az erőforrás frissített reprezentációját tartalmazza, és a szerver lecseréli a meglévő erőforrást az új reprezentációra.
- TÖRLÉS: Ez a módszer egy erőforrás törlésére szolgál. A szervernek el kell távolítania az URL által azonosított erőforrást a rendszerből, és csak akkor kell TÖRLÉS kérést küldeni, ha a kérelmező rendelkezik a megfelelő jogosultságokkal.	

## Hogyan néz ki egy "POST" kérés, ha webböngészőből készül (az előlapra írva)?	

    const data = {
        name: 'John Doe',
        email: 'johndoe@example.com',
        message: 'Hello, world!'
        };

        fetch('https://api.example.com/messages', {
          method: 'POST',
          headers: {
            'Content-Type': 'application/json'
          },
          body: JSON.stringify(data)
        })
        .then(response => response.json())
        .then(data => {
          console.log('Message sent successfully:', data);
        })
        .catch(error => {
          console.error('Error sending message:', error);
        });

- Ebben a példában POST-kérelmet küldünk a „https://api.example.com/messages” URL-címre, a JSON-adatokkal, amelyek egy nevet, e-mail-címet és üzenetet tartalmaznak.
- A fetch() metódus két argumentumot használ: a kérés URL-címét és egy opciós objektumot, amely tartalmazza a methodot, a headers és a kérés bodyt. A metódust 'POST'-ra állítottuk, hogy jelezzük, hogy adatokat szeretnénk küldeni a szervernek, a 'Content-Type' fejlécet pedig 'application/json' értékre állítottuk annak jelzésére, hogy a kérés törzse JSON-adatokat fog tartalmazni.
- Az adatobjektumot ezután a JSON.stringify() metódussal JSON-karakterláncsá alakítja a rendszer, és a kérés törzseként adja át.
- Miután a szerver válaszol, a válaszadatokat a json() metódussal JSON-ba konvertálja, és az adatokat a második then() metódussal kezeli. Ebben a példában egyszerűen naplózzuk a válaszadatokat a konzolra, ha az üzenet sikeresen elküldésre került, vagy naplózunk egy hibát, ha probléma merült fel az üzenet elküldésével.
- (Engedélyezés: Meghatározza azokat a hitelesítési adatokat, amelyeket az ügyfél az erőforrás eléréséhez használ.)
- (Content-Type: Megadja a kérés üzenet törzsében elküldött adatok formátumát.)  

## Mi az API?
- Az API (Application Programming Interface) protokollok, rutinok és eszközök halmaza szoftveralkalmazások készítéséhez.
- Szabványos módot biztosít a különböző szoftveralkalmazások számára az egymással való kommunikációra és adatcserére, függetlenül a használt programozási nyelvtől, operációs rendszertől vagy platformtól.
- Az API-k meghatározzák, hogy a szoftver összetevői hogyan hatnak egymásra, beleértve a köztük lévő kéréseket és válaszokat. Lehetővé teszik a fejlesztők számára olyan szoftveralkalmazások létrehozását, amelyek képesek kihasználni más szoftverszolgáltatások funkcionalitását vagy adatait anélkül, hogy ismerniük kellene a szolgáltatások belső működésének részleteit.
- Az API-k lehetővé teszik, hogy terméke vagy szolgáltatása kommunikáljon más termékekkel és szolgáltatásokkal anélkül, hogy tudná, hogyan valósították meg őket. Ez leegyszerűsítheti az alkalmazásfejlesztést, időt és pénzt takaríthat meg.  

## Mi az a REST API?  
- Az API jelentése Application Programming Interface, amely egy általános kifejezés olyan protokollok, rutinok és eszközök leírására, amelyek lehetővé teszik a különböző szoftveralkalmazások egymás közötti kommunikációját. Az API-k különböző protokollokat használhatnak a kommunikációhoz, például a SOAP-ot, az XML-RPC-t és a JSON-RPC-t.
- A REST (Representational State Transfer) API ezzel szemben az API egy speciális típusa, amely HTTP protokollokat használ a kommunikációhoz. A RESTful API-k egységes műveletkészletet használnak (például GET, POST, PUT, DELETE és PATCH) az erőforrások manipulálására, és állapot nélküliek és gyorsítótárazhatók.
- A RESTful alapelvek irányelvek és megszorítások a REST architektúra stílusát használó webszolgáltatások tervezésére vonatkozóan. Ezek az elvek segítenek abban, hogy a webszolgáltatás egyszerű, méretezhető és könnyen használható legyen. A RESTful API tervezésének fő elvei a következők:  
1. Erőforrás azonosítás: Az erőforrásokat egyedi URI-kkal (Uniform Resource Identifiers) kell azonosítani.  
2. Erőforrás-manipuláció reprezentációk segítségével: Az ügyfeleknek úgy kell manipulálniuk az erőforrásokat, hogy reprezentációkat küldenek a kiszolgálónak.  
3. Önleíró üzenetek: A kliensek és a szerverek között küldött üzeneteknek önleíró jellegűnek kell lenniük, és tartalmazniuk kell az üzenet feldolgozásához szükséges összes információt.  
4. A hipermédia, mint az alkalmazás állapotának motorja (HATEOAS): A szervertől érkező válaszoknak tartalmazniuk kell a kapcsolódó erőforrásokra mutató hivatkozásokat, amelyek lehetővé teszik az ügyfelek számára az alkalmazásban való navigálást.  
5. Állapot nélküli interakció: Minden ügyféltől érkező kérésnek tartalmaznia kell a kérés teljesítéséhez szükséges összes információt anélkül, hogy a szervernek munkamenet-információkat kellene tárolnia.  

## Mi az a JSON, és hogyan használjuk?  
- A JSON (JavaScript Object Notation) egy könnyű adatcsere-formátum, amely könnyen olvasható és írható az emberek számára, a gépek pedig könnyen értelmezhetők és generálhatók. Ez egy szöveges formátum, amely a JavaScript objektumliterálokhoz hasonló szintaxist használ, így népszerűvé teszi a webszolgáltatások és az ügyféloldali alkalmazások közötti adatcserében.
- A JSON-adatok kulcs-érték párokból állnak, amelyekben a kulcsok idézőjelben vannak, az értékek pedig karakterlánc, szám, logikai érték, nulla, tömb vagy objektum.
- A JSON egy népszerű és rugalmas formátum a különböző rendszerek és programozási nyelvek közötti adatcseréhez.
- A JavaScriptben a JSON objektumot használhatja a JSON adatok kódolására és dekódolására:

        // JavaScript-objektum szerializálása JSON-karakterláncra
        const data = {név: "John Doe", életkor: 35, e-mail: "john.doe@example.com"};
        const json_string = JSON.stringify(data);

        // JSON karakterlánc deszerializálása JavaScript objektummá
        const data = JSON.parse(json_string);
        console.log(data.name); // Kimenet: John Doe  

## Mi az API verziószámítás?  
- Az API verziószámítása az API módosításainak kezelésének gyakorlata, és biztosítja, hogy ezek a változtatások az ügyfelek megzavarása nélkül történjenek. A jó API-verziókezelési stratégia egyértelműen kommunikálja a végrehajtott változtatásokat, és lehetővé teszi az API-fogyasztók számára, hogy saját tempójukban döntsenek, mikor frissítsenek a legújabb verzióra.
- Az API fejlődésével új funkciókat lehet hozzáadni, és a meglévő funkciókat módosítani vagy eltávolítani lehet. Ha ezeket a változtatásokat nem kezelik körültekintően, megszakíthatják azokat a meglévő ügyfeleket, amelyek az API korábbi viselkedésére támaszkodnak. Az API verziószámítása segít enyhíteni ezt a problémát azáltal, hogy lehetőséget biztosít az API különböző verzióinak kezelésére, és lehetővé teszi az ügyfelek számára, hogy meghatározzák, melyik verziót kívánják használni.  

## Mondjon 3 példát HTTP válasz állapotkódokra? Magyarázza el, mit jelentenek az egyes számok!	
  - 201 Létrehozva : A kérés sikeres volt, és ennek eredményeként új erőforrás jött létre. Ez általában a POST után küldött válasz
  - 429 Túl sok kérés : A felhasználó túl sok kérést küldött egy adott időn belül ("sebességkorlátozás").
  - 200 OK: Ez a válasz állapotkód azt jelzi, hogy a kérés sikeres volt, és a szerver visszaküldte a kért adatokat a válasz törzsében. Ez a sikeres HTTP-kérések leggyakoribb állapotkódja.
  - 404 Nem található: Ez a válasz állapotkód azt jelzi, hogy a kért erőforrás nem található a szerveren. Ez akkor fordulhat elő, ha az URL helytelen, az erőforrást eltávolították, vagy a felhasználó nem rendelkezik az erőforrás eléréséhez szükséges engedélyekkel.
  - 500 Belső szerverhiba: Ez a válaszállapotkód azt jelzi, hogy a kiszolgáló olyan váratlan körülménybe ütközött, amely megakadályozta a kérés teljesítésében. Ez történhet szoftverhiba, hibás konfiguráció vagy a szerver infrastruktúrájával kapcsolatos probléma miatt.
- Minden HTTP-válasz állapotkód egy háromjegyű szám, amely a válaszfejlécben található, jelezve a kérés állapotát. Az első számjegy az állapotkód általános kategóriáját jelzi, a következő jelentésekkel:
  - 1xx (tájékoztató): A kérés beérkezett, és a szerver folytatja annak feldolgozását.
  - 2xx (Sikeres): A kérés sikeres volt, és a szerver visszaküldte a kért adatokat a választörzsben.
  - 3xx (átirányítás): A kérés teljesítéséhez további műveletekre van szükség, például egy átirányítás követésére.
  - 4xx (Ügyfélhiba): A kérést nem sikerült teljesíteni az ügyféloldali hiba, például érvénytelen kérelem vagy nem megfelelő engedélyek miatt.
  - 5xx (Szerverhiba): A kérést nem lehetett teljesíteni egy szerveroldali hiba, például váratlan állapot vagy infrastrukturális probléma miatt.	
## Hogyan néz ki a "ternary" a javascriptben?	
- Az if-else állítások gyorsírása. A következő szintaxissal rendelkezik:	

      feltétel ? kifejezésIfTrue : kifejezésIfFalse	

- A feltétel logikai értékre kerül kiértékelésre, és ha igaz, akkor azIfTrue kifejezés végrehajtásra kerül. Ha a feltétel hamis, akkor helyette azIfFalse kifejezés kerül végrehajtásra.	
## Hogyan importálhatunk függvényt egy másik modulból JavaScriptben?
- használhatja az import utasítást

      import { myFunction } innen: './myModule.js';	

- Ebben a példában a myFunction fájlt egy myModule.js nevű fájlból importáljuk ugyanabban a könyvtárban. A kapcsos kapcsos zárójelek {} azt jelzik, hogy egy elnevezett exportot importálunk a modulból.
- Ha a modulnak van alapértelmezett exportálása, akkor azt a kapcsos zárójelek nélkül importálhatja, így:

      import myFunction innen: './myModule.js';

- Itt a myModule alapértelmezett exportját importáljuk, amely a myFunction változóhoz van hozzárendelve.
- Vegye figyelembe, hogy a .js fájlkiterjesztés szükséges az importálási utasításban, és a fájl elérési útjának relatívnak kell lennie az aktuális fájlhoz képest. Ezenkívül fontos megbizonyosodni arról, hogy a modult a megfelelő szintaxissal exportálta, mielőtt megpróbálná egy másik modulba importálni.	

## Mi az a shallow copy egy objektumon?	
- egy új objektum, amely ugyanazokkal a tulajdonságokkal rendelkezik, mint az eredeti objektum, de ezeknek a tulajdonságoknak az értékei ugyanazokra az objektumokra vonatkoznak, mint az eredeti
- az új objektum ugyanazokkal a tulajdonságokkal rendelkezik, mint az eredeti objektum, de ezen tulajdonságok értékei nem kerülnek másolásra, csak hivatkoznak rájuk.
- Egy objektum sekély másolatának létrehozásához használhatja a spread operátort ... vagy az Object.assign() metódust. Íme egy példa:

  	  const eredeti = { a: 1, b: 2, c: { d: 3 } };
  	  const copy = { ...eredeti };
      // vagy: const copy = Object.assign({}, original);

- Ha módosítjuk az eredeti c tulajdonságát, akkor a másolat c tulajdonsága is hatással lesz, mert ugyanarra az objektumra hivatkoznak:

      eredeti.c.d = 4;
      console.log(copy.c.d); // Kimenet: 4
  
- Amikor frissíti az állapotot a React alkalmazásban, fontos, hogy hozzon létre egy új objektumot, amely a frissített állapotot képviseli. Ennek az az oka, hogy a React egy sekély összehasonlítást használ annak meghatározására, hogy az állapot megváltozott-e, és ha az állapot nem változott, akkor nem váltja ki az újbóli megjelenítést.
- Ha az állapotot ugyanazzal az objektumhivatkozással frissíti, a React nem észleli a változást, és nem indítja el az újbóli megjelenítést. Ez váratlan viselkedéshez vezethet az alkalmazásban.
- A probléma elkerülése érdekében fontos egy új objektum hivatkozás létrehozása az állapot frissítése során. Egy sekély másolat egyszerű módja ennek elérésére, mivel új objektumot hoz létre, amely ugyanazokkal a tulajdonságokkal rendelkezik, mint az eredeti objektum. Amikor frissíti az állapotot az új objektumhivatkozás használatával, a React észleli a változást, és újrarenderelést indít el.

      import { useState } from 'react';

      function MyComponent() {
        const [személy, setPerson] = useState({ név: 'János', életkor: 30 });

        function handleClick() {
          // hozzon létre egy új objektumot, amely a személy sekély másolata
          const updatedPerson = { ...személy };
          // frissíti az új objektum age tulajdonságát
          updatedPerson.age = 31;
          // az állapot frissítése az új objektum hivatkozással
          setPerson(updatedPerson);
        }

        Visszatérés (
          <div>
            <p>Név: {person.name}</p>
            <p>Kor: {person.age}</p>
            <button onClick={handleClick}>Kor frissítése</button>
          </div>
        );
      }

## Mi az a callabck function? Mondjon néhány példát a használatára.	
- egy függvény, amelyet argumentumként adnak át egy másik függvénynek, és a függvényen belül hívják meg
- A callback function célja, hogy lehetővé tegye az aszinkron vagy eseményvezérelt programozást
1. Eseményfigyelők: megadhat egy callback functiont, amelyet az esemény bekövetkeztekor hív meg, eseményfigyelőt adhat hozzá egy gombhoz, és megadhat egy callback functiont, amely a gombra kattintáskor hívódik meg.
2. Tömb módszerek: leképezés, szűrés és redukálás, egy callback functiont vegyen argumentumként, amely a tömb minden eleméhez meghívódik
3. Aszinkron függvények: általában a callback functiont veszik argumentumnak, amely a függvény befejezésekor kerül meghívásra. Például a setTimeout függvény egy callback functiont és egy időkésleltetést vesz fel argumentumként

## Mi az ovject destructing a javascriptben?

 Az object destructing a JavaScript olyan funkciója, amely lehetővé teszi az objektumok tulajdonságainak kinyerését és változókhoz rendelését, így kényelmesebb és olvashatóbb az objektumokkal való munka. Gyakran használják a React-ban, amikor tulajdonságokat nyer ki az összetevők kellékeiből, és hasznos a függvényparaméterekben is.

Mi az a array destructing a javascriptben?

Az array destructing a JavaScript egyik hatékony funkciója, amely lehetővé teszi elemek tömbből való kinyerését és változókhoz rendelését, így kényelmesebb és olvashatóbb a tömbökkel végzett munka. Gyakran használják, amikor függvényekből visszaadott értékekkel dolgozunk, és hasznos a függvényparaméterekben is.

Mi az a spread operátor a "js"-ben?
- a spread operátort három pont jelöli (...)
- Ha tömbökkel használják, a spread operátor lehetővé teszi a tömb egyedi elemekre történő kibontását. Például:

      const myArray = [1, 2, 3];
      console.log(...myArray); // kimenet: 1 2 3

- A spread operátor tömbök összefűzésére is használható:

      const tömb1 = [1, 2, 3];
      const tömb2 = [4, 5, 6];
      const concatenatedArray = [...tömb1, ...tömb2];
      console.log(concatenatedArray); // kimenet: [1, 2, 3, 4, 5, 6]

- Objektumokkal együtt használva a spread operátor lehetővé teszi új objektumok létrehozását a meglévő objektumok tulajdonságainak összevonásával:

      const obj1 = { a: 1, b: 2 };
      const obj2 = { c: 3, d: 4 };
      const mergedObj = { ...obj1, ...obj2 };
      console.log(mergedObj); // kimenet: { a: 1, b: 2, c: 3, d: 4 }

- A spread operátor használható tömbök és objektumok sekély másolatainak létrehozására is:

      const originalArray = [1, 2, 3];
      const copyOfArray = [...originalArray];
      console.log(copyOfArray); // kimenet: [1, 2, 3]

      const originalObj = { a: 1, b: 2 };
      const copyOfObj = { ...eredeti objektum };
      console.log(copyOfObj); // kimenet: { a: 1, b: 2 }

Mi a különbség a "nyíl" függvény és a normál "függvény" között?
- Szintaxis: A nyíl függvény szintaxisa tömörebb, mint a normál függvény szintaxisa. A nyílfüggvények deklarálása a függvény paraméterei és a függvény törzse közötti nyíl (=>) használatával történik, míg a normál függvény a függvény kulcsszót használja, ezt követi a függvény neve, a paraméterek zárójelben, a függvénytörzs pedig kapcsos zárójelben.
- Visszatérési érték: Nyílfüggvényben, ha a függvény törzse egyetlen kifejezés, akkor a kifejezés automatikusan visszaadásra kerül. Egy normál függvényben a return kulcsszót kell használnia egy érték kifejezett visszaadásához.

      // szabályos függvény
      függvény add(a, b) {
        return a + b;
      }

      // nyíl függvény
      const add = (a, b) => a + b;

Mire használják az "import" kulcsszót?

- funkcionalitás importálása más modulokból, amelyek az aktuális modulban használhatók
- Az importálás használatakor lényegében azt utasítja a böngészőnek vagy a Node.js környezetnek, hogy töltse be a megadott modult, és tegye elérhetővé az exportált funkcióit az aktuális modul számára

      // a math.js fájlban
      függvény exportálása add(a, b) {
        return a + b;
      }

      // a main.js fájlban
      import { add } innen: './math.js';

      console.log(add(1, 2)); // kimenet: 3

- Az import utasítás importálhatja az összes exportált értéket egy modulból a * szintaxis használatával:

      import * matematikaként a './math.js' fájlból;

      console.log(math.add(1, 2)); // kimenet: 3

- Érdemes megjegyezni, hogy az import utasítások csak modulszkriptekben használhatók, amelyek JavaScript fájlok, amelyek a type="module" attribútumot használják a < script > címkéjükben. Ezenkívül a modulrendszert nem támogatják a régebbi böngészők és a Node.js verziói, ezért fontos, hogy ellenőrizze a kompatibilitást, mielőtt importálást használna a kódban.

Mire használják a "required"-et?
A NodeJS-ben a request() egy beépített függvény, amely külön fájlokban létező külső modulokat foglal magában. A request() utasítás alapvetően beolvas egy JavaScript fájlt, végrehajtja azt, majd visszaadja az export objektumot. A request() utasítás nemcsak beépített mag NodeJS modulok hozzáadását teszi lehetővé, hanem közösségi alapú és helyi modulok hozzáadását is.

Mik azok a template literatorok?

A template literatorok backtick (`) karakterekkel elválasztott literálok, amelyek lehetővé teszik többsoros karakterláncok használatát, karakterlánc-interpolációt beágyazott kifejezésekkel és speciális konstrukciókat, amelyeket címkézett sablonoknak neveznek.

Milyen előnyökkel jár a fejlesztő számára a "komponensek" használata (ellentétben azzal, hogy az összes kódot egyetlen fájlba írják)?
- Könnyebb megérteni őket
- Az komponensek könnyen újrafelhasználhatók és módosíthatók
- Egyszerre több ember is dolgozhat különböző komponenseken

Mi a különbség az elem és a komponens között?
- Az elem egy egyszerű JavaScript-objektum, amely egy komponenspéldányt vagy HTML-címkét és annak tulajdonságait írja le, míg a komponens egy függvény vagy osztály, amely egy elemet ad vissza.
- Az elem annak leírása, amit renderelni szeretne, míg a komponens a leírást létrehozó és megjelenítő kód.
- Az elemek megváltoztathatatlan objektumok, míg a komponensek olyan függvények vagy osztályok, amelyek propsokat vehetnek fel, és ezeken a bemeneteken alapuló új elemet állíthatnak vissza és visszaadhatnak.


      // Element
      const element = <div>Hello, World!</div>;

      // Component
      function Greeting() {
        return <div>Hello, World!</div>;
      }f

Hogyan adja át az értékeket a komponensek között a "react"-ban?

A propsok egy React komponens bemenetei. Ezek egy szülőkomponenstől egy utódkomponenshez továbbított adatok. Ezeket egy tulajdonságobjektumba (props) gyűjtik össze, amelyet aztán első argumentumként átadnak a komponens függvénynek. A propsok csak olvashatóak

Mi az a "kulcs" prop?

Egy propsra van szükség, ha egy tömbből elemeket hoz létre. A propsnak minden elemhez egyedinek kell lennie (lehetőleg nem az indexnek). Segít a Reactnak nyomon követni az elemeket a DOM-ban, ha például a sorrend megváltozik.

	
1. Határozzon meg egy eseménykezelő függvényt a szülőkomponensben, és adja át tulajdonságként a gyermekkomponensnek. Az eseménykezelő függvény a gyermekkomponensben kerül meghívásra, és elfogad egy argumentumot, amely a gyermekkomponens adata.

2. Határozzon meg egy állapotot a szülőkomponensben, és adja át a gyermekkomponensnek tulajdonságként. Amikor az állapot be van állítva a gyermekkomponensben, akkor a szülőkomponensben is be lesz állítva. Ezt állapotemelésnek hívják.

Írja be a kódot egy HTML DIV elem létrehozásához a JSX-ben, amelynek innerTextje a `let name = 'Andrew'' változó tartalma.

let name = 'Andrew';

const myDiv = <div>{name}</div>

Írja be a kódot, hogy a JSX-ben egy rendezetlen listát hozzon létre a `let names = ["Mathew", "John", "Maverik"] tömbből

    let names = ["Mathew", "John", "Maverik"];

    const nameList = (
    <ul>
    {names.map((name,index) => (
      <li key={index}>{name}</li>
    ))}
    </ul>
    );

Írja be a kódot, hogy beállítsa egy div háttérszínét JSX-ben.

    import React from 'react';

    function App() {
      return (
        < div style={{ backgroundColor: 'red' }}>
          Hello, World!
        </ div>
      );
    }

    export default App;

## Real DOM	

Amikor egy felhasználó weboldalt kér, a böngésző egy HTML-dokumentumot kap az adott oldalhoz a szervertől. A böngésző ezután egy logikai, faszerű struktúrát hoz létre a HTML-ből, hogy megjelenítse a felhasználónak a kért oldalt a kliensben.

Ezt a faszerű szerkezetet Document Object Model-nek, más néven DOM-nak nevezik. Ez a webdokumentum csomópontok és objektumok szerkezeti ábrázolása.

## Virtuális DOM	

A Reactban minden DOM objektumhoz tartozik egy megfelelő „virtuális DOM objektum”. A virtuális DOM-objektum egy DOM-objektum reprezentációja, mint egy könnyű másolat.

A React először létrehoz egy virtuális DOM-fát, ahol nyomon követi az összes információt, például, hogy az egyes elemek mely összetevőkhöz tartoznak. Ezután ezt a virtuális fát fogja használni a tényleges, valós DOM-fa létrehozásához, amely megjelenik a böngészőben, és csak a fa megjelenítéséhez szükséges információkat tartja meg.
A virtuális DOM egy webfejlesztési koncepció, ami egy memóriában lévő fastruktúrát használ a weboldal vagy felhasználói felület reprezentálására. Ez a fa az aktuális DOM és a fejlesztők által írt kód közötti köztes lépés, amelyet a React és más keretrendszerek használnak a gyorsabb és hatékonyabb felhasználói felületek készítéséhez. A virtuális DOM az aktuális DOM frissítését minimalizálja, ami teljesítményjavulást eredményez.

Amikor egy JSX elemet renderel, a teljes Virtuális DOM objektum frissül. Ezután a React összehasonlítja a virtuális DOM-ot egy virtuális DOM-pillanatfelvétellel, amely közvetlenül a frissítés előtt készült, meghatározza, hogy melyik elemet módosították, és csak azt az elemet frissíti a valódi DOM-on. Ez az egyik módszer, amelyet a virtuális DOM alkalmaz a teljesítmény optimalizálására.

Amikor egy elemet ad hozzá egy tömbhöz, miért szükséges egy új tömböt átadni a "useState" hook-nak?

- A React alkalmazásban, ha frissíteni szeretné egy componenesek állapotát, általában a useState hookot használja. Ha tömbökkel dolgozik, új tömböt kell átadnia a useState hook-nak, amikor egy elemet szeretne hozzáadni a tömbhöz, mivel a React referenciaegyenlőséget használ annak meghatározására, hogy az állapot megváltozott-e.
- Amikor egy új tömböt ad át a useState hook-nak, a React összehasonlítja az új tömböt az előzővel a hivatkozási egyenlőség használatával. Ha az új tömb eltér az előzőtől, a React tudja, hogy az állapot megváltozott, és elindítja a komponens újbóli megjelenítését.
- Ha közvetlenül módosítja a meglévő tömböt, és átadja a useState hook-nak, akkor előfordulhat, hogy a React nem ismeri fel a változást, mert a tömbhivatkozás nem változott. Ez váratlan viselkedéshez és hibákhoz vezethet a kódban.
- Ha egy elemet szeretne hozzáadni egy tömbhöz a useState hook segítségével, akkor a spread operátorral létrehozhat egy új tömböt az eredeti elemekkel és a hozzá adott új elemmel, így:

      const [elemek, setItems] = useState(['elem1', 'elem2']);
	
      const addItem = (newItem) => {
        setItems([...elemek, newItem]);

Írja le, milyen technikákat vagy eszközöket használ a react alkalmazás hibakeresésére.

- console.log()
- A böngészők hibakeresője

## Mi a különbség a react "osztály" komponens és a "funkcionális" komponens között?

- Az osztály componensek ES6 osztályokkal vannak meghatározva, és kiterjesztik a React.Component osztályt. Render() metódusuk van, amely visszaadja az oldalon megjelenítendő JSX-et. Az osztály componensek hozzáférhetnek a componens életciklus metódusaihoz is, mint például a componentDidMount() és a componentDidUpdate(), amelyek lehetővé teszik a műveletek végrehajtását az összetevő felcsatolásakor vagy frissítésekor.
- A funkcionális komponenseket viszont JavaScript függvény segítségével határozzuk meg. Első érvként kellékeket kapnak, és visszaküldik az oldalon megjelenítendő JSX-et. Nem férnek hozzá a componens életciklus metódusaihoz vagy a this kulcsszóhoz, ami azt jelenti, hogy egyszerűbbek és könnyebbek lehetnek, mint az osztálykomponensek.
- különbségek:
  1. Szintaxis: Az osztálykomponensek meghatározása a class kulcsszóval történik, és a React.Component kiterjesztése, míg a funkcionális komponensek JavaScript-függvénnyel definiálhatók.
  2. Állapot: Az osztály componenesek hozzáférnek a statehez, és módosíthatják azt a this.setState() segítségével, míg a funkcionális összetevőknek nincs állapotuk.
  3. Életciklus metódusok: Az osztály componensei hozzáférhetnek a componenes életciklus metódusaihoz, például a componentDidMount(), a componentDidUpdate() és a componentWillUnmount(), míg a funkcionális összetevők nem.
  4. Teljesítmény: A funkcionális componenesek általában könnyebbek, mint az osztályba tartozó componensek, és bizonyos esetekben jobb teljesítményt nyújtanak.

Nevezzen meg 3 életciklus-állapotot egy reagáló "funkcionális" komponensben.

- Mounting - elem kerül hozzáadásra a DOM-hoz
- Updating - elem változások
- Unmounting – az elem eltávolításra kerül a DOM-ból

Mi az a conditional rendering a `react`-ban? Adj egy példát.

Conditional renderinggel csak akkor vehet fel egy elemet a DOM-fához, ha egy bizonyos feltétel teljesül.

    Visszatérés (
    <div>
      {somethingThatsTrueOrFalse && <p>Rendelve!</p>}
    </div>
    )

# Írja be azt a kódot, amely kinyomtatja a konzolra "componenet destroyed", amikor az összetevő, amelynek része, eltávolításra kerül a DOM-fából.	

    import { useEffect } from 'react';

    function MyComponent() {
    useEffect(() => {
    return () => console.log("component destroyed");
    }, []);
    return <div>My Component</div>;
    }

Miért van ebben a kódban végtelen ciklus?

    function App() {
    const [count, setCount] = useState(0); //initial value of this 
    useEffect(() => {
    setCount((count) => count + 1); //increment this Hook
    }); //no dependency array.
    return (
    <div className="App">
      <p> value of count: {count} </p>
    </div>
    );
    }

Ebben a kódban van egy végtelen hurok, amelyet a useEffect hook okoz. Amikor az összetevőt először rendereli, a count állapotváltozó 0-ra van állítva. A useEffect hook ezután meghívásra kerül, és azon belül a setCount függvény a számláló változó növeléséhez. Mivel azonban nincs függőségi tömb a useEffect hook számára, az a komponens minden renderelésén futni fog, beleértve az effektuson belüli setCount függvény által okozott újramegjelenítéseket is.

Ez egy végtelen hurkot hoz létre, ahol a komponens folyamatosan újrarenderelődik, és a számlálási állapot változó folyamatosan növekszik. A képernyőn megjelenő számérték nem változik, és az összetevő nem tudja befejezni az életciklusát.

A probléma kijavításához egy függőségi tömböt kell átadni a useEffect-nek, amely tartalmazza a count értékét, hogy csak akkor fusson le, ha a számérték megváltozik.	

## Mi az adatbázisséma?	

A séma kulcs-érték párokat tartalmazó objektum. A kulcsok a dokumentum azonos nevű mezőinek felelnek meg. Az értékek tartalmazzák az adattípust (pl. String, Number, Boolean...) és egyéb opcionális tulajdonságokat, például kötelezőt, vagy egy alapértelmezett értéket. Ha az adattípuson kívül más paramétereket is megadunk, akkor az értékekben beágyazott objektumokat használunk.

Example:	

    const BlogSchema = new Schema({
    title:  {type: String, required: true }, // required means title must be entered
    author: String, // String is shorthand for {type: String}
    body:   String,
    comments: [{ body: String, date: Date }],
    date: { type: Date, default: Date.now },
    });

# Miért egyedi az "id" egy adatbázisban?	

Mert akkor a dokumentumok azonosíthatók egy rájuk jellemző tulajdonság alapján. Amikor új dokumentumot hoz létre, a Mongoose automatikusan hozzáad egy egyedi „_id” tulajdonságot a dokumentumhoz.

Mik az előnyei és hátrányai a `lean()` függvény mongo lekérdezésben való használatának?

A Mongoose dokumentumok egy-egy leképezést jelentenek a MongoDB-ben tárolt dokumentumokhoz. Minden dokumentum a Modelljének egy példánya. Alapértelmezés szerint a Mongoose lekérdezések a Mongoose Document osztály egy példányát adják vissza. A dokumentumok sokkal nehezebbek, mint a vanília JavaScript objektumok, mivel sok belső állapotuk van a változáskövetéshez.

A "lean()" függvény arra utasítja a Mongoose-t, hogy hagyja ki a teljes Mongoose-dokumentum példányosítását, és csak egy egyszerű JavaScript-objektumot adjon meg.

    const docs = await Model.find().lean();

    Előnyök: A JS-objektumok kisebbek, mint egy Mongoose-dokumentumok, és gyorsabban kezelhetők.

    Hátrányok: A JS objektumok már nem kapcsolódnak a MongoDB-hez, így nem használhatók a DB manipulálására.	

Írja be a kódot a `{name: "Andrew", age: 10}` objektum mongo adatbázisban való tárolására. A csatlakozási paraméterek részét figyelmen kívül hagyhatja.

    async function main() {
    // method 1
    const dbUser = new User({name: "Andrew", age: 10});
    dbUser.save();
    // method 2
    await User.create({name: "Andrew", age: 10});
    };
    main();

# Write the code to delete from a mongo database all employees that are over 18 years. The scheme for an employee is `{name: string, age: int}`. You can ignore the part of connection parameters.	

    const mongoose = require('mongoose');

    // Define the schema for the data you want to store
    const EmployeeSchema = new mongoose.Schema({
      name: String,
      age: Number,
    });

    // Create a model based on the schema
    const Employee = mongoose.model('Employee', EmployeeSchema);

    // Connect to the MongoDB database
    mongoose.connect('mongodb://localhost/my_database');

    // Delete all employees over 18 years old
    Employee.deleteMany({ age: { $gt: 18 } }, (err, result) => {
      if (err) {
        console.error(err);
      } else {
        // log the number of employees that were deleted
        console.log(`${result.deletedCount} employees deleted from database`);
      }
    });


Írja be a kódot, amely a 18 éven felüli alkalmazottak mongo adatbázisából jelenik meg a konzolban. Az alkalmazott séma a következő: `{név: string, életkor: int}. A csatlakozási paraméterek részét figyelmen kívül hagyhatja.

	async function main() {
  	console.log( await Employee.find({ age: { $gt: 18 } }));
	};

	main();

Írja be a kódot a mongo adatbázisból a name='János' alkalmazottak frissítéséhez, és állítsa be az új életkort 8-ra. Az alkalmazott séma `{name: string, age: int}`. A csatlakozási paraméterek részét figyelmen kívül hagyhatja.

 	const mongoose = require('mongoose');

    // Define the schema for the data you want to store
    const EmployeeSchema = new mongoose.Schema({
      name: String,
      age: Number,
    });

    // Create a model based on the schema
    const Employee = mongoose.model('Employee', EmployeeSchema);

    // Connect to the MongoDB database
    mongoose.connect('mongodb://localhost/my_database', { useNewUrlParser: true, useUnifiedTopology: true });

    // Update all employees with name='John' to have age=8
    Employee.updateMany({ name: 'John' }, { age: 8 }, (err, result) => {
      if (err) {
        console.error(err);
      } else {
        console.log(`Updated ${result.nModified} employees`);
      }
    });

# Mit jelent a "MERN" a webfejlesztéssel összefüggésben?	

- `M`ongoDB - dokumentum adatbázis
- `E`xpress - webszerver keretrendszer
- `R`eact - frontend JS keretrendszer
- `N`ode - JS webszerver

# Mi a routing a „react” alkalmazás kontextusában?	
A "react" routing egy kliens oldali útválasztás, ami azt jelenti, hogy különböző oldalakat jeleníthet meg az URL alapján anélkül, hogy kérést küldene a szervernek

Mi az routing az "expressz" alkalmazás kontextusában?
Az „expresszben” történő routing azt jelenti, hogy a szerver a kérés URL-je és metódusa alapján különböző műveleteket fog futtatni, amelyek eltérő válaszokat eredményeznek


Mi az a „CORS” szabályzat?
`C`ross-`O`rigin `R`esource Az `S`haring egy házirend, amely eldönti, hogy a böngésző hozzáférhet-e a webhely forrásától eltérő szerver erőforrásaihoz vagy sem.
CORS, vagyis "Cross-Origin Resource Sharing", röviden egy biztonsági mechanizmus a webböngészőkben. A CORS lehetővé teszi vagy korlátozza, hogy egy weboldal egyik erőforrása (pl. JavaScript kód) lekérdezhet-e vagy módosíthat-e erőforrásokat egy másik eredeti (domain) webhelyről. Ez segít megakadályozni, hogy potenciálisan biztonsági kockázatokat jelentő kód hozzáférjen és manipulálja más webhelyek erőforrásait.

# Milyen előnyei vannak a fejlesztőnek a "bootstrap" vagy a "material ui" használatából?	
A Bootstrap vagy a Material UI használatával a fejlesztők időt takaríthatnak meg, javíthatják a felhasználói élményt, valamint könnyebben hozzáférhető és konzisztens webalkalmazásokat hozhatnak létre.
- Előre megtervezett UI összetevők: Mind a Bootstrap, mind a Material UI előre megtervezett UI összetevők széles skáláját kínálja, például gombokat, űrlapokat, menüket, kártyákat és egyebeket, amelyek egyszerűen testreszabhatók és webalkalmazásba integrálhatók. Ez időt és erőfeszítést takarít meg a fejlesztőknek a felhasználói felület összetevőinek tervezése és megvalósítása során.
- Reszponzív kialakítás: Mind a Bootstrap, mind a Material UI a reszponzív webdizájn figyelembevételével készült, ami azt jelenti, hogy a felhasználói felület összetevői automatikusan alkalmazkodnak a különböző képernyőméretekhez és felbontásokhoz. Ez biztosítja, hogy az ezekkel a keretrendszerekkel épített webalkalmazások jól nézzenek ki, és minden eszközön könnyen használhatók legyenek, beleértve az asztali számítógépeket, táblagépeket és mobiltelefonokat is.
- Következetes tervezési nyelv: Mind a Bootstrap, mind a Material UI egységes tervezési nyelvet és vizuális stílust követ, ami megkönnyíti a fejlesztők számára, hogy összefüggő és konzisztens felhasználói felületet hozzanak létre webes alkalmazásaikhoz. Ez javíthatja a felhasználói élményt, és elősegítheti a felhasználók bizalmának és hitelességének kiépítését.
- Kisegítő lehetőségek: Mind a Bootstrap, mind a Material UI a kisegítő lehetőségeket szem előtt tartva készült, ami azt jelenti, hogy olyan funkciókat és bevált módszereket kínálnak, amelyek a webalkalmazásokat hozzáférhetőbbé teszik a fogyatékkal élő felhasználók számára. Ez magában foglalja a képernyőolvasók, a billentyűzetes navigáció és egyebek támogatását.
- Aktív fejlesztés és közösségi támogatás: Mind a Bootstrap, mind a Material UI aktív fejlesztés alatt áll, és nagy felhasználói és közreműködői közösségekkel rendelkezik. Ez azt jelenti, hogy a fejlesztők profitálhatnak a folyamatos fejlesztésekből, hibajavításokból és új funkciókból, valamint hozzáférést kaphatnak a többi felhasználótól és közreműködőtől származó támogatáshoz és erőforrásokhoz.


# Mi a variable shadowing Java Scriptben?	
A változó árnyékolás (variable shadowing) olyan helyzetet jelent JavaScriptben, amikor egy belső hatókörben (scope) azonos nevű változót deklarálunk, amely már létezik az általánosabb környező hatókörben. Ennek eredményeként a belső változó "árnyékot" vet a külső változóra, és a belső hatókörben lévő változó veszi át az ellenőrzést a külső változó felett. Ez lehet névütközés megelőzésére, valamint az adattípusok és értékek különböző kezelésére szolgál.

		let x = 10;
		
		function outerFunction() {
		  let x = 20; // Belső hatókörben azonos nevű változót hozunk létre
		  console.log(x); // Ez a változó árnyékolja a külső változót
		}
		
		outerFunction();
		console.log(x); // Külső hatókörben a külső változót használjuk
		
		// Kimenet:
		// 20
		// 10

A fenti példában a let x = 20; a belső hatókörben árnyékolja a külső x változót, így az outerFunction-ben használt x a belső változó értékét (20) fogja kiírni. A külső hatókörben a külső x változó értéke (10) marad érvényben.

Fontos megérteni, hogy a változó árnyékolás azt jelenti, hogy a belső változó maszkolja (azaz elfedi) a külső változót ugyanazzal a névvel. Ennek hatására a külső változó az adott hatókörön kívül továbbra is elérhető marad a kód többi részében.

A hoisting a JavaScript nyelv sajátossága, amelynek eredményeként a változók és a függvények deklarációjukat megelőzően is használhatók a kódban. Ennek a viselkedésnek az oka az, hogy a JavaScript motorok a kódot két lépésben dolgozzák fel: először a deklarációkat emelik fel (hoist), majd hajtják végre a kódot.

		Például:
		
		```javascript
		console.log(x); // Kimenet: undefined
		var x = 5;
		```

Ebben a példában a `var` kulcsszóval deklarált `x` változó deklarációja felemelkedik (hoisting) a kód elejére, így az értékét a `console.log` hívás előtt is deklarálják. Azonban az értéke csak a későbbi `var x = 5;` sorban lesz beállítva. Ezért a `console.log` kimenete `undefined` lesz.

A függvények esetében is hasonló hoisting történik:

		hoistingExample(); // Kimenet: "Hello, World!"
		
		function hoistingExample() {
		  console.log("Hello, World!");
		}

Itt a `hoistingExample` függvény definíciója is felemelkedik a kód elejére, így azt a hívás előtt használhatjuk.

Fontos megjegyezni, hogy a hoisting csak a változók és a függvények deklarációira vonatkozik, és nem az értékeikre. Emiatt a változók értékei csak a deklarációt követően lesznek beállítva. A modern JavaScript ajánlott használni a `let` és `const` kulcsszavakat a változók deklarálásához, mivel ezeknél a kulcsszavaknál a hoisting másképp viselkedik, és elkerülhetők a nem várt viselkedések.
--------------------------------------------------------------------------------------------------------

# Miért nem használjuk már a var-t Java Sriptben ?	
A `var` kulcsszó használata JavaScriptben a modern JavaScript fejlesztők körében egyre ritkábbá vált, és helyettük gyakran a `let` és `const` kulcsszavakat használják. Az alábbi okok miatt ajánlott a `var` kerülése és inkább a `let` és `const` használata:

1. Hatókör (scope) kezelése: A `var` hatókör kezelése kiszámíthatatlan és gyakran hibákhoz vezethet. A `var` változók a teljes tartományukra, vagyis az egész funkcióra vonatkoznak, és nem korlátozódnak csak egy blokkra. Ez gyakran váratlan viselkedéshez vezethet, amikor a változók nem ott érvényesülnek, ahol elvárnánk. A `let` és `const` változók viszont blokk-szintű hatókört biztosítanak, ami kiszámíthatóbb és hibákat könnyebb elkerülni.

2. Hoisting problémák: A `var` változókat felemelik (hoist) a hatókör elejére, ami azt jelenti, hogy a változót használhatjuk még mielőtt deklaráltuk volna. Ez is gyakran váratlan viselkedéshez vezethet, mivel a változó már létezhet, de nincs inicializálva, ami hibához vezethet. A `let` és `const` változók ezt a viselkedést korlátozzák, és csak azt használják, amit deklaráltunk.

3. Konstans értékek: Ha egy változónak nem szabad megváltoznia, akkor a `const` használata ajánlott. A `var` és `let` lehetővé teszi a változó értékének módosítását, míg a `const` csak egyszer inicializált értéket fogad el, és nem engedi az érték megváltoztatását.

4. Jobb kódminőség: Az előbbiek miatt a `let` és `const` jobb kódminőséget eredményezhetnek, könnyebben olvasható és karbantartható kódot lehet velük írni.

Az alapvető gyakorlat az, hogy `var` helyett `let` és `const` használata javasolt a modern JavaScript fejlesztés során. Azonban fontos megjegyezni, hogy a `var` továbbra is támogatott és használható, különösen akkor, ha olyan kódhoz kell kapcsolódni, amit már korábban írtak, és amelyben `var` változókat használnak. Az új projektekben azonban erősen ajánlott a `let` és `const` használata a jobb kódminőség és a hibák elkerülése érdekében.
--------------------------------------------------------------------------------------------------------

# Beszélj a let const var változokrol(variable shadowing)?	
JavaScriptben a változók deklarálásához három különböző kulcsszót használhatunk: `let`, `const` és `var`. Ezek a kulcsszavak különböző hatókört, viselkedést és célokat szolgálnak. Itt van egy rövid összefoglaló mindegyikükről:

1. `let`:
   - A `let` kulcsszóval deklarált változók blokk-szintű hatókört (block scope) kapnak. Ez azt jelenti, hogy csak a deklaráló blokkban érhetők el.
   - A `let` változók értékét bármikor megváltoztathatjuk.
   - Használható akkor, amikor a változó értéke változhat a kód futása során.

Példa a `let` használatára:

		let x = 10;
		if (true) {
		  let x = 20; // A blokkon belüli x árnyékolja a külső x-et
		}
		console.log(x); // 10


2. `const`:
   - A `const` kulcsszóval deklarált változók szintén blokk-szintű hatókört kapnak.
   - A `const` változókat csak egyszer inicializálhatjuk, és az értéküket nem változtathatjuk meg később.
   - Használható akkor, amikor egy változó értéke nem változik a futás során.

Példa a `const` használatára:
	
	const pi = 3.14159;
	// pi = 3.14; // Hibát fog okozni, mert nem változtatható meg az értéke
3. `var`:
   - A `var` kulcsszóval deklarált változók funkció-szintű hatókört (function scope) kapnak, és nem blokk-szintű hatókört.
   - A `var` változók hoistingot alkalmaznak, ami azt jelenti, hogy a deklarációt a hatókör elejére emelik.
   - A `var` változók értékét bármikor megváltoztathatjuk.
   - A `var` használata a modern JavaScriptben kevésbé ajánlott, mivel a `let` és `const` kiszámíthatóbb és biztonságosabb működést nyújtanak.

Példa a `var` használatára:

	var y = 5;
	if (true) {
	  var y = 10; // A külső hatókörben lévő y értéke megváltozik
	}
	console.log(y); // 10

Összefoglalva, a `let` és `const` modernebb változódeklarációs módszerek, amelyek a hatókört és az értékek viselkedését pontosabban kezelik, míg a `var` régebbi és kevésbé ajánlott, mivel könnyen hibákat okozhat a blokk-szintű hatókör hiánya és a hoisting miatt. Az ajánlott gyakorlat az, hogy a `let` és `const` használatát részesítsük előnyben a JavaScript kódban.
--------------------------------------------------------------------------------------------------------

# Mi a http?	
Az HTTP (Hypertext Transfer Protocol) egy szabványos protokoll, amelyet az interneten használnak információk cseréjére és weboldalak kéréseinek, válaszainak továbbítására. Az HTTP a kliens-szerver modell alapján működik, ahol a kliens (általában egy webböngésző) kéréseket küld a szervernek, és a szerver válaszokat küld vissza a kérésekre.

Az HTTP alapvetően egy szöveges alapú protokoll, amely állapotszegény, ami azt jelenti, hogy az egyes kérések és válaszok függetlenek egymástól, és az HTTP maga nem tartalmazza a korábbi kérések és válaszok állapotát. Minden HTTP kérés és válasz tartalmazhat fejléceket és tartalmat. A fejlécek információkat szállítanak a kérés vagy válasz szemantikájáról, például a kéréstől várt tartalom típusáról vagy a válasz státuszáról.

Az HTTP alapvetően egy protokoll weboldalak lekérdezéséhez és megjelenítéséhez, de napjainkban számos továbbfejlesztett verziója és változata is létezik, például az HTTPS (HTTP Secure), amely biztonságosabb kapcsolatot kínál azáltal, hogy az adatok titkosítva továbbítják, valamint az SPDY és a HTTP/2, amelyek célja a teljesítmény javítása és a weboldalak gyorsabb betöltése.

HTTP egy alapvető protokoll az interneten, amely nélkül a weboldalak böngészése és az online kommunikáció szinte lehetetlen lenne. Az HTTP és annak változatai alapját képezik a modern webes alkalmazásoknak és a világháló működésének.
--------------------------------------------------------------------------------------------------------

# Mi az API ?	
Az API (Application Programming Interface) egy olyan szoftvert vagy szolgáltatást határoz meg, amely lehetővé teszi az alkalmazások számára, hogy kommunikáljanak egymással és más szoftverkomponensekkel. Az API-k általában meghatározzák, hogy milyen módon lehet kommunikálni egy adott alkalmazás vagy szolgáltatás funkcióival, milyen kéréseket és válaszokat fogadnak el, és milyen adatformátumokat használnak az információk cseréjére.

Az REST API (Representational State Transfer API) egy olyan típusú API, amely a REST architektúra elveire épül. A REST egy tervezési stílus, amelyet eredetileg a World Wide Web számára hoztak létre, de kiterjedt más alkalmazásokra is. Az REST API-k általában a következő fő jellemzőket mutatják:

1. Erőforrások: Az API által kezelt entitásokat (például adatokat vagy szolgáltatásokat) erőforrásokként azonosítják, és minden erőforrás egyedi URI-vel (Uniform Resource Identifier) azonosítható.

2. Állapot nélküliség: Az egyes kérések és válaszok állapota nem függ az előző kérésektől vagy válaszoktól. Minden kérés tartalmazza az összes szükséges információt a válasz elküldéséhez.

3. HTTP módszerek: Az HTTP protokoll által definiált kérések (GET, POST, PUT, DELETE, stb.) használata az erőforrások műveleteinek lekérdezésére és módosítására.

4. Reprózentáció: Az erőforrásokat általában különböző formátumokban (például JSON vagy XML) reprezentálják, és a kliensek kéréseikben megadhatják a preferált reprezentációs formátumot.

A REST API-k sokféle alkalmazásban használhatók, például webes alkalmazásokban, mobilalkalmazásokban, szerverek közötti kommunikációban és sok más helyen. Ezek lehetővé teszik az alkalmazások számára, hogy egyszerűen és hatékonyan kommunikáljanak más rendszerekkel, így adatok lekérdezését, frissítését és továbbítását is könnyűvé teszik.

Az REST API egyike az elterjedt API-tervezési stílusoknak, de más stílusok is léteznek, mint például a SOAP (Simple Object Access Protocol) vagy a GraphQL. Az alkalmazások céljától és igényeitől függően lehet választani a legmegfelelőbb API-stílusra.
--------------------------------------------------------------------------------------------------------

# Mi a külömbség az Array és a ArrayList között?	
Az Array és az ArrayList két különböző adatszerkezet, amelyek gyakran használtak a programozásban, de van néhány alapvető különbség közöttük:	

1. Nyelvi függőség:
   - Az Array JavaScriptben egy beépített adatszerkezet, amely lehetővé teszi azonos típusú elemek gyűjteményét. Az Array egy alapvető adattípus a JavaScriptben.
   - Az ArrayList a Java nyelv egy osztályának része, amely a Java Collection Framework részeként működik. Java nyelven használják.

2. Méret dinamika:
   - Az Array mérete állandó, és nem változtatható meg dinamikusan. Ha egy tömböt inicializálsz, azzal a mérettel rendelkezik, és nem változtathatod meg a tömb elemeinek számát.
   - Az ArrayList dinamikusan méretét változtathatja, amikor elemeket ad hozzá vagy távolít el belőle. Ez azt jelenti, hogy az ArrayList rugalmasabb és alkalmazkodóképesebb a változó méretű gyűjtemények kezeléséhez.

3. Típusbiztonság:
   - Az Array nem rendelkezik beépített típusbiztonsággal, tehát bármilyen típusú elemet hozzáadhatsz egy tömbhöz. Ez azt jelenti, hogy az Array tartalmazhat vegyes típusú elemeket is.
   - Az ArrayList a Java generikus típusai révén típusbiztonságot nyújt. Meghatározhatod, hogy milyen típusú elemeket tartalmazzon az ArrayList, és az ArrayList megakadályozza a nem megfelelő típusú elemek hozzáadását.

4. Nyelvi sajátosságok:
   - Az Array JavaScriptben gyakran használt adatszerkezet, és a nyelv része.
   - Az ArrayList a Java nyelven használt, és a Java Collection Framework része.

Példa JavaScript Array-re:

	let myArray = [1, 2, 3, 4, 5];


Példa Java ArrayList-re:

	import java.util.ArrayList;
	ArrayList<Integer> myList = new ArrayList<Integer>();
	myList.add(1);
	myList.add(2);
	myList.add(3);	


Az Array és az ArrayList különböző programozási nyelvekben használt adatszerkezetek, és különböző tulajdonságokkal rendelkeznek. Az Array a JavaScriptben alapvető, míg az ArrayList a Java nyelv osztályaként szolgál a gyűjtemények kezelésére. Az ArrayList gyakran használható a Java alkalmazásokban a változó méretű listák kezelésére, míg az Array gyakran használható a JavaScriptben.
--------------------------------------------------------------------------------------------------------

# Kod komplexitás?	
Időkomplexitás: Az időkomplexitás értékeli, hogy egy adott algoritmus vagy kód mennyi időt vesz igénybe a futási ideje során, az input méretétől függően. Az időkomplexitás számos jellemzőjét használják a programok teljesítményének értékeléséhez, például a nagy O jelölést, amely egyfajta absztrakt jelölés a futási idő növekedésének értékelésére a bemenet méretének függvényében. Az időkomplexitás célja az algoritmus hatékonyságának és gyorsaságának meghatározása.

Térkomplexitás: A térkomplexitás azt értékeli, hogy egy program vagy algoritmus mennyi memóriát használ a futása során, az input méretétől függően. A térkomplexitás értékelése fontos lehet, különösen korlátozott memóriával rendelkező környezetekben vagy eszközökön. A cél az, hogy a lehető legkevesebb memóriát használja fel a program vagy algoritmus.

konstans: pl amikro egy listábol az indexe alapján keressük ki az adott elemet. Ha tudjuk az elem indexet nem számít mennyi adatunk van a futási idő gyors lesz.

logaritmikus(logn):
pl bináris keresésnél amikor sorba vannak rendezve az elemek.

lineáris(n): pl egy maximum keresés vagy egy adott elem keresése a listában anélkül hogy tudnánk az indexét. A lista minden egyes elemén végig kell menni. A futási idő arányosan nől az adatmennyiséggel.

n logn: pl hányszor van valami

négyzetes(n2): pl 2 egymásba ágyazott for ciklus.

köbös(n3): pl 3 egymásba ágyazott for ciklus

exponenciális(2n)
--------------------------------------------------------------------------------------------------------

# Final kulcsszo?	
A `final` kulcsszó számos különböző kontextusban használható a Java programozási nyelvben, és megadja, hogy egy adott elem (változó, metódus vagy osztály) nem változtatható meg a futás során, vagy hogy adott esetben különleges tulajdonságokkal rendelkezik. Íme a `final` kulcsszó néhány gyakori felhasználása:	

1. Változók:
   - A `final` kulcsszóval jelölt változók értékét csak egyszer lehet inicializálni, és nem változtathatók meg utána. Ez hasznos, ha olyan változót szeretnénk létrehozni, aminek az értéke nem változik futás közben.

   Példa:

   ```java
   final int szam = 10;
   // szam = 20; // Hibát fog okozni, mert a final változó értékét nem lehet megváltoztatni.
   ```

2. Metódusok:
   - Ha egy metódust a `final` kulcsszóval jelölünk meg, akkor azt a metódust nem lehet felülírni egy leszármazott osztályban (a szubosztályokban).

   Példa:

   ```java
   class Szulo {
       final void metodus() {
           // Ezt a metódust nem lehet felülírni a leszármazott osztályban.
       }
   }
   ```

3. Osztályok:
   - Ha egy osztályt a `final` kulcsszóval jelölünk meg, akkor azt az osztályt nem lehet leszármaztatni. Az ilyen osztályokat nem lehet örökítési célokra használni.

   Példa:

   ```java
   final class ZaroOsztaly {
       // Ez az osztály nem leszármaztatható.
   }
   ```	

A `final` kulcsszó használata lehetővé teszi a programozónak, hogy szigorúbb ellenőrzést és garantált viselkedést érjen el a változók, metódusok és osztályok számára. Ezzel elkerülhetők a váratlan változtatások és hibák a kódban, valamint lehetőség nyílik a hatékonyabb optimalizációra is. A `final` kulcsszó alkalmazása azonban bizonyos rugalmasságot is elveszíthet, ezért fontos megfelelően megtervezni és használni a programban.	
--------------------------------------------------------------------------------------------------------

# Mi a jpa?-(orm és jdbc)			
Az adatbázis-kezelési technológiák, például JPA, ORM, JDBC és Hibernate, kulcsfontosságú szerepet játszanak a szoftverfejlesztés során, különösen a relációs adatbázisokkal való kommunikáció területén. Itt találsz egy átfogó vázlatot ezekről a fogalmakról és a kapcsolataikról:

1. **JDBC (Java Database Connectivity):**
   - A JDBC egy Java API (alkalmazásprogramozási interfész), amely lehetővé teszi a Java alkalmazások számára, hogy kapcsolódjanak és kommunikáljanak relációs adatbázisokkal.
   - JDBC segítségével SQL lekérdezéseket küldhetsz az adatbázisnak, adatokat kérhetsz, frissíthetsz vagy törölhetsz.
   - A JDBC használata komoly szintű kódot és sok boilerplate kódot igényel.

2. **ORM (Object-Relational Mapping):**
   - Az ORM egy tervezési minta és technika, amely lehetővé teszi az objektumok és az adatbázisok közötti átalakítást. Az ORM segítségével objektumokat használhatsz az adatbáziskezelés helyett, és az ORM automatikusan leképez objektumokat az adatbázis táblákra.
   - Az ORM keretrendszerek olyan szoftverek, amelyek segítenek az ORM implementálásában, például Hibernate, JPA, Entity Framework (.NET), stb.

3. **JPA (Java Persistence API):**
   - A JPA egy Java szabvány és API az ORM megvalósítására. A JPA definiálja az objektum-relációs leképzési szabványokat, amelyeket ORM keretrendszerek implementálnak.
   - A JPA olyan annotációkat és interfészeket tartalmaz, amelyek segítségével objektumokat leképezhetünk az adatbázis táblákra.

4. **Hibernate:**
   - A Hibernate egy konkrét ORM keretrendszer a Java nyelvhez, amely implementálja a JPA szabványt, de saját, bővített funkciókat is kínál.
   - A Hibernate automatikusan kezeli az objektumok és az adatbázis táblák közötti leképzést, és lehetőséget nyújt a gyors és hatékony adatbáziskezelésre.

Az összefüggések:
- A JPA és a Hibernate kapcsolatban vannak, mivel a Hibernate egy olyan ORM keretrendszer, amely implementálja a JPA szabványt, így a JPA az interfész a Hibernate-vel szemben, ami a konkrét megvalósítás.
- Az ORM és a JPA az objektum-relációs leképzéshez kapcsolódnak. Az ORM keretrendszerek, például a Hibernate, az objektumokat és az adatbázisokat összekapcsolják, hogy egyszerűsítsék az adatbáziskezelést.
- A JDBC a legalapvetőbb szintű eszköz az adatbáziskezeléshez, és általában a JPA vagy a Hibernate fölötti rétegként használják, hogy lehetővé tegye az adatbáziskapcsolódást és az alacsony szintű adatbázis-műveletek végrehajtását.

Fontos megjegyezni, hogy a konkrét technológiai választás attól függ, hogy milyen igényeket és projekt-specifikus követelményeket kell kielégíteni. Az ORM és a JPA lehetővé teszik a fejlesztők számára az objektum-orientált tervezés előnyeinek kihasználását, míg a JDBC a további kontroll és teljesítmény szempontjából hasznos lehet bizonyos esetekben. A Hibernate egy jó példa arra, hogyan lehet a JPA-t használni a könnyűszerrel és kényelemmel, de miközben bővíti azt a további funkciókkal.
--------------------------------------------------------------------------------------------------------

# Mi a git és GitHub? 	
A Git és GitHub két különböző, de szorosan kapcsolódó eszköz a verziókezelésben és a kódmegosztásban. Itt vannak a rövid meghatározások mindkettőről:

1. **Git:**
   - A Git egy elosztott verziókezelő rendszer, amelyet programozók használnak a forráskód verzióinak nyomon követésére és kezelésére.
   - A Git lehetővé teszi a fejlesztők számára, hogy követhessék a változtatásokat a kódban, visszaállíthassák az előző változatokat, együttműködjenek másokkal a projekten, és hatékonyan kezeljék a kódverziókat.

2. **GitHub:**
   - A GitHub egy webes platform, amely az elosztott verziókezelő rendszerre épül, különösen a Git-re.
   - A GitHub lehetővé teszi a fejlesztők számára, hogy tárolják, nyomon kövessék és megosszák a Git-re épülő projektjeiket.
   - A GitHub további funkciókat kínál, például probléma nyomon követés, wiki oldalak, projektkezelés és együttműködési lehetőségek.

A Git és a GitHub közötti kapcsolat:
- A Git egy verziókezelő rendszer, amelyet helyileg, azaz a saját gépeden használhatsz a projektjeid kezelésére.
- A GitHub egy felhőalapú platform, ahol a Git-re épülő projektjeidet tárolhatod és megoszthatod másokkal. A GitHub segítségével kollaboratív fejlesztésre is lehetőség nyílik, így több fejlesztő is dolgozhat egy projektben.

Összefoglalva, a Git egy verziókezelő rendszer, amely lehetővé teszi a kód változásainak kezelését, míg a GitHub egy webes platform a Git-re épülve, amely lehetővé teszi a projektjeid tárolását, megosztását és együttműködését. Mindkettő kritikus szerepet játszik a szoftverfejlesztésben, és segíti a fejlesztőket a hatékony kódmegosztásban és együttműködésben.
--------------------------------------------------------------------------------------------------------

# Mi a cookie?	
A cookie (magyarul sütike) egy kis mennyiségű információ, amit a weboldalak a felhasználó böngészőjében tárolnak, és amely később ismét felhasználható. A cookie-k egy weboldal és a böngésző közötti adatcsere egyik módja, és a következő célra használhatók:

1. **Állapot nyomon követése:** A cookie-kat gyakran használják a felhasználók állapotának (bejelentkezve vagy kijelentkezve) nyomon követésére. Például bejelentkezés után a weboldal elküldhet egy sütiket a böngészőbe, hogy azt jegyezze meg, hogy a felhasználó bejelentkezett.

2. **Egyéni tartalom:** A weboldalak használhatnak cookie-kat az egyéni tartalom és beállítások tárolására. Például egy online bevásárló weboldal megjegyezheti a felhasználó kosarában lévő tételeket a cookie-k segítségével.

3. **Követés és elemzés:** A reklámozók és webanalitikai szolgáltatások cookie-kat használhatnak a felhasználói tevékenység követésére és elemzésére. Ez segít abban, hogy a webhely tulajdonosai megértsék, hogyan használják a felhasználók a weboldalt, és hogy célzott hirdetéseket jelenítsenek meg.

4. **Felhasználói beállítások:** A felhasználók saját beállításait és preferenciáikat is elmenthetik cookie-k formájában. Például egy weboldal elmentheti a felhasználó nyelvi preferenciáit vagy a felugró ablakok bezárásának preferenciáját.

Fontos tudni, hogy a cookie-k két típusra oszthatók: munkameneti (session) cookie-k és tartós (persistent) cookie-k.

- **Munkameneti (session) cookie:** Ezek a cookie-k ideiglenesen tárolódnak, és akkor törlődnek, amikor a felhasználó bezárja a böngészőjét. Általában az aktuális munkamenet során használják, hogy ideiglenes információkat tároljanak, például a bevásárlókosár tartalmát.

- **Tartós (persistent) cookie:** Ezek a cookie-k hosszabb ideig maradnak meg a böngészőben, akár hónapokig vagy évekig. Általában a felhasználói beállítások, preferenciák vagy hosszú távú azonosítók tárolására használják.

Fontos szempont a cookie-kkel kapcsolatban az adatvédelem és a biztonság. Mivel a cookie-k információt tárolnak a felhasználó böngészőjében, fontos, hogy a weboldalak megfelelően kezeljék és védjék azokat. Ezenkívül egyre szigorúbb adatvédelmi törvények szabályozzák a cookie-k használatát, és a felhasználók gyakran engedélyezhetik vagy tilthatják azok használatát a böngészőjük beállításaiban.
--------------------------------------------------------------------------------------------------------

# Mi a White Box Testing(Black Box)?	
A White Box Testing és a Black Box Testing két különböző módszer a szoftvertesztelés során. Ezek a tesztelési módszerek arra összpontosítanak, hogy a szoftver hogyan működik, de eltérő megközelítéseket alkalmaznak a tesztelés során:

1. **White Box Testing (üveges doboz tesztelés):**
   - A White Box Testing egy olyan tesztelési módszer, amely a szoftver belső szerkezetét és működését vizsgálja. A tesztelő ismeri a szoftver forráskódját és az algoritmusait, és a tesztelés során ezeket az ismereteket felhasználja.
   - A White Box Testing célja, hogy a tesztelő megbizonyosodjon arról, hogy a szoftver helyesen működik belső működésének ismeretében. Megvizsgálja az utasításokat, a ciklusokat, az elágazásokat és az adatelérési logikát.
   - A White Box Testing során olyan tesztek készülnek, amelyek a kód minden részét lefedik, beleértve az összes elágazást és ágat. Ennek eredményeként alapos tesztfedettség érhető el.

2. **Black Box Testing (fekete doboz tesztelés):**
   - A Black Box Testing olyan tesztelési módszer, amely a szoftvert egy "fekete dobozként" kezeli, ami azt jelenti, hogy a tesztelőnek nincs ismerete a szoftver belső szerkezetéről vagy működéséről.
   - A Black Box Testing a szoftvert külső interfészek és specifikációk alapján teszteli. A tesztelő nem látja a kódot, hanem a bemeneteket és a kimeneteket vizsgálja, és azok alapján értékeli a szoftver helyes működését.
   - A Black Box Testing célja, hogy ellenőrizze, hogy a szoftver az elvárt funkciókat és teljesítményt nyújtja a felhasználók számára. A tesztelő nem érdekli, hogy a szoftver hogyan valósítja meg ezt.

Mindkét tesztelési módszernek vannak előnyei és hátrányai, és gyakran alkalmazzák őket a szoftvertesztelés során, annak függvényében, hogy milyen célt szeretnénk elérni. A White Box Testing alaposabban ellenőrzi a kód működését és az algoritmusok helyességét, míg a Black Box Testing a felhasználói élményt és a specifikációk teljesítését vizsgálja. Sok projekt során mindkét módszer kombinálható annak érdekében, hogy alaposabb és átfogóbb tesztelési eredményeket érjünk el.
--------------------------------------------------------------------------------------------------------	
--------------------------------------------------------------------------------------------------------	

# Kód komplexitás típusai:	
Időkomplexitás: Az időkomplexitás értékeli, hogy egy adott algoritmus vagy kód mennyi időt vesz igénybe a futási ideje során, az input méretétől függően. Az időkomplexitás számos jellemzőjét használják a programok teljesítményének értékeléséhez, például a nagy O jelölést, amely egyfajta absztrakt jelölés a futási idő növekedésének értékelésére a bemenet méretének függvényében. Az időkomplexitás célja az algoritmus hatékonyságának és gyorsaságának meghatározása.	

Térkomplexitás: A térkomplexitás azt értékeli, hogy egy program vagy algoritmus mennyi memóriát használ a futása során, az input méretétől függően. A térkomplexitás értékelése fontos lehet, különösen korlátozott memóriával rendelkező környezetekben vagy eszközökön. A cél az, hogy a lehető legkevesebb memóriát használja fel a program vagy algoritmus.	

konstans: pl amikor egy listábol az indexe alapján keressük ki az adott elemet. Ha tudjuk az elem indexet nem számít mennyi adatunk van a futási idő gyors lesz.	

logaritmikus(logn):	
pl bináris keresésnél amikor sorba vannak rendezve az elemek.	

lineáris(n): pl egy maximum keresés vagy egy adott elem keresése a listában anélkül hogy tudnánk az indexét. A lista minden egyes elemén végig kell menni. A futási idő arányosan nő az adatmennyiséggel.	

n logn: pl hányszor van valami	

négyzetes(n2): pl 2 egymásba ágyazott for ciklus.	

köbös(n3): pl 3 egymásba ágyazott for ciklus	

exponenciális(2n)	

# Collections:	

Queue: A queue egy olyan collection (vagy interface) ami a first in first out módon kezeli az adatokat.	
Tehát amit először raktam bele azt is veszem ki először. Ezt olyankor használjuk amikor fontos a végrehajtási sorrend.	

ArrayList: A list colelction(interface) egyik megvalósítása. Az arrayList az egy dinamikus tömb amihez dinamikusan tudunk hozzáadni elemeket. Gyorsan tudunk hozzáadni, törölni elemeket a lista végén. Az elején viszont lassabb a folyamat mert igy minden elemet el kell hogy toljon egyel. Egy tömböt használ ami mindig másolásra kerül amikor a lista bővül. Indexe alapján könnyen eltudjuk érni az adott elemeket benne. Sorrendbe vannak az elemek index alapján rendezve. Működik rajtuk az add() remove() get().	

LinkedList: Ez egy kétirányu láncolt listát valósít meg. Minden elem egy olyan csomópont (node) része, amely tartalmaz egy értéket, valamint hivatkozásokat a következő és az előző csomópontokra. Ez lehetővé teszi a gyors beszúrást és törlést a lista bármely pontján. Lehetővé teszi az elemek gyors beszúrását és eltávolításást a lista közepéről. A gyors beszúrás és törlés mellett a LinkedList lassabb hozzáférést biztosít az elemekhez, mivel az elemek közötti navigáláshoz szükség van az előző vagy a következő csomópontokra. A LinkedList hasznos, amikor gyakran kell elemeket hozzáadni vagy eltávolítani a lista közepén vagy bármely más pontján. Azonban ha csak hozzáférésre és iterálásra van szükség a listán, az ArrayList hatékonyabb lehet.	

# Primitiv adattipusok javaban:	
A primitiv adattipusok be vannak építve a nyelvbe amik meghatározott nagyságú adatot vehetnek fel. Ezek bitekként vannak tárolva a memóriában. Ezek nem objectumok.
Ezket lehetnek integer, char, boolean, double float, short, long. Ha egy változóhoz akarunk társítani egy primitiv adatot akkor a konkrét értéket társítja a változóhoz.		

# Referencia típusú adatok:	
Ezek objectumok. Lehetnek tömbök, osztályok, interfacek. Amikor egy ilyen típusú adatot társítunk változóhoz, akkor a változó nem a konkrét objectumot hanem egy referenica értéket fog tárolni ami hivatkozik(rámutat) az objectumra a memoriában.	

# Static kulcsszó:	
Ez egy olyan kulcsszó amivel meg lehet jelölni osztályokat, mezőket, metódusokat.
A program futása során egyszer kerülnek inicializálásra. 
Ha egy mezőt megjelölünk ezzel a szóval az azt jelenteni hogy az a mező az osztályhoz tartozik nem pedig az osztály egy példányához. Ha beállítunk egy értéket neki akkor az osztály minden egyes példányának ez az érték lesz beállítva. 
Egy statikus metódushoz nem kell objectum amin meghívjuk, hozzáférhetőek osztály nevének hivatkozásával.
A static blokkok olyan kódrészletek, amelyek az osztálybetöltés során futnak, még az objektumok létrehozása előtt. Ezeket gyakran az osztályszintű inicializációhoz használják. 
A static elemeket gyakran azért használják, mert közösek az összes példányosított objektum között, és nem igényelnek példányosítást az elérésükhöz. Azonban fontos megérteni, hogy a static tulajdonságok és metódusok nem férnek hozzá az objektum példányzás során használható nem-static elemekhez. Az static elemek osztályszintűek, míg a nem-static elemek objektumszintűek.	

# Dependency inversion:	
A dependency inversion olyan elv ami kimondja hogy a magasabb szintű moduloknak nem az alacsonyabb szintű moduloktol kell függeniÜk, hanem inkább mindkettőnek az absztrakciótol (interface vagy absztract osztályok) így könnyebben cserélhetők az alacsony szintű komponensek vagy bővíthető a rendszer anélkül, hogy a magas szintű komponenseket érintené. Absztrakcióktól kell függeni, nem a részletektől (concrete implementációktól). Azaz a kódoknak az interfészekre vagy absztrakt osztályokra kell hivatkozniuk, és nem a konkrét osztályokra 
Ez segít csökkenteni a kódban lévő szoros kapcsolatokat és függőségeket, így növeli a rugalmasságot és könnyen karbantartható kódot eredményez.
Egy gyakori gyakorlat a Dependency Injection (DI) használata, amely egy tervezési minta, amely lehetővé teszi a függőségek átadását a magas szintű moduloknak az alacsony szintű modulok felől, így a DIP elvét könnyen alkalmazhatóvá teszi a gyakorlatban. Az Dependency Injection révén a magas szintű modulok interfészeket használnak, és azokat az alacsony szintű modulok konkrét implementációkkal injektálják, ami lehetővé teszi a lazább csatolást és a könnyű tesztelhetőséget.	

# SQL:	
Az SQL (Structured Query Language) egy speciális programnyelv és szabvány, amely a relációs adatbázis-kezelő rendszerekhez használt adatmanipulációhoz és adatlekérdezéshez kifejlesztették. Az SQL lehetővé teszi az adatbázisok létrehozását, módosítását, lekérdezését és karbantartását.	
Az SQL aggregációs (vagy aggregáló) függvények olyan függvények, amelyek összegzik, csoportosítják vagy kiszámítják az adatok összegét egy adott lekérdezés eredményének alapján. Az aggregációs függvények hasznosak, amikor összegzést vagy összesítést kell végezni az adatokon  például amikor statisztikákat kell kiszámítani vagy csoportosított eredményeket szeretnénk lekérni.
COUNT(): Az COUNT() függvény számolja meg az eredményhalmaz sorainak számát.	
SUM(): Az SUM() függvény összegzi egy oszlop értékeit.	
AVG(): Az AVG() függvény kiszámítja egy oszlop értékeinek átlagát.	
MIN(): A MIN() függvény meghatározza egy oszlop legkisebb értékét. 	
MAX(): A MAX() függvény meghatározza egy oszlop legnagyobb értékét.	
GROUP BY: A GROUP BY záradékot csoportosítási célból használják. Lehetővé teszi az eredményhalmaz csoportokba rendezését egy vagy több oszlop alapján, és ebben a csoportosított eredményhalmazban az aggregációs függvényeket alkalmazzák	
HAVING: A HAVING záradék a GROUP BY záradékkal használható, és lehetővé teszi az eredménycsoportok szűrését az aggregációs függvények eredménye alapján.	

# CSS:	
CSS (Cascading Style Sheets) egy stíluslapnyelv, amelyet weboldalak formázására és stílusozására használnak. A CSS lehetővé teszi a webfejlesztők számára, hogy megadják, hogy hogyan jelenjenek meg az HTML elemek a böngészőben. A CSS-el formázhatod a szövegek kinézetét, a háttérszíneket, a kereteket, a betűtípusokat és méreteket, a távolságokat, a pozíciókat és még sok minden mást. A CSS segítségével elválaszthatod a tartalmat (HTML) a megjelenéstől (stílus).
A CSS szabályok ún. "szelektorokból" és "deklarációkból" állnak. A szelektorok azt határozzák meg, hogy mely HTML elemekre vonatkoznak a stílusok, míg a deklarációk tartalmazzák a stílusok tulajdonságait és értékeit.	

# ORM:	
Object relational mapping. Egy módszer az adatbázisok valamint a osztályok, objectumok közötti interakciora, adat átvitelre. Az ORM célja, hogy az alkalmazások objektumait és az adatbázisban tárolt adatokat könnyen ÖSSZEHANGOLJA és ÁTFORDÍTSA EGYMÁSBA. Ennek az az előnye, hogy a fejlesztők objektumorientált módon kezelhetik az adatokat, és nem kell SQL-el közvetlenül dolgozniuk.
Az ORM rendszerek számos előnnyel járnak:	
Objektum-orientált megközelítés: Az ORM lehetővé teszi, hogy az adatbázisban tárolt adatokat objektumokként kezeljük a programozási nyelvben. Ez könnyű és intuitív módja az adatok kezelésének, és segíti az alkalmazások strukturálását.	
Adatbázis-függetlesség: Az ORM segítségével az alkalmazások könnyen átültethetők különböző adatbázisrendszerek között, mivel az ORM rendszer kezeli az adatbázisspecifikus lekérdezéseket és műveleteket.
Automatikus adattábla létrehozás: Sok ORM rendszer automatikusan létrehozza az adatbázis táblákat a megadott objektumok alapján. Ez megszünteti a kézi adattábla tervezés szükségességét.
Könnyű lekérdezések: Az ORM rendszerek általában lehetővé teszik egyszerű és kifejező lekérdezések írását az objektumokhoz kapcsolódó adatok eléréséhez.
Karbantarthatóság és tesztelhetőség: Az ORM segít az alkalmazások karbantarthatóságában és tesztelhetőségében, mivel az adatbázis-specifikus kódot kiszorítja a magasabb szintű programkódból.
A Hybernate az egy framework ami segít megvalósítani az orm-t.	

# JDBC és JPA:	
A JDBC (Java Database Connectivity) és a JPA (Java Persistence API) két különböző technológia a Java alkalmazások és relációs adatbázisok közötti kapcsolat kezelésére.	

JDBC: A JDBC egy alacsony szintű API, amely lehetővé teszi a Java alkalmazásoknak, hogy közvetlenül kommunikáljanak relációs adatbázisokkal. A fejlesztőknek SQL lekérdezéseket kell írniuk és adatbázis-vezérlők használniuk a kapcsolat fenntartásához és az adatok lekérdezéséhez és frissítéséhez.	
-összetettebb lekérdezésekre	

JPA: A JPA egy magasabb szintű absztrakció, amely az ORM (Object-Relational Mapping) technológiára épül. Leegyszerűsíti az adatbázis műveletek elvégzését azáltal, hogy az objektumorientált entitásokat és az adatbázis táblákat közötti leképezést kezeli.	
-egyszerűbb lekérdezésekre	

# Hibernate: JPA-ORM implementáció.	
A Hibernate egy Java alapú ORM (Object-Relational Mapping) keretrendszer, amely lehetővé teszi az objektumok és az adatbázisok közötti leképezést és kölcsönhatást.	

JpaRepository: Egy interfész, amelyet a Spring alkalmazásokban használnak a JPA (Java Persistence API) alapú adatbázis hozzáférés egyszerűsítésére. A JpaRepository lehetővé teszi a fejlesztők számára az alapvető adatbázis műveletek, például lekérdezések, beszúrások, frissítések és törlések definiálását egy egyszerű és kényelmes módon.
A JpaRepository definiál különböző alapvető műveleteket, amelyeket a fejlesztők az entitásokhoz tartozó metódusokkal használhatnak. 

# Spring:	
A spring az egy olyan keretrendszer ami featurok és eszközök széles tárházát nyújtja  vállalati szintű alkalmazások fejlesztéséhez, valamint kisebb projektekhez is alkalmas.Felöleli az alkalmazásfejlesztési folyamat legtöbb részét, pl. biztonság, adathozzáférés, tranzakció stb. Támogatja az olyan bevált gyakorlatokat, mint a modularitás, a rugalmasság, és IoC+-függőségi injekciót használ. Jól integrálható a modern, népszerű tesztelési keretrendszerekkel is. Két típuse van a JSE(java standard edition) ez inkább kisebb projectekhez és A JEE(java enterprise edition) ez inkább nagyobb projectekhez.	

# Spring boot:	
Egy keretrendszer a Spring ökoszisztémában. A spring eszközök nagyon széles tárházával rendelkezik és a spring boot ezt próbálja valamilyen keretek közé szorítani és számunkra csak a szükséges eszközöket és a hozzájuk talrtozo konfiguráciokat beállítani.A Spring Boot Starters LEEGYSZERŰSÍTI A FÜGGŐSÉGEK BEÁLLÍTÁSÁT, míg tesztelési segédprogramjai egyszerű és hatékony tesztelést biztosítanak. Összességében a Spring Boot felgyorsítja a fejlesztést, különösen a mikroszolgáltatások esetében, anélkül, hogy lecserélné a Spring Framework-et, továbbfejleszti azt.	

# Inversion of control:	
Az az elv amikor kiadjuk az irányítást a kezünkből és ezt egy framewörk veszi át.	
Ezt az ioc contener framewörk valósítja meg. Az IoC segítségével elérhető, hogy a komponensek ne maguk hozzák létre vagy irányítsák az alapértelmezett függőségeiket, hanem a függőségeiket egy külső forrásból kapják (pl. egy IoC konténerből), ami lehetővé teszi a könnyebb tesztelést és a komponensek cseréjét anélkül, hogy az alkalmazás egészét módosítani kellene.(dependency injection).A Spring IoC konténere (vagy "application context") felelős a bean-ek (komponensek) inicializálásáért és konfigurálásáért, valamint a függőségek injektálásáért. Az alkalmazásmodulok (bean-ek) csak azt kell tudniuk, hogy milyen függőségekre van szükségük, és nem kell foglalkozniuk a függőségek létrehozásával vagy inicializálásával.	
A "package scanning" az IoC konténernek azt a képességét jelenti, hogy felderíti az alkalmazás forrásfájlokat és csomagokat, és azonosítja azokat a Java osztályokat, amelyek Spring bean-ként használhatók.Azokat az osztályokat, amelyek megfelelnek a bean definícióknak (például annotációkkal vagy XML-bean definíciókkal), a konténer inicializálja és beilleszti a Spring konténerébe.A package scanning és az annotációk (például a @Component, @Service, @Repository, @Controller stb.) 	

# Mi a hashmap?	
A hashmap egy adatszerkezet, amely kulcs-érték párokat tárol. A kulcsok egyediek, és mindegyik kulcshoz egy érték tartozik. A hashmap gyors hozzáférést tesz lehetővé az értékekhez a hashkódok segítségével. Az adatszerkezet hashinget alkalmaz, amely egy hashfüggvény segítségével átalakítja a kulcsokat olyan számsorozattá, amely indexként szolgál a belső táblázatban.	

A hashmap gyors hozzáférést biztosít az értékekhez, mivel a hashkódok alapján meghatározza, hogy melyik "vödörbe" kell helyezni az adott kulcs-érték párt. A "vödörök" segítenek a kollíziók kezelésében, amikor két vagy több kulcsnak ugyanaz a hashkódja van. Az adatokat a vödörökben tárolják, például láncolt listák vagy más struktúrák formájában.	

A hashmap mellett szokott említésre kerülni a hasSet is, amely gyakran egy hasonló elvet követ, de csak kulcsokat tárol anélkül, hogy értékekkel rendelkezne. A key-value pairs (kulcs-érték párok) a hashmap alapvető elemei, ahol a kulcsok egyediek és az értékek hozzájuk vannak rendelve.	

Fontos megemlíteni, hogy a hashmapek gyors hozzáférést és keresést biztosítanak, de a hashfüggvény kollíziókat is okozhat. A kollíziókat a különböző vödörök (buckets) használatával kezelik, ahol az egyes vödrökben tárolják az azonos hashkóddal rendelkező kulcs-érték párokat. Az immutability (nem módosíthatóság) azt jelenti, hogy a kulcsok általában nem változhatnak, mivel a változó kulcsok befolyásolhatják a hashkódot és a hashmap belső struktúráját.	

# Mi az Interface segregation?	
Az Interface Segregation Principle (Interfészszegregáció-elv vagy röviden ISP) a SOLID elvek egyike, amelyek a szoftvertervezésben alkalmazandó alapelveket írják le. Az Interface Segregation Principle arra ösztönzi a fejlesztőket, hogy olyan interfészeket hozzanak létre, amelyek kliensosztályok specifikus igényeire vannak szabva, és ne kényszerítsék azokat olyan metódusok implementálására, amelyeket nem használnak.	

A gyakorlatban az Interface Segregation azt jelenti, hogy ne hozzunk létre túlságosan általános interfészeket, amelyek számos különböző műveletet tartalmaznak. Ehelyett kisebb, specifikus interfészeket kell kialakítani, amelyek csak azokat a metódusokat tartalmazzák, amelyek egy adott kliensosztály számára relevánsak.	

Például, ha egy interfész olyan metódusokat tartalmaz, amelyek csak egy részhalmazát használja egy kliensosztály, akkor az Interface Segregation azt javasolja, hogy az interfészt bontsuk szét olyan rész-interfészekre, amelyek specifikusabbak és az adott kliensosztálynak jobban megfelelnek.	

Az Interface Segregation segít abban, hogy az osztályoknak ne legyenek felesleges függőségeik, és csökkenti az interfészek implementálásával járó terhelést, mivel csak a szükséges metódusokat kell megvalósítaniuk. Ezen kívül növeli a kód tisztaságát, karbantarthatóságát és könnyebbé teszi a rendszer bővítését.	

# Relational DB?	
A "Relational Database" (kapcsolati adatbázis) egy olyan adatbázistípus, amely az adatokat táblákban tárolja, és azok közötti kapcsolatokat használja a kölcsönös adatmegosztás és -lekérdezés szempontjából. A relational database (RDBMS) a relációs adatmodell alapján működik, amelyet E. F. Codd vezetett be az 1970-es években.	

A relációs adatmodell lényege, hogy az adatokat táblákba (táblákba) szervezi, ahol minden tábla egy bizonyos típusú entitást (pl. ügyfelek, rendelések, termékek) reprezentál, és minden sor a táblában egy konkrét példányát az adott entitásnak. A táblák közötti kapcsolatokat kulcsok (keys) segítségével definiálják. Az egyes táblákban található kulcsok segítségével lehet összekapcsolni az adatokat, és így lekérdezéseket hajtani végre az összefüggő adatokra.	

A legelterjedtebb relációs adatbázis-kezelő rendszerek közé tartozik az Oracle Database, Microsoft SQL Server, MySQL, PostgreSQL és SQLite. Ezek a rendszerek biztosítják a transzakciókezelést, adatintegritást, biztonságot és hatékony lekérdezési lehetőségeket a relációs adatbázisokhoz.	

A relációs adatbázisok sokféle alkalmazásban használatosak, például az üzleti alkalmazások, webes alkalmazások, könyvelési rendszerek, logisztikai alkalmazások és sok más területen.	

# Merge Conflict?	
A "merge conflict" (összefésülési konfliktus) egy olyan helyzetet jelent a verziókezelés során, amikor a rendszer nem tud automatikusan eldönteni, hogyan kell összefésülni két különböző változatú forráskódot vagy változásokat. A merge conflict akkor következik be, amikor két vagy több ágban végzett módosítások érintik ugyanazt a részt egy fájlban, és a verziókezelő nem tudja automatikusan eldönteni, hogy mely változásokat kell elfogadni.	

A merge conflictok gyakran akkor merülnek fel, amikor fejlesztők együtt dolgoznak ugyanazon a projektben, különféle ágakban végzik a változtatásokat, majd próbálják összefésülni ezeket az ágakat. A konfliktusok akkor jelentkeznek, amikor a verziókezelő észleli, hogy a két ágban olyan módosítások történtek, amelyek egymásnak ellentmondanak.	

A merge conflict megoldása a fejlesztő feladata. A verziókezelő jelzi, hogy hol találhatóak a konfliktusok, és a fejlesztőnek meg kell oldania azokat. Általában ez azt jelenti, hogy a fejlesztő kézzel kiválasztja, mely változásokat kell elfogadni az összefésülés során. A megoldás után a fejlesztő értesíti a verziókezelőt, hogy a konfliktust megoldották, és a változtatásokat hozzá lehet adni a központi verzióhoz vagy az adott ághoz.	

A konfliktuskezelés fontos része a csapatmunkának és a verziókezelési folyamatnak, különösen akkor, amikor több fejlesztő egyidejűleg dolgozik ugyanazon a kódbázison.	

# Docker image vs Container?	
Az image egy készülőfázisban lévő, statikus, könnyen reprodukálható szoftvercsomag, míg a konténer egy dinamikus, futó példánya ennek az image-nek, amely futtató környezetével és a szükséges erőforrásokkal együtt jön létre. A konténerek rugalmasak és könnyen kezelhetők, így a Docker segítségével az alkalmazások egyszerűen és konzisztensen futtathatók különböző környezetekbe	

# Mi a stack? És mi a call stack?(Függvény hivásnál mi kerül a stackbe?)	
A stack a java nyelvben egy adatszerkezet, amely az adatokat veremként kezeli. Ami azt jelenti, hogy az utolsoként hozzáadott elem majd először lesz eltávolitva, vagyis a LIFO (Last In, First Out) elvét követve.
Ez hasznos lehet a metodoshivások visszatérési cimének tárolására.	

