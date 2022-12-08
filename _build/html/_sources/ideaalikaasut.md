# Ideaalikaasut

Ideaalikaasuilla tarkoitetaan kaasuja, joiden rakenneosat vuorovaikuttavat toisten kanssa vain täysin kimmoisten törmäysten yhteydessä. Lisäksi ideaalikaasun rakenneosien ajatellaan olevan äärettömän pieniä. Ideaalikaasua ei ole oikeasti olemassa, mutta useimpia kaasuja voidaan kuvailla riittävän tarkasti ideaalikaasun laskukaavoilla. Todellisista kaasuista lähimpänä ideaalikaasua ovat vety ja helium.

Kaasun tilaa kuvaavat suureet:
- paine $p$ 
- tilavuus $V$ 
- lämpötila $T$

Kaasun tilaa kuvaavat suureet noudattavat kaasulakia:

$pV=nRT$,

missä $R = 8.31~\text{J/(mol K)}$ on kaasuvakio ja $n$ on kaasun määrä mooleina.

Reaalikaasuille eli todellisille kaasuille on olemassa oma tilanyhtälönsä. Se on nimeltään van der Waalsin yhtälö ja näyttää tältä:

$\left[p+a\left(\frac{n}{V}\right)^2\right](V-nb)=nRT$,

missä $a$ on kaasun molekyylien väliseen vuorovaikutukseen liittyvä kerroin, ja $b$ on kaasumolekyylien kokoon liittyvä kerroin. Van der Waalsin lakia voi käyttää valmiilla [laskurilla](https://www.webqc.org/van_der_waals_gas_law.html).

## Ainemäärä

Kaasulaeissa esiintyvä suure $n$ on nimeltään ainemäärä. Se kertoo hiukkasten kappalemäärän. Ainemäärää käytetään suureena esimerkiksi verikokeissa (normaali kolesteriarvo on luokkaa 5 millimoolia yhdessä litrassa verta).

Ainemäärän yksikkö on mooli (lyhenne mol). Yksi mooli tarkoittaa sitä, että aineen perusosasia on $6\cdot 10^{23}$ kappaletta. Kappalemäärä on nimeltään Avogadron vakio $N_A$. Luku on peräisin hiilen ominaisuuksista: 1800-luvulla pystyttiin selvittämään, että 12 grammaa hiiltä sisältää yhden moolin verran hiiliatomeja. 

Rakenneosat, joita ainemäärässä lasketaan, ovat aineesta riippuen yksittäisiä atomeja tai useasta atomista koostuvia molekyylejä. Kukaan ei tietenkään pysty laskemaan esimerkiksi huoneilmassa olevien molekyylien lukumäärää. Ainemäärä onkin määritelty seuraavasti:

$n=\frac{m}{M}$,

missä $m$ on aineen massa, ja $M$ on aineen rakenneosasen moolimassa. Luku $M$ kertoo, kuinka monta grammaa painaa yksi mooli kyseistä ainetta. Moolimassat löytyvät [jaksollisesta järjestelmästä](https://ptable.com/?lang=fi#Ominaisuudet). Useasta atomista koostuvan atomin moolimassan saa siten, että laskee yhteen molekyylissä olevien atomien moolimassat.

::::{admonition} Esimerkki

a) Kuinka monta moolia on 50 grammaa kultaa (Au)?

b) Kuinka monta moolia on 100 grammaa vettä ($\text{H}_2\text{O}$)?

c) Kuinka monta grammaa on 2 moolia rautaa (Fe)?

d) Kuinka monta grammaa on 8 moolia hiilidioksidia $\text{CO}_2$?

:::{admonition} Ratkaisu
:class: tip, dropdown

a) Kullan moolimassa on 196.97 g/mol. Ainemäärä on $n=\frac{50~\text{g}}{196.97~\text{g/mol}}=0.25~\text{mol}$.

b) Vedyn (H) moolimassa on 1.008 g/mol ja hapen (O) moolimassa on 15.999 g/mol. Vesimolekyylissä on kaksi vetyatomia ja yksi happiatomi. Veden moolimassa on siis $M=(2\cdot 1.008+15.999)~\text{g/mol} = 18.015~\text{g/mol}$.

Ainemäärä on $n=\frac{100~\text{g}}{18.015~\text{g/mol}}=5.6~\text{mol}$.

c) Raudan moolimassa on 55.845 g/mol. Ratkaistaan ainemäärän määritelmästä massa $m$ ja sijoitetaan arvot:

$m=nM=2~\text{mol}\cdot 55.845~\frac{\text{g}}{\text{mol}} = 112~\text{mol}$

d) Hiilen (C) moolimassa on 12.011 g/mol ja hapen (O) moolimassa on 15.999 g/mol. Hiilidioksidimolekyylissä on yksi hiiliatomia ja kaksi happiatomia. Sen moolimassa on siis $M=(12.011+2\cdot 15.999)~\text{g/mol} = 44.009~\text{g/mol}$. Massa on

$m=nM=8~\text{mol}\cdot 44.009~\frac{\text{g}}{\text{mol}} = 352~\text{mol}$

:::

::::

Rakennustekniikassa kaasu, jota tarkastellaan, on yleensä tavallista ilmaa. Ilman koostumus on suunnilleen seuraava:
- typpeä $\text{N}_2$ 78 %
- happea $\text{O}_2$ 21 %
- hiilidioksidia $\text{CO}_2$ 0.04 %
- vesihöyryä $\text{H}_2\text{O}$ 0-5 %

Ilman komponenteista hiilidioksidilla on suurin moolimassa. Siksi hiilidioksidi painuu alimmaksi, rakennusten kellareihin. Vesihöyry on moolimassaltaan kevyintä ja nousee siksi ilmakehässä ylöpäin.

Käytännössä ilman moolimassa voidaan laskea prosenttiosuuksilla painotettuna summana, ja käyttäen alkuaineiden moolimassoille pyöristettyjä arvoa, seuraavasti:

$M=0.78\cdot M(\text{N}_2) + 0.22\cdot M(\text{O}_2) = 0.78\cdot (2\cdot 14)~\text{g/mol}+0.22\cdot (2\cdot 16)~\text{g/mol} = 29~\text{g/mol}$

## Kaasulain käyttöä

Tarkastellaan esimerkkejä kaasulain $pV=nRT$ käytöstä.

**Normaaliolosuhteet**

Normaaliolosuhteilla tarkoitetaan olosuhteita, joissa lämpötila $T$ ja paine $p$ pysyvät niinsanotusti normaaleina. Normaaliolosuhteista käytetäänkin lyhennettä NTP-olosuhteet (normal temperature and pressure). On olemassa monta eri määritelmää normaaliolosuhteille ([Wikipedia](https://fi.wikipedia.org/wiki/NTP)). Käytetään tällä opintojaksolla määritelmää: NTP-olosuhteissa lämpötila on $T=273.15~\text{K}$ ja paine on $p=101300~\text{Pa}$.

Kaasulaista $pV=nRT$ voidaan ratkaista kaasun viemä tilavuus, kun olosuhteet ja ainemäärä tiedetään:

$V=\frac{nRT}{p}$

Sijoitetaan laskukaavaan normaaliolosuhteet sekä ainemäärä $n=1~\text{mol}$:

$V=\frac{1~\text{mol} \cdot 8.31~\text{J/(mol K)} \cdot 273.15~\text{K}}{101300~\text{Pa}} = 0.0224~\text{m}^3$

Toisin sanoen: yksi mooli ideaalikaasua vie NTP-olosuhteissa 22.4 litran tilavuuden. Edelleen jos kaasua on $n$ moolia, saadaan tulos:

$V_n=n\cdot 22.4~\frac{\text{l}}{\text{mol}}$

::::{admonition} Esimerkki

Kuinka suuren tilavuuden vie 5000 grammaa hiilidioksidia NTP-oloissa?

:::{admonition} Ratkaisu
:class: tip, dropdown

Lasketaan ensin hiilidioksidin ainemäärä. Aiemmin todettiin, että hiilidioksidin moolimassa on noin 44 g/mol. Siis ainemäärä on

$n=\frac{5000~\text{g}}{44~\text{g/mol}} = 114~\text{mol}$

Tilavuus on siis

$V_n=114~\text{mol} \cdot 22.4~\frac{\text{l}}{\text{mol}} = 2554~\text{l}$

:::

::::

**Kaasulain käyttöä**

Kaavaa $pV=nRT$ voidaan käyttää kaikissa olosuhteissa. 

Voidaan esimerkiksi laskea ideaalikaasun moolitilavuus huoneenlämpötilassa (20 astetta):

$V=\frac{1~\text{mol} \cdot 8.31~\text{J/(mol K)} \cdot 293.15~\text{K}}{101300~\text{Pa}} = 0.0240~\text{m}^3$

Mikäli muiden suureiden arvot tunnetaan, niin yhtälöstä voidaan ratkaista 
- paine $p=\frac{nRT}{V}$, 
- ainemäärä $n=\frac{pV}{RT}$,
- lämpötila $T=\frac{pV}{nR}$.


::::{admonition} Esimerkki

Kuinka paljon huoneessa on ilmaa, kun huoneen mitat ovat 3.5 m, 4.0 m ja 3.0 m, ja huoneilman lämpötila on 22 astetta? Oletetaan, että paine on normaali ilmanpaine 101 300 Pa. Laske ensin ainemäärä ja sitten massa.

:::{admonition} Ratkaisu
:class: tip, dropdown

Nyt tiedossa on paine $p$, tilavuus $V$ (koko huoneen tilavuus) ja lämpötila $T$. Myös kaasuvakio $R$ on tiedossa. Ratkaistaan siis ensin ainemäärä

$n=\frac{101300~\text{Pa}\cdot(3.5\cdot 4.0\cdot 3.0)~\text{m}^3}{8.31~\text{J/(mol K)} \cdot (273.15+22)~\text{K}} = 1735~\text{mol}$

Ilman moolimassaksi laskettiin aiemmin 29 g/mol. Siispä huoneessa olevan ilman massa on

$m=n1735~\text{mol}\cdot 29\text{g/mol} = 50315~\text{g}$ eli noin 50 kg.

:::

::::

**Ilman tiheys**

Ilman (ja minkä tahansa muunkin aineen) tiheys $\rho$ on määritelty: $\rho=\frac{m}{V}$, eli tiheys on massa $m$ jaettuna tilavuudella $V$. Toisaalta massan voi ilmaista myös ainemäärän $n$ ja moolimassan $M$ avulla: $m=nM$. Edelleen kaasun tilavuuksi saadaan kaasulaista $V=\frac{nRT}{p}$. Tiheydelle voidaan näin muodostaa laskukaava:

$\rho=\frac{nM}{\frac{nRT}{p}}$ ja tämä sievenee muotoon

$\rho = \frac{pM}{RT}$

Ilman tiheys voidaan siis laskea halutussa lämpötilassa ja paineessa.

::::{admonition} Esimerkki

Laske ilman tiheys 

a) normaalipaineessa, 0 asteen lämpötilassa,

b) normaalipaineessa, 30 asteen lämpötilassa,

c) lentokoneen lentokorkeudella, jossa lämpötila on noin -50 astetta ja paine noin 23 000 Pa?

:::{admonition} Ratkaisu
:class: tip, dropdown

a) $\rho=\frac{101300~\text{P}\cdot 29~\text{g/mol}}{8.31~\text{J/(mol K)} \cdot 273.15~\text{K}} = 1.29~\frac{\text{kg}}{\text{m}^3}$

b) $\rho=\frac{101300~\text{P}\cdot 29~\text{g/mol}}{8.31~\text{J/(mol K)} \cdot 303.15~\text{K}} = 1.17~\frac{\text{kg}}{\text{m}^3}$

c) $\rho=\frac{23000~\text{P}\cdot 29~\text{g/mol}}{8.31~\text{J/(mol K)} \cdot 223.15~\text{K}} = 0.35~\frac{\text{kg}}{\text{m}^3}$


:::

::::


## Kineettinen kaasuteoria

Kineettisen kaasuteorian mukaan lämpö on kaasuhiukkasten liike-energiaa. Yksittäisen kaasumolekyylin keskimääräiseksi liike-energiaksi on mahdollista johtaa kaava:

$E=\frac{3}{2}kT$,

missä $k=\frac{R}{N_A}=1.38\cdot 10^{-23}~\frac{\text{J}}{\text{K}}$ on nimeltään Boltzmannin vakio.

Lämpö on siis kirjaimellisesti molekyylien liike-energiaa. Pienin mahdollinen lämpötila on 0 K, koska liike-energia ei voi olla negatiivista
Lämpötilassa 0 K kaasumolekyylit astiassa eivät enää liikkuisi ollenkaan. Lämpötilaa 0 K on mahdoton saavuttaa, mutta Suomessakin on päästy
hyvin lähelle (miljoonasosa-asteen päähän).

:::{admonition} Kaavan johtaminen
:class: tip, dropdown

- Oletetaan, että kaasumolekyylin massa on $m$. Molekyyli liikkuu vaakasuuntaisella nopeudella $v_x$ säiliössä, jonka pituus on $x$ ja seinän pinta-ala $A$.

- Kun molekyyli törmää astian seinään, se aiheuttaa seinään paineen $p=F/A$.

- Paineessa esiintyvä voima $F$ lasketaan törmäysliikkeessä tunnetulla impulssiperiaatteella: $2mv_x=F\Delta t$, missä $\Delta t$ on kahden törmäyksen välinen aika. Impulssiperiaatteen mukaan molekyylin liikemäärän muutos on yhtä suuri kuin voiman ja törmäysajan tulo. Liikemäärä puolestaan on massan ja nopeuden tulo. Koska molekyylin nopeus muuttuu vastakkaismerkkiseksi, mutta sen suuruus ei muutu, niin liikemäärän muutos on $2mv_x$.

- Aikaväliksi $\Delta t$ laskukaavaan laitetaan $\Delta t= \frac{2x}{v_x}$, eli kahden törmäyksen välillä kuluva aika

- Voimaksi saadaan siis $F=\frac{2m v_x}{\Delta t}=\frac{2 m v_x}{2x/v_x} = \frac{mv_x^2}{x}$

- Seinään kohdistuva paine on $p=\frac{F}{A}=\frac{mv_x^2}{Ax}$

- Säiliön tilavuus on $V=Ax$, joten $p=\frac{mv_x^2}{V}$

- Kaasumolekyyli liikkuu kolmessa ulottuvuuksissa nopeuksilla $v_x, v_y, v_z$. Kokonaisnopeus $v$ saadaan yhtälöstä $v^2=v_x^2+v_y^2+v_z^2$. Koska liikkeet kaikissa suunnissa ovat yhtä todennäköisiä, niin $v_x^2=\frac{1}{3}v^2$.

- Siis yhden molekyylin aiheuttamaksi paineeksi saadaan $p=\frac{mv^2}{3V}$

- Kun molekyylejä on $N$ kappaletta, niin niiden aiheuttama kokonaispaine on $p=\frac{Nmv^2}{3V}$

- Muokataan yhtälö muotoon $pV=\frac{Nmv^2}{3}$ ja verrataan sitä kaasulakiin $pV=nRT$. Koska vasemmalla puolella on molemmissa sama lauseke $pV$, niin myös oikeiden puolien pitää olla samat:

$\frac{Nmv^2}{3}=nRT$

- Ratkaistaan tästä $mv^2=\frac{3VnRT}{N}$. Mekaniikassa liike-energia on määritelty muodossa $E=\frac{1}{2}mv^2$, joten tässä tapauksessa liike-energia olisi 

$E=\frac{1}{2}\frac{3VnRT}{N}=\frac{3}{2}\frac{VnRT}{N}$

- Ainemäärä voidaan ilmaista hiukkasmäärän $N$ ja Avogadron vakion $N_A$ avulla: $n=\frac{N}{N_A}$, joten $\frac{n}{N}=\frac{1}{N_A}$, jolloin liike-energian kaava sievenee muotoon 

$E=\frac{3}{2}\frac{VRT}{N_A}$ eli $E=\frac{3}{2}kVT$, missä $k=\frac{R}{N_A}$.

:::

**Kaasun sisäenergia**

Yhden molekyylin liike-energia on siis $E=\frac{3}{2}kT$. Jos kaasua on $n$ moolia, niin kaasuhiukkasia on $N=n N_A$ kappaletta, ja tällöin koko kaasumäärän liike-energiaksi voidaan johtaa

$U=\frac{3}{2}nRT$.

Tätä suuretta sanotaan kaasun sisäenergiaksi.

:::{admonition} Esimerkki

Kuinka suuri sisäenergia on 1 moolilla (eli noin 22.4 litralla) ideaalikaasua NTP-olosuhteissa?

:::{admonition} Ratkaisu
:class: tip, dropdown

$U = 1~\text{mol}\cdot \frac{3}{2} \cdot 8.31~\text{J/(mol K)} \cdot 273~\text{K} = 3403~\text{J} = 3.4~\text{kJ}$

:::

**Kaasun tekemä työ**

Yleisesti mekaniikassa ajatellaan, että kun voima $F$ siirtää kappaletta matkan $\Delta s$, niin voima tekee työn $W=F \Delta s$. Oletetaan nyt, että kaasu on sylinterimäisessä astiassa, jossa se voi laajentua työntämällä astian kannen paikalla olevaa mäntää. Kun kaasu laajenee (lämpötilan noustessa tai paineen pienentyessä), se tällöin tekee mekaanisen työn $W=F\Delta s$, missä voiman $F$ paikalle tulee nyt paineen määritelmästä $F=pA$. Siis kaasun tekemä työ on

$W=pA\Delta s$.

Toisaalta samalla kaasun tilavuus muuttuu määrän $\Delta V=A \Delta s$. Kaasun tekemä työ voidaan siis kirjoittaa muodossa

$W=p \Delta V$.

Energian säilymislaki koskee myös lämpöenergiaa: Systeemin sisäenergian muutos = siihen tuotu lämpöenergia + systeemiin tehty työ (esim. puristaminen). Tätä periaatetta sanotaan lämpöopin ensimmäiseksi pääsäännöksi, ja se kirjoitetaan yhtälönä muodossa

$\Delta U = Q + W = Q + p \Delta V$