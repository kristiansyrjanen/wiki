## Kuumailmapuhallinasemalla juottaminen

### Puhallinasema
Tässä kyse spesifisti "SMD rework station" -tyyppisestä puhaltimesta, 
ei perinteisestä "pistoolimallisesta" kuumailmapuhaltimesta. 

![SMD REWORK](geneerinen_puhallinasema.jpg)
*Tämäntapainen OK*

![HOT_AIR](geneerinen_kuumailmapistooli.jpg)
*EI Tällainen*

### Työpiste / Varustelu
![SMD_REWORK -työpiste](telok_puhallustyo_numeroitu.jpg)
*Puhallusaseman käyttö*
1) Puhallinkahvan teline
   * Puhallinkahva kannattaa kiinnittää mahdollisuuksien mukaan tukevasti telineeseen,
     jossa sitä on helppo suunnata.
   * Puhallin pysyy itsenäisesti paikoillaan, joka helpottaa muita työvaiheita.

2) Lämmön rajaus
   * Riippuen sijainnista levyllä, komponenttien koosta/määrästä ja pöydän materiaalista,
     kannattaa pöytäpinta suojata esim puu- tai alumiinilevyllä.
   * Juotettava alue kannattaa levylläkin rajata esimerkiksi alumiinisilla listoilla,
     tämä nopeuttaa halutun kohdan lämpenemistä ja suojaa ympärillä olevia komponentteja lämmöltä.

3) Työkalut
   * Työkalut kannattaa hakea etukäteen esille, ei lähteä kaivamaan laatikoista kesken työn.
   * Irroituksessa käytännössä tarvitaan pinsetit / muu lämpöä kestävä piirin nostotyökalu.
   * Kiinnityksessä hieman enemmän, ks. aiheen kohta.

### Piirien irroitus / desoldering
Jos piiri on tulossa uudelleen käyttöön, 
sen tulisi olla suhteellisen kuiva (epoksi imee hieman kosteutta)<sup>1</sup>
ja erityisen korkeita lämpötiloja vältettävä.

Jos levy on tulossa uudelleen käyttöön, 
kannattaa huolehtia että muoviset liittimet ja muut herkät komponentit ovat suojattuja.<sup>2</sup>
 
Piirien irroitus on suhteellisen yksinkertaista. 
1) Lämmitys
   * Osoita puhallin kohti irrotettavaa piiriä, mutta älä tuo puhallinta liian lähelle.
     Ohjeellisesti muutama sentti on "minimietäisyys" ja isommilla piireillä tätäkin kauempana,
     jotta lämpö leviää koko piirin alueelle.

2) Odota
   * Odota rauhassa, että tina piirin jaloilta (ja mahdollisesti alta) on sulanut. 
     Tässä vaiheessa hosuminen voi johtaa sekä levyn että piirin vahingoittumiseen. <sup>3</sup>

3) Irroitus
   * Kun tina piirin jaloilta alkaa kiillellä (sula pinta), 
     voi piiriä alkaa varovasti nostaa esim pinsettien avulla. 
     Tässä "itsesulkeutuvat" pinsetit ovat kätevät. Piirin nostaminen EI tarvitse voimaa,
     mikäli tuntuu, että piiri ei lähde helposti, odota sulamista äläkä revi.

4) Piirin irrottua sen voi laskea jäähtymään tasolle, 
   joka ei sula kiinni jalkoihin tai vahingoitu lämmöstä.

5) Sammuta lopuksi puhallin puhaltimen ohjeiden mukaisesti

### Piirien kiinnitys / reflow-soldering
Puhaltimella juottaminen on melko pitkälti sama, kuin uunittaminen. 
Ainut merkittävä ero on lämmön jakautuminen ja tasaisuus. 
Suuria kuparialueita sisältäviä levyjä voi olla hyvin haastavaa juottaa pelkällä puhaltimella!

Lähtökohtainen oletus on, että levy on käyttämätön. 
Käytännössä siis pädeillä ei ole valmiiksi tinamöykkyjä tai vakavia hapettumia. 
Kolvin ja tinaimusukan kanssa pääsee eroon liikatinasta.

Tarvittavia työvälineitä piirien juottamiseen: Fluksi-kynä, tinapasta-ruisku,
pinsetit ja mahdollisesti suurennusta (suurennuslasivalaisin, stereomikroskooppi jne)

Käytetystä tinapastasta riippuen fluksia voi tarvita myös puhtailla levyillä, 
mutta erityisesti käytettyjen levyjen kanssa hapettumat ovat yleinen ongelma.

1) Levitä fluksia pädeille
   * Fluksikynä on tässä helppo, käytännössä vain värität pädit kevyesti. 
   * Fluksia ei tarvita niin paljon, että levy "lainehtii", ohut kalvo riittää.
   * Tämä työvaihe ei aina ole pakollinen, mutta lähtökohtaisesti ei ikinä haitallinen.<sup>4</sup>

2) Levitä tinapastaa pädeille
   * Tinapastaa tarvitaan "yllättävän vähän". 
     Erityisesti tiheän jalkavälin komponenteilla tinapastaa tulee helposti liikaa.
   * Tinapastalle tarkotetut ruiskut ovat tässä huomattavasti käytännöllisempiä 
     kuin perinteiset injektioruiskut. 
   * Levityksessä käyneet vahingot on helppo pyyhkiä pois pumpulipuikolla tai paperilla. 

3) Lado komponentit
   * Asettele komponentit levylle. Komponentit tulee laskea "suoraan ylhäältä",
     jotta tinapasta ei leviä. Tarvittaessa poista komponetti ja korvaa sotkeutunut pasta.
   * Asettelun tulee olla "riittävän tarkkaa", komponenttien jalkojen tulisi 
     olla vain omalla pädillään, ei kahden pädin välillä. 
     Komponentit suoristuvat hieman juotosvaiheessa pintajännityksen myötä.

4) Juottaminen
   * Pyri nostamaan lämpötilaa tasaisesti koko juotettavalla alueella. 
   * Kun tinapasta alkaa sulaa (matta pasta => kiiltävä metalli), 
     kannattaa lämpöä pitää tässä vielä 10-30 sekuntia. Jos piirin alla on lämpöpädi, 
     tämän lämpenenminen vie enemmän aikaa kuin reunapädien!
   * Kun juotos on "valmis", poista lämmitys ja anna levyn jäähtyä paikoillaan 
     reilusti alle tinan sulamispisteen.<sup>5</sup>

5) Tarkasta juotokset
   * Kuten muillakin menetelmillä, 
     myös puhallinjuottamisella on hyvä tarkastaa kaikki juotokset (varsinkin aloittelijana).
   * Tehokas suurennus ja johtavuusmittaus yleismittarilla ovat tehokkaita apuvälineitä. 
   * Onko pasta jostain sulamatta? Onko johonkin muodostunut oikosulkuja? 
     Onko jotkin liitokset kylmäjuottuneet?

### Puhaltimen asetukset ja yleistä
Lähtökohtaisesti on puhalimen kannalta parempi, 
jos lämpötila on mahdollisimman matala ja puhallus korkeampi. 
Puhallustehoa ei kuitenkaan voi varsinkaan juottaessa nostaa "rajatta", 
komponentteja ei ole tarkoitus puhaltaa pois levyltä. 

Ohjeellisesti lämpötila kannattaa säätää välille 350-400, 
riippuen levyn kuparialueista ja käytetystä pastasta. Matalampi lämpötila ei aina riitä, 
varsinkin jos lämpö pääsee karkaamaan ympäristöön liian tehokkaasti. 

Monissa puhallusasemissa kahvan palautus "lepotelineeseensä" aloittaa puhaltimen jäähdytyksen,
eli sammuttaa lämpövastuksen mutta ei puhallusta. 
Tämä on usein ohjeistettu/vaadittu sammutustapa puhaltimen pitkäikäisyyden takaamiseksi. 

### Varoituksien ym selityksiä

1) Jos piiri on liian kostea, 
   lämmittäminen voi höyrystää tämän kosteuden ja laajentuminen rikkoa piirin.

2) Uunitukseen tarkoitetut muovit lähtökohtaisesti kestävät lämpöä, mutta puhaltimella
   lämpötila ei nouse aivan yhtä tasaisesti ja yleensä nousee paikoittain huomattavasti
   korkeammaksi kuin uunissa.

3) Liian aikaisessa vaiheessa piirin repiminen voi taivutella jalkoja ja/tai irrottaa pädejä piirilevyltä.
   Kumpikaan ei välttämättä johda suoraan elektroniikkajätteeseen, 
   mutta aiheuttaa aivan turhaan lisävaivaa.

4) Mikäli kyseessä on nanoampeereita käyttävä levy (ts. ei ikinä näppäimistö), 
   voi fluksitahroista (piirien alla) aiheutua liian "hyviä johtimia", eli vain muutamia megaohmeja.
   Mikäli levyn "oikeat" vastukst ovat kymmeniä megaohmeja, tämä on ongelma.

5) Tärinä juotoksen hyytyessä voi aiheuttaa juotokseen näkyviä ja näkymättömiä halkeamia.
   Nämä halkeamat voivat heikentää juotoksen kestävyyttä jatkotärinälle tai jopa  
   tehdä juotoksesta johtamattoman. 
