# Jäähdytyskoneet

Jäähdytyskoneiden toiminta perustuu olomuodon muutoksiin: höyrystymiseen ja tiivistymiseen. Olomuodon muutoksia säädellään paineen avulla. Eri aineiden tutut sulamis- ja kiehumispisteet on määritelty normaalissa ilmanpaineessa. Ali- tai ylipaine normaaliin paineeseen verrattuna voi muuttaa näitä lämpötiloja merkittävästi

## Faasidiagrammi

Lämpötilaa, jossa aine muuttaa olomuotoaan eri paineolosuhteissa, kuvataan faasidiagrammilla. Alla on esimerkkinä veden faasidiagrammi.

![Veden faasidagrammi](phase_diagram_of_water.svg)
Kuva: Cmglee, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=14939155

Veden faasidiagrammin oikeassa alareunassa, oranssilla värillä kuvattuna, vesi on kaasumaisessa olomuodossa. Kiehumispiste, 100 astetta, pätee vain 101325 pascalin paineessa. Mitä pienempi paine on, sitä matalammassa lämpötilassa vesi kiehuu. Veden jäätymispisteeseen paine vaikuttaa vähemmän, jos ali- tai ylipaine ei ole valtavan suuri (jäätä kuvaavan sinisen ja nestettä kuvaavan vihreän alueen raja on lähes pystysuora). Roomalaiset numerot kuvaavat jään erilaisia muotoja.

Kuvaajaan on merkitty myös veden kriittinen piste (critical point). Jos aineen lämpötila on suurempi kuin sen kriittinen
lämpötila, sitä ei voida enää nesteyttää. Lisäksi kuvassa on kolmoispiste (triple point). Kolmoispiste vastaa sellaista painetta ja lämpötilaa, jossa kaikki kolme olomuotoa ovat tasapainossa. Vedellä kolmoispiste on kohdassa jossa paine on 1 bar ja lämpötila noin 0.01 Celsius-astetta. Näissä oloissa jää, vesi ja vesihöyry voivat olla tasapainossa niin, että kunkin määrä pysyy vakiona.

## Jäähdytyskoneen toiminta

Jäähdytyskonetta voidaan kuvata piirinä, jossa jäähdytysaine kiertää putkessa, ja vuorotellen höyrystyy ja tiivistyy. Piirin osaan, jonka nimi on höyrystin, muodostetaan pumpun avulla alipaine. Se saa jäähdytysaineen eli kylmäaineen höyrystymään. Kun ainetta, jonka höyrystymislämpö on $r$, höyrystyy massa $m$, niin lämpöenergiaa sitoutuu määrä $Q=mr$. Näin esimerkiksi ilma jääkaapin sisällä jäähtyy.

Piirin osaa, jossa kylmäaine tiiviistyy höyrystä nesteeksi, kutsutaan nimellä lauhdutin. Sinne luodaan kompressorilla ylipaine. Tiivistyessään aine luovuttaa saman verran lämpöä $Q=mr$, joka siihen sitoutui höyrystimessä. Lämpö siirtyy esimerkiksi jääkaapin sisältä huoneilmaan.

Aiemmin tarkasteltiin lämpövoimakoneita. Lämpövoimakoneet ottavat energian $Q_H$ kuumasäiliöstä, muuttavat osan siitä työksi $W$ ja luovuttavat lopun energian $Q_C$ kylmäsäiliöön. Koska energia säilyy, niin $Q_H=Q_C+W$. Lämpövoimakoneen hyötysuhde on 

$\eta=\frac{W}{Q_H}=\frac{Q_H-Q_C}{Q_H}$

Jäähdytyskone toimii päinvastoin: se ottaa energian $Q_C$ kylmäsäiliöstä, ja luovuttaa sen ulkoisen työn $W$ avulla kuumasäiliöön energiana $Q_H$. Energian säilymislain mukaisesti edelleen voimassa on kaava $Q_H=Q_C+W$. Jäähdytyskoneelle määritellään hyötysuhteen sijasta niinsanottu tehokerroin $\epsilon_R$. Se kertoo, kuinka paljon energiaa kone poistaa kylmäsäiliöstä verrattuna ulkoiseen työhön:

$\epsilon_R=\frac{Q_C}{W}=\frac{Q_C}{Q_H-Q_C}$

Jäähdytyskoneen tehokerrointa kutsutaan myös nimellä kylmäkerroin. Yksinkertaisesti se kuvaa sitä, kuinka monta kilowattituntia lämpöä esimerkiksi jääkaapista poistuu yhdellä kilowattitunnilla sähköä.

Lämpöpumppukin toimii ikään kuin jääkaappi. Lämpöpumpussa kylmäsäiliönä toimii ulkoilma, ja ilman höyrystymisessä sitoutunut lämpö siirretään sisäilmaan. Lämpöpumpun tehokerroin on $\epsilon_P$, ja se kuvaa lämpöpumpun kykyä siirtää huoneilmaan lämpöä:

$\epsilon_P=\frac{Q_H}{W}=\frac{Q_H}{Q_H-Q_C}$

Lämpöpumpun tehokerrointa kutsutaan nimellä lämpökerroin. Se ilmoittaa, kuinka monta kilowattituntia lämpöä se tuo huoneeseen yhdellä kilowattitunnilla sähköä.

Kummastakin tehokertoimesta käytetään usein myös nimitystä COP (coefficient of performance). Laskukaavoihin voi energiasuureiden paikalle sijoittaa myös vastaavat tehosuureet:

$\Phi_C=P+\Phi_H$, $\epsilon_R=\frac{\Phi_C}{P}=\frac{\Phi_C}{\Phi_H-\Phi_C}$, $\epsilon_P=\frac{\Phi_H}{P}=\frac{\Phi_H}{\Phi_H-\Phi_C}$

::::{admonition} Esimerkki

a) Lämpöpumpun COP on 4.0. Se tuottaa sisäilmaan lämpöä 2000 W teholla. Mikä on laitteen sähkönkulutus, ja millä teholla lämpöä poistuu ulkoilmasta?

b) Jääkaapin sähkönkulutus on 100 W, ja se lämmittää huonetta 600 W teholla. Mikä on jääkaapin COP, ja millä teholla lämpöä poistuu jääkaapista?

:::{admonition} Ratkaisu
:class: tip, dropdown

a) Ratkaistaan teho $P$ yhtälöstä $\epsilon_P=\frac{\Phi_H}{P}$:

$P=\frac{\Phi_H}{\epsilon_P}=\frac{2000~\text{W}}{4.0}=500~\text{W}$

Ulkoilmasta poistuvaksi lämpötehoksi saadaan samasta yhtälöstä

$\Phi_C=\Phi_H \frac{\epsilon_P-1}{\epsilon_P}=2000~\text{W}\frac{3}{4}=1500~\text{W}$

tai laskemalla $\Phi_C=\Phi_H-P=2000~\text{W}-500~\text{W}=1500~\text{W}$

b) Lasketaan ensin jääkaapista poistuva lämpöteho:

$\Phi_C=\Phi_H-P=600~\text{W}-100~\text{W}=500~\text{W}$

Tehokertoimeksi saadaan 

$\epsilon_R=\frac{\Phi_C}{P}=\frac{500~\text{W}}{100~\text{W}}=5.0$

:::

::::

Tehokertoimille voidaan laskea Carnot'n koneen mukainen teoreettinen yläraja. Jos kuumasäiliön lämpötila on $T_H$ ja kylmäsäiliön lämpötila on $T_C$, niin tehokertoimien maksimiarvot määräytyvät epäyhtälöistä:

$\epsilon_P \leq \frac{T_H}{T_H-T_C}, \epsilon_R \leq \frac{T_C}{T_H-T_C}$

Laskukaavoista nähdään, että tehokerroin on suurimmillaan silloin, kun kuuma- ja kylmäsäiliön välinen lämpötilaero on mahdollisimman pieni. Lisäksi tehokertoimille voidaan johtaa kaava $\epsilon_P=\epsilon_R+1$.

:::{admonition} Kaavan johtaminen
:class: tip, dropdown

$\epsilon_P=\frac{Q_H}{Q_H-Q_C}=\frac{Q_C+Q_H-Q_C}{Q_H-Q_C}=\frac{Q_C}{Q_H-Q_C}+\frac{Q_H-Q_C}{Q_H-Q_C}=\epsilon_R+1$

:::


## Jäähdytyskoneet ja energian säilyminen

Aineen sisäenergia $U$, lämpöenergia $Q$, paine $p$ ja tilavuus $V$ yhdistyvät toisiinsa seuraavan säännön mukaisesti:

$\Delta U = Q+p\Delta V$,

joka voidaan esittää myös muodossa 

$Q=\Delta U + p\Delta V$. 

Edellisellä laskukaavalla voidaan tarkastella jäähdytyskoneiden energiankulutusta. Otetaan käyttöön vielä apusuure entalpia $H$. Sitä käytetään paljon mm. kemiassa laskuissa, jossa aineen lämpötila muuttuu reaktiossa. Entalpia määritellään kaasun sisäenergia $U$, paineen $p$ ja tilavuuden $V$ avulla seuraavasti: $H=U+pV$. Entalpiaa käytetään laskuissa silloin, kun lasku suoritetaan Mollier-diagrammin avulla.

::::{admonition} Esimerkki

Jääkaapin höyrystimessä, jääkaapin sisäpuolella kiertävissä putkissa, lämpötila on 5 Celsius-astetta. Paine höyrystimessä on 363 kPa. Höyrystimen läpi kulkiessaan suurin osa kylmäaineesta höyrystyy siten, että kaasun tilavuus muuttuu 0.2202 kuutiometristä 0.4513 kuutiometriin. Samalla kaasun sisäenergia muuttuu arvosta 1005 kJ arvoon 1651 kJ.

Lauhduttimessa lämpötila on 80 Celsius-astetta, ja paine on 2305 kPa. Kun suurin osa kaasusta nesteytyy, niin kaasun tilavuus pienenee 0.0682 kuutiometristä 0.00946 kuutiometriin, ja sen sisäenergia muuttuu 1963 kilojoulesta 1171 kilojouleen.

a) Laske kaapin huoneeseen luovuttama lämpöenergia $Q_H$.

b) Laske jääkaapin sisältä otettu lämpöenergia $Q_C$.

c) Kuinka suuren työn $W$ kompressorin moottori tekee yhden syklin aikana?

d) Mikä on kaapin kylmäkerroin edellisten kohtien perusteella?

e) Mikä olisi samalla lämpötilavälillä toimivan Carnot'n koneen tehokerroin?

:::{admonition} Ratkaisu
:class: tip, dropdown

a) Lauhduttimessa huoneeseen luovutettu lämpöenergia on noin 927 kJ, joka saadaan seuraavasti:

$Q_H=\Delta U + p\Delta V$

$Q_H = (1171-1963)~\text{kJ}+ ...$

$ ... 2305000~\text{Pa}\cdot(0.00946-0.0682)~\text{m}^3=-927000~\text{J}$ 

b) Höyrystimessä kaapista otettu lämpöenergia on noin 730 kJ:

$Q_C=\Delta U + p\Delta V $

$Q_C = (1651-1005)~\text{kJ}+ ...$

$... 363000~\text{Pa}\cdot(0.4513-0.2022)~\text{m}^3=730000~\text{J}$

c) Kompressorin tekemä työ on edellisten arvojen erotus:

$W=927~\text{kJ}-730~\text{kJ}=197~\text{kJ}$

d) Kylmäkerroin on

$\epsilon_R=\frac{Q_C}{W}=\frac{730~\text{kJ}}{197~\text{kJ}}=3.696$

e) Teoreettinen maksimi olisi 

$\epsilon_R \leq \frac{(80+273)~\text{K}}{75~\text{K}}=3.71$

:::

::::

## Kylmäaineet

Jäähdytyskoneissa käytetään erilaisia kylmäaineita. Niiden ympäristövaikutuksia kuvataan luvuilla ODP ja GWP. 
- ODP (ozone depletion potential): vaikutus yläilmakehän otsonin hajoamiseen
- GWP (global warming potential): vaikutus ilmaston lämpenemiseen

Aluksi kylmäaineina käytettiin ns. freoneja. Ne ovat aineita, jotka sisältävät klooria, fluoria ja hiiltä. Näiden aineiden englanninkielisistä nimistä (chlorine, fluorine, carbon) tulee aineryhmän toinen nimi CFC-yhdisteet. Näillä aineilla oli hyvin suuri ODP ja myös suuri GWP. Nämä aineet ovat kemiallisesti erittäin kestäviä, joten ne nousevat ilmakehässä aina vain ylemmäs ja ylemmäs ja voivat kiertää siellä vuosikymmeniä. Vasta auringon ultraviolettisäteily hajottaa näitä molekyylejä. Niiden sisältämä kloori reagoi kiivaasti yläilmankehän otsonimolekyylien $\text{O}_3$ kanssa hajottaen niitä yksittäiseksi happiatomeiksi, jotka edelleen muuttuvat tavalliseksi hapeksi $\text{O}_2$. Yläilmakehän otsoni on tärkeää, sillä se suojaa maapalloa liialliselta ultraviolettisäteilyä. CFC-yhdisteiden käyttöä on rajoitettu vuodesta 1987 alkaen Montrealin sopimuksella.

Toisen sukupolven kylmäaineet olivat ns. HFC-yhdisteitä, joissa CFC-yhdisteiden kloorin paikalle vaihdettiin vety (kemiallinen merkki H). Näiden aineiden ODP on nolla, mutta GWP suuri. Lämpöpumpuissa käytetään yleisesti tähän aineryhmään kuuluvaa difluorieteeniä.

Nykyään on alettu käyttää kylmäaineina luonnonmukaisia hiilivetyjä, kuten etaania, propaania, butaania ja pentaania. Näiden ODP on nolla ja GWP on pieni. Lisäksi isoissa kylmälaitoksissa on jo kymmeniä vuosia käytetty yleisesti ammoniakkia, joka ei tuhoa otsonikerrosta eikä ole kasvihuonekaasukaan. Euroopan unionissa kylmälaitteiden suurimmat sallitut ODP- ja GWP-arvot on määritelty direktiiveillä.