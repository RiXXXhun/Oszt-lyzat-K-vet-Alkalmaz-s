# Osztalyzat - követő 

#### <h2>Csoport tagok</h2>
<Strong> Tóth Zoltán </strong> <br>
<Strong> Nagy-Eperjesi Richárd </strong> <br>
<Strong> Sali Levente </strong> <br>

#### <h2>Csapat név</h2>
<Strong> Champions </strong> 


#### <h2>Választott téma: </h2>
<Strong> Osztályzat-követő alkalmazás </strong> <br>

<h5> A feladat során egy olyan alkalmazást kell elkészíteni, ahol egy tanuló tudja rögzíteni a jegyeit tárgyanként. Egy külön pane-en lehessen új tárgyat felvinni. A fő pane-en lenyíló listával lehessen szűrni tárgyakat. A jegyek táblázata alatt jelenjen meg az adott tárgy átlaga. <br> 
Az adatbázis táblájában minden bejegyzéshez rögzítésre kerüljön a tárgy, időpont, jegy, témakör (pl mire kapta a diák az adott jegyet). A jegyekről lehessen pdf formátumban jelentést készíteni egy meghatározott időszakra és egy vagy több meghatározott tárgyra. </h5>



#### <h2>Projektet érintő tantárgyak</h2>
<Strong>IKT Projektmunka</strong> <br>
<Strong>Asztali alkalmazások fejlesztése 2.</strong> <br>
<Strong>Szoftvertesztelés</strong> <br>


#### <h2>Feladat leírása</h2>

<Strong> A feladat során 2-3 fős csapatokban kell megoldanotok a lejjebb felsorolt témák egyikét. Szabadon is
választhatók témák, de előtte egyeztetni kell róla egy oktatóval! <br> 
A projektben egy teljes értékű JavaFX alkalmazást kell implementálni, teszteléseket végezni, dokumentálni, végül prezentálni. <br> 
Ebből kifo-lyólag a projektre 3 tárgyból is kaptok értékelést: Asztali alkalmazás fejlesztés 2, Szoftvertesztelés, IKT projektmunka.

Mindegyik csapattagnak részt kell vennie a kódolási, tesztelési, dokumentációs és prezentációs folya-
matokban! Ajánlott, hogy mindenki a saját maga által implementált funkciókat tesztelje, dokumen-
tálja és prezentálja! Minden csapatban lehetőleg azonos képességű tagok legyenek! </strong> <br>

#### <h2>Elvárások</h2>

<h3> <Strong>Asztali alkalmazás fejlesztés 2 </strong> </h3>

<ol>
  <li>Teljes értékű JavaFX alkalmazás: A hangsúly a funkcionalitáson van, a design másodlagos! <br> 
  Félkész funkciók ne legyenek az alkalmazásban! Ha megakadtok egy funkció fejlesztése közben, az órákon megbeszéljük. <br> 
  A projektben az MVC struktúrát kell alkalmazni (tehát külön-külön fájlokban és osztályokban legyen a nézet, a modell és a kontroller). <br> 
  Az alkalmazásban a nagyon eltérő funkciókat külön-külön Pane-en kell megjeleníteni. Ezeken kívül JDK17-et és Maven csomagolót kell használni!</li> <br>
  <li>Kivétel- és hibakezelés: Az alkalmazásban minden előforduló kivételt és hibát le kell kezelni, ennek előfordulásakor adj vissza hibaüzenetet piros betűszínnel egy Label-be!
  Ha nem történt hiba és sikeresen lefutott egy funkció, adj vissza fekete / zöld betűszínnel egy tájékoztató üzenetet ugyanabban a Label-ben!</li> <br>
  <li>Adatbázis használata JDBC-vel: Az adatbázis funkciókat külön, erre a célra kialakított osztályban kell implementálni. <br> 
  Adatbázishoz való csatlakozás után érdemes rávizsgálni, hogy létezik-e a kívánt adatbázis és táblák. <br> 
  Így ha nem létezik, akkor az alkalmazásból létre is tudjuk hozni őket. Célszerű Derby-t használni, viszont egyéb MySQL megvalósítás is elfogadott.</li> <br>
  <li>Clean code alapelvek használata: A kód legyen letisztult, a különböző részek megfelelően tagolva, indentálva! Figyelni kell, hogy a különböző funkciók külön-külön metódusokba / függvényekbe legyenek tagolva, ne egybe ömlesztve (+ újra felhasználhatóság)! Értelmes változó neveket kell használni, legyenek beszédesek, hogy kitalálható legyen, mire is jók. Célszerű kommentelni is, melyik részegység mire való.</li> <br>
  <li>Szoftver ergonómia: A feliratok jól láthatóak legyenek, a gombok megfelelően kattinthatóak legyenek (ne túl kicsi, ne túl nagy)!</li> <br>

</ol> 

<h3> <Strong>Szoftvertesztelés </strong> </h3>

<ol>
  <li>Készítsd el a projekted dokumentációjához az osztály diagramot! A diagram tartalmazza a megoldás összes osztályát, az osztályok adattagjait és metódusait továbbá a (ha van) jelöld nyilakkal az öröklődéseket <a href="https://www.drawio.com/assets/img/blog/class-diagram-example.png">Minta</a > </li> <br>
  <li>A program gyenge pontjain (ahol felhasználótól kérünk adatot), kezelje megfelelően egy tanult módzserrel úgy, hogy ne okozhasson hibát a felhasználó!</li> <br>
  <li>A programban valahol használjon legalább egy saját készítésű kivételt!</li> <br>
  <li>Készítsen tesztelési útmutatót a projektjéhez! Ez egy reademe.md <a href="https://en.wikipedia.org/wiki/Markdown"> segédlet </a> fájl legyen, amiben lépésről lépésre bemutatja az alkalmazás felhasználását. Figyeljen arra, hogy a program minden funkcióját bemutassa vele! Például:</li><br>
    <h6> Szám esetén: </h6> 
    - Nem egyenlő vizsgálat: túl kicsi opció <br>
    - Egyenlő vizsgálat: megfelelő opció <br>
    - Nem szám vizsgálat: rossz bemenet <br>
    <h6> Szöveg esetén </h6> 
    - Üres vizsgálat: üres bemeneti mező <br>
    - Megfelelő vizsgálat: jó bemenő adat <br>
    - Hibás vizsgálat: nem megfelelő adat <br> <br>

  <li>Készítsen Unit teszteket a programhoz! Válasszon ki legalább 2 függvényt, amelyhez elkészíti a Unit teszteteket. Minden függvényhez készítsen egy egyenlőség vizsgálatot legalább 3 opcióval</li> <br>

</ol> 

<h3> <Strong> IKT projektmunka </strong> </h3>

<ol>
  <li>Bemutató készítése az elkészített szoftverhez.</li> <br>
  <li> A bemutatónak legalább 15 diát kell tartalmaznia, mely az alábbi felépítést tartalmazza: </li><br>
    - A szoftver céljának rövid bemutatása <br>
    - A szoftver felépítése (menürendszer, képernyőképek, stb.) <br>
    - A szoftver használatának bemutatása <br>
    - Az elkészített szoftver továbbfejlesztési lehetőségei <br> <br>

  <li>A diákon maximum 28-as betűméret alkalmazható </li> <br>
  <li> Figyelni kell a helyesírásra, nyelvhelyességre (zavaró elírások, helyesírási hibák, stb. PONTLEVONÁST fog jelenteni)</li> <br>
  <li> Az elkészített bemutató előadása </li> <br>

</ol> 

<br>

#### <h2> Munkamegosztás </h2>


<h3> <Strong> Tóth Zoltán </strong> </h3>

<ol>
  <li>Java.fx tervezés és megvalóítása</li> 
  <li>Java programozás és java.fx tervezés</li>
</ol> 

<h3> <Strong> Nagy-Eperjesi Richárd </strong> </h3>

<ol>
  <li>Markdown (.md)</li> 
  <li>Java programozás és java.fx tervezés</li>
</ol> 

<h3> <Strong> Sali Levente</strong> </h3>

<ol>
  <li>Power Point prezentáció készítés</li> 
  <li>Java programozás és java.fx tevezés</li>
</ol> 

#### <h2> Megvalósítás </h2>

<h3> <Strong> 1. Megtervezzük a projekt alapjait </strong> </h3>
<h3> <Strong> 2. Markdown megírása </strong> </h3>
<h3> <Strong> 3. Tervrajzot készítünk a Java.fx-hez </strong> </h3>
<h3> <Strong> 4. Java programozása</strong> </h3>
<h3> <Strong> 5. PPT megtervezése</strong> </h3>
<h3> <Strong> 6. PPT Elkészítése</strong> </h3>
<h3> <Strong> 7. Projekt bemutatására való felkészülés </strong> </h3>
<h3> <Strong> 8. Projekt összegzése </strong> </h3>
<h3> <Strong> 9. Teljes egész projekt leadása </strong> </h3>

<h3> <Strong> A tervezési pontok között folyamatos ellenőrzés van </strong> </h3>
