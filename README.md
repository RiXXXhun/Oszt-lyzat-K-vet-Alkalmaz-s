\# Osztalyzat követő alkalmazás 

Csoport tagok
-------------

**Tóth Zoltán**  
**Nagy-Eperjesi Richárd**  
**Sali Levente**  
####

Csapat név
----------

**Champions**

Választott téma:
----------------

**Osztályzat-követő alkalmazás**  

##### 
A feladat során egy olyan alkalmazást kell elkészíteni, ahol egy tanuló tudja rögzíteni a jegyeit tárgyanként. 
Egy külön pane-en lehessen új tárgyat felvinni. A fő pane-en lenyíló listával lehessen szűrni tárgyakat. A jegyek táblázata alatt jelenjen meg az adott tárgy átlaga.  
Az adatbázis táblájában minden bejegyzéshez rögzítésre kerüljön a tárgy, időpont, jegy, témakör (pl mire kapta a diák az adott jegyet). A jegyekről lehessen pdf formátumban jelentést készíteni egy meghatározott időszakra és egy vagy több meghatározott tárgyra.

####

Projektet érintő tantárgyak
---------------------------

**IKT Projektmunka**  
**Asztali alkalmazások fejlesztése 2.**  
**Szoftvertesztelés**  
####

Feladat leírása
---------------

**A feladat során 2-3 fős csapatokban kell megoldanotok a lejjebb felsorolt témák egyikét. Szabadon is választhatók témák, de előtte egyeztetni kell róla egy oktatóval!  
A projektben egy teljes értékű JavaFX alkalmazást kell implementálni, teszteléseket végezni, dokumentálni, végül prezentálni.  
Ebből kifolyólag a projektre 3 tárgyból is kaptok értékelést: Asztali alkalmazás fejlesztés 2, Szoftvertesztelés, IKT projektmunka. Mindegyik csapattagnak részt kell vennie a kódolási, tesztelési, dokumentációs és prezentációs folya- matokban! Ajánlott, hogy mindenki a saját maga által implementált funkciókat tesztelje, dokumen- tálja és prezentálja! Minden csapatban lehetőleg azonos képességű tagok legyenek!**  
####

Elvárások
---------

### **Asztali alkalmazás fejlesztés 2**

1.
  Teljes értékű JavaFX alkalmazás: A hangsúly a funkcionalitáson van, a design másodlagos!  
  Félkész funkciók ne legyenek az alkalmazásban! Ha megakadtok egy funkció fejlesztése közben, az órákon megbeszéljük.  
  A projektben az MVC struktúrát kell alkalmazni (tehát külön-külön fájlokban és osztályokban legyen a nézet, a modell és a kontroller).  
  Az alkalmazásban a nagyon eltérő funkciókat külön-külön Pane-en kell megjeleníteni. Ezeken kívül JDK17-et és Maven csomagolót kell használni!
  
3.
  Kivétel- és hibakezelés: Az alkalmazásban minden előforduló kivételt és hibát le kell kezelni, ennek előfordulásakor adj vissza hibaüzenetet piros betűszínnel egy Label-be! Ha nem történt hiba és sikeresen lefutott egy funkció, adj vissza fekete / zöld betűszínnel egy tájékoztató üzenetet ugyanabban a Label-ben!
  
3.
  Adatbázis használata JDBC-vel: Az adatbázis funkciókat külön, erre a célra kialakított osztályban kell implementálni.  
  Adatbázishoz való csatlakozás után érdemes rávizsgálni, hogy létezik-e a kívánt adatbázis és táblák.  
  Így ha nem létezik, akkor az alkalmazásból létre is tudjuk hozni őket. Célszerű Derby-t használni, viszont egyéb MySQL megvalósítás is elfogadott.
  
4. 
  Clean code alapelvek használata: A kód legyen letisztult, a különböző részek megfelelően tagolva, indentálva! Figyelni kell, hogy a különböző funkciók külön-külön metódusokba / függvényekbe legyenek tagolva, ne egybe ömlesztve (+ újra felhasználhatóság)! Értelmes változó neveket kell használni, legyenek beszédesek, hogy kitalálható legyen, mire is jók. Célszerű kommentelni is, melyik részegység mire való.
  
5.
  Szoftver ergonómia: A feliratok jól láthatóak legyenek, a gombok megfelelően kattinthatóak legyenek (ne túl kicsi, ne túl nagy)!
  

### **Szoftvertesztelés**

1.Készítsd el a projekted dokumentációjához az osztály diagramot! A diagram tartalmazza a megoldás összes osztályát, az osztályok adattagjait és metódusait továbbá a (ha van) jelöld nyilakkal az öröklődéseket [Minta](https://www.drawio.com/assets/img/blog/class-diagram-example.png)
  
2.A program gyenge pontjain (ahol felhasználótól kérünk adatot), kezelje megfelelően egy tanult módzserrel úgy, hogy ne okozhasson hibát a felhasználó!
  
3.A programban valahol használjon legalább egy saját készítésű kivételt!
  
4.Készítsen tesztelési útmutatót a projektjéhez! Ez egy reademe.md [segédlet](https://en.wikipedia.org/wiki/Markdown) fájl legyen, amiben lépésről lépésre bemutatja az alkalmazás felhasználását. Figyeljen arra, hogy a program minden funkcióját bemutassa vele! Például:
  

###### Szám esetén:

\- Nem egyenlő vizsgálat: túl kicsi opció  
\- Egyenlő vizsgálat: megfelelő opció  
\- Nem szám vizsgálat: rossz bemenet  

###### Szöveg esetén

\- Üres vizsgálat: üres bemeneti mező  
\- Megfelelő vizsgálat: jó bemenő adat  
\- Hibás vizsgálat: nem megfelelő adat  
  
5.  Készítsen Unit teszteket a programhoz! Válasszon ki legalább 2 függvényt, amelyhez elkészíti a Unit teszteteket. Minden függvényhez készítsen egy egyenlőség vizsgálatot legalább 3 opcióval
  

### **IKT projektmunka**

1.Bemutató készítése az elkészített szoftverhez.
  
2.A bemutatónak legalább 15 diát kell tartalmaznia, mely az alábbi felépítést tartalmazza:
  
\- A szoftver céljának rövid bemutatása  
\- A szoftver felépítése (menürendszer, képernyőképek, stb.)  
\- A szoftver használatának bemutatása  
\- Az elkészített szoftver továbbfejlesztési lehetőségei  
  
3.A diákon maximum 28-as betűméret alkalmazható
  
4.Figyelni kell a helyesírásra, nyelvhelyességre (zavaró elírások, helyesírási hibák, stb. PONTLEVONÁST fog jelenteni)
  
5.Az elkészített bemutató előadása
  

  
####

Munkamegosztás
--------------

### **Tóth Zoltán**

1.  Java.fx tervezés és megvalóítása
2.  Java programozás és java.fx tervezés

### **Nagy-Eperjesi Richárd**

1.  Markdown (.md)
2.  Java programozás és java.fx tervezés

### **Sali Levente**

1.  Power Point prezentáció készítés
2.  Java programozás és java.fx tevezés

####

Megvalósítás
------------

### **1\. Megtervezzük a projekt alapjait**

### **2\. Markdown megírása**

### **3\. Tervrajzot készítünk a Java.fx-hez**

### **4\. Java programozása**

### **5\. PPT megtervezése**

### **6\. PPT Elkészítése**

### **7\. Projekt bemutatására való felkészülés**

### **8\. Projekt összegzése**

### **9\. Teljes egész projekt leadása**

### **A tervezési pontok között folyamatos ellenőrzés van**
