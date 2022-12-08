# Olomuodon muutoksia

Kun aineeseen tuodaan lämpöenergiaa, niin aineen rakenneosien nopeus kasvaa. Tietyssä lämpötilassa nopeus kasvaa niin paljon, että rakenneosat pääsevät pois paikoiltaan tai jopa kokonaan poistumaan muiden rakenneosien luota. Kun aine jäähtyy eli menettää lämpöenergiaa, niin rakenneosien liikkumavapaus vähenee vastaavalla tavalla. Tällöin puhutaan olomuodon muutoksista: kiinteä - neste - kaasu.

Eri olomuodoissa aineen rakenneosien vapaus muuttuu: 
- Kiinteässä aineessa osat ovat kiinni toisissaan. Aineella on koko ja muoto, eikä se puristu kokoon. Aine voi olla kiteistä (rakenneosat ovat tietyssä järjestyksessä) tai amorfista. Rakenneosaset eivät ole täysin liikkumatta, vaan ne värähtelevät, mutta vain omilla paikoillaan.
- Nesteessä rakenneosat voivat liikkua toistensa ohi. Aine on astian muotoinen eikä juurikaan puristu kokoon.
- Kaasussa rakenneosat voivat liikkua vapaasti. Aine ottaa astian muodon ja tilavuuden. Ainetta voidaan puristaa kokoon.

Jokaisella aineella on sulamispiste ja kiehumispiste. Sulamispisteessä aine muuttuu kiinteästä nestemäiseksi (tai toisinpäin) ja kiehumispisteessä nesteestä kaasuksi (tai toisinpäin). Joillakin aineilla nämä lämpötilat ovat sellaisia, että aine pysyy samassa olomuodossa. Esimerkiksi ilman kiehumispiste on $-196^{\circ}~\text{C}$, joten saamme koko ajan hengittää kaasumaista ilmaa. Joillakin aineilla taas sulamispiste voidaan saavuttaa kuumentamalla. Raudan sulamispiste on noin 1500 astetta, mikä mahdollistaa sen, että voimme rakentaa raudasta kiinteitä pysyviä rakenteita, mutta kuitenkin tarvittaessa sulattaakin rautaa. Vesi on erityistapaus aineiden joukossa. Vettä esiintyy maapallon olosuhteissa kaikissa kolmessa olomuodossa.

Energian suunta aineeseen tai aineesta poispäin riippuu siitä, millainen olomuodon muutos on kyseessä:
- Höyrystyminen nesteeksi kaasuksi sitoo lämpöä.
- Tiivistymisessä kaasusta nesteeksi vapautuu lämpöä.
- Sulaminen kiinteästä aineesta nesteeksi sitoo lämpöä.
- Jähmettyminen nesteestä kiinteäksi aineeksi vapauttaa lämpöä.

## Lämpöenergia olomuodon muutoksissa

Olomuodon muutos sitoo energiaa. Yleensä aineen lämpötila nousee, kun ainetta lämmitetään. Jos kuitenkin aine sattuu lämmityksessä saavuttamaan sen lämpötilan, jossa olomuodon muutos tapahtuu, niin kaikki aineeseen tuotava lämpöenergia kuluu olomuodon muutoksiin. Jääpala pysyy 0-asteisena, kunnes se on kokonaan sulanut, eikä kattilassa kiehuvan veden lämpötila nouse 100 asteesta.

Olomuodon muutokseen tarvittava energia riippuu aineen **sulamis- tai höyrystymislämmöstä** ja aineen massasta $m$. Sulamislämmölle käytetään tässä merkintää $s$ ja höyrystymislämmölle merkintää $r$. Tällöin sulamiseen kuluva energia on $Q=sm$ ja höyrystymiseen kuluva energia on $Q=rm$.

Sulamis- ja höyrystymislämmöt ovat sitä suurempia, mitä vahvemmat voimat aineet rakenneosien välillä on. Ionisidos on yleensä lujempi kuin molekyylisidos. Molekyyleistä koostuvassa aineissa molekyylien koko vaikuttaa energian määrään. Veden sulamis- ja höyrystymislämmöt ovat valtavan suuria. Sulamislämpö on $s=333~\text{kJ/kg}$ ja höyrystymislämpö on $s=2260~\text{kJ/kg}$. Esimerkiksi jäätyneen järven sulaminen keväällä sitoo erittäin paljon lämpöenergiaa. Sen jälkeen tarvitaan vielä paljon energiaa, ennen kuin vesi on lämmintä.

Yleisesti lämpöenergiaan liittyvissä laskuissa täytyy huomioida se, sisältyykö tapahtumaan sekä lämpenemistä (tai jäähtymistä) että olomuodon muutoksia. Kaikki nämä tapahtumat pitää huomioida energiamäärän laskemisessa.

::::{admonition} Esimerkki

Ulkona on 18 astetta pakkasta. Tuodaan sisälle 3 kg jäätä. Jää lämpenee sulamispisteeseensä, sulaa ja sen jälkeen lämpenee huoneenlämpötilaan, 20 asteeseen. Kuinka paljon energiaa sitoutuu? Jään ominaislämpökapasiteetti on $c_{\text{jää}}=2100~\frac{\text{J}}{\text{kg}}$.

:::{admonition} Ratkaisu
:class: tip, dropdown

Kokonaisenergia koostuu jään lämpenemisestä nollaan asteeseen (lämpötilan muutos $\Delta T_1$), jään sulamisesta vedeksi, ja veden lämpenemisestä 20 asteeseen (lämpötilan muutos $\Delta T_2$). Veden sulamislämpö on $s=333~\text{kJ/kg}$ ja veden ominaislämpökapasiteetti on $c_{\text{vesi}}=4190~\frac{\text{J}}{\text{kg}}$. Massana käytetään $m=3~\text{kg}$. Laskukaava on siis

$Q=c_{\text{jää}} m \Delta T_1 + sm + c_{\text{vesi}} m \Delta T_2$

eli

$Q=2100~\frac{\text{J}}{\text{kg}} \cdot 3~\text{kg} \cdot 18~\text{K} + 333000\text{J/kg} \cdot 3~\text{kg} + 4190~\frac{\text{J}}{\text{kg}} \cdot 3~\text{kg}\cdot 20~\text{K} = 1 363 800~\text{J}$

Lämpöä sitoutuu noin 1.4 megajoulea.

:::

::::

::::{admonition} Esimerkki

Retkikeittimen teho on noin 1000 wattia. Kuinka kauan kestää valmistaa kyseisellä keittimellä 500 g kiehuvaa vettä lumesta, jonka
lämpötila aluksi on -15 astetta? Lumen ominaislämpökapasiteetti ja sulamislämpö ovat samat kuin jään.

:::{admonition} Ratkaisu
:class: tip, dropdown

Samalla tavalla kuin edellisessä esimerkissä saadaan energian määräksi

$Q=2100~\frac{\text{J}}{\text{kg}} \cdot 0.5~\text{kg} \cdot 15~\text{K} + 333000\text{J/kg} \cdot 0.5~\text{kg} + 4190~\frac{\text{J}}{\text{kg}} \cdot 0.5~\text{kg}\cdot 100~\text{K}$

$ Q = 391 750 J~\text{J}$

Energia $Q$, retkikeittimen teho $P$ ja tarvittava aika $t$ ovat yhteydessä toisiinsa kaavalla $Q=Pt$. Ajaksi saadaan siis 

$t=\frac{Q}{P}=\frac{391 750~\text{J}}{1000~\text{W}}=392~\text{s}$

Aikaa kuluu noin 6.5 minuuttia.

:::

::::

::::{admonition} Esimerkki

Terästehtaan valukoneeseen syötetään sulaa 1590-asteista terästä, joka jäähdytetään vedellä 1200-asteiseksi kiinteäksi teräkseksi. Olomuoto muuttuu 1350 asteen kohdalla. Yhdessä valussa terästä valmistuu 120 000 kg. Valu kestää 1h 15 min. Jäähdytysvesi tuodaan koneeseen 15-asteisena, ja se poistuu 35-asteisena. Laske jäähdytysveden massavirta.

Tarvittavat suureet: veden ominaislämpökapasiteetti $c_v=4190~\frac{\text{J}}{\text{kg}}$, sulan teräksen ominaislämpökapasiteetti $c={t,s}=430 ~\frac{\text{J}}{\text{kg}}$, kiinteän teräksen ominaislämpökapasiteetti $c_{t,k}=470~\frac{\text{J}}{\text{kg}}$, teräksen sulamislämpö $s=270000\text{J/kg}$.


:::{admonition} Ratkaisu
:class: tip, dropdown

Vesi vastaanottaa lämpöenergiaa yhtä paljon kuin teräs luovuttaa sitä. Teräksen massa on $m_t=120000~\text{kg}$.

Ensimmäisessä vaiheessa, kun teräs jäähtyy sulamispisteeseensä, lämpötilan muutos on $\Delta T_1 = (1590-1350)~\text{K}=240~\text{K}$. Vapautuvan energian määrä on 

$Q_1=c_{t,s} m_t \Delta T_1 = 430 ~\frac{\text{J}}{\text{kg}}\cdot 120000~\text{kg} \cdot 240~\text{K}= 12.384~\text{GJ}$

Teräksen kiinteytessä vapautuu energia

$Q_2=sm_t = 270000\text{J/kg} \cdot 120000~\text{kg} = 32.4~\text{GJ}$

Kiinteän teräksen jäähtyessä lämpötilanmuutos on $\Delta T_2 = (1350-1200)~\text{K} = 150~\text{K}$, ja vapautuvan energian määrä on

$Q_3=c_{t,k} m_t \Delta T_2 = 470 ~\frac{\text{J}}{\text{kg}}\cdot 120000~\text{kg} \cdot 150~\text{K}= 8.46~\text{GJ}$

Yhteensä energiaa vapautuu $Q=Q_1+Q_2+Q_3=53.244~\text{GJ}$

Vesi ottaa vastaan saman energiamäärän. Tarvittava massa $m_v$ saadaan yhtälöstä $Q=c_v m_v \Delta T_3$, missä $\Delta T_3 = 20~\text{K}$. Tästä ratkeaa

$m_v=\frac{Q}{c_v \Delta T_3} = \frac{53.244\cdot 10^9~\text{J}}{4190~\frac{\text{J}}{\text{kg}} \cdot 20~\text{K}}=635 370~\text{kg}$

Edellä lasketun massan pitää virrata järjestelmän läpi valuajassa 1 h 15 min eli 4500 sekunnissa. Massavirta on siis 

$q_m = \frac{635370~\text{kg}}{4500~\text{s}} = 141~\frac{\text{kg}}{\text{s}}$

Tilavuusvirtana tämä vastaa 141 litraa sekunnissa.

:::

::::

::::{admonition} Esimerkki

Oletetaan, että pakastin toimii 120 W teholla, kun pakastimen sisälämpötila on -18 astetta. Toiminta perustuu kylmäaineen höyrystymiseen ja tiivistymiseen. Kylmäaineen höyrystymislämpö on $r=216~\text{kJ/kg}$. Mikä on kylmäaineen massavirta putkistossa?

:::{admonition} Ratkaisu
:class: tip, dropdown

Teho 120 W tarkoittaa sitä, että yhdessä sekunnissa pakastin kuluttaa 120 joulea energiaa. Kyseinen energiamäärä $Q$ sitoutuu, kun massa $m$ kylmäainetta höyrystyy. Yhtälöstä $Q=mr$ saadaan $m=Q/r$, joten kylmäainetta tarvitaan sekunnissa

$m=\frac{120~\text{J}}{216000~\frac{\text{J}}{\text{kg}}}=0.000555~\text{kg}$ eli noin 0.56 grammaa.

Jos massavirta halutaan ilmaista yksikössä kg/min, niin tämä lukuarvo on $0.56~\frac{\text{g}}{\text{s}}\cdot 60~\frac{\text{s}}{\text{min}} = 34~\frac{\text{g}}{\text{min}}$.

:::

::::

::::{admonition} Esimerkki

Astiassa on 1000 g vettä 10 asteen lämpötilassa. Astiaan laitetaan 200 g jääpala, jonka lämpötila on 0 astetta. Mikä on seoksen loppulämpötila ja koostumus? Oletetaan, että astia on lämpöeristetyssä laatikossa, eli huoneilma ei lämmitä vettä.

:::{admonition} Ratkaisu
:class: tip, dropdown

Oletetaan, että jää sulaa kokonaan. Tällöin vesi luovuttaa lämpöenergiaa määrän $Q$, joka riittää jään sulattamiseen ja sulaneen veden lämmittämiseen. Sulamiseen kuluu energiaa määrä $sm_j$, missä $s=333000~\text{J/kg}$ on veden sulamislämpö ja $m_j=0.2~\text{kg}$ on jääpalan massa. Lämmittämiseen kuluu energia $cm\Delta T_j$ missä $c=4190~\frac{\text{J}}{\text{kg}\cdot\text{K}}$ on veden ominaislämpökapasiteetti ja $\Delta T_j = (T_l-0)~\text{K}=T_l~\text{K}$ on jääpalasta sulaneen veden lämpötilan muutos, kun seoksen loppulämpötila on $T_l$. Siis vesi luovuttaa energian

$Q=sm_j+cm_j\Delta T_j$

Toisaalta veden luovuttama lämpöenergia voidaan ilmaista myös muodossa $Q=cm_v \Delta T_v$, missä $m_v=1~\text{kg}$ on veden massa ja $\Delta T_v = (10-T_l)~\text{K}$ on veden lämpötilan muutos.

Saadaan siis yhtälö:

$sm_j+cm_j\Delta T_l=cm_v \Delta T_v$

Sijoitetaan lukuarvot:

$333000~\text{J/kg}\cdot 0.2~\text{kg}+4190~\frac{\text{J}}{\text{kg}\cdot\text{K}}\cdot 0.2~\text{kg}\cdot T_l = 4190~\frac{\text{J}}{\text{kg}\cdot\text{K}}\cdot 1~\text{kg} \cdot (10-T_l)~\text{K}$

Yhtälön ratkaisuksi tulee $T_l=-4.9$ ja yksikkönä on Celsius-aste, koska jään ja veden alkuperäisetkin lämpötilat oli annettu Celsius-asteina. Tulos ei ole järkevä, sillä sulaneen veden lämpötila ei voi olla pakkasen puolella.

Lasketaan lasku uudelleen olettaen, että astiassa olevan veden energia ei riitä koko jääpalan sulattamiseen. Jäästä sulaa massa $x$. Tällöin veden luovuttama energia on $Q=sx$. Loppulämpötilan $T_l$ on oltava 0 astetta, sillä niin kauan kuin jäätä on jäljellä, kaikki lämpöenergia kuluu sen sulamiseen. Tällöin veden lämpötilan muutos on $\Delta T = 10~\text{K}$, ja yhtälöksi muodostuu

$sx=c m_v \Delta T$,

josta ratkeaa

$x= \frac{c m_v \Delta T}{s} = \frac{4190~\frac{\text{J}}{\text{kg}\cdot\text{K}}\cdot 1~\text{kg}~\cdot 10~\text{K}}{333000\text{J/kg}} = 0.126~\text{kg}$

Jäätä sulaa siis 126 g. Jäljelle jäi 200 g- 126 g = 74 g, joten lopuksi astiassa on 1126 g vettä ja 74 g jäätä, ja seoksen lämpötila on 0 astetta.

:::

::::